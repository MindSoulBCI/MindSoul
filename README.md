<p align="center"><img src="mindsoul-logo.png" width="180" alt="MindSoul"></p>
<h1 align="center">MindSoul · 脑机接口基座模型与跨平台研究生态</h1>
<p align="center">Transformer · EEG · Multimodal Alignment · Spatial Computing</p>
<p align="center"><a href="https://MindSoul.cn">官方网站 · MindSoul.cn</a></p>

MindSoul 团队致力于基于 Transformer 的脑信号解码算法、多模态标注工具和跨平台脑机交互客户端，面向科研团队与医院研究机构，分阶段公开源码，支持非商业学习、复现与研究。

## 团队使命 · 严肃科研，探索意识与交互的未来

MindSoul 致力于脑信号解码、多模态神经数据研究与跨平台交互。我们希望降低脑机接口科研门槛，让研究者在可复现、可审计的流程中探索人类意识与数字技术的关系。

**长期愿景：探索未来意识上传与意识延续的科学可能性，让人类尽可能早地受益于相关研究。** “意识永生”是团队的探索愿景，不是已实现的能力或可交付承诺；数字人、脑信号解码与数据保存不等同于意识转移，也不能证明个人意识或身份的延续。

**交互愿景：从有限指令走向广泛设备协同。** 我们以“万物控制”表达跨设备交互的长期目标；当前与未来版本仅支持各自明确列出的设备、任务和指令，不承诺任意设备、任意想法的直接控制。实际控制应具有用户明确授权、确认、停止与故障回退机制。

**严肃科研，非诊疗用途。** 本项目面向研究、教学与探索性体验，不用于医学诊断、治疗或替代专业医疗服务，不宣称已有医疗有效性或临床准入资格。

## 研究规范与伦理边界

以下是团队拟遵循的研究与发布要求，不代表已经获得伦理审批、认证或完成全部验证：

- 涉及人体参与的研究，应按适用要求完成伦理审查与知情同意；说明采集内容、用途、保存期限、共享范围、退出与数据处理安排。
- 不在公共仓库上传可识别的受试者原始数据、身份资料或未经授权的数据；代码公开不等于脑信号数据公开。
- 不将模型输出作为对个人真实情绪、意图、人格或意识内容的确定判断，不用于未经同意的监控。
- 发布时说明训练数据授权、被试级划分、跨天及跨设备测试、基线、误差、失败案例与适用限制；待验证结果保持明确标识。
- 体验者招募与产品采购分开说明；参与研究不意味着获得意识上传、永生或医疗收益。

## 32 通道科研套装

**32 通道脑机接口设备＋MindSoul 软件平台：人民币 10,000 元 / 套。**

