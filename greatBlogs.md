#	开发总结

## great blogs collections

### https://blog.csdn.net/weixin_33698043/article/details/91719935
#### https://github.com/jtyjty99999/mobileTech/blob/master/README.md?utm_source=tuicool&utm_medium=referral
总结了一些在移动开发中常见的工具和查询网址，以及关于兼容性的通用设置
***

#### https://www.w3cplus.com/blog/666.html
### 深入了解 Flexbox 伸缩盒模型

#####	http://www.html-js.com/article/2402
###### http://www.html-js.com/article/2400
淘宝团队关于移动适配的一些总结 flexible设计
总结如下
* 使用rem
* 媒体查询设备宽度改变适配效果
* js 改变ratio
* 段落文字还是用px 其他宽高rem
* 1px

```javascript
var metaEl = doc.createElement('meta');
var scale = isRetina ? 0.5:1;
metaEl.setAttribute('name', 'viewport');
metaEl.setAttribute('content', 'initial-scale=' + scale + ', maximum-scale=' + scale + ', minimum-scale=' + scale + ', user-scalable=no');
if (docEl.firstElementChild) {
    document.documentElement.firstElementChild.appendChild(metaEl);
} else {
    var wrap = doc.createElement('div');
    wrap.appendChild(metaEl);
    documen.write(wrap.innerHTML);
}
```
[阿里-可伸缩布局方案-源码](https://github.com/amfe/lib-flexible)

***
### 关于font-size
* pc端 没有设备像素比，基本1px就是1px,自适应可以不用rem,除非需要
* 移动端除了opera 8以外的所有移动浏览器都支持rem单位值


emoji &#x1F34E;

***
### 其他小技巧
*　滚动条可以自定义　::-webkit-scrollbar
*　iPhone 4的一个 CSS 像素实际上表现为一块 2×2 的像素

***

### 其他优秀的blog
[前端监控体系](http://fex.baidu.com/blog/2014/05/build-performance-monitor-in-7-days/)

