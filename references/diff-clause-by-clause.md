# ISO 14001:2015 ↔ 2026(FDIS) 逐条款差异库

> **数据来源（重要）**：本差异库的所有 2015 与 2026 内容，均摘自用户提供的两份 PDF，经 fitz 渲染 300 DPI 图像 + RapidOCR 识别提取的真实原文（非模型生成）：
> - **2026 侧**：`C:/Users/admin/Downloads/ISO 14001：2026（FDIS）(最终草案版，供参考).pdf` → 完整原文见 `standard-2026-cl4.md` ~ `standard-2026-cl10.md` + `standard-2026-annexA.md`
> - **2015 侧**：`C:/Users/admin/Downloads/GBT24001-2016（idt ISO14001-2015）环境管理体系 要求及使用指南.pdf` → 完整原文见 `standard-2015-cl4.md` ~ `standard-2015-cl10.md` + `standard-2015-annexA.md`
> - **草案标注**：2026 版基于 FDIS 最终草案，非正式发布版；OCR 可能存在个别字符误差。正式版发布后请以官方原文为准并复核本库。
>
> **变化性质总判断**：2026 版**框架结构（HLS 十章 1–10）未变**，本质为三件事——① 与最新 ISO 管理体系标准协调统一（术语/结构/措辞，如 outsourced→external provider、fulfil→meet）；② 整合气候变化修订（Amd1:2024）；③ 关键主题要求澄清。属"协调+整合+澄清"型修订，非颠覆性重写。本库所有判断以真实原文比对为准。

---

## 一、结构层级变化总览

| 章节 | 2015 版结构 | 2026 版结构 | 变化 |
|---|---|---|---|
| 6.1 策划 | 6.1.1 总则 / 6.1.2 环境因素 / 6.1.3 合规义务 / 6.1.4 措施的策划 | 6.1.1 总则 / 6.1.2 环境因素 / 6.1.3 合规义务 / **6.1.4 风险和机遇（新增独立）** / **6.1.5 措施策划（新增独立）** | **重大重组**（原 6.1.4 拆分为 6.1.4+6.1.5） |
| 4.1 | 一般表述内外部问题 | 明确列举 climate change / biodiversity / ecosystem health | 强化/具体化 |
| 4.2 | 相关方需求期望 | NOTE 明确含气候/生物多样性相关需求 | 强化 |
| 4.3 | 范围确定 | 新增 f) 生命周期控制/影响能力 | 新增要求 |
| 5.2 | 保护环境的承诺 | NOTE 明确含生物多样性/生态系统保护 | 强化 |
| 8.1 | 运行策划（含生命周期观点） | 生命周期视角措辞强化（设计/采购/外供方/报废各阶段明示） | 强化（措辞） |
| 9.3.2 | 管理评审输入（含风险和机遇） | 措辞协调，风险机遇输入保留 | 澄清（2015 已含，非新增） |

> 术语章节（原 3.1–3.2 字母序）在 2026 中按职能重分组，但本技能聚焦"要求条款 4–10"的升版差异，术语变化见 `new-2026-terms.md`。

---

## 二、逐条款差异（要求条款 4–10）

### 4 组织所处环境（Context of the organization）

#### 4.1 理解组织及其环境
- **变化类型**：强化 / 具体化
- **2026 原文（4.1）**：*"The organization shall determine external and internal issues that are relevant to its purpose and that affect... its ability to achieve the intended outcomes... Such issues can include... environmental conditions, such as pollution levels, availability of natural resources, climate change, biodiversity or ecosystem health (see A.4.1)."*
- **2015 原文（4.1）**：确定与宗旨相关、影响 EMS 预期结果能力的内外部问题（一般表述，未列举具体环境条件）。
- **对企业的含义**：组织环境分析必须**显性纳入**气候变化、生物多样性、生态系统健康议题，不能泛泛写"法律法规"。Annex A.4.1 扩展了生态系统健康定义及气候与其他环境条件的相互作用说明（详见 `standard-2026-annexA.md` A.4.1）。

#### 4.2 理解相关方的需求和期望
- **变化类型**：强化（与 4.1 呼应）
- **2026 原文（4.2 NOTE 1）**：*"needs and expectations of interested parties can include those related to environmental conditions such as pollution levels, availability of natural resources, climate change, biodiversity or ecosystem health."*
- **2015 原文（4.2）**：确定相关方及有关需求和期望（即要求），哪些成为合规义务（未列举环境条件类需求）。
- **对企业的含义**：投资者/社区/监管对气候、生物多样性的诉求，需作为合规义务识别输入。

#### 4.3 确定环境管理体系的范围
- **变化类型**：新增要求
- **2026 原文（4.3 f)）**：在确定范围时考虑项中**新增 f) "its authority and ability to exercise control and influence, over the life cycle of its activities, products and services"**（对生命周期行使控制和影响的能力与权限）。
- **2015 原文（4.3）**：考虑 4.1 内外部问题、4.2 合规义务、组织单元/职能/物理边界、活动产品服务。
- **对企业的含义**：范围说明需论证对生命周期各阶段的控制/影响力边界。

