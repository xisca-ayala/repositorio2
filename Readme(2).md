Para subir el proyecto a Git:
1. Escribo git init al directorio del proyecto.(captura2)
2. Creo un nuevo repositorio en Github, con el mismo nombre del proyecto local. No añadir archivo Read-me. (captura3)
3. Enlazo el local al remoto: (captura4)
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/xisca-ayala/repositorio2.git
git push -u origin main


Crear un archivo .ignore, e introducir una carpeta dentro, y subir:
1. Crea un archivo .ignore
2. Escribir dentro del archivo / + "nombre de la caarpeta" 
3. Subir al repertorio a traves de : git add ./ git commit -m "missage" / git push
Vemos que se sube todo, escepto la carpeta reto_2 que queremos que sea ignorada. 
