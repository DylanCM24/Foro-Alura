ForoHub - API REST para la Gestión de Foros
ForoHub es un sistema backend diseñado para gestionar un foro similar al que usan los estudiantes de Alura Latam para resolver sus dudas sobre cursos y proyectos. Este README proporciona una visión general del proyecto, describiendo su funcionalidad, estructura y las tecnologías empleadas.

Objetivos del Proyecto
El objetivo principal de ForoHub es desarrollar una API REST que permita la gestión completa de tópicos en un foro. Las funcionalidades clave incluyen:

Crear un nuevo tópico
Mostrar todos los tópicos creados
Mostrar un tópico específico
Actualizar un tópico
Eliminar un tópico
Este conjunto de operaciones se conoce comúnmente como CRUD (Crear, Leer, Actualizar, Eliminar).

Tecnologías Utilizadas
ForoHub se construyó utilizando las siguientes tecnologías:

Java 11
Spring Boot 2.5.4
Spring Data JPA
Hibernate
MySQL
Spring Security
Maven
Estructura del Proyecto
El proyecto sigue la arquitectura de capas comúnmente utilizada en aplicaciones Spring Boot:

Controladores (Controllers): Manejan las solicitudes HTTP y las respuestas.
Servicios (Services): Contienen la lógica de negocio y se comunican con los repositorios.
Repositorios (Repositories): Interactúan con la base de datos para realizar operaciones CRUD.
Entidades (Entities): Representan las tablas de la base de datos.
