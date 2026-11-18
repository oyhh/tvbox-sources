# 弹幕接口（LogVar 协议，直连可用）

协议：`{base}/api/v2/search/anime?keyword=` → `{base}/api/v2/bangumi/{animeId}` → `{base}/api/v2/comment/{episodeId}?format=xml`

## 2026-11-18 实测（真直连 + 三轮重试 + 取到弹幕 XML）

| 接口 | 地址 | 弹幕条数（葬送的芙莉莲 ep1） |
|---|---|---|
| 乔蒂深 | https://logvardm.278612356.xyz/steven | 1563 |
| logvar.hhht.cc.cd | https://logvar.hhht.cc.cd | 4340 |

其余 26 个常见接口（炊烟袅袅、Lily、麦当劳、墨云阁、W佬、稳健…）当前直连全部失败：海外主机被墙、403/401、或早已停服。**走代理可能能活，但本机是直连环境，没收录。**

## 怎么用

- MisaTV：设置 → 弹幕 → 接口清单，把上面的地址粘进去（一行一个，可写 `名字@地址`），或者直接开内置的
- 通用：任何支持 LogVar 协议的播放器都能用

## 复测

```powershell
python D:\AI\WorkBuddy\TVBox-PC\test_dm_final.py
```
