# AndroidSimpleCameraApp
Simple Android camera app

# 功能：

利用Camera类设计一个简易照相机，通过SurfaceView组件实现取景预览，拍照保存等功能。拍照时，程序会自动在系统目录下生成"test"目录，保存时按camera+序号.jpg的方式保存照片，序号自动增加，确保拍照保存不会覆盖前面的照片。

# 实现的效果展示：

![image](https://raw.githubusercontent.com/ZHJ0125/AndroidSimpleCameraApp/master/%E6%95%88%E6%9E%9C%E5%9B%BE.gif)

http://47.95.13.239/Study/Android/test.gif

# 生成的APK文件下载地址：

https://raw.githubusercontent.com/ZHJ0125/AndroidSimpleCameraApp/master/app-debug.apk

该文件已在Android7.1.1、Android 4.0.2版本的手机上测试通过，其他Android版本的手机使用时可能会出现问题。

# 项目制作过程：

https://blog.csdn.net/ZHJ123CSDN/article/details/89880558


# 目前发现的bug:

  1.如果系统文件夹下未创建“test”文件夹，程序会闪退。 (已解决)
  
  2.未进行动态权限申请. 除Android 7.1.1版本外，其他版本会在权限上出现问题。 (已解决)

  3.Android 8.0版本的手机，拍照所得的图片会发生倾斜90°的现象，其他版本则不会。 (未解决)
