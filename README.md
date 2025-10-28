<a href="https://github.com/VoltAgent/voltagent">
<img width="1500" height="500" alt="claude-skills" src="https://github.com/user-attachments/assets/39c54dfd-129e-4b43-8b92-20824a56e069" />
</a>

<br/>
<br/>

<div align="center">
    <strong>A collection of Claude Skills, articles, tutorials, and videos from Anthropic and the community.</strong>
    <br />
    <br />
</div>

<div align="center">
    
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)
[![Twitter Follow](https://img.shields.io/twitter/follow/voltagent_dev?style=social)](https://twitter.com/voltagent_dev)
    
</div>

<br/>



# Awesome Claude Skills

Claude Skills are folders with instructions, scripts, and resources that teach Claude specific tasks. Skills can include executable code and are loaded only when needed, allowing you to maintain hundreds without performance impact. Multiple skills can run together for complex tasks like document creation, code testing, and data analysis.

### ⚡️ Maintained by the [VoltAgent](https://github.com/voltagent/voltagent) open-source AI agent framework community.

<a href="https://github.com/VoltAgent/voltagent">
<img width="1800" alt="435380213-b6253409-8741-462b-a346-834cd18565a9" src="https://github.com/user-attachments/assets/452a03e7-eeda-4394-9ee7-0ffbcf37245c" />
</a>

### What a Basic Skill Looks Like?

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

See the [official repo](https://github.com/anthropics/skills) and [creation guide](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills) for more details.


## Official Claude Skills

### Document Creation

| Skill |                                                                                                                                  | Description                                        |
| ----- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- |
| **docx** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/docx) | Create, edit, and analyze Word documents           |
| **pptx** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/pptx) | Create, edit, and analyze PowerPoint presentations |
| **xlsx** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/xlsx) | Create, edit, and analyze Excel spreadsheets       |
| **pdf** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/pdf)  | Extract text, create PDFs, and handle forms        |

### Creative and Design

| Skill |                                                                                                                                               | Description                                                        |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| **algorithmic-art** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/algorithmic-art)   | Create generative art using p5.js with seeded randomness           |
| **canvas-design** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/canvas-design)     | Design visual art in PNG and PDF formats                           |
| **slack-gif-creator** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/slack-gif-creator) | Create animated GIFs optimized for Slack size constraints          |
| **theme-factory** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/theme-factory)     | Style artifacts with professional themes or generate custom themes |

### Development

| Skill |                                                                                                                                               | Description                                                    |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| **artifacts-builder** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/artifacts-builder) | Build complex claude.ai HTML artifacts with React and Tailwind |
| **mcp-builder** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/mcp-builder)       | Create MCP servers to integrate external APIs and services     |
| **webapp-testing** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/webapp-testing)    | Test local web applications using Playwright                   |

### Branding and Communication

| Skill |                                                                                                                                              | Description                                                |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| **brand-guidelines** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/brand-guidelines) | Apply Anthropic's brand colors and typography to artifacts |
| **internal-comms** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/internal-comms)   | Write status reports, newsletters, and FAQs                |

### Meta

| Skill |                                                                                                                                            | Description                                                 |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------- |
| **skill-creator** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/skill-creator)  | Guide for creating skills that extend Claude's capabilities |
| **template-skill** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/template-skill) | Basic template for creating new skills                      |

## Community Skills

### Productivity and Collaboration

