# Algoritmo: Verificacion de número telefonico en una aplicaión

## Descripción
Algoritmo que describe el proceso de verificación de un número 
telefónico al registrarse en una aplicación.

## Pasos:
``text
INICIO
1. Descargar la aplicación.
2. Instalar la aplicación.
3. Abrir la aplicación.
4. Ingresar número telefónico.

SI el número es válido ENTONCES
 - Enviar código de verificación
SI el número es inválido ENTONCES
 - Mostrar mensaje de error.
 - Solicitar ingresar nuevamente el número.

5. Ingresar código de verificación

SI el código es correcto ENTONCES
 - Permitir acceso a la aplicaión
SI el código es incorrecto ENTONCES
 - Mostrar mensaje de error
 - Permitir reintento
FIN
``

### PSEUDOCÓDIGO
``
INICIO
DESCARGAR aplicación
INSTALAR aplicación
ABRIR aplicación

LEER numero_telefonico

SIumero_telefonico ES válido entonces
ENVIAR codigo_verificaion
SINO n
MOSTRAR "Númwero INválido"
SOLICITAR nuevo numero
FIN SI

LEER coigo_verificacion
SI coigo_verificacion ES correcto ENTONCES
PERMITIR acceso
SINO
MOSTRAR "Código Incorrecto"
PERMITIR reintento
FIN SI
FIN
``


 
