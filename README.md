# Cerebro: creado, caído, redimido

Sitio estático del curso asincrónico de Elba Somoza y Daniela Serraino. No requiere compilación ni servidor.

## Archivos

- `index.html`: la aplicación
- `support.js`: motor de la aplicación (debe estar junto a `index.html`)
- `assets/cerebro.png`: imagen del curso

## Subir a GitHub

1. Crea un repositorio nuevo en github.com (por ejemplo `curso-cerebro`).
2. Pulsa **Add file → Upload files** y arrastra el contenido de esta carpeta (no la carpeta en sí), respetando la subcarpeta `assets`.
3. Pulsa **Commit changes**.

## Publicar en Cloudflare Pages

1. En dash.cloudflare.com ve a **Workers & Pages → Create → Pages**.
2. Opción A, conectado a GitHub: **Connect to Git**, elige el repositorio.
   - Framework preset: **None**
   - Build command: *(vacío)*
   - Build output directory: `/`
3. Opción B, sin GitHub: **Upload assets** y arrastra esta carpeta.
4. Pulsa **Deploy**. Obtendrás una dirección `https://<nombre>.pages.dev`.

## Antes de publicar

- Reemplaza `consultas@correo.com` en `index.html` por el correo real de las docentes.
- Completa la biografía de Daniela Serraino (buscar `Biografía pendiente` en `index.html`).

## Datos de los alumnos

El progreso, las respuestas y las notas se guardan en el navegador de cada alumno (localStorage). No se envían a ningún servidor. Cada alumno puede descargarlas con el botón «Descargar mis respuestas».
