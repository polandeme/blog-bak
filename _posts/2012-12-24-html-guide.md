---
layout: post
title:  "html5 guide!"
date:   2013-12-23 13:14:46
categories: html5 
---
###概括
&nbsp;&nbsp;&nbsp;&nbsp;html5并不是想我们想象的那么神秘，其实只是让原来的东西变的更容易。html5增加的东西不仅仅是一些简单都新标签，那些只是一些简单的概念。就像html4的时候各个标签它只是标签而已。更重要的是灵活运用。  
&nbsp;&nbsp;&nbsp;&nbsp;下面主要是将html5主要的东西概括一下。不对都地方请指正。  

- ####新标签  
&nbsp;&nbsp;&nbsp;&nbsp;html5的一些新标签增加了部分比较有用的标签，同时也将上一版的标签的含义有所改变，这个具体请自行看书，html5标签最主要的就是它更接近与语义化。简单的举一下例子。 

    - `header` 标记头部区域的内容(用于整个页面或者页面的一块区域)  
    - `footer` 标记脚部区域的内容(用于整个页面或者页面的一块区域)   
    - `section` Web 页面的一块区域  
    - `article`独立的文章内容  
    -  `aside` 相关内容或者引文  
    - `nav` 导航类辅助内容    
[html5 新增属性总结](http://imsole.net/html5/index.html)
- ####canvas  
&nbsp;&nbsp;&nbsp;&nbsp;canvas是html5中一个基础且重要的东西，用它来进行进行画东西，具体都canvas一些操作 请戳[canvas](https://developer.mozilla.org/zh-CN/docs/Canvas_tutorial)  
    - [用canvas画的时钟](http://polandeme.github.io/2013/09/19/clock/)
    - [好多好的demo](https://developer.mozilla.org/ms/demos/tag/tech:canvas)   
- ####video & audio  
&nbsp;&nbsp;&nbsp;&nbsp;功能强大，知识简单，不做赘述，[常用api](http://polandeme.github.io/2013/09/19/clock/)
- ####Geolocation 
&nbsp;&nbsp;&nbsp;&nbsp;Geolocation是位置信息，利用它可以调用找到你的位置信息，给出的是一个经纬度的值，结合其他地图api可以很好都开发出地图应用。  

    - 个人感觉比较适合做商业应用 资料[参考](http://www.ibm.com/developerworks/cn/web/wa-html5fundamentals3/)  
- ####Communication  
&nbsp;&nbsp;&nbsp;&nbsp; 顾名思义Communication主要就是关于通信，方面的知识，页面与页面之间，页面与框架之间的信息互通，比较常见的一个例子就是html5做的幻灯片就是利用这方面的知识点做的。    

    - 教程[参考](http://software.intel.com/zh-cn/blogs/2012/03/02/webhtml5-communication-api)  
&nbsp;&nbsp;&nbsp;&nbsp;对于这方面的可能比较会用的可能多，希望自习看一下  
- ####webScoket  
&nbsp;&nbsp;&nbsp;&nbsp;webScoket html5中一个强大的通信功能，实现实时更新，减少网络延迟。  
用它可以做什么  
  - 聊天室  
  - 类似你画我猜游戏  
  - 类似与股票数据实时更新效果  
  - 与Geolocation结合定位并实时更新  
  是不是很强大赶快来看一下怎么用吧
[你画我猜](http://www.ibm.com/developerworks/cn/web/1112_huangxa_websocket/)带源码    
[demo](http://www.miaozhuang.net/%E5%9F%BA%E4%BA%8Ehtml5-websocket%E5%92%8Ccanvas%E7%9A%84%E5%A4%9A%E4%BA%BA%E5%9C%A8%E7%BA%BF%E7%94%BB%E5%9B%BE%E7%A8%8B%E5%BA%8F/)   
#####Web scoket 要想学好可能会涉及到一些后台方面的东西，需要简单的了解一下  
- ####Web Storage 
&nbsp;&nbsp;&nbsp;&nbsp;本地存储，其实就是cookie的扩展版。也是一个比较有用的功能,可以不用利用服务器就可以存储数据，方便又快速。
主要包括`sessionStorage` `localstorage`对这方面主要是对数据的处理和了解，只要能够有个大体了解，操作起来并不是太难  
    - [参考](http://blog.baiwand.com/?post=184)  

- ###Forms   
    - `tel`电话号码  
    - `email`电子邮件  
    - `url`网址  
    - `Search`用于搜索引擎  
    - `range`特定范围的数值选择器，滑动条  
    - `number`只能是数字  
    - 未来可能会支持，或者支持不是太好的  
        - `color` 颜色选择器  
        - `datetime`显示完整的时间，时间选择器  
        - `data` 日期选择器  
        - `week`某年的周选择器
    - ...  
表单怎加这些元素最好的用处就是可以节约在前端表单验证方面的工作量。合理利用这些元素会让你开发更有效率  

-----------------------------------------------

```以上主要是应用比较广泛的地方还有一些也很有用的新属性就不一一介绍了，主要是因为比较简单或者不太常用,下面将一些其他的列出来，算是个提纲吧有机会再介绍 ```  

- SVG 与canvsa对应 这个是画矢量图的应用接口  
- 拖放 拖拽上传等功能  
    - [提升用户体验：HTML5 拖放文件上传](http://sofish.de/1545)  
    - 对于处理图片可以看一下关于base64方面的东西，感觉效率挺高的。例如  
    [data:image/png;base64,iVBORw0KGgoAAA...](data:image/png;base64,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)
- history API 可以记录浏览历史，模仿浏览器的前进后退键  
- 离线存储 开发离线应用，或者与其他结合，是网站更加好用  
- Web GL 开发3D应用，canvas主要是用来开发二维图像，这个主要是用来开发3维图像，有个比较好的库three.js  
- Web worker 能够把 JavaScript 计算委托给后台线程，通过允许这些活动以防止使交互型事件变得缓慢。  
- `Camera API` 调用摄像头操作  
- 移动开发   
-  ...

-----------------------------------------------------------------------------------
-----------------------------------------------------------------------------------


###开发html5应用  
&nbsp;&nbsp;&nbsp;&nbsp;上面那些只是对html5的应用的一些介绍，是想要开发一个html5应用你，最主要的是将这些东西能够完美的结合起来。例如开发一个你画我猜，需要画板(canvas),然后需要对方实时看见，那就需要web socket。而webScoket又需要配置环境，如果想用的更好一些，可能还需要一些后台知识。所以说重要的是能将这些知识结合在一起。  
如果有更好的表现还需要看一下css3的相关知识，这些都能够很大程度的减少工程量。  


####整理了整整一个下午，可能不是很完善，但是希望可以有所帮助。  
####链接中的资料绝对都是很好的资料，而且绝大多数都是来自国外，自习看一下，绝对很有帮助  

更多参考  
- [MDN html5](https://developer.mozilla.org/zh-CN/docs/HTML/HTML5)  
- [inter html5](http://software.intel.com/zh-cn/html5/training)  
- [jquery 官方文档](jquery.com)  
- [jquery 中文文档](http://www.css88.com/jqapi-1.9/)  
- [w3cplus](http://www.w3cplus.com/blog/tags/11.html)  
