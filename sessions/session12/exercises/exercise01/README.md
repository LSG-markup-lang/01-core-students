# 📝 Enunciat

## 🎯 Objectiu

Crea un petit programa de **conversió d’unitats** (km↔miles, °C↔°F) que calculi conversions simples i mostri el resultat per consola.

---

## 📋 Requisits (JavaScript)

1. **Carrega del JavaScript**

   - Crea un `index.html` que carregui un fitxer extern `main.js` amb `<script ... defer>` al `<head>`.

2. **Variables i tipus**

   - Usa `const` per valors fixos (factors de conversió).
   - Usa `let` per valors que canviïn (entrada de l’usuari i resultat).
   - Treballa amb `number` i `string`.

3. **Condicions**

   - Demana a l’usuari el tipus de conversió amb `prompt` (p. ex. `km-mi`, `mi-km`, `c-f`, `f-c`).
   - Usa `switch` per decidir quina conversió aplicar.
   - Si l’opció no és vàlida, mostra un missatge d’error per `console.log`.

4. **Objecte predefinit `Math`**

   - Arrodoneix el resultat a **2 decimals** (p. ex. multiplicant per 100, `Math.round`, i dividint per 100).

5. **Output**
   - Mostra sempre el resultat per `console.log` amb un format clar (p. ex. `10 km = 6.21 mi`).

---

## 🎨 Part visual (HTML5 + CSS3)

1. **Estructura HTML**

   - Crea una pàgina amb:
     - Un `<header>` amb el títol “Conversor d’unitats”
     - Un `<main>` amb 2 “cards” (`<section class="card">`):
       - Card 1: “Distàncies (km↔mi)”
       - Card 2: “Temperatura (°C↔°F)”
     - Un `<footer>` amb un text petit (autor, curs, etc.)

2. **Estils CSS**
   - Dissenya les cards amb:
     - `padding`, `border-radius`, `box-shadow`
     - Tipografia llegible i espaiat consistent
   - Fes que les cards es vegin en:
     - 1 columna en mòbil
     - 2 columnes en pantalla ampla (`@media`)

> 💡 Pista: encara que el JS no modifiqui el DOM, la pàgina ha de “semblar” una app real.
