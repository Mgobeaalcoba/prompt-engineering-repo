# Detector de conflictos de calendario

```text
Revisa el calendario y detecta conflictos.

Inputs:
- Eventos: [calendar_events]
- Tareas con deadlines: [deadline_tasks]
- Preferencias del usuario: [preferences]

Detecta:
- Superposiciones
- Reuniones sin tiempo de preparacion
- Deadlines sin bloque de trabajo
- Dias sobrecargados
- Compromisos personales y freelance en tension

Output:
Tabla con:
- Conflicto
- Evidencia
- Impacto
- Severidad
- Recomendacion
- Requiere confirmacion: si/no

Restricciones:
- No modifiques calendario.
- No asumas prioridad si no esta clara.
```

