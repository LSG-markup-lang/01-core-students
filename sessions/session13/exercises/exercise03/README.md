# 📝 Enunciat

## 🎯 Objectiu

Crea un programa que treballi amb una frase introduïda per l’usuari i en faci diferents transformacions.

---

## 📋 Requisits (JavaScript)

1. **Entrada**

   - Demana una frase amb `prompt()`.

2. **String → Array**

   - `split(" ")` per convertir la frase en array.

3. **Operacions amb arrays**

   - `map()` → paraules en majúscules.
   - `filter()` → paraules amb més de 3 caràcters.
   - `find()` → primera paraula amb lletra `"a"`.
   - `reduce()` → nombre total de caràcters (sense espais).

4. **Array → String**

   - `join("-")` per reconstruir la frase.

5. **Més modificacions**

   - `reverse()` per invertir l’ordre.
   - `slice()` per obtenir les 3 primeres paraules.

6. **Output**

   - Mostra tots els resultats per `console.log`.

---

## 🎨 Part visual (HTML5 + CSS3)

### Estructura HTML

- `<header>` amb el títol **“Processador de text”**
- `<main>` amb 2 cards:
  - Card 1: **“Frase original”**
  - Card 2: **“Transformacions”**
- `<footer>` amb informació del projecte

### Estils CSS

- Disseny net amb `padding` i `box-shadow`
- Responsive:
  - 1 columna en mòbil
  - 2 columnes en pantalla ampla

> 💡 El disseny ha de semblar una eina de processament de text, tot i que la sortida real sigui per consola.
