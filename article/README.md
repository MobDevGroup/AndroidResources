## Android技术博文

### 架构
* ### MVC
> 即：Model-View-Controller，是最常见的软件架构之一，业界有着广泛应用。
View 传送指令到 Controller,Controller 完成业务逻辑后，要求 Model 改变状态
,Model 将新的数据发送到 View，用户得到反馈.所有通信都是单向的。

* ### MVP
> 即：Model-View-Presenter，各部分之间的通信，都是双向的。View 与 Model 不发生联系，都通过 Presenter 传递。View 非常薄，不部署任何业务逻辑，称为"被动视图"（Passive View），即没有任何主动性，而 Presenter非常厚，所有逻辑都部署在那里。

* ### MVVM
> 即：Model-View-ViewModel，将 Presenter 改名为 ViewModel，基本上与 MVP 模式完全一致。唯一的区别是，它采用双向绑定（data-binding）：View的变动，自动反映在 ViewModel，反之亦然。Angular 和 Ember 都采用这种模式。

注：节选自阮一峰的博文：[MVC，MVP 和 MVVM 的图示](http://www.ruanyifeng.com/blog/2015/02/mvcmvp_mvvm.html)

### Activity/Fragment

### Service/BroadcastReceiver

### ContentProvider

### 动画

### 资源

### 数据存储

### 兼容与适配

### 自定义View

### 事件分发

### 开源项目解析

### 多媒体

### 传感器

### 地图与定位

### 蓝牙

### 项目构建

### 图像处理

### 性能优化
