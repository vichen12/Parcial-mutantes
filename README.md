Ejercicio MercadoLibre - MUTANTES
Descripción
Este proyecto es un ejercicio técnico comúnmente solicitado por MercadoLibre para el puesto de desarrollador backend. En mi caso, fue programado como parte de la materia Desarrollo de Software en la universidad.

El repositorio contiene mi solución, acompañada de gráficos simples y comentarios para facilitar su comprensión.

En el archivo code_explanation.md encontrarás una breve explicación del enunciado del problema y la solución implementada.

Endpoints
Este proyecto incluye dos endpoints principales:

GET: Estadísticas de mutantes

URL local: http://localhost:9000/person/stats
URL en Render: https://parcial-mutantes-pe0r.onrender.com/persona/stats
POST: Guardar persona como mutante

URL local: http://localhost:9000/persona/mutant
URL en Render: https://parcial-mutantes-pe0r.onrender.com/persona/mutant
Nota: Puedes utilizar herramientas como Postman o JMeter para realizar solicitudes a estos endpoints.

Pre-requisitos
Antes de comenzar, asegúrate de contar con los siguientes requisitos:

JDK 17
IDE como IntelliJ IDEA (o cualquier otro de tu preferencia)
Gradle como gestor de dependencias
H2 como base de datos en memoria para desarrollo y pruebas
Dependencias y Tecnologías Utilizadas
El proyecto hace uso de las siguientes tecnologías y dependencias:

Spring Boot Starter Data JPA: Para interactuar con bases de datos mediante JPA.
Spring Boot Starter Web: Para crear APIs RESTful y manejar solicitudes web.
Lombok: Para reducir código repetitivo como getters, setters y constructores.
Spring Boot DevTools: Para agilizar el desarrollo habilitando la recarga automática.
H2 Database: Base de datos en memoria para desarrollo y pruebas.
JUnit Platform Launcher: Para ejecutar pruebas unitarias con JUnit.
Spring Boot Starter Test: Librerías y herramientas necesarias para pruebas unitarias en el proyecto.
¿Cómo ejecutar el proyecto?
Para ejecutar el proyecto sigue estos pasos:

Descargar el proyecto

Clona el repositorio o descarga el archivo ZIP.
Descargar dependencias

Asegúrate de tener todas las dependencias necesarias para correr el proyecto con Gradle.
Ejecutar el proyecto

Inicia la aplicación desde tu IDE o mediante comandos en consola.
Levantar la base de datos H2

Dirígete a: http://localhost:9000/h2-console/ para acceder a la consola de H2.
Probar la API

Puedes probar la API localmente o en Render usando las URLs mencionadas en la sección de Endpoints.
