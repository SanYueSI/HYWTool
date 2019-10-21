# 整合了下项目中写的一些工具类
![image.png](https://upload-images.jianshu.io/upload_images/13934769-8152cc5ca5db6c09.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
##使用方法
 1.根目录的 build.gradle 添加
 ```
 allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
 ```
 2.在app的buil.gradle 添加
 ```
 implementation 'com.github.YiPHaoYouWei:HYWTool:1.0.0'
 ```

### 包含了
 1.正则表达式AccountValidatorUtil
