# Lab: Moviendo a bird utilizando position, top, y left

## Objetivos
- Agregar estilos utilizando selectores de `id` y `class`
- Utilizar la propiedad `position: absolute`
- Utilizar las propiedades `top` y `left` para posicionar elementos


## Introducción 
Hemos aprendido que cuando un elemento tiene `position: absolute`, este se posiciona con respecto al origen de coordenadas de su ancestro posicionado más cercano (es decir, el ancestro más cercano que no es `static`).Básicamente, el elemento se desplaza respecto a las coordenadas de origen, y la magnitud del desplazamiento es determinado por el valor de `top`, `right`, `bottom` y `left`.


## Funcionalidad del Código
En este lab moveremos la imágen de flappy-bird mediante la propiedad `position`

## Instrucciones 
Bifurca (fork) y clona (clone) este lab en tu entorno local. Navega a su directorio en la terminal, luego ejecuta el comando `code .` para abrir sus archivos en Visual Studio Code. 

1. Agrega `position: absolute;` a la clase `flappy-js` en tu archivo `style.css`
2. Posiciona `#flappy-bird` de tal forma que tenga `bottom: 50px `y `left: 50px `
