# Practica GitFlow

## Introducción:
Git es un sistema de control de versiones que permite tener un seguimiento exaustivo del trabajo en proyectos de desarrollo además de facilitar en gran medida el trabajo en equipo. 

Git Flow es una metodología basada en el modelo de ramificaciones de Vincent Driessen, que nos facilita el trabajo con nuestros repositorios. La idea principal de este método de trabajo es que se parte de dos ramas, una para desarrollo y la otra de producción. A partir de aqui si queremos implementar una nueva funcionalidad ramificaremos la rama develop para asi no "ensuciar" el trabajo que se está desarrollando, estas ramas se llamarán features. A continuación para hacer testing y la revisión de estas nuevas features se usarán las ramas release que se fusionará con develop y master una vez terminado el testing. Y por último las ramas  para solucionar bugs e issues, estas se llaman hotfix y salen de la rama producción si en esta se halla alguna incurrencia. Una vez solventado el issue, se fusionará con la rama master y la rama develop. 

## Ejercicio 1:
### Primeros pasos del usuario 1:
Creación del repositorio y estructura inicial del proyecto. 

![Creacion del repositorio](imgsDocs/1.png)

Se ha creado el repositorio en github y se le ha hecho un push para el commit inicial. 

![Creacion del repositorio](imgsDocs/2.png)

![Creacion del repositorio](imgsDocs/3.png)

Creando la nueva rama develop y publicandola en el repositorio remoto.

![Creacion del repositorio](imgsDocs/4.png)
El usuario 1 ha subido las primeras modificaciones (estructura inicial del HTML y unos cuantos estilos) al repositorio remoro, tanto a la rama master como a la rama develop.

## Ejercicio 2:
### Features del Usuario 2:

![Features del usuario](imgsDocs/5.png)
Como se puede observar en la captura el usuario 2 ha creado las dos nuevas features en el repositorio local.

![Features del usuario](imgsDocs/6.png)
![Creacion del repositorio](imgsDocs/7.png)

A continuación se ha creado el nuevo feature y se ha subido esta rama al repositorio remoto.


![Creacion del repositorio](imgsDocs/9.png)
![Creacion del repositorio](imgsDocs/8.png)

Se ha completado el feature de modificar atributos html y este se ha subido al repositorio remoto.

## Ejercicio 3:
### Features del Usuario 3:

![Creacion del repositorio](imgsDocs/11.png)
![Creacion del repositorio](imgsDocs/10.png)

El usuario 3 ha creado y subido su feature al repositorio remoto.

### Release:

![Creacion del repositorio](imgsDocs/12.png)
![Creacion del repositorio](imgsDocs/13.png)

Se han traido los cambios de las ramas remotas y se han integrado en la rama de release para tener una versión. Como se puede observar en la segunda imagen, se han traido todos los archivos que se habian creado en las ramas remotas.

![Creacion del repositorio](imgsDocs/14.png)

Se ha creado el nuevo tag en la rama de la release que ha hecho el usuario 3.

![Creacion del repositorio](imgsDocs/15.png)

Publicando los cambios en las ramas master y develop.

![Creacion del repositorio](imgsDocs/17.png)
![Creacion del repositorio](imgsDocs/18.png)
Rama Master remota
![Creacion del repositorio](imgsDocs/19.png)
Rama Develop remota

Publicando los cambios en las ramas remotas

![Creacion del repositorio](imgsDocs/20.png)

Subida del tag a la rama master remota.

## Hotfix

![Creacion del repositorio](imgsDocs/21.png)

Se ha solucionado el hotfix y este se ha subido a la rama master del remoto y a la rama develop para que estos dos tengan el bug solucionado