# Landing Page — Natura Avon (Reclutamiento de Emprendedoras)

Este documento es un informe de negocio y marca para el desarrollador que está construyendo la landing page. **No sustituye ni modifica la plantilla HTML/CSS base ni el prompt inicial ya entregado** — es información complementaria (branding, contenido, paleta de colores y requisitos de estilo/efectos) para que el desarrollador la use al iterar con Claude sobre esa plantilla.

## 1. Sobre el negocio

- **Marca:** Natura ∙ Avon (representante/distribuidora independiente que vende por catálogo ambas marcas).
- **Objetivo de la página:** No es una tienda en línea. Es una **landing de reclutamiento** — captar personas interesadas en unirse como vendedoras/emprendedoras por catálogo (modelo de venta directa).
- **Teléfono de contacto:** 5540849754 (formato sugerido para mostrar: 55 4084 9754). Se asume lada México (+52) para cualquier botón de WhatsApp (`https://wa.me/525540849754`) — confirmar con el cliente antes de publicarlo.
- **Llamado a la acción principal:** que la persona interesada escriba/contacte por teléfono o WhatsApp para empezar su negocio.

## 2. Mensaje y propuesta de valor (tomado del flyer de referencia del cliente)

El cliente compartió un flyer que resume cómo hace su publicidad hoy. Usar este mensaje como base de copy, no como estructura de página:

- Frase principal: **"Emprende hoy, transforma tu mañana"**
- Frase de urgencia: **"¡Tu momento es ahora!"**
- Frase de invitación: **"Únete a la familia de emprendedoras Natura y Avon"**
- Cierre motivacional: **"Empieza con poco, gana en grande"**
- Pregunta/gancho: **"¿Qué esperas? Da el primer paso hacia la libertad financiera y la vida que sueñas"**
- Cierre de contacto: **"¡Escríbeme! Yo te ayudo a comenzar tu negocio y alcanzar tus metas"** / **"¡Juntas podemos más!"**

Cuatro beneficios que el cliente destaca para atraer reclutas (úsalos como contenido, no como nuevas secciones — acomódalos donde la plantilla ya tenga espacio para bullets/beneficios/íconos):

1. **Ingresos extras** — Tú eliges cuánto ganar.
2. **Flexibilidad total** — Tiempos para ti y tu familia.
3. **Productos increíbles** — De las marcas que amas.
4. **Crecimiento y apoyo** — Capacitación, acompañamiento y más beneficios.

## 3. Material de referencia (carpeta `/imagenes`)

Todas las imágenes son fotos/capturas del catálogo y publicidad real del negocio. Referencia de qué contiene cada una:

| Archivo | Contenido | Uso sugerido |
|---|---|---|
| `7.jpeg` | **Flyer principal de reclutamiento** "Emprende hoy, transforma tu mañana" con logos de AVON y Natura, mensaje de venta, íconos de beneficios y foto de modelo. | **Referencia #1 de marca, copy y paleta de colores.** Aquí están los logos que hay que recortar (ver sección 5). |
| `1.jpeg` | Catálogo Tododia — crema corporal y jabones "Mango rosa y agua de coco". | Referencia visual de producto / fondo cálido naranja-coral. |
| `12.jpeg` | Catálogo Tododia — desodorantes roll-on (varias fragancias). | Referencia de paleta pastel (lila, verde menta, rosa). |
| `3.jpeg` | Catálogo Lumina — línea de cuidado capilar "Brillo y protección de color". | Referencia de paleta ciruela/vino y dorado rosado. |
| `WhatsApp Image ...9.49.46 PM.jpeg` | Catálogo Avon Care — línea de humectación corporal (avena, almendra, karité). | Referencia de paleta azul marino / neutros cálidos. |
| `WhatsApp Image ...9.49.47 PM.jpeg` | Catálogo Avon — máscaras de pestañas (Extravagant, Shula Up, Wonder Curve). | Referencia menor, tono rojo/índigo/amarillo. |

Estas imágenes de catálogo (1, 12, 3, WhatsApp 46/47) son **apoyo visual secundario** — muestran el tipo de producto que se vende y sirven como banco de fotos/colores de marca si se necesitan imágenes de producto. La imagen que define la identidad y el mensaje de la página es **`7.jpeg`**.

## 4. Paleta de colores de marca

Extraída visualmente del flyer principal (`7.jpeg`). Son valores aproximados — el desarrollador tiene libertad de afinarlos ligeramente para contraste/accesibilidad, siempre dentro de esta misma familia de color:

