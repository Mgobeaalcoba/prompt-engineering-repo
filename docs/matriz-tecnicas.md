# Matriz comparativa de tecnicas

| Tecnica | Mejor para | Ventaja principal | Riesgo comun | Mitigacion |
| --- | --- | --- | --- | --- |
| Zero-shot | Tareas directas | Rapidez y simplicidad | Ambiguedad | Definir contexto, formato y restricciones |
| Few-shot | Estilo, clasificacion, formatos | Consistencia | Ejemplos sesgados | Usar ejemplos variados y representativos |
| Chain-of-thought | Analisis y decision | Mejor descomposicion | Exceso de explicacion | Pedir justificacion breve y criterios visibles |
| Multimodal | Imagenes, audio, tablas, JSON | Mayor contexto | Interpretacion incompleta del input | Indicar exactamente que revisar |
| ROL + Contexto + Tarea + Output + Restricciones + Ejemplos | Prompts reutilizables | Robustez y repetibilidad | Prompts demasiado largos | Mantener solo contexto relevante |

## Guia de eleccion rapida

- Necesitas una respuesta simple: usa **zero-shot**.
- Necesitas que copie un formato: usa **few-shot**.
- Necesitas comparar alternativas: usa **chain-of-thought** con razonamiento resumido.
- Necesitas analizar una imagen o archivo: usa **multimodal**.
- Necesitas un prompt para equipo o proceso recurrente: usa **ROL + Contexto + Tarea + Output + Restricciones + Ejemplos**.

