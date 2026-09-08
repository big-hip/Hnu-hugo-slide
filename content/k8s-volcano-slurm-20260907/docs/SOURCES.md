# 配图来源与许可说明

访问日期：2026-09-07

本目录包含两类配图：项目官方图，以及根据本报告内容绘制的说明图。官方图尽量固定到具体 Git commit，避免上游更新后无法复现。

## 官方图片

| 本地文件 | 用途 | 官方页面 / 仓库 | 固定版本原图 | 许可说明 |
|---|---|---|---|---|
| `kubernetes-components.svg` | Kubernetes 组件关系 | [Kubernetes Components](https://kubernetes.io/docs/concepts/overview/components/) | [kubernetes/website@da36246](https://github.com/kubernetes/website/blob/da362469ceb0802accadb425acbb0576e845d246/static/images/docs/components-of-kubernetes.svg) | Kubernetes 网站内容按 [CC BY 4.0](https://kubernetes.io/docs/home/#license) 提供；使用时保留署名与来源链接 |
| `volcano-architecture.png` | Volcano 控制面与调度流程 | [Volcano Architecture](https://volcano.sh/docs/home/architecture/) | [官网原图](https://volcano.sh/assets/images/arch_2-b7275156fa67c4f872b658ad99877b5c.PNG) | 来源为 Volcano 官方文档；对外再分发时应同时遵循官网及项目当前许可声明 |
| `slinky-operator-architecture.svg` | slurm-operator 在 Kubernetes 中的架构 | [SlinkyProject/slurm-operator](https://github.com/SlinkyProject/slurm-operator) | [slurm-operator@f8f9557](https://github.com/SlinkyProject/slurm-operator/blob/f8f955760285153d1498ad843ace848abc9b9022/docs/_static/images/architecture-operator.svg) | 仓库采用 [Apache-2.0](https://github.com/SlinkyProject/slurm-operator/blob/f8f955760285153d1498ad843ace848abc9b9022/LICENSE) |
| `slurm-architecture.svg` | Slurm 控制器、登录节点与计算节点关系 | [SlinkyProject/slurm-operator](https://github.com/SlinkyProject/slurm-operator) | [slurm-operator@f8f9557](https://github.com/SlinkyProject/slurm-operator/blob/f8f955760285153d1498ad843ace848abc9b9022/docs/_static/images/architecture-slurm.svg) | 仓库采用 [Apache-2.0](https://github.com/SlinkyProject/slurm-operator/blob/f8f955760285153d1498ad843ace848abc9b9022/LICENSE) |
| `kueue-architecture.svg` | Kueue 准入与队列架构 | [Kueue](https://kueue.sigs.k8s.io/) | [kubernetes-sigs/kueue@0727552](https://github.com/kubernetes-sigs/kueue/blob/0727552afba5669f268a2957d34c9d74203ecce1/site/static/images/kueue-architecture.svg) | 仓库采用 [Apache-2.0](https://github.com/kubernetes-sigs/kueue/blob/0727552afba5669f268a2957d34c9d74203ecce1/LICENSE) |
| `jobset-diagram.png` | JobSet 多 Job 编排关系 | [JobSet](https://jobset.sigs.k8s.io/) | [kubernetes-sigs/jobset@d60e758](https://github.com/kubernetes-sigs/jobset/blob/d60e7583902e3208a97ef68d745001b1352f2793/site/static/images/jobset_diagram.png) | 仓库采用 [Apache-2.0](https://github.com/kubernetes-sigs/jobset/blob/d60e7583902e3208a97ef68d745001b1352f2793/LICENSE) |

## 本报告自绘图片

以下 SVG 根据报告中的环境信息和选型结论绘制，采用 1600×900 画布与湖南大学蓝色系，可直接用于本报告和配套幻灯片：

- `current-infrastructure.svg`：当前三节点基础设施、GPU 分池与双调度账本
- `scheduler-comparison.svg`：kube-scheduler、Slurm、Volcano 能力定位对比
- `slinky-vs-volcano-flow.svg`：当前 Slinky 链路与目标 Volcano 链路对比
- `resource-shortage-behavior.svg`：训练与推理在资源不足时的状态变化
- `scheduler-selection-tree.svg`：按工作负载类型选择调度方案

## 使用建议

- 内部汇报可直接使用，但应保留图下注明的项目名称与本文件中的来源记录。
- 对外发布或再分发时，请再次核对上游最新许可与品牌规范。
- 若替换官方图片，应同步更新固定版本链接、访问日期和许可说明。
