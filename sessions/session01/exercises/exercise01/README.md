# 📝 Enunciado

## 🎯 Objetivo

[A partir de un texto dado](./starter/text.txt), crea un **pequeño sitio web multipágina** utilizando HTML y buenas prácticas básicas de SEO (sin publicarlo en Internet).

---

## 📋 Requisitos generales (para todas las páginas)

1. **Idioma del documento:** define el idioma en `<html lang="…">`.
2. **Encabezados y texto:** utiliza **títulos, subtítulos y párrafos**; **resalta al menos 3 palabras** con sentido (`<strong>`, `<em>`).
3. **Jerarquía de encabezados (obligatoria):** mantén una jerarquía correcta (`<h1>` → `<h2>` → `<h3>`…).
4. **Navegación:** en **cada página** debe haber un **enlace para volver a la página principal**.
5. **Estructura del proyecto:**

   - Dentro de la carpeta del ejercicio estarán:
     - `index.html` → Página principal.
     - Carpeta `pages/` → Otras páginas HTML.
     - Carpeta `img/` → Imágenes en formato `.webp`.

**Ejemplo de estructura de carpetas:**

```text
mi-proyecto/
├── index.html ← Página principal
├── pages/
│ ├─ pagina1.html ← Página de texto
│ └── imagenes.html ← Página de imágenes
└── img/
│ ├── foto1.webp
│ ├── foto2.webp
│ ├── foto3.webp
│ └── foto4.webp
└── README.md
```

> [!TIP]
> Usa un solo `<h1>` por página. A partir de ahí, organiza con `<h2>` y `<h3>` según la profundidad de los temas.

---

## 📄 Páginas a crear

### 1️⃣ Página de texto (`pages/pagina1.html`)

- Usa el [texto dado](./starter/text.txt) como contenido principal.
- Añade un **título** relacionado con el tema del texto.
- Divide el contenido en **varios párrafos** usando `<p>`.
- **Destaca al menos 3 palabras importantes** utilizando `<strong>`.

> [!TIP]
> Mantén los párrafos cortos y claros. Evita mezclar muchos temas en un mismo párrafo.

### 2️⃣ Página principal (`index.html`)

- Contiene un **título** del sitio.
- Muestra una **lista de enlaces** hacia:
  - **Página 1 (texto)**.
  - **Página 2 (imágenes)**.

### 3️⃣ Página de imágenes (`pages/imagenes.html`)

- Añade un **título** que englobe el contenido.
- **Incluye 4 imágenes** relacionadas con el tema del texto.
- **Atributo `alt` obligatorio** y **descriptivo** en **todas** las imágenes.

> [!TIP]
> Escribe `alt` que describa lo que _aporta_ la imagen al contenido (no “imagen1” o “foto”).
> Si la imagen es solo decorativa, indícalo con `alt=""`.

---

## 🏆 ADVANCED LEVEL (opcional)

1. **SEO básico**:
   - Añade **al menos 8 palabras clave** coherentes con el contenido (`<meta name="keywords" content="…">`).
   - Define `<meta name="author" content="Tu Nombre">`.
2. **Caché**:
   - Añade los `meta` necesarios para **indicar que no se guarde en caché** del navegador.
3. **Imágenes**:
   - Las **4 imágenes** deben estar en **formato `.webp`**.
   - Cárgalas de forma **diferida** con `loading="lazy"`.

> [!TIP]
> Coloca las imágenes `.webp` en la carpeta `img/` y usa rutas relativas
> (por ejemplo, desde `pages/imagenes.html` a `../img/foto1.webp`).

---

## 🤝 Integración de soluciones (trabajo en parejas)

Cuando termines, **intercambia tu solución** con un compañero/a y cread una estructura conjunta:

```text
CarpetaSoluciones/
├── CarpetaSolucion1/
│ ├── index.html
│ ├── pages/
│ │ ├── pagina1.html
│ │ └── imagenes.html
│ └── img/
│   ├── foto1.webp
│   ├── foto2.webp
│   ├── foto3.webp
│   └── foto4.webp
├── CarpetaSolucion2/
│ ├── index.html
│ ├── pages/
│ │ ├── pagina1.html
│ │ └── imagenes.html
│ └── img/
│   ├── foto1.webp
│   ├── foto2.webp
│   ├── foto3.webp
│   └── foto4.webp
└── index.html ← Página con enlaces a cada solución
```

> [!TIP]
> Al abrir `CarpetaSolucion1/index.html` o `CarpetaSolucion2/index.html`,
> el sitio debe funcionar correctamente y los enlaces deben seguir funcionando.
