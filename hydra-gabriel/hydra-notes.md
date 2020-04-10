# hydra-notes

## Starting
You can use atome code editor or hydra on the browser.

https://github.com/diegodorado/taller-hydra

https://hydra-editor.glitch.me/

Una vez instalado. Probar los ejemplos inciales 

https://github.com/ojack/hydra-examples/blob/master/0-getting-started.js

En atom para correr una línea de código das shift+enter
Y para correr todo el bloque de código ctrl+enter

Probar el helloWorld en atom o en el browser

  ```atomHydra
  //osc (frecuencia, sync (velocidad que se mueve), offset(rgb))
 osc().out()
  ```
Podemos escoger screens abiertas de la computadora o la cámara
 ```atomHydra
  
 s0.initScreen(0) //initCam(0)
 src(s0).out()
  ```
### Solid
Sirve para pintar colores enteros. Al utilizar [ ] es para ir cambiando en un arreglo de valores.
hay cuatro outputs que puedes combinar. Utilizas render() para ver todos o señalar cual quieres ver. 
 ```atomHydra
  
solid([1,0,1],[1,0,0],[0,1,0],1).out(o0)
solid([1,0,0.2],[0,1,0],[0.5,1,0],1).out(o1)
render()
  ```

by Gabriel Andrade

## Notes


