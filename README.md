

<p align="left">
<img src="https://avatars.githubusercontent.com/u/76105412?v=4&s=160">
</p>

## v1.99.20


## Fixes

- ✅ Instalar obras en webOS 11. El dispositivo mantiene la aplicación instalada fuera de /tmp, por lo que el IPK ahora va a /media/developer/temp con el modo 0777, el mismo lugar y modo que se instalan.
- ✅ El archivo remoto obtiene un comando mkdir sobre la transferencia de archivos compartidos. Hace que los padres desaparezcan y funcione en dispositivos sin SFTP, por lo que reemplaza la llamada de shell xargs -0 mkdir.


## Building

- ✅ Las bibliotecas de ares-cli-rs se mueven a v0.6.0.
- ✅ La compilación de Android se ejecuta contra NDK 28, para tamaños de página de 16 KB, y toma OpenSSL 3.6 de nuevo.


## 📄 Licencia

Este proyecto está distribuido bajo la **Licencia MIT**.

Consulta el archivo `LICENSE` para obtener más información.
