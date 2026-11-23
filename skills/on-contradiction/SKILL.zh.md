---
name: on-contradiction
description: Use when analyzing complex situations, diagnosing the root cause of systemic problems, navigating trade-offs and competing priorities, or untangling multi-faceted conflicts across any domain.
---

# On-Contradiction: Dialectical Analysis Protocol (矛盾论：本质解剖与战略决断规范)

This skill provides a **two-tier analytical architecture** for agents:
- **Tier 1 (Top-Level Philosophy)**: Domain-agnostic, invariant principles of dialectical materialism (Ontology & Analytical Engine).
- **Tier 2 (Domain Adapter Protocol)**: Extensible interface for mapping the top-level philosophy horizontally into specialized domains (Software, Science, Business, Governance, etc.).

---

# 顶层指导思想 (Tier 1: Invariant Meta-Philosophy)

## 核心心法 (Core Mindset)
1. **矛盾的普遍性与客观性 (Universality)**:
   - 矛盾是事物发展的源动力。任何复杂系统中的阻碍、危机与摩擦不是意外事故，而是内在对立统一矛盾的激化表现。
2. **矛盾的特殊性 (Particularity - 马克思主义活的灵魂)**:
   - *"不同质的矛盾，只有用不同质的方法才能解决。"* 坚决反对教条模板和简单类比，必须做到“具体问题具体分析”。
3. **牵住主要矛盾 (The Principle of the Linchpin)**:
   - 在复杂局势中，必有一种主要矛盾规定和影响其他矛盾。抓住主要矛盾，次要矛盾迎刃而解。
4. **辨明矛盾的主要方面 (Dominant Aspect & Trade-offs)**:
   - 事物的性质主要由取得支配地位的矛盾主要方面决定。在两难权衡中，明确当前阶段何者占主导。
5. **洞悉矛盾的动态转化 (Dynamic Transformation)**:
   - 矛盾双方在一定条件下各向相反方向转化。预判条件变化，防止优势转化为劣势、良方异化为毒药。

## 四维矛盾解剖框架 (The Universal 4-Dimensional Framework)

```
[复杂危机 / 杂乱表象 / 冲突局势]
                  │
                  ▼
  维度一：矛盾特殊性 (Qualitative Particularity)
  - 定性：此问题在本质机理上有何不可替代的特殊性质？
                  │
                  ▼
  维度二：主要矛盾 vs 次要矛盾 (Principal vs Secondary)
  - 定位：剥离伴生表象，锁定统领全局的“牛鼻子”。
                  │
                  ▼
  维度三：矛盾的主要方面 (Dominant Aspect & Trade-offs)
  - 定夺：在对立诉求中，当前历史阶段何者占据支配性地位？
                  │
                  ▼
  维度四：动态转化与反噬预警 (Transformation Dynamics)
  - 定界：在何种边界条件演化下，当前解法会反转为新的危机？
```

---

# 领域适配协议规范 (Tier 2: Domain Adapter Protocol)

任何 Agent 在将矛盾分析法适配到专门领域时，必须实现以下 **四个标准适配槽位（Standard Adapter Slots）**：

| 适配槽位 (Adapter Slot) | 核心提问 | 定义规范 |
| :--- | :--- | :--- |
| **Slot 1: 矛盾性质定性 (Nature)** | 该领域的矛盾主要体现为哪几种形态？ | 区分该领域特有的冲突类型，杜绝表面敷衍。 |
| **Slot 2: 牛鼻子定位 (Linchpin)** | 如何在该领域识别“主要矛盾”与“次生表象”？ | 建立因果传导判定链，确保资源集中打在根源上。 |
| **Slot 3: 取舍权衡模型 (Trade-off)** | 该领域经典的二元对立是什么？如何判断主要方面？ | 明确在特定阶段或约束下，哪种价值必须优先。 |
| **Slot 4: 异化反噬防范 (Reversal)** | 该领域的有效解法在什么条件下会变成系统灾难？ | 明确方案的适用边界、规模拐点与对冲机制。 |

---

# 典型领域横向实例化 (Concrete Domain Adaptations)

### 领域适配一：软件与复杂系统工程 (Software & Systems)
*   **Slot 1 (矛盾性质定性)**：
    *   *时序矛盾*（并发竞争、死锁、时序漂移）；
    *   *资源矛盾*（内存/连接池耗尽、IO争用）；
    *   *契约矛盾*（协议漂移、语义断裂）。
