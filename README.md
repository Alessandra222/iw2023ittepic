<h1>Crear repositorio</h1>

![image](https://github.com/Alessandra222/iw2023ittepic/assets/114311521/83a4293c-975b-4837-b415-57698eda8059)
![image](https://github.com/Alessandra222/iw2023ittepic/assets/114311521/6d64a6c2-be31-4c79-8cb8-198a376ee488)

<h1>Clonar el repositorio en local</h1>

*git clone https://github.com/Alessandra222/iw2023ittepic

<h1>Creación de archivo README </h1>
* echo "# iw2023ittepic" >> README.md

<h1>Commit Inicial</h1>

* git add README.md git
* commit -m "Initial commit"

<h1>Push Inicial</h1>
* git push origin master

<h1> Ignorar archivo </h1>
* touch privado.txt <br>
* mkdir privada<br>
* touch .gitignore<br>
* vim .gitignore y escribir privado.txt privada/ <br>

<h1>Añadir archivo</h1>
* touch 1.txt<br>
* git add 1.txt<br>
<h1>Creación de Tag</h1>
* git tag v1.0
<h1>Subir cambios</h1>
* git commit -am "v1.0"<br>
* git push origin v1.0<br>

<h1>Creación de tabla</h1>

| Nombre           | Github                                     !
|------------------|--------------------------------------------|
| Sebastian Medina | https://github.com/SebastianMedina2023     |
| Miguel De Robles | https://github.com/MDeRobles               |
| Sandra Esperanza | https://github.com/saliesperanzama         |
| Martin Barron    | https://github.com/DarkMartin18            |
| Juan Graxiola    | https://github.com/Railgun124              |

<h1>Subir todos los archivos y cambios realizados </h1>
* git status <br>
* git add . <br>
* git commit -m "comentarios" <br>
* git push origin master<br>

<h1>Colaboradores</h1>

![image](https://github.com/Alessandra222/iw2023ittepic/assets/114311521/b3dde424-a68c-49b8-8ff6-39b025a7ed74)

![image](https://github.com/Alessandra222/iw2023ittepic/assets/114311521/dcc051b6-bc1d-4561-a87f-c2f7d853d9d7)

![image](https://github.com/Alessandra222/iw2023ittepic/assets/114311521/d8700b8b-dfa1-40d1-97f3-17db51dd3f1e)
![image](https://github.com/Alessandra222/iw2023ittepic/assets/114311521/594950c5-1167-4820-80a4-515c5433fc1d)
![image](https://github.com/Alessandra222/iw2023ittepic/assets/114311521/2324c4d2-ef53-4be3-be38-ca4a9598f135)
![image](https://github.com/Alessandra222/iw2023ittepic/assets/114311521/cbd3b844-1f87-47e8-bb23-b9f32274ed45)


<h1>Crear una rama</h1>
* git branch v0.2

<h1> Posicionar tu carpeta de trabajo sobre esta rama </h1>
* git checkout v0.2

<h1>Añadir archivo 2.txt</h1>
* touch archivo2.txt


<h1>Crear rama remota v0.2</h1>
* git add archivo2.txt<br>
* git commit -m "archivo2.txt"<br> 
* git push origin v0.2<br>

<h1>Merge directo</h1>
* git checkout master<br>
* git merge v0.2<br>

<h1>Merge con conflicto</h1>
<h3>En la rama master poner Hola en el archivo 1.txt y hacer commit</h3>
* vim 1.txt <br>
* git add .<br>
* git commit -m "hola 1.txt"<br>

<h3> Posicionarse en la rama v0.2 y poner Adiós en el archivo 1.txt y hacer commit</h3>
* git checkout v0.2<br>
* vim 1.txt <br>
* git add .<br>
* git commit -m "adios 1.txt"<br>

<h3> Posicionarse de nuevo en la rama master y hacer un merge con la rama v0.2</h3>
* git checkout master<br>
* git merge v0.2<br>
<h3> Listar las ramas con merge y las ramas sin merge</h3>

![image](https://github.com/Alessandra222/iw2023ittepic/assets/114311521/34e012ca-3c11-426d-bada-e16fecb41f80)

![image](https://github.com/Alessandra222/iw2023ittepic/assets/114311521/70a91bcf-4855-4071-9eb1-2dc31cd532d5)


<h3> Arreglar conflicto anterior y hacer un commit</h3>
* vim 1.txt <br>
* git add 1.txt <br>
* git commit -m "Arreglado" <br>

<h1>Borrar rama</h1>
<h3> Crear un tag v0.2</h3>
* git tag v0.2
* git commit -am "v0.2"<br>
* git push origin refs/tags/v0.2<br>

<h3> Borrar la rama v0.2</h3>
* git branch -d refs/heads/v0.2


<h1>Listado de cambios</h1>
1. Listar los distintos commits con sus ramas y sus tags

![image](https://github.com/Alessandra222/iw2023ittepic/assets/114311521/1c6fae95-c536-4c97-a7da-6387086fd7f6)

<h1>Crear una organización</h1>
1. Crear una organización llamada iw2023ittepic-tunombredeusuariodegithub

<h1>Crear equipos</h1>
1. Crear 2 equipos en la organizacióniw2023ittepic-tunombredeusuariodegithub, uno llamado administradores y otro llamado colaboradores
2. Meter a iarjonavizcaino y a 5 de tus compañeros de clase en el equipo de administradores
3. Meter a iarjonavizcaino y a 5 de tus compañeros de clase en el equipo de colaboradores

<h1>Crear un index.html</h1>
1. Crear un index.html que se pueda ver como página web en la organización

<h1>Crear pull-requests</h1>
1. Hacer 2 forks de 2 repositorios iw2023ittepic-tunombredeusuariodegithub
de 2 organizaciones de las que no sean administradores ni colaboradores
2. Crear una rama en cada fork
3. En cada rama modificar el archivo index.html añadiendo tu nombre
4. Con cada rama hacer un pull-request

<h1>Gestionar pull-requests</h1>
1. Aceptar los pull-request que lleguen a los repositorios de tu organizació

