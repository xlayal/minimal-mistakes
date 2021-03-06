---
title:  "简单的SVG效果：沿运动路径移动、旋转并缩放的特效"
header:
  overlay_image: images/unsplash-image-6.JPG
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  cta_label: "Mre Info"
  cta_url: "https://unsplash.com"
---

{% include base_path %}

{% include toc title="目录" %}

### 今天来给大家分享一下如何制作间的SVG动画效果——沿运动路径移动、旋转并缩放的特效
### 第一步：（首先使用到的工具是AI）打开AI并且新建一个文件
![svg1_1.png](https://s20.postimg.cc/4rpf6myfh/svg1_1.png)
### 第二步：简单绘制一个多边形，填充颜色
![svg1_2.png](https://s20.postimg.cc/hj3ld5fx9/svg1_2.png)
### 第三步：绘制完成后，另存为文件，记得要修改保存类型，要修改为SVG
![svg1_3.png](https://s20.postimg.cc/f1ru5wylp/svg1_3.png)
### 第四步：点击保存后，会弹出一个窗口，点击svg代码
![svg1_4.png](https://s20.postimg.cc/xvdn2g6z1/svg1_4.png)
### 第五步：就可以直接看到你绘制一个的SVG图的代码～
![svg1_5.png](https://s20.postimg.cc/tz0b6gtp9/svg1_5.png)
### 第六步：将代码复制粘贴到html文档的<body>标签里
![svg1_6.png](https://i.loli.net/2018/07/08/5b41fdfb55c86.png)
### 第七步：在复制过来的内容里，添加SVG效果代码，就可以看到做出的图片的效果了
![svg1_7.png](https://i.loli.net/2018/07/08/5b41fe5b70768.png)

<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
	</head>
	<body>
<?xml version="1.0" encoding="utf-8"?>
<!-- Generator: Adobe Illustrator 22.0.0, SVG Export Plug-In . SVG Version: 6.00 Build 0)  -->
<svg version="1.1" id="图层_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
	 viewBox="0 0 1280 1024" style="enable-background:new 0 0 1280 1024;" xml:space="preserve">
<style type="text/css">
	.st0{fill:#E780AF;stroke:#000000;stroke-miterlimit:10;}
</style>
<path class="st0" d="M893.8,464.4l-133.9-49.2l38.5-137.4l-121.9,74l-83.4-115.7l-18.2,141.5l-142.5-7l99.3,102.4l-94.3,107.1
	l142-13.8l24.9,140.5l77.8-119.6l125.3,68.1l-45-135.4L893.8,464.4z M648.3,490.4c-30.5-6.2-20.8-53.5,9.6-47.3
	C688.5,449.3,678.8,496.6,648.3,490.4z"/>
	<animateMotion path="M 0 0 L 100 100" begin="1s" dur="5s" fill="freeze" />
      <animateTransform attributeName="transform" attributeType="XML" type="rotate" from="-30" to="0" begin="1s" dur="5s" fill="freeze" /> 
      <animateTransform attributeName="transform" attributeType="XML" type="scale" from="1" to="3" additive="sum" begin="1s" dur="5s" fill="freeze" 
</svg>
	</body>
</html>

