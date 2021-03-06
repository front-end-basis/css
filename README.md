# css/css3

关于css/css3部分，这个可折腾的东西就多了。

在之前，特别是前端新人，可能会觉得CSS（默认包括css3版本，下同）很简单。没错，我在刚开始的时候也是这么觉得的，不过随着深入之后，我发现css还是别有洞天的，有着太多细节性的知识点需要我们去搞定和积累。以及随着数量的增多，不知道你们是否会有一个纠结于怎么命名的阶段，反正我是有过。

我对于css部分的学习，算得上有去关注的，到现在陆陆续续最多只能算是一年多。css手册也看过几遍，不过想要记住所有的标签和属性还是不现实的，至少对于我而言是这样的。当然对于常用的，应该是没啥大问题。

css本身是不具有逻辑性的，如果我们一直都是采用最原始的直接书写css，感觉效率还是有很大提升空间的。所以我们可以选择一种css预处理工具来加快我们的开发书写效率，我自己选择的是**sass中的scss版本**。

随着nodejs的诞生以及前端自动化工具的普及，借助grunt/gulp/npm/webpack等构建工具，确实可以大大的解放我们的双手。那些之前需要手动编译刷新的重复工作，如今都可以直接交给电脑自动处理了。我个人使用的是Gulp自动化工具，之前也有用过一段时间的Grunt，从结果来看算是大同小异的。

**个人对于css的书写习惯是：**

- 一般情况下采用的是英文单词，其次采用的是拼音，当然英文单词和拼音都有可能采取缩写。会尽可能的去遵循语意化。
- 我使用的是连字符“-”方式连接单词，目的其实很简单，就是跟css自身的风格保持一直。我自己是优先使用连字符方式的，但是也不排斥下划线和驼峰式连接方式。
- 我平常书写css的风格是一行一个，然后会利用自动化工具自动压缩一个压缩版的*.min.css。风格示例如下：

```css
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.text-ell {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}
```

现在刚好借助这一年重新夯实基础的机会，重新尝试着系统性的学习，并把之前看到的和自己还可以想起来的东西做一个备份。









PS：

- css在线参考手册：[http://css.doyoe.com/](http://css.doyoe.com/)

其他资源：

- [IE下css3解决方案](http://gucong3000.github.io/selectivizr/)
- [CSS3 Marker](http://www.css3maker.com/)


更多学习资料请查看：[https://github.com/imruxin/front-end-study-collect](https://github.com/imruxin/front-end-study-collect)