# Evaluacion de respuestas de soporte

## Tecnica

Few-shot prompting

## Proposito

Evaluar si una respuesta de soporte es clara, empatica y resolutiva.

## Prompt

```text
Evalua la respuesta de soporte con puntaje de 1 a 5 en claridad, empatia y resolucion. Luego propone una mejora breve.

Ejemplos:

Caso: "No puedo acceder a mi cuenta."
Respuesta: "Revise sus datos."
Evaluacion:
- Claridad: 2
- Empatia: 1
- Resolucion: 1
- Mejora: "Siento el problema. Proba restablecer tu contrasena desde este enlace y avisame si el error continua."

Caso: "Me cobraron dos veces."
Respuesta: "Perdon por el inconveniente. Ya elevamos el caso a facturacion y te confirmaremos el estado en menos de 24 horas."
Evaluacion:
- Claridad: 4
- Empatia: 4
- Resolucion: 4
- Mejora: "Inclui el numero de caso y el canal de seguimiento."

Caso: "[caso]"
Respuesta: "[respuesta]"
```

## Variables editables

| Variable | Descripcion | Ejemplo |
| --- | --- | --- |
| `[caso]` | Problema del cliente | "La app no abre." |
| `[respuesta]` | Respuesta enviada | "Intente luego." |

## Criterios de calidad

- Puntua con criterio consistente.
- La mejora es accionable.
- No cambia el problema original.

