---
name: Dampak — Propuesta 06 (Híbrida)
description: Sistema visual de la propuesta 06. Cabecera y retícula inspiradas en la 03, tipografía de la 04 y temas oscuro/claro.
colors:
  ink-dark: "#100e11"
  ink-soft-dark: "#171417"
  ink-sunk-dark: "#0a090b"
  surface-dark: "#1e1a1e"
  ink-light: "#17140f"
  paper-light: "#f6f3ed"
  paper-raised-light: "#ffffff"
  paper-sunk-light: "#eae5db"
  coral: "#e7513a"
  coral-ink: "#14100f"
  coral-ink-light: "#16110f"
  coral-deep: "#b8371f"
  text-dark: "#f2ede4"
  text-muted-dark: "#a49c93"
  text-strong-dark: "#c9c0b5"
  text-muted-light: "#5c564c"
  text-strong-light: "#3a352e"
  white: "#ffffff"
  black: "#000000"
  light-copy: "#4a443c"
  browser-red: "#ff605c"
  browser-amber: "#ffbd44"
  browser-green: "#34c759"
typography:
  display-hero:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(3.4rem, 7.2vw, 6.5rem)"
    fontWeight: 600
    lineHeight: 0.92
    letterSpacing: "-0.035em"
  display-hero-tablet:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(3.2rem, 7.2vw, 6.5rem)"
    fontWeight: 600
    lineHeight: 0.92
    letterSpacing: "-0.035em"
  display-hero-phone:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2rem, 10.5vw, 6.5rem)"
    fontWeight: 600
    lineHeight: 0.92
    letterSpacing: "-0.035em"
  display-hero-narrow:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(3.2rem, 7.2vw, 6.5rem)"
    fontWeight: 600
    lineHeight: 0.92
    letterSpacing: "-0.035em"
  display-section:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2.1rem, 3.6vw, 3.4rem)"
    fontWeight: 600
    lineHeight: 1.02
    letterSpacing: "-0.035em"
  display-case:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.7rem, 2.8vw, 2.6rem)"
    fontWeight: 600
    lineHeight: 1.02
    letterSpacing: "-0.035em"
  display-quote-lead:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.4rem, 2.2vw, 2.1rem)"
    fontWeight: 400
    lineHeight: 1.32
    letterSpacing: "-0.02em"
  display-quote:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.2rem, 1.6vw, 1.5rem)"
    fontWeight: 400
    lineHeight: 1.32
    letterSpacing: "-0.02em"
  display-member:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.2rem, 1.6vw, 1.45rem)"
    fontWeight: 600
    lineHeight: 1.02
    letterSpacing: "-0.035em"
  display-member-mobile:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 600
    lineHeight: 1.02
    letterSpacing: "-0.035em"
  display-service:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.2rem, 1.7vw, 1.55rem)"
    fontWeight: 600
    lineHeight: 1.02
    letterSpacing: "-0.03em"
  heading-legal:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.2rem"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  display-menu:
    fontFamily: "Bricolage Grotesque, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.4rem"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.03em"
  body-base:
    fontFamily: "Schibsted Grotesk, Helvetica Neue, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
  body-lead:
    fontFamily: "Schibsted Grotesk, Helvetica Neue, Arial, sans-serif"
    fontSize: "0.9rem"
    fontWeight: 400
    lineHeight: 1.6
  body-small:
    fontFamily: "Schibsted Grotesk, Helvetica Neue, Arial, sans-serif"
    fontSize: "0.85rem"
    fontWeight: 400
    lineHeight: 1.6
  body-tiny:
    fontFamily: "Schibsted Grotesk, Helvetica Neue, Arial, sans-serif"
    fontSize: "0.8rem"
    fontWeight: 400
    lineHeight: 1.6
  body-mini:
    fontFamily: "Schibsted Grotesk, Helvetica Neue, Arial, sans-serif"
    fontSize: "0.75rem"
    fontWeight: 400
    lineHeight: 1.5
  label-micro:
    fontFamily: "Spline Sans Mono, Courier New, monospace"
    fontSize: "0.7rem"
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: "0.03em"
rounded:
  square: "0px"
  control: "50% (botón de tema)"
