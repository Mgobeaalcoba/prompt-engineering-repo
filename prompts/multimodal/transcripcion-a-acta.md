# De audio o transcripcion a acta

## Tecnica

Multimodal prompting

## Prompt

```text
A partir del audio adjunto o de esta transcripcion:

[transcripcion]

Genera un acta de reunion con:
- Titulo
- Fecha si aparece
- Participantes mencionados
- Temas tratados
- Decisiones tomadas
- Tareas con responsable y fecha limite si aparecen
- Riesgos o bloqueos
- Preguntas abiertas

Restricciones:
- No inventes participantes, fechas ni responsables.
- Si una tarea no tiene responsable, marca "sin responsable definido".
- Usa formato claro y profesional.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[transcripcion]` | Texto transcripto o resumen del audio |

## Criterios de calidad

- Captura decisiones y tareas.
- No inventa datos faltantes.
- Es util para seguimiento.

