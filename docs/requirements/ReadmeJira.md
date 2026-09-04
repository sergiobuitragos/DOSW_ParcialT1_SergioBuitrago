# Planeación del Sistema
link: https://sergiobuitragosua.atlassian.net/jira/software/projects/PPDT/boards/2/timeline?selectedIssue=PPDT-2

## Desglose de trabajo: Épicas, Historias de Usuario y Tareas

La implementación de los requerimientos identificados de TutoECI se desglosa de la siguiente manera:

### 1. Épica:

| Campo | Descripción |
|------|-------------|
| **IDENTIFICACIÓN** | SCRUM-1 |
| **Título** | Recomendacion de tutor |
| **Descripción** | Permite al estudiante solicitar la tutoria inidcando la preferencia de tutor y el sistema asigna el mejor posible |
| **Tenedor de apuestas** | Usuario |

### 2. Historias de usuario:

| Campo | Descripción |
|------|-------------|
| **IDENTIFICACIÓN** | SCRUM-2 |
| **Título** | Devolver tutor con la 3 preferencias |
| **Descripción** | El usuario pide un tutor con 3 preferencias, el mas rapido, priorizar profesores y preferir otro estudiante |
| **Prioridad** | Alta |
| **Justificación de prioridad** | Es la funcionalidad base del sistema: ya que esto ayuda a los usuarios a escoger sus preferencias de tutores |
| **Estimación** | Pendiente |

### 3. Tareas:

| Campo | Descripción |
|------|-------------|
| **ID** | SCRUM-3 |
| **Título** | Diseñar el modelo de datos para pedir tutorias |
| **ID de la Historia de Usuario asociada** | SCRUM-7 |
| **Descripción** | Definir los usuarios y transiciones de estado (inscrito,verificando,no se progamos tutoria) |
| **Tareas requisito** | Ninguna |

| Campo | Descripción |
|------|-------------|
| **ID** | SCRUM-4 |
| **Título** | Crear la interfaz para pedir tutorias |
| **ID de la Historia de Usuario asociada** | SCRUM-7 |
| **Descripción** | Construir el formulario/endpoint que permita al usuario ingresar fechas, hora y tutor. |
| **Tareas requisito** | SCRUM-12 |

| Campo | Descripción |
|------|-------------|
| **ID** | SCRUM-5 |
| **Título** | Validar el ID único del usuario |
| **ID de la Historia de Usuario asociada** | SCRUM-7 |
| **Descripción** | Implementar la validación del usuario con su ID |
| **Tareas requisito** | SCRUM-12 |