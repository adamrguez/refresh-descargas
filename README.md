# Refresh para Windows

Instaladores de **Refresh**, el sistema gratis para talleres de reparación.

**Descargar:** https://refresh.do/descargar
(enlace directo a la última versión: https://github.com/adamrguez/refresh-descargas/releases/latest/download/Refresh-Instalador.exe)

El código del programa está en el repositorio de Refresh. Este repositorio solo publica el
instalador: `instalador/` tiene el `.exe` partido en piezas de menos de 100 MB, y el workflow
`Publicar instalador` las une, comprueba el SHA-256 y lo sube como Release.

## Refresh Mudanza

`mudanza/` tiene el instalador de **Refresh Mudanza** (trae los datos de otro programa a Refresh) y su
extensión para Chrome y Edge, con su `SHA256` y su `VERSION`. El workflow `Publicar Mudanza` los sube al
Release fijo `mudanza`, sin marcarlo como el último.

**Descargar:** https://refreshtaller.com/mudanza

- https://github.com/adamrguez/refresh-descargas/releases/download/mudanza/Refresh-Mudanza-Instalador.exe
- https://github.com/adamrguez/refresh-descargas/releases/download/mudanza/Refresh-Mudanza-Extension.zip

Los dos archivos salen del workflow «Mudanza (Windows y extensión)» del repositorio de Refresh, que los
compila y los prueba en Windows: para una versión nueva se copian aquí con su `SHA256` y su `VERSION`.