spacing:
  gutter: "clamp(1.25rem, 4.2vw, 4.5rem)"
  section: "clamp(3.5rem, 7vw, 6rem)"
  measure: "28rem a 34rem (65 a 75 caracteres)"
components:
  button-coral:
    backgroundColor: "{colors.coral}"
    textColor: "{colors.coral-ink}"
    rounded: "{rounded.square}"
    padding: "0.75rem 1.1rem"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.ink-light}"
    rounded: "{rounded.square}"
    padding: "0.75rem 1.1rem"
  input-underline:
    backgroundColor: "transparent"
    textColor: "{colors.ink-light}"
    rounded: "{rounded.square}"
  preview-frame:
    backgroundColor: "{colors.paper-raised-light}"
    textColor: "{colors.ink-light}"
    rounded: "{rounded.square}"
---

# Dampak — Propuesta 06 (Híbrida)

## Qué es

La sexta propuesta combina la **cabecera, retícula oscura e índice de proyectos** de la 03 con la **tipografía** de la 04 (Bricolage Grotesque + Schibsted Grotesk + Spline Sans Mono). La apertura presenta el titular en tres líneas, con solo «Hagamos» sobre coral, y rota cuatro proyectos cada 4,2 s dentro de una ventana de navegador de macOS; los siete casos también se presentan en su propia ventana de navegador. El resto del recorrido suma servicios desplegables, testimonios ficticios en un slider automático con pausa, un equipo con retratos circulares y progreso ligado al scroll, y contacto. La identidad tiene tema oscuro por defecto y una variante clara.

El copy está escrito en español colombiano cercano, con «tú» y sin voseo. Los proyectos, nombres y correos se basan en información proporcionada o visible en sus sitios públicos. Los testimonios son ejemplos ficticios rotulados en la página. El número oficial de WhatsApp, las fotos definitivas del equipo y las citas aprobadas siguen pendientes; los retratos actuales son marcadores reemplazables.

## Tokens de color

Los colores viven en variables CSS; el tema se cambia con `html[data-theme="light"]` sobre el mismo bloque de `:root`.

| Token | Oscuro (por defecto) | Claro | Uso |
| --- | --- | --- | --- |
| `--bg` | `#100e11` | `#f6f3ed` | Fondo de la página |
| `--bg-soft` | `#171417` | `#ffffff` | Paneles, testimonios, contacto |
| `--bg-sunk` | `#0a090b` | `#eae5db` | Pie de página |
| `--surface` | `#1e1a1e` | `#ffffff` | Marcos de imagen |
| `--fg` | `#f2ede4` | `#17140f` | Texto principal |
| `--fg-muted` | `#a49c93` | `#5c564c` | Texto secundario |
| `--fg-strong` | `#c9c0b5` | `#3a352e` | Párrafos de apoyo |
| `--coral` | `#e7513a` | `#e7513a` | Acento, bloque del titular, foco |
| `--coral-ink` | `#14100f` | `#16110f` | Texto sobre coral |
| `--coral-text` | `#e7513a` | `#b8371f` | Coral como texto (legible sobre papel) |
| `--line` / `--line-strong` | rgba claro | rgba oscuro | Reglas de 1 px |

La versión original usa coral como acento de marca. La variante hermana `dampak-mockup-verde/` usa el verde brillante exacto del segundo logo del PDF (`#8ce60d`); no mezclar sus assets ni tokens con esta carpeta. El coral nunca se usa como degradado.

El contraste está verificado en los dos temas. El coral se usa como texto en fondos oscuros; en el tema claro se usa `--coral-text` (`#b8371f`) para conservar legibilidad. Los controles de macOS usan coral de marca, amarillo `#ffbd44` y verde `#34c759`, en ese orden.

## Rampa tipográfica

