🧠📊 Inmax Avisadores – Plataforma de Gestión de Campañas Publicitarias

Inmax Avisadores es una plataforma web desarrollada en colaboración con Alloxentric, orientada a la gestión, monitoreo y optimización de campañas publicitarias dentro de la red social Inmax.
El sistema permite a los avisadores crear campañas segmentadas, administrar presupuestos, visualizar métricas clave y analizar interacciones de usuarios para una mejor toma de decisiones.

La plataforma integra tecnologías modernas como Vue.js, FastAPI, MongoDB/PostgreSQL, Docker y Keycloak, logrando una solución escalable, segura y preparada para el crecimiento futuro de la red.

🚀 Características principales

Creación y administración de campañas con segmentación por intereses y ubicación.

Monitoreo de métricas como impresiones, clics, CTR y engagement.

Gestión de avisadores y autenticación segura mediante Keycloak y JWT.

Dashboard interactivo para visualizar datos relevantes en tiempo real.

Arquitectura modular y escalable con contenedores Docker.

Bases de datos híbridas:

PostgreSQL para datos estructurados.

MongoDB para métricas e interacciones.

🧱 Tecnologías utilizadas
Backend

FastAPI (Python)

Keycloak (OAuth2 / JWT)

PostgreSQL

MongoDB

Frontend

Vue.js (próxima fase)

Infraestructura

Docker & Docker Compose

Nginx (opcional)

Visual Studio Code

📂 Estructura del proyecto
Inmax/
├── Inmax-api/          # Backend en FastAPI
├── Inmax-bd/           # Configuración de bases de datos
├── docker-compose.yml  # Orquestación de servicios
└── README.md           # Documentación del proyecto

⚙️ Instalación y ejecución
1️⃣ Clonar el repositorio
git clone https://github.com/farinhadiego22/inmax.git
cd inmax

2️⃣ Levantar los servicios con Docker
docker compose up --build

3️⃣ Acceder a la API de FastAPI

👉 http://localhost:8000/docs

Aquí encontrarás la documentación interactiva de la API (Swagger UI).

4️⃣ Verificar la base de datos

Puedes revisar MongoDB con:

MongoDB Compass

Mongo Express (si lo agregas al docker-compose)

📌 Estado actual del proyecto (Fase 1)
✔ Implementado

Backend funcional en FastAPI.

Conexión estable a MongoDB y PostgreSQL.

Endpoints para:

Login y autenticación

Gestión de avisadores

Creación y administración de campañas

Arquitectura en Docker completamente operativa.

🔄 En desarrollo

Frontend en Vue.js

Dashboards avanzados de métricas

Reportes detallados y exportables

KPIs en tiempo real

Optimización de seguridad con roles avanzados

🧠 Contexto del proyecto

Este sistema surge como una propuesta de mejora para la red social Inmax, desarrollada por Alloxentric.
Su objetivo es proporcionar una plataforma robusta que permita a los avisadores crear campañas segmentadas, monitorear interacciones y obtener información clave para optimizar decisiones de marketing.

La solución fue desarrollada bajo la metodología ágil Scrumban, garantizando flexibilidad, iteración continua y alineación con los requerimientos reales del cliente.

🧑‍💻 Equipo de desarrollo
Rol	Integrante
👨‍💻 Jefe de Proyecto	Diego Fariña
🔍 Investigador	Martín Albizú
📝 Documentador	Nicolas Catro
🛠️ Analista / Programador	Nicolas Gonzales
📜 Licencia

MIT © 2025 – Libre para uso, modificación y distribución.
