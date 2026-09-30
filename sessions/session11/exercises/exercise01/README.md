# 📝 Enunciat

## 🎯 Objectiu

Dissenya una **targeta interactiva** que utilitzi un **pseudo-element** per crear un **halo** quan l’usuari hi passi el ratolí per sobre.

L’efecte s’ha de fer **només amb CSS**, sense afegir cap element HTML extra per fer de halo.

---

## 📋 Requisits

1. **Targeta base**

   - Crea una targeta (per exemple, un `<div>` amb una classe `.card`) amb:
     - Un títol breu
     - Un petit text descriptiu
   - La targeta ha de tenir:
     - Fons clar o fosc
     - `padding` suficient perquè el text “respiri”
     - `border-radius` per suavitzar les cantonades

2. **Halo amb pseudo-element**
   - Fes que la targeta tingui un **pseudo-element** (`::before` o `::after`) que actuarà com a **halo** al darrere del contingut.
   - Aquest pseudo-element ha de:
     - Estar posicionat **darrere** del contingut (`position` + `z-index`)
     - Tenir una forma suau (circular, ovalada, taca difuminada…)
     - Tenir un color o gradient que doni sensació de **llum o resplendor**

> 💡 Pista: pensa el halo com una “ombra lluminosa” creada amb un pseudo-element posicionat absolutament i escapat una mica dels límits de la targeta.

---

## 🏆 ADVANCED LEVEL

**Efecte en passar el ratolí (`:hover`)**

- En estat normal, el halo ha de ser **molt subtil** o pràcticament invisible (per exemple, amb `opacity` molt baixa o `scale` més petit).
- Quan l’usuari passi el ratolí per sobre de la targeta:
  - El halo s’ha de fer **clarament visible**.
  - Pots modificar propietats com:
    - `opacity`
    - `transform` (`scale`, `translate`, etc.)
    - Intensitat del color o del gradient
- Pots utilitzar **`transition`** per fer que el canvi sigui suau, però **no** s’han de fer servir animacions amb `@keyframes`.
