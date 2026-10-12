# 量潮 Hermes 智能体（quanttide-hermes）

量潮第二大脑适配轴（adapters/）的 Hermes 智能体适配仓库。

## 定位

把 `domains/` 的领域知识接通到 Hermes 智能体：负责提示词装配、上下文装载与工具对接，不生产领域事实，只做接通。

- 上游：`domains/` 领域知识
- 下游：Hermes 智能体

## 结构

| 路径 | 仓库 | 说明 |
|:--|:--|:--|
| `apps/qtcloud-hermes` | [qtcloud-hermes](https://github.com/quanttide/qtcloud-hermes) | Hermes 适配的可部署应用 |
| `data/context` | [quanttide-context-of-hermes-agent](https://github.com/quanttide/quanttide-context-of-hermes-agent) | 语境：素材与未定稿的整理内容 |
| `examples/quanttide-hermes-lab` | [quanttide-hermes-lab](https://github.com/quanttide/quanttide-hermes-lab) | 实验室：接口与信息架构原型 |
| `packages/quanttide-hermes-toolkit` | [quanttide-hermes-toolkit](https://github.com/quanttide/quanttide-hermes-toolkit) | 共享工具包 |

`data/` 放装载进运行时的记忆资产，`docs/` 放供人阅读的文档产物。

其余随实现演进补充。

## 许可

[CC BY 4.0](LICENSE)