| Skill |                                                                                                                                                                       | Description                                            |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| **Notion Skills for Claude** | -                                                                                                                                                                     | Skills for working with Notion                         |
| **superpowers-lab** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers-lab)                                                  | Lab environment for Claude superpowers                 |
| **brainstorming** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/tree/main/skills/brainstorming)                       | Generate and explore ideas                             |
| **writing-plans** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/tree/main/skills/writing-plans)                       | Create strategic documentation                         |
| **executing-plans** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/tree/main/skills/executing-plans)                     | Implement and run strategic plans                      |
| **dispatching-parallel-agents** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/tree/main/skills/dispatching-parallel-agents)         | Coordinate multiple simultaneous agents                |
| **sharing-skills** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/tree/main/skills/sharing-skills)                      | Distribute and communicate capabilities                |
| **using-superpowers** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/tree/main/skills/using-superpowers)                   | Leverage core platform capabilities                    |
| **csv-data-summarizer** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/csv-data-summarizer)        | Analyze and visualize CSV files (by ComposioHQ)        |
| **domain-name-brainstormer** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/domain-name-brainstormer)   | Generate and check domain ideas (by ComposioHQ)        |
| **lead-research-assistant** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/lead-research-assistant)    | Identify and qualify business leads (by ComposioHQ)    |
| **article-extractor** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/article-extractor)          | Extract web article content (by ComposioHQ)            |
| **content-research-writer** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/content-research-writer)    | Enhance writing with research (by ComposioHQ)          |
| **meeting-insights-analyzer** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/meeting-insights-analyzer)  | Analyze meeting communication patterns (by ComposioHQ) |
| **competitive-ads-extractor** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/competitive-ads-extractor)  | Analyze competitor advertising (by ComposioHQ)         |
| **family-history-research** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/family-history-research)    | Genealogy research assistance (by ComposioHQ)          |
| **notebooklm-integration** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/notebooklm-integration)     | Source-based document interaction (by ComposioHQ)      |
| **markdown-to-epub-converter** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/markdown-to-epub-converter) | Convert markdown to ebook format (by ComposioHQ)       |
| **image-enhancer** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/image-enhancer)             | Improve image quality (by ComposioHQ)                  |

### Development and Testing

| Skill |                                                                                                                                                                    | Description                                               |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------- |
| **ios-simulator-skill** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/conorluddy/ios-simulator-skill)                                     | Control iOS Simulator (also by ComposioHQ)                |
| **ffuf-claude-skill** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/jthack/ffuf_claude_skill)                                           | Web fuzzing with ffuf (also by ComposioHQ)                |
| **playwright-skill** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/lackeyjb/playwright-skill)                                          | Browser automation with Playwright (also by ComposioHQ)   |
| **test-driven-development** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Write tests before implementing code (also by ComposioHQ) |
| **aws-skills** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/aws-skills)              | AWS development and architecture patterns (by ComposioHQ) |
| **changelog-generator** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/changelog-generator)     | Transform git commits into release notes (by ComposioHQ)  |
| **d3js-visualization** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/d3js-visualization)      | Generate interactive data charts (by ComposioHQ)          |
| **move-code-quality-skill** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/move-code-quality-skill) | Analyze Move language code quality (by ComposioHQ)        |
| **pypict-claude-skill** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/pypict-claude-skill)     | Generate comprehensive test cases (by ComposioHQ)         |
| **skill-seekers** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/main/skill-seekers)           | Convert documentation to Claude skills (by ComposioHQ)    |
| **subagent-driven-development** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Development using multiple sub-agents                     |
| **systematic-debugging** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Methodical problem-solving in code                        |
| **root-cause-tracing** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Investigate and identify fundamental problems             |
| **testing-skills-with-subagents** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Collaborative testing approaches                          |
| **testing-anti-patterns** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Identify ineffective testing practices                    |
| **finishing-a-development-branch** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Complete Git code branches                                |
| **requesting-code-review** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Initiate code review processes                            |
| **receiving-code-review** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Process and incorporate code feedback                     |
| **using-git-worktrees** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Manage multiple Git working trees                         |
| **verification-before-completion** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Validate work before finalizing                           |
| **condition-based-waiting** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Manage conditional pauses or delays                       |
| **commands** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Create and manage command structures                      |
| **writing-skills** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                                                   | Develop and document capabilities                         |

### Specialized Domains

| Skill |                                                                                                                                             | Description                             |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------- |
| **claude-scientific-skills** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/K-Dense-AI/claude-scientific-skills)         | Scientific research and analysis skills |
| **claude-win11-speckit-update-skill** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/NotMyself/claude-win11-speckit-update-skill) | Windows 11 system management            |
| **claudisms** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/jeffersonwarrior/claudisms)                  | SMS messaging integration               |
| **defense-in-depth** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers)                            | Multi-layered security approaches       |

## Articles and Tutorials

### 📚 Official

