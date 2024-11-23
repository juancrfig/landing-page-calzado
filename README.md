# StepAhead

## Integrantes del Equipo

- Juan Camilo Ramirez Figueroa
- Brayan David Vera Mesa

## Maquetacion inicio

Lo primero que se realizó fue el diseño de como se vería la pagina inicial

https://www.canva.com/design/DAGXQNXSPOo/PjR4y2RdsT2RZcqcxBfShw/edit?utm_content=DAGXQNXSPOo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

Luego se realizó la creación de inicio, creando el menu, el main con las cuatro cards con los productos y precios, y con su footer con los contactos.


---


### Comandos por Brayan Vera

- git clone: lo utilize para clonar el repositorio en la carpeta donde iba a trabajar.
- git branch [nombre-de-rama]: Lo use para crear la rama desarrollo donde se subirian todos los cambios antes de hacer pull al main, tambien cree mi rama donde trabaje.
- git switch: lo use para poder cambiar entre mi rama y la rama de desarrollo.
- git status : lo use para ver el estado del are o rama donde estaba trabajando, y asi saber si tenia algun elemento pendiente por hacer commit.
- git add: lo use para meter los cambios o los archivos nuevos que iba añadiendos a stagging.
- git commit -m: lo use para poder subir los commit al area del repositorio local y poder guardar los cambios que añadí previamente en el area de stagging.
- git push: Lo usé para enviar al repositorio remoto todos los commits registrados en el repositorio local.


---


### Comandos por Juan Figueroa

- **git clone**: Lo usé para clonar el repositorio remoto en mi computadora y poder así empezar a trabajar
- **git branch [nombre-de-rama]**: Lo usé para crear las diferentes ramas que se usarán en el repositorio.
- **git switch**: Lo usé para cambiar entre las ramas previamente creadas.
- **git status**: Lo usé para revisar constantemente el estado de las diferentes areas de trabajo que presenta git. Tales como el area de trabajo, el stagging area y 
el area del repositorio remoto.
- **git add**: Lo usé para añadir al area de stagging los cambios que iba realizando en el codigo.
- **git commit -m**: Lo usé para enviar al area del repositorio local todos los cambios que añadí previamente en el area de stagging.
- **git push**: Lo usé para enviar al repositorio remoto todos los commits registrados en el repositorio local.
- **git merge [rama]**: Lo usé para mezcla los contenidos de de dos ramas. Mezclé exitosamente los diferentes intentos de merge y conflictos encontrados.
- **git fetch**: Lo usé para actualizar la metadata del repositorio en el que me encontraba posicionado. Esto me permitió ver los cambios en los archivos sin descargar los cambios en sí.
- **git pull**: Lo usé para descargar los ultimos cambios de una rama a mi repositorio local, y así poder trabajar con la ultima versión del projecto.


---


#### Comandos utilizados al momento de crear la estructura del directorio

- **mkdir**: Para crear carpetas
- **touch**: Para crear archivos
- **cd**: Para navegar entre diferentes carpetas
- **ls**: Para revisar que archivos se encuentran en las carpetas


### Buenas Practicas a la Hora de Realizar un Merge

Para realizar un merge de la mejor manera se usa el *merge editor* que visual studio code proporciona. 
Este divide la pantalla en tres secciones:
- **Seccion superior-izquierda:** Esta sección nos muestra los cambios que se estan tratando de aplicar al momento de realizar el pull. Es decir, aqui podemos ver todos los cambios entrantes
- **Seccion superior-derecha:** Esta sección nos muestra el estado actual de los archivos antes de aplicar el merge. Es decir, como luce el projecto sin los cambios entrantes.
- **Seccion inferior:** Esta sección nos permite visualizar de manera dinámica como lucirá el archivo luego de decidir si mantener los cambios entrantes, los actuales, o juntar ambos. 

Luego de este proceso de análisis se completa el merge de manera exitosa. 