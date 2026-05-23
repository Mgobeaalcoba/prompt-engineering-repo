# Comparacion de alternativas

## Tecnica

Chain-of-thought prompting

## Prompt

```text
Compara estas alternativas para resolver [objetivo]:

Alternativas:
[alternativas]

Contexto:
[contexto]

Evalua cada alternativa segun:
- Beneficio esperado
- Costo o esfuerzo
- Tiempo de implementacion
- Riesgos
- Reversibilidad

Entrega:
1. Tabla comparativa
2. Mejor alternativa para corto plazo
3. Mejor alternativa para largo plazo
4. Recomendacion final
5. Supuestos y dudas

La justificacion debe ser breve, explicita y basada en los criterios anteriores.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[objetivo]` | Resultado buscado |
| `[alternativas]` | Opciones disponibles |
| `[contexto]` | Restricciones y datos relevantes |

## Criterios de calidad

- Compara con criterios consistentes.
- Distingue corto y largo plazo.
- Expone supuestos.

