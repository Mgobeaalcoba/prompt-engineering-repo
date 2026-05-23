# Task schema

Formato recomendado para representar tareas extraidas por el agente.

```json
{
  "id": "generated-or-external-id",
  "title": "Responder a Cliente X sobre propuesta",
  "domain": "freelance",
  "source": {
    "type": "gmail",
    "reference": "asunto/remitente/fecha"
  },
  "evidence": "El cliente pregunto si podemos avanzar esta semana.",
  "priority": "high",
  "status": "new",
  "due_date": null,
  "next_action": "Redactar borrador de respuesta con disponibilidad.",
  "requires_confirmation": false,
  "sensitivity": "normal"
}
```

## Dominios validos

- freelance
- personal
- administrativo
- finanzas
- salud
- hogar
- aprendizaje
- social

## Estados validos

- new
- in_progress
- waiting
- blocked
- done
- dismissed

