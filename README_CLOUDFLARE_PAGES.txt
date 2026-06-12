ALTERNATIVA GRATIS A NETLIFY: CLOUDFLARE PAGES DIRECT UPLOAD

Cloudflare Pages permite subir archivos estáticos ya compilados.

PASOS:
1. Descomprime este ZIP.
2. Abre terminal dentro de la carpeta.
3. Ejecuta:
   npm install
   npm run build
4. Se creará la carpeta dist.
5. Entra a Cloudflare > Workers & Pages > Pages.
6. Crea un proyecto con Direct Upload.
7. Sube la carpeta dist.
8. Cloudflare generará un enlace público para abrirlo desde laptop o celular.

Nota:
- Esta opción es parecida a Netlify Drop.
- Si haces cambios, vuelves a ejecutar npm run build y subes nuevamente dist.
