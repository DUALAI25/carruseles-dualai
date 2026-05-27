# DualAI — Brand Design Guide & Product Overview

> Documento integral de identidad visual, producto y estrategia de marca de DualAI
> Información extraída de [dualai.app](https://dualai.app)  
> Última revisión: Mayo 2026

---

## 1. Resumen Ejecutivo

**DualAI** es una plataforma de **automatización inteligente para negocios** que utiliza inteligencia artificial para optimizar y automatizar procesos empresariales complejos. La plataforma permite que empresas de todos los tamaños implementen soluciones basadas en IA sin requerir conocimientos técnicos profundos.

### Propuesta de Valor Principal
- ⚡ **Automatización eficiente**: Elimina tareas repetitivas mediante IA
- 🤖 **Soluciones empresariales**: Diseñadas específicamente para problemas B2B
- 📈 **Optimización operativa**: Mejora la eficiencia y reduce costos
- 🔄 **Plataforma integrada**: Todo en un único ecosistema

---

## 2. Identidad de Marca

| Campo | Valor |
|---|---|
| **Nombre** | DualAI |
| **Tagline principal** | Automatización Inteligente para Negocios |
| **Subtítulo OG** | Automatiza los procesos clave de tu negocio con IA |
| **Descripción completa** | Automatiza los procesos clave de tu negocio con inteligencia artificial. Atención al cliente 24/7, asistentes de WhatsApp y llamadas, gestión interna y más. |
| **Dominio primario** | dualai.app |
| **Dominio secundario** | dualai.es |
| **Idioma** | Español (es_ES) |
| **Público objetivo** | Negocios y empresas (B2B) |

---

## 3. Servicios y Soluciones Principales

### Servicios Identificados

| Servicio | Descripción | Caso de Uso |
|---|---|---|
| **Atención al Cliente 24/7** | Sistemas de atención automatizada con IA | Respuestas inmediatas sin intervención humana |
| **Asistentes de WhatsApp** | Bots inteligentes para WhatsApp Business | Interacción directa con clientes en su canal preferido |
| **Asistentes de Llamadas (Voice AI)** | Sistema de voz AI para llamadas entrantes/salientes | Gestión automatizada de llamadas telefónicas |
| **Gestión de Citas** | Automatización de reservas y programación | Eliminación de fricción en reservas de servicios |
| **Facturación Automatizada** | Generación y envío automático de facturas | Reducción de carga administrativa |
| **Gestión Interna de Negocios** | Automatización de procesos internos | Streamlining de operaciones internas |

---

## 4. Público Objetivo (Target Market)

### Segmento Principal
- **B2B** (Business-to-Business)
- **Empresas medianas a grandes**
- **Decisores de TI y negocio**
- **Sectores**: Servicios, comercio, atención al cliente

### Verticales de Mercado

**Servicios Profesionales**
- Despachos de abogados (citas, consultas)
- Consultoría empresarial
- Agencias de marketing

**Comercio y Retail**
- E-commerce (consultas de clientes)
- Tiendas físicas con servicio técnico
- Mayoristas B2B

**Salud y Bienestar**
- Clínicas y consultorios (reservas)
- Spas y centros de bienestar
- Farmacias (información de medicamentos)

**Finanzas y Seguros**
- Gestión de consultas de clientes
- Procesamiento de solicitudes automático
- Facturación y cobranza

---

## 5. Paleta de Colores

### Colores Principales

| Nombre | Hex | Uso |
|---|---|---|
| **Deep Navy** | `#070d1a` | Fondo base (`theme-color`), fondos de sección |
| **Cyan / Electric Blue** | `#00d4ff` | Acento principal, CTAs, highlights, bordes activos |
| **Purple / Violet** | `#7b2ff7` | Acento secundario, gradientes, elementos decorativos |
| **Dark Surface** | `#0d1526` | Fondos de tarjetas y paneles |
| **Dark Elevated** | `#111d35` | Superficies elevadas, navbars, modales |

### Colores de Texto

| Nombre | Hex | Uso |
|---|---|---|
| **White** | `#ffffff` | Texto principal en fondos oscuros |
| **Light Gray** | `#b0b8cc` | Texto secundario, subtítulos, descripciones |
| **Muted** | `#6b7a99` | Texto placeholder, metadatos, footers |

### Gradientes Característicos

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

### Estrategia Cromática
- 🎨 **Deep Navy** → Confianza, tecnología, profesionalismo
- 🎨 **Cyan/Electric Blue** → Energía, innovación, actividad
- 🎨 **Purple/Violet** → Creatividad, tecnología avanzada

---

## 6. Tipografía

> ⚠️ **Nota**: La tipografía exacta requiere inspección directa del CSS. Las siguientes referencias se basan en el estilo visual futurista/tech detectado.

### Jerarquía Tipográfica

| Rol | Familia | Peso | Uso |
|---|---|---|---|
| **Display / H1** | `Sora` o `Space Grotesk` | 700–800 | Títulos hero grandes |
| **Headings H2–H3** | misma familia display | 600–700 | Secciones, tarjetas |
| **Body** | `Inter` o `DM Sans` | 400–500 | Párrafos, descripciones |
| **Code / Tech** | `JetBrains Mono` | 400 | Elementos técnicos |
| **Botones / Labels** | display font | 600 | CTAs, badges |

> 📌 Para confirmar las fuentes exactas: abre Chrome DevTools en dualai.app → Pestaña **Elements** → selecciona un h1 → en **Computed** busca `font-family`.

---

## 7. Logo

### Descripción
- **Formato**: JPEG embebido (imagen)
- **Nombre de archivo en HTML**: inline base64
- **Uso**: aparece en la barra de navegación (navbar)
- **Estilo visual**: Logotipo con nombre "DualAI" en tipografía moderna, presumiblemente acompañado de un símbolo/icono

### Variantes Recomendadas
- `logo-light.svg` — versión blanca/cyan para fondos oscuros (uso primario)
- `logo-dark.svg` — versión oscura para fondos claros (uso secundario, si aplica)
- `logo-icon.svg` — solo el símbolo, para favicon/app icon

### Favicon / App Icon
- Theme color: `#070d1a`
- `apple-mobile-web-app-capable: yes`
- `apple-mobile-web-app-status-bar-style: black-translucent`

---

## 8. Estilo Visual General

### Concepto General
**Dark Futuristic / Tech Noir** — Interfaz oscura de alto contraste con acentos neón (cyan y púrpura). Evoca tecnología avanzada, confianza y modernidad. Estética inspirada en interfaces de IA y software enterprise premium.

### Elementos Visuales Característicos

- **Fondos**: Negro azulado profundo (`#070d1a`) con capas de superficies ligeramente más claras
- **Efectos de luz**: Glows suaves en cyan y purple sobre elementos interactivos
- **Tarjetas**: Bordes sutiles con `1px solid rgba(0, 212, 255, 0.15)`, fondo semi-transparente
- **Gradientes**: Uso de gradientes diagonal cyan→purple en textos y elementos hero
- **Animaciones**: Entrada suave de elementos (fade + slide), posiblemente partículas/grid animado de fondo
- **Iconografía**: Línea fina, estilo outline, en color cyan o blanco

### CSS Variables Base (Estimadas)

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

## 9. Componentes UI

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

### Tarjetas de Servicio

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

## 10. Tono de Voz y Mensajería

### Características del Tono
- ✅ **Directo y orientado a resultados** — Va al grano, enfocado en ROI
- ✅ **Técnico pero accesible** — Explica IA sin jerga innecesaria
- ✅ **Confianza y autoridad** — Posicionamiento como experto en IA/automatización
- ✅ **Beneficio empresarial primero** — "¿Cómo te ayuda?" antes que "¿Cómo funciona?"
- ✅ **Sin tecnicismos innecesarios** — Foco en el beneficio empresarial

### Ejemplos de Mensajería

| Tipo | Mensaje |
|---|---|
| **Valor** | "Ahorra horas de trabajo manual cada semana" |
| **Diferenciación** | "IA diseñada para tu negocio, no para programadores" |
| **Urgencia** | "Tu competencia ya la está usando" |
| **Confianza** | "Empresas líderes confían en DualAI" |

### Taglines y Frases Clave

| Tipo | Texto |
|---|---|
| **Título principal** | "Automatización Inteligente para Negocios" |
| **OG Description** | "Automatiza los procesos clave de tu negocio con IA. Atención al cliente 24/7, asistentes de WhatsApp y llamadas, gestión interna y más." |
| **Meta description** | "DualAI automatiza los procesos clave de tu negocio con inteligencia artificial. Atención al cliente 24/7, gestión de citas, facturación y más." |

---

## 11. Propuesta de Valor Detallada

### Beneficios Clave para el Cliente

**1. Eficiencia Operativa**
- Automatiza tareas repetitivas
- Reduce carga de trabajo del equipo
- Aumenta productividad sin contratar más personal

**2. Disponibilidad 24/7**
- Atención al cliente sin parar
- Respuestas inmediatas a consultas
- Servicio continuo sin costos de nómina adicionales

**3. Experiencia del Cliente Mejorada**
- Respuestas rápidas en canales preferidos (WhatsApp, llamadas)
- Menos esperas y frustración
- Interacción más natural con IA moderna

**4. Reducción de Costos**
- Menos necesidad de personal administrativo
- Automático vs. manual = ahorro significativo
- ROI cuantificable

**5. Escalabilidad**
- Crece con tu negocio
- No necesita reentrenamiento constante
- Integración simple con sistemas existentes

### Ventajas Competitivas

| Ventaja | Descripción |
|---|---|
| **Interfaz Intuitiva** | Sin requerimientos técnicos |
| **Multi-canal** | WhatsApp, teléfono, chat, integraciones |
| **Especialización B2B** | Diseñada para empresas, no consumidores |
| **Marca Premium** | Posicionamiento tech de alta gama |
| **Soporte en Español** | Optimizado para mercado hispanohablante |

### Posicionamiento Estratégico

**Vs. Software legacy**
- "IA moderna vs. sistemas viejos"
- "Rápido de implementar vs. proyectos de meses"

**Vs. Freelancers/outsourcing**
- "Consistencia garantizada vs. variabilidad humana"
- "Escalabilidad sin costos crecientes"

**Vs. Startups de IA genéricas**
- "Especializado en negocio vs. soluciones generales"
- "Diseñado para empresas reales, no tech bros"

### Mensaje Central
> "La IA que entiende tu negocio y se integra sin complicaciones"

---

## 12. Características Técnicas

### Plataforma
- **Optimización**: Mobile-first (enfoque en dispositivos móviles)
- **Compatibilidad**: Nota en sitio: "Para la experiencia completa, abre en Safari"
- **Responsive**: Diseñada para toda gama de dispositivos

### Meta Tags Técnicos

```html
<meta name="theme-color" content="#070d1a">
<meta property="og:locale" content="es_ES">
<meta property="og:type" content="website">
<meta property="og:url" content="https://dualai.es">
<meta name="twitter:card" content="summary_large_image">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="mobile-web-app-capable" content="yes">
```

---

## 13. Recomendaciones Estratégicas

### Para Copywriting
1. **Evitar**: Jerga técnica innecesaria, promesas vagas sobre IA
2. **Enfatizar**: Casos concretos (ej: "ahorra 10 horas/semana"), ROI, facilidad
3. **Tonalidad**: Confiada pero no arrogante, moderna pero no futurista lejana
4. **Estructura**: Beneficio primero, explicación técnica después

### Para Design
1. Mantener contraste alto (dark mode + neons)
2. Usar gradientes purple→cyan en elementos hero
3. Animaciones sutiles (no overshooting)
4. Tipografía moderna, weights claros (600+ para destacar)
5. Espaciado generoso en mobile
6. Glows y efectos de luz para evocar tecnología avanzada
7. Consistencia en uso de colores neón

### Posibles Áreas de Mejora
- [ ] Más casos de estudio en la página principal
- [ ] Pricing transparente (si no existe)
- [ ] Video demo de 60 segundos
- [ ] Testimonios de clientes B2B
- [ ] Documentación/API docs destacadas
- [ ] Blog de automatización y tendencias

---

## 14. Roadmap Inferido

### Fase Actual (Activo)
✅ Plataforma core de automatización  
✅ Integración WhatsApp y voz  
✅ Atención al cliente 24/7  
✅ Facturación básica  

### Posibles Expansiones Futuras
- 🚀 Análisis predictivo con IA
- 🚀 Dashboards avanzados de analytics
- 🚀 Más integraciones (Slack, Teams, etc.)
- 🚀 Modelos de IA entrenables por cliente
- 🚀 Marketplace de integraciones

---

## 15. Notas y Pendientes

> Los siguientes elementos requieren verificación manual abriendo DevTools en Chrome sobre dualai.app:

- [ ] **Tipografía exacta**: inspeccionar `font-family` en computed styles de h1, p, botones
- [ ] **Escala tipográfica**: tamaños exactos en rem/px para h1, h2, h3, body, small
- [ ] **Logo vectorial**: exportar SVG desde el inspector (si existe) o solicitar al diseñador
- [ ] **Espaciado y grid**: confirmar sistema de espaciado (8px base o 4px)
- [ ] **Breakpoints responsive**: inspeccionar @media queries del CSS
- [ ] **Casos de estudio**: recopilar testimonios y números de clientes
- [ ] **Pricing page**: definir estructura si no existe

---

## 16. Resumen para Stakeholders

### DualAI en 3 Frases
1. **¿Qué es?** Una plataforma de automatización inteligente para empresas
2. **¿Para quién?** Empresas medianas y grandes que necesitan eficiencia operativa
3. **¿Por qué?** Reduce costos, mejora servicio al cliente y escala sin límites

### Valores Clave de Comunicación
- 🎯 **Eficiencia**: Automatiza, ahorra tiempo y dinero
- 🤖 **Inteligencia**: IA moderna y especializada en negocios
- 🔗 **Integración**: Se adapta a tu ecosistema existente
- 📱 **Accesibilidad**: Fácil de usar, sin necesidad técnica
- 🌟 **Premium**: Solución de clase mundial

---

*DESIGN.md generado con análisis integral de dualai.app*  
*Documento unificado de identidad, producto y estrategia*  
*DualAI, Almería 🇪🇸*  
*Última actualización: Mayo 2026*
