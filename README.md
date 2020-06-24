# build-a-videocapture-library
##为什么需要一个videocapture库
如果你是在做一个计算机视觉相关的项目，同时你算法所要处理的是视频相关的数据，那视频采集基本是比不可少的环节。可能你需要从本地视频文件中读取图像，也可能需要从摄像头或者流媒体中读取图像，对于大部分初入行的计算机视觉人员，视频采集常常成为他们入行的绊脚石，本项目以具体工程为例实现一个视频采集类库。

###常见的视频输入源
####视频、图像序列文件，比如.mp4、.avi等形式的视频文件，或者xx01.jpg,xx02.jpg,....,xx99.jpg形式的图像序列
####摄像头，摄像头种类较多，有ip摄像头、usb摄像头、工业摄像头以及通过视频采集卡连接的视频采集设备。
####流媒体，在直播或者视频网站中使用的流媒体。

###一个简单的计算机视觉项目pipeline
videocapture --> pre-process --> ai/image process --> save/display/send

