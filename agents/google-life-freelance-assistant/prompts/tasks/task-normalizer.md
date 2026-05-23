# Normalizador de tareas

```text
Normaliza tareas dispersas en acciones claras.

Entrada:
[raw_tasks]

Convierte cada item a:
- Verbo de accion
- Resultado esperado
- Contexto minimo
- Fecha limite
- Fuente
- Proximo paso

Ejemplo:
"Cliente X" -> "Responder a Cliente X sobre [tema pendiente] revisando el hilo [origen]."

Reglas:
- Si la tarea no tiene verbo, proponelo.
- Si falta contexto, marca "necesita aclaracion".
- Evita tareas gigantes; dividilas en pasos pequenos.
```

