# FeedbackCraft

> 智能绩效反馈生成器 — 让每一句反馈都有力量

FeedbackCraft 是一个 AI Agent Skill，将绩效反馈的专业流程封装为可复用的配置文件。安装到 Claude Code、Codex 等 AI 编程助手中，即可在对话中一键生成结构化、专业级的绩效反馈。

## 项目介绍

绩效反馈是管理者最频繁的 HR 工作之一，但长期面临三个核心痛点：

- **时间成本高**：平均 30-60 分钟撰写一份反馈
- **质量参差不齐**：不同管理者产出差异巨大
- **AI 输出泛泛**：通用 AI 缺乏绩效管理领域知识

FeedbackCraft 将 HR 最佳实践封装为 Skill，让 AI 按照专业框架生成反馈，兼顾效率和质量。

## 核心功能

| 功能 | 说明 |
|------|------|
| 结构化输入采集 | AI 主动引导用户提供员工信息、成就、改进点 |
| 5 部分结构化输出 | 总体评价 → 核心优势 → 发展建议 → 待改进领域 → 下一步 |
| 3 种语气风格 | 正式（HR系统）/ 温和（辅导型）/ 直接（数据驱动） |
| 7 条质量规则 | 引用具体事例、SMART 建议、2:1 正负比、不编造数据 |
| 在线 Demo | 网页版交互体验，无需安装即可试用 |

## 在线体验

访问 [FeedbackCraft Demo](https://pxlm570.github.io/feedbackcraft/) 在线体验功能。

## 使用教程

### 方式一：在线 Demo（推荐入门）

1. 打开 [在线体验页面](https://pxlm570.github.io/feedbackcraft/)
2. 填写员工信息（姓名、岗位、评估周期）
3. 输入关键成就（2-5 条）和改进领域（1-3 条）
4. 选择语气风格（正式 / 温和 / 直接）
5. 点击"生成反馈"，即可获得结构化绩效反馈

### 方式二：安装 Skill（推荐深度使用）

#### 安装到 Claude Code

```bash
# 1. 创建技能目录
mkdir -p ~/.claude/skills/feedbackcraft

# 2. 下载 SKILL.md
curl -o ~/.claude/skills/feedbackcraft/SKILL.md \
  https://raw.githubusercontent.com/pxlm570/feedbackcraft/main/skill/feedbackcraft/SKILL.md

# 3. 重启 Claude Code 即可生效
```

#### 安装到 Codex

```bash
# 1. 创建技能目录
mkdir -p ~/.codex/skills/feedbackcraft

# 2. 下载 SKILL.md
curl -o ~/.codex/skills/feedbackcraft/SKILL.md \
  https://raw.githubusercontent.com/pxlm570/feedbackcraft/main/skill/feedbackcraft/SKILL.md

# 3. 重启 Codex 即可生效
```

#### 使用方式

安装后，在 AI 助手对话中输入：

```
帮我为张伟写一份 Q2 2026 的绩效反馈。
他是高级后端工程师，主要成就包括：主导支付系统微服务化改造、
核心API响应时间优化40%。改进点：文档输出和跨团队沟通。
```

AI 会按照 Skill 中定义的框架生成专业反馈。

## 技术架构

- **格式**：AI Agent Skill（SKILL.md）
- **兼容平台**：Claude Code、Codex、其他支持 Skill 的 AI 助手
- **依赖**：零依赖，单个 Markdown 文件
- **数据安全**：所有处理在本地 AI 助手中完成，不上传任何外部服务

## 文件结构

```
feedbackcraft/
├── index.html                              # 在线 Demo 页面
├── skill/
│   └── feedbackcraft/
│       └── SKILL.md                        # 核心 Skill 文件
├── docs/
│   └── case-description.md                 # 方案说明
└── README.md
```

## 适用场景

- 季度 / 年度绩效评估
- 1:1 会议准备
- 晋升推荐意见
- 新员工入职评估
- 项目复盘反馈

## 许可证

MIT License
