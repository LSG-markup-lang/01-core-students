# 📝 Enunciat

## 🎯 Objectiu

Crea un programa d’**informe de dates**: l’usuari introdueix una data i el programa calcula informació útil i la mostra per consola.

---

## 📋 Requisits (JavaScript)

1. **Objecte predefinit `Date`**

   - Demana una data amb `prompt` en format `YYYY-MM-DD`.
   - Converteix-la a `Date`.

2. **Validació amb `do...while`**

   - Usa `do...while` per forçar que l’usuari introdueixi una data vàlida.
   - Si la data és invàlida, mostra un missatge i torna-la a demanar.

3. **Càlculs**

   - Calcula la diferència entre la data i avui en dies.
   - Converteix mil·lisegons a dies: `ms / (1000*60*60*24)`.

4. **`switch` o array de dies**

   - Mostra el dia de la setmana en text:
     - amb `switch(date.getDay())`, o
     - amb un array `["diumenge", ...]` i índex.

5. **`Math`**
   - Usa `Math.floor()` o `Math.ceil()` per mostrar dies sencers.
   - Explica amb un comentari per què has triat una o altra.

---

## 🎨 Part visual (HTML5 + CSS3)

1. **Estructura HTML**

   - Crea una pàgina tipus “report” amb:
     - `<header>`: “Informe de dates”
     - `<main>` amb 3 targetes:
       - “Data introduïda”
       - “Dia de la setmana”
       - “Dies de diferència”
     - `<footer>` amb un text de peu

2. **Estils CSS**
   - Estil minimalista de report:
     - grid de cards
     - tipografia i jerarquia (títol, valor gran, text petit)
   - Afegeix una classe visual per “passat” i “futur”:
     - `.status--past`, `.status--future` (decoratiu)

> 💡 Pista: la UI ha de semblar un informe real, encara que els valors surtin només per consola.
