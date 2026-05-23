# Generador de titulos para blog

## Tecnica

Few-shot prompting

## Proposito

Crear titulos consistentes para articulos de blog.

## Prompt

```text
Genera 10 titulos para un articulo de blog. Deben ser claros, especificos y orientados a una audiencia profesional. Evita clickbait.

Ejemplos:

Tema: "automatizacion en equipos de ventas"
Titulos:
1. Como automatizar tareas repetitivas en un equipo de ventas
2. Automatizacion comercial: que procesos conviene mejorar primero
3. Guia practica para ahorrar tiempo en ventas con automatizacion

Tema: "seguridad en aplicaciones web"
Titulos:
1. Principios basicos de seguridad para aplicaciones web modernas
2. Como reducir riesgos comunes en una aplicacion web
3. Checklist de seguridad antes de publicar una aplicacion web

Tema:
"[tema]"
```

## Variables editables

| Variable | Descripcion | Ejemplo |
| --- | --- | --- |
| `[tema]` | Tema central | "gestion del conocimiento con IA" |

## Criterios de calidad

- Los titulos son concretos.
- No prometen resultados exagerados.
- Mantienen una voz profesional.

