# 📝 Enunciat

## 🎯 Objectiu

Crea un petit programa que analitzi una llista de **notes d’alumnes** i generi estadístiques bàsiques per consola.

---

## 📋 Requisits (JavaScript)

1. **Dades inicials**

   - Crea un array d’objectes:

     ```js
     const students = [
       { name: 'Anna', grade: 8 },
       { name: 'Marc', grade: 5 },
       { name: 'Júlia', grade: 9 },
       { name: 'Pau', grade: 4 },
     ];
     ```

2. **Transformació de dades**

   - Usa `map()` per crear un nou array només amb les notes.
   - Usa `filter()` per obtenir els alumnes aprovats (`grade >= 5`).
   - Usa `find()` per trobar el primer alumne amb nota inferior a 5.

3. **Càlculs**

   - Usa `reduce()` per calcular:
     - La nota mitjana.
     - La nota més alta.

4. **Output**
   - Mostra tots els resultats per `console.log`.

---

## 🎨 Part visual (HTML5 + CSS3)

1. **Estructura HTML**

   - `<header>` amb el títol “Anàlisi de notes”
   - `<main>` amb 2 cards:
     - Card 1: “Llista d’alumnes”
     - Card 2: “Estadístiques”
   - `<footer>` amb informació del curs

2. **Estils CSS**

   - Cards amb `padding`, `border-radius`, `box-shadow`
   - 1 columna en mòbil
   - 2 columnes en pantalles grans (`@media`)

> 💡 El JS no modificarà el DOM, però la pàgina ha de semblar una petita aplicació acadèmica.