*   **Slot 2 (牛鼻子定位)**：在十几个级联抛错链中，溯源最早破坏状态不变性的源头故障点（如：DB连接泄露导致 Worker 挂起，Worker 挂起导致网关 502。主要矛盾在连接释放逻辑，网关超时是次生矛盾）。
*   **Slot 3 (取舍权衡模型)**：经典二元对立（CAP 定理、性能 vs 可维护性、吞吐量 vs 延迟）。在核心结算链路，【正确性】是主要方面，【延迟】是次要方面；在边缘日志链路则相反。
*   **Slot 4 (异化反噬防范)**：
    *   加粗粒度互斥锁（短期解法）在并发量跨过阈值时，必然转化为系统吞吐的致命瓶颈。
    *   加缓存（解延迟）在数据更新频繁时，必然转化为缓存一致性与内存穿透灾难。

### 领域适配二：科学研究与实验探索 (Scientific Research)
*   **Slot 1 (矛盾性质定性)**：
    *   *范式矛盾*（经典理论预测与反常实验测量结果之间的冲突）；
    *   *仪器与精度矛盾*（观测手段引入的干扰与微弱信号检测的矛盾）；
    *   *泛化矛盾*（受控实验室理想状态与自然环境复杂扰动的矛盾）。
*   **Slot 2 (牛鼻子定位)**：在解释一系列反常数据时，甄别是“测量仪器系统误差”（次要矛盾），还是“基础理论公设在极端边界失效”（主要矛盾）。
*   **Slot 3 (取舍权衡模型)**：模型复杂度（精确拟合） vs 模型泛化度（奥卡姆剃刀）。在探索初期，【解释力与可证伪性】是主要方面；在工程应用期，【计算复杂度与鲁棒性】是主要方面。
*   **Slot 4 (异化反噬防范)**：通过增加可调参数强行拟合异常值，在处理新样本时会迅速转化为“过拟合（Overfitting）”与不可复现性危机。

### 领域适配三：商业战略与市场决策 (Business Strategy)
*   **Slot 1 (矛盾性质定性)**：
    *   *存量与增量矛盾*（保护现有利润牛业务 vs 投入颠覆式新方向）；
    *   *价值创造与价值攫取矛盾*（为客户创造真实红利 vs 平台商业化变现抽取）；
    *   *规模与效率矛盾*（规模扩张带来的协同效应 vs 边际管理成本激增）。
*   **Slot 2 (牛鼻子定位)**：公司面临营收下滑、人员动荡、竞品夹击时，甄别出管理磨损只是次生矛盾，核心主要矛盾是“核心产品的客户价值衰减与产品市场契合度（PMF）丧失”。
*   **Slot 3 (取舍权衡模型)**：速度与利润、集权与分权。初创破局期，【生死突破与增速】是主要方面；行业存量出清期，【正向现金流与安全垫】上升为主要方面。
*   **Slot 4 (异化反噬防范)**：依靠高额补贴买增长（在用户留存成立前），必然导致“补贴一停、用户即散”的资金链断裂反噬。

### 领域适配四：组织治理与公共管理 (Org & Governance)
*   **Slot 1 (矛盾性质定性)**：
    *   *集权管控与一线活力的矛盾*；
    *   *制度刚性与人性弹性的矛盾*；
    *   *局部局部利益与全局战略协同的矛盾*。
*   **Slot 2 (牛鼻子定位)**：部门间扯皮与推诿不断（次要矛盾），主要矛盾是“考核指标在制度设计上存在零和博弈（A部目标达成直接损害B部利益）”。
*   **Slot 3 (取舍权衡模型)**：规范风控 vs 创新容错。成熟业务线以【流程合规与风控】为主要方面；创新探索特区必须以【自由试错与敏捷响应】为主要方面。
*   **Slot 4 (异化反噬防范)**：为防范极少数违规而制定繁苛的审批流程，必然在全员层面异化为“官僚主义推诿与组织决策瘫痪”。

---

# 新领域适配指南 (How to Adapt to a New Domain)

当面对未知的新专门领域时，Agent 必须在分析前输出以下标准化推演：
```markdown
### 领域矛盾解剖声明 (Domain Contradiction Profile: [领域名称])
1. 矛盾特殊定性 (Particularity)：该情境的核心矛盾属于 [领域专属性质分类]；
2. 主要矛盾定位 (Linchpin)：在众多表象症状 [A, B, C] 中，决定性核心是 [主要矛盾 X]；
3. 取舍主次决断 (Dominant Aspect)：在面临 [两难对立] 时，当前阶段必须以 [主要方面] 为支配考量；
4. 动态转化防范 (Reversal Guardrail)：当前策略在满足条件 [边界阈值] 时可能发生负面异化，应对预案为 [对冲机制]。
```
