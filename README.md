

## Fiddlor - 1.2.7 震撼来袭, 一个基于http,https,proxy的数据包抓取框架。

> 工程结构全新优化   
支持http,https所有包的抓取  


该库部分思想借鉴了以下博客：
 * [https://github.com/yanzhenjie/NoHttp](https://github.com/Y0LANDA/NoHttp) 
 * [https://github.com/square/retrofit](https://github.com/square/retrofit)

在此特别感谢上述作者，喜欢原作的可以去使用原项目。同时欢迎大家下载体验本项目，如果使用过程中遇到什么问题，欢迎反馈。

## 联系方式
 * email： 2987691848@qq.com



## 未来版本
### [v2.2.8]版本
- 计划支持指定域名获取数据
- 计划支持修改数据包，修改kookie

### [v2.2.9]版本
- 计划增加扩展库,加入tcp,udp数据的截取

### 其他功能暂时还没想出来，大家有想法的可以积极加群讨论，或者直接在issue里面提出你的想法，我会第一时间回复。

## 使用

Android Studio用户


```java
//必须使用
implementation 'com.fiddler.storagehelper:fiddlor:1.2.7'

allprojects {
    repositories {
        google()
        jcenter()
        repositories {
            maven { url "https://raw.githubusercontent.com/fiddlersun/fiddlor/master" }
        }
    }
}

//在application中初始化
 Fiddlor.getinstans().initProxy(this);
//在需要获取数据的地方：
实现  接口FiddlerObserver
```

Eclipse的用户(赶紧换AS吧):

如果遇到使用问题，解决办法如下：
1. 看上述文档中是否有相关描述
2. 看别人提的issues是否有你的问题，这里面有很多人的提问
3. 如果你感觉是bug，或者有疑问，也欢迎在issues里面提问，我每天都会认真解答
4. 还有疑问，加入联系方式中的QQ群，大家一起讨论。


## Licenses
```
 Copyright 2019  chinafeng(中国风)

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
```
