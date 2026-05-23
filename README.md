# Prompt Engineering Repo

Repositorio en espanol para organizar prompts utiles al interactuar con modelos de inteligencia artificial. El objetivo es ofrecer una biblioteca practica, versionable y facil de llevar a GitHub, con ejemplos organizados por tecnica de prompting.

## Tecnicas incluidas

- **Few-shot prompting**: usa ejemplos concretos para guiar formato, tono y criterio de respuesta.
- **Chain-of-thought prompting**: estructura el analisis antes de responder. En los ejemplos se recomienda pedir una justificacion breve o razonamiento resumido, sin exigir razonamiento privado extenso.
- **Zero-shot prompting**: pide una tarea directamente, con instrucciones claras y criterios de salida.
- **Multimodal prompting**: combina texto con imagenes, audio, tablas, JSON, CSV u otros datos estructurados.
- **ROL, Contexto, Tarea, Output Esperado, Restricciones y Ejemplos**: patron clasico para prompts robustos y repetibles.

## Estructura

```text
.
├── prompts/
│   ├── few-shot/
│   ├── chain-of-thought/
│   ├── zero-shot/
│   ├── multimodal/
│   └── rol-contexto-tarea-output-restricciones-ejemplos/
├── docs/
│   ├── buenas-practicas.md
│   ├── guia-contribucion.md
│   └── matriz-tecnicas.md
├── templates/
│   └── prompt-template.md
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
└── README.md
```

## Como usar este repositorio

1. Elegi una tecnica segun tu necesidad.
2. Abrir la carpeta correspondiente dentro de `prompts/`.
3. Copiar un ejemplo y reemplazar los campos entre corchetes.
4. Ejecutar el prompt en tu herramienta de IA preferida.
5. Guardar una variante si el resultado fue util y repetible.

## Convencion de archivos

Cada prompt esta documentado con:

- Proposito
- Cuándo usarlo
- Prompt listo para copiar
- Variables editables
- Criterios de calidad
- Posibles adaptaciones

## Recomendaciones rapidas

- Usa **zero-shot** para tareas simples o bien delimitadas.
- Usa **few-shot** cuando necesites imitar estilo, formato o clasificacion.
- Usa **chain-of-thought** cuando la tarea requiera comparacion, diagnostico o planificacion; pedi una explicacion resumida y verificable.
- Usa **multimodal** cuando el input no sea solo texto.
- Usa el patron **ROL + Contexto + Tarea + Output + Restricciones + Ejemplos** para prompts reutilizables en equipos.

## Licencia

Este proyecto esta disponible bajo licencia MIT. Ver [LICENSE](LICENSE).

