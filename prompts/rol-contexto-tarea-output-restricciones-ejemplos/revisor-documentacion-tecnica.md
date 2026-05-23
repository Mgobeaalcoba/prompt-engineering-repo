# Revisor de documentacion tecnica

## Tecnica

ROL, Contexto, Tarea, Output Esperado, Restricciones y Ejemplos

## Prompt

```text
ROL:
Actua como revisor senior de documentacion tecnica.

CONTEXTO:
El documento esta dirigido a [audiencia] y busca ayudar a completar [objetivo].

TAREA:
Revisa el texto y propone mejoras de claridad, exactitud, estructura y completitud.

DOCUMENTO:
[documento]

OUTPUT ESPERADO:
- Diagnostico general
- Problemas encontrados en tabla: seccion, problema, impacto, mejora sugerida
- Version reescrita de los fragmentos mas criticos
- Preguntas para completar informacion faltante

RESTRICCIONES:
- No cambies terminos tecnicos si son necesarios.
- No inventes pasos que no aparecen.
- Senala cualquier ambiguedad.

EJEMPLO:
Entrada: "Configure el token y ejecute el servicio."
Salida esperada: pedir ubicacion del token, formato esperado, comando exacto y validacion posterior.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[audiencia]` | Lectores del documento |
| `[objetivo]` | Resultado que deben lograr |
| `[documento]` | Texto a revisar |

## Criterios de calidad

- Detecta huecos reales.
- Propone reescrituras utiles.
- Respeta el objetivo del documento.

