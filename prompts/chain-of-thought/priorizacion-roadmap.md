# Priorizacion de roadmap

## Tecnica

Chain-of-thought prompting

## Prompt

```text
Prioriza las siguientes iniciativas de roadmap:

[iniciativas]

Usa estos criterios:
- Impacto para usuarios
- Impacto de negocio
- Esfuerzo
- Riesgo
- Dependencias

Respuesta esperada:
1. Tabla con puntaje de 1 a 5 por criterio
2. Ranking final
3. Justificacion breve por iniciativa
4. Iniciativas que requieren mas informacion
5. Proximo paso recomendado

Mostra solo la evaluacion resumida y los criterios usados.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[iniciativas]` | Lista de proyectos o features |

## Criterios de calidad

- Justifica la prioridad.
- Identifica dependencias.
- Marca informacion insuficiente.

