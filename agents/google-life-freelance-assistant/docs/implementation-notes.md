# Notas de implementacion

## Arquitectura sugerida

1. **Router**: clasifica la intencion del usuario.
2. **Retriever**: busca contexto en Gmail, Calendar y Drive.
3. **Extractor**: convierte contexto en eventos, tareas, documentos y personas.
4. **Planner**: prioriza y propone acciones.
5. **Consent gate**: detiene acciones sensibles hasta tener confirmacion.
6. **Executor**: ejecuta cambios autorizados.
7. **Reporter**: resume lo hecho y lo pendiente.

## Estados recomendados

- `draft`: propuesta generada pero no confirmada.
- `confirmed`: usuario aprobo accion.
- `executed`: accion realizada.
- `blocked`: falta permiso, informacion o contexto.
- `waiting`: depende de otra persona.

## Logs utiles

Registrar:

- Solicitud del usuario.
- Fuentes consultadas.
- Acciones propuestas.
- Confirmaciones recibidas.
- Acciones ejecutadas.
- Errores o permisos faltantes.

No registrar:

- Tokens o credenciales.
- Contenido sensible completo si no es necesario.
- Datos personales de terceros fuera del minimo operativo.

