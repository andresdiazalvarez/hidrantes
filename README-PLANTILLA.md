# Plantilla base de aplicación

Esta carpeta es una copia de la aplicación de Extintores preparada para usarla como base en otras aplicaciones.

La aplicación original de Extintores no se debe tocar cuando se quiera crear una app nueva. Para crear una nueva, se copia esta carpeta y se adapta.

## Archivos principales

- `index.html`: estructura de pantallas y botones.
- `app.js`: funcionamiento de la aplicación, registros, fotos, voz y exportación.
- `styles.css`: diseño general.
- `photos.css`: diseño de las pantallas de fotos, tablas y detalle.
- `manifest.webmanifest`: nombre de la app cuando se instala en el móvil.
- `sw.js`: caché para que funcione como aplicación instalada.
- `icon.svg`: icono de la aplicación.
- `exceljs.min.js`: librería para crear Excel con imágenes.
- `vendor/fflate.js`: librería usada para trabajar con Excel.

## Qué se suele cambiar para una app nueva

1. Nombre de la aplicación.
2. Textos de la pantalla principal.
3. Campos del formulario.
4. Listas de defectos u opciones.
5. Nombre de los registros guardados.
6. Formato de exportación Excel.
7. Icono y colores, si se quiere diferenciar.

## Recomendación

Para crear otra aplicación:

1. Copiar esta carpeta.
2. Cambiarle el nombre, por ejemplo `Plantilla-App-Base` → `Nueva-App`.
3. Adaptar los campos y textos.
4. Probarla en el ordenador.
5. Subirla a un repositorio nuevo de GitHub.

Así se conserva la aplicación de Extintores funcionando y usamos esta como molde.
