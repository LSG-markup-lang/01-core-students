# 📝 Enunciat

## 🎯 Objectiu

Crea un programa que gestioni una **llista de productes d’una botiga** i generi diferents resultats a partir de l’array.

---

## 📋 Requisits (JavaScript)

1. **Dades inicials**

   ```js
   const products = [
     { name: 'Laptop', price: 1200, category: 'tech' },
     { name: 'Mouse', price: 25, category: 'tech' },
     { name: 'Chair', price: 150, category: 'home' },
     { name: 'Desk', price: 300, category: 'home' },
   ];
   ```

2. **Operacions amb arrays**

   - `filter()` → productes `"tech"`
   - `map()` → noms dels productes
   - `reduce()` → preu total
   - `forEach()` → mostrar productes amb format

3. **Mutació controlada**

   - `push()` per afegir producte
   - `pop()` per eliminar l’últim
   - `slice()` per crear còpia parcial

4. **Output**

   - Mostra tots els resultats per `console.log`.

## 🎨 Part visual (HTML5 + CSS3)

1. **Estructura HTML**

   - `<header>` amb el títol **“Gestió de productes”**
   - `<main>` amb 2 cards:
     - Card 1: **“Catàleg”**
     - Card 2: **“Resum de dades”**
   - `<footer>` amb autor o curs

2. **Estils CSS**

   - Layout amb cards modernes
   - 1 columna en mòbil
   - 2 columnes en desktop

> 💡 L’HTML simula una botiga online, però tota la lògica es mostra per consola.
