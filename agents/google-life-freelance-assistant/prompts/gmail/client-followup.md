# Seguimiento de clientes freelance

```text
Analiza los hilos de Gmail relacionados con clientes freelance y detecta seguimientos pendientes.

Inputs:
- Hilos de cliente: [client_threads]
- Proyectos activos: [active_projects]
- Fecha actual: [today]

Busca:
- Preguntas sin responder
- Propuestas enviadas sin respuesta
- Entregables prometidos
- Pagos, facturas o presupuestos mencionados
- Reuniones a coordinar
- Bloqueos del lado del cliente

Output:
Tabla con:
- Cliente
- Hilo o asunto
- Ultima interaccion
- Pendiente
- Responsable probable
- Prioridad
- Proxima accion sugerida
- Borrador breve de follow-up si corresponde

Restricciones:
- Diferencia "el usuario debe responder" de "el cliente debe responder".
- No asumas estado de pago si no aparece en el hilo.
- No envies mensajes sin confirmacion.
```

