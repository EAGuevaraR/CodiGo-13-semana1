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

```
git branch
```
- Sirve para poder listar los branch que tengo localmente y me dice en cual me encuentro actualmente.
