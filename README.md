# Enterprise AI Playbook｜企业 AI 项目指南

**何凡 Isaac · 让数据 AI 化，让业务 AI 化，让人才 AI 化。**

从真实业务问题出发，把需求诊断、数据准备、工作流设计、验收与团队共创连接起来。

Practical field notes and reusable templates for enterprise AI projects: discovery, data governance, workflow design, evaluation, and project-based learning.

## 从哪里开始

| 你正在面对的问题 | 可直接使用的材料 |
| --- | --- |
| 业务方提出“想用 AI”，需要明确场景 | [项目需求卡](templates/project-brief.md) |
| 数据分散，字段和来源口径不一致 | [数据字典](templates/data-dictionary.csv) |
| 已经有原型，需要判断是否值得采用 | [验收计划](templates/acceptance-plan.md)与[实验记录表](templates/experiment-log.csv) |
| 团队需要在项目中学会使用 AI | [PBL 项目卡](templates/pbl-project-card.md) |
| 项目需要作出方案取舍并保留理由 | [决策记录](templates/decision-log.md) |

## 三个工作方向

**数据 AI 化**：保留来源，统一字段，设计复核与更新机制，让知识和数据能够进入工作流。

**业务 AI 化**：明确输入、规则、处理动作和责任人，把 AI 放进有业务目标的流程，并用基线与实际结果作比较。

**人才 AI 化**：选一个真实任务，安排业务、技术与使用者共同参与，交付可运行的成果、说明和复盘。

## 场景拆解

- [医疗科研资料治理与随访](scenarios/medical-research-data.md)：资料识别、字段标准化、专业复核与来源追溯。
- [餐饮库存与菜单推荐](scenarios/retail-operations.md)：库存口径、推荐动作、促销增量与经营验证。

场景文档依据 Isaac 已公开的项目介绍展开，分别标明现有方案内容与可供后续项目使用的验证建议。

## 使用方法

1. 复制项目需求卡，选择一个具体流程，记录现状和责任人。
2. 整理输入数据及字段，建立人工处理基线。
3. 在试点前填写验收计划，并保存同一批样本的处理记录。
4. 组织业务方复核，按约定指标决定继续、调整或停止。
5. 用决策记录与 PBL 项目卡完成交接和复盘。

模板内的“待填写”项由项目参与者共同确定。CSV 提供字段表头；数据字典中的 `example_record_id` 为演示字段。

## 交流与贡献

欢迎通过 [Issues](https://github.com/fanh6591-ux/enterprise-ai-playbook/issues) 提交模板改进、清晰的问题和可复现的示例。[贡献说明](CONTRIBUTING.md)

业务合作与项目交流：[Isaac 个人网站](https://isaac2024.online/#contact)。

[个人介绍](https://github.com/fanh6591-ux) · [公开项目案例](https://isaac2024.online/work/) · [MIT License](LICENSE)
