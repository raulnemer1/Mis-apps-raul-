# Mis apps

## Bóveda personal (`boveda-personal/index.html`)

Bóveda cifrada para guardar registros (usuario, clave, enlace, notas y archivos adjuntos) organizados por sección: Registro, Email, Clave general del banco, Inversiones y Zelle.

- Cifrado AES-GCM de 256 bits con clave derivada por PBKDF2-SHA256 (310 000 iteraciones) a partir de la contraseña maestra.
- Los datos se guardan solo en el navegador (IndexedDB); no se sincronizan en línea.
- Respaldo cifrado en JSON, con opciones para restaurarlo y verificarlo.

Copia de la versión publicada en https://claude.ai/artifact/1srcCa9ZnWSBGWKcbHhZax.

> Nota: los botones de descarga (respaldo y adjuntos) usan la capacidad de descargas de los artefactos de claude.ai. Si abres el archivo fuera de claude.ai, esas descargas mostrarán «No se pudo descargar en esta vista».
