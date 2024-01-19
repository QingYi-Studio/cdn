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

将`<link src="https://cdn.qingyi-studio.top/iframe-noborder/iframe-noborder@1.2.0.css" type="text/css">`添加到代码中。

该版本主要修复了前两个版本的历史遗留问题并优化了使用

## 2.0.0



Theme: Typora - Newsprint
