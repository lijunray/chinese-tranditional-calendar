# chinese-tranditional-calendar

## 找了半天没有找到满足下述条件的中国农历iOS应用或者Google Chrome插件：
1. 类似ios自带的日历，可以显示公历+农历。
2. 可以添加农历事项，比如农历生日。
3. 提醒功能。
4. 界面简洁好看，没有其他多余功能。

根据这几个要求，感觉Chrome插件会更好，毕竟功能很少，专门做成app有点浪费，我自己也不太愿意下载这样一个app，不过感觉可以作为一个练手的入门app。

不管怎样，先把坑挖在这了，做不做看心情。=。=

## 未来可以考虑的扩展：（根据优先级排序）
0. 界面简洁好看。
1. 添加用户功能，可以同步日历内容，但是原则是绝对不要求注册登陆才能使用app。
2. 绝对不添加广告（完全不会考虑用这个赚钱，但是有了服务器之后会有一定支出，如果能被cover就好啦），但是如果真的完成了扩展1，可能会在某个不起眼的小地方添加一个“贡献”按钮。
3. 添加一个商店，可以由用户添加各种各样（奇奇怪怪）的日历事项，比如NASA日历显示所有NASA发射的火箭时间之类。


## chrome插件开发官方文档

[https://developer.chrome.com/extensions/getstarted](https://developer.chrome.com/extensions/getstarted)


步骤很简单：

1、配置文件：manifest.json

2、准备资源，包括：图标：icon.png，弹出的页面：popup.html，操作：popup.js

3、加载插件：在chrome://extensions中选择"加载已解压的扩展程序"，选择当前文件夹即可

效果如下：

![d](http://images.cnblogs.com/cnblogs_com/puyangsky/1092407/o_WX20171008-144246@2x.png)