<a href="https://github.com/Andymcdreamy/awesome-agent-skills">
<img width="1500" height="801" alt="claude-skills" src="https://github.com/user-attachments/assets/3a9d4cb3-04bd-4fb1-9146-fd3b53d26961" />
</a>


<br/>
<br/>

<div align="center">
    <strong>主要な開発チームやコミュニティによる公式エージェントスキルの厳選コレクション。
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

# Awesome Agent Skills (素晴らしいエージェントスキル)

「Agent Skills (エージェントスキル)」は、AIコーディングアシスタントに特定のタスクを教えるための手順、スクリプト、リソースを含むフォルダです。

このコレクションは、Anthropic、Google Labs、Vercel、Stripe、Cloudflare、Trail of Bits、Sentry、Expo、Hugging Faceなどの主要な開発チームによって公開された公式スキルと、コミュニティによって作成されたスキルを特徴としています。

Claude Code、Codex、Antigravity、Gemini CLI、Cursor、GitHub Copilot、OpenCode、Windsurfなどと互換性があります。パスとドキュメントについては、以下の表を参照してください。

コミュニティとともに構築・維持されている、最も貢献数の多いエージェントスキルリポジトリです。


### 基本的なスキルの構成

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

詳細は [公式リポジトリ](https://github.com/anthropics/skills) および [作成ガイド](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills) を参照してください。

### 他のAIコーディングアシスタントのスキルパス

| ツール | プロジェクトパス | グローバルパス | 公式ドキュメント |
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

## 公式 Claude スキル

### ドキュメント作成

- **[anthropics/docx](https://github.com/anthropics/skills/tree/main/skills/docx)** - Wordドキュメントの作成、編集、分析
- **[anthropics/doc-coauthoring](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring)** - ドキュメントの共同編集と共著
- **[anthropics/pptx](https://github.com/anthropics/skills/tree/main/skills/pptx)** - PowerPointプレゼンテーションの作成、編集、分析
- **[anthropics/xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx)** - Excelスプレッドシートの作成、編集、分析
- **[anthropics/pdf](https://github.com/anthropics/skills/tree/main/skills/pdf)** - テキスト抽出、PDF作成、フォーム処理

### クリエイティブ・デザイン

- **[anthropics/algorithmic-art](https://github.com/anthropics/skills/tree/main/skills/algorithmic-art)** - p5.jsを使用したシードランダム性のあるジェネレーティブアートの作成
- **[anthropics/canvas-design](https://github.com/anthropics/skills/tree/main/skills/canvas-design)** - PNGおよびPDF形式でのビジュアルアートのデザイン
- **[anthropics/frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design)** - フロントエンドデザインとUI/UX開発ツール
- **[anthropics/slack-gif-creator](https://github.com/anthropics/skills/tree/main/skills/slack-gif-creator)** - Slackのサイズ制限に最適化されたアニメーションGIFの作成
- **[anthropics/theme-factory](https://github.com/anthropics/skills/tree/main/skills/theme-factory)** - プロフェッショナルなテーマで成果物をスタイリング、またはカスタムテーマの生成

### 開発

- **[anthropics/web-artifacts-builder](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder)** - ReactとTailwindを使用した複雑なclaude.ai HTMLアーティファクトの構築
- **[anthropics/mcp-builder](https://github.com/anthropics/skills/tree/main/skills/mcp-builder)** - 外部APIやサービスを統合するためのMCPサーバーの作成
- **[anthropics/webapp-testing](https://github.com/anthropics/skills/tree/main/skills/webapp-testing)** - Playwrightを使用したローカルWebアプリケーションのテスト

### ブランディング・コミュニケーション

- **[anthropics/brand-guidelines](https://github.com/anthropics/skills/tree/main/skills/brand-guidelines)** - Anthropicのブランドカラーとタイポグラフィを成果物に適用
- **[anthropics/internal-comms](https://github.com/anthropics/skills/tree/main/skills/internal-comms)** - ステータスレポート、ニュースレター、FAQの作成

### メタ

- **[anthropics/skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator)** - Claudeの機能を拡張するスキルを作成するためのガイド
- **[anthropics/template](https://github.com/anthropics/skills/tree/main/template)** - 新しいスキルを作成するための基本テンプレート

## Vercel エンジニアリングチームによるスキル

- **[vercel-labs/react-best-practices](https://github.com/vercel-labs/agent-skills/tree/main/skills/react-best-practices)** - Reactのベストプラクティスとパターン
- **[vercel-labs/vercel-deploy-claimable](https://github.com/vercel-labs/agent-skills/tree/main/skills/claude.ai/vercel-deploy-claimable)** - プロジェクトをVercelにデプロイ
- **[vercel-labs/web-design-guidelines](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines)** - Webデザインのガイドラインと標準

## Cloudflare チームによるスキル

- **[cloudflare/agents-sdk](https://github.com/cloudflare/skills/tree/main/agents-sdk)** - スケジューリング、RPC、MCPサーバーを備えたステートフルAIエージェントの構築
- **[cloudflare/wrangler](https://github.com/cloudflare/skills/tree/main/wrangler)** - Workers、KV、R2、D1、Vectorize、Queues、Workflowsのデプロイと管理

## Hugging Face チームによるスキル

- **[huggingface/hugging-face-cli](https://github.com/huggingface/skills/tree/main/skills/hugging-face-cli)** - モデル、データセット、リポジトリ、計算ジョブのためのHF Hub CLI
- **[huggingface/hugging-face-model-trainer](https://github.com/huggingface/skills/tree/main/skills/hugging-face-model-trainer)** - TRLを使用したモデルトレーニング: SFT, DPO, GRPO, GGUF変換

##  コミュニティスキル

### マーケティング

- **[coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills)** - SEO、コピーライティング、メール、広告のための23以上のマーケティングスキル

### 生産性とコラボレーション

- **[notiondevs/Notion Skills for Claude](https://www.notion.so/notiondevs/Notion-Skills-for-Claude-28da4445d27180c7af1df7d8615723d0)** - Notionを扱うためのスキル
- **[Shpigford/readme](https://github.com/Shpigford/skills/tree/main/readme)** - 包括的なプロジェクトドキュメントの生成

### 開発とテスト

- **[antonbabenko/terraform-skill](https://github.com/antonbabenko/terraform-skill)** - Terraformによるインフラストラクチャ・アズ・コード (IaC) のベストプラクティス
- **[zxkane/aws-skills](https://github.com/zxkane/aws-skills)** - インフラ自動化とクラウドアーキテクチャパターンを用いたAWS開発
- **[lackeyjb/playwright-skill](https://github.com/lackeyjb/playwright-skill)** - Playwrightによるブラウザ自動化

## 🤝 貢献

貢献を歓迎します！ガイドラインについては [CONTRIBUTING.md](CONTRIBUTING.md) を参照してください。

- PR経由で新しいスキルを提出
- 既存の定義の改善

## コントリビューター ♥️ ありがとう
![Contributors](https://contrib.rocks/image?repo=voltagent/awesome-agent-skills&max=500&columns=20&anon=1)

## ライセンス

MITライセンス - [LICENSE](LICENSE) を参照

*注: これは主要なリストです。完全なリストについては元のリポジトリを参照してください。*