#### 4.4 环境管理体系
- **变化类型**：澄清（措辞更新，实质不变）
- **2026 原文（4.4）**：明确"establish, implement, maintain and continually improve an environmental management system, including the processes needed and their interactions, in accordance with the requirements of this document"；并强调考虑 4.1/4.2 中获得的知识。
- **2015 原文（4.4）**：建立、实施、保持和持续改进 EMS，包括所需过程及其相互作用。
- **对企业的含义**：无新增硬性要求，强调过程整合与知识管理（详见 Annex A.4.4）。

### 5 领导作用（Leadership）

#### 5.1 领导作用与承诺
- **变化类型**：澄清（措辞协调）
- **2026 原文（5.1 NOTE）**：*"Reference to 'business' in this document can be interpreted broadly to mean those activities that are core to the purpose(s) of the organization's existence."*
- **2015 原文（5.1 注）**："业务"可广义理解为涉及组织存在目的的那些核心活动。
- **对企业的含义**：基本一致，消除"业务"狭义歧义。

#### 5.2 环境方针
- **变化类型**：强化（承诺内容扩展）
- **2026 原文（5.2 NOTE）**：*"Other specific commitment(s) to protect the environment can include: preservation or conservation of natural resources; sustainable resource use; climate change mitigation and adaptation; or protection of biodiversity and ecosystems."*
- **2015 原文（5.2）**：包括保护环境的承诺（含污染预防及其他与组织所处环境有关的特定承诺）——**无此 NOTE 列举**。
- **对企业的含义**：方针若涉及自然相关议题，应明确写入生物多样性/生态系统保护承诺，与新规导向一致（详见 Annex A.5.2）。

#### 5.3 角色、职责和权限
- **变化类型**：实质不变（措辞协调）

### 6 策划（Planning）—— 变化最大章节

#### 6.1.1 总则
- **变化类型**：澄清（过程范围扩展）
- **2026 原文（6.1.1）**：建立、实施和保持满足 **6.1.2 至 6.1.5** 要求所需的过程。
- **2015 原文（6.1.1）**：满足 6.1.2 至 6.1.4 要求（原 6.1.4 为措施策划）。
- **对企业的含义**：过程范围随 6.1.4/6.1.5 拆分而扩展。

#### 6.1.2 环境因素
- **变化类型**：强化（生命周期视角 + 紧急情况 + 有益影响）
- **2026 原文（6.1.2）**：确定环境因素时"considering a life cycle perspective"；明确"shall determine potential emergency situations... including those that can have an environmental impact"；NOTE 2 明确"Significant environmental aspects can result in risks and opportunities associated with either adverse or beneficial environmental impacts"。
- **2015 原文（6.1.2）**：确定能够控制或能够施加影响的环境因素及其环境影响（生命周期视角在 8.1 单独表述，此处未显式要求）。
- **对企业的含义**：环境因素识别须**显式纳入生命周期视角**与**潜在紧急情况**；显著环境因素可带来风险与机遇（含有益影响），识别逻辑更全面。

#### 6.1.3 合规义务
- **变化类型**：实质不变（措辞协调，outsourced→external provider 等）

#### 6.1.4 风险和机遇 ★新增独立条款
- **变化类型**：**新增**（原整合在 6.1 总则，2026 独立成条）
- **2026 原文（6.1.4）**：*"When planning for the environmental management system, the organization shall consider: a) the external and internal issues referred to in 4.1; b) the relevant needs and expectations... of interested parties referred to in 4.2; c) the scope of its environmental management system referred to in 4.3: and determine the risks and opportunities to the organization related to its environmental aspects (see 6.1.2), compliance obligations (see 6.1.3) and other issues and requirements... identified in 4.1 and 4.2 that need to be addressed to: give assurance that the EMS can achieve its intended outcomes; prevent, or reduce, undesired effects...; achieve continual improvement. The risks and opportunities that need to be addressed shall be available as documented information."*
- **2015 对应**：2015 的 6.1 总则仅要求"针对风险和机遇确定措施"，未单列"风险和机遇的确定"过程。
- **对企业的含义**：**必须新建"风险和机遇确定"过程**（识别→登记册→文件化信息），将 4.1/4.2/6.1.2/6.1.3 的风险机遇显式归集管理。这是 2026 升版最实质的新增管理要求。

#### 6.1.5 措施策划（Planning action） ★新增独立条款
- **变化类型**：**新增**（原 6.1.4 措施策划拆分独立）
- **2026 原文（6.1.5）**：*"The organization shall plan: a) to take actions to address its: 1) significant environmental aspects determined in 6.1.2; 2) compliance obligations determined in 6.1.3; 3) risks and opportunities determined in 6.1.4; b) how to: 1) implement the actions into its EMS processes... or integrate the actions into other business processes; 2) evaluate the effectiveness of these actions (see 9.1)."*
- **2015 对应**：2015 的 6.1.4 措施策划涵盖上述动作，但未独立成条。
- **对企业的含义**：措施策划需覆盖"显著环境因素 + 合规义务 + 风险机遇"三类输入，并明确实施与有效性评价方式。

