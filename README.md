# Sistema Gestor de Horarios para Escuela

## Descripción

El **Sistema Gestor de Horarios para Escuela** es una aplicación web diseñada para ayudar a las escuelas a gestionar eficientemente los horarios de clases, reuniones y actividades administrativas. El sistema permite la creación y gestión de usuarios (estudiantes, profesores, personal administrativo y de servicio), la asignación de horarios de manera manual o automática mediante algoritmos de inteligencia artificial, y el envío de notificaciones en tiempo real a los usuarios.

### Características Principales

- **Gestión de Usuarios**: Agregar, modificar, eliminar y gestionar roles de usuarios (estudiantes, profesores, personal administrativo y de servicio).
- **Creación de Horarios**: Generación manual o automática de horarios de clases y actividades.
- **Inteligencia Artificial**: Módulo de IA para optimización automática de horarios basado en disponibilidad de aulas, preferencias de profesores y reglas de negocio.
- **Notificaciones en Tiempo Real**: Envío de notificaciones a usuarios sobre cambios en horarios, recordatorios de clases y eventos importantes.
- **Seguridad**: Autenticación y autorización seguras mediante JWT.
- **Reportes y Análisis**: Generación de reportes sobre uso de aulas, asignación de horarios y asistencia.

## Tecnologías Utilizadas

- **Back-end**: 
  - [NestJS](https://nestjs.com/) (Node.js con TypeScript)
  - [PostgreSQL](https://www.postgresql.org/) con [TypeORM](https://typeorm.io/)
  - [FastAPI](https://fastapi.tiangolo.com/) para el módulo de IA (Python)
  - [JWT](https://jwt.io/) para autenticación

- **Front-end**:
  - [React](https://reactjs.org/) con [TypeScript](https://www.typescriptlang.org/)
  - [Material-UI](https://mui.com/) para componentes de interfaz de usuario
  - [Redux Toolkit](https://redux-toolkit.js.org/) para gestión del estado global
  - [React Router](https://reactrouter.com/) para manejo de rutas

- **DevOps**:
  - [Docker](https://www.docker.com/) para contenedores
  - [Kubernetes](https://kubernetes.io/) para orquestación de contenedores
  - [AWS](https://aws.amazon.com/) para infraestructura en la nube

## Instalación y Configuración

### Prerrequisitos

- Node.js (v14 o superior)
- Docker y Docker Compose
- Python 3.8 o superior
- PostgreSQL

### Instrucciones de Instalación

1. **Clona el Repositorio:**

   ```bash
   git clone https://github.com/tu-usuario/sistema-gestor-horarios.git
   cd sistema-gestor-horarios
