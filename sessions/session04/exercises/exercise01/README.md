# 📝 Enunciado

## 🎯 Objetivo

Crea una **página web** que se asemeje **lo máximo posible** a la **[imagen dada](./starter/img/page.png)**, partiendo del **[código proporcionado](./starter/index.html)**.  
👉 Puedes **añadir clases e IDs** siempre que lo necesites.

---

## 📦 Materiales

- Archivos base en `./starter/`
- Hoja de estilos externa en `./starter/css/`
- Imágenes en `./starter/img/`

---

## 📋 Requisitos

1. Utiliza **una hoja de estilos externa** para el CSS (por ejemplo, `./starter/css/style.css`).
2. Incluye y utiliza **`reset.css`**.
3. Implementa un **efecto parallax** en las imágenes de fondo.
4. Los contenedores (`div`) que crean el efecto parallax deben tener:
   - `width: 100vw`
   - `height: 20vh`
5. Puedes añadir las clases o IDs que necesites para organizar el código.

---

## 🎛️ Pistas técnicas (opcionales)

- Parallax sencillo con CSS:

  ```css
  .parallax {
    background-image: url('./img/bg-01.jpg');
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100vw;
    height: 20vw;
  }

- Recuerda colocar el **reset** antes del resto de estilos.

## 🏆 ADVANCED LEVEL

Añade que **cada vez que el ratón pase por encima** de una de las **imágenes de fondo**, esta se **muestre en blanco y negro**.

> 💡 *Tip:* Puedes hacerlo con la propiedad `filter: grayscale(100%)` sobre un **pseudo-elemento** o aplicarlo directamente al contenedor si la imagen está en `background-image`.
