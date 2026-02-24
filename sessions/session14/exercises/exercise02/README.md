# 📝 Enunciat

## 🎯 Objectiu

Crea una aplicació anomenada **“Habit Tracker Pro”** que permeti registrar quantes vegades has completat diferents hàbits durant el dia.

---

## 📋 Requisits (JavaScript)

1. **Estructura inicial**
   - Mostra 3 hàbits:
     - Beure aigua
     - Fer exercici
     - Llegir
   - Cada hàbit ha de tenir:
     - Un comptador visible (comença a 0)
     - Un botó “+1”

2. **Comptador individual**
   - Cada vegada que es fa clic al botó d’un hàbit:
     - Incrementa només el seu comptador.
     - Actualitza el valor amb `innerText`.

3. **Ús de `dataset`**
   - Cada hàbit ha de tenir:
     - `data-count`
     - `data-goal`
   - El valor real del comptador s’ha de guardar a `dataset`, no només al text visible.

4. **Objectiu diari**
   - Quan `data-count` sigui igual o superior a `data-goal`:
     - Afegeix una classe `.completed`.
     - Mostra un missatge visual indicant que l’hàbit està completat.

5. **Resum global**
   - Mostra un indicador amb:
     - Total d’hàbits completats.
   - S’ha d’actualitzar cada vegada que canviï un comptador.

---

## 🎨 Part visual (HTML5 + CSS3)

- Layout en cards.
- Classe `.completed` amb color verd suau.
- Animació lleu quan s’incrementa el comptador.
- Responsive amb `@media`.

---

## 🔎 Conceptual Focus

- Comptadors independents per element.
- Estat lògic guardat amb `dataset`.
- Diferència entre:
  - Valor visible
  - Valor real intern
- Manipulació dinàmica amb `classList` i `innerText`.
