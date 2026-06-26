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
- Efecto visual: Separación con línea dorada central o ángulo diagonal

MARADONA:
- Avatar estilizado (iniciales "D10S" en círculo con colores argentina)
- Nombre: "DIEGO ARMANDO MARADONA"
- Período: 1977 – 1994 (Selección Argentina)
- Stats en cards visuales: Mundiales (4), Goles mundialistas (8), El Gol del Siglo, Títulos con Argentina (1986)
- Cita: algo sobre la "Mano de Dios" o su legado
- Badges: "D10S" · "El Diego" · "Leyenda Eterna"

MESSI:
- Avatar estilizado (iniciales "LEO" o "G.O.A.T." en círculo)
- Nombre: "LIONEL ANDRÉS MESSI"
- Período: 2005 – presente (Selección Argentina)
- Stats en cards visuales: Mundiales (5), Goles mundialistas (récord histórico), Copas América (3), Títulos con Argentina
- Nota: "En el Mundial 2026, Messi superó el récord histórico de goles mundialistas de Klose"
- Badges: "G.O.A.T." · "La Pulga" · "10 Eterno"

Comparativa visual al final de la sección: "Del Diego al Leo — El legado de la 10"

### SECCIÓN 4: NOTICIAS Y UPDATES
- Título: "ÚLTIMAS NOTICIAS"
- Grid de 3 cards responsive
- Noticias simuladas pero realistas (basadas en el Mundial 2026 real):
  * "Argentina golea 3-0 a Argelia: hat-trick de Messi en el debut" (Victoria · 15 Jun 2026)
  * "Messi rompe el récord de Klose como máximo goleador mundialista" (Histórico · 15 Jun 2026)
  * "Fixture confirmado: Argentina vs Austria en la segunda fecha" (Próximo · 24 Jun 2026)
- Cada card: imagen placeholder con color + categoría badge + título + resumen + fecha + "Leer más"
- Hover: card se eleva con sombra dramática
- Categorías con colores: Victoria (verde), Histórico (dorado), Próximo (azul)

### SECCIÓN 5: PREDICCIONES Y ANÁLISIS
- Título: "CHANCES DE ARGENTINA"
- Probabilidad de campeón: barra de progreso animada al 78%
- Camino proyectado: cards secuenciales Grupos → 16avos → Octavos → Cuartos → Semis → FINAL
- Cada etapa: estado (Superado/En curso/Próximo) + rival probable + porcentaje
- Tabla de rendimiento histórico de Argentina en Mundiales (últimas 5 ediciones)
- Fortalezas del equipo: cards con iconos (Messi, Defensa, Colectivo, Experiencia)

### SECCIÓN 6: COMUNIDAD DE FANS
- Título: "LA COMUNIDAD ALBICELESTE"
- Stats visuales: 847,293 Fanáticos · 12,458 Posts · 3,891 Conversaciones activas
- 3 testimonios/comentarios de fans con avatar (iniciales en círculo), nombre, ciudad, timestamp y texto
  * Fan de Buenos Aires — comentario apasionado sobre el debut
  * Fan de Rosario — comentario sobre Messi
  * Fan de Córdoba — predicción para la final
- CTA: Botón grande "UNIRME A LA COMUNIDAD"
- Diseño: estilo feed de red social, fondo oscuro contrastante

### SECCIÓN 7: FIXTURE DE ARGENTINA
- Título: "CALENDARIO DE ARGENTINA - GRUPO J"
- Tabla o cards de partidos:
  * Partido 1: Argentina vs Argelia — 15 Jun · Miami · RESULTADO: 3-0 ✅
  * Partido 2: Argentina vs Austria — 24 Jun · Dallas · PRÓXIMO ⏳
  * Partido 3: Argentina vs Marruecos — 28 Jun · Houston · PRÓXIMO ⏳
- Cada partido: fecha, hora ARG, rival con bandera emoji, estadio, estado, resultado si aplica
- Botón "Recordarme" en partidos próximos (JavaScript alert o modal estilizado)
- Posición en el grupo: Tabla de posiciones del Grupo J (simulada)

### SECCIÓN 8: FORMULARIO DE CONTACTO
- Título: "ENVIANOS TU MENSAJE"
- Campos: Nombre*, Email*, Tema (select: Consulta/Sugerencia/Reporte/Otro), Mensaje* (textarea)
- Validación JavaScript: campos requeridos, formato email válido, mínimo 10 caracteres en mensaje
- Submit button con animación de loading
- Mensaje de éxito: modal estilizado "¡Gracias! Vamo Argentina 🇦🇷"
- Diseño: formulario sobre fondo con patrón sutil

### SECCIÓN 9: FOOTER
- Logo + tagline
- Links: Sobre nosotros · Política de privacidad · Contacto
- Redes sociales: Instagram 📸 · Twitter/X 🐦 · Facebook 👍 · TikTok 🎵 · YouTube ▶️
- Copyright: "© 2026 Centro de Fans Argentinos. Todos los derechos reservados."
- Frase final: "Vamo Argentina, carajo! 🇦🇷⚽🏆"
</sections>

<interactions_and_animations>
Implementar estas interacciones y animaciones (CSS + JS vanilla):
1. Navbar: cambio de estilo al hacer scroll (glassmorphism con backdrop-filter: blur)
2. Hero: animación de entrada secuenciada con CSS keyframes (fade-in + translate)
3. Secciones: efecto scroll reveal (IntersectionObserver API) — aparecen al hacer scroll
4. Cards de noticias: hover con transform: translateY(-8px) + box-shadow dramática
5. Barras de progreso: animadas con CSS cuando entran en viewport
6. Estadísticas de comunidad: contador animado (efecto count-up) con JavaScript
7. Hamburger menu: animación de X al abrir/cerrar
8. Botones: efecto ripple o shimmer en hover
9. Smooth scroll: al clickear links del navbar
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
