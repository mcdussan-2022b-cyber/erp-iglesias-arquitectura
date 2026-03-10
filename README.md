# ERP Iglesias – Análisis y Mejora de Arquitectura de Software

## Descripción del proyecto

Este proyecto corresponde al análisis y mejora de la arquitectura del sistema **ERP Iglesias**, una aplicación diseñada para la gestión administrativa de iglesias.

El sistema permite administrar información relacionada con:

- Personas
- Cursos
- Inscripciones
- Pagos
- Ofrendas

Durante el desarrollo de esta actividad se realizó un **diagnóstico arquitectónico del sistema**, con el objetivo de identificar problemas en la organización del código, validación de datos y manejo de errores.

A partir de este análisis se propusieron mejoras aplicando **buenas prácticas de desarrollo, principios SOLID y patrones de diseño**.

---

# Arquitectura del sistema

El sistema utiliza una arquitectura **cliente-servidor**, donde:

- El **frontend** desarrollado en Angular se comunica con
- Un **backend construido en Java con Spring Boot**
- A través de una **API REST**

La información del sistema se almacena en una base de datos **PostgreSQL**.

Para facilitar la ejecución del proyecto se utiliza **Docker y Docker Compose**, lo que permite levantar todos los servicios del sistema de forma sencilla.

---

# Stack Tecnológico

| Componente | Tecnología |
|------------|------------|
| Backend | Java + Spring Boot |
| Frontend | Angular + TypeScript |
| Base de Datos | PostgreSQL |
| Gestión de dependencias | Maven |
| Infraestructura | Docker |
| Orquestación | Docker Compose |
| Servidor web | Nginx |

---

# Mejoras implementadas

Durante el análisis del sistema se implementaron mejoras en el código para mejorar la organización, seguridad y calidad de los datos.

Entre los cambios realizados se encuentran:

- Implementación de **validaciones en los datos de entrada**
- Uso de **DTO para separar los datos enviados y recibidos**
- Registro de **logs en los controladores**
- Validación automática de solicitudes usando `@Valid`
- Corrección en el proceso de **registro de cursos en la base de datos**

Estas mejoras ayudan a mantener un sistema más organizado, seguro y fácil de mantener.

---
