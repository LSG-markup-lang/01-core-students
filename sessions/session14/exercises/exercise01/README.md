# 📝 Enunciat

## 🎯 Objectiu

Crea una petita aplicació web que gestioni una **llista de productes** i permeti marcar-los com a comprats utilitzant l’atribut **`dataset`** per guardar informació personalitzada dins del DOM.

---

## 📋 Requisits (JavaScript)

1. **Estructura inicial**
   - La pàgina contindrà una llista `<ul>` amb diversos `<li>` que representen productes.
   - Cada `<li>` haurà de tenir:
     - Un `data-id`
     - Un `data-price`
     - Un `data-status="pending"`

   Exemple:

   ```html
   <li data-id="1" data-price="2.5" data-status="pending">Llet — 2.5€</li>
   ```

   2. **Selecció d’elements**
   - Usa `querySelector()` o `getElementById()` per obtenir la llista.
   - Usa `querySelectorAll()` per obtenir tots els `<li>`.

2. **Ús de `dataset` (NOU CONCEPTE)**

   ⚠️ No s’ha explicat prèviament.

   ### Indicacions:
   - Qualsevol atribut `data-*` es pot accedir des de JS amb:
     ```js
     element.dataset.nomPropietat;
     ```
   - Exemple:
     ```js
     element.dataset.price;
     ```
   - El valor sempre és un **string**.
   - Pots modificar-lo igual que una propietat normal:
     ```js
     element.dataset.status = 'bought';
     ```

3. **Interacció**
   - Afegeix un `addEventListener("click")` a cada producte.
   - Quan es faci clic:
     - Si `data-status` és `"pending"`:
       - Canvia’l a `"bought"`.
       - Afegeix una classe `.bought` amb `classList`.
     - Si és `"bought"`:
       - Torna’l a `"pending"`.
       - Elimina la classe.

4. **Càlcul dinàmic**
   - Cada vegada que es marqui o desmarqui un producte:
     - Calcula el total dels productes comprats.
     - El preu s’ha d’obtenir des de `dataset.price`.
     - Mostra el total en un element del DOM utilitzant `innerText`.

---

## 🎨 Part visual (HTML5 + CSS3)

1. **Estructura HTML**
   - `<header>` amb el títol “Llista de la compra”
   - `<main>` amb:
     - Una card amb la llista de productes
     - Una card amb el “Total comprat”
   - `<footer>` amb informació del curs

2. **Estils CSS**
   - Cards amb:
     - `padding`
     - `border-radius`
     - `box-shadow`
   - Classe `.bought`:
     - `text-decoration: line-through`
     - `opacity: 0.6`
   - Layout:
     - 1 columna en mòbil
     - 2 columnes en pantalles grans (`@media`)

---

## 🔎 Conceptual Focus

- Entendre què són els atributs `data-*`.
- Accedir i modificar informació personalitzada amb `dataset`.
- Diferenciar:
  - Informació visual (`classList`)
  - Informació d’estat lleuger (`dataset`)
- Recorda que `dataset` sempre retorna **strings** (cal convertir si necessites números).

> ⚠️ Nota professional:
> En una aplicació real, el preu d’un producte no es guardaria al `dataset`.
> Vindria d’una base de dades (API / backend).
> Aquí s’utilitza `dataset` únicament amb finalitat didàctica per practicar manipulació del DOM.
