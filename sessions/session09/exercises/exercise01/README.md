# 📝 Enunciat

## 🎯 Objectiu

Crea una **pàgina web** amb un **títol** i una **icona** centrats, que **canviïn en funció de la mida del dispositiu**.

👉 El títol i la icona han de reflectir el tipus de dispositiu detectat.

---

## 📦 Materials

- Icones de dispositius a `./starter/img/` (per exemple: `phone`, `tablet`, `laptop`, `desktop`)

---

## 📋 Requisits

1. **Títol i icona centrats**

   - A la pàgina hi ha d’haver **un títol** i **una icona**, tots dos **centrats**.
   - Utilitza les **icones donades** al projecte.

2. **Text segons dispositiu**

   - El títol ha de mostrar **només un** dels següents textos:
     - `phone`
     - `tablet`
     - `laptop`
     - `desktop`
   - El text mostrat ha de **correspondre al tamany de la pantalla** (segons les teves _media queries_).

3. **Icona segons dispositiu**

   - La **icona** ha de **correspondre al títol** (si el títol és `tablet`, la icona ha de ser la de _tablet_, etc.).

4. **Color de fons**
   - El **color de fons** de la pàgina ha de **canviar per a cada dispositiu**.
   - Pots definir un color diferent per a `phone`, `tablet`, `laptop` i `desktop`.

---

## 🏆 ADVANCED LEVEL

Fes que el **`<body>` actuï com a contenidor** i adapta les regles de CSS per utilitzar com a indicador el **tamany del contingut** en lloc del **tamany de la pantalla**.

> 💡 Pista: investiga l’ús de **container queries** amb `@container` per canviar l’estil segons l’espai disponible dins del contenidor.
