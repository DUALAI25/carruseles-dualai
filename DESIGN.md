# DualAI — Brand Design Guide

> Documento de referencia de identidad visual extraído de [dualai.app](https://dualai.app)  
> Última revisión: Mayo 2026

---

## 1. Identidad de Marca

| Campo | Valor |
|---|---|
| **Nombre** | DualAI |
| **Tagline principal** | Automatización Inteligente para Negocios |
| **Subtítulo OG** | Automatiza los procesos clave de tu negocio con IA |
| **Dominio** | dualai.app / dualai.es |
| **Idioma** | Español (es_ES) |
| **Público objetivo** | Negocios y empresas (B2B) |

---

## 2. Paleta de Colores

### Colores principales

| Nombre | Hex | Uso |
|---|---|---|
| **Deep Navy** | `#070d1a` | Fondo base (`theme-color`), fondos de sección |
| **Cyan / Electric Blue** | `#00d4ff` | Acento principal, CTAs, highlights, bordes activos |
| **Purple / Violet** | `#7b2ff7` | Acento secundario, gradientes, elementos decorativos |
| **Dark Surface** | `#0d1526` | Fondos de tarjetas y paneles |
| **Dark Elevated** | `#111d35` | Superficies elevadas, navbars, modales |

### Colores de texto

| Nombre | Hex | Uso |
|---|---|---|
| **White** | `#ffffff` | Texto principal en fondos oscuros |
| **Light Gray** | `#b0b8cc` | Texto secundario, subtítulos, descripciones |
| **Muted** | `#6b7a99` | Texto placeholder, metadatos, footers |

### Gradientes característicos

```css
/* Gradiente principal de marca */
background: linear-gradient(135deg, #7b2ff7 0%, #00d4ff 100%);

/* Gradiente de fondo oscuro */
background: linear-gradient(180deg, #070d1a 0%, #0d1526 100%);

/* Glow de acento cyan (para sombras/efectos) */
box-shadow: 0 0 40px rgba(0, 212, 255, 0.15);

/* Glow de acento purple */
box-shadow: 0 0 40px rgba(123, 47, 247, 0.2);
```

---

## 3. Tipografía

> ⚠️ **Nota**: La tipografía exacta requiere inspección directa del CSS. Las siguientes referencias se basan en el estilo visual futurista/tech detectado. Verificar en DevTools → Computed → font-family.

### Jerarquía tipográfica estimada

| Rol | Familia | Peso | Uso |
|---|---|---|---|
| **Display / H1** | `Sora` o `Space Grotesk` | 700–800 | Títulos hero grandes |
| **Headings H2–H3** | misma familia display | 600–700 | Secciones, tarjetas |
| **Body** | `Inter` o `DM Sans` | 400–500 | Párrafos, descripciones |
| **Code / Tech** | `JetBrains Mono` | 400 | Elementos técnicos |
| **Botones / Labels** | display font | 600 | CTAs, badges |

> 📌 Para confirmar las fuentes exactas: abre Chrome DevTools en dualai.app → Pestaña **Elements** → selecciona un h1 → en **Computed** busca `font-family`.

---

## 4. Logo

### Descripción
- **Formato**: JPEG embebido (imagen)
- **Nombre de archivo en HTML**: inline base64
- **Uso**: aparece en la barra de navegación (navbar)
- **Estilo visual**: Logotipo con nombre "DualAI" en tipografía moderna, presumiblemente acompañado de un símbolo/icono

### Variantes recomendadas
- `logo-light.svg` — versión blanca/cyan para fondos oscuros (uso primario)
- `logo-dark.svg` — versión oscura para fondos claros (uso secundario, si aplica)
- `logo-icon.svg` — solo el símbolo, para favicon/app icon

### Favicon / App Icon
- Theme color: `#070d1a`
- `apple-mobile-web-app-capable: yes`
- `apple-mobile-web-app-status-bar-style: black-translucent`

---

## 5. Estilo Visual

### Concepto general
**Dark Futuristic / Tech Noir** — Interfaz oscura de alto contraste con acentos neón (cyan y púrpura). Evoca tecnología avanzada, confianza y modernidad. Estética inspirada en interfaces de IA y software enterprise premium.

### Elementos visuales característicos

- **Fondos**: Negro azulado profundo (`#070d1a`) con capas de superficies ligeramente más claras
- **Efectos de luz**: Glows suaves en cyan y purple sobre elementos interactivos
- **Tarjetas**: Bordes sutiles con `1px solid rgba(0, 212, 255, 0.15)`, fondo semi-transparente
- **Gradientes**: Uso de gradientes diagonal cyan→purple en textos y elementos hero
- **Animaciones**: Entrada suave de elementos (fade + slide), posiblemente partículas/grid animado de fondo
- **Iconografía**: Línea fina, estilo outline, en color cyan o blanco

### CSS Variables base (estimadas)

```css
:root {
  --color-bg:          #070d1a;
  --color-surface:     #0d1526;
  --color-elevated:    #111d35;
  --color-accent:      #00d4ff;
  --color-accent-alt:  #7b2ff7;
  --color-text:        #ffffff;
  --color-text-muted:  #b0b8cc;
  --color-border:      rgba(0, 212, 255, 0.15);
  --radius-card:       12px;
  --radius-button:     8px;
}
```

---

## 6. Mensajes de Marca

### Taglines y frases clave

| Tipo | Texto |
|---|---|
| **Título principal** | "Automatización Inteligente para Negocios" |
| **OG Description** | "Automatiza los procesos clave de tu negocio con IA. Atención al cliente 24/7, asistentes de WhatsApp y llamadas, gestión interna y más." |
| **Meta description** | "DualAI automatiza los procesos clave de tu negocio con inteligencia artificial. Atención al cliente 24/7, gestión de citas, facturación y más." |

### Servicios mencionados

- Atención al cliente 24/7
- Asistentes de WhatsApp
- Asistentes de llamadas (voice AI)
- Gestión de citas
- Facturación automatizada
- Gestión interna de negocios

### Tono de voz
- **Directo y orientado a resultados**
- **Técnico pero accesible** (para empresarios no técnicos)
- **Confianza y autoridad** en IA y automatización
- Sin tecnicismos innecesarios, foco en el beneficio empresarial

---

## 7. Componentes UI

### Botones

```css
/* Botón primario */
.btn-primary {
  background: linear-gradient(135deg, #7b2ff7, #00d4ff);
  color: #ffffff;
  font-weight: 600;
  border-radius: 8px;
  padding: 12px 28px;
  border: none;
  box-shadow: 0 0 20px rgba(0, 212, 255, 0.3);
}

/* Botón secundario / outline */
.btn-outline {
  background: transparent;
  color: #00d4ff;
  border: 1px solid #00d4ff;
  border-radius: 8px;
  padding: 12px 28px;
}
```

### Tarjetas de servicio

```css
.card {
  background: #0d1526;
  border: 1px solid rgba(0, 212, 255, 0.15);
  border-radius: 12px;
  padding: 32px;
  transition: border-color 0.3s, box-shadow 0.3s;
}

.card:hover {
  border-color: rgba(0, 212, 255, 0.4);
  box-shadow: 0 8px 40px rgba(0, 212, 255, 0.1);
}
```

---

## 8. Metadatos Técnicos

```html
<meta name="theme-color" content="#070d1a">
<meta name="og:locale" content="es_ES">
<meta name="og:type" content="website">
<meta name="og:url" content="https://dualai.es">
<meta name="twitter:card" content="summary_large_image">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="mobile-web-app-capable" content="yes">
```

---

## 9. Notas y Pendientes

> Los siguientes elementos requieren verificación manual abriendo DevTools en Chrome sobre dualai.app:

- [ ] **Tipografía exacta**: inspeccionar `font-family` en computed styles de h1, p, botones
- [ ] **Escala tipográfica**: tamaños exactos en rem/px para h1, h2, h3, body, small
- [ ] **Logo vectorial**: exportar SVG desde el inspector (si existe) o solicitar al diseñador
- [ ] **Espaciado y grid**: confirmar sistema de espaciado (8px base o 4px)
- [ ] **Breakpoints responsive**: inspeccionar @media queries del CSS

---

*DESIGN.md generado con análisis de dualai.app — DualAI, Almería 🇪🇸*
