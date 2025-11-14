# 🏥 Sistema de Gestión de Turnos Médicos – Salud24Ya
Proyecto académico — UNGS — Especificación y Verificación de Software  
Versión 2025

Este repositorio contiene el análisis, documentación y modelado completo de un sistema de **gestión de turnos médicos online** para la red de clínicas *Salud24Ya*.  
El sistema busca modernizar y centralizar la asignación de turnos, ofreciendo registro de pacientes, manejo de agendas médicas y recordatorios automáticos.

---

## 📌 Objetivo del Proyecto
Desarrollar un sistema centralizado que permita:

- Registro seguro de pacientes.
- Login de pacientes, médicos y administradores.
- Búsqueda de profesionales por especialidad, nombre o sucursal.
- Reserva y confirmación de turnos médicos.
- Cancelación/reprogramación con 24 hs de anticipación.
- Envío automático de recordatorios por email y SMS.
- Gestión de agenda por médicos.
- Alta/baja de profesionales y especialidades por administradores.
- Cierre automático de sesión tras 10 minutos de inactividad.

---

## 📂 Contenido del Repositorio
📁 raiz-del-proyecto
├── 📄 BRD - Documento de Requerimientos de Negocio.pdf
├── 📄 Diagramas
│ ├── Diagrama_de_Clases.png
│ ├── Diagramas_de_Secuencia/
│ └── Diagramas_de_Actividad/
├── 📄 Historias_de_Usuario.pdf
├── 📄 Prototipado_UI/
├── 📄 Casos_de_Testing.pdf
└── README.md

Cada carpeta contiene los artefactos generados durante el análisis del sistema según los estándares de UNGS y del proceso de Especificación y Verificación de Software.

---

## 📘 Documentación Incluida

### 🔹 **BRD – Business Requirements Document**
Incluye:
- BR Change History  
- Scope Statement  
- Business Rules  
- Business Requirements  
- Reglas de negocio  
- Requerimientos funcionales y no funcionales  
- Clasificación FURPS+  
- Glosario  

### 🔹 **Diagramas UML**
- Diagrama de clases completo del dominio.  
- Diagramas de secuencia para procesos principales:  
  - Registro  
  - Login  
  - Búsqueda de médico  
  - Reserva de turno  
  - Confirmación y cancelación  
- Diagramas de actividad con procesos paralelos (15 min de confirmación, 10 min de inactividad).

### 🔹 **Historias de Usuario**
Agrupadas según épicas:
- Sistema de Usuarios  
- Sistema de Turnos  
Incluye criterios de aceptación y priorización.

### 🔹 **Prototipado**
Pantallas principales diseñadas para representar el flujo del usuario:
- Registro  
- Login  
- Home  
- Búsqueda y agenda  
- Confirmación de turno  

### 🔹 **Testing**
Casos de prueba para:
- Registro  
- Login  
- Reserva  
- Cancelación  
- Recordatorios  
- Seguridad y sesión

---

## 🧱 Tecnologías / Herramientas utilizadas
- **UML (Draw.io)** — Diagramas de clases, secuencia y actividad.
- **Google Docs / Word** — Documentación BRD.
- **Figma / Balsamiq** — Prototipado (si aplica).
- **Procesos FURPS+** — Clasificación de requerimientos.
- **SCRUM** — Épicas, features e historias de usuario.

---

## 👥 Equipo de Desarrollo
- **Ciro López**
- **Patricio León**
- **Yesica Oviedo**
- **Melina Scabini**
- **Nielsen, Hernán Ezequiel** (Documento inicial)

---

## 🚀 Próximos pasos (si se continúa el proyecto)
- Implementar backend con **Spring Boot**.
- Autenticación con **JWT / Spring Security**.
- Base de datos **MySQL/PostgreSQL**.
- Microservicios (futuro): agenda, usuarios, notificaciones.
- Frontend **React / Angular**.
- Automatización de recordatorios vía API externa (SMS/Email).

---

## 📝 Licencia
Proyecto académico — Uso educativo.

---

## 💬 Contacto
Para dudas o consultas del proyecto:  
**Ciro López** — contacto a través de la plataforma UNGS.

