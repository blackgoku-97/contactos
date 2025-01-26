**Proyecto de Sistema de Contactos**

## 1. **Introducción**

El proyecto consiste en una aplicación web que permite la gestión de contactos.

## 2. **Requisitos**

### 2.1. **Requisitos funcionales**
* Contactos:

    * El sistema debe permitir la creacion de nuevos contactos.
    * El sistema debe permitir la modificación de contactos.
    * El sistema debe permitir la eliminación de contactos.

### 2.2. **Requisitos Previos**

Antes de proceder, asegúrate de tener estos programas en el equipo:

* **JDK 21**
* **IntelliJ IDEA** (Puede usar cualquier IDE de Java o editor de programación)
* **Brave** (Navegador web puede usar cualquier navegador web) 

### 2.3. **Herramientas**

* Java: Lenguaje de programación utilizado para el desarrollo.
* Spring Boot: Framework de Java para el desarrollo.
* Spring Web: Dependencia de Spring para la integración de servicios web.
* Spring Data JPA: Dependencia de Spring para la integración con bases de datos.
* Spring Boot DevTools: Herramienta de desarrollo (Opcional)
* Thymeleaf: Motor de plantillas para la generación de vistas.
* Lombok: Anotaciones para mejorar la legibilidad del código.
* MySQL Driver: Driver de conexión con MySQL.
* MySQL: Sistema de gestión de bases de datos.
* Maven: Gestor de dependencias.
* GitHub: Sistema de control de versiones.
* Intellij IDEA: IDE de programación.

### 2.4. **Función de la Aplicación**

Para ejecutar el proyecto es necesario seguir estos pasos:

2.4.1. Crear variables de entorno

* DB_HOST: Host de la base de datos.
* DB_PORT: Puerto de la base de datos.
* DB_NAME: Nombre de la base de datos.
* DB_USER: Nombre de usuario de la base de datos.
* DB_PASSWORD: Contraseña de la base de datos.

2.4.2. Verifica la configuración y ejecuta el proyecto:

* Asegúrate de que todas las configuraciones estén correctas.
* Ejecuta el proyecto desde tu IDE.

## 3. **Funcionamiento**

* La aplicación solicita la creacion de un nuevo contacto. Utiliza el formulario para ingresar los datos del contacto.
* El contacto se guarda en la base de datos y se muestra en la tabla de contactos.
* Los contactos se pueden editar y eliminar.

## 4. **Licencia**

Este proyecto está licenciado bajo los términos de la [MIT License](LICENSE).
