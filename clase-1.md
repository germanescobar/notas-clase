# Notas clase 1

Para crear y publicar un repositorio se siguen estos pasos:

### Crear el repo localmente

1. Crear la carpeta.
2. Entrar a la carpeta.
3. Crear el archivo HTML.
4. Inicializar el repo con `git init`
5. Crear el commit con `git add` y `git commit`

### Subirlo a Github

1. Crear el repositorio remoto en Github.
2. Seguir las instrucciones para subir el historial.

Para hacer cambios después de inicializar y subir el proyecto a Github:

1. Realizar los cambios localmente.
2. Crear el commit con `git add` y `git commit`.
3. Hacer el `git push`.

## Ramas

Las ramas nos permiten hacer experimentos que después podemos utilizar o descartar.

* `git branch` se utiliza para listar las ramas de un repositorio.
* `git branch <nombre>` para crear una nueva rama.
* `git checkout <nombre>` para ubicarnos en otra rama.
* `git checkout -b <nombre>` es la únion de los dos comandos anteriores: crea la rama y nos ubica en ella.
* `git branch -d <nombre>` para borrar una rama.
* `git branch -m <nuevo-nombre>` para cambiar el nombre de la rama actual.

Para publicar una rama en Github la primera vez:

* `git push -u origin rama-1`

Para actualizar una rama con lo de Github:

* `git pull`
