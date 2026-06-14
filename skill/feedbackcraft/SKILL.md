---
name: feedbackcraft
description: "Use when managers or team leads need to write performance reviews, feedback comments, evaluation statements, or development suggestions for team members."
---

# FeedbackCraft - 智能绩效反馈生成器

> Version: 1.0.0 | Last Updated: 2026-06-14

## Overview

Generate structured, professional performance feedback in 3-5 minutes instead of 30-60 minutes. This skill guides AI agents to collect key context, apply proven feedback frameworks, and produce balanced, actionable output.

## When to Use

- Quarterly/annual performance reviews
- 1:1 meeting preparation
- Promotion or advancement recommendations
- New employee onboarding evaluations
- Project post-mortem feedback
- Any situation requiring written performance assessment

## Input Collection

Gather the following before generating feedback. Ask one category at a time.

**Required:**
- Employee name and role
- Evaluation period (e.g., Q2 2026, Jan-Jun 2026)
- 2-5 specific achievements or positive contributions
- 1-3 areas for improvement or development

**Optional (ask if not provided):**
- Tone preference: formal / gentle / direct
- Team context (size, structure, reporting line)
- Industry/department (for specialized vocabulary)
- Language preference (Chinese / English / bilingual)

**Guidelines for collecting input:**
- Ask for specific examples, not vague statements
- "Improved team efficiency" is too vague; "Reduced sprint cycle from 2 weeks to 10 days by automating deployment" is actionable
- If user cannot provide enough detail, note this limitation in the output

## Output Structure

Generate feedback using this 5-part template:

### 1. Overall Summary (2-3 sentences)
High-level assessment of the employee's performance during the period.

### 2. Key Strengths
- Reference specific achievements from input
- Use action verbs and quantified results where possible
- Group related strengths thematically

