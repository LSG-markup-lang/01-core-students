# 📝 Enunciat

## 🎯 Objectiu

Dissenya un sistema de **gestió d’una llista de tasques** per consola: afegir tasques, marcar-les com a completades i veure un resum.

---

## 📋 Requisits (JavaScript)

1. **Arrays i objectes literals**

   - Crea un array `tasks` que contingui objectes literals amb:
     - `id` (number)
     - `title` (string)
     - `done` (boolean)
   - Els objectes literals s’han de declarar amb `const` (es modifiquen atributs, no la referència).

2. **Bucle principal**

   - Implementa un bucle `while` que mantingui el programa actiu fins que l’usuari escrigui `sortir`.

3. **Accions (condicions)**

   - Demana una acció amb `prompt`: `afegir`, `completar`, `llistar`, `sortir`.
   - Usa `switch` per executar cada acció.
   - Si l’acció no existeix, mostra un error.

4. **Loops**

   - Per llistar tasques:
     - Usa `for...of` (recomanat) o `for` clàssic.
   - Per trobar una tasca per `id`:
     - Recorre amb un loop i compara.

5. **Scope**
   - Declara variables dins del bloc on es necessiten (`let action` dins del `while`).
   - Evita `var`.

---

## 🎨 Part visual (HTML5 + CSS3)

1. **Estructura HTML**

   - Crea un layout amb:
     - `<header>` amb el títol “Task Manager”
     - `<main>` amb:
       - Un bloc “Comandes disponibles” (llista `<ul>`)
       - Un bloc “Model de dades” (petit snippet de l’objecte task, en `<pre>`)

2. **Estils CSS**
   - Dona estil de “dashboard”:
     - contenidor centrat, ample màxim, espaiat
     - seccions amb fons i `border-radius`
   - Afegeix una “badge” visual per a l’estat:
     - `.badge--done` i `.badge--todo` (encara que sigui només decoratiu)

> 💡 Pista: pensa que estàs dissenyant la UI que tindria aquesta app, tot i que ara només funcioni per consola.
