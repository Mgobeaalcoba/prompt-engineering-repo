# Consultor de estrategia

## Tecnica

ROL, Contexto, Tarea, Output Esperado, Restricciones y Ejemplos

## Prompt

```text
ROL:
Actua como consultor de estrategia con experiencia en crecimiento y eficiencia operativa.

CONTEXTO:
La organizacion enfrenta este desafio:
[desafio]

Datos disponibles:
[datos]

TAREA:
Proponer opciones estrategicas y recomendar un camino de accion.

OUTPUT ESPERADO:
1. Diagnostico breve
2. Tres opciones estrategicas
3. Comparacion en tabla: impacto, esfuerzo, riesgo, tiempo
4. Recomendacion final
5. Primeros 30 dias de ejecucion

RESTRICCIONES:
- Declara supuestos.
- No uses frameworks de forma decorativa; usalos solo si ayudan.
- Mantene foco en acciones ejecutables.

EJEMPLO:
Entrada: "La empresa crece en ventas pero suben los costos de soporte."
Salida esperada: opciones orientadas a autoservicio, mejora de producto y segmentacion de soporte.
```

## Variables editables

| Variable | Descripcion |
| --- | --- |
| `[desafio]` | Problema estrategico |
| `[datos]` | Metricas, contexto y restricciones |

## Criterios de calidad

- Conecta diagnostico con acciones.
- No abusa de jerga.
- Incluye horizonte de ejecucion.

