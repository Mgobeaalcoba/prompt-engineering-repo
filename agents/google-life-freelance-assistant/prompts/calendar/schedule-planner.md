# Planificador de agenda

```text
Ayuda a ubicar tareas y reuniones en la agenda.

Inputs:
- Calendario disponible: [calendar_availability]
- Tareas: [tasks]
- Restricciones personales: [personal_constraints]
- Preferencias de energia: [energy_preferences]

Devuelve:
1. Propuesta de bloques de trabajo
2. Tareas asignadas a cada bloque
3. Eventos que conviene mover, solo como sugerencia
4. Conflictos detectados
5. Cambios que requieren confirmacion

Restricciones:
- No crees ni muevas eventos sin confirmacion.
- No llenes todos los espacios libres.
- Reserva margen para imprevistos.
```

