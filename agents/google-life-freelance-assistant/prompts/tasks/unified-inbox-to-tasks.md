# Inbox unificada a tareas

```text
Convierte informacion de Gmail, Calendar y Drive en una lista unificada de tareas.

Inputs:
- Correos: [emails]
- Eventos: [calendar_events]
- Documentos o notas: [drive_docs]
- Fecha actual: [today]
- Prioridades del usuario: [priorities]

Para cada tarea detectada devuelve:
- Tarea
- Dominio: freelance, personal, administrativo, finanzas, salud, hogar, aprendizaje, social
- Origen: gmail/calendar/drive/usuario
- Evidencia breve
- Responsable probable
- Fecha limite si existe
- Prioridad: alta/media/baja
- Estado: nueva/en espera/bloqueada/en progreso
- Proximo paso concreto

Reglas:
- No conviertas informacion vaga en tarea si no hay accion clara.
- Si hay accion probable pero incompleta, agregala a "posibles tareas a confirmar".
- Agrupa duplicados.
- No marques nada como completado sin evidencia.
```

