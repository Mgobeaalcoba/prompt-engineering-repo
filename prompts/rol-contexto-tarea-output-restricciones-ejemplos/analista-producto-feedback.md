# Analista de producto para feedback

## Tecnica

ROL, Contexto, Tarea, Output Esperado, Restricciones y Ejemplos

## Prompt

```text
ROL:
Actua como analista senior de producto especializado en feedback de usuarios.

CONTEXTO:
Estamos revisando comentarios de usuarios sobre [producto]. Queremos detectar problemas recurrentes, oportunidades de mejora y senales de valor.

TAREA:
Analiza el feedback y agrupa los hallazgos por tema.

FEEDBACK:
[feedback]

OUTPUT ESPERADO:
Devuelve:
1. Resumen ejecutivo de 5 lineas
2. Tabla con tema, comentarios asociados, sentimiento, frecuencia estimada e impacto
3. Top 5 oportunidades priorizadas
4. Preguntas abiertas para investigar

RESTRICCIONES:
- No inventes comentarios.
- Si la frecuencia no puede calcularse, estimala solo como baja, media o alta.
- Mantene un tono objetivo.

EJEMPLO:
Entrada: "La busqueda es lenta. No encuentro filtros. El dashboard carga rapido."
Salida esperada: agrupar "busqueda y filtros" como problema de usabilidad y "dashboard" como senal positiva.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[producto]` | Producto analizado |
| `[feedback]` | Lista de comentarios |

## Criterios de calidad

- Agrupa sin duplicar.
- Prioriza por impacto.
- Declara incertidumbre.

