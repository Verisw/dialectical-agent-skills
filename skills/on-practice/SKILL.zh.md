---
name: on-practice
description: Use when investigating unfamiliar situations, acquiring new domain knowledge, forming and testing hypotheses against reality, or when needing empirical grounding and actionable verification rather than speculative reasoning or blind action.
---

# On-Practice: Dialectical Inquiry & Action Protocol (实践论：知行探索与认知演进规范)

This skill provides a **two-tier epistemological architecture** for agents:
- **Tier 1 (Top-Level Philosophy)**: Domain-agnostic, invariant principles of dialectical materialism (Epistemology).
- **Tier 2 (Domain Adapter Protocol)**: Extensible interface for mapping the top-level philosophy horizontally into specialized domains (Software, Science, Business, Governance, etc.).

---

# 顶层指导思想 (Tier 1: Invariant Meta-Philosophy)

## 核心心法 (Core Mindset)
1. **反对教条主义 / 本本主义 (Anti-Dogmatism)**:
   - *"没有调查，就没有发言权。"* 严禁脱离客观一手事实凭空空想、机械套用教条或预训练偏见。
2. **反对狭隘经验主义 (Anti-Empiricism)**:
   - 盲目的低水平忙碌不是实践。未经抽象与理论加工的经验无法把握系统规律。
3. **实践是检验真理的唯一标准 (Practice as Sole Truth Criterion)**:
   - 内部置信度与推演逻辑再优美，均非真理。真理必须经受外部客观世界能动交互的反作用力检验。

## 通用两阶段认知飞跃 (The Universal 4-Stage Loop)

```
[客观现实 / 待解领域]
          │
          ▼ 调查研究，获取第一手经验
【阶段一：感性认识 (Sensory Grounding)】
          │
          ▼ 十六字思维加工
【阶段二：第一次飞跃：感性 → 理性 (Cognitive Distillation)】
          │
          ▼ 制定假说/方案，主动改造现实
【阶段三：第二次飞跃：理性 → 实践 (Active Reality Testing)】*核心跃迁*
          │
          ├─ [验证成功] ──> 形成相对真理性认知，指导更大行动
          │
          └─ [暴露偏差] ──> 客观反馈揭示主观局限
                                   │
                                   ▼
                      【阶段四：螺旋校准 (Spiral Recalibration)】
                                   │
                                   └──> 迭代认知模型，在更高阶展开新循环
```

---

# 领域适配协议规范 (Tier 2: Domain Adapter Protocol)

任何 Agent 在将顶层思想应用到具体专业领域时，必须实现以下 **四个标准适配槽位（Standard Adapter Slots）**：

| 适配槽位 (Adapter Slot) | 核心提问 | 定义规范 |
| :--- | :--- | :--- |
| **Slot 1: 调查源 (Sensory Source)** | 该领域的“第一手事实”是什么？ | 确定什么是客观原始数据，坚决绕过二手解读与假设。 |
| **Slot 2: 十六字工序 (Domain Distillation)** | 如何在该领域去粗取精、由表及里？ | 明确该领域的典型噪声、常见伪命题、横向规律与因果机制。 |
| **Slot 3: 实践场 (Practice Medium)** | 检验方案的“客观实体”与“真理标准”是什么？ | 明确把方案投放给谁/什么环境，以及成败的硬性指标。 |
| **Slot 4: 校准信号 (Calibration Signals)** | 该领域的哪些客观反馈说明主观偏离了实际？ | 明确意外偏差的具体表征，驱动认知模型的版本更新。 |

---

# 典型领域横向实例化 (Concrete Domain Adaptations)

### 领域适配一：软件与复杂系统工程 (Software & Systems)
*   **Slot 1 (调查源)**：运行时真实环境配置、未经截断的系统日志、最小可复现脚本、生产监控指标（禁止假设版本与依赖）。
*   **Slot 2 (十六字工序)**：
    *   *去粗取精*：从海量堆栈中剥离无关依赖，定位核心调用链。
    *   *去伪存真*：排除缓存未清、并发偶发假象，识别稳定复现路径。
    *   *由此及彼*：关联上游配置漂移、网络拓扑与近期改动。
    *   *由表及里*：穿透表面崩溃，定位底层资源泄漏、时序倒置或数据结构竞争。
