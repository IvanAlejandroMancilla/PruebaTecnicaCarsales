# Rick and Morty - Prueba Técnica Carsales

![Autor](https://img.shields.io/badge/Autor-Iv%C3%A1n%20Mancilla-lightgrey)  ![.NET](https://img.shields.io/badge/.NET-8.0-512BD4?logo=dotnet&logoColor=white)  ![C#](https://img.shields.io/badge/C%23-12.0-239120?logo=csharp&logoColor=white)  ![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-8.0-512BD4?logo=dotnet&logoColor=white)  ![Swagger](https://img.shields.io/badge/Swagger-OpenAPI-85EA2D?logo=swagger&logoColor=black)  ![Angular](https://img.shields.io/badge/Angular-18.2.21-DD0031?logo=angular&logoColor=white)  
![TypeScript](https://img.shields.io/badge/TypeScript-5.5+-3178C6?logo=typescript&logoColor=white)  
![Node.js](https://img.shields.io/badge/Node.js-18+-339933?logo=node.js&logoColor=white)  
![npm](https://img.shields.io/badge/npm-10+-CB3837?logo=npm&logoColor=white)  
![RxJS](https://img.shields.io/badge/RxJS-7.8+-B7178C?logo=reactivex&logoColor=white)  
![Licencia](https://img.shields.io/badge/Licencia-Unlicense-blue)

Aplicación full-stack para explorar el universo de Rick and Morty: Backend BFF en .NET 8 + Frontend en Angular 18.

---

## 📦 Repositorios

### 1. Backend (.NET 8)
**Repositorio:** [BackendCarsales](https://github.com/IvanAlejandroMancilla/BackendCarsales)

API REST desarrollada en ASP.NET Core 8 que actúa como BFF (Backend For Frontend) consumiendo la API pública de Rick and Morty.

**Tecnologías:**
- .NET 8
- C# 12
- ASP.NET Core Web API
- Swagger/OpenAPI
- HttpClient

---

### 2. Frontend (Angular 18)
**Repositorio:** [FrontendCarsales](https://github.com/IvanAlejandroMancilla/FrontendCarsales)

Single Page Application (SPA) desarrollada con Angular 18 y standalone components que consume el backend BFF.

**Tecnologías:**
- Angular 18.2.21
- TypeScript 5.5+
- RxJS 7.8+
- CSS puro (sin frameworks)
- OpenAPI Generator

---

## 🚀 Instalación y Ejecución

Para instrucciones detalladas de instalación, configuración y ejecución de cada entorno, consulta el README de cada repositorio:

- **Backend:** Ver [README del Backend](https://github.com/IvanAlejandroMancilla/BackendCarsales#readme)
- **Frontend:** Ver [README del Frontend](https://github.com/IvanAlejandroMancilla/FrontendCarsales#readme)

---

## ✨ Características

### Backend
✅ Arquitectura BFF (Backend For Frontend)  
✅ Consumo de API externa con HttpClient  
✅ Documentación automática con Swagger  
✅ CORS configurado  
✅ Inyección de dependencias  
✅ Manejo de errores robusto  

### Frontend
✅ Standalone components (sin módulos)  
✅ Routing con child routes  
✅ Consumo de API REST con RxJS  
✅ Diseño responsivo (CSS Grid/Flexbox)  
✅ TypeScript estricto  
✅ Sin frameworks CSS  

---

## 📂 Endpoints Disponibles

### Backend API

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| GET | `/api/Episode` | Lista de episodios |
| GET | `/api/Episode/{id}` | Detalle de episodio |
| GET | `/api/Character` | Lista de personajes | 
| GET | `/api/Character/{id}` | Detalle de personaje |
| GET | `/api/Location` | Lista de locaciones |
| GET | `/api/Location/{id}` | Detalle de locación |

---

## 🎨 Paleta de Colores

- **Primary**: `#2d7a4f` (Verde oscuro)
- **Secondary**: `#52c77a` (Verde medio)
- **Accent**: `#b0f2c2` (Verde claro)
- **Background**: `#8edba7` (Verde pastel)

---

## 👤 Autor

**Iván Alejandro Mancilla**  
GitHub: [@IvanAlejandroMancilla](https://github.com/IvanAlejandroMancilla)

---

## 📄 Licencia

Este proyecto es parte de una prueba técnica para Carsales.

---

⭐ Si este proyecto te resultó útil, no dudes en dar una estrella a ambos repositorios.
