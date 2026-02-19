# Professional Scrum Master I 备考笔记

## 一、Scrum框架概述

### 1.1 Scrum定义

Scrum 是一个轻量级框架，用于开发、交付和持续改进复杂产品。它基于**经验主义**（Empiricism）和**精益思维**（Lean Thinking）。

> "Scrum is a lightweight framework that helps people, teams and organizations generate value through adaptive solutions for complex problems."

### 1.2 Scrum理论基础

| 理论                       | 说明               | 重要性              |
| ------------------------ | ---------------- | ---------------- |
| **经验主义** (Empiricism)    | 知识来源于经验，基于观察做出决策 | 使Scrum基于实际数据而非假设 |
| **精益思维** (Lean Thinking) | 减少浪费，专注于本质       | 优化价值流，提高效率       |

### 1.3 Scrum的三个支柱 (The Three Pillars of Scrum)

| 支柱                     | 定义               | 重要性      |
| ---------------------- | ---------------- | -------- |
| **透明性** (Transparency) | 工作和成果对执行者和接收者都可见 | 使检查成为可能  |
| **检查** (Inspection)    | 频繁检查Scrum工件和进度   | 促进适应     |
| **适应** (Adaptation)    | 根据检查结果及时调整       | 使Scrum有效 |

> **关键点**：三个支柱相互依存，缺一不可。缺乏透明性会导致检查无效；没有适应，检查毫无意义。

## 二、Scrum价值观 (Scrum Values)

| 价值观                 | 定义                 | 重要性    |
| ------------------- | ------------------ | ------ |
| **承诺** (Commitment) | 团队承诺实现目标并互相支持      | 保证团队协作 |
| **专注** (Focus)      | 团队专注于Sprint工作，达成目标 | 保持工作重心 |
| **开放** (Openness)   | 团队和利益相关者对工作和挑战保持开放 | 促进透明沟通 |
| **尊重** (Respect)    | 团队成员相互尊重为有能力、独立的个体 | 建立信任   |
| **勇气** (Courage)    | 团队成员有勇气做正确的事，解决难题  | 促进持续改进 |

> **核心思想**：Scrum价值观是Scrum团队的行为准则，它们使Scrum的三个支柱真正发挥作用。

## 三、Scrum角色 (Scrum Roles)

### 3.1 Scrum团队 (Scrum Team)

*   **规模**：5-9人（理想），不超过10人
*   **结构**：无子团队或层级结构
*   **特性**：
    *   **跨职能** (Cross-functional)：拥有创造价值所需的所有技能
    *   **自我管理** (Self-managing)：内部决定谁做什么、何时做、如何做

### 3.2 三个角色职责

| 角色                | 职责                                                  | 关键点                                               |
| ----------------- | --------------------------------------------------- | ------------------------------------------------- |
| **Scrum Master**  | • 建立Scrum框架<br>• 促进团队自管理<br>• 消除障碍<br>• 保证事件有效进行    | • 服务型领导者<br>• 不是项目经理<br>• 为团队和组织服务                |
| **Product Owner** | • 最大化产品价值<br>• 产品待办事项列表管理<br>• 定义产品目标<br>• 与利益相关者沟通 | • 一个角色，不是委员会<br>• 决策可见于产品待办事项列表和增量                |
| **Developers**    | • 创造增量<br>• 制定Sprint计划<br>• 遵循完成定义（DoD）<br>• 每日调整计划 | • 100%负责Sprint目标<br>• 无子团队<br>• 无需向Scrum Master报告 |

> **重要澄清**：
>
> *   Scrum Master不是项目经理
> *   Product Owner不是产品经理
> *   Developers不是开发人员，而是负责创建增量的团队成员

## 四、Scrum事件 (Scrum Events)

### 4.1 事件概述

| 事件                       | 时长   | 位置        | 目的        | 关键点                                        |
| ------------------------ | ---- | --------- | --------- | ------------------------------------------ |
| **Sprint**               | ≤1个月 | 核心        | 价值创造的容器   | • 固定长度<br>• 从Sprint目标开始<br>• 不能取消（除非目标过时）  |
| **Sprint Planning**      | ≤8小时 | Sprint开始  | 规划Sprint  | • 确定Sprint目标<br>• 选择产品待办事项<br>• 制定Sprint计划 |
| **Daily Scrum**          | 15分钟 | 每天        | 检查进度，调整计划 | • 仅开发人员参加<br>• 仅讨论如何实现Sprint目标             |
| **Sprint Review**        | ≤4小时 | Sprint结束前 | 检查成果，规划未来 | • 展示增量<br>• 与利益相关者讨论<br>• 调整产品待办事项         |
| **Sprint Retrospective** | ≤3小时 | Sprint结束  | 改进流程      | • 讨论上个Sprint<br>• 制定改进计划                   |

### 4.2 Sprint事件流程图

    Sprint开始
    │
    ├─ Sprint Planning (规划Sprint)
    │   ├─ sm确定Sprint目标s
    │   ├─ 选择产品待办事项
    │   └─ 制定Sprint计划
    │
    ├─ Daily Scrum (每日站会)
    │   └─ 检查进度，调整计划
    │
    ├─ Sprint Review (评审会议)
    │   └─ 展示增量，调整产品待办事项
    │
    └─ Sprint Retrospective (回顾会议)
        └─ 制定改进计划

> **关键点**：Sprint是所有事件的容器，其他事件都是为了在Sprint内实现检查和适应。

