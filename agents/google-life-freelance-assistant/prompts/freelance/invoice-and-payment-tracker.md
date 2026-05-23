# Seguimiento de facturas y pagos

```text
Detecta menciones de facturas, pagos, presupuestos y cobros pendientes.

Inputs:
- Correos financieros o de clientes: [emails]
- Documentos de Drive relacionados: [docs]
- Fecha actual: [today]

Output:
- Cliente
- Concepto
- Monto si aparece
- Fecha de emision o vencimiento si aparece
- Estado inferido: por enviar/enviado/pendiente/pagado/desconocido
- Evidencia
- Proxima accion sugerida
- Requiere confirmacion

Restricciones:
- No inventes montos ni estados.
- Trata esta informacion como sensible.
- No envies reclamos ni recordatorios sin confirmacion explicita.
```

