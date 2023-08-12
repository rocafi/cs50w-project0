
# Project 0

Web Programming with Python and JavaScript

Se desarrollo este proyecto con la finalidad de culminar el primer proyecto del web50ni, "Project0", en donde se nos asigno implementar diferentes funcionalidades utilizando SASS y Bootstrap

## De que trata?
Se trata de un sitio web tipo blog, en el cual se muestra informacion acerca de la franquicia de Pokémon, en especifico en una de las regiones que implementaron en mas de sus 9 que llevan actualmente, la cual es la region de Johto

### Index
En la pagina principal se muestra una descripcion de lo que es la region, su etimologia, origen y geografia

### Liga
en esa pagina se muestra de que se trata la liga en pokemon, la cual es una mecanica implementada en sus juegos y anime entre otros

### Pokedex
Aqui se intento implementar una funcionalidad con sass, la cual seria un filtro que permite mostrar por tipo de pokemon entre una lista que se muestra

### juegos
la ultima pagina se encarga de mostrar lo que son algunos de los juegos implementados en el mismo tiempo que fue implementada la region de Johto, la cual seria la segunda generacion

## Implementaciones
#### Tu sitio debe contener al menos 4 diferentes páginas .html, y debe ser posible entrar desde una página hasta otra siguiendo uno o más hipervínculos.
- posee inicio, liga, pokedex y juegos
#### Tu sitio debe contener al menos una lista (ordenada o desordenada), al menos una tabla y al menos una imagen.
- linea 69 del index (lista desordenada)
- linea 119 del index (tabla)
- las imagenes estan a simple vista
#### Tu sitio debe contener al menos una hoja de estilos.
- posee la hoja de estilos main.css que fue compilada de sass
#### Tu sitio debe usar al menos 5 diferentes propiedades CSS, y al menos 5 selectores diferentes. Debes usar el selector de id y el de class al menos una vez.
- eso se puede encontrar en cualquier parte de los archivos sass, utilize varios
#### Tu sitio debe contener al menos un selector responsivo @media query, que debe aplicarse a pantallas más pequeñas.
- tambien se puede encontrar en cualquier archivo sass o en el main.css
#### Debes usar bootstrap 4 en tu sitio, para utilizar al menos un componente de bootstrap, y al menos dos columnas de bootstrap usando su grid layout.
- utilize las columnas en la pagina de liga (linea 77) y el componente de cards en la pagina de juegos (linea 49)
#### Tus hojas de estilo deben contener al menos una variable SCSS, al menos un ejemplo de anidamiento SCSS y al menos un uso de herencia SCSS.
- en section-index.sass se encuentra un uso de herencia en la linea 5 y utilizandola en la linea 21
- el anidamiento se encuentra en todos los archivos sass
- las variables se encuentran en el archivo main