#### 6.2 环境目标及其实现的策划
- **变化类型**：强化（目标需考虑风险机遇）
- **2026 原文（6.2.1）**：建立环境目标时"taking into account... related compliance obligations, and considering its risks and opportunities"。
- **2015 原文（6.2.1）**：建立环境目标时考虑重要环境因素和相关合规义务（未提风险机遇）。
- **对企业的含义**：目标设定逻辑纳入风险机遇维度。

#### 6.3 变更的策划
- **变化类型**：实质不变（措辞协调）

### 7 支持（Support）
- **变化类型**：实质不变（措辞协调统一，如 outsourced process→externally provided process、documented information 表述）
- 7.1 资源 / 7.2 能力 / 7.3 意识 / 7.4 信息交流 / 7.5 文件化信息：要求框架与 2015 一致，详见 `standard-2026-cl7.md` 与 `standard-2015-cl7.md` 原文比对。

### 8 运行（Operation）

#### 8.1 运行策划和控制
- **变化类型**：强化（生命周期视角措辞明示）
- **2026 原文（8.1）**：*"Consistent with a life cycle perspective, the organization shall: a) establish controls... to ensure that its environmental requirement(s)... is (are) addressed in the design and development process... considering each life cycle stage; b) determine its environmental requirement(s) for the procurement...; c) communicate... to external providers...; d) consider the need to provide information about potential significant environmental impacts associated with the transportation or delivery, use, end-of-life treatment and final disposal..."*
- **2015 原文（8.1）**：从生命周期观点出发，组织应 a) 设计开发落实环境要求；b) 确定采购环境要求；c) 与外部供方沟通；d) 考虑提供运输/使用/寿命结束后处理/最终处置相关重大环境影响信息的需求。——**框架一致，2026 措辞更显式（each life cycle stage 明示）**。
- **对企业的含义**：设计、采购、外供方、报废各阶段的环境控制要求被更清晰地法定化，运行控制程序需逐一覆盖。

#### 8.2 应急准备和响应
- **变化类型**：实质不变（措辞协调；2026 明确应急情况"determined in 6.1.2"）

### 9 绩效评价（Performance evaluation）

#### 9.1 监视、测量、分析和评价 / 9.1.2 合规性评价
- **变化类型**：实质不变（措辞协调；2026 用 "meet its compliance obligations" 替代 "fulfil"）

#### 9.2 内部审核
- **变化类型**：实质不变（措辞协调）

#### 9.3 管理评审
- **变化类型**：澄清（**纠正常见误判**：2015 的 9.3 输入 b)4) 本就含"风险和机遇"，2026 保留该项并做措辞协调，**非 2026 新增**）
- **2026 原文（9.3.2 b)4)）**：*"risks and opportunities"*（管理评审输入含风险和机遇）
- **2015 原文（9.3）**：管理评审输入 b) 相关方的需求和期望包括合规义务、其重要环境因素、**风险和机遇**——2015 已列"风险和机遇"。
- **对企业的含义**：管理评审输入保留风险机遇项，升版时无需新增该输入，但应确保风险机遇登记册（6.1.4）的输出能流入管理评审。

### 10 改进（Improvement）
- **变化类型**：实质不变（措辞协调统一）
- 10.1 持续改进 / 10.2 不符合和纠正措施 / 10.3 持续改进：框架与 2015 一致，详见 `standard-2026-cl10.md` 与 `standard-2015-cl10.md`。

---

## 三、升版必补清单（基于真实原文）

| 序号 | 必补项 | 对应条款 | 性质 |
|---|---|---|---|
| 1 | 新建"风险和机遇确定"过程 + 登记册（文件化信息） | 6.1.4（新增） | 硬性新增 |
| 2 | 措施策划覆盖"风险机遇"输入 | 6.1.5（新增） | 硬性新增 |
| 3 | 组织环境分析显性纳入气候/生物多样性/生态系统健康 | 4.1 / 4.2 | 强化 |
| 4 | 方针可写入生物多样性/生态系统保护承诺 | 5.2 | 强化 |
| 5 | 范围说明论证生命周期控制/影响力 | 4.3 f) | 新增要求 |
| 6 | 环境因素识别纳入生命周期视角 + 潜在紧急情况 | 6.1.2 | 强化 |
| 7 | 运行控制程序覆盖设计/采购/外供方/报废各阶段 | 8.1 | 强化（措辞） |
| 8 | 目标设定纳入风险机遇维度 | 6.2.1 | 强化 |
| 9 | 管理评审输入风险机遇（2015 已含，确认保留） | 9.3.2 | 澄清 |
| 10 | 全文措辞协调（external provider / meet compliance obligations 等） | 全文 | 澄清 |

> 本差异库为导航索引；每个条款的**完整真实原文**见对应 `standard-2026-clX.md` / `standard-2015-clX.md`。Agent 在回答具体条款差异时，应优先读取这些原文文件而非仅凭本库摘要。
