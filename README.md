# yeliex.Carousel
一个简单的Carousel Jquery插件

## 插件信息
### 作者: yeliex (yeliex.com)
### 插件网站: work.yeliex.com/carousel
### 版本: 1.4
### 更新: 2015-09-21

## 预览

## 用法

	引入依赖文件: basic.css,yCarousel.min.js

	<div class="wrapper"> // 需要一个容器
		<div class="carousel" data-content="true"> // 插件会检测页面中的每一个carousel,所以这个样式是必须的.data-content=true代表需要文本显示的遮罩层
        	<div class="list active" data-img="img1" data-content="标题1/内容1" data-btn="按钮1"></div> // list样式代表这是一个子项,active代表页面加载的时候从这个项目开始显示.active不强制加在第一个上面,但只能有一个.会从带有active的项目开始循环
        	<div class="list" data-img="img2" data-link='#' data-content="标题2/内容2" data-btn="按钮2"></div> // data-img中的内容是图片的地址
        	<div class="list" data-img="img3" data-link='#' data-content="标题3/内容3" data-btn="按钮3"></div> // data-link中的内容是链接地址,如果不需要点击以后打开新页面则留空/不填
        	<div class="list" data-img="img4" data-link='#' data-content="标题4/内容4" data-btn="按钮4"></div> // 这里的data-content代表要在图片上显示的内容,标题/内容以"/"分割
					<div class="list" data-img="img5" data-link='#' data-content="标题5/内容5" data-btn="按钮5"></div> // 如果需要加上按钮,需要加上data-btn参数,内容为显示的按钮内容.目前需要自定义按钮样式
    	</div>
	</div>
	后面会有计划加入对html的元素支持,目前没有这个需求:)
