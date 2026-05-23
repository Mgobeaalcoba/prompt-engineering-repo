# Revision de tabla CSV

## Tecnica

Multimodal prompting

## Prompt

```text
Analiza la tabla CSV adjunta o pegada abajo:

[csv]

Objetivo:
Detectar patrones, errores y oportunidades de mejora.

Entrega:
1. Resumen de columnas y contenido
2. Posibles problemas de calidad de datos
3. Hallazgos relevantes
4. Preguntas que conviene responder con analisis adicional
5. Recomendaciones para limpiar o enriquecer la tabla

Si el archivo es grande, trabaja con la muestra visible y aclara sus limitaciones.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[csv]` | Datos tabulares pegados o adjuntos |

## Criterios de calidad

- Identifica calidad de datos.
- No extrapola mas alla de la muestra.
- Propone acciones concretas.

