# 📝 Enunciat

## 🎯 Objectiu

Crea una aplicació anomenada **“Reaction Speed Test”** que mesuri el temps de reacció de l’usuari.

---

## 📋 Requisits (JavaScript)

1. **Estructura inicial**
   - Un botó “Començar”.
   - Una caixa gran amb text informatiu.
   - Un espai per mostrar el resultat.

2. **Funcionament**
   - En clicar “Començar”:
     - La caixa mostra “Espera...”.
     - Després d’un temps aleatori, canvia a “CLICA ARA!”.
   - L’estat de la caixa s’ha de guardar a `dataset`:
     - `data-status` amb valors com `waiting`, `ready`, `finished`.
     - `data-start` per guardar el moment inicial.

3. **Clic de l’usuari**
   - Si l’usuari fa clic quan l’estat és `ready`:
     - Calcula el temps de reacció.
     - Mostra el resultat amb `innerText`.
   - Si fa clic abans:
     - Mostra un missatge de penalització.

4. **Reinici**
   - Permet repetir la prova.
   - Restaura l’estat visual i els atributs `dataset`.

---

## 🎨 Part visual (HTML5 + CSS3)

- Caixa centrada.
- Canvi de color segons estat:
  - Esperant → gris
  - Preparat → verd
  - Massa aviat → vermell
- Transicions suaus.

---

## 🔎 Conceptual Focus

- Estat controlat amb `dataset`.
- Separació entre:
  - Estat lògic
  - Estat visual (`classList`)
- Manipulació de text amb `innerText`.
- Control d’esdeveniments amb `addEventListener`.
- Aplicació basada en canvis d’estat.
