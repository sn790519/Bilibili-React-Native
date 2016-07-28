## Bilibili客户端的ReactNative版本
---
目前进度：添加了打开APP的欢迎页面；改成了使用props传递navigator进行跳转；做了下载页的页面和跳转；现在碰到一个问题就是没有用Android原生的抽屉组件，模拟进行滑动动作采集频率太低了，不能形成连贯的动作，**希望有想法的同学联系我！Q:2427322447**。

### 开发环境

+ PLATFORM:    Windows
+ RN:   React-Native 0.29
+ IDE:   Webstorm
+ VM:   Genymotion

### 任务列表

+ 前期任务
	+ 实现各个各个activity之间的跳转功能
	+ 写出主要的四五个页面
	+ 使用图片资源为静态资源

+ 中期任务
	+ 搭建Nodejs服务器，进行网络通信
	+ 对本地资源进行管理，并实现设置功能
	+ 使用B站API进行视频查询和用户信息拉取

+ 后期任务
	+ 加入ijkPlayer，并实现弹幕播放器的主要功能
	+ 不同大小设备的自适应
	+ ......

+ 其他尝试
	+ 联系B站获取AppKey，弃用本地接口，进行高级功能的开发
	+ 将应用移植到ios上

### App实况截图
![主页面](http://7xsm7w.com1.z0.glb.clouddn.com/0728175950.png)
![侧 面](http://7xsm7w.com1.z0.glb.clouddn.com/8180010.png)
![下载页](http://7xsm7w.com1.z0.glb.clouddn.com/28180022.png)
