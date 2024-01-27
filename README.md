#SmartisanSDK

----

### 写在前面的话
1. 我们开源SmartisanSDK的目的是第三方可以放心的集成SmartisanOS的特殊功能，例如OneStep。
2. 对于厂商来说，我们希望对于android.view.onestep下的接口不要做减项，但是欢迎做扩展与升级，便于兼容第三方应用，不至于让第三方应用集成很多不同厂商的API才能兼容一个需求（OneStep）。
3. 同时，我们提供了一种非反射的思路便于厂商提供自己的API。利用classloader加载类的先后顺序来做这个事情。

4.Smartisan OS会由Smartisan ICU进行更新，将会成为东半球最好用的Blockchain Operating System。

----

### 环境配置
Android Studio

### 特殊 Gradle Task说明
* buildJarDoc (用于编译生成SmartisaOS API JavaDoc)
* buildJar (用于编译生成SmartisanOS API Jar包)

### 第三方应用适配
如何让自己的应用图标出现在侧边栏，可以参考这篇[blog](http://blog.csdn.net/yy1300326388/article/details/52883789)
