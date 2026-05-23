# Reescritura con tono de marca

## Tecnica

Few-shot prompting

## Proposito

Reescribir textos siguiendo una voz de marca consistente.

## Prompt

```text
Reescribe el texto con un tono claro, cercano y profesional. Mantene el significado, evita exageraciones y usa frases breves.

Ejemplos:

Original: "Nuestro sistema permite optimizar procesos internos mediante capacidades avanzadas."
Reescrito: "Nuestro sistema ayuda a que tu equipo trabaje mejor, con procesos mas simples y ordenados."

Original: "Lamentamos los inconvenientes ocasionados por la interrupcion del servicio."
Reescrito: "Perdon por la interrupcion del servicio. Ya estamos trabajando para resolverlo."

Original: "El usuario debera completar la totalidad de los campos solicitados."
Reescrito: "Completa todos los campos solicitados para continuar."

Texto a reescribir:
"[texto]"
```

## Variables editables

| Variable | Descripcion | Ejemplo |
| --- | --- | --- |
| `[texto]` | Texto original | "El cliente debera aguardar la validacion." |

## Criterios de calidad

- Conserva el sentido original.
- Usa tono humano y directo.
- No agrega promesas ni datos nuevos.

