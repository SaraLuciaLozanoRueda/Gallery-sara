# Gallery sara

```
transition: transform 0.3s ease-in-out;
```

esta propiedad  es la responsable del movimiento con un efecto de transición con un inicio y un final lentos

```
.grid-item:hover{

  filter: opacity(0.9);

}
```

cuando usamos esta línea  de código significa que cada vez que nos situemos sobre un .grid-item este se tornara de un color un poco mas opaco en este caso un 0.9 de el color #03afff.

```
transform: scale(1.04)
```

esta línea de código (es el complemento de transition) representa el valor en el  aumento de tamaño cada vez que nos posicionamos en un .grid-item

```
minmax(200px,auto);
```

en esta propiedad le estamos indicando en el primer valor el tamaño mínimo que puede tener la celda y el segundo valor indica el máximo

- gap: es el espacio entre los grid
- padding: es el espacio entre el margen y nuestro contenido

```
grid-auto-flow:dense
```

#### RESPONDA:

- Que hace un MediaQuery: Al parecer un @media funciona como if, debido a que comprueba el tamaño y/o resolución, pienso que esta propiedad nos ayudara mucho para hacer una pagina responsive

- Que hace un min-width: esto hace que el tamaño mínimo que toma la celda sea de 600px

- span: esta propiedad nos ayuda a que  nuestro ítem escogido tome 2 espacios.

  ```
   .wide{
          grid-column:span 2;
      }
      .tall{
          grid-row:span 2;
      }
  ```

  en el primero toma el dos espacios de la columna

  en el segundo toma dos espacios de la fila

​	y en el index.html especificamos un .grid-item con ambas funciones y es por eso 	que toma ambas propiedades.

#### .grid-item

- **background-size:cover**

  cambia el tamaño de fondo para cubrir todo el contenedor

- **background-position:center**

  posicion inicial de la imagen en este caso el centro

- **background-repeat:no repeat**

  compara las imágenes de las celdas para no repetirlas