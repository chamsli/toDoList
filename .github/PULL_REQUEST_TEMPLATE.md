## 📝 Descripció dels Canvis

Afegeix una funció de lògica de tasques per eliminar les tasques completades de manera pura i reutilitzable. També inclou proves unitàries per validar el comportament i documenta les regles de desenvolupament del repositori per a futurs canvis.

## 🤖 Resum Assistit per IA / Copilot

- S'ha afegit `clearCompletedTasks(tasks)` a `js/taskManager.js`.
- La funció retorna un nou array amb només les tasques pendents.
- No modifica l'array original, i es manté dins del patró de lògica pura del projecte.
- S'han afegit tests a `tests/app.test.js` per verificar:
  - que les tasques completades s'eliminen,
  - que es retorna un nou array,
  - que l'array original no es modifica,
  - que un conjunt totalment completat retorna un array buit.
- S'han incorporat les instruccions del repositori a `.github/copilot-instructions.md` i la plantilla de PR a `.github/PULL_REQUEST_TEMPLATE.md`.

## 🧪 Verificació de Tests i Qualitat
- [x] Els tests unitaris s'executen localment amb `npm test` i passen correctament.
- [x] El codi generat respecta les regles de `.github/copilot-instructions.md`.
