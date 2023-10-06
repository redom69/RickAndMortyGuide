# RickMortyExercise

Esta es una guia completa de todos los personajes de Rick y morty que podemos econtrar en esta API: https://rickandmortyapi.com/api/character

## Método de ejecución

El método que he utilizado yo para ejecutar este repositorio es el siguiente, me he creado un dispositivo vistual en android studio. Estos pasos tambien se podrán replicar desde Xcode para iOS, o desde dispositivos físicos con sus respectivas aplicaciones.
Una vez tengamos ya el dispositivo activo simplemente tendremos que ejecutar el siguiente comando:
```
yarn start
```
Al haber implementado la aplicación con expo, esto por debajo ejecuta el comando:
```
expo start
```
que lanzará expo y hará posible el despliegue de la aplicación en el dispositivo móvil.
Seleccionaremos el sistema operativo que deseamos y se lanzará en el dispositivo seleccionado anteriomente.

## Explicación de la aplicación

Esta aplicación es una aplicación básica que lo que hará es obtener un listado de todos los personajes de Rick y Morty y filtrar por el nombre que introduzcamos en el buscador. Este listado tendrá la foto y el nombre del personaje.
Para ello se han desarrollado tres ficheros, el App.js, el Guide.js y Homescreen.js.

- *App.js*: Es el fichero que se encargará de ejecutar la aplicación y que contendrá la búsqueda de personajes.

- *Homescreen.js*: Es el fichero que se encargará de ejecutar mostrar una pantalla de inicio que dará inicio a la guia de personajes.

- *Guide.js*: Es el fichero que contiene la lógica de mostrar el listado de personajes y el filtrado por nombre. Este estará formado por dos componentes un TextInput el cual mediante un hook obtendremos los personajes que tienen ese nombre y una lista que nos mostrará los personajes.

Al entrar en la guía se mostrarán todos los personajes que estan en la API. Pero cuando introduzcamos un valor en el buscador renderizaremos la aplicación para obtener los nuevos valores de la lista y mostrarla.

## Tiempo de desarrollo

Alrededor de 1h y 35 minutos. 

