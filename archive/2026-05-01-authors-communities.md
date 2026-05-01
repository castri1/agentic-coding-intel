# 2026-05-01 — Autores, comunidades y formato corregido

## Qué se añadió

- Señales públicas de Boris Cherny, creador de Claude Code.
- Señales de Cat Wu y Daisy Hollman sobre Claude Code, plugins, agent teams, plan mode, background tasks y web/iOS.
- Lectura de comunidades activas: Hacker News, GitHub repos, GitHub issues/PRs de Codex.
- Corrección de render: la página ahora usa HTML manual en vez de conversión simple desde Markdown.

## Señales de autores clave

### Boris Cherny

- Publicó que en una próxima versión Claude Code WebFetch añadirá automáticamente `Accept: text/markdown, *` para que sitios de documentación devuelvan Markdown token-efficient.
- Ha destacado plugins como bundles de agents, slash commands, MCP servers y hooks.
- Ha explicado que cambios visuales en `/context` sobre auto-compact eran transparencia cosmética; el auto-compact cerca de ~155k tokens ya existía.
- Ha destacado soporte nativo del Claude Code SDK para Python y TypeScript.

Interpretación: optimizar docs para agentes y empaquetar workflows en plugins/skills es una tendencia central.

### Cat Wu

- Ha comunicado no-waitlist, background tasks, Claude Code web/iOS, plan mode, microcompact, subagents, PDF support y `/add-dir`.

Interpretación: Claude Code se dirige a sesiones largas, multitarea, multi-directorio y multi-superficie.

### Daisy Hollman

- Ha destacado Claude Code plugins y agent teams.

Interpretación: la extensión y coordinación de múltiples agentes son pilares de la evolución de Claude Code.

## Comunidades activas

- Hacker News tiene debates intensos sobre Claude Code: lanzamiento, sourcemap leak, complejidad, OpenClaw, plugins y `/ultrareview`.
- GitHub muestra fuerte actividad en repos como `anthropics/claude-code`, `anthropics/claude-plugins-official`, `awesome-claude-code`, `claude-hud` y marketplaces de plugins/skills.
- Codex tiene actividad fuerte en GitHub issues/PRs: `/goal`, Shift+Enter macOS, sandbox, MCP schema conversion, hooks, remote SSH, memoria editable, ad-hoc instructions y shared plugin paths.

## Fuentes

- https://r.jina.ai/http://https://x.com/bcherny
- https://r.jina.ai/http://https://x.com/_catwu
- https://r.jina.ai/http://https://x.com/The_Whole_Daisy
- https://hn.algolia.com/?q=Claude%20Code
- https://github.com/openai/codex/issues
- https://github.com/openai/codex/pulls
- https://github.com/openai/codex/releases/tag/rust-v0.128.0
