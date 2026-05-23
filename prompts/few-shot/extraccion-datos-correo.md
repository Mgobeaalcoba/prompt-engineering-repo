# Extraccion de datos desde correos

## Tecnica

Few-shot prompting

## Proposito

Extraer datos operativos de correos en un JSON consistente.

## Prompt

```text
Extrae los datos del correo y devuelve solo JSON valido con estas claves:
cliente, fecha_solicitada, producto, cantidad, prioridad, notas.
Si un dato no aparece, usa null.

Ejemplos:

Correo: "Hola, soy Ana de Norte SA. Necesitamos 20 licencias de Analytics Pro para el 12/06. Es urgente porque arrancamos una implementacion."
JSON:
{"cliente":"Norte SA","fecha_solicitada":"12/06","producto":"Analytics Pro","cantidad":20,"prioridad":"alta","notas":"Arrancan una implementacion."}

Correo: "Buenas, consulto por precios de 5 usuarios del plan Starter. No tenemos fecha definida."
JSON:
{"cliente":null,"fecha_solicitada":null,"producto":"plan Starter","cantidad":5,"prioridad":"media","notas":"Consulta por precios."}

Correo: "Necesitamos renovar el paquete Enterprise. Somos Delta Group."
JSON:
{"cliente":"Delta Group","fecha_solicitada":null,"producto":"paquete Enterprise","cantidad":null,"prioridad":"media","notas":"Renovacion."}

Correo:
"[correo]"
```

## Variables editables

| Variable | Descripcion | Ejemplo |
| --- | --- | --- |
| `[correo]` | Cuerpo del email | "Hola, soy..." |

## Criterios de calidad

- Devuelve solo JSON valido.
- Usa null cuando falta informacion.
- No deduce datos sin evidencia.

