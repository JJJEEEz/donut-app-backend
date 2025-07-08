# 🍩 Donut App - Backend

Este es el backend del proyecto **Donut App**, una API REST creada con **Spring Boot** y **PostgreSQL** como base de datos. Es un sistema que simula una tienda digital con productos categorizados, usuarios y operaciones básicas como el manejo de carritos y pedidos.

---

## 🛠 Tecnologías utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Maven
- PgAdmin
- Postman (para pruebas)

---

## 🎯 Objetivos del proyecto

Este proyecto fue uno de mis primeros proyectos en Spring Boot, y me ayudó a comprender los fundamentos de:

- Conexión con bases de datos (PostgreSQL)
- Modelado de entidades con relaciones
- CRUD con JPA/Hibernate
- Creación de APIs REST
- Buenas prácticas con `.gitignore`
- Estructura por capas en Java

---

## 🧩 Funcionalidades

- Consultar todos los productos
- Consultar productos por ID
- Registrar productos nuevos
- Eliminar productos
- Relación entre productos y categorías
- Registro básico de usuarios
- Preparado para manejar carritos y pedidos

---

## 🧪 Endpoints disponibles

| Método | Endpoint                  | Descripción                    |
|--------|---------------------------|--------------------------------|
| GET    | `/api/products`           | Listar todos los productos     |
| GET    | `/api/products/{id}`      | Obtener un producto por ID     |
| POST   | `/api/products`           | Crear un producto nuevo        |
| DELETE | `/api/products/{id}`      | Eliminar producto por ID       |

---

## 🗄 Configuración de la base de datos

**Base de datos:** `donut-app-3a`

En `application.properties`:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/donut-app-3a
spring.datasource.username=postgres
spring.datasource.password=TU_CONTRASEÑA
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

---

## 📷 Imágenes  
Las imágenes de los productos se almacenan en una carpeta local (`img/`) y se referencian mediante URLs simples en los registros de la base de datos, como:

- img/donut-glaseada.jpg
- img/pizza-jamon.jpg

---


---

## 📝 Notas  
Este proyecto es **solo backend**, pero está preparado para conectarse fácilmente a un frontend como una app móvil o SPA.

- La contraseña del usuario puede ir en **texto plano por ahora**, pensando en implementar seguridad más adelante.  
- El código fue estructurado para crecer con lógica de **carrito de compras**, **pedidos** e **historial de compras**.

---

## 📚 Aprendizajes  
Este proyecto me permitió comprender la integración entre **Spring Boot** y **PostgreSQL**, y cómo estructurar un backend profesional siguiendo buenas prácticas.  
También practiqué el uso de controladores, repositorios y entidades con relaciones.

---

## © Autor  
**Juan Pérez**  
Estudiante de Ingeniería en Software  
GitHub: [@JJJEEEz](https://github.com/JJJEEEz)
