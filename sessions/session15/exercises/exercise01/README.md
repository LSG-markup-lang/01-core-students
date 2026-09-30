# 📝 Enunciat 1 — Dog Gallery (TheDogAPI)

## 🎯 Objectiu

Crea una mini-aplicació que mostri una **galeria de fotos de gossos** amb control de quantitat i gestió d’errors.

---

## 📋 Requisits (JavaScript)

1. **Inputs i controls**
   - Un `<input type="number">` per indicar quantes imatges vols (1–10).
   - Un botó “Carregar gossos”.
   - Un botó “Netejar galeria”.

2. **Crida a l’API (Promises / async)**
   - Fes una petició a TheDogAPI per obtenir imatges aleatòries.
   - Llegeix la guia oficial a: `https://thedogapi.com/`.
   - URL a usar: `https://api.thedogapi.com/v1/images/search?limit=...`
   - Endpoint orientatiu: `GET /v1/images/search?limit=...`
   - Implementa la crida amb `async/await` i `try/catch`.

3. **Render al DOM (createElement best practice)**
   - Per cada imatge rebuda:
     - Crea un `<img>` amb `createElement()`.
     - Assigna `src` i `alt` amb propietats.
     - Afegeix-lo a la galeria amb `appendChild()`.

4. **Estats de UI**
   - Mentre carrega: mostra un text “Loading…” i desactiva el botó de carregar.
   - Si hi ha error de xarxa o resposta buida:
     - Mostra un missatge d’error visible.

5. **Extra opcional (dataset)**
   - Desa a cada `<img>` un `data-id` amb l’`id` de la imatge retornada per l’API.
   - En fer clic a una imatge, mostra el seu `data-id` en un text a la pantalla.

---

## 🎨 Part visual (HTML5 + CSS3)

- Galeria en grid (responsive).
- Imatges amb `border-radius`.
- Un missatge d’error amb estil destacat.

---

## 🔎 Conceptual Focus

- `fetch()` retorna una Promise.
- `async/await` + `try/catch` per consum professional.
- Render segur: `createElement()` + `appendChild()` + `textContent`.
