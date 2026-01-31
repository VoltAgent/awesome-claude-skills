<a href="https://github.com/Andymcdreamy/awesome-agent-skills">
<img width="1500" height="801" alt="claude-skills" src="https://github.com/user-attachments/assets/3a9d4cb3-04bd-4fb1-9146-fd3b53d26961" />
</a>


<br/>
<br/>

<div align="center">
    <strong>Una colección curada de habilidades (Skills) oficiales para Agentes de los principales equipos de desarrollo y la comunidad.
    </strong>
    <br />
    <br />
    <p>
        <a href="README.md">English</a> |
        <a href="README_es.md">Español</a>
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

# Awesome Agent Skills (Habilidades Increíbles para Agentes)

La "Agent Skills" (Habilidades de Agente) son carpetas con instrucciones, scripts y recursos que enseñan a los asistentes de codificación de IA tareas específicas.

Esta colección incluye habilidades oficiales publicadas por equipos de desarrollo líderes, incluidos Anthropic, Google Labs, Vercel, Stripe, Cloudflare, Trail of Bits, Sentry, Expo, Hugging Face y más, junto con habilidades creadas por la comunidad.

Compatible con Claude Code, Codex, Antigravity, Gemini CLI, Cursor, GitHub Copilot, OpenCode, Windsurf y más. Consulta la tabla a continuación para ver las rutas y la documentación.

El repositorio de habilidades de agente con más contribuciones, construido y mantenido junto con la comunidad.


### ¿Cómo se ve una Habilidad Básica?

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

