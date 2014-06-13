# HTML5:一个全新的视觉媒介

从静态页面，表单，提交按钮开始，HTML已经发展了很长时间。在2000年代早期，浏览器通过Ajax技术来动态的修改页面的某一部分来实现富交互。然而，通过这种方式修改页面大大受限于HTML和CSS的图形特性。如果一个开发者希望突破这些限制，他不得不采用一些媒体插件比如说Flash和QuickTime。

整个2000年代基本就是这个现状，但是最近几年情况发生了改观。在这段时期开发的几个先进浏览器开始引入HTML5.通过HTML5，浏览器变成了可以运行复杂应用的平台，其特性和性能可以媲美原生应用。HTML5对原来的HTML标准作了大量的修正，包括语法简化，新的JavaScript语言特性以及应用编程接口，移动能力，以及跨越式的多媒体支持。HTML5平台的核心包含了一系列高级的图形图像技术，这些特性正是我们本书所关注的：

* WebGL 通过JavaScript在3D渲染的时候做硬件加速。WebGL基于久经考验的图形图像API OpenGL，WebGL已经成为几乎所有的桌面浏览器的标准支持，同时更多的移动浏览器也开始支持它。
* CSS3 3D变形，变换以及高级页面效果的定制化滤镜。CSS经过过去的几年发展现如今包含了通过样式表语言就能控制的硬件加速3D渲染和动画特性。
* Canvas元素和它的2D绘制内容API。这一特性被浏览器广泛支持，相关的JavaScript API允许开发者在DOM元素的表面绘制随意的图形。尽管Canvas是2D API，通过使用一些额外的JavaScript库可以让其呈现出3D效果，这也为那些不支持WebGL和CSS3 3D的平台提供了一个额外的选择。

这些特性，每一个都有其长处，短处以及技术上的权衡，每一个在创建引人入胜的3D交互和视觉体验中都有其不可或缺的角色。你使用哪一种技术可能基于几种因素--你打算创建什么，你打算支持哪个平台，性能是否是决定因素等等。比如说你打算创建一个第一人称射击的游戏那么你将需要高质量的图形图像。如果不使用WebGL扩展访问渲染硬件，这将很难实现。再举另外一个例子，或许你正在为一个视频网站开发一个精心设计的调台器界面，需要包括一个实时的视频缩略图，旋钮上需要有旋转效果，频道之间的过渡效果，这种情况下，使用CSS3就可以完成这些事情并具有超棒的体验。

【页内标注】
统治所有东西的标准。。。
大多数web开发者都知道HTML5实际上是一个技术和标准的集合。其中的一些是被W3C所批准并在所有浏览器中实现的。另外有一小部分被作为标准但是却没被广泛支持。还有另外一些，比如WebGL，是厂商和事实上的标准，但是却不属于W3C控制。