| Color | Hex aprox. | Uso |
|---|---|---|
| Rojo Avon | `#E4002B` | Logo Avon, acentos puntuales |
| Naranja Natura | `#F7941D` | Logo Natura, acentos cálidos |
| Magenta / Rosa marca | `#EC008C` | Color principal de marca — CTAs, textos destacados, gradientes |
| Púrpura marca | `#6B2C91` | Segundo color principal — títulos, fondos de banners, gradientes |
| Verde crecimiento | `#7CB342` | Uso puntual (ícono "crecimiento y apoyo") |
| Blush / rosa pálido | `#FDE8EC` | Fondos suaves, secciones claras |
| Blanco | `#FFFFFF` | Fondo base, espacios en blanco |
| Texto oscuro | `#241F2B` | Texto principal sobre fondos claros |

Tonos secundarios opcionales (tomados de los catálogos de producto, por si se necesita profundidad adicional en detalles pequeños, no como colores dominantes): ciruela `#5B2333` (Lumina), azul marino `#1B3A6B` (Care), naranja coral cálido `#F2793C` (Tododia).

La dirección de color debe sentirse **premium**, no como flyer de catálogo: usar el magenta y el púrpura como protagonistas en gradientes sutiles, dejar mucho espacio en blanco/blush, y usar el rojo/naranja de los logos solo como acento puntual (no como fondo grande).

## 5. Logo — atención especial

En `7.jpeg` aparecen los dos logotipos (AVON y Natura) en la parte superior, **pero vienen con fondo** (no son archivos PNG transparentes, son parte de la foto/flyer). El desarrollador debe:

1. Recortar/extraer ambos logotipos de esa imagen.
2. **Eliminar el fondo** para dejarlos en PNG con transparencia.
3. Usar esa versión transparente en: pantalla de carga, header/navbar, favicon y cualquier otro lugar donde la plantilla ya coloque un logo.

Si el cliente llega a enviar un archivo de logo oficial en alta resolución más adelante, ese debe reemplazar el recorte hecho a mano.

## 6. Dirección de estilo visual

El sitio debe verse **premium, corporativo y de marca**, no como un flyer de catálogo. Referencia de nivel: **big tech, elegante, minimalista**. Concretamente:

- Tipografía y layout limpios, mucho espacio en blanco, jerarquía clara — no saturar la pantalla como los catálogos de producto.
- Gradientes y color usados con moderación, con la paleta de la sección 4, para transmitir sofisticación, no "oferta de catálogo".
- Sensación de marca establecida y confiable, aunque el negocio sea de venta directa/reclutamiento.
- Mantener este nivel de acabado en **todo** el sitio, no solo en el hero.

## 7. Efectos y animaciones requeridas

- **Pantalla de carga (loading screen):** overlay a pantalla completa que se muestra mientras carga la página, con un spinner/loader y el logo del negocio (ya sin fondo, ver sección 5) centrado. Debe desaparecer con una transición suave (fade) una vez que el contenido esté listo. Estilo acorde a la paleta y al nivel premium/minimalista, no genérico.
- **Animaciones al hacer scroll:** los bloques de contenido deben aparecer con animación (fade/slide sutil) a medida que el usuario baja por la página. Movimiento suave y elegante, sin rebotes ni exageraciones — coherente con el estilo "high tech" solicitado.
- **Título del hero:** aplicar efecto de **máquina de escribir** (typewriter) al texto principal del hero.
- **Letras del título del hero:** además del typewriter, las letras deben tener un efecto de **cambio de color** (por ejemplo, transición/ciclo de color usando la paleta de marca — magenta, púrpura, naranja), de forma elegante y no infantil.

## 8. Cómo trabajar sobre la plantilla

- El desarrollador **ya cuenta con la plantilla base en HTML/CSS** y un prompt inicial entregado previamente para adaptarla al negocio. Este documento no reemplaza eso: es contexto de marca y negocio para seguir iterando.
- **No se debe reestructurar ni agregar secciones nuevas.** Todo el contenido, branding y efectos descritos aquí deben implementarse **dentro de la estructura de la plantilla existente**, adaptando lo que ya está, no inventando secciones adicionales.
- El desarrollador puede **iterar libremente con Claude**, dándole las instrucciones/prompts necesarios sobre este mismo proyecto, tantas veces como haga falta, hasta lograr el resultado final deseado según lo descrito en este informe.

## 9. Resumen rápido para el desarrollador

- Negocio: venta por catálogo Natura + Avon, esta página es para **reclutar vendedoras**, no para vender producto directo.
- Teléfono: **5540849754**.
- Mensaje/copy: tomar de la sección 2 (basado en el flyer real del cliente, `imagenes/7.jpeg`).
- Colores: sección 4 (magenta/púrpura como protagonistas, rojo/naranja de logos como acento).
- Logo: recortar de `imagenes/7.jpeg` y quitarle el fondo antes de usarlo.
- Estilo: premium, corporativo, big tech, elegante, minimalista.
- Efectos obligatorios: loading screen con spinner + logo, animaciones al hacer scroll, typewriter en el título del hero, letras del hero cambiando de color.
- Estructura: se respeta la plantilla existente, no se agregan secciones nuevas.
