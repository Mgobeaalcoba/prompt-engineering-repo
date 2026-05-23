# Gmail inbox triage

```text
Analiza los correos disponibles y arma un triage operativo.

Objetivo:
Detectar que requiere respuesta, que contiene tareas, que puede esperar y que es ruido.

Inputs:
- Correos o hilos: [emails]
- Fecha actual: [today]
- Prioridades conocidas del usuario: [priorities]

Clasifica en:
1. Requiere respuesta hoy
2. Requiere respuesta esta semana
3. Contiene tarea o compromiso
4. Esperando respuesta de otra persona
5. Informativo
6. Puede archivarse o ignorarse, solo como sugerencia

Para cada item devuelve:
- Asunto
- Remitente
- Fecha
- Categoria
- Motivo
- Proxima accion sugerida
- Riesgo si se ignora

Restricciones:
- No marques nada como archivado o respondido.
- No inventes deadlines.
- Si la urgencia es inferida, aclaralo.
```

