# 壳 + 源 清单

> 更新：2026-11-18。播放器/阅读器壳子 + 各自能吃的源。raw 直连超时，用 jsDelivr。

## MisaTV · 影视(点播+直播)
- 仓库：https://github.com/yagami-hue/MisaTV
- 本机：`D:\AI\WorkBuddy\TVBox-PC\MisaTV.exe`
- 源格式：TVBox 接口 JSON (CMS/多仓) + Kazumi 规则 + jar/js/py 蜘蛛
- 采集站 44：https://cdn.jsdelivr.net/gh/oyhh/tvbox-sources@main/tvbox-cms-direct.json
- 多仓 42：https://cdn.jsdelivr.net/gh/oyhh/tvbox-sources@main/tvbox-stores-direct.json
- Kazumi 动漫规则 18：https://cdn.jsdelivr.net/gh/Predidit/KazumiRules@main/index.json

## HGhub · 影视(桌面+安卓)
- 仓库：https://github.com/Minireel/HGhub
- 本机：`D:\AI\WorkBuddy\HGhub\App\HGhub.exe`
- 源格式：HPP 1.0 单文件 JS 插件
- HPP 插件 14：anfuns、apple、avtoday、duanjutt、hdmoli、hkdoll、huangguo、jdys、jpyy、madou、pornhub、wwgz、xhamster、xingya

## 洛雪音乐 · 音乐
- 仓库：https://github.com/lyswhut/lx-music-desktop
- 本机：`D:\Tools\lx-music-desktop-v2.11.0-win_x64-green\lx-music-desktop.exe`
- 源格式：自定义音源脚本 (user_api JS)
- 音源 20（pdone/lx-music-source）：
  - 长青SVIP音源 1.3.0 · https://raw.githubusercontent.com/pdone/lx-music-source/main/changqing/latest.js
  - 非常刀 v5 · https://raw.githubusercontent.com/pdone/lx-music-source/main/feichangdao/latest.js
  - fish_music 1.9.0 · https://raw.githubusercontent.com/pdone/lx-music-source/main/fish/latest.js
  - 野花🌷 1 · https://raw.githubusercontent.com/pdone/lx-music-source/main/flower/latest.js
  - 野草🌾 1 · https://raw.githubusercontent.com/pdone/lx-music-source/main/grass/latest.js
  - 𝖧౿ᥣᥣ𝗈 Ԝ𝗈𝗋ᥣᑯ 260925 · https://raw.githubusercontent.com/pdone/lx-music-source/main/helloworld/latest.js
  - 幻音音源 v3 · https://raw.githubusercontent.com/pdone/lx-music-source/main/huanyin/latest.js
  - Huibq_lxmusic源 v1.2.0 · https://raw.githubusercontent.com/pdone/lx-music-source/main/huibq/latest.js
  - HYWmusic_公益版 v1.2.0 · https://raw.githubusercontent.com/pdone/lx-music-source/main/hyw/latest.js
  - ikun音源 v22 · https://raw.githubusercontent.com/pdone/lx-music-source/main/ikun/latest.js
  - 杰翔聚合音源 2.3.0 · https://raw.githubusercontent.com/pdone/lx-music-source/main/jiexiang/latest.js
  - 聚合API接口 (CF) 3 · https://raw.githubusercontent.com/pdone/lx-music-source/main/juhe/latest.js
  - 独家音源 7 · https://raw.githubusercontent.com/pdone/lx-music-source/main/lx/latest.js
  - 全豆要[聚合音源] 9.3 93特供版 DeepSeek优化 · https://raw.githubusercontent.com/pdone/lx-music-source/main/qdy/latest.js
  - 轻量音源（四平台多源并行） 2.1.0 · https://raw.githubusercontent.com/pdone/lx-music-source/main/qingliang/latest.js
  - 六音音源 v1.2.1 · https://raw.githubusercontent.com/pdone/lx-music-source/main/sixyin/latest.js
  - 溯音音源 v1 · https://raw.githubusercontent.com/pdone/lx-music-source/main/suyin/latest.js
  - 星海音乐源 v3.2.18 · https://raw.githubusercontent.com/pdone/lx-music-source/main/xinghai/latest.js
  - 星澜聚合音源 (StellarWave) v4.0.2 · https://raw.githubusercontent.com/pdone/lx-music-source/main/xinglan/latest.js
  - lx-玉宁熙-Pro v1.2.5 · https://raw.githubusercontent.com/pdone/lx-music-source/main/yuningxi/latest.js

