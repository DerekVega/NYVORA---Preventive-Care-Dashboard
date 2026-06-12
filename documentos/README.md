# NYVORA---Preventive-Care-Dashboard
NYVORA es una plataforma web cliente/servidor orientada al monitoreo preventivo de pacientes. Centraliza métricas biométricas y hábitos de salud como peso, actividad física, sueño y frecuencia cardíaca, permitiendo su visualización mediante dashboards interactivos para facilitar el seguimiento y la toma de decisiones.


# NYVORA - Preventive Care Dashboard

Sistema web cliente/servidor para la gestión y monitoreo preventivo de pacientes mediante la centralización de métricas biométricas, hábitos de salud y seguimiento clínico.

## Descripción

NYVORA es una plataforma web desarrollada para facilitar el monitoreo preventivo de pacientes mediante la recopilación y visualización de información relacionada con su estado físico y hábitos de salud.

Actualmente, muchas personas utilizan distintas aplicaciones para registrar peso, actividad física, sueño, alimentación y otros indicadores. Sin embargo, esta información suele encontrarse distribuida en múltiples plataformas, dificultando su análisis integral y seguimiento.

La plataforma busca centralizar estos datos en un único sistema, permitiendo tanto a pacientes como a profesionales de la salud acceder a información consolidada para mejorar el control y la prevención de riesgos.

---

## Objetivo General

Desarrollar una plataforma web cliente/servidor que permita centralizar, almacenar y visualizar métricas biométricas y hábitos de salud de pacientes, facilitando el seguimiento preventivo mediante una arquitectura moderna basada en Docker.

---

## Funcionalidades

### Gestión de Pacientes
- Registro de pacientes.
- Consulta y actualización de información.
- Historial clínico básico.
- Seguimiento del progreso.

### Dashboard Interactivo
Visualización de métricas como:
- Peso corporal.
- Grasa corporal.
- Masa muscular.
- Actividad física.
- Frecuencia cardíaca.
- Hidratación.
- Sueño.
- Alimentación.

### Sistema de Alertas
- Detección de cambios importantes en métricas.
- Seguimiento preventivo.
- Notificaciones de evolución del paciente.

---

## Arquitectura

```text
Paciente/Usuario
        │
        ▼
Frontend (HTML, CSS, JavaScript)
        │
        ▼
Backend (PHP)
        │
        ▼
Base de Datos (MySQL)
```

### Arquitectura Docker

El proyecto se encuentra dividido en tres contenedores:

| Contenedor | Función |
|------------|----------|
| Frontend | Interfaz de usuario |
| Backend | Lógica de negocio y API |
| Database | Almacenamiento de datos |

---

## Tecnologías Utilizadas

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- PHP

### Base de Datos
- MySQL

### Infraestructura
- Docker
- Docker Compose

### Control de Versiones
- Git
- GitHub

---

## Estructura del Proyecto

```text
NYVORA/
│
├── frontend/
│   ├── css/
│   ├── js/
│   ├── assets/
│   └── index.html
│
├── backend/
│   ├── api/
│   ├── controllers/
│   ├── models/
│   └── config/
│
├── database/
│   ├── scripts/
│   └── schema.sql
│
├── docker/
│
├── docs/
│
├── docker-compose.yml
│
└── README.md
```

---

## Instalación

### Clonar el repositorio

```bash
git clone https://github.com/usuario/nyvora.git
```

### Ingresar al proyecto

```bash
cd nyvora
```

### Levantar los contenedores

```bash
docker-compose up -d
```

### Verificar servicios

```bash
docker ps
```

---

## Funcionalidades Futuras

Las siguientes características forman parte de futuras versiones del proyecto:

- Integración con dispositivos wearables.
- Aplicación móvil.
- Inteligencia Artificial para análisis preventivo.
- Machine Learning para detección de riesgos.
- Sincronización con plataformas de salud externas.

---

## Equipo de Desarrollo

Proyecto desarrollado para el curso:

**SC-502 Ambiente Web Cliente/Servidor**

---

## Estado del Proyecto
En desarrollo

---

## Licencia

Este proyecto se desarrolla con fines académicos y educativos.
