# Revisión visual — DDA Technologies

## Escritorio (1280 × 720, página completa)

La composición conserva la referencia: hero oscuro de dos campos con fotografía industrial, headline compacto en Barlow Condensed, acentos naranja, navegación superior, banda de cuatro capacidades, bloque editorial claro, lista de soluciones, sección de aplicaciones, proceso, barra de indicadores, contacto y footer. La jerarquía se mantiene legible en la captura completa y las imágenes generadas aparecen en el hero, el bloque de nosotros, el primer servicio y la sección de aplicaciones.

## Móvil (390 × 844, página completa)

El contenido se apila sin desbordamientos visibles. El hero conserva el contraste y las diagonales en una escala más compacta; la banda de capacidades se convierte en dos columnas; los servicios pasan a filas verticales; la sección de sectores conserva una lista en dos columnas; el proceso y los indicadores se reorganizan en rejillas de dos columnas; contacto y footer se apilan. La navegación se convierte en botón de menú para no comprimir enlaces en la cabecera.

## Validaciones técnicas

`pnpm check` y `pnpm build` finalizan correctamente. El build reporta únicamente una advertencia de tamaño de chunk de Vite, sin errores de compilación. Los enlaces principales son anclas internas, los datos de contacto usan `tel:` y `mailto:`, y la página declara idioma español, title y description.

## Decisión

No se requieren cambios visuales correctivos para esta primera entrega. Se mantiene la fidelidad a la propuesta del usuario por encima de ajustes subjetivos de estilo.
