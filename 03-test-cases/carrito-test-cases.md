CASOS DE PRUEBA - CARRITO DE COMPRAS

Aplicación: Sauce Demo
Modulo: Carrito de compras

CART-001 - AGREGAR PRODUCTO AL CARRITO

Precondiciones:
- El usuario se encuentra autenticado
- El usuario se encuentra en el listado de productos

Pasos:
1. Seleccionar un producto
2. Hacer clic en el botón "Add to cart"

Resultado esperado
- El producto se agrega al carrito
- El contador del carrito se incrementa

CART-002 - ELIMINAR PRODUCTO DEL CARRITO

Precondiciones:
- El usuario se encuentra autenticado
- Producto que haya sido agregado al carrito

Pasos:
1. Acceder al carrito
2. Hacer clic en el botón "Remove"

Resultado esperado
- El producto se elimina del carrito
- El contador del carrito se actualiza

CART-003 - VISUALIZAR PRODUCTOS EN EL CARRITO

Precondiciones:
- El usuario se encuentra autenticado
- Productos que hayan sido agregados al carrito

Pasos:
1. Acceder a la vista del carrito

Resultado esperado
- El sistema muestra los productos agregados
- Se visualiza nombre, precio y cantidad


CART-004 - CARRITO VACÍO

Precondiciones:
- El usuario se encuentra autenticado
- NO hay productos agregados al carrito

Pasos:
1. Acceder a la vista del carrito

Resultado esperado
- El sistema indica que el carrito está vacío
