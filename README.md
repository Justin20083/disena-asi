# disena-asi — Skill de estilo de diseño

Skill con el estilo visual general de Justin: ADN cromático y tipográfico, layout
editorial, componentes, tokens obligatorios, recetas maestras y checklist de
pre-entrega. Incluye el "pensamiento permanente": toda IA que la instale debe
leerla antes de diseñar o programar cualquier pieza visual.

- **Repo:** https://github.com/Justin20083/disena-asi
- **Skill:** `disena-asi`
- **Fuentes:** carpeta `~/Documents/Diseños` (67 diseños únicos analizados)

---

## Instalación — prompt para pegar a tu IA (copia y pega exactamente)

> **Copia el bloque de abajo y pégalo en el chat de la IA donde quieras instalar la skill.
> La IA se encarga de clonar, instalar y configurar todo.**

```
Instala la skill "disena-asi" desde el repositorio https://github.com/Justin20083/disena-asi
siguiendo estos pasos y confirma cada uno antes de pasar al siguiente:

1. Clona el repositorio en una carpeta temporal:
   git clone https://github.com/Justin20083/disena-asi /tmp/disena-asi
   Si ya existe /tmp/disena-asi, haz `git pull` en su lugar.

2. Detecta tu plataforma y directorio de skills:
   - OpenCode: ~/.config/opencode/skills/disena-asi
   - Claude Code: ~/.claude/skills/disena-asi
   - Codex: ~/.codex/skills/disena-asi
   - Cursor: ~/.cursor/skills/disena-asi
   Si existen varios, instala en el que corresponda a la IA con la que hablo;
   si no estás seguro, pregunta al usuario cuál es.

3. Crea el directorio de skills si no existe y copia los archivos:
   mkdir -p <directorio>
   cp /tmp/disena-asi/SKILL.md /tmp/disena-asi/REFERENCIA-COMPLETA.md <directorio>/

4. Verifica que los dos archivos estén presentes (SKILL.md y REFERENCIA-COMPLETA.md)
   y reporta su tamaño en bytes.

5. Configura el "pensamiento permanente": añade una nota en tu memoria/contexto
   permanente (AGENTS.md, CLAUDE.md, reglas del proyecto o equivalente) que diga:
   "Antes de diseñar o programar cualquier pieza visual (web, landing, dashboard,
   app, tarjeta, slide, mockup, componente frontend, email, CSS/Tailwind), leer
   primero la skill disena-asi (SKILL.md y REFERENCIA-COMPLETA.md). Es el estilo
   general de Justin y se actualiza con el tiempo."

6. Limpia el clon temporal: rm -rf /tmp/disena-asi

7. Confirma al usuario: "Skill disena-asi instalada en <directorio>. Lista para usar."

No modifiques los archivos de la skill. No instales dependencias adicionales.
Si algún paso falla, detente y reporta el error exacto antes de continuar.
```

---

## Qué contiene

| Archivo | Qué es |
|---|---|
| `SKILL.md` | La skill: ADN visual, tokens obligatorios, recetas A–F, checklist pre-entrega, pensamiento permanente |
| `REFERENCIA-COMPLETA.md` | Guía completa ficha por ficha (67 diseños únicos de referencia) |
| `README.md` | Este archivo |

## Resumen del estilo (para que la IA lo entienda sin leer todo)

- **Base neutra extrema:** `#FAFAFA`/crema o `#0A0A0A`–`#171717`, **un solo acento**
  (rojo/verde/azul/dorado/ámbar). Sin gradientes multicolor saturados.
- **Display grotesk gigante** (tracking `-0.02 a -0.04em`, line-height 0.9–0.95) que a
  menudo se cruza con la imagen; **serif itálica** para la palabra "poética".
- **Micro-labels caps 10–12px** tracking `+0.08 a +0.18em` con `◆ ◦ ✳ ● +` o
  paréntesis `(2026)`, `01/02/03`.
- **CTAs pill con flecha** `→`/`↗`; chips/tags pill; nav pill flotante con blur.
- **Radius anidado:** `exterior = interior + padding` (ej. 24 / 16 + 8).
- **Tarjetas:** media → título → meta 1 línea → rating → specs con iconos →
  descripción → **1 CTA**. Nunca `Label: value`.
- **Glass:** Frosted / Clear iOS / Blur cálido con parámetros definidos.
- **Dark UI:** paneles `#1C1C1E` radio 20–28px, glow/foto ambiente, estados con punto.
- **Grises Tailwind neutral AAA.** Texto body mínimo `#525252`.
- **Recetas A–F:** estudio premium, e-commerce editorial, SaaS/IA, dark app,
  tarjeta, slide.

## Actualización

Este estilo es general y vivo: se irá actualizando con nuevo material de diseño.
Cada cambio se refleja en `SKILL.md` y, si aplica, en `REFERENCIA-COMPLETA.md`.
Para actualizar una instalación existente, vuelve a ejecutar el prompt de arriba
(o haz `git pull` en la carpeta de la skill).
