**简体中文** | [English](README.en.md)

<p align="center"><img src="mindsoul-logo.png" width="180" alt="MindSoul"></p>
<h1 align="center">MindSoul · 脑机接口基座模型与跨平台研究生态</h1>
<p align="center">Transformer · EEG · Android XR · visionOS · PICO OS 6 · PC</p>
<p align="center"><a href="https://MindSoul.cn">官方网站 · MindSoul.cn</a></p>

MindSoul 团队致力于基于 Transformer 的脑信号解码算法、多模态标注工具和跨平台脑机交互客户端，面向科研团队与医院研究机构，分阶段公开源码，支持个人研究与复现。

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

**32 通道脑机接口设备＋MindSoul 软件平台：整套售价不到人民币 20,000 元，具体配置与报价请微信联系。**

团队将持续优化成本，目标是把 **32 通道、干电极、可移动的脑机接口＋MindSoul 软件平台整套方案降低至人民币 10,000 元以内**。这是后续研发与成本目标，不代表当前售价或当前硬件已具备全部上述规格。

具体硬件配置、软件版本、配件、税费及服务范围以正式报价为准。路线图中的待发布功能不代表已包含在当前交付版本中。采购与科研合作：[MindSoul.cn](https://MindSoul.cn)。

## 跨平台支持方向 · Android XR / visionOS / PICO OS 6

**重点适配 Android XR、visionOS 与 PICO OS 6，并提供 PC 桌面研究入口。** 客户端源码按路线分阶段公开；具体设备、系统版本及可用功能以发布说明为准。

团队提供的眼镜展示包括 **URXR One、XREAL AURA、Apple Vision Pro、PICO 4 Ultra**；更多品牌方向包括玩出梦想。以下沿用原海报中的眼镜图片，展示适配生态，不表示全部型号已完成测试或获得厂商认证。

<p align="center"><img src="poster-xr.jpg" width="720" alt="URXR One、XREAL AURA、Apple Vision Pro 与 PICO 4 Ultra；Android XR、visionOS、PICO OS 6"></p>

## 任务公开进度

进度以可下载源码、版本和说明为依据；当前公开的是主页与路线图，以下勾选项将在实际发布后更新。

- [ ] 首批 · 文字脑信号解码
- [ ] 首批 · 图像脑信号解码
- [ ] 首批 · SSVEP 稳态视觉诱发电位解码
- [ ] 首批 · 运动想象解码
- [ ] 首批 · PC 桌面研究客户端
- [ ] 后续 · 情绪识别
- [ ] 后续 · 专注度识别
- [ ] 后续 · 四肢控制
- [ ] 后续 · 十根手指控制
- [ ] 后续 · 上下左右与方位控制
- [ ] 后续 · Android XR、visionOS、PICO OS 6 客户端源码
- [ ] 后续 · MEG → EEG、EEG → fMRI 标注与翻译器

<p align="center"><img src="poster-tasks.jpg" width="900" alt="MindSoul 七类任务研究方向与扩展任务示意"></p>

海报中的训练与能力描述为团队研究方向展示；源码公开状态以上述清单为准。

## 非侵入式脑机接口生态

**优先支持慧仁创新 32 通道脑机接口；同时支持博睿康（Neuracle）与博瑞恩（Boruien）。** 此为团队提供的适配信息，具体型号、协议和验证结果以各版本兼容说明为准，不代表所有同品牌产品均兼容。

| 重点设备 / 品牌 | 展示素材 |
| --- | --- |
| 慧仁创新 · 32 通道（官网原页面写作“惠仁创欣”） | <img src="product-huirenchuangxin.jpg" width="240" alt="慧仁创新设备展示"> |
| 博瑞恩 · Boruien | <img src="product-boruien-cap.jpg" width="240" alt="博瑞恩脑电设备展示"> |
| 博睿康 · Neuracle | <img src="product-neuracle-device.jpg" width="240" alt="博睿康设备展示"> |

[MindSoul.cn](https://MindSoul.cn) 非侵入式设备页面还列出：BrainCo 强脑科技、BrainLink 脑陆科技（含 Tune、Pro、Lite）、MUSE / InteraXon（含 Muse S Athena）、OpenBCI、IHNNK 华南脑控、NeuroDance 神舞科技。品牌及设备展示不等于正式合作背书；采购前请微信确认具体型号的接入状态。

## 发布状态

本仓库是团队成果展示与发布路线入口。下列项目为计划公开内容；只有提供源码、版本与使用说明后才标记为已发布。当前主页不代表算法、模型权重或客户端已可下载。

| 阶段 | 内容 | 状态 |
| --- | --- | --- |
| 第一阶段 | SSVEP 稳态视觉诱发电位解码 | 优先发布，源码待上传 |
| 第一阶段 | 运动想象（Motor Imagery）解码 | 优先发布，源码待上传 |
| 第一阶段 | PC 桌面研究客户端 | 优先发布，源码待上传 |
| 1,000 Stars 后 | Android XR、visionOS、PICO OS 6 客户端适配 | 后续公开计划 |
| 第一阶段 | 图像识别、文字识别脑信号解码算法 | 优先发布，源码待上传 |
| 1,000 Stars 后 | 十根手指、四肢控制、方位控制 | 后续公开计划 |
| 1,000 Stars 后 | 情绪识别、专注度识别 | 后续公开计划 |
| 1,000 Stars 后 | MEG → EEG、EEG → fMRI 多模态对齐与标注平台 | 后续公开计划 |

文字、图像、SSVEP 与运动想象为首批公开任务，其余任务后续逐步公开。XR 客户端与其他后续模块保留 1,000 Stars 阶段计划，各模块分批发布。具体可用能力、数据集、权重、性能与平台兼容性以每个版本的说明为准。

## 后续源码公开 · 跨模态标注与翻译器

我们计划后续公开 **MEG → EEG** 与 **EEG → fMRI** 的标注与翻译器，按本仓库阶段路线逐步发布。目前为计划方向，尚未在本仓库交付。

“翻译”指研究性的跨模态对齐、表征映射或预测，不表示从 EEG 无损恢复真实 fMRI，也不表示 MEG、EEG、fMRI 可在测量或临床用途上相互替代。发布时将分别说明输入输出、配对数据条件、时间与空间对齐方法、预测不确定性及独立验证结果。

## 研究方向

- **神经解码**：以 Transformer 为研究架构，探索 SSVEP、运动想象、图像与文字任务，以及精细运动和方向意图解码。
- **状态识别**：探索情绪与专注度的脑信号建模。
- **多模态标注**：建设 MEG → EEG、EEG → fMRI 的对齐、标注和验证工作流。
- **跨平台交互**：连接 PC、Android XR、visionOS 与 PICO OS 6 的研究客户端。

上述方向不构成已验证性能或临床有效性声明。

## 使用许可

使用范围详见 [LICENSE](LICENSE)。商业使用或机构合作，请通过 [MindSoul.cn](https://MindSoul.cn) 或下方微信联系 MindSoul团队，另行取得授权。

## 科研引用

如果使用本项目的软件、算法、模型或工具开展研究并发表论文、报告或其他成果，请在参考文献或致谢中注明 **MindSoul团队**，并提供本仓库地址及实际使用的版本或提交编号。请清楚说明使用了哪些模块，以便复现。

建议引用：MindSoul团队. *MindSoul：脑机接口基座模型与跨平台研究生态* [软件项目]. https://github.com/MindSoulBCI/MindSoul （请补充所用版本或提交编号及访问日期）。

机器可读引用信息见 [CITATION.cff](CITATION.cff)。当前引用对象为项目仓库，不代表已有正式发表论文或 DOI。引用不构成论文共同作者要求；论文署名应依据实际学术贡献与期刊规范确定。

## 团队与联系

- 成都（上海）脑云矩阵科技有限公司
- 官方网站：[MindSoul.cn](https://MindSoul.cn)
- 微信咨询：请扫描下方“跨平台终端与空间计算”海报内的微信二维码，咨询配置、报价及科研合作。[打开微信联系海报原图](poster-xr.jpg)。

## English

[Read the full English documentation →](README.en.md)

MindSoul explores Transformer-based brain-signal decoding, multimodal annotation and cross-platform BCI research clients. Phase 1 prioritizes text and image decoding, SSVEP, motor imagery and the PC desktop client. Further algorithms, XR clients and MEG-to-EEG and EEG-to-fMRI annotation and translation tools are planned after this flagship repository reaches 1,000 stars. Code availability will be documented per release. See LICENSE for permitted use. Contact the MindSoul team for commercial or institutional licensing. No clinical validation is implied.

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

<!-- mindsoul-huggingface:start -->
## Hugging Face · 七大 Neural AI 模型

七个模型介绍页已上线，状态为 **准备发布 · 即将更新**；尚未发布模型权重或评测结果。

- [图像识别](https://huggingface.co/mindsoulBCI/mindsoul-image)
- [文字识别](https://huggingface.co/mindsoulBCI/mindsoul-text)
- [情绪识别](https://huggingface.co/mindsoulBCI/mindsoul-emotion)
- [专注力识别](https://huggingface.co/mindsoulBCI/mindsoul-attention)
- [四肢控制](https://huggingface.co/mindsoulBCI/mindsoul-limbs)
- [方位识别与控制](https://huggingface.co/mindsoulBCI/mindsoul-direction)
- [十根手指识别与控制](https://huggingface.co/mindsoulBCI/mindsoul-fingers)

### 首批任务与评测入口 · 即将发布

- [SSVEP](https://huggingface.co/mindsoulBCI/mindsoul-ssvep) — 准备发布 · 即将更新
- [运动想象](https://huggingface.co/mindsoulBCI/mindsoul-motor-imagery) — 准备发布 · 即将更新
- [Benchmark](https://huggingface.co/spaces/mindsoulBCI/benchmark) — 准备发布 · 即将更新

[MindSoul 团队主页](https://huggingface.co/mindsoulBCI)

公司：**成都（上海）脑云矩阵科技有限公司**
<!-- mindsoul-huggingface:end -->
