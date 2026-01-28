CASOS DE PRUEBA - LOGIN

Aplicación: Sauce Demo
Modulo: Autenticación

LOGIN-001 - INICIO DE SESIÓN EXITOSO

Precondiciones: 
- El usuario se encuentra ubicado en la página del login
- El usuario cuenta con credenciales válidas

Pasos:
-1 Ingresar usuario válido
-2 Ingresar contraseña válida
-3 Hacer clic en el botón "Login"

Resultado esperado
- El sistema permite el acceso
- El usuario es redirigido al listado de productos

LOGIN-002 - USUARIO INVALIDO

Precondiciones: 
- El usuario se encuentra ubicado en la página del login

Pasos:
-1 Ingresar usuario inválido
-2 Ingresar contraseña válida
-3 Hacer clic en el botón "Login"

Resultado esperado
- El sistema NO permite el acceso
- El muestra un mensaje de ERROR

LOGIN-003 - CONTRASEÑA INVALIDO

Precondiciones: 
- El usuario se encuentra ubicado en la página del login

Pasos:
-1 Ingresar usuario válido
-2 Ingresar contraseña inválida
-3 Hacer clic en el botón "Login"

Resultado esperado
- El sistema NO permite el acceso
- El muestra un mensaje de ERROR

LOGIN-004 - CAMPOS VACÍOS

Precondiciones: 
- El usuario se encuentra ubicado en la página del login

Pasos:
-1 NO ingresar usuario 
-2 NO ingresar contraseña
-3 Hacer clic en el botón "Login"

Resultado esperado
- El sistema NO permite el acceso
- El sistema debe mostrar un mensaje de VALIDACIÓN
