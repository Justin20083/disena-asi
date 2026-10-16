# Guía de Diseño «Diseña así» — Análisis de 68 referencias visuales

> **Propósito de este documento:** servir como *briefing de estilo* para IAs (Claude, GPT, Gemini, Cursor, Copilot, etc.) que tengan que **diseñar webs, landings, dashboards, apps, tarjetas, slides o mockups con este estilo**. Cada referencia está descrita detalle a detalle y cada ficha termina con **reglas accionables** («Reglas que enseña»).
>
> **Fuente:** carpeta `~/Documents/Diseños` — 68 capturas (`IMG_8179` a `IMG_8249`; faltan 8238–8240; `IMG_8181` es copia idéntica de `IMG_8179`, así que hay **67 diseños únicos**).
>
> **Cómo debe usar una IA este archivo:** leer primero la sección **2. ADN visual común** (los patrones que se repiten en TODOS los diseños) y después la **ficha concreta** o la **receta maestra** (sección 4) del tipo de pieza que va a crear. Las reglas medibles (radios, escala tipográfica, tokens) están en 2.7.

---

## Índice

- [1. Inventario de las 68 capturas](#1-inventario-de-las-68-capturas)
- [2. ADN visual común (el «estilo» que comparten)](#2-adn-visual-común-el-estilo-que-comparten)
  - 2.1 Paletas
  - 2.2 Tipografía
  - 2.3 Layout y composición
  - 2.4 Componentes recurrentes
  - 2.5 Imágenes, texturas y atmósfera
  - 2.6 Personalidad y micro-copy
  - 2.7 Reglas medibles y tokens (obligatorias)
  - 2.8 Dark UI, glass y widgets (macOS / iOS / dashboards)
- [3. Fichas detalladas, diseño por diseño](#3-fichas-detalladas-diseño-por-diseño)
- [4. Recetas maestras (cómo combinar todo)](#4-recetas-maestras-cómo-combinar-todo)
- [5. Checklist final para IA + prompt maestro](#5-checklist-final-para-ia--prompt-maestro)

---

## 1. Inventario de las 68 capturas

| Archivo | Tamaño | Formato | Familia / tipo de pieza |
|---|---|---|---|
| IMG_8179 | 736×976 | Slide vertical ~3:4 | Portfolio estudio creativo (Studio Atón) |
| IMG_8180 | 736×1308 | Página completa 9:16 | E-commerce moda editorial (Zerouge) |
| IMG_8181 | 736×976 | — | **Duplicado exacto de IMG_8179** |
| IMG_8182 | 736×976 | Slide vertical | Agencia creativa (Monero) |
| IMG_8183 | 736×976 | Slide vertical | Estudio de diseño (minimalist studio) |
| IMG_8184 | 736×981 | Página web larga | Arquitectura (auren) — hero + intro |
| IMG_8185 | 736×981 | Página web larga | Arquitectura (auren) — servicios + footer |
| IMG_8186 | 736×919 | Vertical 4:5 | Real estate de lujo (K / Pure – Luxe) |
| IMG_8187 | 736×694 | Casi cuadrado | Presentación Studio 99 (slide) |
| IMG_8188 | 564×423 | Slide 4:3 | Editorial (ncll / «less.») |
| IMG_8189 | 736×552 | Slide 4:3 | Surf / documental (Titans of the Mavericks) |
| IMG_8190 | 735×432 | Slide 16:9 | Agencia de viajes (BOTTEGA53) |
| IMG_8191 | 735×575 | Slide 4:3 | Portada de portfolio (Ramy Ayman) |
| IMG_8192 | 736×981 | Página web larga | Arquitectura (auren) — studio highlights |
| IMG_8193 | 735×1166 | Página larga | Portfolio personal (Kamery Yandell) |
| IMG_8194 | 700×1050 | Página larga 2:3 | SaaS RRHH (Worklife, FR) |
| IMG_8195 | 736×936 | Slide | Estudio digital (HYDNA / Process) |
| IMG_8196 | 736×1220 | Página larga | Agencia (Ockham, proyectos) |
| IMG_8197 | 736×1238 | Página larga | E-commerce moda (GAZU) |
| IMG_8198 | 736×1237 | Página larga | E-commerce calzado (NORD) |
| IMG_8199 | 735×497 | Franja 3:2 | Outerwear (NORDEN) |
| IMG_8200 | 736×736 | Slide 1:1 | Streetwear (lab. / X-LAB) |
| IMG_8201 | 736×1308 | 9:16 | Dashboard SaaS (RevenueX) |
| IMG_8202 | 736×981 | Vertical | Dashboard fintech (Credit Karma / Health) |
| IMG_8203 | 736×1040 | Vertical | App cripto dark (Giza) |
| IMG_8204 | 736×920 | Vertical | App IA workspace (Acme) |
| IMG_8205 | 735×525 | Horizontal | UI de chat IA dark |
| IMG_8206 | 735×421 | Horizontal 16:9 | Modal «Novedades» dark |
| IMG_8207 | 735×669 | Vertical | Empty state cripto dark |
| IMG_8208 | 735×551 | Horizontal 4:3 | Landing IA minimal (documentos) |
| IMG_8209 | 736×967 | Vertical | Widget de ayuda dark |
| IMG_8210 | 736×736 | 1:1 | Spec/redline de chat input |
| IMG_8211 | 736×736 | 1:1 | Design tokens (grises light/dark) |
| IMG_8212 | 735×708 | Casi 1:1 | Paleta + escala tipográfica |
| IMG_8213 | 736×615 | Horizontal | Glassmorphism (Frosted / Clear / Blur) |
| IMG_8214 | 736×920 | 3:4 | Unreal Engine (hero con guías) |
| IMG_8215 | 735×475 | Horizontal | Landing waitlist (Railroad.ai) |
| IMG_8216 | 736×460 | Horizontal | Landing IA (BridgeAI) |
| IMG_8217 | 735×490 | Horizontal | Landing IA (Step Through) |
| IMG_8218 | 736×736 | 1:1 | Hero concept (viajes) |
| IMG_8219 | 736×736 | 1:1 | Estudio creativo (Thought Before Form) |
| IMG_8220 | 736×736 | 1:1 | Viajes eco (Ruthway) |
| IMG_8221 | 736×552 | 4:3 | Wellness (ATMA) |
| IMG_8222 | 736×1472 | Página XXL | Hoteles Bali (Hotle) |
| IMG_8223 | 736×1324 | Página XXL | Agencia de viajes (Visa Travels) |
| IMG_8224 | 736×1472 | Página XXL | Energía eólica (SOLTERA) |
| IMG_8225 | 736×552 | 4:3 | CRM + modal promo (Conduit AI) |
| IMG_8226 | 600×359 | Horizontal | Widget calendario macOS (Spellar) |
| IMG_8227 | 736×414 | Horizontal | Command bar macOS (Start in Mail) |
| IMG_8228 | 736×1308 | 9:16 | Widget notch macOS (Nook / Tray) |
| IMG_8229 | 736×736 | 1:1 | Concepto iPhone (botones laterales) |
| IMG_8230 | 735×457 | Horizontal | Foto + tipografía (SAAS Startups) |
| IMG_8231 | 736×700 | Horizontal | Widget notch dark (registro horario) |
| IMG_8232 | 736×841 | Vertical | Widget reuniones dark (Coming Up) |
| IMG_8233 | 736×552 | 4:3 | Widget calendario light (Noviembre) |
| IMG_8234 | 736×736 | 1:1 | Formulario de contacto con arte |
| IMG_8235 | 736×981 | Vertical | Dashboard transporte dark (mapa) |
| IMG_8236 | 736×981 | Vertical | Dashboard transporte dark (alertas) |
| IMG_8237 | 736×917 | Vertical | Tip de diseño (border radius) |
| IMG_8241 | 736×920 | Vertical | Tip de diseño (tipografía) |
| IMG_8242 | 736×981 | Vertical | Tip de diseño (jerarquía visual) |
| IMG_8243 | 736×920 | Vertical | Tip de diseño (UX makover) |
| IMG_8244 | 735×523 | Horizontal | Tarjetas de alojamiento (2 variantes) |
| IMG_8245 | 736×552 | 4:3 | Tarjetas de vuelos (2 variantes) |
| IMG_8246 | 736×736 | 1:1 | Tarjeta de propiedad (glass oscuro) |
| IMG_8247 | 736×981 | Página larga | Real estate (Haven*) |
| IMG_8248 | 540×844 | 9:16 móvil | Alquiler vacacional (Stayli) |
| IMG_8249 | 736×1343 | Página XXL | Arquitectura industrial (ApexForm) |

**Familias presentes:** ① portfolios/estudios creativos, ② e-commerce editorial (moda/calzado), ③ arquitectura/real estate/lujo, ④ SaaS/AI/dashboards (light y dark), ⑤ UI de sistema macOS/iOS (widgets, modales, command bars), ⑥ micro-tips de diseño (radios, tipografía, jerarquía). Muchas piezas están presentadas como **slides de presentación o mockups 3D** (marco blanco + fondo gris/ambiente), no como capturas planas.

---

## 2. ADN visual común (el «estilo» que comparten)

Estos son los patrones que se repiten una y otra vez. Una IA debe aplicarlos por defecto salvo que la ficha diga lo contrario.

### 2.1 Paletas

1. **Base casi siempre neutra extrema:** blanco hueso / `#FAFAFA` / crema (`#F5F1EA`, `#EFEBE4`) **o** negro `#0A0A0A`–`#171717`. El color de marca aparece **solo en 1 acento** (rojo Zerouge, rojo GAZU, verde BridgeAI/SOLTERA, azul Stayli, dorado ATMA).
2. **Grises de sistema (tokens reales vistos en IMG_8211 – Tailwind neutral, certificados AAA):**
   - Light: `#FFFFFF` Base · `#FAFAFA` 50 · `#F5F5F5` 100 · `#E5E5E5` 200 · `#D4D4D4` 300 · `#A3A3A3` 400 · `#737373` 500 · `#525252` 600 · `#404040` 700 · `#262626` 800 · `#171717` 900 · `#0A0A0A` 950.
   - Dark: `#000000` Base · `#0A0A0A` 50 · `#171717` 100 · `#262626` 200 · `#373737` 300 · `#525252` 400 · `#8A8A8A` 500 · `#A3A3A3` 600 · `#D4D4D4` 700 · `#E5E5E5` 800 · `#F5F5F5` 900 · `#FAFAFA` 950.
3. **Paleta editorial con nombre (IMG_8212):** Alabaster `#FAFAFA`, Silver Chalice `#ADADAD`, Concord `#7E7E7E`, Black Cow `#454545`, Gluon Grey `#1E1C1C`, Onyx `#0E0E0E` (equivalentes rgb: 250/250/250, 173/173/173, 126/126/126, 69/69/69, 30/28/28, 14/14/14).
4. **Gradientes suaves “atmosféricos”** para fondos de mockup o hero: cielo azul con nubes, atardecer durazno→malva, verde salvia, dorado ámbar, azul marino profundo. Nunca gradientes multicolor saturados tipo “startup 2019”.
5. **Blobs/globos de gradiente** detrás de tarjetas clave (RevenueX dorado, Credit Karma naranja, Acme rojo) con desenfoque fuerte.
6. **Fotografía como color:** cuando hay imágenes grandes, se desaturan (B&N o casi) y el color se reserva para el acento. Excepción: paisajes a todo color como fondo de hero (BridgeAI, Ruthway, ATMA).

### 2.2 Tipografía

1. **Sans grotesk en dos registros:** (a) display *súper* grande (tipo Anton/Helvetica Now/Overused Grotesk/Archivo) para palabras-marca que ocupan el ancho completo o se salen del lienzo — `MONERO`, `minimalist studio`, `Studio⁹⁹`, `auren`, `NORD`, `GAZU`, `Hotle`, `SOLTERA`, `Portfolio`, `PROJECTS`, `LET'S TALK`, `Industrial & Commercial`; (b) grotesk neutra pequeña (Inter/Suisse/Neue Haas) para todo lo demás.
2. **Serif editorial itálica** como contrapunto intercalado: «Studio» en serif itálica vs «Atón» en bold sans (IMG_8179); `ApexForm` y `architecture / live, work, chill` en serif itálica dentro de frases sans (IMG_8222, IMG_8249); `Simplicity` itálica en IMG_8208; `reality` en IMG_8234. Regla: **la itálica serif marca la palabra “poética” de la frase**.
3. **Logos serif Didone** para marcas premium/clásicas (NORD, ncll). Logos sans-heavy para marcas modernas (gazu, MONERO).
4. **Micro-tipografía en mayúsculas con tracking amplio (10–12 px):** etiquetas de sección con prefijo `◆` `◦` `✳` `●` `+` o paréntesis `(2026)`, `(025)`, `◦ SERVICES`, `◆ THE BENEFITS OF WIND POWER`, `[BROADCAST TV]`, `NEW COLLECTION`, `INTRO`, `About Us`. Este detalle aparece en casi TODAS las piezas.
5. **Precios/estadísticas gigantes** en sans light-medium (`832`, `142,580`, `120+`, `8m — 20m`, `±2.5 min`, `78.3%`, `$137,036`). Números tabulares, sin decoración.
6. **Números y códigos “de archivo”** como ornamento: `V 023. Copy 034`, `09.01.2026`, `018053` vertical, coordenadas `37.4995 - 122.5235`, `EST. 2024`, `@2019 – 26`, `© 2026 Auren LLC`.
7. **Escala tipográfica de referencia (IMG_8212):** Heading XL 270px · Heading Large 77px · Display XL 48px · Display Large 31px · Párrafo Regular 19px · Párrafo Small 15px. Ancho máximo de composición: **1240px**.

### 2.3 Layout y composición

1. **Texto gigante que se cruza con la imagen** (texto delante o detrás, mezcla z-index): “auren” tapa la foto por abajo; “Unreal Engine” se superpone a la silla; “Hotle” detrás de la casa; “GAZU” detrás del modelo; “NORD” detrás de la zapatilla. La imagen “respira” entre letras.
2. **Grillas asimétricas editoriales:** bloque de texto 2/3 + meta-info 1/3; masonry 2+1 (IMG_8183); filas de 3 tarjetas con una central elevada y más grande (IMG_8194); columnas 01/02/03 con imágenes de alturas distintas (IMG_8192, IMG_8223).
3. **Franjas negras full-width** dentro de páginas claras para las secciones de producto/servicio (GAZU, NORD) o al revés (footer negro con wordmark gigante fantasma, auren IMG_8185).
4. **Nav “pill” flotante** (cápsula con blur) centrada o a la derecha, y botones pill negros con flecha `→` / `↗`. El nav plano con micro-caps y logo wordmark también es válido (Ockham, GAZU, NORD).
5. **Secciones numeradas** `01`, `02`, `03` diminutos en las esquinas de tarjetas + líneas guía de 1px (`#E5E5E5`) como retícula visible (SOLTERA, auren).
6. **Tarjetas flotantes sobre foto** con sombras grandes y suaves (Credit Karma, SOLTERA “10+ YEARS / 1.5M+”; K “MINIMAL & PREMIUM”).
7. **Composición centrada simétrica** para heroes emocionales (Railroad, ATMA, BridgeAI, Ruthway, «Your Next Adventure Starts Here»): título 1–2 líneas, sub de 2 líneas, un botón pill, todo sobre fondo imagen.
8. **Márgenes generosos**: 32–80px en desktop, respiro vertical grande entre secciones (100–160px). Nada pegado a los bordes salvo los full-bleed.
9. **Fondos de “escenario”:** muchas piezas viven dentro de un marco (monitor 3D, teléfono, ventana de tren, card blanca sobre gris `#D9D9D9`/`#C9C9C9`) con sombra difusa — es un recurso de presentación típico de este set.

### 2.4 Componentes recurrentes

- **Botón pill negro** con texto blanco small-caps o sentence case + icono `→`/`↗` (CTA primario universal). Variantes: outline con borde 1px, blanco sobre foto, “ghost” con blur.
- **Chips/tags pill** para categorías con estado activo negro y resto blanco/gris con borde 1px (filtros de Pexels, Home=Capsule/Cabin/Eco-villa, “I'm looking for…” de IMG_8234, pills de SOLTERA).
- **Botones circulares con flecha** (Ockham, Titans, Worklife “+”/“−” negros circulares).
- **Badge circular giratorio** “GET IN TOUCH” (Ockham) — sello circular con texto en anillo.
- **Pills de estado tipo frosted glass** (Frosted Vally Estate, Top Rated, 5 day stay, “1/8” contador de fotos).
- **Listas de navegación en 2 columnas** con labels pequeñísimos (“Projects / Services / The Studio / Blog / Careers”).
- **Dividers de 1px** y **líneas punteadas** como separadores (lista de servicios de auren: Architecture activo en negro, el resto en gris claro).
- **Tablas de datos densas** con mono-caps: rutas `L1 L12 L13`, offsets `-2min +0min -13min`, barras de progreso, sparklines.
- **Skeletons/ghosts** como decoración de empty states (IMG_8207: filas fantasma detrás del mensaje “Your watchlist is empty”).
- **Inputs de una sola línea con acción dentro** (email + “Join Waitlist”, “Your Email Address” + “Stay Updated”, command bar con `⌘K` / `⌘+Space`).
- **Avatares apilados** en pill (“5 invited · 3 accepted”) y avatares con punto verde online.
- **Tooltips de atajos de teclado** (`⌘ + Space`, `⌘ K`) en barras de búsqueda.

### 2.5 Imágenes, texturas y atmósfera

1. **Fotografía editorial**: retratos con luz dura y sombras, modelos en movimiento con blur (NORDEN, GAZU hero), arquitectura al atardecer con luces cálidas encendidas, paisajes épicos (Himalaya, valles verdes, dunas negras).
2. **Duotonos puntuales**: naranja/rojo sobre retratos (Studio Atón), rojo saturado total (Zerouge), monocromo frío casi azul (Studio Atón pilates).
3. **Grano/noise sutil** sobre fotos e ilustraciones (dunas IMG_8219, “bloom” en ATMA).
4. **Halftone/dither** como recurso gráfico (tigre de puntos de Zerouge, dot matrix).
5. **Arte no fotográfico**: ilustración lineal B&N minimal (IMG_8195: persona en silla con laptop), arte pintado tipo storybook (IMG_8234), 3D renders limpios con reflejos (ApexForm, Unreal Engine, Worklife flecha de cristal).
6. **Texturas de fondo**: patrones de líneas topográficas (NORDEN), tramas de puntos (tips), líneas de guía/blueprint (ATMA, Unreal), “paint strokes” pastel (fondo de widgets macOS).
7. **Guías de cámara/blueprint** sobre heroes (círculos, cruces `+`, marcos finos) — detalle de “diseño de diseño” (Unreal Engine IMG_8214, ATMA).

### 2.6 Personalidad y micro-copy

- Copy con actitud y breve, en minúsculas o sentence case: *“Not here to match the energy.”*, *“Wear responsibly. Or don't.”*, *“Who prefer magnetism over likability.”*, *“Not Your Boring Travel Agent”*, *“We plan chill, curated trips with good vibes and better people.”*
- **Emojis muy dosificados** (1 por pantalla máximo, siempre junto a un saludo o acción): 👋, 🤙, ✨, 🤩, ⭐.
- **Datos “en vivo”** como ambientación: “New York 10:39 AM”, “in 2 minutes”, “4m ago”, “142,580 today”.
- **Idiomas mezclados** esporádicos (EN/UA, EN/ES, francés) y textos de utilería en latín (`Lorem ipsum`) solo en mockups.
- **Nada de iconos decorativos saturados**: iconografía lineal fina (1.5px) y consistente; iconos solo cuando aportan función (features, specs, lista).

### 2.7 Reglas medibles y tokens (obligatorias)

1. **Border radius anidado (IMG_8237):** `radio_exterior = radio_interior + padding`. Ejemplo correcto: card 24px / inner 16px con 8px de padding. Nunca radios iguales anidados. Regla extra: si los dos radios comparten centro, el inner sin padding máximo `< 24 − 8`. Multiplicador permitido (~1.5×). Para testear: escalar el frame interior al tamaño del exterior.
2. **Jerarquía tipográfica (IMG_8241):** tamaño headline 24px, subheading 16px, cuerpo 14px, botones 16px (ejemplo ✅). Ejemplo ❌: 26/13/11/18 — diferencias caóticas y cuerpo demasiado pequeño. Reglas: *jerarquía clara, botones legibles, cuerpo legible ≥14px, escala consistente*.
3. **Jerarquía visual de tarjeta (IMG_8242):** NUNCA `Label: value` repetido (❌). En su lugar: media grande → Título grande (una sola vez) → meta en una línea (lugar/estado) → rating con estrellas y conteo → fila de specs con iconos → descripción corta → **un** CTA sólido. El ojo debe escanear en F/Z sin leer todo.
4. **UX Makover (IMG_8243):** coloca la imagen, luego `Título` + fila `Precio · ⭐Rating`, descripción con truncado elegante (“more…”), divider, y CTA con **sombra/glow** + acción secundaria en color de acento (Customization). Antes: datos “Nombre: / Precio: / Ratings:” — prohibido.
5. **Densidad y espaciado:** padding interno de cards 16–24px; gaps 8/12/16/24/32/48; secciones 96–160px; radios 8/12/16/24/999 (pills). Sombras: `0 20px 60px rgba(0,0,0,.10)` para flotantes, `0 2px 8px rgba(0,0,0,.06)` para sutiles.
6. **Contraste:** los grises vistos están validados **AAA** (IMG_8211). Texto body mínimo `#525252` sobre blanco; nada de grises claros para texto.
7. **Glass real (IMG_8213):** tres recetas — *Frosted* (blur 20–40px + tinte oscuro 30–50% + borde blanco 10%), *Clear* (blur bajo 8–12px + borde 1px blanco 25% + sombra interna nítida, estilo iOS), *Blur cálido* (blur 30px + tinte beige, estilo One UI). Aplicar a pills, chips, tarjetas sobre foto y navs.
8. **Alturas de línea:** display `0.9–0.95`; títulos `1.05–1.15`; cuerpo `1.5–1.6`. Tracking: display `-0.02em a -0.04em`; micro-caps `+0.08em a +0.18em`.

### 2.8 Dark UI, glass y widgets (macOS / iOS / dashboards)

- **Fondos dark:** `#0A0A0A`–`#171717` con un gradiente/glow de color muy sutil (azul marina, rojo, verde) y **foto de ambiente** (dunas, cielo, rocas) fuera de la UI.
- **Widgets estilo macOS:** panel de vidrio oscuro con esquinas 20–28px, sombra profunda, contenido en pilas: icono+etiqueta, título grande, meta en gris `#8A8A8A`, acciones pill.
- **Command bars / inputs IA:** input redondeado (24–28px) centrado, glass, con chips internos (`5 tools` azul), toolbar de iconos finos debajo, popover de acciones con checks.
- **Toasts/modales dark:** card `#1C1C1E`–`#262626`, título blanco semibold, texto gris `#A3A3A3`, 1 CTA claro, cierre `×` arriba a la derecha; icono fantasma de marca al 10% de opacidad como watermark (IMG_8206).
- **Empty states:** ghost/skeleton de la lista real detrás, mensaje claro centrado, CTA blanco “pill”. 
- **Dashboards dark:** panel lateral + mapa/foto a sangre, tarjetas de métricas con micro-charts, alertas en rojo `#B3261E` sobre `#2A1A1A`, valores grandes light, tablas mono.
- **Dashboards light cálidos:** fondo blanco con **blob de gradiente dorado** detrás del módulo hero (RevenueX), título serif itálica de sección (“Performance Overview”), filas de tabla con thumbnails de producto y checkboxes (uno marcado verde).
- **Detalle iOS 2026 (IMG_8229):** el “botón de acción” se explora como control vertical gigante con iconos apilados (modo silencio/🔕, luna oscura, persona/work, cámara). Concepto: física de hardware como lenguaje gráfico.

---

## 3. Fichas detalladas, diseño por diseño

> Formato de cada ficha: **Familia · Formato** → descripción detallada por zonas → tipografía/color → detalles → **Reglas que enseña**.

### IMG_8179 — «Studio Atón» (portfolio de estudio) · *duplicada en IMG_8181*
**Familia:** portfolio estudio creativo · **Formato:** slide vertical 3:4.

- **Hero:** grid de fotos con kicker de color: retrato duotono naranja a la izquierda, dos manos rosadas a la derecha, retrato pelirrojo en azul a la izquierda, **mujer haciendo pilates en reformer** (foto fría azulada) en el centro, foto oscura a la derecha. Encima, nav mínimo: “Studio Atón ®” izquierda; “Work / About / News / Contact” derecha (10px, sentence case).
- **Wordmark gigante** partido y superpuesto al grid: **“Studio” en serif light itálica** + **“Atón” en sans bold** + ® volado. Une las dos mitades con una línea de 1px que atraviesa el medio.
- **Bloque blanco** debajo: label centrado `( Studio Atón ® )`, párrafo centrado a 5 líneas: “— a design studio working at the intersection of brand, product, and technology. Designing brands and digital products that move businesses forward.”
- **CTA:** pill negro “● Let's chat” centrado.
- **Fila de logos** de clientes en gris (Lightbox, Boltshift, FeatherDev, Spherule) con iconos geométricos.
- **Siguiente sección:** “Latest projects” en tipografía display negra enorme (2 líneas, apretada), con contador `(26)` a la izquierda y flecha-flecha sutil a la derecha.
- **Fondo del entorno:** la página vive dentro de un marco sobre foto gris desenfocada (presentación).

**Reglas que enseña:** mezclar 2 tipografías (serif itálica + sans bold) en el wordmark; grid de imágenes con variedad cromática y una central protagonista; nav ultra-minimal; CTA pill con punto; prueba social con logos monocromos; display gigante tipo “Latest projects” con `(contador)`.

### IMG_8180 — «Zerouge» (e-commerce moda)
**Familia:** e-commerce editorial · **Formato:** página completa 9:16 (presentada sobre fondo de nubes).

- **Barra superior negra** fina con micro-caps: “THE HOTTEST BAGS IN [brand]” izquierda; “ZEROUGE” centro; derecha “SHOP / CART (0)”.
- **Nav:** Men / Women / News — logo **Zerouge en script rojo itálica** al centro — Shop / Cart (0). Fondo blanco.
- **Hero foto:** Cadillac rojo descapotable con una mujer recostada, **cohete despegando** al fondo (humor/absurdo). Debajo, fila de micro-caps rojas separadas: “BUILT FOR STARING CONTESTS · WEAR RESPONSIBLY · OR DON'T · ZEROUGE ASSOCIATION ®”.
- **Sección tipográfica:** “Not here TO MATCH the energy.” — mezcla de serif/sans y display gigante roja con **tigre hecho de puntos (halftone)** saltando entre “TO” y “MATCH”; “the energy.” en columna pequeña a la derecha.
- **Grid de producto 3-up** con etiqueta “BUY” minúscula sobre cada foto (gafas de esquí/deporte, modelo con camiseta, modelo con gafas). 
- **Cierre:** “WHO PREFER MAGNETISM OVER LIKABILITY.” en rojo bold centrado + párrafo legal mínimo.

**Reglas que enseña:** todo el sistema cromático rojo+blanco+negro; tipografía display condensada como voz de marca; ironía en el copy; micro-caps de “asociación/membresía” para dar estatus; producto en 3-up con etiqueta mínima.

### IMG_8182 — «Monero» (agencia creativa)
**Familia:** agencia · **Formato:** slide vertical.

- **Nav:** isotipo geométrico izquierda · **pill negro flotante “☰ Menu” centrado** · “Connect Us” derecha.
- **“MONERO” gigantesco** (peso black, tracking negativo) ocupando todo el ancho, alineado a la izquierda.
- Debajo: `@ 2019 – 26` en pequeño + **tres tarjetas fotográficas tipo abanico**: retrato naranja duotono / gradiente iridiscente violeta-azul con objeto metálico / verde salvia con **taza roja** (punto de color).
- Columna derecha vertical: “Based in USA” rotado 90°.
- **Columna izquierda:** icono globo de alambre + claim: “Creative Solutions & Innovation Tailored for forward-thinking companies.”
- **Columna derecha:** chips grises apilados (Motion Graphics, Campaign Strategy, Brand Identity, Web Design) — el activo en blanco con borde.
- **Sección “Studio”**: label `• Studio •` centrado; statement grande: “A global creative agency crafting bold and adaptive for modern businesses.” (con salto rítmico de líneas).
- **Fila de 5 cards-logotipo** “Logolpsum” (variaciones de isotipo) con “EST.21, EST.23, EST.25, EST.21…”.
- Corta en negro abajo (siguiente sección dark).

**Reglas que enseña:** display one-word como cabecera; tarjetas de imagen con ligeras rotaciones/offset; servicios en chips verticales; prueba social funny-fake; contraste de secciones blanco→negro en la misma página.

### IMG_8183 — «minimalist studio» (estudio de diseño)
**Familia:** estudio/agencia · **Formato:** slide vertical.

- **Nav:** `✳ Minimalist` izquierda; Home, Projects, Services, About us, Articles; **botón rojo pill “Contact →”** derecha.
- **Titular display de 2 líneas** “minimalist studio” (minúsculas, peso black) con una **imagen colorida tipo molinete/caleidoscopio insertada entre las palabras** (justo después de “minimalist”) — la imagen interrumpe la tipografía.
- Fila de meta: “We're a creative design agency dedicated to building brands that stand out and connect.” | “Based in NYC United State” | botón rojo “Book a call →”.
- **Grid de proyectos masonry 2+1:** (1) bloques de madera con logo espiral centrado → “Boldstream — Branding · Motion Design”; (2) excursionistas → “InnovateX — Website · Motion Design” con patrón checkerboard sobre la foto; (3) mesa con whisky → “PixelForge — Digital Marketing…”. 
- Etiquetas dentro de cada card: nombre en negro abajo-izquierda, servicios abajo-derecha.

**Reglas que enseña:** insertar una imagen dentro del titular; un solo acento rojo para CTAs; cards con **logo-marca centrado sobre la foto**; tags de servicios dentro de la card; contraste tipográfico minúsculas-black vs texto normal.

### IMG_8184 — «auren» (arquitectura) — hero + intro
**Familia:** arquitectura/estudio · **Formato:** página larga.

- **Hero full-bleed:** interior arquitectónico cálido (madera, cuadro, planta, sillón). Nav blanco arriba: logo “auren” izquierda; “Projects / Services / The Studio / Blog / Careers” en columna; “📍 Contact” derecha.
- **Textos overlay** en 3 puntos: “work from 2016” (izq.) · “Designing timeless spaces with clarity, warmth, and intention.” (centro) · “(2026)” (der.).
- **“auren” blanco gigante** (light, minúsculas, casi 100% del ancho) **montado sobre el borde inferior de la foto**, con su parte baja cayendo al blanco.
- **Sección blanca:** label `INTRO` micro centrado; statement grande centrado “We create refined residential and commercial environments that balance architecture, interior design, and modern living”, con **fotos superpuestas** flotando alrededor (casa al atardecer arriba-derecha, Porsche 911 abajo-izquierda, interior abajo-derecha).

**Reglas que enseña:** wordmark gigante a caballo entre imagen y fondo; textos overlay en las 3 posiciones clásicas; sección “INTRO” con fotos desperdigadas alrededor del texto centrado; paleta cálida neutra (beige, madera, negro).

### IMG_8185 — «auren» — servicios + footer
- **Hero corto:** repite foto con “Linea Loft” blanco grande + sub “Urban loft interior combining minimalism and warm materiality”.
- **Bloque gris claro “SERVICES”:** label micro; párrafo statement a la izquierda (“We provide architecture, interior design, and spatial planning services…”).
- **Lista de servicios tipográfica** (columna derecha): “Architecture” en **negro activo** con línea debajo, seguido de “Interior Design”, “Space Planning”, “Creative Direction” en **gris claro** — el degradado de color indica estado/orden. A la izquierda, foto pequeña de casa moderna con jardín.
- **Footer negro:** nav horizontal (Projects, Services, About, Blog, Careers, Contact), “© 2026 Auren LLC”, “Privacy Policy”, y **wordmark “auren” negro gigante recortado al fondo** (marca fantasma).

**Reglas que enseña:** servicios como lista tipográfica (no cards), activo negro vs inactivos `#D4D4D4`; foto acompañante flotante; footer con wordmark gigante en tono apenas visible; datos legales pequeños.

### IMG_8186 — «K · Pure – Luxe» (real estate de lujo)
**Familia:** inmobiliaria/lujo · **Formato:** vertical.

- **Cielo azul limpio** como fondo superior. Arriba centrado: “**Pure [isotipo K] Luxe**”.
- Titular “MINIMAL & PREMIUM” en blancas espaciadas (peso light), sub de 3 líneas centrado: “Bold geometry balanced with the soft luxury of natural light, a home that stands with confidence yet feels effortless.”
- **Render fotorrealista** de villa de hormigón y blanco con palmeras, un Mercedes G-Class negro aparcado y un sedán desenfocado en movimiento (velocidad). 
- Pie: isotipo K abajo-izquierda; abajo-derecha **“Al-Wakra | 20 · Qatar | 23”** (lugar/año en columnas).

**Reglas que enseña:** fondo plano de color natural (cielo) para “respirar”; white-spaced caps para lujo; el auto/velocidad como símbolo de estatus; metadata de proyecto en esquinas; logo dispuesto como “sándwich” (Pure · Luxe alrededor del isotipo).

### IMG_8187 — «Studio 99» (slide de presentación)
**Familia:** estudio · **Formato:** cuadrado, mockup de slide sobre gris claro.

- **Slide blanco:** “Studio°” arriba-izquierda; derecha: lista micro-caps “PROJECTS / ABOUT / CONTACT / BLOG” + **switch pill con asterisco** `✳` (control de UI).
- **Izquierda:** foto cuadrada (caja metálica, altavoz negro oval, jarra) + lista de categorías: “Branding” (negro) / “Website / Packaging / Interior” (grises).
- **Derecha-abajo:** “Studio⁹⁹” en display black gigante con el “99” volado como superíndice.

**Reglas que enseña:** una sola foto producto sobre blanco puro; categorías como texto (no menú); el nombre como tipografía objetual con número volado; el switch de UI como detalle de marca.

### IMG_8188 — «ncll / less.» (editorial)
**Familia:** editorial/moda · **Formato:** slide 4:3.

- **Nav:** “ncll” izquierda; “Print Shop · Commercials · Covers”; hamburguesa derecha.
- **Izquierda:** “Categories +” en vertical; **botón circular “Slide”** con outline fino (control artesanal).
- **“less.” en serif Didone negra gigante** abajo-izquierda, con el punto final enorme.
- **Derecha:** dos fotos B&N (retrato de perfil de Kobe Bryant; mano señalando al cielo), con pies de foto: “PORTRAIT / Kobe Bryant — STYLE. /A7” y “EDITORIAL / Untitled Res — PORT.GQ”. Códigos de archivo en micro-tipografía.
- **Fondo slide:** beige claro `#EFECE6` aprox.

**Reglas que enseña:** serif de alto contraste para palabra corta + punto; fotos B&N con “créditos de editorial” (tipo de pieza + nombre + código); controles de navegación circulares finos; el vacío como lujo.

### IMG_8189 — «Titans of the Mavericks waves» (documental/surf)
**Familia:** editorial deportivo · **Formato:** slide 4:3.

- Isotipo de **tres olas** dibujadas a línea, arriba-izquierda. Nav derecha: Main, Spots, Communities, About, Sponsors + “Search”.
- **Contenido en 3 columnas:** titular negro grande “Titans of the Mavericks waves” (3 líneas) | **foto B&N del surfista en la ola** (con tabla “Pillar Point”) | cifra “8m — 20m” (tamaño de ola) en grande.
- **Bloque “1967”** + párrafo explicativo del lugar (Mavericks, Pillar Point, contest 1999–2016).
- Pie: “Pillar Point / Halfmoon, California / **37.4995 - 122.5235** (coordenadas reales)” + **botón circular con flecha →**.
- Fondo blanco hueso `#F2F1ED`.

**Reglas que enseña:** datos verificables como diseño (año, altura de ola, coordenadas); foto central B&N; titular editorial a la izquierda; isotipo dibujado a mano; nav plano + búsqueda.

### IMG_8190 — «BOTTEGA53» (agencia de viajes)
**Familia:** agencia · **Formato:** slide 16:9 **negro total**.

- Tipografía Helvetica blanca. Arriba-izquierda “BOTTEGA53”; arriba-derecha **texto vertical rotado** (dígitos “018053”).
- **Centro-derecha:** “PROJECTS” grande con subrayado luminoso + debajo lista: “SEARCH / DESTINATIONS ⊙ / FAQ”.
- **Abajo-izquierda:** “ABOUT / CONTACT” en dos líneas gigantes.
- **Centro-abajo:** email y teléfono subrayados (“MANO@BOTTEGA53.COM · +81 90 754 330 053”).
- **Pie:** micro “MANO PROJECT · COMMERCIAL EXPERIENCE” izquierda; “INSTAGRAM PINTEREST FACEBOOK” derecha.

**Reglas que enseña:** slides de menú/catálogo en negro puro con Helvetica gigante; agrupar todo en 4 zonas; línea subrayando el título; verticales rotados como acento; mail/tel como elementos gráficos.

### IMG_8191 — «Portfolio» (portada de presentación)
**Familia:** portada personal · **Formato:** slide 4:3 blanco.

- Arriba-izquierda: **logo-ojo dentro de un óvalo** (símbolo), “09 Jan. 2026”, “**Creative Presentation**” (semibold), “Presented By: Ramy Ayman”.
- Pie de página: “Art Director / Brand Designer / illustrator” izquierda; derecha “V 023. Copy 034 · 09.01.2026”.
- **“Portfolio” en sans bold gigante recortado por el borde inferior** (solo se ve la mitad superior de las letras).

**Reglas que enseña:** portadas = metadata + una palabra gigante recortada; numeración de versión y copia; logo-símbolo pequeño arriba; nada más. El corte del display por el borde es un gesto de esta familia de piezas.

### IMG_8192 — «auren» — studio highlights
- Repite hero “Linea Loft”. Después, sección blanca: label `STUDIO HIGHLIGHTS`; titular centrado “**Designed for creativity and collaboration**”.
- **Tres columnas `01/02/03`** con etiquetas micro y fotos de distinta altura: `01` Material Library (cocina clara + macetas + párrafo: “Our studio reflects the same principles we bring into every project — calm atmosphere, refined materials, natural light, and intentional design decisions that support both creativity and focus.”), `02` Collaborative Workspace (auto clásico verde en nave), `03` Design Archive (escaleras de madera, luz de ventana).
- Los títulos van **debajo** de cada imagen, alineados con el borde inferior de la foto.

**Reglas que enseña:** secciones numeradas con dos dígitos; 3 columnas de fotos con alturas alternadas; el párrafo de misión vive en la columna 01; títulos pegados a la imagen (continuidad).

### IMG_8193 — «Kamery Yandell» (portfolio personal freelance)
**Familia:** portfolio personal · **Formato:** página larga.

- **Barra superior:** email en texto plano; pills negras “Copy” y “CV”; derecha “LinkedIn / Dribbble / Instagram”.
- **Centro:** avatar circular pequeño con **pill conectora “Kamer Yandell →”** flotando a su derecha; titular centrado “**Building digital products, brands, and experience.**” (3 líneas, ~40px).
- CTA pill negro “Latest Work ↗”.
- **Panel blanco full-width** (bordes redondeados grandes) con logos: National Bank, matterd*, Coca-Cola, Adobe, SUBWAY, codecademy (monocromo B&N).
- **Sección servicios:** titular centrado “Collaborate with brands and agencies to create impactful results.”; **línea horizontal con pill “Services” centrado encima**; 4 columnas con iconos lineales: UX & UI, Web & Mobile App, Design & Creative, Development, y descripciones de 2-3 líneas.
- **Panel blanco final:** icono circular con apretón de manos; “Tell me about your next project”; pills “✉ Email Me” (negro) + “Whatsapp” (blanco borde).
- Pie: “© 2024 All rights reserved.” + redes.

**Reglas que enseña:** estructura freelance clásica pero con detalles premium (avatar con pill-de-nombre, línea de sección con chip centrado, paneles blancos sobre gris); CV y Copy como pills; logos cliente en B&N; sección contacto personalizada con 2 canales.

### IMG_8194 — «Worklife» (SaaS de beneficios, francés)
**Familia:** SaaS light · **Formato:** página 2:3.

- **Nav:** logo “w worklife”; menú “Pourquoi Worklife ? / Avantages Salariés / Cas Clients / Ressources”; dos botones: “Activer ma carte” (claro) + “**Parler à un expert**” (negro).
- **Hero:** titular grande “**Avec Worklife, vous avez l'avantage.**” con **icono 3D de flecha de cristal** insertado en el blanco entre líneas; sub de 1-2 líneas; CTA pill negro.
- **Fila de logos** (Amazon, Allianz, GRDF, Saint-Gobain, Danone, Adecco) con caption “Plus de 300 entreprises se sont révélées à nos côtés”.
- **Tres tarjetas de estadísticas** ligeramente superpuestas en fila: “**9** collaborateurs sur 10 ouvrent leur application…” (card blanca, botón circular negro ↓), “**62%** d'augmentation…” (**card verde salvia elevada y más grande**, botón +), “**27%** d'économies grâce à la centralisation…” (botón −).
- **Bloques foto con tarjetas de vidrio** superpuestas (personas, luz cálida).
- Cierre: “**Votre politique RH a du potentiel, révélez-le.**” con “politique RH” resaltado en azul/lila.

**Reglas que enseña:** datos > adjetivos (9/62%/27%); una card central destacada por color y escala; texto clave resaltado con color dentro del titular; iconos 3D insertados en el titular; logos como banda de confianza; localización completa del idioma.

### IMG_8195 — «HYDNA / Process» (estudio digital, 2 slides)
**Familia:** estudio · **Formato:** slide compuesto.

- **Slide 1:** “HYDNA” rotado 90° a la izquierda; nav micro: Work, Home, Playground, Contact; **ilustración lineal B&N** de una persona sentada en un taburete con laptop (trazo fino, estilo editorial); titular **serif** grande “Shaping digital experiences with clarity, intention, and character.” (3 líneas) abajo-izquierda.
- **Slide 2:** “Process” en serif grande + **columna editorial** con micro-secciones (DISCOVERY, RESEARCH…) y párrafos justificados en cuerpo muy pequeño; numeración de página `01`, `02`; tabs verticales laterales; zonas difuminadas (prototipo).
- Fondo huevo `#F0EEE9`.

**Reglas que enseña:** el “process” se muestra como página de revista; ilustración de 1 tinta sobre fondo crema; rotar el logotipo; cuerpo de texto minúsculo + título serif grande; marcar la página con número.

### IMG_8196 — «Ockham» (agencia audiovisual)
**Familia:** agencia · **Formato:** página larga.

- **Nav:** “OCKHAM” izquierda; WORK / ABOUT / CONTACT derecha (micro-caps).
- **“PROJECTS” display black gigante** + “26” volado.
- **Fila de filtros:** “ALL · FILMS · [BROADCAST TV] · FASHION · FITNESS · FOOD” (el activo entre corchetes).
- **Cards de proyecto** con estructura editorial: título en caps + año + tags micro (Fashion, Lifestyle, Automotive…) y foto con **botón circular →**:
  - LUCID MODE 2021 (tablet oscura, foto a sangre).
  - FILE NOT FOUND 2019 (cabezas invertidas, foto a la derecha).
  - COMES BACK 2022 (auto negro cruzado, desierto).
  - CALLAWAY 2021 / TRIMMING JINGLE 2023 (pares a 2 columnas).
- **Cierre:** “**LET'S TALK**” display gigante + “AND CREATE SOMETHING TOGETHER” + **badge circular giratorio “GET IN TOUCH”** + email/teléfono en micro-caps + nav repetido.

**Reglas que enseña:** lista de proyectos como índice tipográfico + imágenes alternadas; filtros con corchetes; el footer-reel “LET'S TALK” + sello circular; año como metadata; contraste constante de foto color vs texto negro sobre blanco.

### IMG_8197 — «GAZU» (e-commerce moda, India)
**Familia:** e-commerce · **Formato:** página larga.

- **Barra negra fina:** “FREE DELIVERY ON ORDERS ABOVE ₹999” izquierda; “DOWNLOAD APP · TRACK ORDER · HELP” derecha.
- **Nav:** MEN WOMEN KIDS BEAUTY · **GAZU** (letterspaced geométrico) centro · 🔍 LOGIN ♡ WISHLIST 🛒 CART (0).
- **Hero B&N:** modelo caminando con gabardina (grayscale), **“GAZU” gigante gris detrás como marca de agua**; texto “FASHION THAT MOVES WITH YOU.” + línea; botones “SHOP NOW” (negro) y “EXPLORE NEW IN” (outline); derecha “NEW COLLECTION 2024”.
- **Banda negra** con 3 bloques producto: MEN (“Elevated everyday essentials.” SHOP MEN →), WOMEN (“Effortless style for every you.”), KIDS (“Comfort meets cool every day.”) — foto cuadrada + título caps + micro-link.
- **Sección “NEW SEASON / NEW VIBES”:** titular grande 2 líneas + “Discover everything new and now.” + “EXPLORE COLLECTION” negro; derecha foto de modelo.
- **Barra de servicios:** 4 items con iconos lineales (FAST DELIVERY, EASY RETURNS 15 days, QUALITY ASSURED, SECURE PAYMENT).
- **“BEST OF GAZU” + “VIEW ALL”** con subrayado; grid de 4 productos con corazón ♡.

**Reglas que enseña:** marca de agua tipográfica detrás del modelo; banda negra intermedia partiendo la página; servicios en 4 columnas con iconos finos + línea superior; títulos de producto como caps + micro-link con flecha; newsletter/hearts discretos.

### IMG_8198 — «NORD» (e-commerce calzado premium)
**Familia:** e-commerce premium · **Formato:** página larga.

- Fondo **crema `#F3EFE6`**. Barra fina: “FREE SHIPPING · FREE DELIVERY ON ORDERS ABOVE 1890 · TRACK ORDER | HELP”.
- **Nav:** SNEAKERS BOOTS ESSENTIALS COLLABS · **NORD en serif Didone** centro · 🔍 👤 📄 ♡ 🛒 CART.
- **Hero:** “**NORD**” serif gigante detrás; **zapatilla crema sobre bloque de piedra** (foto central); izquierda “DESIGN THAT ENDURES” + “SHOP NOW” negro; derecha “COLLECTION NO. 1 · EST. 2024”.
- **Banda negra** con 3 categorías: SNEAKERS (“Refined performance.”), BOOTS (“Classic utility.”), ESSENTIALS (“Pure form.”) con thumbnails cuadrados y links →.
- **Sección “NEW SEASON — RAW TEXTURES”:** “Explore our latest materials and craftsmanship.” + “EXPLORE COLLECTION”; derecha **botín chelsea sobre hormigón** en luz dura.
- Servicios (4 iconos), y “BEST OF NORD / VIEW ALL” con grid de zapatillas (beige, negra, blanca, botín).

**Reglas que enseña:** “premium clásico” = serif Didone + crema + piedra/hormigón + luz dramática; misma estructura que GAZU (hero tipográfico, banda negra, servicios, best-of) — **la plantilla se repite cambiando tipografía y color**: esta es la prueba de que el set comparte un esqueleto.

### IMG_8199 — «NORDEN» (outerwear técnico)
**Familia:** e-commerce outdoor · **Formato:** franja 3:2.

- Fondo blanco con **patrón de líneas topográficas** suave.
- Nav: “NORDEN” izquierda; Collection, Field Tests, Technology, Journal; “**Buy Now**” pill negro.
- Izquierda: “NEW COLLECTION” micro. **Titular grande:** “The mountain is the measure.” (2 líneas). Sub: “Precision-built outerwear for when conditions decide the outcome. From studio to summit — tested, trusted, refined in motion.”
- Derecha: “**Shop Jackets ↗**” con subrayado + flecha.
- **Foto central:** 4 chaquetas infladas colgadas en una barra (gris, crema, negra, naranja quemado) — alineadas como muestra de color.
- Detalle: cruz `+` de “expandir/mapa” arriba-derecha.

**Reglas que enseña:** patrón topográfico = código visual outdoor; una línea de producto alineada = “paleta” visual (gris/crema/negro/naranja); titular + sub + 1 CTA textual con flecha (sin botón pesado); cruz `+` como detalle.

### IMG_8200 — «lab.» (streetwear X-LAB 2019)
**Familia:** moda urbana · **Formato:** slide 1:1 sobre gris.

- Slide blanco: “+1” y “PROJECTS” micro arriba; centro-derecha: AW19 · SHOP · NEW ARRIVALS ▾; “•••” esquina.
- **“lab.” display bold con punto** a la izquierda (peso fuerte, caja baja).
- Pequeños bloques de texto ilegibles/desenfocados (ficha técnica) a los lados.
- **Persona con chaqueta roja técnica** (gorro bucket + máscara) delante de una **franja roja horizontal** que corta el layout; texto vertical derecha: “X-LAB / MATERIALS OF CREATION 2019”.
- “**100**” gris (outline/gray) abajo-izquierda + cuadrado con “→” abajo al centro.

**Reglas que enseña:** franja de color como escenario del producto; texto vertical con nombre de colección; contador/número grande de fondo; la tipografía con punto (“lab.”) como firma; elementos de UI (•••, ▾) como decoración.

### IMG_8201 — «RevenueX» (dashboard SaaS sobre mockup)
**Familia:** dashboard light cálido · **Formato:** 9:16 con fondo desierto/atardecer.

- **Mockup flotante en 3D** (perspectiva) sobre foto de dunas y cielo al atardecer.
- **Sidebar translúcida tipo vidrio oscuro:** logo flor/engranaje + “RevenueX”; grupos: **Main** (Dashboard activo con pill, Contracts, Analytics), **Inboxes** (Clients +1 (415) 555-0123, Personal, Sales Team), **Other** (Messages con badge “2”, Performance Insights), **Account** (Settings, Feedback); abajo usuario “Evan Parker · evan.parker@gmail.com”.
- **Topbar:** búsqueda “Search data, reports, or products…” + atajo `⌘+Space`.
- **Contenido:** “**Performance Overview**” (mezcla serif itálica “Overview”); “Your sales, growth, and insights — all in one place”.
- **Banner hero del módulo:** blob de gradiente **dorado**, título serif “Explore your performance”, “Dive into trends and product insights”; dos botones circulares (oscuro con icono de gráfico, claro con “+”).
- **Tabla “Product Performance”:** columnas Product / Total Orders; filas con thumbnail: Sonic Headphones (SPH-101), Scope VR Glasses (VSG-309, **checkbox verde marcado**), VisionEdge Monitor (VEM-204), ChronoSmart Watch (CSW-412, spinner), Sonic Headphones; valores “250 uni…”.

**Reglas que enseña:** UI light + blob dorado detrás del módulo principal; títulos de sección con una palabra en serif itálica; sidebar glass con grupos y paddings; tabla con miniaturas y checkboxes de estado; presentar el dashboard como objeto 3D flotante sobre paisaje.

### IMG_8202 — «Credit Karma · Health Karma» (dashboard fintech sobre monitor)
**Familia:** dashboard fintech · **Formato:** monitor 3D.

- Pantalla renderizada en un monitor sobre fondo de bloques verdes/negros.
- **Glow naranja→amarillo** invadiendo la esquina superior derecha.
- **Header:** hamburguesa, logo creditkarma, tabs pill: “Karma” (negro activo), “Credits”, “Money”.
- Título “**Health Karma**”; chips “Equifax”, “TransUnion”.
- **Score:** “1 pts” micro + “**832**” gigante + “Excellent · Checked Daily” + **gauge semicircular** (dial fino).
- **Cards:** Net Worth `$137,036` (icono flecha arriba), Total Debt `$64,100` (icono alerta, flecha abajo).
- **Columna derecha:** “Credit Card Use 9” (card sobre blob iridiscente con paginación de puntos), “Credit Age 4 Years” (mini-sparkline), “Payment History 100”, “Total Accounts 12”.
- **Barra inferior negra:** “Score History” + bar-chart con eje 850/800/750, pills de rango (3 month, 6 month, 1 year), tooltip “816 · +8 pts · Excellent credit score”.
- **“Credit Offers”:** cards con logos (Goldman Sachs — Auto 14 / Rental 18; Bank of America).

**Reglas que enseña:** número clave (score) como héroe; un gradiente cálido como “energía”; mezcla de cards blancas y oscuras en la misma pantalla; histórico en chart minimal; ofertas como filas con marca + cifras.

### IMG_8203 — «Giza» (app cripto dark)
**Familia:** fintech dark · **Formato:** vertical.

- Fondo: cielo azul oscuro degradado con horizonte cálido (foto).
- **Panel negro redondeado (24px+):** topbar “✦ Giza” + Deposit / Withdraw / Settings.
- **Dos esferas de cristal gigantes:** la izquierda “**Scanning yield...**” con spinner y reflejo tipo eclipse; la derecha negra con truncados “$50 / LIFE… / +$3…”.
- **Fila de pills glass:** círculo con 🔍; “**%16.54 Total APY, 12 pools**”; otra pill a la derecha.
- **Lista de pools (pills apiladas, vidrio):** “USDVC Prime — Morpho — 15.45% APY — 40% Allocated” (iconos ETH/BTC), “Renzo Restaked ETH — Morpho — 13.2% APY — 40% Allocated”, “M11C Level lvlUSD — 22.55% APY — 20%”.
- Frase ancla: “Your portfolio keeps thinking even when you don't.”

**Reglas que enseña:** esferas/orbes como objetos de estado (loading = eclipse); cifras de APY alineadas a la derecha en columna; pills de vidrio oscuro con bordes suaves; copy de producto con carácter (“keeps thinking even when you don't”).

### IMG_8204 — «Acme» (workspace IA dark)
**Familia:** app IA dark · **Formato:** vertical con foto de bosque + glow rojo.

- **Ventana con semáforos macOS** sobre fondo de árboles desenfocados con resplandor rojo.
- **Sidebar oscura:** logo “Acme” + switcher (⇅); búsqueda con `⌘K`; grupos: **WORKFLOW** (Workspace activo resaltado con pill, Projects, Collaborators, Insights, Workflows, Repos), **SUPPORT** (Documentation, Help center), **EXTENSIONS** (Claude, Perplexity, Cursor con sus logos).
- **Main:** header “⊞ Workspace”; hero centrado: “Hi, Stephen 👋” (gris) + “**What are we bui[lding]**” grande blanco.
- **Input card:** “Outline your product, fl…” + botón “+”; links “Sync my calendar / Crea…”
- **Sección “Build environment”** + “Connect tools, automate workflows.”; dos tarjetas de imagen (espiral azul, persona trabajando).

**Reglas que enseña:** sidebar con grupos y item activo tipo pill; saludo personal + pregunta grande; input como área de trabajo con acciones inline; “extensions” con logos de terceros como prueba de ecosistema; glow de color detrás del vidrio.

### IMG_8205 — Chat IA dark (command/ask bar)
**Familia:** IA dark · **Formato:** horizontal.

- Fondo negro casi puro; **logo fantasma** (blob con cara) al 8% de opacidad, centrado arriba.
- **Input grande redondeado (28px):** “🔍 Solve a math problem…” con cursor; línea interior “**＋ Add tabs or files**”; derecha: 🎙 icono y **↑ en círculo blanco** (enviar).
- **Fila de skills/slash-commands debajo:** “○ / future-self”, “**／performance-review**” (pill seleccionada), “/ Research”, “＋ New Skill”, “⋯”.
- **Toast**: “**You've got 5 invites!** — As an early tester, we trust your instincts. That's why we've given you 5 Dia invites.” con dos imágenes mini y gradiente naranja→oscuro, cerrar `×`.
- Cursor de mouse visible (captura real).

**Reglas que enseña:** command bar central con ghost de logo detrás; slash-commands como pills (una seleccionada); toolbar mínima (voz, enviar); toast con gradiente cálido y tono conversacional (“we trust your instincts”).

### IMG_8206 — Modal «New Feature: Dark Mode Support»
**Familia:** modal dark · **Formato:** horizontal 16:9 sobre foto de rocas.

- Card oscura `#1F1F22` redondeada (~16px) con sombra; **icono de regalo fantasma** al 10% abajo-derecha.
- “**New Feature: Dark Mode Support**” (blanco, semibold) + `×`.
- Texto: “We've added a beautiful dark mode to improve your experience during those late-night sessions.”
- Botón “**See What's New →**” (oscuro con borde 1px) centrado a la izquierda.

**Reglas que enseña:** modal de novedades = título corto + 1 frase + 1 CTA con flecha; watermark de icono temático (regalo); sobre foto de fondo para dar contexto.

### IMG_8207 — Empty state «Your watchlist is empty»
**Familia:** empty state dark · **Formato:** vertical.

- Fondo negro. **Card central** con **skeleton fantasma** de una lista real (estrellas, círculos de token, barras de texto, pills con chevron ▾) en grises 10–15% de opacidad.
- Mensaje: “**Your watchlist is empty**” (bold blanco) + “Start building your crypto watchlist by clicking the button below” (gris).
- CTA: “**＋ New asset**” pill blanca.

**Reglas que enseña:** el empty state muestra la estructura futura (ghost) + 1 CTA claro; blanco sobre negro sin más decoración; “＋” dentro del botón.

### IMG_8208 — «Complexity turned into Simplicity» (IA de documentos)
**Familia:** landing IA minimal · **Formato:** horizontal 4:3.

- Fondo crema `#F4F1EC` con **veladuras de líneas suaves** (bokeh de dibujo técnico).
- Titular **serif** centrado: “Complexity turned into **Simplicity**” (Simplicity en itálica).
- **Card flotante horizontal:** pila de **3 hojas de documento asomando** por arriba; dentro: chip “**3 files**”, placeholder “Summarize, rephrase, convert…”, iconos finos (sliders, clip) abajo-izquierda, **botón circular negro con →** abajo-derecha.
- Caption gris centrado: “Complex bureaucracy just got simple. Add any files, give any task. Watch it get done in seconds.”

**Reglas que enseña:** hey IA sencilla = 1 titular serif poético + una sola card con gesto visual (papeles) + CTA circular; nada de features list; tipografía serif humaniza el producto.

### IMG_8209 — Widget de ayuda dark
**Familia:** widget help · **Formato:** vertical sobre foto de cañón.

- Panel dark redondeado (20px) flotando a la derecha.
- Logo de burbuja de chat blanco + `×`.
- “Evening Shayan.” (gris) / “**How can we help?**” (blanco grande).
- Menú de acciones con iconos + chevron: “♥ Get Started” (**fila resaltada**), “💬 Ask a question”, “📖 Documentation”, “⭐ Help Guides”.
- **Botón pill flotante “Help”** (blanco, esquina inferior-derecha).

**Reglas que enseña:** saludo contextual (“Evening…”) + pregunta; opciones como lista con icono y chevron; una opción preseleccionada/hover; launcher pill pegado al borde.

### IMG_8210 — Spec/redline de chat input
**Familia:** documentación de diseño · **Formato:** 1:1 (fondo oscuro).

- Vista de un input de chat **con anotaciones de medidas**: círculos naranja “16” y verde “8” en la parte superior, “16” a la derecha, líneas rojas de margen, líneas punteadas verdes internas, etiqueta “**40**” junto al botón.
- Contenido del chat: barra “← / Ask follow-up… / →(blanco)”; chip “**Make 🍔 dance excitedly ▾**”; estado “3D animation 12s” con puntos animados azul/amarillo; texto “Your social video package is ready; just hit Publish.”; **icono carpeta 3D azul** “3D Renders — 8 items · 226,4 MB”; barra inferior “**→ Publish**” + select “Sonnet 4.6 ▾” + “40”.

**Reglas que enseña:** especificar paddings (16/8/16), gap interno 8, altura de controles y márgenes con redlines; estructura de respuesta IA con “paquete de assets”; select de modelo inline; botón de acción con flecha.

### IMG_8211 — Design tokens (grises, AAA)
**Familia:** tokens · **Formato:** 1:1 (dos mitades).

- Mitad superior “**Light**” + badge “**AAA Pass**”; grid 6×2 de swatches con hex + step: `#FFFFFF Base, #FAFAFA 50, #F5F5F5 100, #E5E5E5 200, #D4D4D4 300, #A3A3A3 400` / `#737373 500, #525252 600, #404040 700, #262626 800, #171717 900, #0A0A0A 950`.
- Mitad inferior “**Dark**” invertido: `#000000 Base, #0A0A0A 50, #171717 100, #262626 200, #373737 300, #525252 400` / `#8A8A8A 500, #A3A3A3 600, #D4D4D4 700, #E5E5E5 800, #F5F5F5 900, #FAFAFA 950`.
- Cada swatch: rectángulo redondeado (8px) + hex en bold + step en gris.

**Reglas que enseña:** usar esta escala como única fuente de grises; validar contraste AAA; documentar tokens exactamente así (nombre hex + step).

### IMG_8212 — Paleta + escala tipográfica de marca
**Familia:** brand board · **Formato:** casi 1:1.

- **3 columnas superiores:** “Alabaster `#FAFAFA` (rgb 250,250,250)”, “Silver Chalice `#ADADAD` (173,173,173)”, “Concord `#7E7E7E` (126,126,126)” — swatch grande con nombre+hex+rgb.
- **Fila 2:** “Black Cow `#454545` (69,69,69)”, “Gluon Grey `#1E1C1C` (30,28,28)”, “Onyx `#0E0E0E` (14,14,14)”.
- **Bloque tipográfico negro:** “**Overused Grotesk**” repetido en escala descendente con especímenes: `270px Heading XL · 77px Heading Large · 48px Display XL · 31px Display Large · 19px Paragraph Regular · 15px Paragraph Small`; nota “Typefaces: Overused Grotesk (Display Sans Serif) / Exponent (Sans Serif)”; “Essential” en la esquina; guía “H1-0 max-width 1240px”.

**Reglas que enseña:** el sistema base es: 6 tonos con nombre + 2 tipografías + 6 tamaños + ancho 1240px. Aplicarlo tal cual produce el “look” de este set.

### IMG_8213 — Glassmorphism: Frosted / Clear / Blur
**Familia:** exploración de material · **Formato:** horizontal.

- Fondo: foto desenfocada con reflejos (persona en escritorio, cuadernos, latas) — fondo a propósito caótico para probar el vidrio.
- **Rectángulo grande “Frosted / Concept”:** blur fuerte + tinte gris oscuro, esquinas ~28px, texto blanco.
- **Card izquierda “Clear / iOS”:** vidrio limpio, blur bajo, **borde blanco fino brillante** (highlight de canto), más nítido.
- **Card derecha “Blur / One UI”:** blur medio + **tinte beige cálido**, más suave/lechoso.

**Reglas que enseña:** nombrar los 3 materiales y sus parámetros (blur, tinte, borde); usar Clear para iOS, Blur cálido para Android/One UI, Frosted para overlays de marketing; validar el vidrio SIEMPRE sobre fondo complejo.

### IMG_8214 — «Unreal Engine» (hero con guías)
**Familia:** hero de campaña · **Formato:** 3:4.

- Foto: colina de hierba alta con **silla de madera de perfil** en la cima, cielo azul con nubes.
- **Retícula de guías de cámara visible:** círculos concéntricos, líneas de tercios, cruces `+` blancas en esquinas y centro; marco fino blanco; “**Let's do it**” micro a la izquierda; badge “(u)” del logotipo Unreal a la derecha del titular.
- **“Unreal / Engine” blanco gigante**, con la silla **por delante de las letras** (la imagen tapa parte del texto).
- Abajo: “Unreal Engine'da yaratilgan virtual sahnalardan zavqlaning!” (uzbeko) blanco.
- Base: riel de flechas “→ →” (carrusel).

**Reglas que enseña:** mezclar texto y foto con oclusión real (la silla delante); exhibir la retícula de composición como parte del diseño; titular 2 líneas centrado; flechas de carrusel como pie.

### IMG_8215 — «Railroad.ai» (waitlist)
**Familia:** landing IA · **Formato:** horizontal.

- **Foto:** vista desde el interior de un tren antiguo con el **paisaje enmarcado por la ventana** (montañas, campo, nubes) — la ventana es el “viewport” del hero.
- Nav pill glass arriba-centro: “How it works? · Pricing · Products · Blog”; izquierda logo “Railroad.ai”; derecha “**Get Started**” blanco pill.
- Pill “**100+ people subscribed**” encima del titular.
- Titular oscuro centrado: “**Focus in a Constantly Distracted World**”; sub: “Cut through the noise of notifications, endless feeds, and constant interruptions. Learn how to reclaim your attention and do meaningful work that truly matters.”
- **Input combinado:** “Enter your email” + botón blanco “**Join Waitlist**”.

**Reglas que enseña:** escenario narrativo (tren = viaje/enfoque); el titular vive DENTRO del paisaje; prueba social mínima en pill; captura de email como objeto único; nav en glass sobre cielo.

### IMG_8216 — «BridgeAI»
**Familia:** landing IA · **Formato:** horizontal.

- Foto: valle verde con niebla y **puente de piedra** en el centro.
- Nav: “BridgeAI™” izquierda; pills “Mission / How it Works / Pricing” + “**Book a Demo**” negro; derecha “New Account ↗ · Login”.
- **Titular verde serif-style:** “Bridge the gap between **data and decisions**” (2 líneas, la segunda en tono más claro).
- Sub: “Turn disconnected data into actionable insights with AI-powered automation.”
- **Abajo-izquierda:** icono “**BridgeCore™**” + párrafo: “BridgeAI seamlessly connects your business tools, automating data flow across platforms without the need for complex coding.”; CTA “Book a Demo” (negro) + “Learn More”.
- **Abajo-derecha:** “How it works? 1:02” + miniatura verde de video con play.

**Reglas que enseña:** metáfora física (puente = integración) y el titular la nombra; dos CTAs (primario/ secundario); ficha del producto (BridgeCore™) como pieza editorial; video con duración.

### IMG_8217 — «Step Through. Work Smarter.» (IA)
**Familia:** landing IA · **Formato:** horizontal.

- Foto: cañón rojo/negro al amanecer con **dos monolitos gigantes** y **luz entre ellos** (portal).
- Nav caps blanco espaciado: FEATURES · SOLUTIONS · HOW IT WORKS · [logo] · PRICING · RESOURCES · GET STARTED.
- **Titular 3 líneas:** “Step Through. Work Smarter. / Cross the threshold into **AI-driven efficiency.**” (más fino en la 2ª línea).
- Micro-caps izquierda: “A SYSTEM THAT LEARNS, ADAPTS, AND ACCELERATES YOUR SUCCESS.” (con línea roja bajo el titular).
- Derecha, 2 párrafos pequeños: “Step into the future of automation…”; “AI that doesn't just assist—it anticipates, learns, and executes with precision.”

**Reglas que enseña:** atmósfera épica (portal) + copy de umbral (“threshold”); capas de texto: titular grande + micro-caps + 2 párrafos de apoyo a la derecha; nav todo caps con logo al centro.

### IMG_8218 — Hero concept «Your Next Adventure Starts Here»
**Familia:** hero de presentación · **Formato:** 1:1 (slide con marco).

- Slide en blanco con **marco interior**; dentro: paisaje al atardecer (colinas, agua, niebla), **silla amarilla dentro del agua** como objeto solitario.
- Overlay blanco centrado: isotipo simple, “**Your Next Adventure Starts Here**” (2 líneas), sub “Discover hidden gems, plan unforgettable trips, and explore the world — all in one seamless app.”, botón “Download Now”.
- Nav minúsculo arriba: “Home · Our Story · FAQ · Policies” (pills glass).
- Pie del slide: “HERO CONCEPT · · · ILLIA V. · · · 2025”.

**Reglas que enseña:** héroes de viaje = paisaje + objeto simbólico único (silla/bote); texto centrado con jerarquía 3 niveles; créditos de autor como en portafolio.

### IMG_8219 — «Creative Studio® · Thought Before Form»
**Familia:** estudio · **Formato:** 1:1.

- **Nav:** “Creative Studio®” izquierda; Home · Work · About · Philosophy; “Contact” derecha.
- **Izquierda:** “**Thought / Before Form.**” (2 líneas, negro, con punto).
- **Derecha:** párrafo “We craft meaning through form — a visual dialogue between intention and intuition, where brands are not just seen, but felt.”
- Línea de meta: “(025)” izquierda; “**Formless** — Brand Identity, Visual Curation” derecha (Formless en bold).
- **Imagen full-bleed:** dunas negras con cresta iluminada en naranja/rojo (con grano), etiquetas dentro: “**New York 10:39 AM**” abajo-izquierda; “**See More →**” abajo-derecha.

**Reglas que enseña:** declaración de filosofía en 2 bloques (frase corta + párrafo); numeración (025); una foto protagonista con hora local “en vivo”; flechas en el borde de la imagen.

### IMG_8220 — «Ruthway» (viajes sostenibles)
**Familia:** turismo eco · **Formato:** 1:1 (marco blanco).

- Nav pill centrada: Ruthway · Home · Adventures · Eco Impact · Gear & Tips · About Us · Contact.
- Micro-caps: “FOR THE SUSTAINABLE EXPLORER”; titular “**Discover hidden paths**”; sub “Unleash your adventurous spirit with unique journeys through the world's untouched landscapes.”
- Botones “Start Exploring” (negro) + “View Adventures” (claro).
- **Foto full-width:** valle verde con sendero serpenteante hacia la niebla.
- Fila de logos de partners en las rocas del pie: GARMIN · Petzl · SONY · Jeep.

**Reglas que enseña:** navegación-pill para temas eco; CTA doble; el sendero como metáfora (“hidden paths”); partners sobre la imagen (integrados, no en banda).

### IMG_8221 — «ATMA Wellness»
**Familia:** wellness · **Formato:** 4:3 (card flotante).

- Card con borde fino. Nav: “ATMA Wellness” (isotipo de piedras apiladas) izquierda; How It Works · Coaches · Programs · Pricing; “Get Started” glass derecha.
- **Escena:** árbol de olivo con hojas doradas flotando sobre montañas al amanecer (bruma).
- Titular blanco: “The Art of **Mindful** Living Platform” — **“Mindful” en otro estilo (itálica dorada)**.
- Sub: “A personal sanctuary to cultivate inner peace, emotional intelligence, and lasting resilience through science-backed practices.”
- Botones: “Begin Your Journey” (oscuro) + “Practice Now” (texto).
- Logos: Disney · Mindfulness · Blossom · Proline · Luminous (gris, con blobs de color suave).
- Se ven **líneas de guía blueprint** azuladas muy tenues (margen de 64px, columnas).

**Reglas que enseña:** highlighting de una palabra del titular (Mindful) con estilo/color; escena mística + luz cálida; logos apagados para no competir; guías de construcción visibles como textura sutil.

### IMG_8222 — «Hotle» (alojamiento Bali)
**Familia:** real estate/hospitality · **Formato:** página XXL.

- Nav pills: Home (negro) · Backyard · Works · Contact; derecha “Join the Waitlist” (outline).
- **“Hotle” display gigante** (casi caja del hero) con la **casa de madera oscura con luces encendidas** detrás/en medio.
- Micro-textos en las 3 posiciones: “Dream big. Live remote.” · “Masterpiece of Architecture” · “Space to Recharge like nowhere.”
- Bajo el hero: pills de filtro “Capsule · Cabin Modular · **Eco-villa** (activo)” + “Ubud, Bali” derecha.
- **Sección About:** “Stunning *architecture* for spaces where people *live*, *work*, and *chill*.” (las itálicas serif marcan el ritmo) + “About Us”; **render de cabaña de madera con techo metálico** a la derecha.
- Izquierda: “◆ CABIN MODULAR” + párrafo “Our signature model has the basics covered. Compact yet generous, efficient yet flexible…” + botón “Search my area”.
- **Stats:** “**120+** Experienced people | **15+** | **5+**”.
- Cierre: “**Comfort x Nature**” grande; izquierda “Choose space to rest”; derecha párrafo sobre simbiosis marca/diseño.

**Reglas que enseña:** display que se funde con la arquitectura; frases con itálicas intercaladas; filtros de catálogo con una opción activa; stats de experiencia; “x” como conector de conceptos (Comfort x Nature).

### IMG_8223 — «Visa Travels»
**Familia:** agencia de viajes · **Formato:** página XXL.

- **Hero foto:** cordillera (Himalaya) + estepa con **yurtas**; “**Travel**” blanco gigante; sub “Travel with intention. Discover retreats, active adventures, and boutique stays all in one place.”; nav: Visa Travels · Home Stories Destinations Community About us · derecha Sign in/Stories/Resources/Contact us.
- **Barra de datos** sobre la foto: 4 campos (Activity/Food: “Hiking, Yoga, Food Tasting”; Location; Date/Duration “August 2, 2025”; Budget “$50-$150”) + botón blanco “**Explore**”.
- Banda: “✈ We are Melail · ⭐ 5K+ People Satisfied” + flechas circulares.
- **Titular centrado:** “Visa Travels means **Going Places**” (2 líneas) con **línea punteada + pines de mapa** dibujados debajo.
- Bloque “◆ 03 Our Value”: “**Not Your Boring Travel Agent**” + “We plan chill, curated trips with good vibes and better people.” + “Book a Seat” negro.
- **3 cards de destino escalonadas:** Panglupitan (colinas verdes), “Bangli, East Bali — Cultural walk with local guides”, Uluwatu (perro negro), yurtas blancas; pills “Prev/Next”.
- **Sección “◆ Popular Destination 2025 / Pick the Place”** + “We have great options for everyone and cozy spots for your squad to enjoy together.”
- **Barra de filtros**: Destination (Find a spot…), Category (Select type), Price (Select range budget), Date (Select date range) + “Confirm” (lupa).
- **Cards de tour:** “Uluwatu — Badung Regency, Bali · ⭐4 Star left” con foto, overlay “$35.00 · Open Trip · 12-11 August”; “Toba Lake — Sumatra · ⭐5”; “Sumba Adventure — West Sumba” con badge “Sold Out”; bajo cada card specs: “Accommodation: 2N at LakeSide Villa / Transport: Private car / Meals: Full board”.

**Reglas que enseña:** hero con barra de datos de reserva (los datos venden); dashed line + pines como adorno funcional; tono anti-corporativo (“Not Your Boring Travel Agent”); cards con precio/duración en overlay y specs abajo; filtros como formulario horizontal.

### IMG_8224 — «SOLTERA» (energía eólica)
**Familia:** industria/energía · **Formato:** página XXL.

- **Nav glass:** logo sol, EN/SP, Home · Benefits · Product · How it works · Clients · Reviews · Contact us; “Search” (lupa) + carrito “0” circular + “Get in touch” negro.
- **Hero:** “**SOLTERA**” blanco gigante sobre campo verde con aerogeneradores; “**POWER YOUR FARM SMARTLY**” (2 líneas) con botón circular de globo; izquierda: “Wind energy is more than a trend. It helps reduce costs and gives your farm full independence today.”
- **Tarjetas glass sobre la foto:** “**1.5M+ WIND POWER UNITS** — Teams trust us to power their work with wind across all seasons reliably.” (con foto de turbina) y “**10+ YEARS** — A decade of expertise in efficient and clean energy.”
- **Sección 01 “◆ THE BENEFITS OF WIND POWER”:** titular “Choose us to reduce operational costs and gain energy independence…” + párrafo gris; CTA “Get in touch →” negro.
- **Dos cards métricas:** “**5MW** CAPACITY” (foto colinas + turbinas) y “**30%** COST REDUCTION” — cada una con párrafo y numeración `01/02` en esquinas.
- **Sección 02 “◆ ENGINEERED FOR PERFORMANCE”:** titular + CTA; **foto grande del hub de una turbina** con cita overlay: “Innovation and stability in every turbine we build to power your farm's business” (marcada `01`); debajo dos cards: “DURABILITY / Reliable wind turbines designed to deliver stable and consistent performance…” y “RELIABLE TECH / Smart control systems ensure efficient operation and long-term operational stability…” con icono `+`/engranaje.
- **Sección 03 “◆ HOW IT WORKS (STEP BY STEP)”:** titular “We deliver a complete process from planning to launch with consistent results…”; **card “01 INITIAL CONSULTATION”** con foto de dos ejecutivos y párrafos subrayados.

**Reglas que enseña:** cifras como titulares de card (5MW, 30%, 1.5M+); secciones numeradas con ◆; una cita overlay sobre la foto clave; pasos con “01 …” y descripción larga subrayada; glass sobre paisaje para datos de confianza.

### IMG_8225 — CRM «Acme Labs» + modal «Unlock Conduit AI»
**Familia:** SaaS CRM · **Formato:** 4:3 (captura con modal).

- **Fondo (blur):** app de CRM con breadcrumb “Companies / Database”, toolbar: “All companies ⌄ · ⇅ Sort · Filters · Columns setting · Add to Attio · **New Company** (negro)”; tabla con logos de empresas (ClickUp, OpenAI, Trado, Slack, Aera, Zoom, Disney, Nvidia, Figma), columnas Revenue/Funding con cifras.
- **Modal central:** imagen superior con **gradiente verde-teal + logo de flor blanca** (marca Conduit); título “**Unlock Conduit AI**” + chip rojo “**Private Beta**”; texto “Run your agents over phone calls — same instructions, same tools, just voice. **Leave us a 0.2 review to unlock.**”; botones “Leave a review” (negro) + “Maybe later” (texto).

**Reglas que enseña:** modales de upsell con imagen de marca arriba y 1 requisito claro (review); chip de estado “Private Beta”; el fondo siempre es la app real difuminada; CTA primario + escape “Maybe later”.

### IMG_8226 — Widget «Spellar» (calendario macOS)
**Familia:** widget macOS · **Formato:** horizontal sobre wallpaper de montañas.

- Barra superior de la app: “5 min • Spellar calendar” + iconos (wifi, búsqueda, campana, portapapeles).
- **Widget dark:** columna izquierda “Spellar / **Next Meeting in 5 min**” + pill blanca “⏺ Start recording”; lista “Today”: Spellar Demo 10:00-11:30 (Online), Spellar Widgets 16:00-16:30 (Online) — cada item con **barra de color** (verde/naranja) y hora; Product meeting 15:30-16:00 · Video call; Spellar Sprint 17:30-18:00 · Video call.
- Columna derecha: mini-calendario “October” con día 23 en rojo.

**Reglas que enseña:** widget de agenda = próxima reunión arriba + botón de grabación + lista con barras de color; texto blanco/gris sobre `#1C1C1E`; el wallpaper hace el color.

### IMG_8227 — «Start in Mail…» (command bar macOS)
**Familia:** command bar · **Formato:** horizontal sobre dunas verdes.

- **Barra central glass:** icono de Mail azul + “Start in Mail…” + chip azul “**5 tools**” + “＋” circular; debajo, fila de iconos finos: persona, carpeta, imagen, documento, clip, onda de voz.
- **Popover superior:** “Computer can” con checklist: ✓ Compose Emails, View Mailboxes, ✓ Read Emails, ✓ Search Emails, Read Window Context (checks azules en los activos, chevrons en los pasivos).

**Reglas que enseña:** command bar = campo + contador de herramientas + acciones secundarias en fila; capacidad de la IA explicitada en popover con checks; todo en vidrio sobre paisaje minimal.

### IMG_8228 — Widget notch «Nook / Tray» (macOS)
**Familia:** widget notch · **Formato:** 9:16 (notch sobre wallpaper de trazos pastel).

- **Pill en el notch:** tabs “Nook | Tray”; izquierda reproductor: álbum (silueta azul) + “**Stargazing** / Myles Smith” + icono Spotify verde + controles ⏮ ▶ ⏭.
- Derecha: “**Jul**” + semana 23-29 con **26 (Wed) resaltado azul**; icono calendario; “Nothing for today”; engranaje arriba-derecha.

**Reglas que enseña:** el notch es una superficie de UI (música + calendario); dos columnas equilibradas; selección en azul del sistema; fondo wallpaper pastel de pinceladas.

### IMG_8229 — Concepto iPhone «lateral» (3 vistas)
**Familia:** concepto hardware · **Formato:** 1:1.

- Tres perfiles de iPhone pegados, mostrando **la franja negra del lateral** como UI gigante con iconos apilados.
- Vista 1 (gris): **control deslizante de volumen gigante** (mitad blanca) con icono de altavoz — el botón físico como slider.
- Vista 2 (plata): franja con **🔕 rojo tachado + “SILENT”** y campana abajo.
- Vista 3 (oliva): **luna morada, persona morada, icono de retrato cian + “WORK”** (modos/perfiles); micro cámara.
- Wallpapers metálicos con reflejos suaves; crédito “@upinthezone on X/Twitter”.

**Reglas que enseña:** explorar el hardware como lenguaje de iconos de estado; color por modo (rojo silencio, morado pessoal, cian cámara); minimalismo de materiales metálicos.

### IMG_8230 — «Design and Eng For SAAS Startups»
**Familia:** foto-tipografía · **Formato:** horizontal.

- Marco natural: **copas de árboles verdes** alrededor de un óvalo de cielo azul (foto tomada hacia arriba).
- **Texto negro centrado dentro del cielo:** “Design and Eng For **SAAS Startups.**” — la segunda línea en otra tipografía (serif display en caps).
- Debajo: “Trusted by fast growing startups” + logos: watchup, Salvesive / ScribeAI, Salesbase, Venn (negro, con iconos).

**Reglas que enseña:** usar la naturaleza como marco tipográfico; mezclar 2 fuentes dentro del mismo titular; prueba social mínima justo debajo.

### IMG_8231 — Widget notch dark (registro horario)
**Familia:** widget notch · **Formato:** horizontal sobre fondo azul/negro.

- Panel dark glass (24px) con profundidad (capas detrás).
- “**Good evening**” (sans redonda, blanca) + pill de fecha “☀ Tue 18. Oct, 19:22”.
- Card “**Yesterday** · 09:42 → 16:45” con icono de calendario-reloj (zona de toque).
- “This week”: fila M T W T F S S (T seleccionada con recuadro).
- Cards de métricas: “**Total session time** · 7h 2m · ↘ -30h 47m” (icono reloj) y “**Latest clock out** · 16:45 · ↘ from 13:02” (icono luna).

**Reglas que enseña:** resumen personal (“Good evening”); ayer/hoy/semana como bloques; cifras grandes + delta con flecha y color; el widget corta a propósito en el borde (entra/sale).

### IMG_8232 — Widget «Coming Up» (reuniones dark)
**Familia:** widget reuniones · **Formato:** vertical.

- Fondo negro; **efecto de pila de cards** (varios bordes asomando arriba y abajo).
- Header “🕐 Coming Up” gris; card: “**AI Exploration Sync**” blanco + “**Details ↗**” (borde suave) derecha; “11:00 - 11:30 · **in 2 minutes**” (naranja).
- **Avatares apilados** en pill: “5 invited · 3 accepted”.
- **Caja de contexto** (borde punteado): “✨ Context: The last meeting emphasized AI's role in digital applications, showcasing its capacity to streamline processes and improve user experiences with personalized suggestions.”
- Botón ancho “**Join meeting**” (outline claro).

**Reglas que enseña:** el widget anticipa la reunión con contexto generado; pila de cards para indicar cola; tiempo relativo en acento; jerarquía: título → hora → gente → contexto → acción.

### IMG_8233 — Widget calendario light (Noviembre)
**Familia:** widget iOS claro · **Formato:** 4:3.

- Card blanca crema minimal (radio ~28px): “November” centrado; días M T **W** T F S S (W en rojo); números 1–7 con **puntos** debajo de 1/5/6; **3 seleccionado en círculo rojo**.
- Eventos: “**Discuss health plan** — 3 PM · Jenny Wilson” (avatar con punto verde), “**Plan a movie night with friends** — 4:20 PM · Jacob Jones” (avatar apagado, texto más gris), cada uno con chevron >.
- Paleta: blanco hueso `#F5F2EE`, rojo suave para acentos, tipografía redondeada.

**Reglas que enseña:** widgets iOS = fondo crema, radios enormes, acento rojo mínimo; eventos con avatar + hora + persona; estado activo/pasado por opacidad; dots de densidad.

### IMG_8234 — Formulario de contacto «Let's talk! 🤙»
**Familia:** web studio · **Formato:** 1:1 (artwork + card).

- **Fondo:** pintura digital colorida tipo storybook (montañas nevadas, pradera de flores, esferas flotantes). Nav: logo + “Who we are · Services · Case studies · Blog” + “**Get in touch**” negro.
- **Card blanca derecha:** “**Let's talk! 🤙**”; “Mail us at / **hello@pixelperfect.com**” + 4 iconos sociales cuadrados (X, Instagram, Dribbble, LinkedIn); “**OR**”; “Leave a brief message”: inputs “Your name”, “Email”, textarea “Briefly describe your project idea...”; “I'm looking for...” con **chips seleccionables** (Website activo con borde negro, Mobile App, Web App, E-Commerce, Brand Identity, 3D & Animation, Social Media Marketing, Brand Strategy & Consulting, Other); botón negro “**Send a message**”.
- Pie sobre el arte: “We can turn your dream project into *reality*” (itálica serif).

**Reglas que enseña:** formulario como card única con secciones separadas por “OR”; chips multi-select para el brief; email real + redes; el arte vende el estilo del estudio; frase final con itálica poética.

### IMG_8235 — «Traffic Management» (dashboard transporte dark) — vista mapa
**Familia:** dashboard dark industrial · **Formato:** vertical (mockup monitor, marca RON R).

- **Sidebar colapsada:** logo + “Live Map” (pill activa), Fleet, Routes, Analytics, Maintenance, Incidents, Crew.
- **Panel izquierdo:** filtros “24 Bus · 100 Taxi · 12 Trains · 13 Trams”; “Online 12” (punto verde) / “Offline 4” (punto rojo); “**Operational Efficiency 78.3%**” + **line chart** con eje 06:00→21:00 y objetivo +80%.
- **Tarjetas de flota** (grid 2×2): “**Bus 6023** · 01.03.2026, 11:23:13 AM · Online · 📶4G · 🛰GPS · LTE · 06AM—11PM” con miniatura del bus, ruta y **barra de batería/progreso**; equivalentes: Bus 4120, Bus 2209, E-Bus 07.
- **Mapa** (terreno satélite oscuro con rutas verde/azul y pins): título “**Traffic Management**” + selects “Bus 6023 ⌄ / Map 2 ⛶”; card flotante “**Passenger Load 87%**”; controles ⊕ ⊖ ⛶.
- **Tabla “Schedule Offset”:** “**±2.5 min** Average Variance”; columnas L1, L12, L13, L15, L24; filas de bus “46623: -2min, +0min, -13min, …” con barras de progreso y valores en naranja/verde.

**Reglas que enseña:** dashboard industrial = mapa a sangre + panel de control flotante; filtros por tipo de vehículo con conteo; eficiencia como KPI principal; tarjetas de flota con telemetría (conexión, ruta, batería); tabla de desviaciones con cifras de color.

### IMG_8236 — «Traffic Management» — vista alertas
- **Mapa full** (mismo estilo) con **zona de influencia punteada** alrededor de un bus.
- **Panel derecho “Warning”** (colapsable): “**Capacity Issues (2 lines)**”; alerta roja “**−180 passengers left behind** · 4m ago · Affected stations: Central Station (115 passengers waiting) / University Campu (65 passengers waiting) · **Recommend: Dispatching reserve E-Bus**”; “**Schedule Deviations (Route 14)**”: “**Bus 4120 is 15 mins behind schedule** · 12m ago”.
- **Bottom card “Live Passenger Volume”:** “**142,580** today” + bar-chart por franjas horarias: 55k · 57k (+6%) · 56k · 55k (0%) · 52k (-12%) · 55k …, con **columnas sombreadas con patrón de rayas** y líneas de referencia.

**Reglas que enseña:** alertas con causa, tiempo, afectados y recomendación (no solo “error”); volumen en vivo como cifra única; chart de barras con patrón para diferenciar columnas; el panel de alertas es flotante y prioriza por color.

### IMG_8237 — Tip «Better Nested Border Radius»
**Familia:** tip de diseño · **Formato:** vertical.

- Fondo blanco. Créditos: “**@alenn.design** & **@ui.aida**” con avatares.
- Titular black gigante: “**Better Nested Border Radius**”.
- **Dos diagramas comparativos:** ❌ izquierda “outer r = inner r” (card con 24px exterior y frame interior 24px sin corrección) con **X roja** y etiqueta “outer r = inner r”; ✅ derecha misma card con “**24px**” exterior (naranja) + guía “**8px**” (azul) y frame interior “**16px**” (verde) + check verde, etiqueta “outer r = inner r + padding”.
- Texto: “Works if both radius have the same center point. Or use a multiplier. To test, scale up your inner frame to the size of your outer frame.”
- Pie: “Follow us for more content like this 🤩”.

**Reglas que enseña:** ✅/❌ lado a lado; colorear cada radio (naranja/verde/azul) para explicar la fórmula; fórmula explícita; CTA de seguimiento.

### IMG_8241 — Tip «Bad vs Good Typography»
**Familia:** tip de diseño · **Formato:** vertical (fondo de puntos).

- Titular: “**Bad** vs **Good** Typography” (Bad rojo / Good verde).
- **Dos cards iguales** (foto de lago al atardecer + Headline / Subheading / párrafo lorem + botones Secondary/Primary), anotadas con **líneas de medida punteadas**:
  - ❌ Bad: Headline 26px · Subheading 13px · cuerpo 11px · botones 18px (líneas rojas).
  - ✅ Good: 24px · 16px · 14px · 16px (líneas verdes).
- Card buena con borde verde; checklist: “● Set a clear Font hierarchy ● Balance Button Text ● Keep it Readable ● Use Consistent Scaling”.
- Pie: “**UXD** @UXDevotion · Save for Later 🔖”.

**Reglas que enseña:** reglas exactas 24/16/14/16; el error típico es cuerpo 11px y jerarquía arbitraria; usar checklists; footer con guardado.

### IMG_8242 — Tip «Create a clear visual hierarchy» (Practical UI)
**Familia:** tip de diseño · **Formato:** vertical.

- “**UI DESIGN GUIDELINE**” micro-caps + titular “**Create a clear visual hierarchy**”; párrafo: “Aim to present information in order of importance by making more important elements look more prominent…”.
- **Dos phones (Beach Getaway):**
  - ❌ Izquierda: lista `Name: / Type: / Price: / Location: / Rating: / Bedrooms: / Bathrooms: / Parking: / Description:` — todo con la misma voz; X roja sobre la foto.
  - ✅ Derecha: foto con contador “1/8”; “**Beach Getaway**” grande; “Blissful Beach, NSW, Australia”; “**★★★★★ 5.0 (38 reviews)**”; **atributos con iconos** (House · 2 beds · 1 bath · 1 garage); párrafo recortado; “**Book now**” azul; check verde.
- Esquina: libro “**Practical UI**” (portada morada) + avatar; “practical-ui.com”.

**Reglas que enseña:** prohibido label:value plano; convertir datos en atributos visuales (estrellas, iconos); un solo CTA de color; contador de fotos “1/8”; marca personal (libro/avatar) como firma del tip.

### IMG_8243 — Tip «UX Makover» (UXRishi)
**Familia:** tip de diseño · **Formato:** vertical.

- Marco: “Design tip” (izq) / “UXRishi” (der) arriba y abajo + “2025”.
- Titular “**UX Makover**” centrado.
- **Antes (rojo “Before UX”):** card con imagen pizza centrada, icono arriba-derecha, datos `Name:/Price:/Ratings:/Details:` a la izquierda, “ADD” rojo + “Customization” rojo abajo.
- **Después (verde “After UX”):** icono arriba-izquierda, imagen a la derecha, “**Margherita pizza**” bold + “**$15**” y “**⭐ 4.3**” en la misma fila, descripción a la izquierda con “**more…**” bold, divider, botón “**ADD**” rojo con sombra/glow + “Customization” en rojo.

**Reglas que enseña:** reorganización = título+precio+rating en una fila; elementos accionables con sombra de color; truncado elegante; imagen como bloque lateral (no centrado muerto); el “antes” siempre en rojo y el “después” en verde.

### IMG_8244 — Tarjetas «Iceland Cabin» (2 variantes)
**Familia:** tarjetas de alojamiento · **Formato:** horizontal (comparativa).

- **Variante clara (izquierda):** card blanca; foto arriba (cabaña de madera); “**Iceland Cabin**” bold; “$680 per night”; párrafo “Cozy cabin nestled in Iceland's breathtaking landscape, offering stunning views of mountains and Northern Lights.”; dos recuadros de dato “**Days 3**” y “**Rating 4.9**” (label arriba, valor grande abajo); botón negro full-width “Reserve”.
- **Variante oscura (derecha):** foto a sangre con **gradiente a negro** en la parte baja; “•••” arriba; pill “**$680**” frosted; “**Iceland Cabin**” blanco; descripción; chips “**Top Rated**” y “**5 day stay**” frosted; botón blanco full-width “Reserve”.

**Reglas que enseña:** mostrar las dos direcciones (light card vs foto-full-bleed); chips con la info clave (rating/duración) sobre foto; precio como pill; CTA full-width; párrafo idéntico en ambas para comparar solo el tratamiento.

### IMG_8245 — Tarjetas de vuelo «New York / San Francisco»
- **Izquierda (foto full):** card con la ciudad a sangre (NY con rascacielos), ♡ arriba-derecha, degradado oscuro abajo: “**New York**” blanco, “Economy” gris, fila “♡ from **$120** · ✈ JFK”, botón blanco pill “Search flight”.
- **Derecha (mixta):** foto de la Golden Gate arriba con bordes redondeados, cuerpo blanco: “**San Francisco**”, “Premium economy” gris, “♡ from **$240** · ✈ SFO”, botón **negro** “Search flight” + corazón en círculo outline a la derecha.

**Reglas que enseña:** dos layouts para el mismo componente (overlay vs split); precio destacado en negrita junto al icono de bolsa; código IATA como micro-dato; CTA domina la base; corazón para favoritos.

### IMG_8246 — Tarjeta de propiedad (glass oscuro) «Frosted Vally Estate»
- Card vertical elevada (radio ~32px) sobre fondo claro; foto de casa moderna.
- **Pill frosted superior:** “**Frosted Vally Estate · Norway**” + `×` a la derecha.
- **Degradado oscuro** desde la mitad.
- “**Property Features**” blanco; **chips frosted con iconos lineales**: 📶 Wifi · 🏙 City Skyline Views · 🏡 Outdoor Patio · 🏊 Outdoor Pool · 🚗 Free Parking · 🔥 Indoor Fireplace.
- Botón ancho frosted: “**View all 24 features →**”.

**Reglas que enseña:** features como chips de vidrio con icono fino; el contador “24 features” customiza el CTA; título en pill frosted como “etiqueta de objeto”; una sola foto de calidad.

### IMG_8247 — «Haven*» (real estate premium)
**Familia:** real estate · **Formato:** página larga.

- Fondo azul cielo muy suave en degradado; “**Haven\***” arriba-izquierda; `+` arriba-derecha (detalle).
- Hero: “**Extraordinary living begins here.**” blanco (2 líneas, tipo humanista/geometric light); sub “Timeless architecture, exclusive locations, and luxury homes designed to inspire your next chapter.”; **villa blanca minimalista** fotografiada (fachada, escalera exterior de vidrio).
- **Sección blanca:** titular “**Where your vision finds its [minifoto] home.**” — **una imagen incrustada dentro de la frase** (óvalo del paisaje); párrafo “Haven offers more than just a place to live—it's a space designed to reflect your unique style…”; **input de email + botón negro “Stay Updated”**.
- Segunda foto: otra villa con personas (cotidianeidad) al fondo de la página.

**Reglas que enseña:** azul cielo + blanco = lujo sereno; imagen recortada dentro del titular; solo captura de email (waitlist) como único form; asterisco como firma de marca (Haven*).

### IMG_8248 — «Stayli» (alquiler vacacional, móvil)
**Familia:** travel/booking · **Formato:** 9:16 móvil.

- Nav: logo “D Stayli”; Home · Listings · About Us · Blog Posts · Contact · Pages ▾; “**Get started**” negro.
- Hero: cielo azul; “**Discover your ideal vacation home today**” blanco; sub “Uncover a world of unique homes and unforgettable experiences. Your perfect getaway awaits just a search away.”; botón negro “**Book today**”.
- Foto: casa de madera en desierto con cactus y arena blanca, **fundida con degradado blanco** hacia abajo.
- Bloque: izquierda “Find the ideal spot for your next adventure.” (micro); derecha titular: “Discover the world's most extraordinary stays with Stayli. Whether you're planning a romantic getaway, a family vacation, or a business trip, we have the perfect space waiting for you.”
- Dos mini-columnas: icono maleta “**Remote Work Destinations** — Quiet spots with fast Wi-Fi, ideal for working in a new setting.”; icono familia “**Family getaways** — Comfortable spaces perfect for family memories.”; botón “**Explore**”.
- Abajo: dos cards de imagen (nuevas villas) asomando.

**Reglas que enseña:** el hero se funde con el blanco (transición suave); titular izquierda-par + statement derecha; casos de uso (trabajo/familia) con iconos; el listado real comienza justo abajo (continuidad).

### IMG_8249 — «ApexForm» (arquitectura industrial)
**Familia:** arquitectura dark premium · **Formato:** página XXL.

- **Nav:** “ApexForm®” izquierda; centro: micro-texto “We design high-performance industrial and commercial facilities optimized for operations, efficiency, and measurable business results.” + “**BOOK A CONSULTATION →**”; derecha “EN | UA” + hamburguesa.
- **Hero:** edificio oscuro de varias plantas al atardecer (terrazas con vegetación, luces cálidas). **“Industrial & Commercial” en serif itálica blanca gigante** cruzando toda la foto, superpuesta a los pastos.
- Fila de micro-labels bajo el titular: “ARCHITECTURE · DRIVEN BY · ENGINEERING PRECISION” (3 columnas separadas).
- **Banda de logos** en blanco/gris: iconos CONSTRUCTION, CONDON, **Morrison Construction**, más marcas (monocromo).
- **Sección negra:** statement centrado “*ApexForm* is not a traditional architectural studio®” (**ApexForm** en serif itálica, el resto sans); **render 3D flotante** de un edificio blanco de esquinas curvas con reflejoss; a los lados, **columnas de guiones/líneas** decorativas; pie: “We operate as a strategic partner for businesses that require precision, predictability, and performance from their built environments.” + “**BOOK A CONSULTATION →**” (caja).

**Reglas que enseña:** serif itálica gigante + foto oscura = “arquitectura de autor”; claim con “is not a traditional X studio®”; render 3D como escultura de la sección oscura; guiones laterales como textura técnica; CTA repetido idéntico arriba y abajo.

---

## 4. Recetas maestras (cómo combinar todo)

### Receta A — Landing de estudio creativo premium (blanco/negro)
1. Nav mínimo: logo wordmark + 4 links micro + 1 CTA pill negro con `→`.
2. Hero tipográfico: display gigante (una palabra, tracking -3%), imagen insertada entre palabras o foto a sangre con el display a caballo del borde.
3. Fila de micro-caps con datos (`(2026)`, `EST.21`, `@2019–26`) + logos clientes monocromos.
4. Statement centrado 2–3 líneas (max-width 1240) con label `( • Sección • )`.
5. Grid de proyectos masonry 2+1, cada card: foto + nombre abajo-izq + servicios abajo-der, un solo H3.
6. Lista de servicios tipográfica con activo negro / inactivos `#D4D4D4`.
7. Footer negro: nav repetido + legal + wordmark fantasma gigante recortado.

### Receta B — E-commerce editorial (GAZU/NORD/Zerouge)
1. Barra fina superior de envío/devolución (micro-caps) + nav con logo central.
2. Hero: modelo o producto + wordmark gigante como watermark detrás + claim corto + 2 CTAs (negro sólido + texto con línea).
3. Banda negra con 3 categorías (foto cuadrada + título caps + micro-link →).
4. Sección “NEW SEASON”: titular grande + sub + botón; foto lateral en luz dura.
5. Barra de 4 servicios con iconos lineales y línea superior.
6. “BEST OF X / VIEW ALL” + grid de producto con corazón.
7. Paleta: 1 base (crema o gris claro), 1 negro, 1 acento máx.

### Receta C — Web SaaS / IA con imagen de fondo
1. Nav pill glass centrado + botón “Get started” flotante.
2. Hero = paisaje o metáfora 3D a pantalla completa; titular centrado 2 líneas + sub 2 líneas + un solo campo (email) o CTA doble.
3. Pill de prueba social (“100+ people subscribed”), logos banda.
4. Sección datos: 3 tarjetas con número gigante (la central destacada con color), micro-copy de 2 líneas.
5. CTA final con el nombre del producto + 1 frase + botón.

### Receta D — UI dark (app/dashboard/widget)
1. Fondo `#0A0A0A`–`#171717` + una foto/glow de ambiente detrás del panel.
2. Paneles `#1C1C1E` radio 20–28px, borde 1px blanco 8%, sombra profunda.
3. Jerarquía: saludo/estado (gris) → título grande (blanco) → meta/cifras → acción pill blanca.
4. Glass para chips y barras; cifras tabulares alineadas a la derecha; estados con punto de color (verde online/rojo alerta).
5. Alertas con causa + tiempo + afectados + recomendación.
6. Empty states con skeleton fantasma + CTA “＋ …”.

### Receta E — Tarjeta de contenido (viajes/inmuebles/productos)
- Foto grande (radio 16–24) → título → meta 1 línea → fila icono+cifra (precio/rating) → descripción 2–3 líneas → 1 CTA full-width.
- Variantes: overlay completo (oscuro con chips) o split (foto arriba + cuerpo blanco).
- Nunca label:value; convertir todo en iconos, chips y tipografía jerárquica.

### Receta F — Slide de presentación (portada/catálogo/tip)
- Portada: logo-símbolo + metadata (fecha/versión/autor) arriba; display recortado por el borde inferior.
- Catálogo/menú: negro puro + Helvetica blanco en 4 zonas (marca, secciones, contacto, redes).
- Tip educativo: titular con palabra en color (rojo/verde), comparativa ❌/✅ lado a lado, checklist, crédito + follow.

---

## 5. Checklist final para IA + prompt maestro

### Checklist antes de entregar un diseño con este estilo
- [ ] ¿Hay **una** tipografía display gigante (≥72px) que domina una zona? ¿Se cruza con una imagen?
- [ ] ¿El sistema tiene **máx. 3 colores** + neutros de la escala? ¿Un solo acento?
- [ ] ¿Existen **micro-labels caps con 0.1em de tracking** (◆ ◦ ✳ + contador/paréntesis)?
- [ ] ¿Los CTAs son **pill negros/blancos con flecha** o texto subrayado?
- [ ] ¿Los datos son cifras grandes con label micro (`832`, `30%`, `±2.5 min`, `8m — 20m`)?
- [ ] ¿Los radios siguen **outer = inner + padding** (24/16/8)?
- [ ] ¿La jerarquía de texto de tarjeta es 24/16/14/16 o mayor, nunca label:value?
- [ ] ¿Hay prueba social mínima (logos monocromos o “100+ people”)?
- [ ] ¿Hay un detalle de personalidad: coordenadas, hora en vivo, versión `V 023`, chiste fino, 1 emoji dosificado?
- [ ] ¿El espaciado respira (secciones ≥96px, cards 16–24px de padding)?
- [ ] Si es dark: ¿glass con tinte correcto, sombra profunda y foto/glow de ambiente?
- [ ] ¿Footer con wordmark fantasma, numeración o badge circular?

### Prompt maestro (copiar-pegar para una IA)
> Diseña **[página/componente]** para **[marca]** con el estilo de la carpeta `Diseños` (leer `GUIA-DISENO-PARA-IA.md`). Reglas no negociables: base neutra `#FAFAFA` o `#0A0A0A`; un solo color de acento **[rojo/verde/azul/dorado]**; tipografía display grotesk gigante (tracking -0.03em, line-height 0.95) con **una palabra clave en serif itálica**; micro-labels en mayúsculas con tracking +0.1em y símbolos ◆/( )/01; CTAs pill con flecha; tarjetas con radio 24 exterior / 16 interior y padding 16–24; escala de grises Tailwind neutral (AAA); imágenes editoriales con grano o duotono; un detalle de personalidad (coordenadas, hora en vivo, contador). Estructura: nav mínimo → hero con display e imagen cruzada → statement centrado → grid editorial 2+1 o 3 columnas numeradas → datos con cifras gigantes → CTA final pill → footer con wordmark fantasma. Inspírate en las fichas **[IMG_#### y IMG_####]** para layout y atmósfera; mantén el copy breve, con actitud y sin relleno.

---

*Documento generado a partir del análisis visual de las 68 capturas de `~/Documents/Diseños` (67 diseños únicos; IMG_8181 duplica IMG_8179).*