| Rol | Familia | Tamaño | Peso | Interlineado |
| --- | --- | --- | --- | --- |
| Titular de apertura | Bricolage Grotesque | `clamp(3.4rem, 7.2vw, 6.5rem)` | 600 | 0.90 |
| Titular de sección | Bricolage Grotesque | `clamp(2.1rem, 3.6vw, 3.4rem)` | 600 | 1.02 |
| Título de caso | Bricolage Grotesque | `clamp(1.7rem, 2.8vw, 2.6rem)` | 600 | 1.02 |
| Cita principal | Bricolage Grotesque | `clamp(1.4rem, 2.2vw, 2.1rem)` | 400 | 1.32 |
| Cita | Bricolage Grotesque | `clamp(1.2rem, 1.6vw, 1.5rem)` | 400 | 1.32 |
| Nombre del equipo | Bricolage Grotesque | `clamp(1.2rem, 1.6vw, 1.45rem)` | 600 | 1.02 |
| Nombre del equipo móvil | Bricolage Grotesque | `1.25rem` | 600 | 1.02 |
| Nombre del servicio | Bricolage Grotesque | `clamp(1.2rem, 1.7vw, 1.55rem)` | 600 | 1.02 |
| Cuerpo base | Schibsted Grotesk | `1rem` | 400 | 1.6 |
| Entrada / apoyo | Schibsted Grotesk | `0.9rem` | 400 | 1.6 |
| Cuerpo pequeño | Schibsted Grotesk | `0.85rem` | 400 | 1.6 |
| Interfaz | Schibsted Grotesk | `0.8rem` | 400–500 | 1.6 |
| Pie de texto | Schibsted Grotesk | `0.75rem` | 400 | 1.5 |
| Etiqueta / metadata | Spline Sans Mono | `0.7rem` | 400 | 1.5 |

Reglas de la rampa:

- Ningún texto funcional baja de `0.7rem` (11.2 px).
- El interlineado nunca baja de 1.3 en citas ni de 1.5 en cuerpo.
- El tracking llega hasta `-0.035em` y nunca más.
- Solo la palabra «Hagamos» lleva fondo de color y permanece en una línea (`white-space: nowrap`). El titular completo ocupa tres líneas: «Hagamos», «una web que sí» y «te sirva». El máximo actual es 6.5 rem.
- Las medidas de lectura se quedan entre 65 y 75 caracteres (28 rem a 34 rem).

## Retícula y secciones

Contenedor de contenido máximo de 1440 px; header, apertura, servicios, casos y equipo respetan el mismo canalón exterior. Testimonios, contacto y footer extienden su fondo a todo el viewport mientras el contenido queda alineado al mismo contenedor. Orden obligatorio de las secciones:

1. **Header** fijo: marca, navegación, botón de tema, llamada a la acción, menú móvil.
2. **Apertura** (`#inicio`): titular «Hagamos / una web que sí / te sirva», con solo «Hagamos» sobre bloque coral + vista previa rotativa de proyectos.
3. **Servicios** (`#servicios`): híbrido de lista de capacidades y detalles desplegables, cinco filas con entregables.
4. **Casos de éxito** (`#casos`): siete proyectos reales con captura, ficha y enlace al sitio publicado. Orden: Playground, Futureproof, El Nuevo Siglo, Burger Fest, MAAD 101, Fe y Alegría y RUANCO.
5. **Qué opinan nuestros clientes** (`#clientes`): bloque tipográfico con tres ejemplos rotulados como ficticios, pendientes de aprobación.
6. **Quiénes somos** (`#nosotros`): tres personas con formación, cargo y correo.
7. **Contacto** (`#contacto`): formulario con casilla de datos y llamada a WhatsApp.
8. **Pie**: marca, secciones, legales, redes, copyright.

Breakpoints: 1120 px, 960 px, 620 px, 400 px. La palabra «Hagamos» es `white-space: nowrap`; la columna izquierda del hero ocupa 6.4 de 12 fracciones y la escala baja en pantallas estrechas para mantener el titular en tres líneas sin desbordar. La columna de texto se estira y distribuye su contenido para terminar a la misma altura que la vista previa. Las secciones testimonios, contacto y pie comparten el mismo contenedor máximo de 1440 px. Verificar escritorio, tablet y móvil; capturar al menos 1440, 1024, 768 y 390 px antes de la entrega.

## Movimiento

