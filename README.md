<h1 align="center">Proyecto Foro Hub API</h1>

<p align="center">
  <img src="src/main/resources/static/img/Inicio-foro-hub.png" alt="Foro Hub" width="50%">
</p>

## Tabla de Contenido
- [Objetivos](#objetivos)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Configuración al Crear el Proyecto en Spring Initializr](#configuración-al-crear-el-proyecto-en-spring-initializr)
- [Dependencias para Agregar al Crear el Proyecto con Spring Initializr](#dependencias-para-agregar-al-crear-el-proyecto-con-spring-initializr)
- [Cómo Usar la API](#cómo-usar-la-api)
- [Funcionalidades del Sistema](#funcionalidades-del-sistema)
- [URL de Funciones](#url-de-funciones)
- [Redes Sociales](#redes-sociales)

## Objetivos
Foro Hub es una aplicación que permite la gestión de foros con funcionalidades de CRUD (Crear, Leer, Actualizar, Eliminar) para varias entidades. Los objetivos principales de la aplicación son:
- Autenticación y Login
- Creación de Perfil para cada usuario autenticado con su respectivo CRUD
- Creación de Tópico con su respectivo CRUD
- Creación de Respuestas con su respectivo CRUD

## Tecnologías Utilizadas
- **Java JDK**: versión 17 en adelante
- **Maven**: versión 4 en adelante
- **Spring**: versión 3.2.3 - [Spring Initializr](https://start.spring.io/)
- **Postgress**: versión 11 en adelante
- **IDE (IntelliJ IDEA)**: opcional

## Configuración al Crear el Proyecto en Spring Initializr
- **Java**: versión 17
- **Maven**: Initializr utiliza la versión 4
- **Spring Boot**: versión 3.2.3
- **Proyecto**: JAR

## Dependencias para Agregar al Crear el Proyecto con Spring Initializr
- Lombok
- Spring Web
- Spring Boot DevTools
- Spring Data JPA
- Flyway Migration
- Postgress Driver
- Validation
- Spring Security

## Cómo Usar la API
1. Modificar el archivo `application.properties` reemplazando las variables `DB_NAME`, `DB_USER`, `DB_PASSWORD` por el nombre de una base de datos creada, el nombre de usuario y contraseña respectivamente o declarando las variables de entorno de su sistema operativo.
2. Ejecutar el archivo `ApiApplication.java`.

## Funcionalidades del Sistema
-  LISTAR PERFIL, TOPICO, RESPUESTA
-  FILTRAR ID
-  ELIMINACIÓN ID
-  CRUD PERFIL, TOPICO, RESPUESTA
-  SUBIDA DE ARCHIVOS
-  LOGIN, AUTENTICACIÓN
-  MANEJO ROLES
-  FILTROS Y PERMISOS DE SEGURIDAD POR ROLES
-  VALIDACIONES
-  MANEJO DE EXCEPCIONES HANDLER

## URL de Funciones
<p>
  <img src="src/main/resources/static/img/Descripcion-general-API.png" alt="Función 1" width="30%">
  <img src="src/main/resources/static/img/pagina-principal.png" alt="Función 2" width="30%">
</p>
<p >
  <img src="src/main/resources/static/img/funciones-perfil.png" alt="Función 2" width="30%">
  <img src="src/main/resources/static/img/funciones-respuestas.png" alt="Función 2" width="30%">
</p>
<p > 
  <img src="src/main/resources/static/img/funciones-Topicos.png" alt="Función 3" width="30%">
  <img src="src/main/resources/static/img/metodos-put-post.png" alt="Función 3" width="30%">
</p>

<p> 
    <img src="src/main/resources/static/img/metodos-put-post.png" alt="Función 3" width="30%">
</p>


## Redes Sociales
- [GitHub](https://github.com/adferatuz)
- [LinkedIn](https://www.linkedin.com/in/adrian-fernandez-606a21248)

