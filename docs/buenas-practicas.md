# Buenas practicas de prompting

## 1. Definir la tarea con precision

Un prompt efectivo dice que se espera, para quien es la salida y que restricciones debe respetar.

Mal:

```text
Explica este tema.
```

Mejor:

```text
Explica [tema] para una persona sin experiencia previa. Usa una analogia, tres puntos clave y un ejemplo practico.
```

## 2. Separar contexto, tarea y formato

La separacion evita que el modelo mezcle informacion de fondo con instrucciones.

```text
Contexto: [informacion relevante]
Tarea: [accion concreta]
Formato: [estructura de salida]
Restricciones: [limites]
```

## 3. Pedir salidas verificables

Cuando sea posible, solicita tablas, listas de chequeo, supuestos explicitos o pasos accionables.

## 4. Evitar ambiguedades

Reemplaza palabras generales como "mejor", "bueno" o "rapido" por criterios concretos:

- "menos de 200 palabras"
- "ordenado por impacto"
- "incluye riesgos y mitigaciones"
- "devuelve solo JSON valido"

## 5. Usar ejemplos cuando el formato importa

Si la respuesta debe seguir un estilo especifico, pocos ejemplos bien elegidos suelen mejorar la consistencia.

## 6. Tratar el razonamiento con cuidado

Para tareas complejas, puede ser util pedir que el modelo analice criterios, compare alternativas o muestre una justificacion breve. Evita depender de razonamientos extensos como si fueran prueba de verdad: valida los resultados con datos, fuentes o pruebas externas.

## 7. Iterar

Un prompt raramente queda perfecto en la primera version. Guarda variantes utiles y documenta que cambio mejoro el resultado.

