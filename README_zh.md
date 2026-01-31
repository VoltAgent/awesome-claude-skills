<a href="https://github.com/Andymcdreamy/awesome-agent-skills">
<img width="1500" height="801" alt="claude-skills" src="https://github.com/user-attachments/assets/3a9d4cb3-04bd-4fb1-9146-fd3b53d26961" />
</a>


<br/>
<br/>

<div align="center">
    <strong>来自领先开发团队和社区的官方智能体技能 (Agent Skills) 精选合集。
    </strong>
    <br />
    <br />
    <p>
        <a href="README.md">English</a> |
        <a href="README_es.md">Español</a> |
        <a href="README_ja.md">日本語</a> |
        <a href="README_zh.md">中文</a>
    </p>

</div>

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<a href="https://github.com/VoltAgent/voltagent">
  <img alt="VoltAgent" src="https://cdn.voltagent.dev/website/logo/logo-2-svg.svg" height="20" />
</a> 

![Skills Count](https://img.shields.io/badge/Skills-172+-blue?style=flat-square)
![Last Update](https://img.shields.io/github/last-commit/VoltAgent/awesome-agent-skills?label=Last%20update&style=flat-square)
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)
[![GitHub forks](https://img.shields.io/github/forks/VoltAgent/awesome-agent-skills?style=social)](https://github.com/VoltAgent/awesome-agent-skills/network/members)

</div>

# Awesome Agent Skills (很棒的智能体技能)

“Agent Skills (智能体技能)” 是包含指令、脚本和资源的文件夹，用于教导 AI 编程助手执行特定任务。

本合集收录了由 Anthropic、Google Labs、Vercel、Stripe、Cloudflare、Trail of Bits、Sentry、Expo、Hugging Face 等领先开发团队发布的官方技能，以及由社区构建的技能。

兼容 Claude Code、Codex、Antigravity、Gemini CLI、Cursor、GitHub Copilot、OpenCode、Windsurf 等。请参阅下表了解路径和文档。

这是一个与社区共同构建和维护的、贡献最多的智能体技能仓库。


### 基本技能长什么样？

```YAML
---
name: api-tester
description: Test REST APIs and validate responses
---

# API Tester

Test HTTP endpoints and validate response structures.

## When to Use This Skill

Use this skill when you need to test API endpoints and verify response data.

## Instructions

When testing an API:

1. Send a request to the specified endpoint
2. Check the response status code
3. Validate the response body structure
4. Report any errors or unexpected results

## Response Validation

- Verify required fields exist
- Check data types match expected values
- Confirm nested objects have correct structure
```

详情请参阅 [官方仓库](https://github.com/anthropics/skills) 和 [创建指南](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills)。

### 其他 AI 编程助手的技能路径

| 工具 | 项目路径 | 全局路径 | 官方文档 |
|------|-------------|-------------|---------------|
| Antigravity | `.agent/skills/` | `~/.gemini/antigravity/skills/` | [Antigravity Skills](https://antigravity.google/docs/skills) |
| Claude Code | `.claude/skills/` | `~/.claude/skills/` | [Claude Code Skills](https://docs.anthropic.com/en/docs/claude-code/skills) |
| Codex | `.codex/skills/` | `~/.codex/skills/` | [Codex Skills](https://developers.openai.com/codex/skills) |
| Cursor | `.cursor/skills/` | `~/.cursor/skills/` | [Cursor Skills](https://cursor.com/docs/context/skills) |
| Gemini CLI | `.gemini/skills/` | `~/.gemini/skills/` | [Gemini CLI Skills](https://geminicli.com/docs/cli/skills/) |
| GitHub Copilot | `.github/skills/` | `~/.copilot/skills/` | [Copilot Skills](https://docs.github.com/en/copilot/concepts/agents/about-agent-skills) |
| OpenCode | `.opencode/skills/` | `~/.config/opencode/skills/` | [OpenCode Skills](https://opencode.ai/docs/skills) |
| Windsurf | `.windsurf/skills/` | `~/.codeium/windsurf/skills/` | [Windsurf Cascade Skills](https://docs.windsurf.com/windsurf/cascade/skills) |

<br/>

<a href="https://github.com/VoltAgent/voltagent">
<img width="1390" height="296" alt="social" src="https://github.com/user-attachments/assets/4c40affa-8e20-443a-9ec5-1abb6679b170" />
</a>

<br/>

## 官方 Claude 技能

### 文档创建

- **[anthropics/docx](https://github.com/anthropics/skills/tree/main/skills/docx)** - 创建、编辑和分析 Word 文档
- **[anthropics/doc-coauthoring](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring)** - 协作文档编辑和共同创作
- **[anthropics/pptx](https://github.com/anthropics/skills/tree/main/skills/pptx)** - 创建、编辑和分析 PowerPoint 演示文稿
- **[anthropics/xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx)** - 创建、编辑和分析 Excel 电子表格
- **[anthropics/pdf](https://github.com/anthropics/skills/tree/main/skills/pdf)** - 提取文本、创建 PDF 和处理表单

### 创意与设计

- **[anthropics/algorithmic-art](https://github.com/anthropics/skills/tree/main/skills/algorithmic-art)** - 使用带有随机种子的 p5.js 创建生成艺术
- **[anthropics/canvas-design](https://github.com/anthropics/skills/tree/main/skills/canvas-design)** - 设计 PNG 和 PDF 格式的视觉艺术
- **[anthropics/frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design)** - 前端设计和 UI/UX 开发工具
- **[anthropics/slack-gif-creator](https://github.com/anthropics/skills/tree/main/skills/slack-gif-creator)** - 创建针对 Slack 尺寸限制优化的动画 GIF
- **[anthropics/theme-factory](https://github.com/anthropics/skills/tree/main/skills/theme-factory)** - 使用专业主题为成果物设定样式或生成自定义主题

### 开发

- **[anthropics/web-artifacts-builder](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder)** - 使用 React 和 Tailwind 构建复杂的 claude.ai HTML 成果物
- **[anthropics/mcp-builder](https://github.com/anthropics/skills/tree/main/skills/mcp-builder)** - 创建 MCP 服务器以集成外部 API 和服务
- **[anthropics/webapp-testing](https://github.com/anthropics/skills/tree/main/skills/webapp-testing)** - 使用 Playwright 测试本地 Web 应用程序

### 品牌与传播

- **[anthropics/brand-guidelines](https://github.com/anthropics/skills/tree/main/skills/brand-guidelines)** - 将 Anthropic 的品牌颜色和排版应用于成果物
- **[anthropics/internal-comms](https://github.com/anthropics/skills/tree/main/skills/internal-comms)** - 撰写状态报告、时事通讯和常见问题解答

### 元技能 (Meta)

- **[anthropics/skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator)** - 创建扩展 Claude 功能的技能的指南
- **[anthropics/template](https://github.com/anthropics/skills/tree/main/template)** - 用于创建新技能的基本模板

## Vercel 工程团队的技能

- **[vercel-labs/react-best-practices](https://github.com/vercel-labs/agent-skills/tree/main/skills/react-best-practices)** - React 最佳实践和模式
- **[vercel-labs/vercel-deploy-claimable](https://github.com/vercel-labs/agent-skills/tree/main/skills/claude.ai/vercel-deploy-claimable)** - 将项目部署到 Vercel
- **[vercel-labs/web-design-guidelines](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines)** - 网页设计指南和标准

## Cloudflare 团队的技能

- **[cloudflare/agents-sdk](https://github.com/cloudflare/skills/tree/main/agents-sdk)** - 构建具有调度、RPC 和 MCP 服务器的有状态 AI 智能体
- **[cloudflare/wrangler](https://github.com/cloudflare/skills/tree/main/wrangler)** - 部署和管理 Workers, KV, R2, D1, Vectorize, Queues, Workflows

## Hugging Face 团队的技能

- **[huggingface/hugging-face-cli](https://github.com/huggingface/skills/tree/main/skills/hugging-face-cli)** - 用于模型、数据集、仓库和计算任务的 HF Hub CLI
- **[huggingface/hugging-face-model-trainer](https://github.com/huggingface/skills/tree/main/skills/hugging-face-model-trainer)** - 使用 TRL 训练模型：SFT, DPO, GRPO, GGUF 转换

## 社区技能

### 营销

- **[coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills)** - 23+ 种营销技能，涵盖 SEO、文案写作、电子邮件和广告

### 生产力与协作

- **[notiondevs/Notion Skills for Claude](https://www.notion.so/notiondevs/Notion-Skills-for-Claude-28da4445d27180c7af1df7d8615723d0)** - 使用 Notion 的技能
- **[Shpigford/readme](https://github.com/Shpigford/skills/tree/main/readme)** - 生成全面的项目文档

### 开发与测试

- **[antonbabenko/terraform-skill](https://github.com/antonbabenko/terraform-skill)** - Terraform 基础设施即代码 (IaC) 最佳实践
- **[zxkane/aws-skills](https://github.com/zxkane/aws-skills)** - 包含基础设施自动化和云架构模式的 AWS 开发
- **[lackeyjb/playwright-skill](https://github.com/lackeyjb/playwright-skill)** - 使用 Playwright 进行浏览器自动化

## 🤝 贡献

欢迎贡献！请参阅 [CONTRIBUTING.md](CONTRIBUTING.md) 了解指南。

- 通过 PR 提交新技能
- 改进现有定义

## 贡献者 ♥️ 感谢
![Contributors](https://contrib.rocks/image?repo=voltagent/awesome-agent-skills&max=500&columns=20&anon=1)

## 许可证

MIT 许可证 - 参见 [LICENSE](LICENSE)

*注：这是精选列表。完整列表请参阅原始仓库。*
