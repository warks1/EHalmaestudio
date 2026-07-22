EH ALMA ESTUDIO — BETA FUNCIONAL v0.1

QUÉ INCLUYE
- Pantalla principal con estadísticas.
- Fichas de clientes.
- Alta, edición y eliminación de clientes.
- Registro de visitas, fórmulas, importes y fotografías.
- Historial técnico.
- Estadísticas básicas.
- Pestaña permanente de Booksy con enlace configurable.
- Copia de seguridad e importación en JSON.
- Instalación como aplicación web (PWA).

CÓMO PROBARLA
1. Descomprime la carpeta.
2. Para una prueba rápida en ordenador, abre una terminal dentro de la carpeta y ejecuta:
   python3 -m http.server 8000
3. Abre http://localhost:8000 en el navegador.

Para publicarla en GitHub Pages, sube todos los archivos conservando las carpetas.

IMPORTANTE SOBRE LOS DATOS
Esta primera beta guarda los datos en el navegador del dispositivo (localStorage). No existe todavía una base de datos en la nube ni acceso con contraseña. Usa la opción Ajustes > Descargar copia JSON para conservar copias.
