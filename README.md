# 🛒 G5 Jerseys MX - Landing Page de Ventas

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge&logo=vercel&logoColor=white" alt="Status">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

<p align="center">
  🌐 <strong>Sitio en vivo:</strong> https://oscaromargp.github.io/G5JerseysMX/<br>
  📂 <strong>Repositorio:</strong> https://github.com/oscaromargp/G5JerseysMX
</p>

---

> 🎯 **Landing page de alta conversión** para la venta de jerseys México 2026 Versión Jugador (Calidad G5). Diseñada con técnicas de copywriting profesional, social proof y CTAs directos a WhatsApp.

---

## 📋 Tabla de Contenidos

1. [Descripción del Proyecto](#-descripción-del-proyecto)
2. [Propuesta de Valor](#-propuesta-de-valor)
3. [Producto](#-producto)
4. [Tecnologías Utilizadas](#-tecnologías-utilizadas)
5. [Estructura del Proyecto](#-estructura-del-proyecto)
6. [Secciones del Sitio](#-secciones-del-sitio)
7. [Características y Funcionalidades](#-características-y-funcionalidades)
8. [Enlaces y Recursos](#-enlaces-y-recursos)
9. [Prompts Utilizados](#-prompts-utilizados)
10. [Logs de Cambios](#-logs-de-cambios)
11. [Guía de Configuración](#-guía-de-configuración)
12. [Guía de Deployment](#-guía-de-deployment)
13. [SEO y Metadatos](#-seo-y-metadatos)
14. [Personalización](#-personalización)
15. [Roadmap](#-roadmap)
16. [Créditos y Contacto](#-créditos-y-contacto)

---

## 📝 Descripción del Proyecto

**G5 Jerseys MX** es una landing page premium diseñada para convertir visitantes en compradores. El sitio web está optimizado para:

- 🎯 **Conversión directa** a WhatsApp
- 📱 **Mobile First** (90% del tráfico viene de Facebook/Instagram)
- ⚡ **Alta velocidad** de carga
- 🎨 **Diseño Dark Luxury** con acentos Verde México
- 🔄 **Scroll suave** y animaciones profesionales

### Objetivo Principal
Convertir tráfico de redes sociales (Facebook/Instagram) en ventas a través de WhatsApp, sin necesidad de un carrito de compras o pasarela de pago integrada.

---

## 💡 Propuesta de Valor

| Aspecto | Descripción |
|---------|-------------|
| **¿Qué vendemos?** | Jerseys México 2026 Versión Jugador (Calidad G5) |
| **¿Para quién?** | Aficionados al fútbol, equipos amateurs, revendedores |
| **¿Por qué nosotros?** | Calidad profesional a precio justo, envíos a todo México |
| **Diferenciador** | Versión Jugador (G5) = misma calidad que usan los profesionales |
| **Color principal** | Verde Selección Mexicana (#22C55E) |

---

## 👕 Producto

### Jersey México 2026 Versión Jugador

**Especificaciones del producto:**
- **Marca:** adidas
- **Modelo:** JL8537 - México 2026 Home Stadium Jersey
- **Tecnología:** Climacool (ventilación avanzada)
- **Material:** 100% Poliéster reciclado
- **Tipo:** Versión Jugador (G5) - Máxima calidad disponible
- **Características:**
  - Logos Termosellados (no bordados)
  - Corte Atlético Ajustado
  - Holograma de autenticidad
  - Etiqueta oficial con código verificable
- **Tallas disponibles:** S, M, L, XL, XXL, 3XL
- **Color:** Bold Green (Verde selección mexicana)

### Kits Disponibles

| Kit | Contenido | Precio | Envío |
|-----|-----------|--------|-------|
| **Aficionado** | 1 Jersey | $299 MXN | +$150 estándar |
| **Equipo** ⭐ | 12 Jerseys | $2,499 MXN | GRATIS |
| **Mayorista** | 50+ Jerseys | Cotizar | Según volumen |

---

## 🛠️ Tecnologías Utilizadas

### Stack Principal

| Tecnología | Versión | Propósito | CDN/Documentación |
|-----------|---------|-----------|-------------------|
| **HTML5** | - | Estructura semántica del documento | [MDN Docs](https://developer.mozilla.org/es/docs/Web/HTML) |
| **Tailwind CSS** | 3.x | Framework CSS utility-first | [Tailwind Docs](https://tailwindcss.com/) |
| **Vanilla JavaScript** | ES6+ | Interactividad sin dependencias | [MDN Docs](https://developer.mozilla.org/es/docs/Web/JavaScript) |
| **Google Fonts** | - | Tipografía web premium | [Fonts](https://fonts.google.com/) |

### Fuentes Tipográficas

| Fuente | Uso | Peso | Documentación |
|--------|-----|------|--------------|
| **Plus Jakarta Sans** | Títulos y headers | 400-800 | [Google Fonts](https://fonts.google.com/specimen/Plus+Jakarta+Sans) |
| **Inter** | Cuerpo de texto | 400-600 | [Google Fonts](https://fonts.google.com/specimen/Inter) |

### Recursos Externos

| Recurso | URL | Uso en el Proyecto |
|---------|-----|-------------------|
| Tailwind CDN | `https://cdn.tailwindcss.com` | Estilos CSS |
| Google Fonts | `https://fonts.googleapis.com` | Tipografía |
| YouTube | `https://www.youtube.com/embed/wKZY-opNjfQ` | Video de manufactura |
| Google Photos | Álbum de fotos del producto | Galería de imágenes |

---

## 📁 Estructura del Proyecto

```
G5JerseysMX/
├── index.html          # Archivo principal (HTML + CSS inline + JavaScript)
├── README.md           # Documentación del proyecto
├── images/            # Directorio para imágenes locales (vacío)
│   └── .gitkeep      # Marcador para mantener el directorio
└── .git/             # Repositorio Git
```

### Arquitectura del Sitio

```
index.html (todo-en-uno)
├── <head>
│   ├── Meta tags (charset, viewport, title, description)
│   ├── Preconnect para Google Fonts
│   ├── Google Fonts (Plus Jakarta Sans + Inter)
│   ├── Tailwind CSS CDN
│   └── CSS Custom (variables, animaciones, componentes)
│
├── <body>
│   ├── Stock Banner (urgencia)
│   ├── Navigation (navbar fijo)
│   ├── Hero Section
│   ├── ¿Qué es G5? (comparativa)
│   ├── Características
│   ├── Galería
│   ├── Testimonios
│   ├── Precios (3 kits)
│   ├── Video (YouTube)
│   ├── FAQ (accordion)
│   ├── CTA Final
│   ├── Footer
│   ├── WhatsApp Float Button
│   └── <script> (JavaScript)
```

---

## 📄 Secciones del Sitio

### 1. Stock Banner (Urgencia)
- Banner superior con colores Verde México
- Mensaje: "¡Solo 47 jerseys disponibles esta semana!"
- Promoción: "Envío GRATIS hasta el 31 de marzo"
- Animación de urgencia (pulse)

### 2. Navigation (Navbar)
- Logo "G5 Jerseys MX"
- Links: ¿Qué es G5?, Características, Testimonios, Precios, FAQ
- Botón CTA: "Pedir por WhatsApp"
- Efecto sticky con blur al scroll
- Menú móvil hamburger

### 3. Hero Section
- Badge: "Edición Mundial 2026 - México"
- Headline: "El Jersey que los Profesionales Usan, Ahora a Tu Alcance"
- Subtítulo con propuesta de valor
- Trust badges: Envío a 32 estados, Pago seguro, Stock limitado
- CTAs: WhatsApp + Conocer más
- Imagen del jersey con animación flotante
- Partículas de fondo

### 4. ¿Qué es G5? (Comparativa)
- Título: "G5 = La Calidad Profesional"
- Descripción del diferenciador
- **Card G5 (Verde):** 6 beneficios de la versión jugador
- **Card Réplica (Rojo):** 6 desventajas de réplicas económicas
- Grid de 4 features: 100% Original, Climacool, Logos Termosellados, Corte Atlético

### 5. Características (Features)
- Título: "Detalles que Marcan la Diferencia"
- Grid de 6 cards con hover:
  1. Logos Termosellados
  2. Tecnología Climacool
  3. Corte Atlético Ajustado
  4. Tela Premium 100% Poliéster
  5. 100% Auténtico
  6. Envío a Todo México

### 6. Galería
- Grid responsive de fotos reales
- Primera imagen destacada (2x2)
- Hover zoom en todas las imágenes
- Overlay con descripción

### 7. Testimonios
- Título: "Lo que Dicen Nuestros Clientes"
- 6 testimonios con:
  - Avatar con iniciales
  - Nombre y ubicación
  - Rating 5 estrellas
  - Quote específico
  - Tiempo desde compra
- Trust stats: 500+ vendidos, 32 estados, 98% satisfechos, 4.9/5

### 8. Precios (Pricing)
- Título: "Elige Tu Kit Perfecto"
- 3 cards:
  - **Kit Aficionado** ($299): 1 jersey + envío
  - **Kit Equipo** ($2,499): 12 jerseys + GRATIS (MÁS VENDIDO)
  - **Lote Mayorista** (Cotizar): 50+ piezas
- Proceso de compra en 4 pasos

### 9. Video
- Video de manufactura (YouTube)
- Título: "Cómo Se Fabrica Tu Jersey"
- Iframe responsive 16:9

### 10. FAQ
- Título: "Preguntas Frecuentes"
- 6 preguntas con accordion:
  1. ¿Qué es exactamente "Calidad G5"?
  2. ¿Cuáles son los costos de envío?
  3. ¿Cuánto tarda en llegar?
  4. ¿Se puede pagar con tarjeta?
  5. ¿Es original o réplica?
  6. ¿Qué pasa si no me gusta?

### 11. CTA Final
- Título: "¿Listo para Vestir como un Profesional?"
- Urgencia: "Stock limitado... Envío GRATIS hasta el 31 de marzo"
- Botón principal WhatsApp
- Trust badges finales

### 12. Footer
- Logo y descripción
- Links organizados: Productos, Información, Contacto
- Copyright
- Badge "Hecho con ❤️ en México 🇲🇽"

### 13. WhatsApp Float
- Botón flotante siempre visible
- Posición: bottom-right
- Animación pulse
- Enlace directo a WhatsApp con mensaje predefinido

---

## ✨ Características y Funcionalidades

### Diseño
- [x] Diseño 100% Mobile First
- [x] Dark Mode Premium (fondo negro #000000)
- [x] Acentos Verde México (#22C55E)
- [x] Glassmorphism en cards
- [x] Animaciones CSS suaves
- [x] Gradientes radiales
- [x] Efectos glow en elementos importantes

### Interactividad
- [x] Navegación sticky con efecto blur
- [x] Smooth scroll para navegación interna
- [x] Menú móvil responsive (hamburger)
- [x] FAQ accordion interactivo
- [x] Hover effects en cards
- [x] Botón flotante WhatsApp

### Optimización
- [x] Tailwind CSS vía CDN (sin build)
- [x] Google Fonts con preconnect
- [x] Imágenes externas optimizadas
- [x] CSS inline (sin archivo externo)
- [x] JavaScript vanilla (sin dependencias)

### SEO
- [x] Meta tags básicos
- [x] Title optimizado
- [x] Description con keywords
- [x] Viewport para responsive
- [x] Estructura semántica HTML5

---

## 🔗 Enlaces y Recursos

### Enlaces del Proyecto
| Recurso | URL |
|---------|-----|
| 🌐 Sitio en vivo | https://oscaromargp.github.io/G5JerseysMX/ |
| 📂 Repositorio GitHub | https://github.com/oscaromargp/G5JerseysMX |
| 📝 Issues | https://github.com/oscaromargp/G5JerseysMX/issues |

### Enlaces del Producto (Referencia)
| Recurso | URL |
|---------|-----|
| Producto original | https://mexicofanshop.com/es/collections/world-cup/products/adidas-2026-mexico-home-jersey |
| Adidas México | https://www.adidas.mx/jersey-local-seleccion-nacional-de-mexico-26/JL8537.html |

### Enlaces de Marketing
| Recurso | URL |
|---------|-----|
| Video promo 1 | https://photos.app.goo.gl/w9mP2ZYYYWMMuHoN9 |
| Video promo 2 | https://photos.app.goo.gl/JXw6stbj5sNmjieW9 |
| Álbum de fotos | https://photos.app.goo.gl/ZZz4Gdj4MNn6PjNY7 |
| Google Form (cotizaciones) | https://forms.gle/rmrtYFEMU9dbNXkKA |
| Video manufactura | https://www.youtube.com/watch?v=wKZY-opNjfQ |

### Contacto del Negocio
| Medio | Contacto |
|-------|----------|
| 📱 WhatsApp | +52 1 612 107 8078 |
| 📧 Email | (Incluir si aplica) |
| 📍 Ubicación | México |

---

## 📝 Prompts Utilizados

### Prompt Principal (Creación Original)

```markdown
# 🚀 PROMPT UNIVERSAL: Landing Page Premium Dark Mode

## 📋 INSTRUCCIONES PARA LA IA

### ❓ PREGUNTA 1: Información del Negocio
- **Nombre del negocio/marca:** G5 Jerseys MX
- **Tagline:** Jersey México 2026 Versión Jugador - Calidad Premium
- **Propuesta de valor:** Venta de jerseys adidas México 2026 Versión Jugador 
  (Calidad G5) con tecnología Climacool, logos termosellados y envío a todo México.

### ❓ PREGUNTA 2: Sector y Estilo
- **Sector/Industria:** E-commerce / Venta de artículos deportivos
- **Tipo de web:** E-commerce (Tienda en línea simple)

### ❓ PREGUNTA 3: Color Principal
- **Color de acento principal:** Verde (#22C55E) - Verde selección mexicana

## Producto de Referencia
La playera que se vende es este modelo:
https://mexicofanshop.com/es/collections/world-cup/products/adidas-2026-mexico-home-jersey

## Links Proporcionados
- Video promo 1: https://photos.app.goo.gl/w9mP2ZYYYWMMuHoN9
- Video promo 2: https://photos.app.goo.gl/JXw6stbj5sNmjieW9
- Álbum de fotos: https://photos.app.goo.gl/ZZz4Gdj4MNn6PjNY7
- Google Form: https://forms.gle/rmrtYFEMU9dbNXkKA
- Video manufactura: https://www.youtube.com/watch?v=wKZY-opNjfQ

## Número de WhatsApp
+52 1 612 107 8078 (no mostrar número, solo botones)
```

### Análisis Post-Lanzamiento

```markdown
Análisis completo del sitio actual:
- NO hay testimonios
- NO hay FAQ
- NO explica qué es "G5"
- Proceso de COMPRA incompleto
- Sin navegación interna, sin trust badges, sin urgencia

Objetivo: convertirlo en una landing page de ventas de alta conversión 
(técnica AIDA + social proof + objeciones resueltas).

Secciones nuevas obligatorias:
1. "¿Qué es la Calidad G5?" - Comparativa G5 vs Réplica
2. Testimonios (6 testimonios reales)
3. FAQ (accordion con preguntas frecuentes)

Mejoras de diseño:
- Navegación fija con smooth scroll
- Hero más potente
- Trust badges
- Contador de stock
- Urgencia ("Envío gratis hasta...")
- Mobile-first 100%
```

---

## 📊 Logs de Cambios

### [v3.0.0] - 2026-03-20
**Optimización Final para Conversión**

- ✅ Reescritura completa con Tailwind CSS
- ✅ Nueva sección "¿Qué es G5?" con comparativa visual
- ✅ 6 testimonios detallados con ubicaciones reales
- ✅ FAQ completo con 6 preguntas frecuentes
- ✅ Banner de stock/urgencia
- ✅ Trust badges mejorados en Hero
- ✅ Proceso de compra en 4 pasos
- ✅ Navegación fija con smooth scroll
- ✅ Mobile menu funcional
- ✅ Botón flotante WhatsApp
- ✅ Animaciones optimizadas

**Archivos modificados:** `index.html`

---

### [v2.0.0] - 2026-03-20
**Landing Page Completa**

- ✅ Hero section impactante
- ✅ Sección de características
- ✅ Galería de fotos reales
- ✅ 3 planes de precios
- ✅ Video de manufactura
- ✅ CTA con WhatsApp
- ✅ Footer básico

**Archivos añadidos:** `index.html`

---

### [v1.0.0] - 2026-03-20
**Versión Inicial**

- ✅ Repositorio creado
- ✅ README básico

**Archivos añadidos:** `README.md`

---

## ⚙️ Guía de Configuración

### Requisitos Previos

Para trabajar con este proyecto necesitas:

1. **Un navegador web moderno** (Chrome, Firefox, Edge, Safari)
2. **Git** (para control de versiones)
3. **Editor de código** (VS Code recomendado)
4. **Cuenta de GitHub** (para hosting)

### Clonar el Repositorio

```bash
# Clonar el repositorio
git clone https://github.com/oscaromargp/G5JerseysMX.git

# Entrar al directorio
cd G5JerseysMX

# Abrir en VS Code (opcional)
code .
```

### Desarrollo Local

1. Abre `index.html` directamente en tu navegador
2. O usa una extensión de VS Code como "Live Server"
3. Edita el archivo y guarda para ver cambios

### Variables Editables

#### Número de WhatsApp
```javascript
// Buscar y reemplazar en todo el archivo
// Número actual: 5216121078078
// Formato: 52 + número sin + al inicio
```

#### Precios
```html
<!-- Buscar en sección de Precios -->
<span class="text-5xl font-extrabold text-white">$299</span>
```

#### Stock
```html
<!-- Banner de stock -->
<span id="stock-count" class="font-bold text-yellow-300">¡Solo 47 jerseys disponibles esta semana!</span>
```

#### Promociones
```html
<!-- Fecha de promoción -->
<span class="text-green-200">Envío GRATIS hasta el 31 de marzo</span>
```

---

## 🚀 Guía de Deployment

### Opción 1: GitHub Pages (Gratuito) ⭐

1. Ve a **Settings** del repositorio en GitHub
2. En el menú lateral, click en **Pages**
3. En **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main** / **/ (root)**
4. Click **Save**
5. Espera 2-5 minutos
6. Tu sitio estará en: `https://TU_USUARIO.github.io/G5JerseysMX/`

### Opción 2: Vercel

```bash
# Instalar Vercel CLI
npm i -g vercel

# Deploy
vercel

# Deploy a producción
vercel --prod
```

### Opción 3: Netlify

1. Ve a [netlify.com](https://netlify.com)
2. Arrastra la carpeta del proyecto
3. ¡Listo! Obtén una URL gratuita

### Opción 4: Hosting Tradicional

1. Sube `index.html` por FTP
2. Asegúrate de que el archivo se llame `index.html`
3. Configura tu dominio

---

## 🔍 SEO y Metadatos

### Meta Tags Actuales

```html
<title>G5 Jerseys MX | Jersey México 2026 Versión Jugador - Calidad Premium</title>
<meta name="description" content="Jersey México 2026 Versión Jugador con tecnología Climacool. Calidad G5 = La misma que usan los profesionales. Envíos a todo México.">
```

### Meta Tags Open Graph (Recomendado añadir)

```html
<meta property="og:title" content="G5 Jerseys MX - Jersey México 2026">
<meta property="og:description" content="Jersey México 2026 Versión Jugador. Calidad G5 = La misma que usan los profesionales.">
<meta property="og:image" content="URL_DE_IMAGEN">
<meta property="og:url" content="https://oscaromargp.github.io/G5JerseysMX/">
<meta property="og:type" content="website">
```

### Meta Tags para Redes Sociales

```html
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="G5 Jerseys MX">
<meta name="twitter:description" content="Jersey México 2026 Versión Jugador">
<meta name="twitter:image" content="URL_DE_IMAGEN">
```

---

## 🎨 Personalización

### Cambiar Color Principal

El color principal es Verde México (`#22C55E`). Para cambiarlo:

1. Busca `22C55E` y reemplázalo por tu color HEX
2. Ajusta los colores derivados (más claro/más oscuro)
3. Actualiza los valores RGB para rgba()

```css
/* Color base */
--green-500: #TU_COLOR_NUEVO;

/* Versiones claras */
--green-400: #COLOR_MAS_CLARO;
--green-300: #COLOR_AUN_MAS_CLARO;

/* Versiones oscuras */
--green-600: #COLOR_MAS_OSCURO;
--green-700: #COLOR_AUN_MAS_OSCURO;

/* RGB para rgba() */
--primary-rgb: R, G, B; /* Valores de 0-255 */
```

### Agregar Más Testimonios

Copia el formato de un testimonial card y modifica:

```html
<div class="testimonial-card glass-card p-6">
    <div class="flex items-center gap-4 mb-4">
        <div class="w-14 h-14 rounded-full bg-gradient-to-br from-green-500 to-green-600 flex items-center justify-center text-xl font-bold text-black">AB</div>
        <div>
            <h4 class="font-bold">Nombre Apellido</h4>
            <p class="text-gray-400 text-sm">Ciudad • Tipo de compra</p>
        </div>
    </div>
    <div class="flex gap-1 mb-3">
        <span class="text-yellow-400">★★★★★</span>
    </div>
    <p class="text-gray-300 mb-4">"Tu testimonial aquí..."</p>
    <div class="flex items-center gap-2 text-green-400 text-sm">
        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
        Tiempo desde compra
    </div>
</div>
```

### Agregar Más Preguntas FAQ

Copia el formato y modifica:

```html
<div class="faq-item glass-card overflow-hidden">
    <button class="faq-question w-full flex items-center justify-between p-6 text-left" onclick="toggleFaq(this)">
        <span class="font-bold text-lg">Tu pregunta aquí</span>
        <svg class="faq-icon w-6 h-6 text-green-500 flex-shrink-0" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path></svg>
    </button>
    <div class="faq-answer px-6 pb-6">
        <p class="text-gray-400">Tu respuesta aquí...</p>
    </div>
</div>
```

---

## 🗺️ Roadmap

### Fase 1: Completo ✅
- [x] Landing page básica
- [x] WhatsApp integration
- [x] SEO básico
- [x] Mobile responsive

### Fase 2: En Progreso 🚧
- [x] Testimonios
- [x] FAQ
- [x] Explicación G5
- [ ] Open Graph tags
- [ ] Analytics

### Fase 3: Pendiente 📋
- [ ] Google Analytics / Plausible
- [ ] Sitemap.xml
- [ ] Robots.txt
- [ ] Favicon.svg
- [ ] Optimizar imágenes (WebP)

### Fase 4: Futuras Mejoras 🚀
- [ ] Integración Mercado Pago
- [ ] Carrito de compras
- [ ] Panel de administración
- [ ] Multi-idioma (EN/ES)
- [ ] PWA (Progressive Web App)
- [ ] Chatbot de WhatsApp

---

## 👨‍💻 Créditos y Contacto

### Desarrollador
| Campo | Información |
|-------|-------------|
| **Nombre** | Oscar Omar Gómez Peña |
| **Título** | Emprendedor Tecnológico Digital |
| **Email** | oscaromargp@gmail.com |
| **Teléfono** | 612-107-8075 |
| **Web** | [bit.ly/oscaromargp](https://bit.ly/oscaromargp) |

### Herramientas Utilizadas
- **Framework CSS:** [Tailwind CSS](https://tailwindcss.com/)
- **Tipografía:** [Google Fonts](https://fonts.google.com/)
- **Hosting:** [GitHub Pages](https://pages.github.com/)
- **IDE:** [VS Code](https://code.visualstudio.com/)

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.

Puedes usar, modificar y distribuir este código libremente, dando crédito al desarrollador original.

---

<p align="center">
  <strong>G5 Jerseys MX</strong> © 2026<br>
  🌐 https://oscaromargp.github.io/G5JerseysMX/<br>
  📱 WhatsApp: +52 1 612 107 8078<br>
  🇲🇽 Hecho con ❤️ en México
</p>
