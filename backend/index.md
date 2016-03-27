---
layout: post
title:  "Backend Web"
categories: joko modulos
---


Joko utiliza los patters comunes de Spring para la división en capas de las aplicaciones: 

**Capa de Controllers**

Funcionalidades genéricas:

- BaseController (agrupando típicas operaciones para controllers)

1. Paginación
2. Buscadores con filtro
3. Operaciones tipo CRUD

Listado de componentes soportados por el backend (además de los inputs stándar HTML 5)

1. Grilla de visualización
2. Ventanas Modales
3. File Uploader via Ajax
4. Calendario
5. Árbol
6. Paneles con pestañas (Tabs)
7. Barra de menú (estático y dinámico)

Componentes customizados
1. Selectores modales para relaciones (Foreing Keys de tablas)
2. Sugeridor de resultados al tipear (autocomplete)
3. Selector con multiples opciones

**Capa de negocios/Services**:

BaseBusiness 

- consultas de datos con o sin paginación
- buscadores con filtros
- operaciones básicas CRUD
- Components de Spring

**Capa de acceso a datos** 

- JPA/ORM
- Generación de IDs ofuscados y sin colisiones

Funcionalidades Genéricas Bases de Datos SQL Relacional
Clases Base para todos los Entities (ORM)

Repositories (Spring data)

- consultas de datos con o sin paginación
- buscadores con filtros
- operaciones básicas CRUD
- operaciones directamente con JDBC

Estrategias de transacciones:

- Local Transactions, Niveles de aislamiento y estrategías de llaveado.
- Global Transactions

Funcionalidades Genéricas Bases de Datos NO SQL

- consultas de datos con o sin paginación
- buscadores con filtros
- operaciones básicas CRUD

