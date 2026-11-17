# 漫画：壳 + 源（2026-11-18 实测）

## 结论：建议从异次元换到 Mihon（或 Komikku），异次元留作备用

| | 异次元 | Mihon | Komikku（Mihon 的增强分支） |
|---|---|---|---|
| 开源 | 闭源 | ✅ Apache-2.0 | ✅ Apache-2.0 |
| 仓库热度 | 无公开仓库 | 25385★ | 5036★ |
| 最近更新 | — | v0.21.3（2026-10-25） | v1.14.1（2026-07-17） |
| 源形态 | 图源 JSON（手工合集） | 扩展 APK（自动更新） | 同 Mihon |
| 中文源 | 靠个人合集，我这批 104 条里只有 19 条还活着 | keiyoushi 官方扩展库，`src/zh` 里 **79 个中文扩展** | 同 Mihon |
| 书架/追更 | 有，但源失效就没有替代 | 书架 + 自动检查更新 + 多源聚合 | 同 Mihon，另有 tracker/主题增强 |

**为什么换**：异次元本身能用，问题在"源"——闭源软件没有持续维护的源仓库，图源全靠个人整理，站点一改版就成批失效（实测 104 → 19）。Mihon 的扩展是带签名、可自动更新的 APK，腾讯漫画、漫画柜、动漫屋、漫画人、快看、漫客栈这些都有现成扩展，不用自己盯规则。

## Mihon 安装（安卓）

- 下载：https://github.com/mihonapp/mihon/releases/latest
  - `mihon-arm64-v8a-v0.21.3.apk`（27.8MB，绝大多数手机）
  - `mihon-armeabi-v7a-v0.21.3.apk`（24.6MB，老 32 位机型）
  - `mihon-v0.21.3-foss.apk`（67.3MB，全架构）
- 装完：**更多 → 设置 → 浏览 → 扩展** → 添加仓库，粘贴下面任一个：
  - 官方（GitHub 直连，国内常超时）：`https://github.com/keiyoushi/extensions/raw/repo/index.pb`
  - jsDelivr 镜像（推荐）：`https://cdn.jsdelivr.net/gh/keiyoushi/extensions@repo/index.pb`
  - gh-proxy 镜像：`https://gh-proxy.com/https://github.com/keiyoushi/extensions/raw/repo/index.pb`
- 仓库加好后逐个装中文扩展（漫画柜 / 动漫屋 dm5 / 漫画人 / 快看 / 漫客栈 / 腾讯漫画 / 拷贝漫画 …）。

> 注意：keiyoushi 现在用的索引是 `index.pb`（Mihon 0.20.1+ 的新格式），老的 `index.min.json` 里只剩两条"Outdated App"占位，别再用它。

## 异次元备用：导入这 19 条图源

`yiciyuan-sources-19.json`（80KB，19 条，JSON 数组）

- 网络导入（jsDelivr）：`https://cdn.jsdelivr.net/gh/oyhh/tvbox-sources@main/comic/yiciyuan-sources-19.json`
- 或把文件传到手机，异次元 → 图源 → 本地导入
- 这 19 条是我从 `lin686/legado-comic-sources` 的 104 条里筛出来的：先探首页（28/104 通），再用「斗破苍穹」实测搜索接口，最终 **19 条搜索返回 200 且有结果**。
- 名单：土豪漫画网-M、动漫屋、邪恶集(18禁)、漫客栈(正版)、咚漫-M、知音漫客-M、GMANHUA、热血漫画、168漫画-M、前未漫画-M、大古漫画-M、1316漫画网-M、七夕漫画-M、咚漫、漫本、腾讯漫画(正版)、漫画人、极速漫画、腐漫画。

## 站点可达性（直连、模拟手机 UA）

- 直连 200：manhuagui 漫画柜 158KB、dm5 动漫屋 436KB、manhuaren 12KB、kuaikan 225KB
- 需代理：mangabz、colamanga、mangacopy
- 403/超时：baozimh 直连与代理都 403；copymanga 超时
- 腾讯漫画、快看这类正版源只放免费章节，想全看要付费，属正常。
