# 📝 Enunciat

## 🎯 Objectiu

Crea una **pàgina web** que mostri un **spinner** girant de manera **infinita**, utilitzant les propietats d'**animació** explicades a classe.

---

## 📋 Requisits

1. **Crear un spinner animat**
   - El spinner ha de **girar eternament**.
   - Pots construir-lo amb la propietat `border`, fent servir alguns costats **transparents**, per exemple:
     - `border: 1px solid black;`
     - `border-left-color: transparent;`
   - Utilitza `@keyframes` i les propietats d’animació (`animation-duration`, `animation-iteration-count`, `animation-timing-function`, etc.) per aconseguir l’efecte.

---

## 🏆 ADVANCED LEVEL

Crea una **segona animació** perquè el spinner comenci **invisible i petit**, i gradualment **apareixi i creixi** fins a la seva mida final.

- Utilitza `opacity` i `transform: scale()`.
- Amb `forwards`, es queda visible i a mida completa.
- Aquesta animació s’ha d’executar **només un cop**.

> 💡 Pots combinar **dues animacions**: una per girar i una altra per fer creixer l'element.
