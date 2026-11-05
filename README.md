# Servicios eléctricos: baja y media tensión

Sitio de una sola página para una empresa de servicios eléctricos en Chile: servicios en baja y media tensión, sistemas fotovoltaicos, guía de consultas, normativa SEC y formulario de visita y presupuesto.

## Cómo editarlo
Abre `index.html` y busca el objeto `CONFIG` al inicio del bloque `<script>`. Ahí están los datos de la empresa (nombre, teléfono, WhatsApp, correo, N° de registro SEC), los servicios, la guía, las preguntas frecuentes, los plazos y los parámetros de la calculadora solar. El resto del archivo no necesita cambios.

Para que el formulario envíe las solicitudes a un servicio externo, pon su dirección en `formEndpoint`. Si queda vacío, el formulario prepara el mensaje para enviarlo por WhatsApp o copiarlo.

## Publicarlo con GitHub Pages
1. Sube estos archivos a la raíz del repositorio.
2. En Settings, Pages, elige "Deploy from a branch", rama `main`, carpeta `/ (root)`.
3. En uno o dos minutos el sitio queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

Las referencias normativas son informativas. Verifica siempre el texto oficial vigente en sec.cl y bcn.cl.
