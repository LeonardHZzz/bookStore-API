# 📚 bookStore-API

> Una API REST moderna y eficiente para gestión integral de librerías digitales

## Descripción del Proyecto

El objetivo principal es proporcionar a los desarrolladores de frontend una base de datos organizada y endpoints eficientes para manejar el flujo completo de una librería, desde la consulta de títulos hasta la administración de stock de forma segura y escalable.

---

## ✨ Funcionalidades Clave

| Característica | Descripción |
|---|---|
| **📖 Catálogo Dinámico** | Gestión completa (CRUD) de libros, incluyendo metadatos como ISBN, autores y editoriales |
| **🔍 Búsqueda Avanzada** | Filtros inteligentes por categoría, precio, fecha de publicación y popularidad |
| **📦 Gestión de Inventario** | Control de existencias en tiempo real con alertas de bajo stock |

---

## 🛠️ Tech Stack

- **Java 11+**
- **Spring Boot**
- **Gradle**

---

## 🚀 Inicio Rápido

### Requisitos Previos
- Java 11 o superior
- Gradle 7.0+

### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/LeonardHZzz/bookStore-API.git
cd bookStore-API

# Compilar el proyecto
./gradlew build

# Ejecutar la aplicación
./gradlew bootRun
```

---

## 📝 Endpoints principales

```
GET    /api/books        - Obtener todos los libros
GET    /api/books/:id    - Obtener libro por ID
POST   /api/books        - Crear nuevo libro
PUT    /api/books/:id    - Actualizar libro
DELETE /api/books/:id    - Eliminar libro
```

---

## 📄 Licencia

Este proyecto está bajo licencia MIT.

---

