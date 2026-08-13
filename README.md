# Biblia Inercia · cómo publicarla en GitHub Pages

Esta carpeta es autocontenida: `index.html` + `assets/` (videos con *faststart* para
que streameen bien y nombres sin espacios ni acentos, seguros para URLs).

## Publicar (una vez)

1. Crea un repositorio en GitHub (por ejemplo `biblia-inercia`). Puede ser privado
   con GitHub Pages de pago, o público si no hay problema con que la URL sea adivinable.
2. Sube TODO el contenido de esta carpeta a la raíz del repo (index.html y la carpeta assets).
   - Fácil sin terminal: en el repo → **Add file → Upload files** → arrastra `index.html`
     y luego la carpeta `assets` completa.
3. En el repo: **Settings → Pages → Source: Deploy from a branch → Branch: main / (root) → Save**.
4. En 1–2 minutos queda viva en `https://TU-USUARIO.github.io/biblia-inercia/`.

## Actualizar contenido

- ¿Cambió un video o foto? Reemplaza el archivo en `assets/` **con el mismo nombre** y sube el cambio. No hay que tocar el HTML.
- ¿Nuevo asset? Agrégalo a `assets/` con nombre en minúsculas-con-guiones (sin espacios, sin acentos) y referencia `assets/nombre.mp4` en el HTML.

## Notas

- El intro (cerebro + línea) corre al abrir; el botón INICIAR aparece cuando sale la línea (~seg 6). Hay un "saltar intro" discreto arriba a la derecha.
- El video de referencia TVA es un embed de YouTube: requiere internet (en GitHub Pages siempre lo hay).
- Falta la foto del expediente SRP (slot 08-C marcado como pendiente).
