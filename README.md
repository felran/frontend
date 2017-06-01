# frontend-前端知识分享

## 面试总结

前段时间找工作，陆续收到一些公司的面试通知，记录下来给大家分享一下，这边记录的为多家企业的面试问题综合；

### 基础知识篇

主要涉及一些javascript/html/css基础知识
#### javascript
* 前端javascript 作为静态语言与动态语言的区别是什么
* 解释下javascript 中的prototype机制以及原型链和继承，最好举例说明
* 闭包的概念，闭包被调用的时机，闭包中scope的生命周期
* js 事件，解释冒泡机制和捕获机制
* eval的作用，如何做到将string 格式的js代码变为可执行代码;答：（eval(str),new Function(str)）
* html 中的script 是否会阻塞，放页面顶部要不阻塞怎么做？script标签的 async 和defer 有什么区别
* 是否用过requestAnimationFrame
* js 的数组操作常见的有哪些。shift与pop，unshift与push，splice
* 跨域的几种方式
#### css
* css  的盒子模型
* css 中容器设置为position:absolute,该容器相对谁布局
* css 子元素为float,父容器的高度是怎么样？如何高度自适应

### 各类框架

这些内容主要根据你的项目经验来看，因人而异！主要记住一点，你需要主动引导面试官，让他问你希望他问题的问题就OK了，千万别答不上来，此环节尽量别说不知道，若真不知道也别直说；此处列举一些常见的技术和框架可能问的问题

* angular框架的双向绑定
* react框架的生命周期
* webpack 熟悉到什么程度
* RequireJS的实现原理，详细描述RequireJS如何加载一个文件（本人大多项目中均用过RequireJS）
* websocket的实现机制是什么，轮询，长轮询，长连接的区别，websocket与SSE
* hybrid app开发与原生开发的区别，hybrid app的运行机制
* 一个网站从页面加载到渲染完成的过程(越详细越好)

### 性能优化相关

* 站点性能优化
* 代码性能优化（repaint和reflow），分别介绍可做哪些优化改进
