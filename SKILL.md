---
name: disena-asi
description: Estilo de diseño obligatorio de Justin. Usar SIEMPRE antes de diseñar o programar cualquier web, landing, dashboard, app, tarjeta, slide, mockup o frontend. Define paletas, tipografia, layout editorial, componentes, tokens y recetas maestras.
---

# Disena-Asi — Estilo de diseno obligatorio

> **PENSAMIENTO PERMANENTE PARA LA IA:** cada vez que vayas a disenar o programar
> cualquier pieza visual (web, landing, dashboard, app, tarjeta, slide, mockup,
> componente frontend, email, CSS/Tailwind), **LEE ESTA SKILL PRIMERO** antes de
> escribir codigo o proponer diseno. Es el estilo general de Justin y se actualiza
> con el tiempo: si existe `REFERENCIA-COMPLETA.md` junto a este archivo, leela
> tambien para el detalle ficha por ficha. Nunca disenes en otro estilo por defecto.

## 1. ADN (aplicar por defecto)

**Base neutra extrema:** blanco hueso `#FAFAFA` / crema `#F5F1EA` `#EFEBE4` **o**
negro `#0A0A0A`–`#171717`. **Un solo color de acento** por pieza
(rojo, verde, azul, dorado o ambar). Nada de gradientes multicolor saturados;
solo atmosfericos suaves (cielo, durazno→malva, salvia, dorado, marino) o
blob de gradiente con blur fuerte detras de la tarjeta clave.

**Grises (Tailwind neutral, AAA):**
Light: `#FFFFFF` `#FAFAFA` `#F5F5F5` `#E5E5E5` `#D4D4D4` `#A3A3A3` `#737373`
`#525252` `#404040` `#262626` `#171717` `#0A0A0A`.
Dark (invertido): `#000000` `#0A0A0A` `#171717` `#262626` `#373737` `#525252`
`#8A8A8A` `#A3A3A3` `#D4D4D4` `#E5E5E5` `#F5F5F5` `#FAFAFA`.
Paleta con nombre: Alabaster `#FAFAFA`, Silver Chalice `#ADADAD`,
Concord `#7E7E7E`, Black Cow `#454545`, Gluon Grey `#1E1C1C`, Onyx `#0E0E0E`.
Texto body minimo `#525252` sobre blanco.

## 2. Tipografia

- **Display grotesk gigante** (Anton / Helvetica Now / Overused Grotesk / Archivo),
  tracking `-0.02em a -0.04em`, line-height `0.9–0.95`, ocupa todo el ancho o se
  sale del lienzo. Con frecuencia **cruzado con la imagen** (texto delante o detras).
- **Serif italica como contrapunto:** la palabra "poetica" de la frase va en serif
  italica (ej: *Simplicity*, *reality*, *architecture*). Logos premium en serif
  Didone; logos modernos en sans heavy.
- **Micro-labels caps 10–12px, tracking +0.08em a +0.18em**, con prefijo
  `◆ ◦ ✳ ● +` o parentesis `(2026)` `(025)` `01/02/03`. Aparecen en CASI todo.
- Escala ref: Heading XL 270 · H Large 77 · Display XL 48 · Display Large 31 ·
  Parrafo 19 · Small 15. Ancho maximo **1240px**. Cuerpo nunca <14px.
  Botones 16px. Display line-height 0.95, titulos 1.05–1.15, cuerpo 1.5–1.6.
- **Numeros/cifras gigantes** como heroes de dato: `832`, `142,580`, `120+`,
  `5MW`, `30%`, `±2.5 min`, `78.3%`. Tabulares, sin decoracion.
- Detalle archivo como ornamento: `V 023`, coordenadas, `EST. 2024`, `© 2026`.

## 3. Layout y composicion

- Display gigante que se cruza con la foto (z-index mezclado).
- Grillas asimetricas editoriales: texto 2/3 + meta 1/3; masonry 2+1; 3 columnas
  `01/02/03` con alturas alternadas; filas de 3 tarjetas con central elevada.
- Franja negra full-width para producto/servicios dentro de pagina clara
  (y footer negro con wordmark fantasma gigante recortado).
- **Nav pill flotante con blur** + botones pill negros con `→`/`↗`.
- Tarjetas flotantes sobre foto con sombra `0 20px 60px rgba(0,0,0,.10)`;
  sutiles `0 2px 8px rgba(0,0,0,.06)`.
