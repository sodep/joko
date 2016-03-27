---
layout: default
title:  "Devops"
date:   2016-03-27 16:00:41
categories: joko update
---

Desde aproximadamente el año 2009, se popularizó el término [Devops](https://en.wikipedia.org/wiki/DevOps) (Development + Operations), como la convergencia y colaboración entre tres áreas escenciales para producir un sistema complejo: 

- Desarrollo
- Operaciones (Infraestructura, seguridad, etc.)
- Quality Assurance (QA). 

[Diagrama de Venn para Devops](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/Devops.svg/330px-Devops.svg.png)

Joko contempla los siguientes aspectos de las tareas de Devops:

1. Entornos de desarrollo y ejecución: 
- Proveedor y versión de Java development/runtime: JDK 8
- Proveedor y versiones de servidores de aplicaciones: Apache Tomcat 8.x
- Proveedor y versiones para versionado de código: Github
- Proveedor y versionado de base de datos relacionales: Postgres 9.x, H2 1.x, Liquibase 3.4.x)
- Sistema operativo de ejecución (desarrollo, homologación, producción): Ubuntu LTS (Current 14.04, Upcoming: 16.04 LTS).
- Entorno de desarrollo: IDE, herramientas de integración y pruebas

2. Continuous Integration y Continuous delivery:
- Puppet 
- Jenkins 
3. Code review y Quality Assurance: 
- Gerrit
- Findbugs
- Sonarqube