*   **Slot 3 (实践场)**：编译运行、单元与集成测试、端到端灰度验证。**真理标准**：Exit code 0、断言完全通过、指标平稳。
*   **Slot 4 (校准信号)**：测试报错、内存激增、死锁。提示假设存在未察觉的环境变量或边界条件。

### 领域适配二：科学研究与实验探索 (Scientific Research)
*   **Slot 1 (调查源)**：未经篡改的仪器观测原始读数、未清洗的实验数据集、一手文献原始方法章节。
*   **Slot 2 (十六字工序)**：
    *   *去粗取精*：剔除仪器基线漂移与测量随机误差。
    *   *去伪存真*：识别假阳性、幸存者偏差与统计伪相关。
    *   *由此及彼*：类比同类物理/化学/生物过程模型。
    *   *由表及里*：从数据拟合曲线推导底层控制微分方程与机理模型。
*   **Slot 3 (实践场)**：受控双盲对照实验、可复现性压力测试、同行对抗性检验。**真理标准**：实验严格可复现、预测与新测量完全吻合。
*   **Slot 4 (校准信号)**：反常观测（Anomaly）、统计显著性消失。提示理论模型遗漏关键物理变量或假设前提不成立。

### 领域适配三：商业战略与市场决策 (Business Strategy)
*   **Slot 1 (调查源)**：一线未失真的客户访谈原声、未粉饰的现金流与留存漏斗、供应商与渠道一线实地体感。
*   **Slot 2 (十六字工序)**：
    *   *去粗取精*：过滤公关宣传泡沫与虚荣指标（如单纯注册量）。
    *   *去伪存真*：甄别用户“口头宣称需要”与“实际付费意愿”的落差。
    *   *由此及彼*：比对行业生命周期、宏观周期与跨品类演进路径。
    *   *由表及里*：穿透价格战表象，解剖单位经济模型（UE）与供求结构性失衡。
*   **Slot 3 (实践场)**：最小可行性产品（MVP）试水、定向定价实验、真实商业闭环结算。**真理标准**：真金白银的自然留存率与净现金流流入。
*   **Slot 4 (校准信号)**：高获客成本、极低生命周期价值（LTV）、团队推行阻力。提示用户画像假设或价值主张主观化。

### 领域适配四：组织治理与协作管理 (Org & Governance)
*   **Slot 1 (调查源)**：一线基层员工匿名反馈、跨部门协作交付周期、日常沟通与决策日志（禁止单纯听取中层汇报）。
*   **Slot 2 (十六字工序)**：
    *   *去粗取精*：剥离情绪宣泄，萃取共性流程堵点。
    *   *去伪存真*：看清“制度规定流程”与“实际潜规则运转流程”的脱节。
    *   *由此及彼*：比对权责划分与利益激励机制的匹配度。
    *   *由表及里*：穿透“员工执行力不足”的表象，发现权责不对等与考核指标冲突的制度根源。
*   **Slot 3 (实践场)**：试点团队机制微调、新授权制度试行。**真理标准**：端到端交付时效提升、基层主动性与成果产出。
*   **Slot 4 (校准信号)**：推诿推责、政策下有对策、核心人员流失。提示机制设计存在逆向激励（Moral Hazard）。

---

# 新领域适配指南 (How to Adapt to a New Domain)

当面对未知的新专门领域时，Agent 必须在首轮思考中执行以下适配实例化：
```markdown
### 领域认知映射声明 (Domain Adaptation Profile: [领域名称])
1. 调查源 (Sensory Source)：我将通过 [具体第一手数据渠道] 获取客观真实情况；
2. 十六字加工 (16-Char Distillation)：在该领域中，我需特别警惕 [领域专属伪命题/噪音]，重点追问 [底层因果机理]；
3. 实践场 (Practice Medium)：我将通过 [具体试点/运行/交付方式] 接受客观检验，成功标准为 [量化客观指标]；
4. 校准信号 (Calibration)：一旦观察到 [特定负反馈]，立即复盘并重构认知。
```
