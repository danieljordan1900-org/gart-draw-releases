# Novedades de GART Draw

<!--
Formato (la app lo separa por versión):
  ## X.Y.Z — AAAA-MM-DD        (la fecha es opcional; la más reciente arriba)
  Video: https://…             (opcional, puede repetirse)
  - viñetas en Markdown
GART Draw lee este archivo al abrir Ayuda → Novedades: los cambios se ven sin
publicar una versión (tardan hasta ~5 min por la caché de GitHub).
Video: enlace https público (Google Drive, Google Fotos, YouTube…); se abre en el navegador del usuario.
Para que un video se vea, compártelo con quienes usan la app.
-->

## 0.1.49 — 2026-11-20
- **Formularios renovados**: 9 estilos nuevos, cada uno con su miniatura en la galería
- Campos de texto: **recuadro**, **subrayado** y **valor destacado**; siguen sirviendo como entrada de los calculadores
- Etiquetas: **título de sección**, **nota** y **designador** (R1, K2…), que se ajusta al texto
- **Áreas de texto con formato**: títulos, listas, negrita y enlaces escritos en Markdown, con ajuste de líneas. Se editan con doble clic o desde el campo Texto del panel derecho
- Herramienta **Texto** como en Visio: clic en el lienzo y escribe; la caja se ajusta al texto
- **Tipo de punta** para las flechas (Simple, Doble, Triángulo, Abierta, Círculo, Rombo)
- Corregido: al mover una forma dentro de un grupo se desplazaban las demás
- Corregido: el alto y ancho en mm no se actualizaban al mover los puntos de una línea o flecha
- Corregido: el texto vertical o inclinado se descentraba al cambiar de tamaño
- Corregido: el botón Pegar del editor de imagen pedía permiso de WebView2

## 0.1.48 — 2026-11-16
- **Editor de imagen** renovado: girar y voltear (los SVG siguen siendo SVG), recortar y guardar variantes con **Guardar como**
- Selección con asas para mover, escalar y girar; también elíptica, a mano alzada y **varita mágica**, con **Quitar fondo**
- Cuentagotas, bote de pintura con tolerancia, menú **Tamaño** (1× a 5×) y hasta 50 pasos para deshacer
- Pegar imágenes copiadas desde otros programas
- **Orden manual de formas** en las galerías: arrastra para ordenarlas o insertarlas
- Botón para **quitar decimales** de la posición X/Y

## 0.1.47 — 2026-10-28
Video: https://photos.app.goo.gl/9KcDm34pFvDPEfwn8
- **Categorías en las galerías**: dale una categoría a cada forma (por ejemplo "Barra") y filtra la galería con un clic
- El buscador también encuentra formas por su categoría
- **Editar categorías** de una galería: renombrar, unir o quitar, y todas sus formas se actualizan
- **Novedades** en Ayuda: los cambios de cada versión, con video cuando lo haya

## 0.1.46 — 2026-10-23
- Exportar una galería publicada en la nube e importarla reemplazando su contenido o como copia
- Las galerías se abren al instante y la sincronización en la nube es más robusta
- Casilla **No imprimir** en Propiedades → Otros
- Corregido: las cajas "H × W × P totales" copiadas seguían enlazadas a la original

## 0.1.45 — 2026-10-18
- **H × W × P totales** en las cajas de medidas
- Popover de la regla con nuevo diseño y **Medir desde**: punto medio, interior o desplazado
- Pestañas y ubicación de campos en **Envolver en caja**
- Las etiquetas de caja se imprimen sin la medida base

## 0.1.44 — 2026-10-16
- **Etiquetas de distancia** desde el popover de la regla
- **Revisar caja**: vuelve a medir y edita una caja existente
- Posición de la selección con varios elementos y **Envolver en caja** (experimental)
- Marca "No incluir en separación de coordenadas"

## 0.1.43 — 2026-10-13
- Guías de alineación que se pueden activar y desactivar (Ctrl+Shift+A)
- Cuadrícula y medidas en milímetros reales según la escala
- Enter aplica las dimensiones escritas al lienzo

## 0.1.42 — 2026-10-12
- Calculador: **modo asociación** más claro, valores en la lista y se cierra con Enter
- Copiar y pegar calculadores sin referencias al original
- Las formas giradas en diagonal aportan 0 al cálculo y lo avisan

## 0.1.41 — 2026-09-29
- Modo asociación: la caja de selección vincula las formas al soltar
- Corregidos resultados del calculador que quedaban desactualizados al borrar o deshacer

## 0.1.40 — 2026-09-13
- Corregidas la alineación y la selección de grupos
