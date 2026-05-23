# Playbook: daily brief

## Objetivo

Preparar al usuario para el dia con una vista integrada de agenda, correos, documentos y tareas.

## Fuentes

- Gmail: correos recientes y pendientes.
- Calendar: eventos de hoy y manana temprano.
- Drive: documentos asociados a reuniones o proyectos activos.
- Memoria: preferencias, proyectos y prioridades.

## Prompt operativo

```text
Genera mi brief diario.

Fecha: [today]

Usa:
- Agenda de hoy: [calendar_today]
- Agenda de manana temprano: [calendar_tomorrow_morning]
- Correos pendientes: [pending_emails]
- Documentos relevantes: [relevant_docs]
- Proyectos activos: [active_projects]
- Preferencias: [preferences]

Formato:
1. Lo importante de hoy
2. Agenda con preparacion necesaria
3. Top 3 tareas recomendadas
4. Correos que conviene responder
5. Riesgos o conflictos
6. Bloques sugeridos de foco
7. Cierre: una accion para empezar

Reglas:
- Maximo 700 palabras.
- Separa freelance y personal.
- No propongas mas de 3 prioridades principales.
- Marca todo lo incierto como supuesto.
```

