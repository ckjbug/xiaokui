
<div align="center">
    <img src="https://i.imgur.com/7K8pfdy.jpg">
    <br>
</div>

-----------

## Markdown高阶语法

### Markdown的扩展语法，使用GitHub徽标，SVG，Font Awesome，emoji等装饰Markdown。


### 一，GitHub 徽标的官方网站[Shields.io](https://shields.io/#/)使用教程：

<div align="center">
    <img src="https://i.imgur.com/9c7k20y.png">
    <br>
</div>

参考链接：

[Github上常见的徽章标签和进度条](https://shikieiki.github.io/2017/03/01/%E4%B8%BA%E4%BD%A0%E7%9A%84Github%E7%94%9F%E6%88%90%E6%BC%82%E4%BA%AE%E7%9A%84%E5%BE%BD%E7%AB%A0%E5%92%8C%E8%BF%9B%E5%BA%A6%E6%9D%A1/)

[GitHub项目徽章的添加和设置](http://www.mdslq.cn/archives/b687dd8f.html)

[GitHub项目徽章的添加和设置](http://www.cocoachina.com/programmer/20170512/19256.html)

----------------------------


### 二，License是什么？有什么用？有哪几种License？该怎么添加？

- License是什么？

当我们在 GitHub 浏览一些开源项目时，经常会看到这样的标志：

![](https://i.imgur.com/5FjAAtj.png)

![](https://i.imgur.com/ViXtFVS.png)

> License就是开源许可证，开源许可证即授权条款，也可以说是一个开源项目的协议，开源软件并非完全没有限制。最基本的限制，就是开源软件强迫任何使用和修改该软件的人承认发起人的著作权和所有参与人的贡献。任何人拥有可以自由复制、修改、使用这些源代码的权利，不得设置针对任何人或团体领域的限制；不得限制开源软件的商业使用等。而许可证就是这样一个保证这些限制的法律文件。
- 常见的License有那种？
> MIT 许可证 -- 只要用户在项目副本中包含了版权声明和许可声明，他们就可以拿你的代码做任何想做的事情，你也无需承担任何责任。
> 
> Apache 许可证 -- 类似 MIT 许可证，但它同时还包含了贡献者向用户提供专利授权相关的条款。
> 
> GPL 许可证 -- 这是一种copyleft许可证，要求修改项目代码的用户再次分发源码或二进制代码时，必须公布他的相关修改。V3版本与V2类似，但其进一步约束了在某些限制软件更改的硬件上的使用范围。
- 怎么给一个开源项目添加License？

> 给一个新建的仓库添加许可证

<div align="center">
    <img src="https://i.imgur.com/hK5PBL3.png" width="700px">
    <br>
</div>

> 给一个已经建好的仓库添加许可证

<div align="center">
    <img src="https://i.imgur.com/QUk0yXm.png" width="680px">
    <br>
</div>

<div align="center">
    <img src="https://i.imgur.com/xiM5HUu.png" width="680px">
    <br>
</div>

<div align="center">
    <img src="https://i.imgur.com/cSqKfDA.png" width="700px">
    <br>
</div>

-------------
图解License

![](https://camo.githubusercontent.com/494ade0327e20b7ab4417e64f1045c0a3e8ba0e3/68747470733a2f2f70686f64616c2e6769746875622e696f2f6c6963656e7365732f6c6963656e73652e737667)

----------------------


### 三，Markdown编辑器有哪些？

Markdown编辑器有很多，我使用过好几种Markdown编辑器，各有各的优点，按照我的体验给大家推荐。

- MarkdownPad2
- Acrylic Markdown
- MarkdownEditor
- Typora


MarkdownPad2  
  功能比较齐全，有时候需要下载安装一个[Awesomium SDK](https://blog.csdn.net/joyhen/article/details/41577193)才能加载。专业版需要收费，用起来的确比较舒服，但表格有时候渲染不出来。

![](https://i.imgur.com/SQ0Wrkb.png)

Acrylic Markdown  
  微软家的UWP应用，收费，我花了20RMB买了一个，发现用起来还不错，而且能够直接上传文章到博客（WordPress和Medium），软件也在持续更新中，期待发布更多的功能模块。
<div align="left">
    <img src="https://i.imgur.com/fKDkxZo.png" width="98px">
    <br>
</div>

MarkdownEditor  
  我最开始使用的一款Markdown编辑器，免费，比较轻量级而且免安装，不到2M的一个应用，功能虽然没有那么多，但是更能专注地写作。

![](https://i.imgur.com/Budo9Nx.png)

Typora  
  朋友推荐的，免费，要安装（软件挺大），界面比较简单，但是功能很丰富，主题也挺多的，最主要的是它可以View Page Source，像浏览器查看网页源码一样的功能，推荐大家使用。


![](https://i.imgur.com/QLejvAh.png)

[这里有更多关于Markdown编辑器的介绍](https://www.jianshu.com/p/3ac8453f55d2)

-----------------------

### 四，Markdown支持视音频

其实Markdown是支持视频和音频的，但是Github不支持，所以也办法展示出来。但是你可以在本地的Markdown编辑器中写入下面的代码，就可以看到效果了。当然，Github Pages应该是支持的。

视频：
```
<video id="video" controls="" preload="none" poster="http://om2bks7xs.bkt.clouddn.com/2017-08-26-Markdown-Advance-Video.jpg">
      <source id="mp4" src="http://om2bks7xs.bkt.clouddn.com/2017-08-26-Markdown-Advance-Video.mp4" type="video/mp4">
</video>
```

音频：
```
<audio id="audio" controls="" preload="none">
      <source id="mp3" src="http://oht4nlntk.bkt.clouddn.com/Music_iP%E8%B5%B5%E9%9C%B2%20-%20%E7%A6%BB%E6%AD%8C%20%28Live%29.mp3">
</audio>
```


