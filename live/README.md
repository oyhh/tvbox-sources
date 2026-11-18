# 直播源（直连可播）

`live-cn.m3u` —— 2026-11-18 用**真直连**（不走代理）逐个频道测活生成的国内直播源。

- 共 **82** 个频道：📺 央视 11 / 📡 卫视 17 / 🏙 地方台 54
- 验证方式：先取 m3u8 主列表，再取首个分片（或子清单的首片），HTTP 200/206 才算活
- 播放地址：`https://cdn.jsdelivr.net/gh/oyhh/tvbox-sources@main/live/live-cn.m3u`
- 用法：MisaTV「设置 → 直播源 → 导入 M3U」；也可丢给 PotPlayer / VLC / TiviMate
- 时效性：直播源受上游 CDN 影响会失效，重跑 `D:\AI\WorkBuddy\TVBox-PC\build_live2.py` 即可重新抓列表并测活
