# Hidrantes - GitHub Pages

Esta carpeta esta lista para publicarse como web estatica en GitHub Pages.

## Subida rapida

1. Crea un repositorio en GitHub, por ejemplo `hidrantes`.
2. Sube todos los archivos de esta carpeta a la raiz del repositorio.
3. En GitHub, entra en `Settings > Pages`.
4. En `Build and deployment`, elige `Deploy from a branch`.
5. Selecciona la rama `main` y la carpeta `/root`.
6. Guarda y espera a que GitHub publique la URL.

La app funciona bien tanto en:

- `https://usuario.github.io/hidrantes/`
- `https://usuario.github.io/`

## Notas

- No necesita servidor ni base de datos.
- Los registros y fotos se guardan en el navegador del dispositivo con IndexedDB.
- Para instalarla como PWA, abre la URL publicada desde Chrome/Edge y usa `Instalar`.
- Si cambias archivos y el movil sigue mostrando una version antigua, abre la app una vez con conexion y recarga. El service worker usa la cache `hidrantes-github-pages-v2`.
