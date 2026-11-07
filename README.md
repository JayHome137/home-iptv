# home-iptv

家里局域网用的 APTV 播放列表。每一条频道都指向主路由上的转换服务：

`http://192.168.1.1:4022/udp/组播IP:端口`

## 在 APTV 里添加

直接导入这一条链接即可：

https://raw.githubusercontent.com/JayHome137/home-iptv/main/playlist.m3u

如果 raw 地址加载较慢，可以用这条备用：

https://cdn.jsdelivr.net/gh/JayHome137/home-iptv@main/playlist.m3u

只能在家里局域网播放；手机或 Apple TV 需要连着家里的网。

## 说明

- 当前列表共 145 个频道，已在 2026-11-08 通过家里的转换服务实测能出流。
- 频道名和组播地址来自公开的江苏电信 IPTV 组播表（主要参考 [wxq684007/gx](https://github.com/wxq684007/gx) 和 [imDazui 的江苏电信组播列表](https://github.com/imDazui/Tvlist-awesome-m3u-m3u8)），并改写成家里的转换地址。
- 当时测不通的频道没有写进去，例如 CCTV9、山东卫视、重庆卫视、河南卫视、兵团卫视等。
- 点播和回看不在这份列表里。