- Composicion centrada simetrica para heroes emocionales (titulo 1–2 lineas,
  sub 2 lineas, 1 boton pill, sobre imagen).
- Espaciado: secciones 96–160px; cards padding 16–24px; gaps 8/12/16/24/32/48;
  radios 8/12/16/24/999. Margenes desktop 32–80px.

## 4. Componentes

- CTA primario: **pill negro + flecha**. Variantes: outline 1px, blanco sobre foto,
  ghost con blur. Botones circulares con flecha; chips/tags pill (activo negro).
- Badge circular giratorio "GET IN TOUCH"; pills frosted glass sobre foto
  (`$680`, `Top Rated`, `1/8`); avatares apilados; inputs de 1 linea con accion
  dentro (email + Join); tooltips `⌘K` `⌘+Space`.
- Listas de servicios como **lista tipografica** (activo negro, inactivos
  `#D4D4D4`), no cards. Dividers 1px `#E5E5E5`. Tablas densas mono-caps.
- Fotografia editorial con grano sutil o duotono; B&N cuando hay acento de color.
  Iconografia lineal fina 1.5px, solo funcional. Maximo 1 emoji por pantalla.
- Copy breve con actitud. Datos "en vivo" (hora local, `in 2 minutes`, `4m ago`).

## 5. Tokens obligatorios

1. **Radius anidado:** `exterior = interior + padding` (ej: 24 / 16 + 8). Nunca
   iguales. Probar escalando el frame interior al exterior.
2. **Tarjeta:** media grande → titulo grande (1 vez) → meta 1 linea → rating
   estrellas → specs con iconos → descripcion corta → **1 CTA**. NUNCA `Label: value`.
3. **Glass:** Frosted (blur 20–40 + tinte oscuro 30–50% + borde blanco 10%) ·
   Clear iOS (blur 8–12 + borde 1px blanco 25% + sombra interna) ·
   Blur calido (blur 30 + tinte beige).
4. **Dark UI:** fondos `#0A0A0A`–`#171717` + glow/foto ambiente; paneles
   `#1C1C1E` radio 20–28px, borde blanco 8%; saludo gris → titulo blanco → meta →
   accion pill blanca; estados con punto (verde online / rojo alerta);
   alertas con causa + tiempo + afectados + recomendacion; empty states con
   skeleton fantasma + CTA "+ …".

## 6. Recetas (elegir una)

- **A · Estudio premium:** nav minimo → hero tipografico → micro-caps + logos B&N →
  statement centrado → grid masonry 2+1 → lista servicios tipografica →
  footer negro con wordmark fantasma.
- **B · E-commerce editorial:** barra micro envio → nav logo central → hero producto +
  wordmark watermark + 2 CTAs → banda negra 3 categorias → NEW SEASON →
  4 servicios con iconos → BEST OF + grid con ♡.
- **C · SaaS/IA con fondo:** nav pill glass → hero paisaje/metafora + titular 2 lineas
  + email o doble CTA → pill prueba social → 3 tarjetas dato (central destacada) →
  CTA final.
- **D · Dark app/dashboard:** fondo + glow/foto → paneles glass → saludo/estado →
  titulo → cifras → pill → alertas completas.
- **E · Tarjeta:** foto → titulo → meta → precio/rating → descripcion → 1 CTA
  full-width. Variantes overlay o split.
- **F · Slide:** portada = simbolo + metadata + display recortado por el borde;
  catalogo = negro + Helvetica en 4 zonas; tip = ❌/✅ + checklist + firma.

## 7. Checklist pre-entrega

Display gigante ≥72px cruzado con imagen · max 3 colores + 1 acento ·
micro-labels caps ◆/( )/01 · CTAs pill con flecha · cifras gigantes ·
radius outer=inner+padding · tarjeta 24/16/14/16 sin label:value ·
prueba social minima · 1 detalle personalidad (coordenadas, hora, `V 023`) ·
secciones ≥96px · dark con glass+glow · footer fantasma o badge circular.

Detalle ficha por ficha: ver `REFERENCIA-COMPLETA.md` en esta misma carpeta
(fuente: `~/Documents/Diseños/GUIA-DISENO-PARA-IA.md`, 67 disenos unicos).
