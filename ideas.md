# Dirección de diseño — DDA Technologies

## Referencia visual y especificación de fidelidad

La imagen entregada por el usuario es la **fuente de verdad visual** para la primera versión del sitio. La interfaz debe conservar su lenguaje corporativo industrial: navegación horizontal en una franja superior azul marino, logotipo blanco a la izquierda, CTA de asesoría con contorno naranja a la derecha, hero dividido entre copy de alto impacto y fotografía de automatización industrial, diagonales técnicas en blanco/naranja, módulos de soluciones con iconografía lineal y bloques de contenido alternados en azul marino y gris muy claro.

La composición prioriza una lectura de izquierda a derecha y una sensación de movimiento operativo. El sitio debe sentirse como una empresa de ingeniería y tecnología que trabaja con procesos reales, no como una startup genérica. La adaptación responsiva mantendrá el contraste, el sistema de diagonales y la jerarquía del hero, pero apilará los contenidos en móvil y convertirá el menú en una navegación compacta.

## Enfoque seleccionado: Ingeniería editorial de alto contraste

### Design Movement

**Brutalismo corporativo refinado**, inspirado en dashboards industriales, señalética de planta y diseño editorial suizo. La precisión modular se combina con cortes diagonales, líneas técnicas y fotografía documental de operaciones automatizadas.

### Core Principles

1. **Precisión operativa:** cada bloque comunica una capacidad o resultado concreto; se evitan adornos que no ayuden a entender el negocio.
2. **Contraste con propósito:** azul noche para confianza y profundidad, blanco humo para claridad y naranja señalético para acción, foco y rendimiento.
3. **Ritmo asimétrico:** composición editorial con paneles divididos, diagonales y alineaciones no centradas que transmiten movimiento y especialización.
4. **Resultados visibles:** métricas, sectores y capacidades aparecen como evidencia visual, no como promesas abstractas.

### Color Philosophy

El **azul noche industrial** (#0B1224) recuerda el ambiente de una planta en operación y comunica rigor, control y confianza técnica. El **naranja señal** (#F28A16) funciona como código de acción y energía: se reserva para CTAs, cifras, líneas de énfasis y estados activos. El **blanco humo** (#F1F1EF) aporta pausas editoriales y facilita la lectura de textos largos. Un azul acero (#162643) conecta los paneles oscuros con las imágenes de maquinaria sin caer en un gradiente ornamental.

### Layout Paradigm

Una estructura de **franja operativa**: encabezado compacto, hero de dos campos, banda de cuatro capacidades, sección editorial de dos mitades, caso de éxito con imagen de proceso y una barra final de indicadores. En desktop, las divisiones diagonales invaden los límites entre módulos; en móvil, se transforman en acentos lineales para preservar legibilidad. El contenido se alinea mayoritariamente a la izquierda y utiliza anchos controlados para conservar tensión visual.

### Signature Elements

- Diagonales técnicas en blanco, gris y naranja como separadores y marcos de imagen.
- Línea de energía naranja de 2–4 px que subraya títulos activos, cifras y llamadas a la acción.
- Iconografía lineal de ingeniería: engranaje, brazo robótico, código, gráfico y brújula de proceso.

### Interaction Philosophy

Las interacciones deben sentirse como controles de una herramienta profesional: respuestas rápidas, claras y discretas. Los CTAs cambian de fondo o elevan ligeramente su borde al pasar el cursor; los enlaces de navegación muestran una línea naranja que crece desde el centro; las tarjetas de soluciones revelan un borde naranja y un desplazamiento mínimo. La navegación móvil abre un panel oscuro legible y fácil de cerrar. Los enlaces a secciones sin página completa llevan al bloque correspondiente o muestran una confirmación breve si todavía son placeholders.

### Animation

Las entradas de sección usan una aparición corta con desplazamiento vertical de 16–24 px, escalonada entre elementos por 50–70 ms. Las diagonales y líneas de interfaz no deben parpadear: pueden deslizarse entre 180–260 ms con una curva de salida marcada. Los botones responden en 140–180 ms y se reducen a 97% al presionar. No se animan propiedades de layout; solo `transform` y `opacity`. Todo movimiento decorativo queda desactivado o reducido para `prefers-reduced-motion: reduce`.

### Typography System

La tipografía principal será **Barlow Condensed** para titulares, navegación y cifras: sus formas compactas recuerdan a señalética industrial y permiten titulares de alto impacto. El texto corrido usará **Manrope**, por su legibilidad en bloques de información y su tono tecnológico sobrio. Los titulares se escribirán en mayúsculas, con pesos 600–800 y tracking ligeramente negativo; el cuerpo se mantendrá entre 15 y 18 px con alturas de línea generosas. Los labels y métricas usarán Barlow Condensed con tracking positivo para reforzar el carácter técnico.

### Brand Essence

**DDA Technologies convierte desafíos operativos complejos en sistemas industriales más inteligentes, medibles y escalables.** Personalidad: **precisa, resolutiva, transformadora**.

### Brand Voice

Los titulares son directos, activos y orientados a impacto; los CTAs invitan a conversar sobre el problema real, no a consumir una promesa genérica. El microcopy es concreto y evita palabras vacías como “revolucionario” o “de clase mundial”.

Ejemplos:

- “Tecnología que transforma tu operación.”
- “Hablemos del cuello de botella que quieres resolver.”

### Wordmark & Logo

El logotipo debe tratarse como un símbolo técnico compuesto por cuatro círculos conectados —una lectura visual de datos, procesos, personas y máquinas— acompañado por el wordmark **DDA Technologies** en composición horizontal. En esta primera entrega, el símbolo se reproducirá como un emblema vectorial limpio y de alto contraste, sin inventar una tipografía distinta al referente.

### Signature Brand Color

**Naranja señal DDA — #F28A16.** Es el color propio de acción, avance y resultados: debe aparecer con moderación, pero siempre que el usuario deba identificar una decisión o un dato importante.

## Aplicación al sitio

La landing page incluirá: encabezado con navegación; hero con el mensaje “Tecnología que transforma tu operación”; banda de soluciones para Ingeniería, Automatización, Software y Análisis de datos; bloque “Sobre DDA Technologies”; caso de éxito del centro de distribución del sector alimentación; indicadores de experiencia; sección de sectores; proceso de trabajo; CTA de asesoría; y pie de página con datos de contacto y enlaces. El copy final se extraerá del brochure y se adaptará únicamente para claridad web, sin inventar testimonios, reseñas o resultados no documentados.

## Style Decisions

- La referencia visual del usuario tiene prioridad sobre cualquier tendencia genérica de landing pages.
- Se usará fondo oscuro en el hero y paneles de resultados, con secciones claras para lectura editorial.
- No se usarán gradientes morados, tarjetas uniformemente redondeadas, layouts completamente centrados ni la fuente Inter.
- Las imágenes generadas para el sitio deben mostrar entornos industriales reales, con espacio negativo controlado para texto y una paleta azul acero/naranja coherente.
- El diseño será responsivo y accesible: contraste verificable, foco visible, navegación por teclado y reducción de movimiento disponible.
