# TVBox 直连源（2026-11-17 实测）

不挂代理实测可用的 TVBox 配置，自用。

- `tvbox-cms-direct.json` — 单配置，44 个采集站，全部直连实测 `ac=list` 有返回（0.7–5s）
- `tvbox-stores-direct.json` — 多仓索引，42 个仓库不挂代理也能拉到

TVBox / 影视仓里填地址，jsDelivr 那条国内直连最稳：

```
https://cdn.jsdelivr.net/gh/oyhh/tvbox-sources@main/tvbox-cms-direct.json
https://cdn.jsdelivr.net/gh/oyhh/tvbox-sources@main/tvbox-stores-direct.json
```

raw.githubusercontent 国内直连超时，别直接用。

## 壳 + 源 总清单

见 [SOURCES.md](SOURCES.md)（人看）与 [sources.json](sources.json)（机读）。覆盖 4 个壳子与其可用源：
MisaTV（44 采集站 + 42 多仓 + 18 条 Kazumi 动漫规则）、洛雪音乐（20 个自定义音源）、SoNovel（14 个内置书源）、HGhub（14 个 HPP 插件）。
