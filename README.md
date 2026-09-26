# ORBIA Releases

Canal público de distribución binaria de ORBIA Desktop.

Este repositorio contiene únicamente paquetes compilados y metadatos de actualización. El código fuente, bases de datos, archivos de clientes, credenciales, certificados y configuraciones privadas permanecen fuera de este repositorio.

Los paquetes oficiales se publican mediante GitHub Releases e incluyen verificación SHA-256.


## Canales de actualización

ORBIA consulta manifests públicos sin necesitar acceso al repositorio privado de código:

- `channels/pilot/latest.json`: PCs piloto reciben primero cada versión.
- `channels/stable/latest.json`: sólo versiones promovidas a uso general.

El manifest usa el contrato `orbia-release.v1` e incluye versión, arquitectura, URL del instalador, tamaño y SHA-256.

Los binarios se publican como GitHub Releases. El canal `stable` exige instalador firmado antes de ser publicable.
