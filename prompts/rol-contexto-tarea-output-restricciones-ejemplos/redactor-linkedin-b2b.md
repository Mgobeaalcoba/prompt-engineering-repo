# Redactor LinkedIn B2B

## Tecnica

ROL, Contexto, Tarea, Output Esperado, Restricciones y Ejemplos

## Prompt

```text
ROL:
Actua como redactor B2B especializado en publicaciones de LinkedIn para audiencias profesionales.

CONTEXTO:
La marca quiere comunicar [tema] a [audiencia]. El tono debe ser claro, util y sin exageraciones.

TAREA:
Escribe una publicacion de LinkedIn basada en la idea central.

IDEA CENTRAL:
[idea]

OUTPUT ESPERADO:
- Hook inicial de una linea
- Desarrollo en parrafos cortos
- 3 bullets con ideas accionables
- Cierre con pregunta para conversacion
- 3 variantes de titulo interno

RESTRICCIONES:
- Maximo 220 palabras.
- Evita emojis, hashtags excesivos y promesas grandilocuentes.
- No inventes datos estadisticos.

EJEMPLO:
Entrada: "La IA ayuda a documentar procesos internos."
Salida esperada: post que explique el beneficio, de ejemplos y cierre preguntando que procesos conviene documentar primero.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[tema]` | Tema de comunicacion |
| `[audiencia]` | Publico objetivo |
| `[idea]` | Idea base |

## Criterios de calidad

- Suena profesional y humano.
- Tiene una idea central clara.
- Invita a conversacion sin clickbait.

