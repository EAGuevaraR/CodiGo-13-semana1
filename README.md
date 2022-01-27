#Codigo 13

## Comando para GIT
```
git init
```
- Este comando solo se hace una vez por proyecto, sirve para inicializar nuestro proyecto con git.
- :eye: Crea una carpeta oculta llamada ".git".

```
git status
```
- Poder listar y ver si los archivos están listos para subir.
- :eye: en caso los archivos no estén listos se verán de color rojo y cuando lo estén serán de color verde.

```
git add .
git add nombre_de_archivo
```
- Se encarga de agregar los archivos a la memoria de GIT, es decir, los guarda en un stash.

```
git commit -m "comentario"
```
- Crea un punto en la línea de tiempo de nuestros cambios y a estos se les es posible poner y adjuntar un comentario.
- :eye: Los comentarios deben estar relacionados a los cambios que hice, esto es una recomendación.

```
git push origin main
```
- Sirve para poder subir los cambios a nuestro repositorio en la nube, en este caso GitHub.

```
git pull origin main
```
- Sirve para poder descargar los cambios de nuestro repositorio en la nube, en este caso Github.

<<<<<<< HEAD
Esta línea es para probar

=======
```
git branch
```
- Sirve para poder listar los branch que tengo localmente y me dice en cual me encuentro actualmente.

```
git checkout -b nombre_del_branch
```
- Sirve para crear una nueva branch y poder trabajar en él.

```
git checkout nombre_del_branch
```
- Sirve para moverme entre branches y poder trabajar en él. Si tuviera el -b sería para crear.
>>>>>>> eb0c8a4e6c87407e5166fb53568feaadd3a989df
