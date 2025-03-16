# Proyecto LAMP y LEMP para Prestashop

Este proyecto ofrece dos entornos de desarrollo funcionales para Prestashop utilizando LAMP (Linux, Apache, MySQL y PHP) y LEMP (Linux, Nginx, MySQL y PHP).

## 🚀 Instalación y Ejecución

1. **Descargar y descomprimir el archivo .zip del repositorio**.

2. **Levantar el entorno deseado con el siguiente comando**:

   - Para el entorno LAMP:
     ```bash
     docker compose -f compose-lamp.dev.yml up --build
     ```

   - Para el entorno LEMP:
     ```bash
     docker compose -f compose-lemp.dev.yml up --build
     ```

3. **Configurar la conexión a la base de datos**:

   Introducir las credenciales de la base de datos que se encuentran en el archivo `.env` del aula virtual.

## 📌 Notas

- Ambos entornos han sido comprobados y funcionan correctamente.
- Se envían sin la instalación previa de Prestashop debido a un error de permisos que ocurría tras comprimir la carpeta con los entornos ya instalados.
- Para probar la funcionalidad del proyecto hay que poner la ruta test.lan en el navegador.
- Funciona tanto para http como https.
