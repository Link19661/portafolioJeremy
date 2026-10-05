# Capturas de proyectos

Guardá en esta carpeta las capturas que querás mostrar en el portafolio. Se recomienda WebP o JPG, con buena resolución y sin datos confidenciales.

## Cómo reemplazar una portada

1. Abrí `index.html` y buscá la tarjeta por el nombre del proyecto dentro de `#proyectos`.
2. En esa tarjeta, reemplazá el `<div class="project-art ...">` actual por este bloque. Conservá el número de la tarjeta:

```html
<div class="project-art project-art--image">
  <img
    class="project-screenshot"
    src="assets/image/projects/tabacotrack.webp"
    alt="TabacoTrack: control de producción tabacalera"
  >
  <span class="art-number">01</span>
</div>
```

3. Cambiá el nombre del archivo y el texto de `alt` para describir la captura. La clase `project-art--image` muestra la imagen completa, sin estirarla ni recortarla.

Las portadas actuales son ilustraciones creadas con HTML y CSS; no son capturas de pantalla reales.
