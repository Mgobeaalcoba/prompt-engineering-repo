# AGENTS.md — Prompt Engineering Repo

Guía para cualquier agente (Claude Code, Codex, Antigravity/Gemini, Copilot). Los puentes `CLAUDE.md`, `GEMINI.md` y `.github/copilot-instructions.md` apuntan a este archivo.

## Qué es

Biblioteca pública en español de prompts útiles para modelos de IA, organizada por técnica: few-shot, chain-of-thought, zero-shot, multimodal y el patrón rol / contexto / tarea / output esperado / restricciones / ejemplos. Incluye agentes de ejemplo, documentación y plantillas. El `README.md` es el índice y `CONTRIBUTING.md` rige los aportes.

## Estructura

- `prompts/` — prompts organizados por técnica.
- `agents/` — agentes de ejemplo.
- `docs/` — documentación de apoyo; `templates/` — plantillas reutilizables.
- `CHANGELOG.md` — historial de cambios; `README.md` — índice general.

## Cómo trabajar acá

- Un prompt (o set) por archivo/carpeta de técnica, con ejemplo y notas de uso; mantener el índice del README al día.
- Sin credenciales en los ejemplos: placeholders genéricos.
- Español; respetar `CONTRIBUTING.md` y `CODE_OF_CONDUCT.md`.
- Entrada en `CHANGELOG.md` para cambios visibles.

## Estado

Biblioteca estable; última actualización: 23/05/2026.

## Memoria de sesiones

- `memory/STATE.md` (foto del estado) y `memory/LOG.md` (historial *append-only*).
- Al cerrar una sesión con cambios: actualizar STATE, agregar la entrada en LOG y commitear; `scripts/scan_secrets.py` corre como hook pre-commit.
