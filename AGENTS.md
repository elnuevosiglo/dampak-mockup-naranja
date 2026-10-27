# Guía de trabajo — Propuesta 06

Estas instrucciones aplican a `dampak-mockup-naranja/`. Es una maqueta independiente; su variante verde vive en `dampak-mockup-verde/`. No mezcles assets ni tokens entre las dos carpetas ni modifiques las propuestas 01–05 para cambiar esta página.

## Antes de editar

- Conserva el orden de página: Header, Apertura, Servicios, Casos de éxito, Qué opinan nuestros clientes, Quiénes somos, Contacto y Footer.
- Revisa primero `DESIGN.md` y este archivo. Mantén la identidad naranja de esta carpeta, el tema oscuro inicial y el selector claro/oscuro.
- La palabra «Hagamos» debe permanecer en una línea a 320 px o más; conserva `white-space: nowrap`. El titular completo ocupa tres líneas y solo «Hagamos» lleva fondo de color.
- La vista previa y las siete capturas de casos usan ventana de navegador con dominio visible. Los tres puntos son coral, amarillo y verde, en ese orden.
- Las opiniones son un slider automático cada 7 s, con animación y pausa visible. El equipo conserva el carril de progreso enlazado al scroll y retratos circulares de 5.5 rem en una cabecera horizontal.
- Las secciones, incluido contacto y footer, usan `--max: 1440px` y el mismo canalón exterior.
- Las ventanas de navegador de la vista previa y los siete casos comparten la barra de macOS (`browser-dots`, dominio, estado publicado).
- Testimonios: slider automático con pausa, transición direccional y controles manuales. Equipo: progreso ligado al scroll, paso activo con `aria-current="step"`.
- Las secciones principales comparten el contenedor máximo `--max: 1440px`.
- Testimonios, contacto y footer usan fondo a todo el ancho; conserva su contenido alineado al mismo contenedor de 1440 px.
- Usa el skill Impeccable para cualquier cambio de interfaz. Respeta su guía de responsive, accesibilidad, movimiento reducido y calidad visual.
- No reemplaces ni edites otras propuestas para resolver una necesidad de esta carpeta.

## Preparación para CMS

El HTML actual es una demostración estática, no una integración de CMS. Al migrarlo:

- Separa contenido y presentación. No guardes contenido editable dentro de CSS o JavaScript.
- Modela secciones, servicios, proyectos, testimonios y personas como colecciones editables; los textos, imágenes, enlaces, orden y estados de publicación deben poder cambiar sin tocar plantillas.
- Conserva campos legibles y estables: `title`, `slug`, `summary`, `body`, `image`, `imageAlt`, `url`, `category`, `sortOrder`, `published` y `updatedAt` según aplique.
- Los servicios deben admitir título, resumen, descripción, alcance y lista de entregables.
- Los casos deben admitir nombre, categoría, descripción, foco, experiencia, URL pública, capturas y texto alternativo. No atribuyas tecnologías ni resultados que no estén confirmados.
- Los testimonios deben guardar cita, nombre, cargo, organización, autorización de publicación y estado. No publiques contenido sin aprobación explícita.
- Los perfiles deben admitir nombre, cargo, formación, presentación, correo y retrato autorizado. Los archivos actuales de `assets/team/` son marcadores neutros, no retratos reales; sustitúyelos por fotos autorizadas con los mismos nombres.
- Mantén las políticas legales como páginas administrables y somételas a revisión profesional antes de publicar.
- Mantén los identificadores de sección únicos y los enlaces internos basados en slug para que la navegación sobreviva a la migración.
- El formulario de esta maqueta no envía datos. Al conectarlo al CMS o a un servicio, agrega validación del lado del servidor, protección contra abuso, almacenamiento seguro y una política de tratamiento vigente.

## Contenido y voz

- Escribe en español colombiano neutro, usando «tú» y «cuéntanos»; no uses voseo ni expresiones rioplatenses.
- Prefiere frases directas, cálidas y específicas. No añadas métricas, premios, promesas de resultados, clientes o capacidades no verificadas.
- Los testimonios actuales son ejemplos ficticios solicitados para visualizar el bloque. Deben conservar su aviso y reemplazarse por citas reales autorizadas antes de publicar.
- Falta confirmar el número oficial de WhatsApp. No inventes uno ni publiques un enlace de destino vacío como si fuera el canal oficial.
- Las cuentas de redes sociales todavía no existen. Los iconos son únicamente una muestra visual; no los conviertas en enlaces sin URLs confirmadas.
- Los textos de las páginas legales son borradores de propuesta, no asesoría jurídica ni documentos aprobados.

## Responsive, accesibilidad y movimiento

- Diseña y verifica escritorio, tablet y móvil; evita desbordamiento horizontal y conserva el orden de lectura en pantallas estrechas.
- Usa HTML semántico, etiquetas asociadas a sus controles, foco visible, contraste suficiente y mensajes de validación accesibles.
- Respeta `prefers-reduced-motion`; toda información debe seguir disponible sin animaciones. El estado activo del equipo permanece legible aunque se oculte el marcador móvil.
- El autoplay de la apertura avanza cada 4,2 s y el de opiniones cada 7 s; ambos se pausan con hover/foco, fuera de pantalla y con la pestaña oculta. El carril del equipo conserva el estado activo, pero oculta su marcador en movimiento.
- El autoavance de la vista previa es 4,2 s, se pausa en hover/foco, fuera de pantalla y con la pestaña oculta; no lo aceleres por debajo de una lectura cómoda.
- No elimines textos alternativos ni estados accesibles para simplificar una integración futura.
