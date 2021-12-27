# Flat-Ads---IS-custom-adapter
Flat Ads - IS custom adapter

###Android SDK
##添加依赖和初始化
添加依赖
```
dependencies {
    implementation 'com.flatads.sdk:flatads:1.3.0'
    implementation 'com.ironsource.adapters:flatadapter:1.0.2'
}

//

allprojects {
    repositories {
        maven {url "http://maven.flat-ads.com/repository/maven-public/"}
    }
}
```

混淆规则
```
-keep class com.flatads.sdk.response.* {*;}
```