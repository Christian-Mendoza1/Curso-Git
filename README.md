# Curso Completo de GIT

En este curo introductorio a GIT aprenderás que es GIT, para que sirve y los comandos más básicos pero más utilizados para crear tus propios repositorios y modificarlos.

## ¿Qué es GIT?
GIT es un software de control de versiones, donde nos permite actualizar las versiones de nuestros proyectos de trabajo. Como puede ser (una app, una web, archivos locales o hasta un videojuego). 

Para lograr trabajar comodamente con GIT este tiene su propia terminal llamada **GIt Bash**.

GIT es una tecnología muy demandada en el mundo laboral tecnológico, ya que es una habilidad requerida para un programador, ingeniero de software o para cualquier rama de la informática.

## Funcionalidades de GIT en el mundo Real
¿Por qué es importante que un programador sepa utilizar de manera adecuada la herrmaienta de GIT?

**Te voy a dar un ejemplo de la vida real de un equipo de desarrollo de una app en un empresa cualquiera.**

Imagina que tue eres uno de los tantos miembros convocados a desarrollar una aplicación, donde cada miembro esta dividido en secciones del desarrollo.

Bueno una vez teniendo está idea en tu cabeza, aquí es donde GIT entra en juego sobre el tablero. Cada programador tiene una tarea designada y para subir una actualización de la app, se utiliza GIT. 

Ya que con esto nosotros como desarrolladores a cada rato estaremos actualizando nuestra app, asignando nuevos aditamentos y desarrollando nuevas cosas para la optimización de está app. Aquí entra en juego el control de versiones de la app.

Para desarrollar el entorno de la app crearemos un portafolio en git donde aquí todos como equipo trabajaremos para el archivo principal. Donde crearemos diferentes ramas. Si GIT se trabaja por medio de ramas, donde cada rama tendrá un desarrollo en específico.

Después de que cada programador haga su tarea asignada para introducir las modificaciones hechas al archivo o código fuente principal de la app se utiliza la rama principal de nuestro portafolio de GIT. Donde este recibirá todas las actualizaciones de cada sub rama y las introducirá en la rama principal.

A continuación veremos nuestros primeros comandos para empezar a entender la funcionalidades de que nos ofrece GIT.

## Comandos para modificar GIT

Estos primeros comandos sirven para poder modificar GIT con nuestra área de trabajo y con nuestros propios datos personales.

* ### git --version

    Este comando nos mostrará la versión más reciente de nuestro GIT.

    ```
    git --version
    ```

* ### git config --global

    Este comando mostrará toda la información global de GIT.

    ```
    git config --global
    ```

* ### git config --global user.name

    Este comando lo utilizamos para poder configurar GIT con nuestro nombre de usuario.

    ```
    git config --global user.name "User Name"
    ```

* ### git config --global user.email

    Este comando lo utilizamos para poder configurar GIT con nuestro propio email.

    ```
    git config --global user.email "User Email"
    ```

* ### git config --global core.edior "code --wait"

    Este comando configurará GIT con  nuestro editor de código que utilicemos, en mi caso es Visual Studio Code.

    ```
    git config --global core.editor "code --wait"
    ```

## Comandos de Directorios

Estos comandos sirven para poder crear acceder y movernos a lo largo de todos nueestros directorios de nuestro PC.

* ### ls

    Este comando nos mostrará el listado de nuestras carpetas en cualquier parte del directorio en el que nos encontramos.

    ```
    ls
    ```

* ### pwd

    Este comando mostrará la dirección del directorio en el que nos encontramos.

    ```
    pwd
    ```

* ### cd

    Este comando es para cambiar de directorio **(change directory)** es comando se utiliza ingresando cd y después la ruta (carpeta) a la que queremos acceder.

    ```
    cd ruta/
    ```

* ### cd ..

    Este comando sirve para salirnos de una ruta (carpeta) del directorio.

    ```
    cd ..
    ```

* ### mkdir

    Este comando nos sirve para poder crear una nueva carpeta en dicho directorio en el que nos encontremos.

    ```
    mkdir "Nueva Carpeta"
    ```

## Comando Básicos de GIT

Estos proximos comando son los más básicos pero los más importantes para poder crear un repositorio en git en nuestro editor de código y poder trabajar con el desde el git bash.

