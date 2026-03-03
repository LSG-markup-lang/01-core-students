# 📝 Enunciat 2 — Weather Snapshot (Open-Meteo)

## 🎯 Objectiu

Crea una app que mostri un **resum del temps actual** i una **previsió curta** per una ciutat (o coordenades) utilitzant Open-Meteo.

---

## 📋 Requisits (JavaScript)

1. **Inputs i controls**
   - Dos inputs:
     - `latitude`
     - `longitude`
   - Un botó “Consultar”.
   - Un selector (dropdown) amb 3 presets que ompli automàticament lat/long:
     - Barcelona → `41.3874`, `2.1686`
     - Madrid → `40.4168`, `-3.7038`
     - París → `48.8566`, `2.3522`

2. **Crida a l’API**
   - Llegeix la guia oficial a: `https://open-meteo.com/`.
   - URL d’exemple: `https://api.open-meteo.com/v1/forecast?latitude=41.3874&longitude=2.1686&current_weather=true`.
   - Endpoint orientatiu: `GET /v1/forecast?latitude=...&longitude=...&current_weather=true`
   - Implementa la consulta amb `async/await` i `try/catch`.

3. **Render del resultat**
   - Mostra:
     - Temperatura actual
     - Velocitat del vent
     - Hora del registre (time)
   - Render amb `createElement()` (no `innerHTML`).

4. **Estats i errors**
   - Si lat/long estan buits o no són números:
     - Mostra un missatge d’error i NO facis fetch.
   - Si la resposta no inclou `current_weather`:
     - Mostra “Dades no disponibles”.

5. **Bones pràctiques d’implementació**
   - Mantén el flux de consulta en `async/await` + `try/catch` de principi a fi.
   - Organitza el codi en funcions petites (build URL, validació, render, gestió d’errors).

---

## 🎨 Part visual (HTML5 + CSS3)

- Card de resultat amb icona simple (emoji serveix).
- Estat loading visible.
- Responsive.

---

## 🔎 Conceptual Focus

- Validació abans de cridar l’API.
- Gestió d’errors amb `try/catch`.
- Flux asíncron clar i mantenible amb `async/await`.
