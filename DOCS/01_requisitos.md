# Plan de Desarrollo Scrum y Requisitos del Sistema

**Proyecto:** Directorio de docentes e ideas de investigación[cite: 1]  
**Institución:** Universidad Mariana - Programa de Ingeniería de Sistemas[cite: 1]  
**Período:** 30 de septiembre - 10 de noviembre[cite: 1]

---

## 📋 Requisitos Funcionales por Actor

### 1. Estudiante
- **RF-E01:** Mostrar la página principal con el directorio sin iniciar sesión[cite: 2].
- **RF-E02:** Permitir filtrar docentes por área y eje temático[cite: 2].
- **RF-E03:** Mostrar perfil de cada profesor con foto, nombre, título, correo, áreas y ejes[cite: 2].
- **RF-E04:** Mostrar proyectos dirigidos (activos y finalizados) con fechas y etiquetas[cite: 2].
- **RF-E05:** Mostrar ideas de investigación e identificar las no disponibles[cite: 2].
- **RF-E06:** Ofrecer pestaña "Base de ideas"[cite: 2].
- **RF-E07:** Indicar estado del profesor y ocultar inhabilitados[cite: 2].
- **RF-E08:** Botón "Enviar correo" que dirija a Gmail con el correo del docente[cite: 2].

### 2. Profesor
- **RF-P01:** Inicio de sesión mediante Google con correo institucional (@umariana.edu.co)[cite: 2].
- **RF-P02:** Visualizar su perfil tal como lo ve el estudiante[cite: 2].
- **RF-P03:** Permitir editar únicamente sus propios datos[cite: 2].
- **RF-P04:** Visualizar áreas y ejes asignados por el Super Admin[cite: 2].
- **RF-P05:** Agregar ideas de investigación[cite: 2].
- **RF-P06:** Editar ideas sin opción de eliminarlas[cite: 2].
- **RF-P07:** Cambiar la disponibilidad de sus ideas[cite: 2].
- **RF-P08:** Impedir la modificación de datos/ideas de otros profesores[cite: 2].
- **RF-P11:** Cerrar sesión[cite: 2].

### 3. Super Admin
- **RF-S01:** Inicio de sesión administrativo con correo y contraseña propios[cite: 2].
- **RF-S02:** Acceso al espacio docente mediante Google institucional[cite: 2].
- **RF-S04 / RF-S05:** Agregar y editar datos de cualquier profesor[cite: 3].
- **RF-S06 / RF-S07:** Gestionar disponibilidad e inhabilitar/reactivar profesores[cite: 3].
- **RF-S08:** Crear, editar y desactivar catálogo de áreas y ejes temáticos[cite: 3].
- **RF-S09 / RF-S10:** Crear, asignar proyectos y registrar fechas (creación, inicio, fin)[cite: 3].
- **RF-S12:** Cambiar automáticamente un proyecto a "Finalizado" al registrar fecha de fin[cite: 3].

---

## 🎯 Product Backlog Resumido

| Código | Historia Resumida | Sprint | Prioridad | Story Points |
| :--- | :--- | :--- | :--- | :--- |
| **HU-E01** | Consultar directorio | Sprint 1 | Must Have | 3 SP[cite: 3] |
| **HU-E02** | Filtrar por área y eje | Sprint 1 | Must Have | 5 SP[cite: 3] |
| **HU-E03** | Consultar perfil docente | Sprint 1 | Must Have | 3 SP[cite: 3] |
| **HU-E04** | Consultar proyectos dirigidos | Sprint 1 | Should Have | 5 SP[cite: 3] |
| **HU-E05** | Consultar ideas | Sprint 1 | Must Have | 3 SP[cite: 3] |
| **HU-E06** | Consultar disponibilidad | Sprint 1 | Must Have | 3 SP[cite: 3] |
| **HU-E07** | Contactar por correo | Sprint 1 | Should Have | 2 SP[cite: 3] |
| **HU-P01** | Inicio de sesión Google | Sprint 2 | Must Have | 8 SP[cite: 3] |
| **HU-P03** | Editar datos personales | Sprint 2 | Must Have | 5 SP[cite: 3] |
| **HU-P05** | Agregar ideas | Sprint 2 | Must Have | 5 SP[cite: 3] |
| **HU-P06** | Editar ideas | Sprint 2 | Must Have | 3 SP[cite: 3] |
| **HU-P07** | Cambiar disponibilidad de ideas | Sprint 2 | Must Have | 3 SP[cite: 3] |
| **HU-P08** | Proteger datos de otros profesores | Sprint 2 | Must Have | 5 SP[cite: 3] |
| **HU-S01** | Inicio de sesión Super Admin | Sprint 3 | Must Have | 5 SP[cite: 3] |
| **HU-S02** | Agregar profesores | Sprint 3 | Must Have | 5 SP[cite: 3] |
| **HU-S05** | Inhabilitar/reactivar profesores | Sprint 3 | Must Have | 5 SP[cite: 3] |
| **HU-S06** | Administrar áreas y ejes | Sprint 3 | Must Have | 5 SP[cite: 3] |
| **HU-S07** | Crear y asignar proyectos | Sprint 4 | Must Have | 8 SP[cite: 3] |
| **HU-S09** | Finalización automática de proyectos | Sprint 4 | Must Have | 5 SP[cite: 3] |
