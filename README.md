## hexo-electric-clock-plus
修改自 [Zfour](https://github.com/Zfour) 大佬的 [hexo-electric-clock](https://github.com/Zfour/hexo-electric-clock)，主要解决了搜狐 API 对境外 IP 访问失效的问题。主要修改内容：
- 将原搜狐 API：
```bash
https://pv.sohu.com/cityjson?ie=utf-8
```
改为通过请求 ip-api 网址获取 IP 信息：
```bash
https://ipapi.co/json/
```

- 调整 CCS 样式，使得当获取到的 IP 为 IPv6 时也能正确地显示。


## 食用
- 该修改后的插件已经上传自 `npmjs.com`，直接安装该插件即可：
```bash
npm install hexo-electric-clock-plus --save
``` 

- 然后根据 Zfour 大佬的[教程](https://zfe.space/post/hexo-electric-clock.html)走即可。