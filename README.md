# home-iptv

家里局域网用的 APTV 播放列表。大多数频道指向主路由上的转换服务：

`http://192.168.1.1:4022/udp/组播IP:端口`

苏州台来自公开的苏州电视台网播地址，不经过家里的组播转换。

## 在 APTV 里添加

直接导入这一条链接即可：

https://raw.githubusercontent.com/JayHome137/home-iptv/main/playlist.m3u

如果 raw 地址加载较慢，可以用这条备用：

https://cdn.jsdelivr.net/gh/JayHome137/home-iptv@main/playlist.m3u

APTV 会按列表里的分组显示：央视台、卫视台、苏州台、地方台、其他。

只能在家里局域网播放组播转换的频道；手机或 Apple TV 需要连着家里的网。苏州台在能访问公网时即可播放。

## 说明

- 当前列表共 149 个频道（145 路组播实测可播，另加 4 个苏州台）。
- 分组：央视台 21、卫视台 38、苏州台 4、地方台 53、其他 33。
- 频道名和组播地址来自公开的江苏电信 IPTV 组播表（主要参考 [wxq684007/gx](https://github.com/wxq684007/gx) 和 [imDazui 的江苏电信组播列表](https://github.com/imDazui/Tvlist-awesome-m3u-m3u8)），并改写成家里的转换地址。
- 苏州新闻综合、苏州社会经济、苏州文化生活、苏州生活资讯来自 [vbskycn/iptv](https://github.com/vbskycn/iptv) 里的苏州台网播地址。
- 当时测不通的组播频道没有写进去，例如 CCTV9、山东卫视（保留了能播的山东卫视 4K）、重庆卫视、河南卫视、兵团卫视等。
- 点播和回看不在这份列表里。
