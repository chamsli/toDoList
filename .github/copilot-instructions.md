
# Instrucciones de Desarrollo para DevTasks

1. Arquitectura de Módulos y Desacoplamiento:
- Toda la lógica de negocio (cálculos, validaciones, filtrajes) ha de ir ÚNICAMENTE a `js/taskManager.js` utilizando ES6 Modules (`export`).
- Las funciones de `taskManager.js` han de ser puras (sin referencias a `document`, `window` o `localStorage`).
- La manipulación del DOM, eventos de interfaz y persistencia corresponden exclusivamente a `js/app.js`.

2. Tests Unitarios Con Vitest:
- Para cualquier nueva función o modificación realizada a `taskManager.js`, crea obligatoriamente sus pruebas unitarias en `tests/app.test.js` usando Vitest (`describe`, `it`, `expect`).

3. Estilo y Calidad de Código:
- Utiliza JavaScript moderno (ES6+), funciones claras, nombres de variables descriptivos y evita el uso de variables globales no deseadas.
