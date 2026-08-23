SIMULACIÓN DE FEED PARA ESTUDIO EXPERIMENTAL

ESTRUCTURA
instagram_feed_estudio/
├── index.html
└── images/
    ├── post01.jpg ... post08.jpg
    └── profile01.jpg ... profile08.jpg

QUÉ MODIFICAR
1. Abre index.html en un editor de texto.
2. Busca: const posts = [
3. En cada objeto puedes cambiar:
   - username
   - profileImage
   - image
   - imageAlt
   - aspectRatio
   - location
   - likes
   - caption
   - comments
   - totalComments
   - date
4. Reemplaza las imágenes de ejemplo dentro de /images conservando los nombres,
   o cambia las rutas en el array.
5. Si una imagen no es 4:5, actualiza aspectRatio para reservar el espacio correcto.

PRIVACIDAD
El archivo no incluye cookies, analytics, trackers, localStorage, formularios,
inicio de sesión ni conexiones con Instagram.

PUBLICACIÓN EN GITHUB PAGES
1. Crea un repositorio nuevo en GitHub.
2. Sube index.html y la carpeta images.
3. Ve a Settings > Pages.
4. En Build and deployment, selecciona Deploy from a branch.
5. Elige branch main y carpeta /(root).
6. Guarda.
7. GitHub mostrará la URL pública cuando termine el despliegue.
