APLICATIVO DE PUNTO DE EQUILIBRIO, RENTABILIDAD, REPARTO Y PLANILLA MYPE

1) PARA USAR EN LAPTOP

- Descomprime esta carpeta.
- Abre una terminal dentro de la carpeta.
- Ejecuta:

  npm install
  npm run dev

- Abre en tu navegador:

  http://localhost:5173

2) PARA USAR EN CELULAR EN LA MISMA RED WIFI

- Deja el aplicativo corriendo en la laptop con:

  npm run dev

- En Windows, abre CMD y ejecuta:

  ipconfig

- Busca tu IPv4. Ejemplo: 192.168.1.35
- En el celular, conectado al mismo WiFi, abre Chrome y entra a:

  http://TU-IP:5173

Ejemplo:

  http://192.168.1.35:5173

3) PARA SUBIR A NETLIFY

Opción recomendada:

- Ejecuta:

  npm install
  npm run build

- Se creará una carpeta llamada dist.
- Entra a Netlify Drop y arrastra la carpeta dist.
- Netlify te dará un enlace público para abrirlo desde laptop o celular.

4) DATOS Y GUARDADO

- El aplicativo guarda los datos en localStorage del navegador.
- Si lo abres en otro celular o navegador, empezará con datos base.
- Para conservar datos, usa siempre el mismo navegador y dispositivo.

5) ARCHIVO PRINCIPAL

- El aplicativo está en:

  src/index.tsx