Hay **un momento de entrada** en la apertura; la vista previa aparece dentro de la ventana y el acento coral sigue anclado al texto. Casos, testimonios y perfiles entran al llegar a la vista; las citas cambian solo por decisión de la persona.

La vista previa rota cada 4,2 s con una barra de progreso, dentro de una ventana de navegador reconocible. Se pausa si el puntero o el foco está en la lista, si la vista previa sale de pantalla o si la pestaña pierde el foco. El slider de opiniones avanza cada 7 s con una transición de entrada y salida; el botón de pausa y el foco lo detienen. Con `prefers-reduced-motion: reduce` no rota y todas las animaciones se desactivan. La preferencia de tema se guarda bajo una clave propia de esta propuesta.

## Componentes

- **Ventanas de navegador:** controles de macOS, dominio y estado publicado; aparecen en la vista previa y en cada caso de éxito.
- **Botones:** coral con texto ink; borde de 1 px para la variante secundaria; foco visible coral.
- **Vista previa:** ventana de navegador con tres controles de macOS, dominio actualizado, captura real, barra de progreso y pie con tipo y proyecto.
- **Servicios:** fila en `<details>` con nombre, qué resuelve, alcance y entregables; el primero viene abierto.
- **Casos:** cada captura real vive dentro de una ventana de navegador con controles, dominio y estado de publicación; ficha de dos datos y enlace externo con `rel="noopener noreferrer"`.
- **Testimonios:** slider con una cita por vez, animación direccional al cambiar, avance automático cada 7 s, barra de progreso, pausa y controles anterior/siguiente. Se detiene al pasar el puntero o el foco, fuera de pantalla, con la pestaña oculta y con movimiento reducido.
- **Equipo:** tres etapas con retrato circular de 5.5 rem y cabecera horizontal (foto, nombre y cargo), carril de progreso y paso activo según el scroll; los retratos pasan de escala de grises a color al activarse. En escritorio el marcador se desplaza en horizontal y en móvil la línea gira a vertical. La animación empieza antes y termina cuando la sección aún está en pantalla.
- **Formulario:** campos con filete inferior, errores en línea con `aria-live`, casilla de datos obligatoria y estado de éxito que declara que es una demostración local.
- **Pie:** cuatro columnas, logos de redes sin enlaces confirmados y copyright.

## Accesibilidad

- El tema y el menú exponen estados con `aria-pressed` y `aria-expanded`; verificar contraste y teclado en ambos temas antes de publicar.
- El slider de testimonios avanza cada 7 s, pero ofrece pausa visible. Se detiene con hover, foco, fuera de pantalla, pestaña oculta o `prefers-reduced-motion`; solo hay una cita visible.
- En «Quiénes somos», cada perfil es un paso de una secuencia; el paso activo comunica el scroll (`aria-current="step"`).
- `aria-pressed` en el botón de tema y en las filas de la vista previa; `aria-expanded` en el menú móvil; `hidden` real en el menú cerrado.
- El formulario expone `aria-invalid` y mensajes con `aria-live="polite"`; el primer campo inválido recibe el foco.
- `prefers-reduced-motion` mantiene la información, desactiva el autoplay y oculta el marcador móvil del proceso sin desactivar el estado activo.
- Foco visible coral en todo el sitio; enlace de salto al contenido.
- Los números del mono usan `font-variant-numeric: tabular-nums`.
- La barra de desplazamiento está tematizada con los tokens del tema.

## Pendientes

1. **Número de WhatsApp:** el botón abre WhatsApp con texto preparado, pero no dirige a una cuenta de Dampak hasta agregar el número oficial.
2. **Testimonios:** las tres citas son ejemplos ficticios y están rotuladas en la interfaz; reemplazarlas por citas reales autorizadas.
3. **Textos legales:** los tres documentos son plantillas; deben pasar por revisión jurídica.
4. **Fotos del equipo:** los retratos se recortan en círculo con `object-fit: cover`. Si algún archivo sigue siendo un marcador neutro, reemplazarlo por un retrato autorizado conservando el nombre y actualizando el `alt`.
5. **Redes sociales:** los logos ya están; faltan las URLs reales.
