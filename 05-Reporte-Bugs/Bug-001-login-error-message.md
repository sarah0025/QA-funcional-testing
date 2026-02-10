BUG 001 – Mensaje de error genérico en login

ID: BUG-001  
Módulo: Login  
Severidad: Media  
Prioridad: Media  
Estado: Abierto

DESCRIPCIÓN
Al intentar iniciar sesión con credenciales inválidas, el sistema muestra un mensaje de error genérico que no especifica claramente el motivo del fallo, lo que puede generar confusión en el usuario

PASOS PARA REPRODUCIR
1. Acceder a la página de login de Sauce Demo
2. Ingresar usuario inválido
3. Ingresar una contraseña inválida
4. Hacer clic en el botón "Login"

RESULTADO ESPERADO
El sistema debe mostrar un mensaje de error claro indicando que las credenciales son incorrectas

RESULTADO ACTUAL
El sistema muestra un mensaje de error genérico sin detallar la causa del error

EVIDENCIA
Captura de pantalla del mensaje de error (ver carpeta "06-evidencias")