具体硬件配置、软件版本、配件、税费及服务范围以正式报价为准。路线图中的待发布功能不代表已包含在当前交付版本中。采购与科研合作：[MindSoul.cn](https://MindSoul.cn)。

## 发布状态

本仓库是团队成果展示与发布路线入口。下列项目为计划公开内容；只有提供源码、版本与使用说明后才标记为已发布。当前主页不代表算法、模型权重或客户端已可下载。

| 阶段 | 内容 | 状态 |
| --- | --- | --- |
| 第一阶段 | SSVEP 稳态视觉诱发电位解码 | 优先发布，源码待上传 |
| 第一阶段 | 运动想象（Motor Imagery）解码 | 优先发布，源码待上传 |
| 第一阶段 | PC 桌面研究客户端 | 优先发布，源码待上传 |
| 1,000 Stars 后 | Android XR、visionOS、PICO OS 6 客户端适配 | 后续公开计划 |
| 1,000 Stars 后 | 图像识别、文字识别脑信号解码算法 | 后续公开计划 |
| 1,000 Stars 后 | 十根手指、四肢控制、方位控制 | 后续公开计划 |
| 1,000 Stars 后 | 情绪识别、专注度识别 | 后续公开计划 |
| 1,000 Stars 后 | MEG → EEG、EEG → fMRI 多模态对齐与标注平台 | 后续公开计划 |

以本成果主仓库的 GitHub Stars 达到 1,000 为第二阶段公开节点，各模块分批发布。具体可用能力、数据集、权重、性能与平台兼容性以每个版本的说明为准。

## 后续源码公开 · 跨模态标注与翻译器

我们计划后续公开 **MEG → EEG** 与 **EEG → fMRI** 的标注与翻译器，按本仓库阶段路线逐步发布。目前为计划方向，尚未在本仓库交付。

“翻译”指研究性的跨模态对齐、表征映射或预测，不表示从 EEG 无损恢复真实 fMRI，也不表示 MEG、EEG、fMRI 可在测量或临床用途上相互替代。发布时将分别说明输入输出、配对数据条件、时间与空间对齐方法、预测不确定性及独立验证结果。

## 研究方向

- **神经解码**：以 Transformer 为研究架构，探索 SSVEP、运动想象、图像与文字任务，以及精细运动和方向意图解码。
- **状态识别**：探索情绪与专注度的脑信号建模。
- **多模态标注**：建设 MEG → EEG、EEG → fMRI 的对齐、标注和验证工作流。
- **跨平台交互**：连接 PC、Android XR、visionOS 与 PICO OS 6 的研究客户端。

上述方向不构成已验证性能或临床有效性声明。医院机构可在许可范围内用于非商业学习与研究；诊疗、收费服务或商业部署不在本许可授权范围内。

## 使用许可

**源码公开 · 仅限非商业学习与研究 · 禁止商业使用。**

采用自定义 [MindSoul 非商业学习与研究许可](LICENSE)。这是一种 source-available 许可，不属于 OSI 认可的开源许可。第三方依赖遵循其原有许可；本许可不覆盖第三方权利。

## 团队与联系

- 成都市脑云矩阵科技有限公司
- 上海市脑云矩阵科技有限公司
- 官方网站：[MindSoul.cn](https://MindSoul.cn)

## English

MindSoul explores Transformer-based brain-signal decoding, multimodal annotation and cross-platform BCI research clients. Phase 1 prioritizes SSVEP, motor imagery and the PC desktop client. Further algorithms, XR clients and MEG-to-EEG and EEG-to-fMRI annotation and translation tools are planned after this flagship repository reaches 1,000 stars. Code availability will be documented per release. Non-commercial learning and research only; commercial use is prohibited. No clinical validation is implied.

## 品牌与探索计划 · 海报展示

以下为团队提供的历史宣传与概念素材，保留原图。海报中的“数字永生”“基座大模型”等用语应结合本页愿景及研究状态说明理解，不构成效果保证。海报里的 fMRI → EEG 为原素材方向；当前后续发布计划以本页 MEG → EEG、EEG → fMRI 为准。海报中的功能、招募及购买信息以官方最新说明与具体交付版本为准；概念图不代表已验证产品能力，路线图不代表相关源码已经公开。

### MindSoul · 脑机接口平台
<p align="center"><img src="poster-platform.jpg" width="600" alt="MindSoul 脑机接口平台宣传海报"></p>

### 跨平台终端与空间计算
<p align="center"><img src="poster-xr.jpg" width="600" alt="MindSoul 终端与 Android XR、visionOS、PICO OS 6 适配方向"></p>

### 情绪、专注度与 MR 交互探索
<p align="center"><img src="poster-bci.png" width="600" alt="MindSoul 脑机接口与 MR 交互宣传海报"></p>

### 人类数字永生计划 · 探索愿景与体验者招募
<p align="center"><img src="poster-digital-life.jpg" width="600" alt="MindSoul 人类数字永生探索计划与体验者招募海报"></p>

参与相关体验不意味着获得意识上传或意识永生服务。具体参与条件、数据使用及知情同意安排请通过 [MindSoul.cn](https://MindSoul.cn) 了解。