## 阅读3.0 · legado-with-MD3 · 小说(安卓书架,可追更)
- 仓库：https://github.com/HapeLee/legado-with-MD3
- 本机：`D:\AI\WorkBuddy\Novel\legado-3.26.28-core-universal.apk`
- 源格式：legado 书源 JSON (CSS/JSONPath 规则)
- 说明：原作者 gedoor/legado 仓库已被阅文投诉清空(README 只剩侵权公告、无 release)；此为活跃维护的 Material3 分支，仍在发版。
- 书源 400 条精选（全量 3104）：https://cdn.jsdelivr.net/gh/oyhh/tvbox-sources@main/legado-book-sources-top400.json
  - 导入：阅读App → 我的 → 书源管理 → 右上角 ⋮ → 网络导入 → 粘上面 URL
  - 全量/本地：D:\AI\WorkBuddy\Novel\legado-book-sources.json (全量 3104) / legado-book-sources-top400.json (精选)

## SoNovel · 小说(整本下载 epub/txt)
- 仓库：https://github.com/freeok/so-novel
- 本机：`D:\AI\WorkBuddy\SoNovel\SoNovel\sonovel.exe`
- 源格式：书源规则 JSON
- 说明：只能整本下载，无增量追更；WebUI http://127.0.0.1:7765
- 内置书源 13（rules/main.json），WebUI http://127.0.0.1:7765
  - 香书小说 `http://www.ibiqugu.net/`
  - 书海阁小说网 `https://www.shuhaige.net/`
  - 梦书中文 `http://www.mcxs.la/`
  - 鸟书网 `http://www.99wx.info/`
  - 笔尖中文 `http://www.xbiquwk.com/`
  - 悠久小说网 `http://www.ujxsw.org/`
  - 阅读库 `http://www.yeudusk.com/`
  - 笔趣阁365 `https://www.biquge365.net/`
  - 第八中文网 `https://www.d8zw.com/`
  - 笔趣阁52 `https://www.52bqg.com/`
  - 少年小说网 `https://www.snxsw.com/`
  - 新笔趣阁小说网 `https://www.xbiquge.info/`
  - 笔趣阁info `https://www.bqg.info/`

## Mihon（+ Komikku）· 漫画
- 仓库：https://github.com/mihonapp/mihon （25385★，v0.21.3）
- 源格式：扩展 APK，来自 keiyoushi 扩展库
- 中文扩展 79 个（`keiyoushi/extensions-source` 的 `src/zh`）
- 加仓库（Mihon → 设置 → 浏览 → 扩展）：
  - 官方：`https://github.com/keiyoushi/extensions/raw/repo/index.pb`
  - jsDelivr（推荐）：`https://cdn.jsdelivr.net/gh/keiyoushi/extensions@repo/index.pb`
  - gh-proxy：`https://gh-proxy.com/https://github.com/keiyoushi/extensions/raw/repo/index.pb`
- 备用壳：Komikku https://github.com/komikku-app/komikku （v1.14.1）

## 异次元 · 漫画（备用）
- 图源合集来源：https://github.com/lin686/legado-comic-sources
- 实测可用 19/104 条：`comic/yiciyuan-sources-19.json`
  - https://cdn.jsdelivr.net/gh/oyhh/tvbox-sources@main/comic/yiciyuan-sources-19.json
- 说明：闭源应用，图源靠个人合集维护，站点改版即批量失效 → 主用 Mihon

## 直播源（直连可播，2026-11-18 测活）

`live/live-cn.m3u` —— 82 个频道：📺 央视 11 / 📡 卫视 17 / 🏙 地方台 54

- 地址：https://cdn.jsdelivr.net/gh/oyhh/tvbox-sources@main/live/live-cn.m3u
- MisaTV：设置 → 直播源 → 导入 M3U（也可以直接填这个 URL）
- 验证：主列表 + 首个分片都返回 200/206 才算活，代理全程关闭


## 弹幕接口（MisaTV / LogVar 协议，直连实测）

2026-11-18 真直连三轮重试，只有两个接口能真正取到弹幕 XML：

| 名称 | 地址 | 实测（葬送的芙莉莲 ep1） |
|---|---|---|
| logvar.hhht.cc.cd | https://logvar.hhht.cc.cd | 4340 条 / 28 集 |
| 乔蒂深 | https://logvardm.278612356.xyz/steven | 1563 条 / 28 集 |

- 清单文件：`danmaku/endpoints.json`，说明见 `danmaku/README.md`
- MisaTV 已把这两个设为启用（设置 → 播放与外观 → 字幕与弹幕 → 弹幕接口）
- 其余内置 26 个（炊烟袅袅、Lily、麦当劳、W佬、稳健…）直连全挂，保持关闭
