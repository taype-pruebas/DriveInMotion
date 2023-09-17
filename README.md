# Autocine Drive In Motion

Este proyecto implementa un sistema de autocine basado en microservicios utilizando Spring Boot, Thymeleaf, Bootstrap y MySQL.

## Características

- **Microservicios**: La aplicación está dividida en microservicios independientes, cada uno con su propia funcionalidad.
- **Thymeleaf y Bootstrap**: Utiliza Thymeleaf como motor de plantillas y Bootstrap para el diseño y estilo de la interfaz de usuario.
- **Persistencia en MySQL**: La información se almacena en una base de datos MySQL.
- **Arquitectura escalable**: Los microservicios permiten una arquitectura escalable y modular, facilitando la administración y el despliegue.

## Microservicios

- **Autocine Service**: Gestiona las proyecciones de películas, horarios y disponibilidad de espacios.
- **Usuario Service**: Maneja el registro y autenticación de usuarios.
- **Reserva Service**: Controla las reservas de boletos y asientos.

## Tecnologías Utilizadas

- Spring Boot 3
- Thymeleaf
- Bootstrap
- MySQL
- Java 20

## Requisitos

- Java 20 o superior instalado
- MySQL instalado y configurado
- Un IDE Java (recomendado: IntelliJ IDEA)

## Configuración

1. Clona el repositorio: `git clone https://github.com/tu-usuario/autocine-microservicios.git`
2. Configura la base de datos en `application.properties`.
3. Ejecuta cada microservicio por separado.

## Iniciar la Aplicación

1. Abre cada microservicio en tu IDE.
2. Ejecuta el archivo `AutocineApplication.java` en cada microservicio.
3. La aplicación estará disponible en `http://localhost:8080` por defecto.

## Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras un error o tienes una idea para mejorar el proyecto, no dudes en abrir un issue o enviar un pull request
