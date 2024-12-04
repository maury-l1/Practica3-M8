# Practica3-M8



<img src="Imagen01.png" alt="Imagen"/>

Creamos un directorio nuevo y dentro creamos una subcarpeta llamada “src” y en el directorio principal creamos un archivo README.md




<img src="Imagen02.png" alt="Imagen"/>

Creamos alias para facilitar el trabajo




<img src="Imagen03.png" alt="Imagen"/>

Creamos un archivo .gitignore con la siguiente configuración








<img src="Imagen04.png" alt="Imagen"/>

Este archivo sirve para indicarle a Git que ignore los archivos de esos tipos, es decir que no los restree, en este caso archivos de tipo .log y temporales.













<img src="Imagen05.png" alt="Imagen"/>

Añadimos los 3 archivos y hacemos commit















<img src="Imagen06.png" alt="Imagen"/>

Si creamos un repositorio en github con un README.md se crea un commit “Initial commit” con un archivo readme con el nombre del repositorio









<img src="Imagen07.png" alt="Imagen"/>


Si creamos un repositorio en github sin un archivo README.md, se crea un repositorio vacio y nos dan otras opciones que con la opcion anterior no aparecian











<img src="Imagen08.png" alt="Imagen"/>
Los comandos que nos facilita Github son: 

echo "# Repo2" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/maury-l1/Repo2.git
git push -u origin main







<img src="Imagen09.png" alt="Imagen"/>


Vinculamos el repositorio local con el repositorio remoto con el comando 

git remote add 








<img src="Imagen10.png" alt="Imagen"/>



Creamos una nueva rama llamada feature/documentation y dentro de esta creamos un archivo docs.md, añadimos este archivo y hacemos un commit
