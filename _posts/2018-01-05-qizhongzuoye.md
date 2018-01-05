---
layout: article 
title: “web笔记” 
categories:  rwd
image:
    teaser: web1.jpg
    feature: web1.jpg
---
<body>
<div class="flexbox-container">
	<div class="left" >
		<p>Hue 色调/色相</p>
			<span class="Hue"></span>
			<span class="Hue"></span>
			<span class="Hue"></span>
			<span class="Hue"></span>
			<span class="Hue"></span>
			<span class="Hue"></span>
			<span class="Hue"></span>
			<span class="Hue"></span>
			<span class="Hue"></span>
			<span class="Hue"></span>
			<span class="Hue"></span>
			<span class="Hue"></span>
		<p>Saturation 饱合度</p>
			<span class="Saturation"></span>
			<span class="Saturation"></span>
			<span class="Saturation"></span>
			<span class="Saturation"></span>
			<span class="Saturation"></span>
			<span class="Saturation"></span>
			<span class="Saturation"></span>
			<span class="Saturation"></span>
			<span class="Saturation"></span>
			<span class="Saturation"></span>
			<span class="Saturation"></span>
			<span class="Saturation"></span>
		<p>Brightness 明亮度/明度/亮度</p>
			<span class="Brightness"></span>
			<span class="Brightness"></span>
			<span class="Brightness"></span>
			<span class="Brightness"></span>
			<span class="Brightness"></span>
			<span class="Brightness"></span>
			<span class="Brightness"></span>
			<span class="Brightness"></span>
			<span class="Brightness"></span>
			<span class="Brightness"></span>
			<span class="Brightness"></span>
			<span class="Brightness"></span>
			
		<br/><br/><br/>
		<img src="颜色不平等.jpg" alt="颜色不平等">	
		<p>同一照明度下多种颜色的相对亮度不一（黄色的亮度几乎是蓝色的4倍）</p>
	</div>
	<div class="right">
	<div class="w">可读性的最佳组合是白底黑字</div>
	<div class="s">黑字白底的可读性也不错</div>
	<div class="g">白底上的明亮颜色像黄色会消失看不清</div>
	<div class="f">白底上的暗颜色像蓝色或红色</span>效果较佳</div>
	<div class="o">渐变背景极易制造可读性问题，是因为部份文字将因较弱的对比使可读性降低。若非用渐变背景不可，请使用黑色字，并不要在背景使用暗色</div>
	<div class="r">有些许红绿色盲的10%男性读者，会觉得此段落很难读，特别是红色和绿色的明亮度很接近的状况。不要在文本上单靠颜色来产生对比。</div>
	</div>