* ### git init

    **Este comando es importante** ya que este lo vamos a utilizar siempre para crear un nuevo repositorio de git en la carpeta en la que estemos trabajando.

    ```
    git init
    ```

* ### cd .git

    Este comando sirve para acceder a nuestro repositorio GIT.

    ```
    cd .git
    ```

* ### git status

    Este comando mostrará el estatus de nuestro repositorio y toda la información de este.

    ```
    git status
    ```

* ### git status -s

    Este comando es lo mismo que git status pero sin embargo no mostrara toda la info de nuestro repositorio. Sino solo mostrará aquellos archivos que esten o no en la etapa de stage.

    ```
    git status -s
    ```

* ### git add

    Este comando sirve para agregar el archivo con su nombre en específico a la etapa de stage de nuestro repositorio de GIT.

    ```
    git add index.html
    
    ```

* ### git add .

    Este comando agregará todos los archivos de nuestra etapa de stage de nuestro repositorio. **No se recomienda utilizar este comando**.

    
    ```
    git add .
    
    ```

* ### git commit -m

    Este comando compromete el archivo de la etapa de stage y lo sube a nuestro repositorio, **Es necesario ponerle un comentario con una breve descripción sobre nuestra modificación**.

    
    ```
    git commit -m "Este es un comentario modificado"
    
    ```

* ### git commit -a

    Este comando abre un archivo en nuestro editor de código y ahí escribiremos un mensaje para subirlo a nuestro repositorio y después cerrarlo. 
    
    **Este comando compromete todos los archivos en la etapa de stage, no recomiendo utilizarlo.**

    
    ```
    git add -a
    
    ```

* ### rm

    Este comando eliminará un archivo de nuestro git branch.

    
    ```
    rm index.html
    
    ```

* ### git restore --staged

    Este comando sirve para sacar un archivo a la etapa de stage.

    
    ```
    git restore --staged
    
    ```

* ### git restore

    Este comando sirve para recuperar un archivo de la etapa de stage.

    
    ```
    git restore index.hmtl
    
    ```

* ### mv

    Con este comando podremos cambiar el nombre de un archivo.

    
    ```
    mv index.html myProyect.html
    
    ```

* ### git diff

    Con este comando veremos de una manera más visual los cambios en algun archivo.

    
    ```
    git diff
    
    ```

* ### git branch

    Este comando muestra la rama en la que estamos.

    
    ```
    git branch
    
    ```

* ### git branch -m

    Este comando sirve para cambiarle el nombre a una branch (rama) de nuestro repositorio de GIT.

    
    ```
    git branch -m Rama-1
    
    ```

* ### git checkout -b

    Este comando sirve para crear una nueva branch (rama) en nuestro repositorio de GIT y cambiarnos hacia ella.

    
    ```
    git checkout -b Rama-2
    
    ```

* ### git checkout

    Con este comando nos cambiaremos a diferentes branch (ramas) de nuestro depositorio de GIT.

    
    ```
    git checkout Rama-3
    
    ```

* ### git log

    Este comando mostrará a detalle el historial de nuestro repositorio de GIT.

    
    ```
    git log
    
    ```

* ### git log --online 

    Este comando mostrará la información más importante en el historial de nuestro repositorio de GIT.

    
    ```
    git log --online
    
    ```

* ### cat

    Este comando mostrará el contenido de nuestro archivo.

    
    ```
    cat 
    
    ```

* ### git merge

    Este comando sirve para enviar las modificaciones de un branch al branch principal de nuestro repositorio.

    
    ```
    git merge main
    
    ```

* ### git branch -d

    Este comando sirve para eliminar una branch en nuestro repositorio de GIT.

    
    ```
    git branch -d Rama-1
    
    ```

* ### git push -u origin 

    Este comando sirve para mandar a nuestro repositorio todas nuestras modificaciones y archivos creados en el branch.

    **Cuando modifiquemos un archivo ya existente en el branch es necesario hacer esto para ver las nuevas modificaciones del archivo ya en el repositorio.**

    
    ```
    git push -u origin main
    
    ```

## Comentarios Finales

Estos son los comando más utilizados e importantes para empezar a dominar GIT e ir explorando y trabajando con está herramienta super importante en el mundo TEC, si quieres escucharlo y verlo de una manera más detallada para complementar está información aquí te dejo el link a mi curso de Youtube explicando la teoría de éste repositorio.

### Curso Creado por Christian Mendoza 2025