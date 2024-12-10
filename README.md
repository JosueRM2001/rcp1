# RPC
Este es un proyecto que fue desarrollado con GO en una arquitectura RPC.

## Descripción
Este proyecto muestra como funcion un server y client para dar la ejecución. 
Es un programa sencillo para mostrar cómo funciona un programa en el lenguaje de programación con un estilo de arquitectura.

## Tecnologías Utilizadas
**Contiene lo Siguiente**
- Visual Studio Code (version mas actual)
- Docker
- RPC
- GO(version mas actual)

## Requerimientos para el Desarrollo
- **Docker Desktop** (si lo quieres correr en un contenedor)
- **Visual Studio Code** (opcional, pero recomendado)
- **GO**(requerido y recomendado)
- **La extensión GO para Visual Studio Code** (para mejorar el soporte y el resaltado de sintaxis).
- **GitHub Desktop** (si quieres clonar y usar el proyecto)
  
  ```bash
  https://www.docker.com/products/docker-desktop/
  ```
  
- **Docker hub** (si quieres clonar y usar el proyecto)
  
  ```bash
  https://hub.docker.com/layers/erickjrm/programrpc/latest/images/sha256-22d24c8d407e8ae11a809d78cfe189b0dd6354b2752e589b90600df140759ba3?context=repo
  ```

## Intruciciones para ejecutar el proyecto
## Pasos para ejecutar
**Paso #1**
  **Clonar este repositorio**
Si aún no ha clonado el repositorio, puede hacerlo con el siguiente link:

 ```bash
https://github.com/JosueRM2001/rcp1.git
 ```
**Paso #2**
  **Construya la imagen de Docker**

Ejecuta el siguiente comando, que generará la imagen:

```bash
docker pull erickjrm/programrpc:latest
```

**Paso #3**
**Ejecute el contenedor Docker:**

Luego ejecuta el siguiente comando, que genera el contenedor y el puerto.

```bash
docker run -d -p 4000:4000 --name RPC erickjrm/programrpct:latest
```

**Paso #4**

Abre Docker Desktop para ver si la imagen se creó correctamente y envíala a ejecutar para verla.

**Paso #5**

**Accede a la aplicación**: Si está ejecutándose, puedes acceder a la aplicación navegando a la

siguiente url en tu navegador web:

```bash
https://localhost:4000
```
