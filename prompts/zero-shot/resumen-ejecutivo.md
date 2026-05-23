# Resumen ejecutivo

## Tecnica

Zero-shot prompting

## Prompt

```text
Resume el siguiente texto para una audiencia ejecutiva.

Requisitos:
- Maximo 180 palabras.
- Inclui objetivo, hallazgos principales, riesgos y siguiente paso recomendado.
- Usa lenguaje claro y sin jerga innecesaria.
- No agregues informacion que no este en el texto.

Texto:
[texto]
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[texto]` | Documento, transcripcion o informe a resumir |

## Criterios de calidad

- Es breve y orientado a decision.
- Distingue hechos de recomendaciones.
- No inventa datos.

