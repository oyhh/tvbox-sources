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