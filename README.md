# SIGCAD - Sistema de Gestión de Carga Académica y Docente

![Status](https://img.shields.io/badge/Status-En%20Desarrollo-yellow)
![Team](https://img.shields.io/badge/Team-NexaByte-blue)
![Version](https://img.shields.io/badge/Version-1.0.0-green)

## 📖 Descripción del Proyecto

**SIGCAD** es una solución web que permite la asignación de materias y horarios en universidades, eliminando errores como cruces de horarios y sobrecarga de horas docentes. A diferencia de la gestión manual actual, nuestro sistema valida reglas académicas en tiempo real y se sincroniza con sistemas de seguimiento de calificaciones, centralizando la toma de decisiones basada en estadísticas de rendimiento y deserción.

El objetivo principal es optimizar la administración académica y garantizar la integridad de los datos mediante una arquitectura escalable y segura.

---

## 👥 Equipo: NexaByte

[cite_start]Este proyecto es desarrollado por estudiantes de la Licenciatura en Ingeniería de Software y Sistemas Computacionales de la UNID Campus Campeche[cite: 1, 2].

* [cite_start]**Jorge Andrés Faisal Sulub (Líder)** [cite: 7]
* [cite_start]**Diego Manuel Pérez Estrella (Arquitecto de Software)** [cite: 8]
* [cite_start]**Andrés Oswaldo Heredia Torres (Desarrollador)** [cite: 9]
* [cite_start]**José Alberto Castillo Vieyra (Desarrollador)** [cite: 9]
* [cite_start]**Luis Felipe Quintero Cervera (Desarrollador)** [cite: 9]
* [cite_start]**Melvin Yuriel Gutiérrez Martinez (Tester)** [cite: 9]
* [cite_start]**Abraham Kantun Cauich (Tester)** [cite: 9]

---

## 🛠️ Stack Tecnológico Preliminar

[cite_start]La arquitectura del proyecto está basada en un enfoque **Full-Stack JavaScript** para unificar el desarrollo, utilizando una arquitectura desacoplada (Frontend y Backend separados) comunicada vía API RESTful[cite: 100, 119].

### Frontend (Interfaz de Usuario)
| Tecnología | Propósito | Justificación Breve |
| :--- | :--- | :--- |
| ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) | **React.js** | [cite_start]Construcción de SPA (Single Page Application) responsiva y basada en componentes[cite: 44]. |
| ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white) | **Vite** | [cite_start]Bundler de última generación para recarga en caliente y optimización de build[cite: 46]. |

### Backend (API & Lógica de Negocio)
| Tecnología | Propósito | Justificación Breve |
| :--- | :--- | :--- |
| ![NodeJS](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) | **Node.js** | [cite_start]Entorno de ejecución asíncrono y orientado a eventos[cite: 48]. |
| ![Express](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white) | **Express.js** | [cite_start]Framework minimalista para la creación de la API RESTful[cite: 50]. |
| ![JSON](https://img.shields.io/badge/JSON-000000?style=flat&logo=json&logoColor=white) | **JSON** | [cite_start]Formato estándar de intercambio de datos ligero[cite: 58]. |

### Base de Datos
| Tecnología | Propósito | Justificación Breve |
| :--- | :--- | :--- |
| ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=mariadb&logoColor=white) | **MariaDB** | [cite_start]RDBMS Open Source que garantiza integridad ACID y alto rendimiento[cite: 54]. |
| ![MySQL Workbench](https://img.shields.io/badge/MySQL_Workbench-4479A1?style=flat&logo=mysql&logoColor=white) | **MySQL Workbench** | [cite_start]Herramienta GUI para modelado y administración de la BD[cite: 54]. |

### Infraestructura y Herramientas
| Categoría | Herramientas |
| :--- | :--- |
| **Control de Versiones** | [cite_start]**Git** y **GitHub** para CI/CD y gestión de código[cite: 60]. |
| **Despliegue (PaaS)** | [cite_start]**Railway** para infraestructura cloud bajo demanda[cite: 56]. |
| **Diseño y Prototipado** | [cite_start]**Miro** (Wireframes) y **Draw.io** (Diagramas UML/Arquitectura)[cite: 62, 64]. |
| **IDE** | [cite_start]**Visual Studio Code**[cite: 42]. |

---

## 🏗️ Arquitectura del Sistema

El sistema utiliza una arquitectura cliente-servidor donde:
1.  **Frontend:** Consume datos mediante peticiones HTTP (Axios/Fetch).
2.  **Backend:** Procesa la lógica de negocio y protege la base de datos en una red privada.
3.  [cite_start]**Producción:** Desplegado en Railway con servicios desacoplados para escalabilidad vertical[cite: 112, 115].

---

© 2026 NexaByte - Universidad Interamericana para el Desarrollo
