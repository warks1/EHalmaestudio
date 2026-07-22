EH ALMA ESTUDIO — BETA FUNCIONAL v0.2

NOVEDADES DE ESTA VERSIÓN
- Dos espacios editables para imágenes destacadas en la página principal.
- Las imágenes se pueden añadir, cambiar o eliminar desde la propia portada.
- Nueva pestaña Calculadora con catálogo de servicios, cantidades y descuento.
- Editor de servicios y tarifas: permite añadir, modificar o eliminar precios.
- El total calculado puede enviarse directamente al formulario Nueva visita.
- Botón «Editar ficha» más visible dentro de cada clienta.
- Al guardar una corrección, la aplicación vuelve a mostrar la ficha actualizada.
- Conserva automáticamente los datos guardados en la beta v0.1.

PRECIOS INICIALES
Se han incluido únicamente los importes ya confirmados: corte de caballero (24 €), pack color + corte + brushing corto (85 €) y largo (110 €). El resto aparece con precio 0 para que podáis completar vuestra tarifa exacta desde Calculadora > Editar precios.

FUNCIONES CONSERVADAS
- Pantalla principal y estadísticas.
- Fichas de clientes, alta, edición y eliminación.
- Registro de visitas, fórmulas, importes y fotografías.
- Historial técnico.
- Pestaña permanente de Booksy con enlace configurable.
- Copia de seguridad e importación en JSON.
- Instalación como aplicación web (PWA).

CÓMO PROBARLA
1. Descomprime la carpeta.
2. En una terminal dentro de la carpeta ejecuta:
   python3 -m http.server 8000
3. Abre http://localhost:8000 en el navegador.

Para publicarla en GitHub Pages, sube todos los archivos conservando las carpetas.

IMPORTANTE SOBRE LOS DATOS
Esta beta guarda los datos y las imágenes en el navegador del dispositivo. Todavía no existe base de datos en la nube ni acceso con contraseña. Usa Ajustes > Descargar copia JSON para conservar copias periódicas.
