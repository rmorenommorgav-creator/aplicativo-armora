ALTERNATIVA GRATIS A NETLIFY: GITHUB PAGES

Este proyecto está preparado para publicarse en GitHub Pages sin Netlify.

REQUISITOS:
- Tener una cuenta gratuita en GitHub.
- Crear un repositorio nuevo, por ejemplo: aplicativo-armora.

PASOS DESDE GITHUB WEB:
1. Descomprime este ZIP en tu laptop.
2. Entra a github.com y crea un repositorio nuevo.
3. Sube todos los archivos y carpetas del proyecto al repositorio.
   Importante: también debe subirse la carpeta .github/workflows/deploy.yml.
4. En GitHub, entra al repositorio.
5. Ve a Settings > Pages.
6. En Build and deployment, selecciona Source: GitHub Actions.
7. Ve a la pestaña Actions.
8. Ejecuta o espera el workflow: Deploy React app to GitHub Pages.
9. Cuando termine, GitHub mostrará el enlace público.

El enlace normalmente tendrá este formato:
https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/

USO EN CELULAR:
- Abre ese enlace desde Chrome en tu celular.
- Puedes agregarlo a la pantalla de inicio desde el menú de Chrome.

GUARDADO DE DATOS:
- El aplicativo guarda datos en localStorage.
- Si lo abres en otro celular o navegador, los datos no se copian automáticamente.
- Para conservar tus datos, usa siempre el mismo dispositivo/navegador, salvo que luego agreguemos exportar/importar configuración.

USO LOCAL SIN INTERNET:
1. Instala Node.js.
2. Abre una terminal dentro de esta carpeta.
3. Ejecuta:
   npm install
   npm run dev
4. En laptop abre:
   http://localhost:5173
5. En celular conectado al mismo WiFi abre:
   http://IP-DE-TU-LAPTOP:5173
