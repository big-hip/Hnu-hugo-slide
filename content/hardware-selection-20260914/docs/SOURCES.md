# 硬件选型 PPT 来源登记

本 deck 使用的材料基线在仓库 `PPT材料/硬件选型/` 下，配图与厂商官方图片的完整清单见
`PPT材料/硬件选型/hardware_selection_assets/official/SOURCES.md`。

## 一、内容底稿

- `PPT材料/硬件选型/HARDWARE_SELECTION_PPT_PLAN.md`：本 deck 的 10 页制作方案。
- `PPT材料/硬件选型/HARDWARE_COMPATIBILITY_EVIDENCE_MATRIX.md`：第 6–8 页逐厂商、逐芯片、逐软件的证据矩阵。
- `PPT材料/硬件选型/推理一体机竞品调研_阶段性完整总结_20260914.md`、`大模型训推一体机商业竞品调研_完整对话与资料汇编.md`、`DeepSeek-R1一体机部署结论_含宝德Atlas关系与对比表.md`：原始调研材料。

## 二、自绘架构图（assets/，可编辑 SVG 见素材目录）

| deck 内文件 | 原始文件 | 用途 |
|---|---|---|
| `six-layer-chain.png` | 素材目录同名图 | 第 1 页：六层技术链 |
| `four-plan-comparison.png` | 同名 | 第 2 页：宝德四套方案总览 |
| `hbm-capacity.png` | 同名 | 第 4 页：A2 HBM 容量对比 |
| `model-selection-tree.png` | 同名 | 第 5 页：模型选型决策树 |
| `compatibility-chain.png` | `国产卡兼容性闭环` | 第 6 页：国产卡软件闭环 |
| `framework-matrix.png` | 同名 | 第 7 页：卡型 × 框架 × 模型矩阵 |
| `commercial-appliance-three-layers.png` | 同名 | 第 8 页：商业名称三层拆解 |
| `evidence-tiers.png` | 同名 | 第 9 页：竞品证据分层 |
| `acceptance-flow.png` | `训推一体机验收流程` | 第 10 页：训推验收流程 |

## 三、厂商官方图片与标识

| deck 内文件 | 来源 | 说明 |
|---|---|---|
| `official-huawei-atlas-800i-a3.png` | e.huawei.com Atlas 800I A3 产品页 | 官方产品图 |
| `official-h3c-linseercube-deepseek.jpg` | h3c.com 灵犀 Cube DeepSeek 文章 | 官方产品线图 |
| `official-mthreads-s5000-oam.jpg` | en.mthreads.com/product/S5000 | 摩尔线程 MTT S5000 OAM 官方图 |
| `assets/logos/*` | Wikimedia Commons / Simple Icons / 厂商官方仓库 | 厂商标识，仅内部引用 |

> 版权归各厂商所有，仅供内部/教学技术汇报引用，不作独立商业宣传素材再分发。

## 四、口径与限制

- 宝德四套配置来自现有转录与调研材料；右侧数量、正式 SKU、价格和销售主体仍需供应商书面确认。
- 矩阵中的“官方路径/待核验”是证据状态，不代表已完成实机验证；不得改写为“已支持并达标”。
- 本 deck 不制作缺少原始数据支持的 TPS、价格或性价比排名。
