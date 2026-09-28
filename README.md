# dsh-policy-analysis

DSH 政策解读插件（包名 `@local/policy-analysis`）。源码 = 8.6 宿主 live 副本快照（2026-09-28，`~/01-DSH/07-政策解读插件/policy-analysis`）。部署：宿主 profile + 10 个用户 profile，11 份副本 tar 聚合 md5 全部一致。

## 结构

- `client.js` — 面板/交互（前端）
- `index.js` — 服务端注册入口
- `locale/` — zh/en 双语文案

## 发行件

`dist/dsh-policy-analysis-1.4.2.tgz` —— 确定性构建（校验见 [CHECKSUMS.md](dist/CHECKSUMS.md)）。

## 版本

| 版本 | 内容 |
| --- | --- |
| 1.4.2 | 首发 = 8.6 线上活副本快照（2026-09-28） |
