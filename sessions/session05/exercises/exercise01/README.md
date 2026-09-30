# 📝 Enunciado

## 🎯 Objetivo

Crea una **página web** que se parezca **lo máximo posible** a la [**imagen de referencia**](./starter/img/Captura.PNG), partiendo del [**código base proporcionado**](./starter/).  
👉 Puedes **añadir clases e IDs** cuando lo necesites.

---

## 📦 Materiales

- Archivos base en `./starter/`
- Hoja de estilos en `./starter/css/`
- Imágenes en `./starter/img/`

---

## 📋 Requisitos

1. **Solo** implementa la **navegación horizontal** (`nav`) mostrada en la imagen.
2. Utiliza **Flexbox** para **posicionar y alinear** los elementos siempre que sea posible  
   (en algún caso podrás complementar con `margin`).
3. **Centra** el contenido de los **`span` dentro de cada enlace `a`**, **vertical y horizontalmente**.
4. En el elemento **`li` del logo**, aplica **`margin-right`** para separarlo del resto del menú:  
   **no uses un número**, **usa una palabra** (p. ej., `auto`).

> ✅ Mantén una estructura HTML semántica y ordena el CSS de forma clara (reset → variables → layout → componentes).

---

## 🎛️ Pistas técnicas (opcionales)

```css
/* Contenedor del menú */
nav ul {
  display: flex;
  align-items: center;   /* Alineación vertical */
  gap: 1rem;             /* Separación uniforme (si procede) */
  list-style: none;
  padding: 0;
  margin: 0;
}

/* Logo separado del resto */
nav li.logo {
  margin-right: auto;    /* Usa palabra, no número */
}

/* Centrado del texto dentro de los enlaces */
nav a span {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}
```

## 🏆 ADVANCED LEVEL

Añade el **código necesario** para que el **nav vertical** también se vea **igual que en la imagen de referencia**.  
Deberás ajustar su estructura y disposición usando **Flexbox**.
