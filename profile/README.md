## Bugbusters Org

# Organización de Microservicios - Guía de Creación y Configuración

## Tabla de Contenidos
1. [Introducción](#introducción)
2. [Guia de Microservicios](#guia-de-microservicios)
3. [Configuración de Proyectos](#configuración-de-proyectos)
   - [Frontend](#frontend)
   - [Backend](#backend)
4. [Recomendaciones](#recomendaciones)
   - [Extensiones](#extensiones)
6. [Despliegue](#despliegue)
7. [Contribuciones](#contribuciones)
8. [Contacto](#contacto)

## Introducción
Este documento sirve como guía para la creación y configuración de proyectos en la organización, cubriendo tanto el desarrollo Frontend como Backend. La organización está estructurada en microservicios, cada uno alojado en su propio repositorio.

## Guia de Microservicios (TODO)
Cada microservicio tiene su propio repositorio alojado en un puerto:

## Configuración de Proyectos

### Frontend (TODO)
Para los proyectos Frontend, se recomienda seguir los siguientes pasos:
#### React Vite

**Configuración inicial**
1. Instalar Node.js. LTS
2. Ejecutar `npm -g install pnpm`.

**Creacion de proyecto**
1. Posicionarse en una carpeta de proyectos.
2. Ejecutar `pnpm create vite`.
3. Establecer nombre de proyecto, nombre del paquete, tecnología a usar como React, variante a usar como Typescript + SWC.
4. Entrar a la carpeta del proyecto.
5. Agregar librerias necesarias modificando package.json
6. Ejecutar `pnpm install`.

**Uso de proyectos ya hechos**
1. Descargar proyecto.
2. Entrar a la carpeta del proyecto.
3. Ejecutar `pnpm install`.

**Despliegue del Front**
1. Entrar a la carpeta del proyecto.
2. Ejecutar `pnpm run dev`.

### Backend (TODO)
Para los proyectos Backend, sigue estos pasos:
#### Python Flask

**Configuración inicial**
1. Instalar Python 3.12
2. Ejecutar `pip install virtualenv`

**Creacion de proyecto**
1. Posicionarse en una carpeta de proyectos, crear una carpeta de proyectos, entrar en la carpeta
2. Instalar el entorno virtual ejecutando `virtualenv env`
3. Activar el entorno virtual ejecutando `env\Scripts\activate`
4. Crear la carpeta src y el archivo app.py dentro de esta
5. Agregar contenido al archivo app.py y librerias

**Uso de proyectos ya hechos**
1. Descargar proyecto.
2. Entrar a la carpeta del proyecto
3. Instalar el entorno virtual ejecutando `virtualenv env`
4. Activar el entorno virtual ejecutando `env\Scripts\activate` 
5. Ejecutar `pip install -r requirements.txt`

**Despliegue del Front**
1. Entrar a la carpeta del proyecto.
2. Ejecutar `python src/app.py`.

## Recomendaciones (TODO)
### Extensiones para VSCode (TODO)
- **Postman**: Para hacer solicitudes POST.
- **Bracket Pair Color DLW**: Para diferenciar llaves anidadas.
- **Color Highlight**: Permite remarcar el color basado en el valor hexadecimal presente en el HTML.
- **Material Icon Theme** : Muestra iconos de carpetas y archivos según funciones.
- **GitHub Copilot**: Asistente de IA.

## Despliegue (TODO)
...

---
