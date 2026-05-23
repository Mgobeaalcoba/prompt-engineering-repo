# Diagnostico de problema

## Tecnica

Chain-of-thought prompting

## Prompt

```text
Diagnostica el siguiente problema y propone pasos de resolucion.

Problema:
[problema]

Datos disponibles:
[datos]

Estructura la respuesta asi:
1. Sintoma principal
2. Hipotesis posibles ordenadas por probabilidad
3. Evidencia a favor y en contra de cada hipotesis
4. Pruebas recomendadas para confirmar o descartar
5. Accion inmediata sugerida

Mantene el analisis breve y trazable a los datos. No inventes causas sin evidencia.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[problema]` | Descripcion del incidente o situacion |
| `[datos]` | Logs, sintomas, metricas o contexto |

## Criterios de calidad

- Separa hipotesis de hechos.
- Propone pruebas concretas.
- No salta a conclusiones.

