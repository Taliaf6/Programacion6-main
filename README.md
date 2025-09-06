# Programación VI  
**| API REST con .NET Core**

## 📌 Descripción General

Este proyecto consiste en el desarrollo de una **API REST utilizando .NET Core Web API**, orientada a demostrar el dominio de arquitectura de software, servicios web y persistencia de datos. La solución implementa al menos una de las operaciones CRUD (Create, Read, Update, Delete), también conocidas como ABCC (Altas, Bajas, Cambios y Consultas), sobre una base de datos relacional.

La aplicación está diseñada para que los **controladores interactúen exclusivamente con servicios internos**, respetando el principio de separación de responsabilidades. La base de datos utilizada **no es accesible directamente** por aplicaciones externas, garantizando que toda interacción se realice a través del servicio REST.



Este proyecto responde a los requerimientos de la materia **Programación VI**.

## 🛠️ Tecnologías Utilizadas

- **.NET Core 6.0** – Framework principal para la construcción de la Web API  
- **Entity Framework Core** – ORM para el acceso a datos  
- **SQL Server / PostgreSQL / MySQL** – Motor de base de datos (según elección del alumno)  
- **Swagger** – Documentación interactiva de la API  
- **Postman** – Herramienta para pruebas de endpoints  
- **GitHub** – Control de versiones y colaboración


## 🔄 Operaciones CRUD Implementadas

La API implementa al menos una de las siguientes operaciones:

- **Create (Alta)**: Registro de nuevas entidades  
- **Read (Consulta)**: Recuperación de datos específicos o listados  
- **Update (Cambio)**: Modificación de registros existentes  
- **Delete (Baja)**: Eliminación lógica o física de registros

## 🧩 Arquitectura de la Solución

```plaintext
[Cliente/API Consumer]
        ↓
[Controlador] → [Servicio] → [Repositorio] → [Base de Datos]


