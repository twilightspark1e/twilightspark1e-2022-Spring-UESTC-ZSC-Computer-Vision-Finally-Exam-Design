# 课程设计——中山学院疫情防控人脸签到系统

该项目需要Windows系统配置好的pycharm环境，以及可以正常连接互联网的PC机

## 所调用的外部工具：

QT designer 和 Pyuic

### 安装、汉化和教程：

- [QT designer的安装与汉化（pycharm）] https://blog.csdn.net/qq_36374896/article/details/83513828

## 所调用的库：

- base64
- opencv-python
- numpy
- pyqt5
- requests
- sqlite3
- sys

## 素材壁纸选用：

![](https://i.bmp.ovh/imgs/2022/01/76c1f6930cafdb85.jpg)
- 为了方便命名为1.jpg，图片的位置位于mywindow.py的第22行  `self.label.setPixmap(QPixmap("1.jpg"))`
- 采用了学校北门的一张照片，可以进行更换，直接将图片命名为"1.jpg"进行替换即可

## 使用方法：

在界面打开后，主菜单的左上角有相应的功能按钮，直接点击需要的功能按钮即可正常使用

## 可能存在的一些问题：

1. 在签到的时候读取摄像头转化base64编码时可能会出现一些问题，导致整个程序卡住，需要在调试状态下重新运行
2. 当一个用户出现了两个人脸，会导致程序直接卡死（例如使用class1），此时需要删除用户的数据重新创建
3. 百度API的调用存在一定的失败率，百度API的监控报表里有说明具体的原因，包括但不限于摄像头未能正确的读取到人脸图像、格式错误等问题

## 关于百度API具体的文档：
- [百度API文档-人脸检测] https://cloud.baidu.com/doc/FACE/s/yk37c1u4t

## 个人信息
- 姓名：
- 专业班级：游戏开发M班
- 学号：

## 下载链接
- https://drive.google.com/file/d/1vztmSwSZCkVrbgetYx7CaO5sBdKr025G/view?usp=share_link

----------------------------



