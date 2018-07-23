---
title: 快应用（Quick App）
date: 2018-07-03 21:04:40
categories:
- Quick App
tags:
- Quick App 
presentation:
  theme: league.css
  enableSpeakerNotes: true
  transition: 'zoom' # none/fade/slide/convex/concave/zoom
---

<!-- slide data-transition="zoom" -->

### 快应用（Quick App）

<img src="https://gss2.bdstatic.com/9fo3dSag_xI4khGkpoWK1HF6hhy/baike/c0%3Dbaike150%2C5%2C5%2C150%2C50/sign=33fae635a5014c080d3620f76b12696d/d6ca7bcb0a46f21f64d735cffa246b600d33ae4f.jpg" width="70%" style="margin-top:40px" />
<!-- [![](https://gss2.bdstatic.com/9fo3dSag_xI4khGkpoWK1HF6hhy/baike/c0%3Dbaike150%2C5%2C5%2C150%2C50/sign=33fae635a5014c080d3620f76b12696d/d6ca7bcb0a46f21f64d735cffa246b600d33ae4f.jpg)](https://swsdl.vivo.com.cn/appstore/developer/uploadfile/20180323/20180323183010837.mp4) -->
[官方视频短片](https://swsdl.vivo.com.cn/appstore/developer/uploadfile/20180323/20180323183010837.mp4)

<!-- slide data-transition="zoom" -->

### 谁动了我的奶酪

导火线，小程序接入广点通，厂商的利益受到了挑战。

快应用标准虽然是3月20日才发布，实际却是早有运作，小米“直达服务”、魅族“快捷应用”、金立的“秒开应用”都属于快应用，这次只是形成联盟制定统一的开发、接入标准。

在 2013 年的百度世界大会上，百度正式推出了「百度轻应用」。在会上百度是这么介绍的通过「轻应用」的模式，用户无须下载 Native APP，直接通过搜索框，实现即搜即得。


<!-- slide data-transition="zoom" vertical=true -->
### 快应用 VS 微信小程序 VS 原生App

<img src="https://am.zdmimg.com/201803/28/5abb24f722b8c695.png_e600.jpg" height="550" />

<!-- slide data-transition="zoom" vertical=true -->
### 快应用 VS 微信小程序 VS 原生App

<img src="https://qnam.smzdm.com/201803/28/5abb21f3a35af6823.jpg_e600.jpg" width="70%" />

<!-- slide data-transition="zoom" vertical=true -->
### 快应用 VS 微信小程序 VS 原生App

<img src="https://am.zdmimg.com/201803/28/5abb4768760c03200.jpg_e600.jpg" width="70%" />

<!-- slide data-transition="zoom" vertical=true -->
### 快应用 VS 微信小程序 VS 原生App

<img src="https://am.zdmimg.com/201803/28/5abb21f3adc741627.jpg_e600.jpg" width="70%" />

<!-- slide data-transition="zoom" -->

### 快应用的优势？

- **具备传统APP完整的应用体验，无需安装、即点即用。**

- **覆盖Android主流手机10亿设备**

- **与手机系统深度整合的提供场景化体验的新型应用**

<!-- slide data-transition="zoom" -->

### 快应用与小程序

<img src="https://a.zdmimg.com/201803/28/5abb75e13f9f29126.png_fo710.jpg" width="70%" />

<!-- slide data-transition="zoom" -->

### 快应用入口

- **通知栏搜索框**

- **负一屏**

- **桌面快捷图标**

- **应用商店**

- **浏览器**

<!-- slide vertical=true data-transition="convex" -->

**构建资源树**：
Parcel 接受单个入口资源作为输入，可以是任意类型： JS 文件、HTML、CSS 和图片等等。有许多不同的资源类型在 Parcel 中被定义，它知道如何去处理特定的文件类型。资源会被解析，资源的依赖会被提取，资源会被转换成最终编译好的形态。此过程创建了一个资源树
<!-- slide vertical=true data-transition="convex" -->

**构建文件束（Bundle）树**： 
一旦资源树被构建好，资源会被放置在文件束树中。首先一个入口资源会被创建成一个文件束，然后动态的 import() 会被创建成子文件束 ，这引发了代码的拆分。 
当不同类型的文件资源被引入，兄弟文件束就会被创建。例如你在 JavaScript 中引入了 CSS 文件，那它会被放置在一个与 JavaScript 文件对应的兄弟文件束中。 
如果资源被多于一个文件束引用，它会被提升到文件束树中最近的公共祖先中，这样该资源就不会被多次打包。
<!-- slide vertical=true data-transition="convex" -->

**打包**： 
在文件束树被构建之后，每个文件束都会被 packager 写到一个特定文件类型的文件中。packagers 知道如何从每个资源中将代码合并起来，生成到最终被浏览器加载的文件中

<!-- slide data-transition="zoom" data-background-image="https://i.loli.net/2016/07/18/578c66da6a5a3.jpg" --> 