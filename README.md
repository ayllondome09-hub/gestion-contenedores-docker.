# Gestión de Aplicaciones Contenerizadas con GitHub y Docker

## Introducción
Este repositorio ha sido creado para demostrar la integración de GitHub en el flujo de trabajo de virtualización por contenedores.

## El Rol de GitHub en el Trabajo Colaborativo
GitHub actúa como el eje central para la colaboración. Permite:
* **Control de versiones:** Historial completo de cambios en el código.
* **Revisiones de código:** A través de Pull Requests para asegurar la calidad.
* **Gestión de proyectos:** Seguimiento de tareas y errores (Issues).

## GitHub y la Virtualización por Contenedores
En el desarrollo moderno, GitHub es el repositorio de la "Infraestructura como Código" (IaC). Aquí se almacenan los archivos necesarios para definir entornos de ejecución idénticos, independientemente de la máquina donde se desplieguen.

## Relación con Docker
Docker es la herramienta que permite empaquetar una aplicación con todas sus dependencias. La relación con GitHub es fundamental:
1. **Source of Truth:** GitHub aloja el `Dockerfile`.
2. **Automatización:** Se pueden usar GitHub Actions para construir imágenes de Docker automáticamente.
3. **Despliegue:** Facilita que cualquier colaborador descargue el código y levante el entorno con un simple `docker-compose up`.

---
*Creado por: [Domenica Ayllon]*
