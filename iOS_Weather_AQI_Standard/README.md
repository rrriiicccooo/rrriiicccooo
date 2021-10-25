## 修改自 [Hackl0us](https://github.com/Hackl0us/SS-Rule-Snippet/blob/master/Scripts/Surge/iOS_Weather_AQI_Standard.js) 原始项目，以及 [chouchoui](https://github.com/chouchoui/QuanX/tree/master/Scripts/iOS_Weather_AQI_Standard) 项目

##使用教程：

首先前往 https://aqicn.org/data-platform/token/ 注册账户，将申请的 API Token 记录下来

1. 打开 Quantumult X，重写 - 引用
-
    如果你的地区和语言设置分别是中国大陆和英文 - 添加
```
https://raw.githubusercontent.com/rrriiicccooo/rrriiicccooo/main/iOS_Weather_AQI_Standard/iOS_Weather_AQI_Standard.conf
```
-
    如果你的地区和语言设置分别是美国和英文 - 添加   
```
https://raw.githubusercontent.com/rrriiicccooo/rrriiicccooo/main/iOS_Weather_AQI_Standard/iOS_Weather_AQI_Standard_en_US.conf
```
2. 打开 BoxJs
    - http://boxjs.com
    - http://boxjs.net
    - http://127.0.0.1:9999
> 关于 BoxJs 的使用教程请查看 BoxJs 使用手册 [https://chavyleung.gitbook.io/boxjs/](https://chavyleung.gitbook.io/boxjs/)

3. BoxJs 中 订阅 - 添加
```
https://raw.githubusercontent.com/Hackl0us/SS-Rule-Snippet/master/Scripts/hackl0us.boxjs.json
```
4. 在 应用 中找到刚订阅的 `Hackl0us 应用订阅`，点击下方的 `将 iOS 系统原生 天气 App 的空气质量标准改为 AQI-US` 应用
5. 在 应用设置 的 aqicn API Token 文本框中填入 aqicn.org 申请获得的 Token，保存设置
6. 在天气应用中查看是否生效
