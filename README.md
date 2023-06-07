# Paquetería Aeropuerto El Dorado

## Descripción
Este proyecto es una aplicación web para gestionar el envío y recepción de paquetes en el Aeropuerto El Dorado. Permite registrar y visualizar información sobre los paquetes, así como generar y descargar informes en formato PDF.

## Funcionalidades
- Registro de paquetes con información detallada.
- Registro de personas con información detallada.
- Visualización de la lista de paquetes registrados.
- Visualización de la lista de personas registradas.
- Generación y descarga de informes en formato PDF con la lista de paquetes.

## Tecnologías utilizadas
- Java
- Spring Framework (Spring Boot, Spring MVC, Spring Data JPA)
- PDFBox (para la generación de archivos PDF)
- MySQL (como base de datos)

## Configuración
1. Clonar este repositorio.
2. Configurar la conexión a la base de datos MySQL en el archivo `application.properties`.
3. Configurar la ruta de los pdfs en el archivo `application.properties`.
4. Ejecutar el proyecto utilizando Maven o una herramienta de desarrollo integrado (IDE) compatible con Spring Boot.

## Uso
1. Acceder a la aplicación a través de la URL: `http://localhost:8080`.
2. Registrar paquetes utilizando el formulario de registro.
3. Visualizar la lista de paquetes registrados.
4. Descargar informes en formato PDF con la lista de paquetes utilizando el botón "Descargar PDF".
