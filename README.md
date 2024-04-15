# Hello Kitty Carrito de compra 👩‍💻

## ⚙️ Funcionalidad:
+ Permite agregar, eliminar y modificar la cantidad de productos en un carrito de compras virtual.
+ Muestra el total del carrito y lo actualiza dinámicamente según se agregan o eliminan productos.
+ Oculta el carrito si está vacío.
Estructura:

## 🚀 Variables:
`carritoVisible`: Controla la visibilidad del carrito.
`botonesEliminarItem`: Almacena los botones de eliminación de cada producto.
`botonesSumarCantidad`: Almacena los botones para aumentar la cantidad de cada producto.
`botonesRestarCantidad`: Almacena los botones para disminuir la cantidad de cada producto.
`botonesAgregarAlCarrito`: Almacena los botones para agregar productos al carrito.

## 🚀 Funciones:
`ready()`: Se ejecuta cuando la página está lista y configura los eventos para los botones.
`pagarClicked()`: Elimina todos los productos del carrito, actualiza el total y lo oculta.
`agregarAlCarritoClicked(event)`:
✔️ Obtiene la información del producto (título, precio, imagen) del botón clickeado.
✔️ Agrega el producto al carrito creando un elemento HTML dinámico.
✔️ Controla que el producto no se agregue dos veces.
✔️ Actualiza el total del carrito.
✔️ Muestra el carrito si está oculto.

`hacerVisibleCarrito()`: Muestra el carrito.
`agregarItemAlCarrito(titulo, precio, imagenSrc)`: Crea el HTML para el elemento del producto en el carrito y lo agrega.
`sumarCantidad(event)`: Aumenta la cantidad de un producto en el carrito y actualiza el total.
`restarCantidad(event)`: Disminuye la cantidad de un producto en el carrito y actualiza el total.
`eliminarItemCarrito(event)`: Elimina un producto del carrito y actualiza el total.
`ocultarCarrito()`: Oculta el carrito si está vacío.
`actualizarTotalCarrito()`: Recorre los productos del carrito, calcula el total y lo muestra.

## ☑️ Detalles adicionales:
* Utiliza clases CSS para identificar y manipular elementos HTML.
* Maneja eventos click para capturar las interacciones del usuario con los botones.
* Actualiza dinámicamente el DOM (contenido de la página) para reflejar los cambios en el carrito.
* Utiliza expresiones regulares para eliminar símbolos de moneda y puntos de miles al calcular el total.
* Implementa validación básica para evitar agregar productos duplicados.

![](image.png)
