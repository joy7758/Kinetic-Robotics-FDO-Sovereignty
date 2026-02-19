# K-RFS: Kinetic Robotics FDO Sovereignty
# K-RFS: 动力学机器人 FDO 主权

## Bilingual Governance Notice
**CN**: 所有标准文档均以中文与英文同步发布，英文为完整翻译版本。  
**EN**: All standards are published in Chinese and English, and the English content must be a full translation.

## 🛡️ Technical Architecture / 技术架构 (Dual-Core Architecture)

The K-RFS ecosystem is powered by a dual-core architecture that bridges kinetic logic with legal compliance.
K-RFS 生态系统采用双核驱动架构，实现了动力学逻辑与法律合规的深度闭环。

| Core Component / 核心组件 | Function / 职能 | Status / 状态 |
| :--- | :--- | :--- |
| 🚀 **[K-RFS Core](https://github.com/joy7758/Kinetic-Robotics-FDO-Sovereignty)** | **Kinetic Entity Layer:** Defines RLCP & K-FDO metadata, locking "Action Sovereignty". <br> **动力学实体层：** 定义 RLCP 协议与 K-FDO 元数据，锁定“动作主权”。 | **Stable / 已上线** |
| ⚖️ **[MCP-Legal-China](https://github.com/joy7758/MCP-Legal-China)** | **Governance Layer:** Translates 2026 DPP regulations into machine code, establishing "Institutional Sovereignty". <br> **治理与合规层：** 将 2026 DPP 法规转化为机器代码，确立“制度主权”。 | **Active / 已上线** |

> **Note:** Protocols for Intelligence (AASP) and Connectivity (DOIP) are natively integrated within the K-RFS Core specification.
> *(注：智能度量 AASP 与通信协议 DOIP 已内置于 K-RFS 核心规范中。)*

---

## 📜 K-FDO Technical Specification / K-FDO 技术规范

### Abstract / 摘要
Traditional robotics data lacks "Agency." K-FDO treats robot actions as living digital entities with a "Metabolic Rate" and "Logic Purity."
传统的机器人数据缺乏“代理权”。K-FDO 将机器人动作视为具有“代谢率”和“逻辑纯度”的活性数字实体。

### Key Metadata Fields / 关键元数据字段

| Field / 字段 | Type / 类型 | Description / 描述 |
| :--- | :--- | :--- |
| `sovereignty_id` | PID/Handle | The unique identity of the action creator. / 动作创建者的唯一身份标识。 |
| `logic_purity` | Float | Percentage of logic decoupled from raw data. / 逻辑从原始数据中解耦的比例。 |
| `metabolic_rate` | Frequency | How often the object updates its internal logic. / 对象更新其内部逻辑的频率。 |

### Regenerative Logic-Core Protocol (RLCP) / 再生逻辑核协议

**Concept / 概念**:
RLCP ensures the "Logic Sovereignty" of the robot. It decouples the abstract computational logic (how to move) from the internal factual storage (what happened today).
RLCP 确保了机器人的“逻辑主权”。它将抽象的计算逻辑（如何动作）与内部的事实存储（今天发生了什么）进行解耦。

**Implementation / 实现路径**:
1. **Distillation / 提炼**: Extracting the neural logic via Information Bottleneck Principle. / 通过信息瓶颈原理提炼神经逻辑。
2. **Metabolism / 代谢**: Periodically "unlearning" noisy factual data to maintain a pure logic core. / 定期“去学习”噪声事实数据，以维持纯净的逻辑核。

### Adaptive Agent Sovereignty Protocol (AASP) / 自适应智能体主权协议

Based on Integrated Information Theory (IIT 4.0), we assign a $\phi$ value to each K-FDO.
基于整合信息理论 (IIT 4.0)，我们为每个 K-FDO 分配一个 $\phi$ 值。

- **$\phi$ < 0.1**: Passive data (Static FDO). / 被动数据 (静态 FDO)。
- **$\phi$ > 0.5**: Autonomous agent with subjective evolution (K-FDO). / 具备主观演化能力的自主智能体 (K-FDO)。
  - Higher $\phi$ values grant the digital object greater autonomy in cross-border data transfer. / 更高的 $\phi$ 值赋予数字对象在跨境数据传输中更大的自主权。

### The Snowflake Effect & Non-stationarity / 雪花效应与非平稳性

**Definition / 定义**:
Even with identical initial parameters, robots develop unique "Electrophysiological Response Patterns" due to environmental micro-fluctuations. This is the **Snowflake Effect**.
即使初始参数完全相同，机器人也会因环境的微小波动而发展出独特的“电生理响应模式”。这就是**雪花效应**。

**K-FDO Solution / K-FDO 解决方案**:
K-FDO captures this non-stationarity by embedding real-time state deviations into the metadata, ensuring each digital entity is unique and sovereign.
K-FDO 通过将实时状态偏差嵌入元数据来捕捉这种非平稳性，确保每个数字实体都是唯一且具备主权的。

### Mathematical Foundation of Sovereignty / 主权的数学基础

To quantify the "Agency" of a K-FDO, we apply the Integrated Information Theory (IIT 4.0) formula:
为了量化 K-FDO 的“代理权”，我们应用整合信息理论 (IIT 4.0) 公式：

$$\Phi = \min_{\mathcal{P}} \{ D_{KL} ( p(s) \parallel \prod_{M \in \mathcal{P}} p(M) ) \}$$

Only K-FDOs with $\Phi > \text{Threshold}$ are granted autonomous decision-making rights in the Digital Biosphere.
在数字生物圈中，只有 $\Phi > \text{阈值}$ 的 K-FDO 才被授予自主决策权。

### 2026 Compliance: Dynamic DPP Implementation / 2026 合规性：动态数字产品护照 (DPP) 实现

Traditional static DPPs cannot track the "Metabolic Drift" of robotic hardware. Our K-FDO architecture provides a **Real-time Compliance Kernel** that updates as the robot ages.
传统的静态 DPP 无法追踪机器人硬件的“代谢漂移”。我们的 K-FDO 架构提供了一个**实时合规内核**，随机器人老化而自动更新状态。

**Key Benefit / 核心优势**:
Compliance status is a self-governing attribute within the K-FDO (Automatic Audit).
合规状态是 K-FDO 内部的自我治理属性，无需外部人工审计（自动审计）。

---

## Belongs to RedRock Constitution / 隶属于红岩宪章体系

This repository is part of the RedRock Constitution architecture framework.

Please start from the central governance hub:

https://github.com/joy7758/RedRock-Constitution

本仓库属于红岩宪章体系，请从总入口开始阅读与理解：

https://github.com/joy7758/RedRock-Constitution
