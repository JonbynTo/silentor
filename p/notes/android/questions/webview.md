Questions for WebView
============
> WebView的那些坑。



### 1. webview遇到http和https混合请求在高版本的适配问题

在API>=21的版本上，webview的http和https的混合请求默认是关闭的，而在21以下默认开启，使得高版本上面的http请求不能正确跳转。

* 解决方法
```java
	if (Build.VERSION.SDK_INT >= 21) {
	    webSettings.setMixedContentMode(WebSettings.MIXED_CONTENT_ALWAYS_ALLOW );
	}
```