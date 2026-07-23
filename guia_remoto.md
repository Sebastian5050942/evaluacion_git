# Guía Técnica 2: Creación y conexión de un repositorio remoto en GitHub

## 1. Creación de un repositorio remoto en GitHub

Un repositorio remoto es un espacio alojado en la nube que permite almacenar, administrar y compartir el código de un proyecto. Para crear un repositorio remoto se deben seguir los siguientes pasos:

1. Ingresar a GitHub y crear una cuenta o iniciar sesión.
2. Seleccionar la opción **"New Repository"**.
3. Asignar un nombre al repositorio.
4. Seleccionar si el repositorio será público o privado.
5. Crear el repositorio sin agregar archivos iniciales si ya existe un proyecto local.
6. Copiar el enlace generado por GitHub para conectar el repositorio local con el remoto.

---

## 2. Enlace entre el repositorio local y GitHub

Para conectar un proyecto creado en Git Bash con un repositorio remoto en GitHub se utiliza el comando:

```bash
git remote add origin URL_DEL_REPOSITORIO
