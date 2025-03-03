# Bili-ShortVid-DEL
过滤 哔哩哔哩 过短视频
## 自定义
自己改源代码去 :)
```js
    // 配置参数，自己改，我不会 GUI
    const config = {
        videoItemSelector: '.bili-video-card__wrap', // 视频卡片容器
        checkInterval: 1000,                         // 检查间隔(毫秒)
        requestDelay: 500,                           // 请求延迟防止封禁
        minDuration: 120                             // 最小允许时长(秒)
    };
```
