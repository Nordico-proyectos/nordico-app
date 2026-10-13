# Nórdico · App móvil (Android)

Versiones de la app móvil de Hielo Nórdico para los perfiles **Preventista** y **Planta**.

Cada versión se publica en [Releases](../../releases) con su APK y la lista de cambios.

## Cómo instalarla

1. Entrá a [Releases](../../releases) y abrí la versión más nueva (**Latest**).
2. En **Assets**, descargá el archivo `nordico-<versión>.apk` desde el celular.
3. Abrí el archivo descargado. Si Android lo pide, permití **instalar apps de fuentes desconocidas** para el navegador o el gestor de archivos.
4. Abrí la app e iniciá sesión con tu usuario.

> **Antes de instalar, desinstalá la versión anterior de la app** (la que llegó por Firebase). Después instalá el APK nuevo e iniciá sesión de nuevo.

## Actualizaciones

- Los arreglos chicos llegan **solos** al abrir la app (Shorebird). No hace falta volver a descargar nada: cerrá la app y abrila de nuevo para aplicarlos.
- Solo cuando sale una **versión nueva** en Releases hay que descargar e instalar el APK otra vez.

## Para el equipo de desarrollo

- El código fuente está en `Nordico-proyectos/nordico-ui`.
- El APK de cada release tiene que ser el que genera `shorebird release android --artifact apk`, firmado con la llave de producción. Un APK recompilado de otra forma no recibe los parches.
