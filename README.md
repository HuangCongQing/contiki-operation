# contiki-operation
contiki基础学习，开发 物联网（IoT）

官网：http://contiki-os.org/
Github: https://github.com/HuangCongQing/contiki

*[Contiki-3.0例子程序](./contiki-3.0（例子程序）/)


### 现在准备
官网上已经有各种下载软件链接以及步骤了，看下图
http://contiki-os.org/start.html
![image.png](https://upload-images.jianshu.io/upload_images/4340772-43f2890b4e6f9fd2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 准备工作
* 首先下载Instant Contiki
[ Instant Contiki ](http://sourceforge.net/projects/contiki/files/Instant%20Contiki/)，找到自己想下载的版，下载好之后再解压，如下图，

![](https://upload-images.jianshu.io/upload_images/4340772-4c75a397b3fa4a0a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
* 下载安装好VMware虚拟机
[Download VMWare Player »](http://www.vmware.com/go/downloadplayer/)
* 在解压好的Contiki文件夹里双击`.vmx`文件，会自动在虚拟机中打开
![](https://upload-images.jianshu.io/upload_images/4340772-21a2e87d8bc240ed.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 进去界面之后，输入密码`user`.就进入显示界面了
### 启动
* `Ctrl + Alt + T` 打开终端
输入
```
cd contiki/tools/cooja
ant run
```
如下图

![](https://upload-images.jianshu.io/upload_images/4340772-afce0df3d413c4c3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


* 当Cooja编译完成后，它将以一个蓝色的空窗口开始
![](https://upload-images.jianshu.io/upload_images/4340772-4d69b0785a6dc826.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
现在Cooja正在运行，我们可以通过一个模拟示例来尝试。

### 在模拟中运行Contiki
#### 创建新的模拟
单击`File`，然后单击 `New simulation `。![simulation](https://upload-images.jianshu.io/upload_images/4340772-da55633fb6932b58.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#### 设置模拟选项
Cooja现在打开`Create new simulation`对话框。在这个对话框中，我们可以选择给我们的模拟一个新的名字，但是对于这个例子，我们将坚持使用我的模拟。点击`Createe`按钮。

![image.png](https://upload-images.jianshu.io/upload_images/4340772-1cf86ad27c01f6e6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 仿真窗口
Cooja带来了新的模拟。 
屏幕左上方的`Network`窗口显示了模拟网络中的所有微粒 - 现在已经空了，因为我们的模拟没有任何细节。 
屏幕底部的`Timeline `窗口显示了模拟中的所有通信事件 - 非常方便了解网络中发生的事情。
屏幕右侧的` Mote output`窗口显示所有微尘的所有串口打印输出。
右上角的`Notes`窗口是我们可以为模拟放置注释的地方。
`Simulation control模拟控制`窗口中，我们开始，暂停，并重新加载我们的模拟。
还是放个图吧，谷歌翻译的
![](https://upload-images.jianshu.io/upload_images/4340772-e1ab8b353235e5d6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



