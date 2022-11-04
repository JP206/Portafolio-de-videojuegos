<p>Este fue un juego desarrollado como proyecto final en el curso de Introducción al Desarrollo de
Videojuegos en Unity de edX.</p>
<p>La consigna consistía en desarrollar un juego del estilo de Fruit Ninja, en el cual se utilizaran corrutinas. Adicionalmente le agregué funciones y detalles como frenar todo movimiento con la barra espaciadora, música, sistemas de partículas, y demás.</p>
<p>En esta carpeta se encuentra la carpeta con el juego. Al clonar el repositorio es posible jugar a Stone Destroyer al hacer doble click en el ejecutable.</p>
<p>Debajo hay un video mostrando el funcionamiento del juego, y algunas imágenes del código.</p>


```diff
@@ Funcionamiento del juego: @@
```
<p>El jugador deberá destruir todas las rocas lanzadas exceptuando las rojas, de lo contrario perderá.</p>
<p>En el video se puede apreciar la pantalla principal, los sistemas de partículas al destruir rocas, detener el movimiento con la barra espaciadora y ver cómo luce una derrota.</p>

https://user-images.githubusercontent.com/88661539/199898694-a9be5955-b3d1-4668-923c-9f6485407eb1.mp4

```diff
@@ Fragmento de código conteniendo la corrutina encargada de lanzar rocas aleatoriamente: @@
```
![corrutina](https://user-images.githubusercontent.com/88661539/199899706-e611b6e6-dbba-4c9f-9d27-5db0920b6ae6.png)

```diff
@@ Clase que modela las rocas: @@
```
![piedras](https://user-images.githubusercontent.com/88661539/199899812-93d55bd3-2b7c-4bb1-8054-cf6a7e2497c0.png)

```diff
@@ Interfaz de Unity en la escena del juego. En el inspector, a la derecha, se pueden observar algunos de los @@
@@ componentes de una roca: @@
```
![unity](https://user-images.githubusercontent.com/88661539/199899936-1d25d39e-15fa-4c2e-a146-0c69e94d39c8.png)
