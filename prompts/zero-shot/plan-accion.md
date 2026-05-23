# Plan de accion

## Tecnica

Zero-shot prompting

## Prompt

```text
Crea un plan de accion para resolver el siguiente problema:

Problema:
[problema]

Contexto disponible:
[contexto]

Formato de salida:
1. Diagnostico breve
2. Objetivo
3. Acciones priorizadas en tabla con responsable sugerido, esfuerzo, impacto y plazo
4. Riesgos
5. Primer paso para las proximas 24 horas

Restricciones:
- No propongas acciones que requieran informacion no disponible sin marcarlas como supuesto.
- Prioriza acciones realistas.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[problema]` | Situacion a resolver |
| `[contexto]` | Informacion de fondo |

## Criterios de calidad

- Ordena por prioridad.
- Incluye responsables sugeridos.
- Separa supuestos de hechos.

