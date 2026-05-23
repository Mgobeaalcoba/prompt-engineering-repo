# Revision de riesgos

## Tecnica

Zero-shot prompting

## Prompt

```text
Analiza los riesgos del siguiente plan:

[plan]

Devuelve:
- Top 5 riesgos ordenados por severidad
- Probabilidad: baja, media o alta
- Impacto: bajo, medio o alto
- Senales tempranas
- Mitigacion recomendada
- Preguntas abiertas

No asumas datos que no esten presentes. Cuando falte informacion, indicalo como pregunta abierta.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[plan]` | Plan, propuesta o estrategia a revisar |

## Criterios de calidad

- Prioriza riesgos reales.
- Incluye mitigaciones accionables.
- Explicita informacion faltante.

