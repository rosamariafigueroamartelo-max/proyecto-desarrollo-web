# VaRo Vet · Bienestar animal

Sitio web de una clínica veterinaria en Sahagún, Córdoba. Proyecto de **Desarrollo Web I** (Ingeniería de Sistemas, Universidad de Córdoba).

**Autoras:** Rosa María Figueroa Martelo y Valentina González Hoyos
**Docente:** Ing. Juan Manuel Muskus Muskus

> Estado: **Primera entrega** (HTML5 semántico y diseño responsive). Siguen JavaScript con APIs y localStorage (Avance 2) y la migración a Vue.js (entrega final).

El diseño sigue los mockups hechos en Penpot para la propuesta (versiones de escritorio y móvil).

## Páginas

| Archivo | Contenido |
| --- | --- |
| `index.html` | Inicio: presentación, servicios destacados y horario |
| `nosotros.html` | Quiénes somos, misión y horario |
| `servicios.html` | Seis servicios en tarjetas |
| `contacto.html` | Dirección, teléfonos, correo, horario y formulario de mensaje |
| `agendar-cita.html` | Formulario de solicitud de cita |

## Estructura

```
varo-vet/
├── index.html
├── nosotros.html
├── servicios.html
├── contacto.html
├── agendar-cita.html
├── css/
│   └── styles.css
├── img/            # fotos, logo, patitas y hojas decorativas
└── README.md
```

## Decisiones técnicas

- **HTML semántico:** `header`, `nav`, `main`, `section`, `article`, `aside` y `footer`, sin `div` innecesarios.
- **Formularios:** validación nativa con `required`, `pattern`, `min`, `max`, `minlength`, `maxlength`, `type="email"`, `type="tel"`, `type="date"` y `type="time"`.
- **Metadatos:** `charset`, `viewport`, `title` y `description` en cada página.
- **Imágenes:** fotos recortadas con forma orgánica, logo en PNG con fondo transparente y decoraciones en SVG.
- **CSS:** `css/styles.css` con Grid para la estructura de página, hero, rejillas y formularios, y Flexbox para navegación, tarjetas, botones y pie de página.
- **Responsive (mobile first):** breakpoints en 768 px (tablet), 1024 px (escritorio) y 1280 px (pantalla grande).
- **Menú móvil:** hamburguesa hecha solo con CSS (checkbox + label), sin JavaScript.
- **CDN:** fuentes Lora, Outfit y Source Sans 3 (Google Fonts) e íconos Font Awesome.
- **Accesibilidad:** enlace para saltar al contenido, `aria-current` en la página activa, foco visible, etiquetas asociadas a cada campo y respeto de `prefers-reduced-motion`.

## Cómo ejecutarlo en local

No requiere instalación. Descomprime la carpeta completa y abre `index.html` en el navegador (o usa Live Server en VS Code). No abras los archivos desde dentro del zip.