Consulta el [repositorio oficial](https://github.com/anthropics/skills) y la [guía de creación](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills) para más detalles.

### Rutas de Habilidades para otros Asistentes de Codificación IA

| Herramienta | Ruta del Proyecto | Ruta Global | Documentación Oficial |
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

## Habilidades Oficiales de Claude

### Creación de Documentos

- **[anthropics/docx](https://github.com/anthropics/skills/tree/main/skills/docx)** - Crea, edita y analiza documentos de Word
- **[anthropics/doc-coauthoring](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring)** - Edición colaborativa de documentos
- **[anthropics/pptx](https://github.com/anthropics/skills/tree/main/skills/pptx)** - Crea, edita y analiza presentaciones de PowerPoint
- **[anthropics/xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx)** - Crea, edita y analiza hojas de cálculo de Excel
- **[anthropics/pdf](https://github.com/anthropics/skills/tree/main/skills/pdf)** - Extrae texto, crea PDFs y maneja formularios

### Creatividad y Diseño

- **[anthropics/algorithmic-art](https://github.com/anthropics/skills/tree/main/skills/algorithmic-art)** - Crea arte generativo usando p5.js con aleatoriedad controlada
- **[anthropics/canvas-design](https://github.com/anthropics/skills/tree/main/skills/canvas-design)** - Diseña arte visual en formatos PNG y PDF
- **[anthropics/frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design)** - Herramientas de diseño Frontend y desarrollo UI/UX
- **[anthropics/slack-gif-creator](https://github.com/anthropics/skills/tree/main/skills/slack-gif-creator)** - Crea GIFs animados optimizados para Slack
- **[anthropics/theme-factory](https://github.com/anthropics/skills/tree/main/skills/theme-factory)** - Da estilo a artefactos con temas profesionales o genera temas personalizados

### Desarrollo

- **[anthropics/web-artifacts-builder](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder)** - Construye artefactos HTML complejos para claude.ai con React y Tailwind
- **[anthropics/mcp-builder](https://github.com/anthropics/skills/tree/main/skills/mcp-builder)** - Crea servidores MCP para integrar APIs y servicios externos
- **[anthropics/webapp-testing](https://github.com/anthropics/skills/tree/main/skills/webapp-testing)** - Prueba aplicaciones web locales usando Playwright

### Marca y Comunicación

- **[anthropics/brand-guidelines](https://github.com/anthropics/skills/tree/main/skills/brand-guidelines)** - Aplica colores y tipografía de la marca Anthropic
- **[anthropics/internal-comms](https://github.com/anthropics/skills/tree/main/skills/internal-comms)** - Escribe reportes de estado, boletines y preguntas frecuentes

### Meta

- **[anthropics/skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator)** - Guía para crear habilidades que extienden las capacidades de Claude
- **[anthropics/template](https://github.com/anthropics/skills/tree/main/template)** - Plantilla básica para crear nuevas habilidades

## Habilidades del Equipo de Ingeniería de Vercel

- **[vercel-labs/react-best-practices](https://github.com/vercel-labs/agent-skills/tree/main/skills/react-best-practices)** - Mejores prácticas y patrones de React
- **[vercel-labs/vercel-deploy-claimable](https://github.com/vercel-labs/agent-skills/tree/main/skills/claude.ai/vercel-deploy-claimable)** - Despliega proyectos en Vercel
- **[vercel-labs/web-design-guidelines](https://github.com/vercel-labs/agent-skills/tree/main/skills/web-design-guidelines)** - Guías y estándares de diseño web
- **[vercel-labs/react-native-skills](https://github.com/vercel-labs/agent-skills/tree/main/skills/react-native-skills)** - Mejores prácticas y guías de rendimiento para React Native

## Habilidades del Equipo de Cloudflare

- **[cloudflare/agents-sdk](https://github.com/cloudflare/skills/tree/main/agents-sdk)** - Construye agentes con estado con programación, RPC y servidores MCP
- **[cloudflare/building-ai-agent-on-cloudflare](https://github.com/cloudflare/skills/tree/main/building-ai-agent-on-cloudflare)** - Construye agentes de IA con estado y WebSockets en Cloudflare
- **[cloudflare/building-mcp-server-on-cloudflare](https://github.com/cloudflare/skills/tree/main/building-mcp-server-on-cloudflare)** - Construye servidores MCP remotos con herramientas y OAuth
- **[cloudflare/commands](https://github.com/cloudflare/skills/tree/main/commands)** - Referencia de comandos CLI de Cloudflare
- **[cloudflare/durable-objects](https://github.com/cloudflare/skills/tree/main/durable-objects)** - Coordinación con estado usando RPC, SQLite y WebSockets
- **[cloudflare/web-perf](https://github.com/cloudflare/skills/tree/main/web-perf)** - Audita Web Vitals y recursos que bloquean el renderizado
- **[cloudflare/wrangler](https://github.com/cloudflare/skills/tree/main/wrangler)** - Despliega y gestiona Workers, KV, R2, D1, Vectorize, Queues, Workflows

## Habilidades del Equipo de Supabase

- **[supabase/postgres-best-practices](https://github.com/supabase/agent-skills/tree/main/skills/supabase-postgres-best-practices)** - Mejores prácticas de PostgreSQL para Supabase

## Habilidades de Google Labs (Stitch)

Habilidades de Agente para el servidor MCP de Stitch, compatible con Claude Code, Gemini CLI, Cursor y más.

- **[google-labs-code/design-md](https://github.com/google-labs-code/stitch-skills/tree/main/skills/design-md)** - Crea y gestiona archivos DESIGN.md
- **[google-labs-code/react-components](https://github.com/google-labs-code/stitch-skills/tree/main/skills/react-components)** - Conversión de Stitch a componentes React

## Habilidades del Equipo de Hugging Face

Habilidades oficiales de agentes de IA del equipo de Hugging Face para flujos de trabajo de ML.

- **[huggingface/hugging-face-cli](https://github.com/huggingface/skills/tree/main/skills/hugging-face-cli)** - CLI de HF Hub para modelos, datasets, repos y trabajos de cómputo
- **[huggingface/hugging-face-datasets](https://github.com/huggingface/skills/tree/main/skills/hugging-face-datasets)** - Crea y gestiona datasets con configs y consultas SQL
- **[huggingface/hugging-face-evaluation](https://github.com/huggingface/skills/tree/main/skills/hugging-face-evaluation)** - Evaluación de modelos con vLLM/lighteval y tablas de evaluación
- **[huggingface/hugging-face-jobs](https://github.com/huggingface/skills/tree/main/skills/hugging-face-jobs)** - Ejecuta trabajos de cómputo y scripts de Python en infraestructura HF
- **[huggingface/hugging-face-model-trainer](https://github.com/huggingface/skills/tree/main/skills/hugging-face-model-trainer)** - Entrena modelos con TRL: SFT, DPO, GRPO, conversión GGUF
- **[huggingface/hugging-face-paper-publisher](https://github.com/huggingface/skills/tree/main/skills/hugging-face-paper-publisher)** - Publica papers en HF Hub con enlaces a modelos/datasets
- **[huggingface/hugging-face-tool-builder](https://github.com/huggingface/skills/tree/main/skills/hugging-face-tool-builder)** - Construye scripts reutilizables para operaciones de la API de HF
- **[huggingface/hugging-face-trackio](https://github.com/huggingface/skills/tree/main/skills/hugging-face-trackio)** - Rastrea experimentos de ML con dashboards en tiempo real

## Habilidades del Equipo de Stripe

- **[stripe/stripe-best-practices](https://github.com/stripe/ai/tree/main/skills/stripe-best-practices)** - Mejores prácticas para construir integraciones de Stripe
- **[stripe/upgrade-stripe](https://github.com/stripe/ai/tree/main/skills/upgrade-stripe)** - Actualiza versiones de SDK y API de Stripe

## Habilidades de Seguridad del Equipo Trail of Bits

- **[trailofbits/ask-questions-if-underspecified](https://github.com/trailofbits/skills/tree/main/plugins/ask-questions-if-underspecified)** - Solicita aclaración sobre requisitos ambiguos
- **[trailofbits/audit-context-building](https://github.com/trailofbits/skills/tree/main/plugins/audit-context-building)** - Contexto arquitectónico profundo mediante análisis de código granular
- **[trailofbits/building-secure-contracts](https://github.com/trailofbits/skills/tree/main/plugins/building-secure-contracts)** - Toolkit de seguridad para contratos inteligentes con escáneres de vulnerabilidades
- **[trailofbits/insecure-defaults](https://github.com/trailofbits/skills/tree/main/plugins/insecure-defaults)** - Detecta configuraciones inseguras por defecto (secretos hardcodeados, credenciales por defecto)
- **[trailofbits/modern-python](https://github.com/trailofbits/skills/tree/main/plugins/modern-python)** - Herramientas modernas de Python con uv, ruff, ty y mejores prácticas de pytest
- **[trailofbits/static-analysis](https://github.com/trailofbits/skills/tree/main/plugins/static-analysis)** - Toolkit de análisis estático con CodeQL, Semgrep y SARIF
*Nota: Se han listado las principales. Consulta el repositorio original para la lista completa.*

## Habilidades del Equipo de Expo

Habilidades oficiales de agentes de IA del equipo de Expo para construir, desplegar y depurar aplicaciones Expo.

- **[expo/expo-app-design](https://github.com/expo/skills/tree/main/plugins/expo-app-design)** - Diseña y construye aplicaciones Expo
- **[expo/expo-deployment](https://github.com/expo/skills/tree/main/plugins/expo-deployment)** - Despliega aplicaciones Expo a producción
- **[expo/upgrading-expo](https://github.com/expo/skills/tree/main/plugins/upgrading-expo)** - Actualiza versiones del SDK de Expo

## Habilidades del Equipo de Sentry

- **[getsentry/code-review](https://github.com/getsentry/skills/tree/main/plugins/sentry-skills/skills/code-review)** - Realiza revisiones de código
- **[getsentry/create-pr](https://github.com/getsentry/skills/tree/main/plugins/sentry-skills/skills/create-pr)** - Crea pull requests
- **[getsentry/find-bugs](https://github.com/getsentry/skills/tree/main/plugins/sentry-skills/skills/find-bugs)** - Encuentra e identifica errores en el código

## Habilidades del Equipo Better Auth

- **[better-auth/best-practices](https://github.com/better-auth/skills/tree/main/better-auth/best-practices)** - Mejores prácticas para integración de Better Auth
- **[better-auth/create-auth](https://github.com/better-auth/skills/tree/main/better-auth/create-auth)** - Crea configuración de autenticación con Better Auth

## Habilidades del Equipo Tinybird

- **[tinybirdco/tinybird-best-practices](https://github.com/tinybirdco/tinybird-agent-skills/tree/main/skills/tinybird-best-practices)** - Guías de proyectos Tinybird para fuentes de datos, pipes, endpoints y SQL

## Habilidades del Equipo Neon

- **[neondatabase/using-neon](https://github.com/neondatabase/agent-skills/tree/main/skills/neon-postgres)** - Mejores prácticas para Neon Serverless Postgres

## Habilidad de Ingeniero de Cloudflare

- **[dmmulroy/cloudflare-skill](https://github.com/dmmulroy/cloudflare-skill/tree/main/skill/cloudflare)** - Referencia de la plataforma Cloudflare para Workers, Pages, almacenamiento, IA y redes

## Habilidades del Equipo fal.ai

- **[fal-ai-community/fal-audio](https://github.com/fal-ai-community/skills/blob/main/skills/claude.ai/fal-audio/SKILL.md)** - Texto a voz y voz a texto usando modelos de audio de fal.ai
- **[fal-ai-community/fal-generate](https://github.com/fal-ai-community/skills/blob/main/skills/claude.ai/fal-generate/SKILL.md)** - Genera imágenes y videos usando modelos de IA de fal.ai

## Habilidades del Equipo Remotion

- **[remotion-dev/remotion](https://github.com/remotion-dev/skills/tree/main/skills/remotion)** - Creación programática de videos con React

## Habilidades de la Comunidad

### Marketing

- **[coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills)** - Más de 23 habilidades de marketing para SEO, copywriting, email y anuncios
- **[ComposioHQ/content-research-writer](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/content-research-writer)** - Mejora la escritura con investigación
- **[wshuyi/x-article-publisher-skill](https://github.com/wshuyi/x-article-publisher-skill)** - Publica artículos en X/Twitter

### Productividad y Colaboración

- **[notiondevs/Notion Skills for Claude](https://www.notion.so/notiondevs/Notion-Skills-for-Claude-28da4445d27180c7af1df7d8615723d0)** - Habilidades para trabajar con Notion
- **[op7418/NanoBanana-PPT-Skills](https://github.com/op7418/NanoBanana-PPT-Skills)** - Generación de PPT impulsada por IA con análisis de documentos
- **[gokapso/integrate-whatsapp](https://github.com/gokapso/agent-skills/tree/master/skills/integrate-whatsapp)** - Conecta WhatsApp, configura webhooks y envía mensajes
- **[wrsmith108/linear-claude-skill](https://github.com/wrsmith108/linear-claude-skill)** - Gestiona issues, proyectos y equipos en Linear
- **[Shpigford/readme](https://github.com/Shpigford/skills/tree/main/readme)** - Genera documentación completa del proyecto

### Desarrollo y Pruebas

- **[robzolkos/skill-rails-upgrade](https://github.com/robzolkos/skill-rails-upgrade)** - Analiza aplicaciones Rails y proporciona evaluaciones de actualización
- **[antonbabenko/terraform-skill](https://github.com/antonbabenko/terraform-skill)** - Mejores prácticas de infraestructura como código con Terraform
- **[zxkane/aws-skills](https://github.com/zxkane/aws-skills)** - Desarrollo en AWS con automatización de infraestructura y patrones de arquitectura cloud
- **[sanjay3290/postgres](https://github.com/sanjay3290/ai-skills/tree/main/skills/postgres)** - Ejecuta consultas SQL seguras de solo lectura
- **[lackeyjb/playwright-skill](https://github.com/lackeyjb/playwright-skill)** - Automatización de navegador con Playwright
- **[ibelick/ui-skills](https://github.com/ibelick/ui-skills)** - Restricciones con opinión para guiar a los agentes al construir interfaces
- **[nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)** - Patrones y mejores prácticas de diseño UI/UX
- **[obra/test-driven-development](https://github.com/obra/superpowers/blob/main/skills/test-driven-development/SKILL.md)** - Escribe pruebas antes de implementar código
- **[ComposioHQ/changelog-generator](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/changelog-generator)** - Transforma commits de git en notas de lanzamiento
- **[obra/systematic-debugging](https://github.com/obra/superpowers/blob/main/skills/systematic-debugging/SKILL.md)** - Resolución metódica de problemas en código
- **[fvadicamo/dev-agent-skills](https://github.com/fvadicamo/dev-agent-skills)** - Habilidades de flujo de trabajo Git y GitHub
- **[alinaqi/claude-bootstrap](https://github.com/alinaqi/claude-bootstrap)** - Inicialización de proyectos con "guardrails" de seguridad

### Ingeniería de Contexto

- **[muratcankoylan/context-fundamentals](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-fundamentals)** - Entiende qué es el contexto y por qué importa
- **[muratcankoylan/memory-systems](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/memory-systems)** - Diseña arquitecturas de memoria a corto y largo plazo

### Dominios Especializados

- **[K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)** - Habilidades de investigación y análisis científico
- **[NotMyself/claude-win11-speckit-update-skill](https://github.com/NotMyself/claude-win11-speckit-update-skill)** - Gestión del sistema Windows 11
- **[sanjay3290/imagen](https://github.com/sanjay3290/ai-skills/tree/main/skills/imagen)** - Genera imágenes usando la API de Google Gemini

### Automatización n8n

- **[czlonkowski/n8n-code-javascript](https://github.com/czlonkowski/n8n-skills/tree/main/skills/n8n-code-javascript)** - JavaScript en nodos de Código n8n con patrones de acceso de datos
- **[czlonkowski/n8n-workflow-patterns](https://github.com/czlonkowski/n8n-skills/tree/main/skills/n8n-workflow-patterns)** - Patrones de flujo de trabajo para tareas webhooks, HTTP, bases de datos e IA

### Otros

- **[materials-simulation-skills](https://github.com/HeshamFS/materials-simulation-skills)** - Habilidades de agente para ciencia de materiales computacional
- **[Skill_Seekers](https://github.com/yusufkaraaslan/Skill_Seekers)** - Convierte automáticamente sitios de documentación y repositorios en habilidades de IA.

## 🤝 Contribuir

¡Damos la bienvenida a las contribuciones! Consulta [CONTRIBUTING.md](CONTRIBUTING.md) para ver las pautas.

- Envía nuevas habilidades vía PR
- Mejora las definiciones existentes

**Nota:** Por favor no envíes habilidades que creaste hace 3 horas. Nos enfocamos en habilidades adoptadas por la comunidad, especialmente aquellas publicadas por equipos de desarrollo y probadas en el mundo real. Calidad sobre cantidad.

## Contribuidores ♥️ Gracias
![Contributors](https://contrib.rocks/image?repo=voltagent/awesome-agent-skills&max=500&columns=20&anon=1)

## Licencia

Licencia MIT - ver [LICENSE](LICENSE)

Esta es una lista curada. Las habilidades listadas aquí son creadas y mantenidas por sus respectivos autores y equipos, no por nosotros. Seleccionamos habilidades adoptadas por la comunidad y probadas, pero no auditamos, respaldamos ni garantizamos la seguridad o corrección de los proyectos listados. No están auditados en seguridad y deben ser revisados antes de su uso en producción.

Si encuentras un problema con una habilidad listada o quieres que tu habilidad sea eliminada, por favor [abre un issue](https://github.com/VoltAgent/awesome-agent-skills/issues) y nos ocuparemos de ello prontamente.
