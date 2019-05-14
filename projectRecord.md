#基础配置 
## React Native中文官网
&emsp;&emsp;https://reactnative.cn/

&emsp;&emsp;**1、搭建环境的链接如下所示**

&emsp;&emsp;https://reactnative.cn/docs/getting-started.html

&emsp;&emsp;**2、开始项目LittleWhale**

&emsp;&emsp;&emsp;&emsp;**(1)、新建项目LittleWhale**

&emsp;&emsp;&emsp;&emsp;``` react-native init LittleWhale```

&emsp;&emsp;&emsp;&emsp;创建好的项目目录如下图所示：

&emsp;&emsp;&emsp;&emsp;![projectDirectory](https://github.com/meilingJing/LearningRN/blob/master/projectDirectory.png?raw=true)

&emsp;&emsp;&emsp;&emsp;**(2)、运行项目LittleWhale**

&emsp;&emsp;&emsp;&emsp;在DOC窗口中进入到项目LittleWhale的根目录下执行(已经连接android真机)：
&emsp;&emsp;&emsp;&emsp;``` react-native run-android```
&emsp;&emsp;&emsp;&emsp;当你开开心心等待项目运行起来时，突然报错了T_T
&emsp;&emsp;&emsp;&emsp;![sdkLocationNotFound](https://github.com/meilingJing/LearningRN/blob/master/sdk_location_not_found.png?raw=true)

&emsp;&emsp;&emsp;&emsp;**<font color=#ff0000 size=4> 注意:这个错误的原因是创建的项目中android目录的部分缺少了Android sdk路径的配置文件local.properties，具体配置如下图所示： </font>**

&emsp;&emsp;&emsp;&emsp;![addAndroidSdkLocation](https://github.com/meilingJing/LearningRN/blob/master/add_android_sdk_location.png?raw=true)

