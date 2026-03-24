# Trackademic  
**Plataforma para el Control y Análisis del Riesgo Académico**

---

## 🧩 Descripción del Proyecto

Trackademic es una plataforma web desarrollada para la **gestión, seguimiento y análisis del riesgo académico** de los estudiantes en el marco del Sistema de Acompañamiento y Seguimiento Estudiantil (SARA) de la Universidad del Quindío.

El sistema permite integrar datos académicos desde archivos Excel o CSV, gestionar información por parte de docentes y generar **indicadores y dashboards visuales** que facilitan la toma de decisiones oportunas.

---

## 🎯 Objetivo

Desarrollar una plataforma que permita identificar, analizar y visualizar el riesgo académico de los estudiantes mediante el uso de datos estructurados, facilitando el seguimiento por parte de docentes y coordinación académica.

---

## ⚙️ Tecnologías Utilizadas

### Backend
- Java 21
- Spring Boot
- Spring Data JPA
- Spring Security (JWT)
- PostgreSQL
- Apache POI
- Maven

### Frontend (opcional)
- React.js
- Chart.js / Recharts
- Axios

---

## 🏗️ Arquitectura del Sistema

            Frontend (React)
                    ↓
      Backend (Spring Boot API REST)
                    ↓
        Base de Datos (PostgreSQL)


---

## 🔐 Roles del Sistema

### Administrador
- Carga de archivos (Excel/CSV)
- Gestión de usuarios
- Reportes globales

### Docente
- Visualización de materias asignadas
- Registro de notas
- Consulta de rendimiento estudiantil

### Coordinación SARA
- Identificación de estudiantes en riesgo
- Generación de reportes
- Seguimiento académico

---

## 🔄 Flujo del Sistema

1. **Carga de datos**
   - Se importa archivo `.xlsx` o `.csv`
   - Se registran estudiantes, docentes y materias

2. **Gestión docente**
   - El docente visualiza sus cursos
   - Ingresa notas y ponderaciones

3. **Procesamiento**
   - El sistema calcula indicadores académicos
   - Clasifica el nivel de desempeño

4. **Visualización**
   - Se generan dashboards por estudiante

5. **Seguimiento SARA**
   - Consulta de estudiantes en riesgo
   - Generación de reportes

---

## 📊 Funcionalidades Principales

- ✔ Carga masiva de datos desde Excel/CSV  
- ✔ Gestión de estudiantes, docentes y materias  
- ✔ Registro de notas con ponderación  
- ✔ Cálculo automático de rendimiento académico  
- ✔ Clasificación de nivel de desempeño  
- ✔ Dashboard académico por estudiante  
- ✔ Generación de reportes  

---

## 📁 Estructura del Proyecto
            src/main/java/co/edu/uniquindio/sara
            │
            ├── config
            ├── security
            ├── controller
            ├── service
            ├── repository
            ├── model
            ├── dto
            ├── mapper
            ├── exception
            ├── util
            └── importation

---

## 🧠 Entidades Principales

- User → Usuarios del sistema  
- Student → Estudiantes  
- Teacher → Docentes  
- Subject → Materias  
- Enrollment → Relación estudiante-materia  
- Grade → Notas  
- AcademicCondition → Estado académico  

---
