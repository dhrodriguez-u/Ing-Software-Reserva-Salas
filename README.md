# Sistema de Reserva de Salas Universitarias

[![Metodología: Scrum + Kanban](https://img.shields.io/badge/Metodolog%C3%ADa-Scrum%20%2B%20Kanban-orange.svg)]()


Este proyecto consiste en el diseño y desarrollo de un **Sistema de Reserva de Salas** para una comunidad universitaria. El software permite gestionar de manera óptima los espacios físicos (Aulas, Laboratorios y Auditorios), controlando la disponibilidad horaria y evitando conflictos de reservas.

El proyecto se gestiona aplicando el marco de trabajo **Scrum** junto con un tablero **Kanban** en GitHub Projects para visualizar el flujo de trabajo en tiempo real.

---

## Características del Sistema

El sistema cubre las siguientes necesidades del negocio universitario:
* **Registrar Salas:** Alta de espacios especificando capacidad y tipo (Aula, Laboratorio, Auditorio).
* **Crear Reservas:** Asignación de salas a usuarios en fechas y rangos horarios específicos (con validación de choques).
* **Consultar Reservas:** Buscador filtrado de ocupación de espacios.
* **Cancelar Reservas:** Liberación inmediata de un espacio previamente apartado.
* **Listar Salas y Reservas:** Panel principal de visualización del estado del sistema.
* **Generar Reporte General:** Módulo estadístico sobre el uso y porcentaje de ocupación de las salas.

---
---

## Arquitectura del Software

Para el análisis, diseño e implementación de las funcionalidades, el equipo aplica el patrón de arquitectura **Entity-Boundary-Control (EBC)**:

* **Boundary (Frontera):** Vistas e interfaces construidas en JavaFX (`FormularioSalaView`, `FormularioReservaView`, etc.) que interactúan directamente con el usuario.
* **Control (Controlador):** Componentes encargados de la lógica de negocio, validaciones y coordinación de flujos (`SalaController`, `ReservaController`, etc.).
* **Entity (Entidad):** Clases que representan el modelo de datos y la persistencia del sistema (`Sala`, `Reserva`, `Usuario`).

---

## Gestión del Proyecto (Scrum & Kanban)

El desarrollo del proyecto está estructurado estrictamente bajo un enfoque ágil. El equipo avanza de forma conjunta prioridad por prioridad en el backlog académico:

### Flujo de Trabajo en Kanban
Nuestro tablero Kanban de GitHub refleja las fases metodológicas requeridas como prioridades de entrega en bloque (*Swarming*):
1.  **Requerimientos del Sistema**
2.  **Casos de Uso**
3.  **Escenarios para Casos de Uso**
4.  **Precondiciones y Postcondiciones**
5.  **Abstracción de Clases (EBC)**
6.  **Diagramas de Colaboración y Secuencia**
7.  **Implementación del Código en Java**

> **Nota de Proceso:** El equipo se asigna colectivamente a la prioridad activa en la columna `Haciendo` (In Progress). Aunque la división interna de tareas optimiza la velocidad, la aprobación de cada tarjeta requiere una revisión cruzada en equipo antes de ser trasladada a `Hecho` (Done).

---

## 👥 Integrantes del Equipo y Roles

* **[Daniel]**  
* **[Yeison]** 
* **[Juan]** 
---
