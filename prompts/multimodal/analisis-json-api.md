# Analisis de JSON de API

## Tecnica

Multimodal prompting

## Prompt

```text
Analiza el siguiente JSON de respuesta de API:

[json]

Objetivo:
Explicar que contiene, detectar posibles problemas y sugerir mejoras de contrato.

Formato:
1. Descripcion general
2. Campos principales y significado probable
3. Problemas potenciales: nombres, tipos, valores nulos, consistencia
4. Recomendaciones para consumidores de la API
5. Preguntas para el equipo responsable

Restricciones:
- Devuelve observaciones basadas solo en el JSON.
- Si inferis algo, marcalo como inferencia.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[json]` | Respuesta JSON |

## Criterios de calidad

- Detecta inconsistencias.
- Distingue hechos de inferencias.
- Sugiere mejoras practicas.

