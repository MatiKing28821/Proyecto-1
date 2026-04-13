# 📝 CSS - Documentación Técnica

## Archivo Principal: `styles.css`

### 📌 Variables CSS Globales
```css
:root {
  --black:   #0a0a0a;
  --white:   #ffffff;
  --gray:    #f4f4f4;
  --gray2:   #e8e8e8;
  --muted:   #888;
  --text:    #111;

  --lime:    #c8f135;     /* Acento principal */
  --orange:  #ff5c1a;     /* Acento secundario */
  --blue:    #1a6cff;     /* Acento terciario */

  --font-display: 'Bebas Neue', sans-serif;
  --font-body:    'DM Sans', sans-serif;

  --radius:  12px;
  --radius-lg: 20px;
  --shadow:  0 4px 20px rgba(0,0,0,0.1);
  --shadow-lg: 0 12px 40px rgba(0,0,0,0.18);
  --trans: 0.22s ease;
}
```

---

## 🏗️ Secciones CSS

### 1. **HEADER** (Sticky)
- Posición sticky para mantener visible
- Flexbox: logo | nav | carrito
- Bordes y sombras sutiles
- Transiciones suaves en hover

### 2. **HERO**
- Imagen de fondo (100vh)
- Gradiente overlay
- Ticker animado (22s)
- Botones con efectos

### 3. **NOVEDADES**
- Grid asimétrico (flex)
- Card con hover elevado
- Imagen con zoom
- Badges (NEW, SALE)

### 4. **PRODUCTOS**
- Grid responsive (flex-wrap)
- Tarjetas con botón reveal
- Filtros con estado active
- Rating y precio

### 5. **LOOKBOOK**
- CSS Grid (3x2)
- Tamaños asimétricos
- Zoom en hover

### 6. **BANNER**
- Fondo negro
- Tipografía grande
- Acento verde lima

### 7. **CONTACTO**
- Layout flex (2 columnas)
- Formulario HTML5
- Avatar del equipo
- Focus states

### 8. **FOOTER**
- Flexbox responsive
- Links con hover color
- Fondo oscuro

---

## 🎨 Paleta de Colores

| Color | Variable | Uso |
|-------|----------|-----|
| Negro | `--black` | Fondos, textos, bordes |
| Blanco | `--white` | Fondos claros, texto |
| Gris | `--gray` | Fondos secundarios |
| Gris 2 | `--gray2` | Bordes sutiles |
| Muted | `--muted` | Texto secundario |
| Verde lima | `--lime` | Acentos principales |
| Naranja | `--orange` | Tags, badges |
| Azul | `--blue` | Alternativa |

---

## 📐 Sistema de Tipografía

### Display (Bebas Neue)
- Títulos grandes: clamp(2.8rem, 5vw, 4.5rem)
- Hero: clamp(5rem, 10vw, 9rem)
- Mayúsculas, letras espaciadas

### Body (DM Sans)
- Texto: 0.95rem - 1rem
- Labels: 0.78rem - 0.88rem
- Weights: 300, 400, 500, 700

---

## 🔄 Transiciones Clave

```css
/* Transición estándar */
--trans: 0.22s ease;

/* Aplicada en */
- Botones (transform, box-shadow)
- Cards (transform, box-shadow)
- Imágenes (transform)
- Links (color, border-color)
- Inputs (border-color, box-shadow)
```

---

## ✨ Efectos Especiales

### Ticker Animado
- 22 segundos duración
- Loop infinito
- Desplazamiento horizontal

### Reveal Button
- Botón oculto (-50px bottom)
- Transición al 0px on hover
- Fondo negro, texto blanco

### Scale on Hover
- Imágenes: 1.04x
- Suave y profesional
- Aplicado en todos los cards

### Lift Effect
- translateY(-4px)
- Box-shadow aumenta
- Cards y productos

---

## 📱 Responsive Design

### Flexbox Responsive
```css
flex: 1 1 260px;  /* Min 260px, crece según espacio */
flex-wrap: wrap;   /* Se ajusta en pantallas pequeñas */
gap: 1.5rem;       /* Espaciado flexible */
```

### Clamp() para Tipografía
```css
font-size: clamp(2.8rem, 5vw, 4.5rem);
/* Min: 2.8rem, Ideal: 5vw, Max: 4.5rem */
```

---

## 🚀 Optimizaciones

✅ **CSS Minimalista**
- 687 líneas totales
- Sin código redundante
- Variables reutilizables

✅ **Performance**
- Transiciones suaves (0.22s)
- Transforms en lugar de cambiar layout
- Box-shadows sutiles

✅ **Accesibilidad**
- Contraste suficiente
- Focus states en inputs
- Textos legibles

---

## 📋 Checklist de Calidad

- ✅ Variables CSS implementadas
- ✅ Flexbox en header y footer
- ✅ Grid asimétrico en lookbook
- ✅ Animaciones CSS3
- ✅ Hover effects en cards
- ✅ Responsive con clamp()
- ✅ Paleta coherente
- ✅ Transiciones suaves
- ✅ Focus states
- ✅ Estructura ordenada
