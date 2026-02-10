BUG 002 – Falta de validación en campos obligatorios del checkout

ID: BUG-002
MODULO: checkout
SEVERIDAD: Alta
PRIORIDAD: Alta
ESTADO: Abierto

DESCRIPCIÓN

Durante el proceso de checkout, el sistema permite continuar al siguiente paso sin validar correctamente que todos los campos obligatorios hayan sido completados, lo que puede provocar errores en el proceso de compra.

PASOS PARA REPRODUCIR
1. Iniciar sesión con usuario válido
2. Agregar uno o más productos al carrito
3. Acceder al carrito y hacer clic en "checkout" 
4. Dejar uno o más campos obligatorios vacíos
5. Hacer clic en botón "Continue"

RESULTADO ESPERADO
- El sistema debe validar los campos obligatorios
- Se deben mostrar mensajes de error indicando que campos faltan por completar
- No debe permimtir avanzar en el proceso
  
RESULTADO ACTUAL
El sistema permite avanzar al siguiente paso sin validar correctamente todos los pasos obligatotios

EVIDENCIA
Captura de pantalla del formulario de checkout sin validaciones visibles
