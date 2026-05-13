# Sistema de Gestión de Reclamos con IA (Agente Municipal) 🤖🏛️

Este proyecto consiste en el desarrollo de un **MVP (Producto Mínimo Viable)** de un sistema inteligente de gestión de reclamos municipales. La solución permite a los ciudadanos reportar incidentes de forma simple a través de WhatsApp, utilizando Inteligencia Artificial para la clasificación y priorización automática de los reportes.

---

## 📑 Descripción del Proyecto
El objetivo es optimizar la comunicación entre el vecino y el municipio. Mediante un agente de IA, el sistema es capaz de recibir descripciones textuales y fotografías de problemas en la vía pública, identificar la categoría del reclamo (alumbrado, bacheo, limpieza, etc.) y registrarlo en una base de datos para su gestión mediante un panel administrativo (Dashboard).

### Características Principales (Fase 1)
- **Agente de IA Multimodal:** Procesamiento de texto e imágenes mediante Gemini API.
- **Clasificación Automática:** Categorización de reclamos sin intervención humana.
- **Análisis de Prioridad:** Detección de urgencias basada en el contexto del reclamo.
- **Dashboard Municipal:** Panel para que los empleados visualicen y gestionen los tickets en tiempo real.

---

## 🛠️ Stack Tecnológico

| Componente | Tecnología |
| :--- | :--- |
| **Backend** | [Node.js](https://nodejs.org/) con Express |
| **Base de Datos** | [PostgreSQL](https://www.postgresql.org/) |
| **Inteligencia Artificial** | [Google Gemini API](https://ai.google.dev/) |
| **Frontend (Dashboard)** | [React](https://reactjs.org/) con Tailwind CSS |
| **Gestión de Flujos** | n8n / Webhooks |

---

## 📂 Estructura del Repositorio
- `/backend`: Servidor API Rest y lógica de negocio.
- `/frontend`: Dashboard administrativo desarrollado en React.
- `/docs`: Documentación de la Fase 1 (Resumen ejecutivo, Canvas, Requisitos).
- `/database`: Scripts de creación de tablas y esquema relacional.

---

## 🚀 Plan de Desarrollo (Fase 1 - Abril)
Durante este mes, el equipo se enfocó en el descubrimiento y definición técnica:
1.  **Conformación de grupo y roles.**
2.  **Investigación de usuarios:** Entrevistas y análisis de sistemas actuales.
3.  **Definición de Alcance:** Creación del Modelo de Negocio (Canvas) y Resumen Ejecutivo.
4.  **Configuración de Entorno:** Setup inicial del repositorio y base de datos.

---

## 👥 Integrantes y Roles
- **Matias Borsini** - Responsable Técnico / Líder de Proyecto
- **Matias Borsini** - Responsable de IA / Documentación
- **Ezequiel Luque** - Responsable de Diseño UX/UI / Frontend
- **Matias Zampetti** - Responsable de QA / Testing

---

## 📄 Licencia
Este proyecto es desarrollado para la materia Practicas Profesionalizantes 2 perteneciente a la carrera de Desarrollo de Software. 2026.
