<script>
// 创建一个新的链接元素
var link = document.createElement('link');
// 设置链接的属性
link.href = 'https://cdn.qingyi-studio.top/PT-Serif/PT-Serif.css';
link.rel = 'stylesheet';
link.type = 'text/css';
link.crossOrigin = true;
// 将链接插入到页面的`<head>`中
document.head.appendChild(link);
// 修改页面的标题
document.title = "青衣工作室CDN";
// 在2秒后再次修改标题为“青衣工作室CDN”
setTimeout(function() {
  document.title = "青衣工作室CDN";
}, 2000);
</script>
# 无边框*iframe*

## 1.0.0

使用方法：

将`<link src="https://cdn.qingyi-studio.top/iframe-noborder/iframe-noborder@1.0.0.css" type="text/css">`添加到代码中。

### 单纯无边框

将*iframe*的*class*属性设为*noborder*。

例如`<iframe class="noborder" src="https://www.example.com/"></iframe>`

### 无边框+高度自适应

将*iframe*的*class*属性设为*noborder-heightauto*。

例如`<iframe class="noborder-heightauto" src="https://www.example.com/"></iframe>`

### 无边框+宽度自适应

将*iframe*的*class*属性设为*noborder-widthauto*。

例如`<iframe class="noborder-widthauto" src="https://www.example.com/"></iframe>`

### 无边框+高度宽度自适应

将*iframe*的*class*属性设为*noborder-allauto*。

例如`<iframe class="noborder-allauto" src="https://www.example.com/"></iframe>`

### 历史遗留bug

刚刚发现，这个不是自适应，其实是填满全屏，无所谓了，反正后面会在1.2.0优化好的。

<p style="text-align:right">
	——灰风
	<br>
	2024.1.19 14:25
</p>
## 1.1.0

将`<link src="https://cdn.qingyi-studio.top/iframe-noborder/iframe-noborder@1.1.0.css" type="text/css">`添加到代码中。

该版本优化了使用，简化了*css*文件代码

### 单纯无边框

将*iframe*的*class*属性设为*noborder*。

例如`<iframe class="noborder" src="https://www.example.com/"></iframe>`

### 无边框+高度自适应

将*iframe*的*class*属性设为*noborder*和*heightauto*。

例如`<iframe class="noborder heightauto" src="https://www.example.com/"></iframe>`

### 无边框+宽度自适应

将*iframe*的*class*属性设为*noborder*和*widthauto*。

例如`<iframe class="noborder widthauto" src="https://www.example.com/"></iframe>`

### 无边框+高度宽度自适应

将*iframe*的*class*属性设为*noborder*和*allauto*。

例如`<iframe class="noborder allauto" src="https://www.example.com/"></iframe>`

### 历史遗留bug

同1.0.0。

## 1.2.0

将`<link src="https://cdn.qingyi-studio.top/iframe-noborder/iframe-noborder@1.3.0.css" type="text/css">`添加到代码中。

该版本主要修复了前两个版本的历史遗留问题并优化了使用。

### 单纯无边框

将*iframe*的*class*属性设为*noborder*。

例如`<iframe class="noborder" src="https://www.example.com/"></iframe>`

### 无边框+高度

将*iframe*的*class*属性设为*noborder*和*h%*。

例如：

```html
<iframe class="noborder h5" src="https://www.example.com/"></iframe>
<iframe class="noborder h10" src="https://www.example.com/"></iframe>
<iframe class="noborder h50" src="https://www.example.com/"></iframe>
```

高度应为*h+5的倍数*，例如*h5*、*h10*、*h15*，以此类推至*h100*。

### 无边框+宽度

将*iframe*的*class*属性设为*noborder*和*w%*。

例如：

```html
<iframe class="noborder w5" src="https://www.example.com/"></iframe>
<iframe class="noborder w10" src="https://www.example.com/"></iframe>
<iframe class="noborder w50" src="https://www.example.com/"></iframe>
```

高度应为*w+5的倍数*，例如*w5*、*w10*、*w15*，以此类推至*w100*。

### 无边框+高度+宽度

将*iframe*的*class*属性设为*noborder*+*h%*+*w%*。

例如：

```html
<iframe class="noborder h5 w5" src="https://www.example.com/"></iframe>
<iframe class="noborder h10 w10" src="https://www.example.com/"></iframe>
<iframe class="noborder h50 w50" src="https://www.example.com/"></iframe>
```

如果需要宽高全部撑满屏幕，可使用以下快捷设置：

```html
<iframe class="noborder wh100" src="https://www.example.com/"></iframe>
```

## 2.0.0

将`<link src="https://cdn.qingyi-studio.top/iframe-noborder/2.0.0/iframe-noborder@2.0.0.css" type="text/css">`添加到代码中。

该版本使用*Sass*重写，优化了使用，细化了调整范围，限制了适用范围为含有*class*属性为*noborder*的*iframe*。

### 单纯无边框

将*iframe*的*class*属性设为*noborder*。

例如`<iframe class="noborder" src="https://www.example.com/"></iframe>`

### 无边框+高度

将*iframe*的*class*属性设为*noborder-h%*。

例如：

```html
<iframe class="noborder-h5" src="https://www.example.com/"></iframe>
<iframe class="noborder-h6" src="https://www.example.com/"></iframe>
<iframe class="noborder-h23" src="https://www.example.com/"></iframe>
```

高度应为*h+1的倍数*，例如*h5*、*h6*、*h23*，最大至*h100*。

### 无边框+宽度

将*iframe*的*class*属性设为*noborder-w%*。

例如：

```html
<iframe class="noborder-w5" src="https://www.example.com/"></iframe>
<iframe class="noborder-w7" src="https://www.example.com/"></iframe>
<iframe class="noborder-w39" src="https://www.example.com/"></iframe>
```

高度应为*w+1的倍数*，例如*w5*、*w7*、*w39*，最大至*w100*。

### 无边框+高度+宽度

将*iframe*的*class*属性设为*noborder-h%w%*或*noborder-w%h%*。

例如：

```html
<iframe class="noborder-w5h3" src="https://www.example.com/"></iframe>
<iframe class="noborder-h9w10" src="https://www.example.com/"></iframe>
```

如果需要宽高全部相等，可使用以下快捷设置：

```html
<iframe class="noborder wh13" src="https://www.example.com/"></iframe>
<iframe class="noborder wh56" src="https://www.example.com/"></iframe>
<iframe class="noborder wh79" src="https://www.example.com/"></iframe>
```

------

Theme: Typora - Newsprint
