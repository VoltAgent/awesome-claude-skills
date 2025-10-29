<a href="https://github.com/VoltAgent/voltagent">
<img width="1500" height="500" alt="claude-skills" src="https://github.com/user-attachments/assets/39c54dfd-129e-4b43-8b92-20824a56e069" />
</a>

<br/>
<br/>

<div align="center">
    <strong>The awesome collection of Claude Skills with official and community-built resources.
    </strong>
    <br />
    <br />
    
</div>

<div align="center">
    
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)
[![Twitter Follow](https://img.shields.io/twitter/follow/voltagent_dev?style=social)](https://twitter.com/voltagent_dev)
    
</div>



<div align="center">
 ⚡️ Maintained by the <a href="https://github.com/voltagent/voltagent">VoltAgent </a> open-source AI agent framework community.
    <br />
</div>


# Awesome Claude Skills

Claude Skills are folders with instructions, scripts, and resources that teach Claude specific tasks. Skills can include executable code and are loaded only when needed, allowing you to maintain hundreds without performance impact. Multiple skills can run together for complex tasks like document creation, code testing, and data analysis.

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

|  |                                                                                                                                  |                                         |
| ----- | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- |
| **anthropics/docx** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/document-skills/docx) | Create, edit, and analyze Word documents           |
| **anthropics/pptx** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/document-skills/pptx) | Create, edit, and analyze PowerPoint presentations |
| **anthropics/xlsx** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/document-skills/xlsx) | Create, edit, and analyze Excel spreadsheets       |
| **anthropics/pdf** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/document-skills/pdf)  | Extract text, create PDFs, and handle forms        |

### Creative and Design

|  |                                                                                                                                               |                                                         |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| **anthropics/algorithmic-art** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/algorithmic-art)   | Create generative art using p5.js with seeded randomness           |
| **anthropics/canvas-design** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/canvas-design)     | Design visual art in PNG and PDF formats                           |
| **anthropics/slack-gif-creator** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/slack-gif-creator) | Create animated GIFs optimized for Slack size constraints          |
| **anthropics/theme-factory** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/theme-factory)     | Style artifacts with professional themes or generate custom themes |

### Development

|  |                                                                                                                                               |                                                     |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| **anthropics/artifacts-builder** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/artifacts-builder) | Build complex claude.ai HTML artifacts with React and Tailwind |
| **anthropics/mcp-builder** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/mcp-builder)       | Create MCP servers to integrate external APIs and services     |
| **anthropics/webapp-testing** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/webapp-testing)    | Test local web applications using Playwright                   |

### Branding and Communication

|  |                                                                                                                                              |                                                 |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------- |
| **anthropics/brand-guidelines** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/brand-guidelines) | Apply Anthropic's brand colors and typography to artifacts |
| **anthropics/internal-comms** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/internal-comms)   | Write status reports, newsletters, and FAQs                |

### Meta

|  |                                                                                                                                            |                                                  |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------- |
| **anthropics/skill-creator** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/skill-creator)  | Guide for creating skills that extend Claude's capabilities |
| **anthropics/template-skill** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/anthropics/skills/tree/main/template-skill) | Basic template for creating new skills                      |

## Community Skills

### Productivity and Collaboration

|  |                                                                                                                                                                       |                                             |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ |
| **notiondevs/Notion Skills for Claude** | [![Article](https://img.shields.io/badge/article-blue?logo=medium&logoColor=white)](https://www.notion.so/notiondevs/Notion-Skills-for-Claude-28da4445d27180c7af1df7d8615723d0) | Skills for working with Notion                         |
| **obra/superpowers-lab** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers-lab)                                                  | Lab environment for Claude superpowers                 |
| **obra/brainstorming** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/brainstorming/SKILL.md)                       | Generate and explore ideas                             |
| **obra/writing-plans** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/writing-plans/SKILL.md)                       | Create strategic documentation                         |
| **obra/executing-plans** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/executing-plans/SKILL.md)                     | Implement and run strategic plans                      |
| **obra/dispatching-parallel-agents** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/dispatching-parallel-agents/SKILL.md)         | Coordinate multiple simultaneous agents                |
| **obra/sharing-skills** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/sharing-skills/SKILL.md)                      | Distribute and communicate capabilities                |
| **obra/using-superpowers** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/using-superpowers/SKILL.md)                   | Leverage core platform capabilities                    |
| **ComposioHQ/content-research-writer** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/content-research-writer)    | Enhance writing with research          |
| **ComposioHQ/meeting-insights-analyzer** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/meeting-insights-analyzer)  | Analyze meeting communication patterns |
| **ComposioHQ/competitive-ads-extractor** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/competitive-ads-extractor)  | Analyze competitor advertising         |
| **ComposioHQ/image-enhancer** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/image-enhancer)             | Improve image quality                  |

### Development and Testing

