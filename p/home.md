![](react-home.png)
# 一、关于React
* React源于Facebook，于2013年5月开源，用于构建用户界面。
* 几个前端框架：AngularJS，React，Vue
* React预热：JS，DOM，JSX（不必须）

# 二、React的特点
* 虚拟DOM

    >与其它框架相比，React采取了一种特立独行的操作DOM的方式。

	>它并不直接对DOM进行操作。

	>它引入了一个叫做虚拟DOM的概念，安插在JavaScript逻辑和实际的DOM之间。

	>这一概念提高了Web性能。在UI渲染过程中，React通过在虚拟DOM中的微操作来实对现实际DOM的局部更新。
	
* 组件化：组合、重用、可维护性强

	>上手快，易学

	>为你程序编写独立的模块化UI组件，这样当某个或某些组件出现问题是，可以方便地进行隔离。

	>每个组件都可以进行独立的开发和测试，并且它们可以引入其它组件。这等同于提高了代码的可维护性。

* 单向数据流

	>

# 三、React的使用
* 安装

	> 1. 到[官网](https://facebook.github.io/react/downloads.html "React")下载压缩包
	
	> 2. 解压
	
	> 3. build目录

* HelloWorld, ReactDOM.render方法
    
	<pre>    &lt;script src="../build/react.js"></script>
	    &lt;script src="../build/react-dom.js"></script>
	    &lt;script src="../build/browser.js"></script>
	</pre>

	[hello_world.html](react-demos-master/demo01/index.html)

* JSX语法

	>JSX语法让我们可以在javascript代码中嵌入html代码
	
	[jsx_demo.html](react-demos-master/demo03/index.html)

* 组件化, React.createClass方法

	>React允许我们将代码封装成组件，然后像插入普通 HTML 标签一样，在网页中插入这个组件。React.createClass方法就用于生成一个组件类。
	
	>注意：组件名首字母必须大写, 只能包含一个顶级标签。
	
	[component.html](react-demos-master/demo04/index.html)

* DOM，表单，事件，Ajax
# 四、React的实用性和可实施性
# 五、参考链接
* React英文官网 [https://facebook.github.io/react/index.html](https://facebook.github.io/react/index.html)
* React中文官网 [http://reactjs.cn/react/index.html](http://reactjs.cn/react/index.html)
* 阮一峰入门实例教程 [http://www.ruanyifeng.com/blog/2015/03/react.html](http://www.ruanyifeng.com/blog/2015/03/react.html)
* 一些Demo [https://github.com/ruanyf/react-demos](https://github.com/ruanyf/react-demos)
* React社区 [http://react-china.org/](http://react-china.org/)