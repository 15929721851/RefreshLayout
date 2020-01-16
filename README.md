修改自[SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout/tree/master) 2.0版本



1. 去除拼命下拉的时候出现的彩蛋吐司: "你这么死拉，臣妾做不到啊！"

    ```
    使用作者的添加tag的方式无效所以直接修改源码
    ```

    

2. 增加`autoRefresh`下拉刷新时动画时长, 看上去动画更加平滑



## 安装

project 的 build.gradle

```groovy
allprojects {
    repositories {
        // ...
        maven { url 'https://jitpack.io' }
    }
}
```



module 的 build.gradle

```groovy
implementation 'com.github.liangjingkanji:RefreshLayout:1.0'
```