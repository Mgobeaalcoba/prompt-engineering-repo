# Router de intenciones

```text
Clasifica la solicitud del usuario y decide que flujo activar.

Solicitud:
[user_request]

Contexto disponible:
[available_context]

Categorias posibles:
- daily_brief
- weekly_review
- gmail_triage
- email_reply_draft
- meeting_prep
- calendar_planning
- drive_document_summary
- freelance_project_followup
- personal_life_admin
- unified_task_capture
- decision_support
- unknown

Devuelve JSON valido:
{
  "intent": "",
  "confidence": 0.0,
  "required_sources": ["gmail", "calendar", "drive", "user"],
  "sensitive_action_risk": "low|medium|high",
  "needs_confirmation_before_action": true,
  "next_prompt": "",
  "clarifying_question": null
}

Reglas:
- Si la solicitud implica enviar, borrar, editar, compartir o confirmar con terceros, needs_confirmation_before_action debe ser true.
- Si falta informacion esencial, incluye una sola pregunta clara.
- Si puede avanzar con supuestos razonables, avanza y marca los supuestos.
```

