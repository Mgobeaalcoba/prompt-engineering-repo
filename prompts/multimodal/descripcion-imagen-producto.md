# Descripcion de imagen de producto

## Tecnica

Multimodal prompting

## Prompt

```text
Observa la imagen de producto adjunta y genera una descripcion para ecommerce.

Inclui:
- Nombre descriptivo del producto
- Caracteristicas visibles
- Posibles materiales o componentes, marcados como "aparente" si no son seguros
- Beneficios para el comprador
- Texto alternativo accesible

Restricciones:
- No afirmes datos que no puedan inferirse visualmente.
- No menciones marcas si no son claramente visibles.
- Usa tono claro y comercial, sin exagerar.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| Imagen adjunta | Foto del producto |

## Criterios de calidad

- Distingue observacion de inferencia.
- Incluye alt text.
- Evita promesas no verificables.

