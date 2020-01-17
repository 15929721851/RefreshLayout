修改自[SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout/tree/master) 2.0 版本



1. 去除拼命下拉的时候出现的彩蛋吐司: "你这么死拉，臣妾做不到啊！"

    ```
    使用作者的添加tag的方式无效所以直接修改源码
    ```

    

2. 增加下拉刷新/上拉加载时动画持续时间以及减少回弹比率, 使动画看上去更加自然平滑





如果想体验具备缺省页和自动处理下拉刷新/上拉加载/分页加载等功能的可以试试我的另一个库: [BRV](https://github.com/liangjingkanji/BRV)



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