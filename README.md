 	一直以来，安卓UI自动化测试都存在以下两个障碍，一是测试工具Mokey/Appium等的学习成本较高，不方便刚接触移动端自动化的新手入门；另一个是，在测试代码书写中耗费在控件元素查找上的时间太多，在一些稍微复杂的应用中尤其突出。LazyAndroid正是为了解决这些问题而诞生的一款UI自动化测试框架。它基于appium，封装了appiumDriver的设置、安卓基本控件的使用和手机的滑动、按键等基本操作，增加了元素查找的重试机制、异常处理截屏等。结合LazyUiautomaterViewer工具自动生成的bean层java代码，更可以使QA可以无需亲自动手完成具体页面中控件的抓取，无需关心appium api的使用，即可轻松完成测试逻辑代码的书写。
--------------------- 
重新修改了部分资源文件及jar包，支持android-api26及以上
使用说明：
1. 将所有jar包拷贝到%SDK%/tools\lib目录下，覆盖原来的uiautomatorviewer.jar 或者直接点击运行
2. 使用%SDK%/tools\uiautomatorviewer.bat 运行即可。 

感谢：拥春飞翔 
来源：CSDN 
原文：https://blog.csdn.net/iamhuanggua/article/details/53104345 