## 五、Scrum工件 (Scrum Artifacts)

### 5.1 工件概述

| 工件                  | 说明        | 承诺                 | 关键点                        |
| ------------------- | --------- | ------------------ | -------------------------- |
| **Product Backlog** | 产品改进的有序列表 | Product Goal       | • 产品价值的单一来源<br>• 持续细化      |
| **Sprint Backlog**  | Sprint的计划 | Sprint Goal        | • 由开发人员制定<br>• 随Sprint进行更新 |
| **Increment**       | 产品价值的增量   | Definition of Done | • 可用的<br>• 每个Sprint可有多个增量  |

### 5.2 三个承诺 (Commitments)

| 承诺                     | 说明                  | 重要性             |
| ---------------------- | ------------------- | --------------- |
| **Product Goal**       | 产品未来状态，Scrum团队的长期目标 | 为产品待办事项提供方向     |
| **Sprint Goal**        | Sprint的单一目标         | 为Sprint提供焦点和凝聚力 |
| **Definition of Done** | 增量完成的质量标准           | 确保增量质量，提供透明度    |

> **关键点**：所有承诺都是为了增强经验主义和Scrum价值观。

## 六、Scrum关键概念

### 6.1 Scrum框架特性

*   **轻量级**：仅定义必要的框架，不规定详细操作
*   **可扩展**：可封装现有实践，或使其变得不必要
*   **经验主义**：基于观察和实验，而不是预先计划
*   **迭代增量**：通过短周期的Sprint来优化可预测性

### 6.2 Scrum vs. Traditional Project Management

| 项目管理      | Scrum          |
| --------- | -------------- |
| 详细计划      | 适应性计划          |
| 项目经理控制    | 自我管理团队         |
| 交付物在项目结束时 | 每个Sprint交付可用增量 |
| 严格遵循计划    | 适应变化           |
| 阶段性交付     | 迭代交付           |

## 七、考试重点总结

### 7.1 角色职责 (必须掌握)

*   **Scrum Master**：服务型领导者，保证Scrum框架实施，消除障碍
*   **Product Owner**：最大化产品价值，管理产品待办事项，决策权在Product Owner
*   **Developers**：100%负责Sprint目标，制定计划，遵循DoD

### 7.2 事件关键点

*   **Sprint**：固定长度，≤1个月；不能取消（除非目标过时）
*   **Sprint Planning**：必须在Sprint开始前完成；Sprint Goal必须在会议结束前确定
*   **Daily Scrum**：15分钟；仅开发人员参加；聚焦进度和计划
*   **Sprint Review**：展示增量，与利益相关者讨论；不是发布门
*   **Sprint Retrospective**：改进团队流程；必须在Sprint结束前完成

### 7.3 工件与承诺

*   **Product Backlog**：有序列表；Product Goal是其目标
*   **Sprint Backlog**：Sprint计划；Sprint Goal是其目标
*   **Increment**：可用增量；Definition of Done是其标准

### 7.4 Scrum价值观 (COFRC)

*   **C**ommitment
*   **O**penness
*   **F**ocus
*   **R**espect
*   **C**ourage

## 八、常见误解澄清

| 误解                          | 正确理解                                        |
| --------------------------- | ------------------------------------------- |
| Scrum Master是项目经理           | Scrum Master是服务型领导者，帮助团队自我管理                |
| Product Owner是产品经理          | Product Owner是负责产品价值最大化的人，不一定是产品经理          |
| Sprint可以随时取消                | 只有Product Owner可以取消Sprint，且仅在Sprint目标过时的情况下 |
| Scrum需要详细文档                 | Scrum是轻量级框架，强调面对面沟通和透明度，而不是详细文档             |
| Scrum团队可以有子团队               | Scrum团队是无层级结构的，没有子团队                        |
| Product Owner可以随时改变Sprint目标 | Sprint目标在Sprint期间不应改变，但可以与Product Owner协商范围 |

## 九、实用记忆技巧

1.  **Scrum角色**：记住"Scrum Master"的"Master"不是"Master"，而是"Service"（服务）。
2.  **Scrum事件**：Sprint是心脏，其他事件围绕它。
3.  **Scrum价值观**：COFRC（Commitment, Openness, Focus, Respect, Courage）。
4.  **三个承诺**：Product Goal（长期目标）、Sprint Goal（短期目标）、Definition of Done（质量标准）。
5.  **Sprint事件**：Sprint Planning → Daily Scrum → Sprint Review → Sprint Retrospective。

## 十、Scrum框架完整视图

    Scrum Framework
    │
    ├─ Scrum Values (COFRC)
    │   ├─ Commitment
    │   ├─ Openness
    │   ├─ Focus
    │   ├─ Respect
    │   └─ Courage
    │
    ├─ Scrum Roles
    │   ├─ Scrum Master
    │   ├─ Product Owner
    │   └─ Developers
    │
    ├─ Scrum Events
    │   ├─ Sprint
    │   ├─ Sprint Planning
    │   ├─ Daily Scrum
    │   ├─ Sprint Review
    │   └─ Sprint Retrospective
    │
    └─ Scrum Artifacts
        ├─ Product Backlog
        ├─ Sprint Backlog
        └─ Increment
            └─ Definition of Done

> **重要提示**：Scrum框架是不可变的。只实施部分Scrum不是Scrum。

***

**祝您考试顺利！**\
*基于Scrum Guide 2020整理，符合Professional Scrum Master I考试要求*
