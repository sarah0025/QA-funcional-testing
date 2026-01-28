CASOS DE PRUEBA - CHECKOUT

Aplicación: Sauce Demo 
Modulo: Proceso de Checkout

CHECKTOUT-001 - INICION DE CHECKOUT CON PRODUCTOS EN EL CARRITO

Precondiciones:
- El usuario se encuentra autenticado
- Al menos un producto agregado al carrito

Pasos:
1. Acceder al carrito
2. Hacer clic en el botón "Checkout"

Resultado esperado
- El producto redirige a la pantalla de ingreso de información personal

CHECKTOUT-002 - CHECKOUT CON INFORMACIÓN VÁLIDA

Precondiciones:
- El usuario se encuentra autenticado
- Al menos un producto agregado al carrito
- El usuario debe estar en la pagina de checkout

Pasos:
1. Ingresar nombre
2. Ingresar apellido
3. Ingresar codigo postal
4. Hacer clic en el botón "Continue"

Resultado esperado
- El sistema permite continuar con el proceso de compra
- Se muestra el resumen de la orden

CHECKTOUT-003 - CAMPOS OBLIGATORIOS VACÍOS

Precondiciones:
- El usuario se encuentra autenticado
- El usuario debe estar en la pagina de checkout

Pasos:
1. NO ingresar información en los campos requeridos
2. Hacer clic en el botón "Continue"

Resultado esperado
- El sistema no permite avanzar en el proceso
- El sistema muestra mensajes de validación

CHECKTOUT-004 - FINALIZAR COMPRA EXITOSAMENTE

Precondiciones:
- El usuario se encuentra autenticado
- Información de checkout válida
- Usuario en el resumen de la orden

Pasos:
1. Hacer clic en el botón "Finish"

Resultado esperado
- El sistema confirma la compra
- El sistema muestra mensaje de COMPRA EXITOSA