|  |                                                                                                                                                                    |                                                |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------- |
| **conorluddy/ios-simulator-skill** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/conorluddy/ios-simulator-skill)                                     | Control iOS Simulator                |
| **jthack/ffuf-claude-skill** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/jthack/ffuf_claude_skill)                                           | Web fuzzing with ffuf                |
| **lackeyjb/playwright-skill** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/lackeyjb/playwright-skill)                                          | Browser automation with Playwright   |
| **obra/test-driven-development** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/test-driven-development/SKILL.md)                                                   | Write tests before implementing code |
| **ComposioHQ/changelog-generator** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/changelog-generator)     | Transform git commits into release notes  |
| **obra/subagent-driven-development** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/subagent-driven-development/SKILL.md)                                                   | Development using multiple sub-agents                     |
| **obra/systematic-debugging** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/systematic-debugging/SKILL.md)                                                   | Methodical problem-solving in code                        |
| **obra/root-cause-tracing** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/root-cause-tracing/SKILL.md)                                                   | Investigate and identify fundamental problems             |
| **obra/testing-skills-with-subagents** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/testing-skills-with-subagents/SKILL.md)                                                   | Collaborative testing approaches                          |
| **obra/testing-anti-patterns** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/testing-anti-patterns/SKILL.md)                                                   | Identify ineffective testing practices                    |
| **obra/finishing-a-development-branch** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/finishing-a-development-branch/SKILL.md)                                                   | Complete Git code branches                                |
| **obra/requesting-code-review** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/requesting-code-review/SKILL.md)                                                   | Initiate code review processes                            |
| **obra/receiving-code-review** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/receiving-code-review/SKILL.md)                                                   | Process and incorporate code feedback                     |
| **obra/using-git-worktrees** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/using-git-worktrees/SKILL.md)                                                   | Manage multiple Git working trees                         |
| **obra/verification-before-completion** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/verification-before-completion/SKILL.md)                                                   | Validate work before finalizing                           |
| **obra/condition-based-waiting** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/condition-based-waiting/SKILL.md)                                                   | Manage conditional pauses or delays                       |
| **obra/commands** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/tree/main/skills/commands)                                                   | Create and manage command structures                      |
| **obra/writing-skills** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/writing-skills/SKILL.md)                                                   | Develop and document capabilities                         |

### Specialized Domains

|  |                                                                                                                                             |                              |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------- |
| **K-Dense-AI/claude-scientific-skills** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/K-Dense-AI/claude-scientific-skills)         | Scientific research and analysis skills |
| **NotMyself/claude-win11-speckit-update-skill** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/NotMyself/claude-win11-speckit-update-skill) | Windows 11 system management            |
| **jeffersonwarrior/claudisms** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/jeffersonwarrior/claudisms)                  | SMS messaging integration               |
| **obra/defense-in-depth** | [![Source Code](https://img.shields.io/badge/source-code-blue?logo=github)](https://github.com/obra/superpowers/blob/main/skills/defense-in-depth/SKILL.md)                            | Multi-layered security approaches       |

## Articles and Tutorials

### 📚 Official

| Article | |  |
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

| Article | |  |
|---------|---|-------------|
| [**Simon Willison: Claude Skills**](https://simonwillison.net/2025/Oct/16/claude-skills/) | [![Blog](https://img.shields.io/badge/blog-blue?logo=rss&logoColor=white)](https://simonwillison.net/2025/Oct/16/claude-skills/) | Introduction to Claude Skills |
| [**Nick Nisi: Claude Skills**](https://nicknisi.com/posts/claude-skills/) | [![Blog](https://img.shields.io/badge/blog-blue?logo=rss&logoColor=white)](https://nicknisi.com/posts/claude-skills/) | Getting started with Claude Skills |
| [**Young Leaders: Skills, Commands, Subagents, Plugins**](https://www.youngleaders.tech/p/claude-skills-commands-subagents-plugins) | [![Blog](https://img.shields.io/badge/blog-blue?logo=rss&logoColor=white)](https://www.youngleaders.tech/p/claude-skills-commands-subagents-plugins) | Comparison of Claude features |

### 🎥 Videos

| Video | | |
|-------|---|---|
| **Claude Skills Just 10x'd My AI Agents by Greg Isenberg** | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=G-5bInklwRQ) | |
| **Claude Skills: Build Your Own AI Experts (Full Breakdown)** | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=46zQX7PSHfU) | |
| **Agent Skills: Specialized capabilities you can customize** | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=IoqpBKrNaZI) | |
| **Claude Skills—From TOY to TOOL: Grab My Tutorial** | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=WKFFFumnzYI) | |
| **Claude Skills: Glimpse of Continual Learning?** | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=FOqbS_llAms) | |
| **Stop Using MCP... Use NEW Claude Skills Instead** | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=M8yaR-wNGj0) | |
| **Claude Skills explained: How to create reusable AI workflows** | [![YouTube](https://img.shields.io/badge/YouTube-red?logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=MZZCW179nKM) | |



## 🤝 Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

- Submit new skills via PR
- Improve existing definitions
- Add new docs & videos & articles

