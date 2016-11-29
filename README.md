# Lazyload-Img
A try to lazyload single img

# zh-cn
_　图片出现在可视区域时将 data-src　赋值给他的 src　从而实现了图片的被动加载;
_  加入了节流函数，监听滚动条滚动行为并延迟调用懒加载函数，避免滚动时的卡顿效果;
_  后续考虑加入 getBoundingRect.top 或是　循环遍历 offsetTop　来尽可能地获取图片的真实高度;
