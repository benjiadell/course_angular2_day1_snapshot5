Angular 2: Getting Started - SnapShot 5
===================
En esta parte veremos estos contenidos del curso de Pluralshight:

 - Building Nested Components

Building Nested Components
-------------------

En esta eccion el objetio es crear un Nested Component, en concreto, a Star Component para las puntuaciones del producto.

![enter image description here](https://i.imgur.com/IPI3bLi.png)

#### Building & using a Nested Component
Para crear un Nested Component necesitamos una plantilla y una clase. Para utilizarlos necesitamos referenciarlo desde otro componente mediante la directiva definida, en este caso: **ai-star**
![enter image description here](https://i.imgur.com/lexsIP7.png)
#### Passing Data to Nested Component using @Input
Para representar la puntuacion del producto necesitamos indicar al componente que valor debe representar. Paa ellos utilizaremos un parametro @Input
#### Passing Data fromNested Component using @Output
En muchos casso necesitamos emitir mediante un evento alguna accion. Es importante recalcar que la unica manera de utilizar @Output es mediante un evento **EventEmmitter<>** En nuestro caso emiteremos un evento cuando se haga click dentro del componente.

Para ello clonamos el **SnapShot 5** desde le primer commit de:

    git clone https://github.com/tc-frontend/course_angular2_day1_snapshot5
    git checkout HEAD~1
    npm install
    code .
 
Seguimos los pasos detallados en el historial de commits:

    https://github.com/tc-frontend/tc-frontend-angular2_day1_snapshot5/commits/master   
  
Si queremos ver la App en nuestro browser

    npm start

Si queremos ver la solucion final de este SnapShot:

    git checkout master
    npm install
    npm start



