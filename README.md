# Publicación en GitHub Pages

## Archivos
- `index.html`: página principal del sitio.
- `.nojekyll`: evita que GitHub Pages procese el sitio con Jekyll.

## Pasos para publicar
1. En GitHub, crea un repositorio nuevo.
2. Sube `index.html` y `.nojekyll` a la raíz del repositorio (no dentro de otra carpeta).
3. Abre **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)`, y guarda.
6. Espera a que termine la publicación. GitHub mostrará la dirección del sitio en la sección **Pages**.

## Importante sobre seguridad
GitHub Pages publica contenido estático y no protege información confidencial por sí solo. Si esta página contiene un formulario de acceso o una contraseña implementada únicamente en HTML/JavaScript, eso no debe considerarse una protección segura: el código puede inspeccionarse y los archivos publicados pueden ser accesibles. No publiques contraseñas, datos personales, informes internos ni información confidencial en este repositorio público. Para un sitio operativo interno, utiliza un repositorio privado según las opciones disponibles y un sistema de autenticación real; ten en cuenta que hacer privado el repositorio no siempre significa que el sitio publicado quede restringido, dependiendo del plan y la configuración.
