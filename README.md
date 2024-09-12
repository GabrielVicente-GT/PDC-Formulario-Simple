
# Proyecto Simple con Docker - API, PostgreSQL y Frontend

Este proyecto es una aplicación simple que incluye:
- Un backend (API) conectado a una base de datos PostgreSQL.
- Un frontend que permite a los usuarios interactuar con un sistema de login y un formulario.

Todo el proyecto se ejecuta mediante contenedores Docker.

## Estructura del Proyecto

- **Backend (API)**: Un servidor que expone una API RESTful para gestionar la lógica del login y los formularios, y que interactúa con la base de datos PostgreSQL.
- **Base de Datos (PostgreSQL)**: Almacena la información de usuarios y de los formularios enviados.
- **Frontend**: Una interfaz web que permite a los usuarios registrarse, iniciar sesión y rellenar un formulario.

## Requisitos Previos

Asegúrate de tener instalados los siguientes componentes antes de ejecutar el proyecto:

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Configuración del Proyecto

### 1. Clonar el Repositorio

```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
