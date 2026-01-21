# luisplis/e-plantShopping

[luisplis/e-plantShopping](https://github.com/luisplis/e-plantShopping.git)

Crearás la interfaz de usuario de una aplicación de compras llamada “Vivero Paraíso”. La interfaz de la aplicación te permitirá explorar una variedad de plantas de interior y añadirlas a un carrito de compras. La función del carrito de compras te permite ver todos tus artículos y su costo total. Tu carrito de compras también debería permitirte ajustar la cantidad de artículos en el carrito antes de realizar el pago.

Las páginas de listado de productos y del carrito de compras deben tener un encabezado. El encabezado debe tener un ícono de carrito de compras con un número que se actualiza dinámicamente, mostrando el total de artículos en el carrito. El encabezado también debe contener navegación hacia cualquiera de las otras páginas, dependiendo de en qué página te encuentres.

## Página de Inicio

La página de inicio debe tener los siguientes elementos:

- Una imagen de fondo
- Un párrafo sobre la empresa
- El nombre de la empresa
- Un botón de Comenzar que enlace a la `Página Listado de Productos`

### Navegación

> El botón de **Comenzar** de la `Página de Inicio` redirige a la `Página Listado de Productos` y la `Barra de Navegación` será visible desde entonces, esta contiene tres enlaces:

- Paradise Nursey: enlace a la `Página de Inicio`.
- Plants: enlace al `Listado de Productos`.
- Ícono del carrito: enlace al `Carrito de la Compra`.

## Página Listado de Productos

La página de listado de productos debe tener al menos seis plantas (productos-artículos) de interior a la venta, organizadas en tres o más tipos de planta (categorías-secciones).

El listado mostrará las plantas por sección, cada sección mostrará el tipo de plantas a modo de título del grupo de plantas.

Cada planta debe tener los siguientes detalles:

- Imagen en miniatura
- Nombre de la planta
- Precio de la planta
- Botón de Agregar al Carrito

> El botón de **Agregar al Carrito** añade la planta al carrito de compras y queda desabilitado miesntras la planta permanezca en el mismo.

Esta página mostrará la `Barra de Navegación` con enlace al la `Página de Inicio` y la `Página Carrito de la Compra` con el ícono del carrito de compras y el número de artículos en el carrito.


## Página Carrito de la Compra

La página del carrito de compras muestra todos los detalles sobre los artículos seleccionados en la `Página Listado de Productos` destacando los detalles a modo global de la siguiente manera:

- Número total de plantas añadidas
- Coste total de todos los artículos añadidos
- Botón para continuar comprando
- Botón para realizar el pago

Además de un ficha por cada producto añadido al carrito, incluyendo:

- Imagen en miniatura de la planta o producto
- Nombre de la planta o producto
- Precio unitario del producto
- Precio total por cantidad seleccionada del producto
- Botón para aumentar o disminuir la cantidad del producto
- Botón de eliminar cada producto

> Los botones **Aumentar** y **Disminuir** y **Eliminar** actualizan el ícono del carrito en el encabezado y el número y coste total destacados en el carrito.

Esta página mostrará la `Barra de Navegación` con enlace al la `Página de Inicio` y la `Página Carrito de la Compra` con el ícono del carrito de compras y el número de artículos en el carrito.
