# STRK — Tienda Deportiva Urbana

Sitio web estático de tienda de ropa deportiva streetwear, desarrollado como parte de la **Evaluación Sumativa 1**. Aplica HTML5 semántico, CSS3 con Flexbox, imágenes reales (Unsplash), formulario de contacto y control de versiones con Git.

---

## 🌐 Vista previa

> Publicado en: [https://MatiKing28821.github.io/Proyecto-1](https://MatiKing28821.github.io/Proyecto-1)

---

## 📁 Estructura de carpetas

```
Proyecto-1/
├── index.html      ← Página principal con HTML5 semántico
├── css/
│   └── styles.css  ← Estilos externos (CSS3 + Flexbox + Grid)
├── .gitignore      ← Archivo de control de versiones
└── README.md       ← Documentación del proyecto
```

---

## 🧱 Secciones del sitio

| Sección | Etiqueta | Descripción |
|---|---|---|
| Header | `<header>` | Logo STRK, navegación, ícono carrito |
| Hero | `<section>` | Imagen de fondo real, título grande, ticker animado |
| Novedades | `<section>` | Grid asimétrico con 3 productos destacados |
| Productos | `<section>` | 6 productos con hover reveal y botón agregar |
| Lookbook | `<section>` | Galería de 4 fotos reales en grid asimétrico |
| Banner | `<section>` | Promo envío gratis sobre fondo negro |
| Contacto | `<section>` | Formulario + datos + foto del equipo |
| Footer | `<footer>` | Links de navegación y créditos |

---

## 🌿 Ramas Git y commits

```
main               ← Versión final estable
develop            ← Integración de cambios
feature/estructura ← HTML5 semántico completo
feature/estilos    ← CSS3, Flexbox y animaciones
```

**Evidencia de commits progresivos:**
- `feature/estructura`: 3 commits con header, navegación, y todas las secciones
- `feature/estilos`: 3 commits con variables CSS, Flexbox, animaciones y grid
- `develop`: Merge de ambas features
- `main`: Versión final después del merge de develop

---

## 🎨 Prompts utilizados durante el desarrollo

### Prompt 1: Estructura HTML5 semántico
**Propósito:** Crear la estructura base con etiquetas semánticas correctas

**Prompt utilizado:**
```
"Crea el HTML5 de una tienda de ropa deportiva urbana llamada STRK. Debe incluir: 
header con logo y navegación, sección hero con imagen de fondo real de Unsplash 
de un atleta urbano, sección novedades con grid asimétrico de 3 productos, 
sección de 6 productos con imágenes de Unsplash, galería lookbook con 4 fotos, 
banner promocional, formulario de contacto con validación HTML5, y footer con links. 
Todas las imágenes deben ser de Unsplash con URLs reales."
```

**Aplicación:**
- Implementó estructura semántica con `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- Agregó 8 secciones completas con contenido coherente
- URLs de imágenes reales de Unsplash (no IA)

---

### Prompt 2: CSS3 con Flexbox y Grid
**Propósito:** Diseñar la identidad visual con CSS3 y maquetación moderna

**Prompt utilizado:**
```
"Diseña el CSS para una tienda deportiva urbana estilo streetwear. Usa fuente 
Bebas Neue para títulos y DM Sans para el cuerpo. Paleta: negro (#0a0a0a), 
blanco, gris (#f4f4f4), y verde lima (#c8f135) como acento. Aplica Flexbox 
en header/footer, grid asimétrico para productos, animaciones hover que 
muestren botones deslizándose desde abajo en tarjetas, transiciones suaves, 
y variables CSS para reutilización."
```

**Aplicación:**
- Sistema de 9 variables CSS (colores, fuentes, efectos)
- Flexbox usado en: header, navegación, footer, formulario, grids
- Grid CSS en: sección lookbook, sección novedades
- Animaciones de hover con transform y opacity

---

### Prompt 3: Ticker animado y animaciones CSS
**Propósito:** Agregar interactividad visual con CSS puro

**Prompt utilizado:**
```
"Crea una banda de texto que se desplace horizontalmente de forma infinita 
usando @keyframes de CSS. El texto debe repetirse sin saltos. Fondo verde lima, 
texto negro, tipografía display, mayúsculas. La animación debe ser continua y suave."
```

**Aplicación:**
- Animación ticker que recorre 22 segundos en bucle infinito
- Transiciones suaves en botones (0.22s)
- Scale effects en imágenes al hacer hover

---

### Prompt 4: Lookbook con Grid asimétrico
**Propósito:** Crear galería de fotos con layout dinámico

**Prompt utilizado:**
```
"Crea un grid CSS asimétrico para una galería de 4 fotos. Una foto debe 
ocupar 2 filas a la izquierda (tall), una foto debe ocupar 2 columnas abajo (wide), 
y 2 fotos pequeñas en la esquina. Todas las imágenes de Unsplash con focus 
deportivo/urbano."
```

**Aplicación:**
- Grid CSS 3x2 con propiedades grid-row y grid-column
- Imágenes de Unsplash de atletas y moda deportiva
- Hover zoom suave en todas las imágenes

---

### Prompt 5: Formulario con validación HTML5
**Propósito:** Implementar formulario funcional y accesible

**Prompt utilizado:**
```
"Crea un formulario de contacto con validación HTML5. Campos: nombre (required), 
email (required, type=email), asunto (optional), mensaje (required, textarea). 
Estilos: fondo gris, borde sutil, focus state con borde negro. Labels en 
mayúscula pequeña, placeholder descriptivos, botón submit oscuro."
```

**Aplicación:**
- Validación HTML5 nativa (required, type=email)
- Estados focus con box-shadow
- Diseño responsive con flexbox
- Integración con sección contacto

---

### Prompt 6: Imágenes reales de Unsplash
**Propósito:** Reemplazar imágenes IA con fotografías reales

**Prompt utilizado:**
```
"Utiliza solo imágenes reales de Unsplash en lugar de IA. Para tienda deportiva 
necesito: fotografías de ropa (camisetas, pantalones, zapatillas, mochilas, 
hoodies, chaquetas), atletas posando, modelos en ropa deportiva, ambientes urbanos. 
Todas con URLs de Unsplash directas."
```

**Aplicación:**
- 20+ URLs de Unsplash integradas
- Fotos de ropa real, accesorios y atletas
- Optimizadas para web (w=600&q=80)

---

## ✅ Tecnologías utilizadas

- **HTML5** — Etiquetas semánticas, imágenes con `alt`, formulario con validación
- **CSS3** — Variables CSS, Flexbox, Grid, @keyframes, transiciones, transforms
- **Imágenes** — Fotografías reales de Unsplash (sin inteligencia artificial)
- **Git** — 4 ramas con commits progresivos y merges
- **GitHub** — Repositorio público con estructura ordenada

---

## 🎯 Cumplimiento de Requerimientos

| Requerimiento | Estado | Detalle |
|---|---|---|
| HTML5 semántico | ✅ | Header, nav, main, section, footer |
| CSS externo | ✅ | styles.css con 687 líneas |
| Flexbox | ✅ | Header, footer, grid de productos, formulario |
| Imágenes | ✅ | 20+ imágenes de Unsplash |
| Enlaces | ✅ | Navegación interna (#), botones, links |
| Formulario | ✅ | Contacto con validación HTML5 |
| Diseño ordenado | ✅ | Coherente, profesional, responsive |
| Git commits | ✅ | 7 commits progresivos |
| 4 ramas | ✅ | main, develop, feature/estructura, feature/estilos |
| README.md | ✅ | Documentación completa con prompts |

---

## 🚀 Cómo usar

### Clonar el repositorio:
```bash
git clone https://github.com/tu-usuario/strk.git
cd strk
```

### Ver el proyecto localmente:
Abre `index.html` en tu navegador, o usa un servidor local:
```bash
# Con Python 3
python -m http.server 8000

# Luego abre: http://localhost:8000
```

### Ver el historial de Git:
```bash
git log --oneline --graph --all
git branch -a
```

---

## 👨‍💻 Autor

Proyecto desarrollado como **Evaluación Sumativa 1** de Desarrollo Web.

**Fecha de entrega:** 13 de abril de 2026
**Plataforma:** GitHub

---

## 📄 Licencia

Este proyecto es de código abierto bajo licencia MIT.
# Proyecto-1