### 3. Areas for Improvement
- Frame constructively (what to develop, not what's wrong)
- Reference specific input examples
- Provide context on why this matters

### 4. Development Suggestions
- SMART format: Specific, Measurable, Achievable, Relevant, Time-bound
- 2-3 concrete actions for the next quarter
- Include both skill development and behavioral suggestions

### 5. Next Steps
- 1-2 priority focus areas for the upcoming period
- Suggested discussion topics for follow-up 1:1

## Tone Guidelines

**Formal (正式)**
- For official HR systems, promotion packets, formal evaluations
- Professional vocabulary, structured paragraphs
- Example opener: "在过去的一个周期中，[姓名]展现了出色的专业能力..."

**Gentle (温和)**
- For junior employees, support-oriented feedback, coaching contexts
- Encouraging language, growth-focused framing
- Example opener: "[姓名]在本周期取得了令人欣喜的进步..."

**Direct (直接)**
- For senior employees, data-driven reviews, urgent improvement needs
- Concise, metrics-focused, no hedging
- Example opener: "[姓名]本周期核心指标达成率[XX]%，具体表现如下..."

## 中文输出指南 (Chinese Output Guidelines)

When generating feedback in Chinese, follow these rules:

### 用词规范
| 场景 | 推荐用词 | 避免用词 |
|------|---------|---------|
| 正面评价 | 能力项、核心优势、突出表现 | 技能点、好处、不错 |
| 改进建议 | 发展建议、提升空间、优化方向 | 要改的地方、缺点、不足 |
| 量化表达 | 降幅达XX%、提升XX%、覆盖XX个 | 降了很多、提升了不少 |
| 行为描述 | 主导了、推动了、协调了、输出了 | 做了、搞了、弄了 |

### 句式模板
- **成就描述**：[动词] + [具体事项] + [量化结果]
  - 示例："主导支付系统微服务化改造，按期交付零线上事故"
- **改进建议**：针对"[具体问题]"，建议在[时间]内[具体行动]，目标[可衡量结果]
  - 示例："针对'文档输出不够及时'，建议在Q3完成核心系统文档补全，设定具体清单和完成时限"
- **下一步**：建议[时间]聚焦[方向]，可在[场景]中讨论[话题]
  - 示例："建议Q3聚焦微服务治理体系建设，可在下次1:1中讨论监控方案选型"

### 标点规范
- 使用中文标点（，。；：）
- 数字与中文之间加空格（200ms → 200 ms）
- 英文术语保留原文（API、Sprint、1:1）

## 行业适配指南 (Industry Adaptation)

### 技术/研发行业
**关键能力项：** 技术攻坚、架构设计、代码质量、技术分享、问题排查、性能优化
**常用指标：** 响应时间、代码覆盖率、Bug修复率、上线成功率、技术债务
**专业术语：** 微服务、CI/CD、Code Review、技术方案、系统设计

**示例句式：**
- "主导XX系统重构，代码可维护性提升40%"
- "输出技术方案X份，通过率100%"

### 销售/商务行业
**关键能力项：** 客户开发、商务谈判、关系维护、业绩达成、团队协作
**常用指标：** 签约金额、回款率、客户满意度、新客户开发数、续约率
**专业术语：** Pipeline、CRM、客户画像、商务拓展、客户成功

**示例句式：**
- "Q2签约金额达XX万，完成率120%"
- "新开发客户X家，其中X家进入Pipeline"

### 产品/运营行业
**关键能力项：** 需求分析、项目推进、数据分析、用户洞察、跨部门协作
**常用指标：** 需求交付率、用户增长率、留存率、NPS、项目按时交付率
**专业术语：** PRD、MVP、A/B测试、用户画像、增长黑客

**示例句式：**
- "主导XX功能上线，用户留存率提升15%"
- "完成X次用户调研，输出X份分析报告"

### 职能/支持部门
**关键能力项：** 流程优化、服务意识、响应速度、成本控制、合规管理
**常用指标：** 响应时长、满意度评分、流程效率、成本节约、合规率
**专业术语：** SOP、KPI、OKR、流程再造、精益管理

**示例句式：**
- "优化XX流程，处理时长缩短30%"
- "完成X次内部培训，覆盖X人次"

## Quality Rules

1. **Reference specific inputs** — Every claim must trace back to user-provided examples. Never invent achievements or metrics.
2. **No vague phrases** — Replace "good teamwork" with "proactively collaborated with design team to resolve 3 blocking issues in Sprint 12"
3. **Balanced ratio** — Maintain approximately 2:1 positive-to-improvement ratio unless user specifies otherwise
4. **SMART suggestions** — All development suggestions must be Specific, Measurable, Achievable, Relevant, and Time-bound
5. **No fabrication** — If input is insufficient, note the gap and ask for clarification rather than guessing
6. **Professional vocabulary** — Use industry-appropriate terminology (see 行业适配指南)
7. **Ask when uncertain** — If critical information is missing (e.g., no achievements provided), pause and ask before generating
8. **Respect sensitivity** — When addressing improvement areas, use constructive framing that preserves dignity

## 负面反馈话术指南 (Handling Difficult Feedback)

When improvement areas are sensitive or potentially demotivating, follow these guidelines:

### 框架转换
| 原始问题 | 转换框架 | 示例表达 |
|---------|---------|---------|
| 能力不足 | 发展空间 | "在XX方面有进一步提升的空间" |
| 态度问题 | 行为描述 | "建议在XX场景下更主动地..." |
| 产出不够 | 目标对齐 | "建议与团队目标更紧密地对齐..." |
| 协作问题 | 协作优化 | "建议增加与XX团队的沟通频率..." |

### 话术模板
- **建设性开头**："[姓名]在XX方面有扎实的基础，在下一阶段可以重点提升..."
- **成长导向**："这是一个很好的发展机会，通过XX可以进一步增强..."
- **具体可行**：建议避免"[不要做XX]"，改为"建议尝试[做XX]，目标[结果]"

### 避免的表达
- ❌ "工作态度不积极"
- ❌ "经常出错"
- ❌ "团队协作能力差"
- ✅ "建议在XX场景下更主动地参与讨论"
- ✅ "建议在提交前增加自检环节，提升交付质量"
- ✅ "建议增加与XX团队的主动沟通，减少信息差"

## Common Mistakes

| Mistake | Why It's Wrong | Fix |
|---------|---------------|-----|
| "工作态度积极" | Too vague, every review says this | Reference specific behavior: "主动承担了XX项目的攻坚任务" |
| Positive-only feedback | Fails the 2:1 balance rule | Always include development areas with constructive framing |
| No actionable items | Feedback without next steps is incomplete | Every review must include 2-3 SMART suggestions |
| Tone mismatch | Formal tone for junior employee feels cold | Match tone to employee level and context |
| Fabricated metrics | "Increased sales by 30%" when user never mentioned sales | Only use data from user input; note gaps explicitly |
| Negative framing | "XX做得不好" | Use growth-oriented framing: "XX有提升空间" |

## Example

**Input:**
- Name: 张伟, Role: 高级后端工程师, Period: Q2 2026
- Achievements: Led migration of payment system to microservices, reduced API latency by 40%, mentored 2 junior engineers
- Improvement areas: Documentation habits, cross-team communication
- Tone: Formal

**Output:**

> **总体评价**
>
> 张伟在2026年第二季度展现了卓越的技术领导力和团队协作能力，在核心系统改造和团队赋能方面均取得了突出成绩。
>
> **核心优势**
>
> 1. **技术攻坚能力突出**：主导支付系统微服务化改造，从单体架构成功迁移至分布式架构，项目按期交付且零线上事故，体现了扎实的系统设计能力和风险把控意识。
> 2. **性能优化成效显著**：通过数据库查询优化和缓存策略调整，将核心API平均响应时间从200ms降至120ms，降幅达40%，直接提升了用户支付体验。
> 3. **团队赋能意识强**：主动承担2名初级工程师的导师工作，通过代码审查和技术分享帮助其快速成长，其中1名已独立负责模块开发。
>
> **发展建议**
>
> 1. **完善技术文档**：建议在每个项目交付时同步输出架构设计文档和运维手册，目标：Q3内完成现有核心系统的文档补全（可设定具体文档清单和完成时限）。
> 2. **加强跨团队协作**：建议主动参与产品和前端团队的周会，提前了解需求变更和技术依赖，减少后期返工。可从Q3的XX项目开始实践。
>
> **下一步**
>
> 建议Q3重点聚焦微服务治理体系建设，同时将文档规范化作为持续改进方向。可在下次1:1中详细讨论微服务监控方案的选型。

## Changelog

### v1.0.0 (2026-06-14)
- Initial release
- 5-part output structure
- 3 tone styles (formal/gentle/direct)
- 7 quality rules
- Chinese output guidelines
- Industry adaptation guides (tech/sales/product/support)
- Difficult feedback handling framework
