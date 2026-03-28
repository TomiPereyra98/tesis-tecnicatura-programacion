# Sistema de Gestión de Turnos Multicomercio (Shopping Scheduler)

Este proyecto es una plataforma integral de reserva de turnos diseñada bajo un modelo de "Shopping". Permite que múltiples comercios coexistan en una misma infraestructura, cada uno con su propia gestión de profesionales, horarios y clientes.

## 🚀 Funcionalidades Principales

### Para Clientes (Acceso Público)
* **Reserva de Turnos:** Selección de comercio, elección de profesional específico y visualización de disponibilidad en tiempo real.
* **Gestión por Comprobante:** Sistema de consulta y cancelación mediante número de turno único, sin necesidad de registro obligatorio para el usuario final.
* **Detalle Completo:** Visualización de datos del comercio, profesional asignado, fecha y hora del turno solicitado.

### Para Comercios (Panel de Administración)
* **Gestión de Staff:** Alta, baja y modificación de profesionales y empleados.
* **Control de Agendas:** Configuración personalizada de días y horarios de atención por cada profesional.
* **Monitoreo de Turnos:** Visualización de todas las solicitudes recibidas con capacidad de edición y cancelación.
* **Administración de Elementos:** Control total sobre los servicios y recursos del comercio.

## 🏗️ Arquitectura Técnica
El proyecto está desarrollado con una separación clara entre la lógica de negocio y la interfaz de usuario:

* **Backend (`/api`):** Desarrollado en **Python**, encargado de la lógica multitenant, validación de horarios y persistencia de datos.
* **Frontend (`/frontend`):** Interfaz dinámica que adapta la vista según el rol de sesión (Cliente vs. Comercio).
* **Punto de Entrada (`main.py`):** Ejecución centralizada del sistema.

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python
* **Backend:** [Flask / FastAPI]
* **Frontend:** [HTML5, CSS3, JavaScript / React]
* **Manejo de Dependencias:** requirements.txt

## 📂 Estructura del Repositorio
* `/api`: Endpoints, modelos de datos y lógica de turnos.
* `/frontend`: Archivos de vista y componentes de la interfaz.
* `main.py`: Archivo de arranque del servidor.
* `requirements.txt`: Librerías necesarias para el entorno de ejecución.

---
*Proyecto desarrollado como Tesis Final para la carrera de Técnico en Programación.*
