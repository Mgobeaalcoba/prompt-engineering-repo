# Analisis de causa raiz

## Tecnica

Chain-of-thought prompting

## Prompt

```text
Realiza un analisis de causa raiz del siguiente incidente:

Incidente:
[incidente]

Evidencia disponible:
[evidencia]

Formato:
- Resumen del incidente
- Linea de tiempo probable
- Causas contribuyentes
- Causa raiz probable
- Evidencia que falta
- Acciones correctivas
- Acciones preventivas

Usa un razonamiento resumido y verificable. Si algo es incierto, etiquetalo como hipotesis.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[incidente]` | Que ocurrio |
| `[evidencia]` | Datos disponibles |

## Criterios de calidad

- Diferencia causa raiz de sintomas.
- Incluye acciones preventivas.
- Declara incertidumbre.