| Article | | Description |
|---------|---|-------------|
| **Claude Skills Quickstart** | [![Docs](https://img.shields.io/badge/docs-blue?logo=readthedocs&logoColor=white)](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/quickstart) | Get started with Claude Skills |
| **Claude Skills Best Practices** | [![Docs](https://img.shields.io/badge/docs-blue?logo=readthedocs&logoColor=white)](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/best-practices) | Best practices for creating skills |
| **Skills Cookbook** | [![Docs](https://img.shields.io/badge/docs-blue?logo=github&logoColor=white)](https://github.com/anthropics/claude-cookbooks/blob/main/skills/README.md) | Skills examples and guides |
| **What Are Skills** | [![Docs](https://img.shields.io/badge/docs-blue?logo=readthedocs&logoColor=white)](https://support.claude.com/en/articles/12512176-what-are-skills) | Introduction to Claude Skills |
| **Using Skills in Claude** | [![Docs](https://img.shields.io/badge/docs-blue?logo=readthedocs&logoColor=white)](https://support.claude.com/en/articles/12512180-using-skills-in-claude) | How to use skills in Claude |
| **How to Create Custom Skills** | [![Docs](https://img.shields.io/badge/docs-blue?logo=readthedocs&logoColor=white)](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills) | Step-by-step guide to creating skills |
| **Create a Skill Through Conversation** | [![Docs](https://img.shields.io/badge/docs-blue?logo=readthedocs&logoColor=white)](https://support.claude.com/en/articles/12599426-how-to-create-a-skill-with-claude-through-conversation) | Create skills by talking to Claude |
| **Claude for Financial Services Skills** | [![Docs](https://img.shields.io/badge/docs-blue?logo=readthedocs&logoColor=white)](https://support.claude.com/en/articles/12663107-claude-for-financial-services-skills) | Industry-specific skills for financial services |
| **Equipping Agents for the Real World** | [![Article](https://img.shields.io/badge/article-blue?logo=medium&logoColor=white)](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) | Technical deep dive into agent skills |
| **Teach Claude Your Way of Working** | [![Docs](https://img.shields.io/badge/docs-blue?logo=readthedocs&logoColor=white)](https://support.claude.com/en/articles/12580051-teach-claude-your-way-of-working-using-skills) | Customize Claude with your workflow |

### 👥 Community

| Article | | Description |
|---------|---|-------------|
| [**Simon Willison: Claude Skills**](https://simonwillison.net/2025/Oct/16/claude-skills/) | [![Blog](https://img.shields.io/badge/blog-blue?logo=rss&logoColor=white)](https://simonwillison.net/2025/Oct/16/claude-skills/) | Introduction to Claude Skills |
| [**Nick Nisi: Claude Skills**](https://nicknisi.com/posts/claude-skills/) | [![Blog](https://img.shields.io/badge/blog-blue?logo=rss&logoColor=white)](https://nicknisi.com/posts/claude-skills/) | Getting started with Claude Skills |
| [**Young Leaders: Skills, Commands, Subagents, Plugins**](https://www.youngleaders.tech/p/claude-skills-commands-subagents-plugins) | [![Blog](https://img.shields.io/badge/blog-blue?logo=rss&logoColor=white)](https://www.youngleaders.tech/p/claude-skills-commands-subagents-plugins) | Comparison of Claude features |

### 🎥 Videos

| Video | | |
|-------|---|---|
| [**Video 1**](https://www.youtube.com/watch?v=421T2iWTQio) | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=421T2iWTQio) | |
| [**Video 2**](https://www.youtube.com/watch?v=G-5bInklwRQ) | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=G-5bInklwRQ) | |
| [**Video 3**](https://www.youtube.com/watch?v=46zQX7PSHfU) | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=46zQX7PSHfU) | |
| [**Video 4**](https://www.youtube.com/watch?v=IoqpBKrNaZI) | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=IoqpBKrNaZI) | |
| [**Video 5**](https://www.youtube.com/watch?v=QpGWaWH1DxY) | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=QpGWaWH1DxY) | |
| [**Video 6**](https://www.youtube.com/watch?v=WKFFFumnzYI) | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=WKFFFumnzYI) | |
| [**Video 7**](https://www.youtube.com/watch?v=FOqbS_llAms) | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=FOqbS_llAms) | |
| [**Video 8**](https://www.youtube.com/watch?v=v1y5EUSQ8WA) | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=v1y5EUSQ8WA) | |
| [**Video 9**](https://www.youtube.com/watch?v=M8yaR-wNGj0) | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=M8yaR-wNGj0) | |
| [**Video 10**](https://www.youtube.com/watch?v=MZZCW179nKM) | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=MZZCW179nKM) | |


## 🤝 Contributing

- Submit new subagents via PR
- Improve existing definitions
- Add new Skills & docs & videos & articles


