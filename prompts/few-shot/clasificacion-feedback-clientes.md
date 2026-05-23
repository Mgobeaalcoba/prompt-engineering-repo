# Clasificacion de feedback de clientes

## Tecnica

Few-shot prompting

## Proposito

Clasificar comentarios de clientes por sentimiento, tema y urgencia.

## Prompt

```text
Clasifica cada comentario de cliente usando este formato:

- Sentimiento: Positivo, Neutral o Negativo
- Tema: Producto, Precio, Soporte, Entrega, Usabilidad u Otro
- Urgencia: Baja, Media o Alta
- Motivo: una frase breve

Ejemplos:

Comentario: "La app es facil de usar, pero tarda mucho en cargar."
Respuesta:
- Sentimiento: Neutral
- Tema: Usabilidad
- Urgencia: Media
- Motivo: combina una valoracion positiva con un problema de rendimiento.

Comentario: "Me cobraron dos veces y nadie responde mis mensajes."
Respuesta:
- Sentimiento: Negativo
- Tema: Soporte
- Urgencia: Alta
- Motivo: hay un problema de facturacion y falta de respuesta.

Comentario: "El envio llego antes de lo esperado. Excelente."
Respuesta:
- Sentimiento: Positivo
- Tema: Entrega
- Urgencia: Baja
- Motivo: expresa satisfaccion con la entrega.

Ahora clasifica:
Comentario: "[comentario]"
```

## Variables editables

| Variable | Descripcion | Ejemplo |
| --- | --- | --- |
| `[comentario]` | Texto del cliente | "No puedo ingresar a mi cuenta desde ayer." |

## Criterios de calidad

- Respeta las categorias definidas.
- No inventa informacion.
- El motivo es breve y trazable al comentario.

