# Proyecto ERP - Grupo X — Documentación de Arquitectura

Repositorio de documentación de arquitectura de software para el 
Módulo de Compras del Sistema ERP, desarrollado como taller de la 
asignatura Software Patterns and Design en la Universidad Manuela 
Beltrán.

## Objetivo del taller

Este taller guía a los estudiantes a través de un ciclo de vida de 
desarrollo de software, desde la captura de requisitos ágiles hasta el 
diseño de una arquitectura documentada profesionalmente, mediante:

- Un backlog de producto gestionado en Jira.
- Diagramas de arquitectura de alto nivel con el modelo **C4** (Contexto 
  y Contenedores).
- Diseño detallado de una historia de usuario con **UML** (diagrama de 
  secuencia y modelo Entidad-Relación).
- Documentación consolidada usando la plantilla **arc42**.

## Enlaces principales

- 📋 **Tablero de gestión ágil (Jira)**: [enlace al tablero](https://jcamilocespedes2507.atlassian.net/jira/software/projects/PEGX/list?jql=project+%3D+PEGX+ORDER+BY+cf%5B10019%5D+ASC&atlOrigin=eyJpIjoiZDVjMzE0YjZlZjUwNDFiOGI2ODlhNDliNDRhYzViYzkiLCJwIjoiaiJ9)
- 📄 **Documentación de arquitectura (arc42)**: [`docs/arc42-template-EN-plain-markdown/arc42-template-EN.md`](docs/arc42-template-EN-plain-markdown/arc42-template-EN.md)

## Estructura del repositorio
erp-software-architecture/
├── docs/
│ ├── arc42-template-EN-plain-markdown/
│ │ └── arc42-template-EN.md # Documentación de arquitectura arc42
│ └── images/
│ ├── c1_context.png # Diagrama de Contexto (C1)
│ ├── c2_containers.png # Diagrama de Contenedores (C2)
│ ├── sequence_registrar_producto.png # Diagrama de secuencia
│ └── mer_compras.png # Modelo Entidad-Relación
└── README.md

## Resumen del Módulo de Compras

El Módulo de Compras permite:
- Registrar y consultar productos del catálogo.
- Registrar proveedores.
- Asociar precios de un mismo producto a distintos proveedores.
- Generar órdenes de compra.

## Arquitectura

- **Frontend**: Single-Page Application (React)
- **Backend**: API REST monolítica (Java, Spring Boot)
- **Base de datos**: PostgreSQL
- **Comunicación**: HTTPS/JSON

Ver el detalle completo en la [documentación arc42](docs/arc42-template-EN-plain-markdown/arc42-template-EN.md).

## Autor

Camilo — Software Engineering, Universidad Manuela Beltrán