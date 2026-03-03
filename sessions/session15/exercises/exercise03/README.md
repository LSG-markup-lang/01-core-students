# 📝 Enunciat 3 — SpaceX Launchboard (SpaceX API)

## 🎯 Objectiu

Crea un panell que permeti consultar i visualitzar el **darrer llançament** i una **llista de pròxims llançaments** (o els més recents) de SpaceX.

---

## 📋 Requisits (JavaScript)

1. **Controls**
   - Botó “Carregar darrer llançament”.
   - Botó “Carregar llançaments (llista)”.
   - Botó “Netejar”.

2. **Crides a l’API**
   - Llegeix la guia oficial a: `https://github.com/r-spacex/SpaceX-API`.
   - URLs d’exemple:
     - `https://api.spacexdata.com/v4/launches/latest`
     - `https://api.spacexdata.com/v4/launches`
   - Endpoints orientatius:
     - Darrer: `GET /v4/launches/latest`
     - Llista: `GET /v4/launches` (i després en selecciones N amb JS)
   - Implementa-ho amb `async/await` i `try/catch`.

3. **Render (best practice)**
   - Darrer llançament: mostra en una card
     - Nom del llançament
     - Data
     - Estat (success / fail / null)
   - Llista: crea un `<ul>` amb `<li>` per cada llançament.
   - Usa `createElement()` i `appendChild()`.

4. **Ús de dataset (interacció real)**
   - A cada `<li>`, guarda amb `dataset`:
     - `data-launch-id` (id del llançament)
     - `data-success` (true/false/null com string)
   - En fer clic a un `<li>`:
     - Mostra un detall ampliat a la part dreta o sota (detail view),
       reutilitzant les dades del `dataset` i el text del node.

5. **Gestió d’errors i loading**
   - Loading visible mentre carrega.
   - Si falla la xarxa:
     - Mostra missatge clar.
   - Si el JSON no té algun camp:
     - Mostra “—” en comptes de petar.

---

## 🎨 Part visual (HTML5 + CSS3)

- 2 columnes en desktop:
  - Llista a l’esquerra
  - Detall a la dreta
- 1 columna en mòbil.
- Diferencia visual per success/fail (classe CSS).

---

## 🔎 Conceptual Focus

- Consum d’APIs reals amb Promises.
- Render segur i mantenible amb `createElement`.
- Estat per element amb `dataset` + `click`.