</div>
<style type="text/css">
span {
	display: inline-block;
	height: 2rem;
	width: 2rem;
	background-color: white;
}
.flexbox-container{
	background-color: rgb(255, 255, 255);
	display: -ms-flex;
	display: -webkit-flex;
	display: flex;
	margin: 60px;
	padding: 50px;
}
.flexbox-container > .left {
	width: 70%;
	padding: 0 28px;
	border-right: 2px solid black;
}
.flexbox-container > .right {
	width: 45%;
	padding: 0 28px;
}
.left>span:nth-child(2) {
	background-color: rgb(237, 40, 49);
}
.left>span:nth-child(3) {
	background-color: rgb(236, 50, 149);
}
.left>span:nth-child(4) {
	background-color: rgb(179, 81, 158);	
}
.left>span:nth-child(5) {
	background-color: rgb(101, 82, 163);	
}
.left>span:nth-child(6) {
	background-color: rgb(53, 92, 171);	
}
.left>span:nth-child(7) {
	background-color: rgb(1, 182, 237);	
}
.left>span:nth-child(8) {
	background-color: rgb(0, 170, 137);	
}
.left>span:nth-child(9) {
	background-color: rgb(0, 166, 82);	
}
.left>span:nth-child(10) {
	background-color: rgb(32, 177, 76);	
}
.left>span:nth-child(11) {
	background-color: rgb(230, 230, 22);	
}
.left>span:nth-child(12) {
	background-color: rgb(243, 123, 37);	
}
.left>span:nth-child(13) {
	background-color: rgb(238, 44, 45);	
}
.left>span:nth-child(15) {
	background-color: rgba(48, 95, 173,0.087);	
}
.left>span:nth-child(16) {
	background-color: rgba(48, 95, 173,0.17);	
}
.left>span:nth-child(17) {
	background-color: rgba(48, 95, 173,0.253);	
}
.left>span:nth-child(18) {
	background-color: rgba(48, 95, 173,0.336);	
}
.left>span:nth-child(19) {
	background-color: rgba(48, 95, 173,0.419);	
}
.left>span:nth-child(20) {
	background-color: rgba(48, 95, 173,0.502);	
}
.left>span:nth-child(21) {
	background-color: rgba(48, 95, 173,0.585);	
}
.left>span:nth-child(22) {
	background-color: rgba(48, 95, 173,0.668);	
}
.left>span:nth-child(23) {
	background-color: rgba(48, 95, 173,0.751);	
}
.left>span:nth-child(24) {
	background-color: rgba(48, 95, 173,0.834);	
}
.left>span:nth-child(25) {
	background-color: rgba(48, 95, 173,0.917);	
}
.left>span:nth-child(26) {
	background-color: rgb(48, 95, 173);	
}
.left>span:nth-child(28) {
	background-color: hsl(214, 47.4%, 54.5%);	
}
.left>span:nth-child(29) {
	background-color: hsl(214, 47.4%, 49.54%);	
}
.left>span:nth-child(30) {
	background-color: hsl(214, 47.4%, 44.58%);	
}
.left>span:nth-child(31) {
	background-color: hsl(214, 47.4%, 39.62%);	
}
.left>span:nth-child(30) {
	background-color: hsl(214, 47.4%, 44.58%);	
}
.left>span:nth-child(31) {
	background-color: hsl(214, 47.4%, 39.62%);	
}
.left>span:nth-child(32) {
	background-color: hsl(214, 47.4%, 34.66%);	
}
.left>span:nth-child(33) {
	background-color: hsl(214, 47.4%, 29.7%);	
}
.left>span:nth-child(34) {
	background-color: hsl(214, 47.4%, 24.74%);	
}
.left>span:nth-child(35) {
	background-color: hsl(214, 47.4%, 19.78%);	
}
.left>span:nth-child(36) {
	background-color: hsl(214, 47.4%, 14.82%);	
}
.left>span:nth-child(37) {
	background-color: hsl(214, 47.4%, 9.86%);	
}
.left>span:nth-child(38) {
	background-color: hsl(214, 47.4%, 4.9%);	
}
.left>span:nth-child(39) {
	background-color: hsl(214, 47.4%, 0%);	
}


/* span:nth-child(2n+3) {
	background-color: #f90;
	border-radius: 50%;
} */

/* span:nth-child(-2n+3) {
	background-color: #f90;
	border-radius: 50%;
} */

.right > div {
	max-width:100%;
	display: block;
	padding: 1.2rem 2.2rem;
	border: 1px dashed black;
}
.left > p{
	padding: 0.1rem ;
	margin: 1.2rem 0 0;
	}
.w {
	display: block;
	padding: 1.2rem 2.2rem;
	background-color: rgb(255, 255, 255);
	color:rgb(0,0,0);
	
}
.s {
	display: block;
	padding: 1.2rem 2.2rem;
	background-color: rgb(0, 0, 0);
	color:rgb(255,255,255);
}

.g {
	color:#FFFF00;
}

.f {
	color:#0000FF;
}

.o {
	background: linear-gradient(#2B4A94, #ffffff);
	color:rgb(255,255,255);
}

.r {
	background-color: rgb(100,190,110);
	color:rgb(160,150,91);
}
</style>
</body>