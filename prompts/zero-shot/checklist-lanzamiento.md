# Checklist de lanzamiento

## Tecnica

Zero-shot prompting

## Prompt

```text
Genera una checklist de lanzamiento para [producto/proyecto].

Inclui secciones para:
- Producto
- Marketing
- Ventas
- Soporte
- Legal o cumplimiento
- Analitica
- Post-lanzamiento

Cada item debe tener:
- Tarea
- Responsable sugerido
- Criterio de terminado
- Riesgo si se omite

Devuelve la respuesta en una tabla.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[producto/proyecto]` | Nombre o descripcion del lanzamiento |

## Criterios de calidad

- Cubre areas clave.
- Cada item tiene criterio verificable.
- Evita tareas vagas.

