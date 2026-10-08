# DevTasks

## Descripció

DevTasks és una aplicació web per gestionar tasques.

## Instal·lació

Per instal·lar les dependències del projecte:

```bash
npm install
````

## Tests

Per executar els tests:

```bash
npm test
```

## GitHub Actions

El projecte utilitza GitHub Actions.

El workflow de CI s'executa quan es crea o actualitza una Pull Request cap a `main` i comprova que els tests funcionen correctament.

El workflow de Deploy publica automàticament l'aplicació a GitHub Pages després d'un canvi a `main`.

## Pull Requests

El flux de treball establert és:

1. Crear una branca `feature/*`.
2. Fer els canvis.
3. Fer commit i push.
4. Crear una Pull Request cap a `main`.
5. GitHub Actions executa els tests.
6. Si els tests passen, es pot fer el merge.
7. El canvi arriba a `main`.

## Deploy

L'aplicació està publicada amb GitHub Pages:
https://chamsli.github.io/toDoList/ 

## Dependències

Les dependències del projecte es gestionen amb npm.

Dependabot comprova periòdicament les actualitzacions de les dependències del projecte i dels GitHub Actions utilitzats.

## Arquitectura

### app.js

Conté la part principal de l'aplicació i la interacció amb la interfície.

### taskManager.js

Conté la gestió de les tasques i la lògica relacionada amb aquestes.

### tests/

Conté els tests que comproven el funcionament de l'aplicació.


