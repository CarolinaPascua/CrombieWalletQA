# CrombieWalletQA
Este es un conjunto de pruebas y reportes que diseñé sobre el proyecto CrombieWallet que desarrolló la Escuelita de Programación de Crombie en el año 2023.


#Historias de Usuario
HU1 - Registro de Usuario
La aplicación deberá tener un formulario de registro de usuario que solicita los siguientes datos:

Nombre de usuario.
Email (debe ser un correo válido).
Contraseña (debe tener al menos 8 caracteres, incluyendo letras, números y al menos un carácter especial).
Agregado de valor:
Enviar un email al usuario para confirmar la activación de la cuenta.

HU2 - Inicio de Sesión
La aplicación deberá tener un formulario de inicio de sesión que solicita los siguientes datos:

Email.
Contraseña.
Ambos campos son necesarios para iniciar sesión.

HU3 - Registrar Movimiento de Dinero
La aplicación cuenta con un formulario para registrar un movimiento de dinero, ya sea de ingreso o egreso. Los detalles del movimiento son:

Monto (puede tener como máximo dos decimales).
Título del movimiento.
Descripción para justificar el movimiento.
HU4 - Home
En la página principal se le muestra al usuario:

El balance total de su dinero.
Su nombre de usuario.
Un botón para registrar un movimiento.
Un botón para ocultar el balance.
Un listado de los últimos movimientos. El listado de movimientos está paginado, ordenado por fecha e indica el monto, el tipo de movimiento y la fecha.
Agregados de Valor Generales
Gráfico de tortas y de gráfico de areas que indican el movimiento del dinero en el tiempo.
API que detalla el valor actual del dólar para conocer el valor dolarizado.
Notificador de gastos que genera una notificación cuando el usuario supera un cierto monto de dinero establecido por el usuario.
Internacionalización: Se puede elegir el idioma con un toggle en donde podrás ver la aplicación en español o en inglés.
Extra: Se puede elegir entre tema claro/oscuro con un toggle donde podras visualizar la aplicación en los distintos modos.
