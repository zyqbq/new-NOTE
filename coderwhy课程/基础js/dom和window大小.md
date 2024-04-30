### dom元素的大小

divEl.clientWidth 元素内容宽度+padding(不含滚动条)

divEl.offWidth 元素所有宽度 margin以外的宽度 包含滚动条(滚动条在padding中)

divEl.offsetTop 相对于父元素(包含块)上方的距离 子元素border之外开始计算

divEl.scrollHeight 可滚动区域的高度

divEl.scrollTop 已经滚动过的高度

divEl.clientTop boder-top的宽度

### window的大小

window.ourWidth 浏览器的宽度 包含标签页工具栏等

window.innnerWidth 视口宽度(内容区域包含滚动条)

window.scrollX x轴滚动的大小

window.scrollBy(0,100) 向下滚动100px(可以多次滚动)

window.scrollTo(0,100) 向下滚动到100px的位置