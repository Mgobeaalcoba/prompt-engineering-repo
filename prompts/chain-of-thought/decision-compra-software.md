# Decision de compra de software

## Tecnica

Chain-of-thought prompting

## Prompt

```text
Ayudame a evaluar una decision de compra de software.

Contexto:
[contexto]

Opciones:
[opciones]

Analiza de forma estructurada:
1. Criterios de decision mas importantes
2. Ventajas y desventajas de cada opcion
3. Riesgos y costos ocultos
4. Supuestos que estas usando
5. Recomendacion final con justificacion breve

No muestres razonamiento interno extenso. Mostra solo el analisis resumido, verificable y orientado a decision.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[contexto]` | Necesidad, equipo, presupuesto, restricciones |
| `[opciones]` | Herramientas o proveedores a comparar |

## Criterios de calidad

- Explica criterios de decision.
- Reconoce supuestos.
- Termina con recomendacion accionable.

