# Google Life & Freelance Assistant

Sub-repositorio de prompts para un agente personal conectado al ecosistema Google: Gmail, Google Drive y Google Calendar.

El objetivo del agente es ayudar a organizar tareas freelance y vida personal, convirtiendo correos, eventos, documentos y notas dispersas en prioridades claras, recordatorios, agendas, borradores y proximas acciones.

## Alcance

El agente ayuda con:

- Triage de Gmail.
- Preparacion de reuniones.
- Resumen de documentos de Drive.
- Organizacion de tareas personales y freelance.
- Planificacion semanal y diaria.
- Seguimiento de clientes, entregables y pagos.
- Creacion de borradores de respuesta.
- Deteccion de conflictos de agenda.

## Principio operativo

El agente puede **analizar, resumir, ordenar, proponer y redactar** de forma autonoma.

El agente debe pedir confirmacion antes de:

- Enviar emails.
- Crear, modificar o cancelar eventos.
- Mover, borrar o compartir archivos.
- Confirmar compromisos con terceros.
- Marcar tareas como completadas si no hay evidencia.
- Acceder o procesar informacion especialmente sensible.

## Estructura

```text
agents/google-life-freelance-assistant/
├── prompts/
│   ├── core/
│   ├── gmail/
│   ├── calendar/
│   ├── drive/
│   ├── tasks/
│   ├── freelance/
│   └── personal/
├── playbooks/
├── evals/
├── templates/
├── drive-package/
└── docs/
```

## Prompts principales

- `prompts/core/system-prompt.md`: identidad, reglas y estilo base del agente.
- `prompts/core/router.md`: decide que flujo activar segun la solicitud.
- `prompts/core/safety-and-consent.md`: reglas de consentimiento y acciones sensibles.
- `prompts/tasks/unified-inbox-to-tasks.md`: convierte Gmail, Calendar y Drive en tareas accionables.
- `playbooks/daily-brief.md`: rutina diaria.
- `playbooks/weekly-review.md`: revision semanal.
- `drive-package/`: CSV y documentos importables a Google Drive para la Etapa 2.

## Filosofia de diseno

- Menos ruido, mas claridad.
- Priorizar acciones pequenas y concretas.
- Separar vida personal y trabajo freelance sin perder contexto.
- Ser proactivo con organizacion, conservador con acciones externas.
- Mantener trazabilidad: toda recomendacion debe indicar de donde sale.
