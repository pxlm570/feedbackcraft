---
name: performance-feedback-generator
description: "Use when managers or team leads need to write performance reviews, feedback comments, evaluation statements, or development suggestions for team members."
---

# AI Performance Feedback Generator

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
- Example opener: "在过去的一个季度中，[姓名]展现了出色的专业能力..."

**Gentle (温和)**
- For junior employees, support-oriented feedback, coaching contexts
- Encouraging language, growth-focused framing
- Example opener: "[姓名]在本季度取得了令人欣喜的进步..."

**Direct (直接)**
- For senior employees, data-driven reviews, urgent improvement needs
- Concise, metrics-focused, no hedging
- Example opener: "[姓名]本季度核心指标达成率[XX]%，具体表现如下..."

## Quality Rules

1. **Reference specific inputs** — Every claim must trace back to user-provided examples. Never invent achievements or metrics.
2. **No vague phrases** — Replace "good teamwork" with "proactively collaborated with design team to resolve 3 blocking issues in Sprint 12"
3. **Balanced ratio** — Maintain approximately 2:1 positive-to-improvement ratio unless user specifies otherwise
4. **SMART suggestions** — All development suggestions must be Specific, Measurable, Achievable, Relevant, and Time-bound
5. **No fabrication** — If input is insufficient, note the gap and ask for clarification rather than guessing
6. **Professional vocabulary** — Use HR-appropriate terminology (e.g., "能力项" not "技能点", "发展建议" not "要改的地方")
7. **Ask when uncertain** — If critical information is missing (e.g., no achievements provided), pause and ask before generating

## Common Mistakes

| Mistake | Why It's Wrong | Fix |
|---------|---------------|-----|
| "工作态度积极" | Too vague, every review says this | Reference specific behavior: "主动承担了XX项目的攻坚任务" |
| Positive-only feedback | Fails the 2:1 balance rule | Always include development areas with constructive framing |
| No actionable items | Feedback without next steps is incomplete | Every review must include 2-3 SMART suggestions |
| Tone mismatch | Formal tone for junior employee feels cold | Match tone to employee level and context |
| Fabricated metrics | "Increased sales by 30%" when user never mentioned sales | Only use data from user input; note gaps explicitly |

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
