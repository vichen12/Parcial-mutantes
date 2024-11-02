Ejercicio MercadoLibre - MUTANTES
Descripción
Este es un ejercicio técnico de entrevista que suele ser solicitado en MercadoLibre para el puesto de desarrollador backend. En mi caso, lo programé para la materia "Desarrollo de Software" en la universidad.

En este repositorio encontrarás mi solución, la cual intentaré explicar con algunos gráficos simples y comentarios.

En el documento code_explanation.md encontrarás una breve explicación del enunciado del problema y la solución que implementé.

Pre-requisitos
JDK (17)
IntelliJ IDEA (o cualquier IDE de tu preferencia)
Gradle (Gestor de Dependencias)
H2 (Base de Datos)
Dependencias
Tecnologías Utilizadas
Este proyecto utiliza las siguientes dependencias y tecnologías:

Spring Boot Starter Data JPA: Para interactuar con bases de datos usando JPA.
Spring Boot Starter Web: Para crear APIs RESTful y manejar solicitudes web.
Lombok: Para reducir código repetitivo como getters, setters y constructores.
Spring Boot DevTools: Para acelerar el desarrollo habilitando la recarga automática de la aplicación.
H2 Database: Base de datos en memoria para desarrollo y pruebas.
JUnit Platform Launcher: Para ejecutar pruebas unitarias con JUnit.
Spring Boot Starter Test: Herramientas y librerías necesarias para realizar pruebas unitarias en el proyecto.



¿Cómo ejecutar?
Descargar el proyecto
Descargar las dependencias necesarias para correr el proyecto
Ejecutar el proyecto
Levantar la base de datos H2, navegando a: http://localhost:9000/h2-console/
Puedes probar la API localmente o utilizando render:

En render, con la URL: https://examen-mercadolibre.onrender.com
Prueba la API con Postman o cualquier otro software de tu preferencia:
POST (guardar persona local) http://localhost:9000/persona/mutant
POST (guardar persona render) https://examen-mercadolibre.onrender.com/persona/mutant
GET (recuperar estadísticas) http://localhost:9000/persona/stats