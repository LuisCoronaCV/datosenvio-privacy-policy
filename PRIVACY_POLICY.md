# Política de Privacidad — Datos Envío

**Fecha de vigencia:** 27 de septiembre de 2026

Datos Envío ("la aplicación") es una herramienta local para registrar envíos.
El desarrollador no opera servidores propios ni recopila directamente los
datos de envío de los usuarios. Los datos de clientes, direcciones, teléfonos,
fotografías, notas y demás información registrada por la aplicación permanecen
en el dispositivo, salvo las transferencias que el usuario inicia
expresamente, como abrir una dirección en Maps o exportar un archivo ZIP.

## Datos que procesa la aplicación

Los registros que el usuario crea pueden contener:

- Nombres de clientes, vendedores y notas o folios.
- Direcciones de entrega (calle, números, código postal, alcaldía).
- Teléfonos de contacto.
- Fechas y horarios de entrega, notas e indicaciones.
- Montos de flete, costos y saldos.
- Catálogo de productos.
- Fotografías de evidencia de notas.
- Enlaces de ubicación que el usuario registra.

## Dónde se guardan los datos

Toda la información se almacena únicamente en el dispositivo del usuario, en
la base de datos local y en los archivos internos de la aplicación.

La aplicación:

- No envía sus datos de envío a internet ni a servidores del desarrollador.
- No tiene cuentas de usuario, analítica propia, publicidad ni rastreo.
- No solicita permisos sensibles; la cámara y las fotografías se usan mediante
  los selectores del sistema operativo.

## Copias de seguridad

La copia de seguridad automática de Android está deshabilitada para la base de
datos y los archivos de la aplicación. La aplicación nueva comienza limpia al
instalarse en otro dispositivo.

Para trasladar la información, el usuario puede crear un respaldo **ZIP manual
sin cifrar** que contiene los registros y las fotografías. El usuario decide
dónde guardarlo y es responsable de protegerlo, ya que contiene información
personal. La restauración agrega datos; no reemplaza los registros existentes.

## Acciones que salen del dispositivo por decisión del usuario

La aplicación no comparte datos por sí misma. Existen acciones iniciadas
explícitamente por el usuario que transfieren información a otros destinos:

- **Abrir una dirección en Google Maps:** Datos Envío no envía
  automáticamente datos a Google. Cuando usted toca el botón de Maps,
  usted decide abrir Google Maps con esa dirección; a partir de ese
  momento la información se rige por las políticas de Google.
- **Copiar un resumen al portapapeles:** el resumen queda disponible para
  cualquier aplicación donde el usuario lo pegue.
- **Exportar o importar el respaldo ZIP:** el archivo se guarda o se lee en la
  ubicación que el usuario elija (por ejemplo, su almacenamiento o un servicio
  de nube bajo su control).

## Reconocimiento de texto (OCR)

La extracción de texto de las fotografías se realiza dentro del dispositivo
mediante ML Kit de Google. Las imágenes, el texto reconocido y los resultados
del OCR **no se envían** a servidores de Google ni a terceros.

ML Kit es un SDK de Google y, conforme a su documentación oficial, puede
transmitir a Google **información técnica** del SDK para diagnósticos y
analítica de uso, que puede incluir:

- Información del dispositivo (fabricante, modelo, versión y compilación del
  sistema operativo, aceleradores de hardware disponibles).
- Información de la aplicación (nombre del paquete y versión).
- Identificadores del dispositivo e identificadores por instalación. Los
  identificadores por instalación descritos por Google no están destinados a
  identificar de forma única a un usuario o dispositivo físico.
- Métricas de rendimiento (como la latencia).
- Configuración de la API (formato y resolución de imagen), tamaños de entrada
  y salida, y versión de la función utilizada.
- Tipos de eventos del SDK (inicialización, descarga de modelos, detección,
  liberación de recursos) y códigos de error.

Esta información técnica se transmite cifrada mediante HTTPS y Google indica
que no la comparte con terceros. No incluye el contenido de sus envíos, sus
fotografías ni los textos reconocidos.

## Menores

La aplicación está dirigida a usuarios que gestionan envíos y no está
orientada a menores.

## Cambios a esta política

Si esta política se actualiza, la nueva versión se publicará en la misma URL
pública donde se hospeda este documento.

## Contacto

Para preguntas sobre esta política:

**plazamibebe@gmail.com**
