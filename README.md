# PFO2 — Prompt Engineering en Agentes de IA

**Tecnicatura Superior en Desarrollo de Software · IFTS N°29**
**Materia:** Desarrollo de Front End
**Comisión:** Lunes

---

## Datos del estudiante

| Campo | Detalle |
|-------|---------|
| Nombre | Sebastián Mombelli |
| Institución | IFTS N°29 |
| Carrera | Tecnicatura Superior en Desarrollo de Software |
| Materia | Desarrollo de Front End |
| Comisión | Lunes |
| Entrega | 26/06/2026 |

---

## Deploy unificado

🔗 **[Ver proyecto completo](https://pfo-2-prompt-engineering-agentes-ia.vercel.app/)**
> *(Link disponible tras el deploy en Vercel)*

---

## Descripción del proyecto

Se diseñó un único prompt de alta precisión siguiendo las guías oficiales de prompt engineering de **Anthropic** y **OpenAI**. El mismo prompt fue ejecutado en dos agentes de desarrollo de software distintos de forma completamente autónoma, sin modificación manual del código generado.

El resultado es una landing page **"Centro de Fans Argentinos"** — un portal dedicado a seguimiento, predicciones y comunidad alrededor de Argentina en la Copa Mundial 2026.

---

## Agentes utilizados

| Agente | Modelo | Razonamiento |
|--------|--------|-------------|
| OpenAI Codex | GPT-5.5 | Alto |
| Anthropic Claude Code | Claude Sonnet 4.6 | Default |

---

## Prompt utilizado

```
<context>
Eres un desarrollador web experto con más de 10 años de experiencia creando experiencias visuales impactantes e interfaces de usuario distintivas. Tu especialidad es HTML5, CSS3 y JavaScript vanilla de alto nivel. Este proyecto es para una práctica académica universitaria donde se evaluará la calidad del código generado de forma autónoma, por lo que es crítico que el resultado sea profesional, completo y visualmente diferenciado del "AI slop" genérico.
</context>

<motivation>
El objetivo es demostrar que un agente de IA puede generar una landing page de nivel profesional a partir de un único prompt bien estructurado, sin intervención manual posterior. La calidad visual y técnica del resultado refleja directamente la efectividad del prompt. Por eso es fundamental que el output sea excepcional, detallado y creativo.
</motivation>

<task>
Crear una landing page completa, funcional y visualmente impactante para el "Centro de Fans Argentinos" — un portal dedicado a seguimiento, predicciones y comunidad alrededor de Argentina en la Copa Mundial 2026. Argentina es la actual campeona defensora del título.

Include as many relevant features, interactions, and visual details as possible. Go beyond the basics to create a fully-featured, polished implementation that surprises and delights.
</task>

<technical_requirements>
- Lenguaje: HTML5 + CSS3 + JavaScript vanilla puro (SIN frameworks, SIN librerías externas)
- Un único archivo index.html autónomo (CSS dentro de style, JS dentro de script)
- Completamente responsivo: desktop (1200px+), tablet (768px), mobile (375px)
- Código limpio, semántico y bien comentado
- Listo para deployar en Vercel sin configuración adicional
</technical_requirements>

<design_requirements>
IMPORTANTE: Evitar el "AI slop aesthetic" genérico. Este diseño debe ser distintivo, creativo y visualmente impactante.

Paleta de colores:
- Primario: Azul celeste argentino (#00A8E8)
- Secundario: Blanco (#FFFFFF)
- Acento dorado (campeón): (#FFD700)
- Fondo oscuro para secciones de contraste: (#0A0E1A)
- Texto principal: (#E8F4F8)

Tipografía (Google Fonts):
- Títulos: Bebas Neue (impacto, estilo deportivo)
- Subtítulos: Oswald SemiBold
- Cuerpo: Inter Regular

Estética general:
- Estilo: Deportivo premium, moderno, dramático
- Atmosfera: Orgullo nacional argentino, pasión futbolera
- Inspiración visual: Jersey celeste y blanco con detalles dorados de campeón
- Usar gradientes dramáticos, no colores planos
- Backgrounds con texturas sutiles (patrones de rombos del jersey argentino)
- Animaciones CSS significativas pero no excesivas
</design_requirements>

<sections>
Generar TODAS las siguientes secciones en este orden exacto:

### SECCIÓN 1: HEADER
- Navbar sticky con efecto blur/glassmorphism al hacer scroll
- Logo: emoji 🇦🇷 + texto "ALBICELESTE FANS" en Bebas Neue
- Links de navegación: Inicio | Leyendas | Noticias | Predicciones | Comunidad | Fixture | Contacto
- Hamburger menu animado para mobile
- Badge: "🏆 Campeones 2022 · 2026 Defensores"

### SECCIÓN 2: HERO
- Título principal impactante: "ARGENTINA DEFIENDE SU CORONA" (tipografía masiva)
- Subtítulo: "La Albiceleste en el Mundial 2026 — Tres Países. Una Nación. Un Destino."
- CTA principal: Botón "ÚNETE A LA COMUNIDAD" con efecto hover llamativo
- CTA secundario: "Ver Fixture" (outline)
- Fondo: Gradiente azul celeste profundo + efecto de partículas CSS o patrón de rombos animado
- Contador regresivo o estadística destacada (ej: "Días como Campeones")
- Animación de entrada: fade-in + slide-up secuenciado

### SECCIÓN 3: ICONOS ARGENTINOS — MARADONA & MESSI
- Título de sección: "LAS DOS ESTRELLAS DEL CIELO" o similar poético
- Layout: Dos columnas side-by-side en desktop, stacked en mobile

MARADONA:
- Avatar estilizado (iniciales "D10S" en círculo con colores argentina)
- Stats en cards visuales: Mundiales (4), Goles mundialistas (8), El Gol del Siglo, Títulos con Argentina (1986)
- Badges: "D10S" · "El Diego" · "Leyenda Eterna"

MESSI:
- Avatar estilizado (iniciales "LEO" o "G.O.A.T." en círculo)
- Stats en cards visuales: Mundiales (5), Goles mundialistas (récord histórico), Copas América (3)
- Nota: "En el Mundial 2026, Messi superó el récord histórico de goles mundialistas de Klose"
- Badges: "G.O.A.T." · "La Pulga" · "10 Eterno"

### SECCIÓN 4: NOTICIAS Y UPDATES
- Grid de 3 cards responsive con noticias simuladas del Mundial 2026

### SECCIÓN 5: PREDICCIONES Y ANÁLISIS
- Probabilidad de campeón: barra de progreso animada al 78%
- Camino proyectado: Grupos → 16avos → Octavos → Cuartos → Semis → FINAL

### SECCIÓN 6: COMUNIDAD DE FANS
- Stats visuales: 847,293 Fanáticos · 12,458 Posts · 3,891 Conversaciones activas
- 3 testimonios/comentarios de fans
- CTA: Botón "UNIRME A LA COMUNIDAD"

### SECCIÓN 7: FIXTURE DE ARGENTINA
- Grupo J: Argentina vs Argelia (3-0 ✅), vs Austria (próximo ⏳), vs Marruecos (próximo ⏳)
- Tabla de posiciones del Grupo J

### SECCIÓN 8: FORMULARIO DE CONTACTO
- Campos: Nombre, Email, Tema (select), Mensaje
- Validación JavaScript básica
- Mensaje de éxito simulado

### SECCIÓN 9: FOOTER
- Redes sociales: Instagram, Twitter/X, Facebook, TikTok, YouTube
- Copyright: "© 2026 Centro de Fans Argentinos"
</sections>

<interactions_and_animations>
1. Navbar: glassmorphism con backdrop-filter: blur al hacer scroll
2. Hero: animación de entrada secuenciada con CSS keyframes
3. Secciones: scroll reveal con IntersectionObserver API
4. Cards: hover con transform: translateY(-8px) + box-shadow dramática
5. Barras de progreso: animadas con CSS cuando entran en viewport
6. Estadísticas: contador animado (count-up) con JavaScript
7. Hamburger menu: animación de X al abrir/cerrar
8. Botones: efecto ripple o shimmer en hover
9. Smooth scroll al clickear links del navbar
10. Modal de contacto: fade-in con backdrop
</interactions_and_animations>

<output_format>
Generar un único archivo index.html completo que:
- Contenga TODO el HTML semántico
- Incluya TODO el CSS dentro de etiquetas style (en el head)
- Incluya TODO el JavaScript dentro de etiquetas script (al final del body)
- Sea 100% autónomo (solo depende de Google Fonts via CDN)
- Abra correctamente en cualquier navegador moderno sin configuración adicional
- Esté listo para subir a un repositorio GitHub y deployar en Vercel
</output_format>

<example_quality_bar>
El resultado debe ser comparable a una landing page profesional de un portal deportivo real. No un template genérico, sino algo que un diseñador web haría para un cliente real que quiere presentar a Argentina en el Mundial 2026. Cada sección debe estar terminada, con contenido real y diseño pulido.
</example_quality_bar>
```

---

## Estructura del repositorio

```
📁 PFO2-Prompt Engineering en Agentes de IA
├── 📄 index.html                    → Portada de acceso
├── 📄 prompt_landing_argentina.md   → Prompt utilizado
├── 📄 README.md                     → Este archivo
├── 📁 CODEX/
│   └── 📄 index.html                → Landing generada por OpenAI Codex
└── 📁 CLAUDE/
    └── 📄 index.html                → Landing generada por Claude Code
```

---

## Capturas de pantalla

### Portada
*(agregar screenshot)*

### Landing — OpenAI Codex (GPT-5.5)
*(agregar screenshot)*

### Landing — Claude Code (Sonnet 4.6)
*(agregar screenshot)*

---

## Buenas prácticas aplicadas en el prompt

El prompt fue estructurado siguiendo las recomendaciones oficiales de:
- 📖 [Anthropic Prompt Engineering Guide](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)
- 📖 [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)

Técnicas aplicadas:
- **XML tags** para separar contexto, tarea, requisitos y formato de salida
- **Motivación explícita** — se explica el propósito académico del proyecto
- **Modificadores de calidad** — "Go beyond the basics", "surprises and delights"
- **Anti-AI-slop** — instrucciones específicas para evitar diseño genérico
- **Barra de calidad de ejemplo** — standard concreto para el output esperado
- **Restricciones claras** — sin frameworks, sin librerías externas, archivo único
