# CrombieWalletQA

Descargable: [Test Cases](https://docs.google.com/spreadsheets/d/1VIVNfrzXtxhWzyKC57z6o0tdURyTwaQWdc4ca0nF3RY/edit?usp=sharing)

Este es un conjunto de pruebas y reportes que diseñé sobre el proyecto CrombieWallet.

El propósito de este documento es el de describir la manera en que será testeado el proyecto CrombieWallet. El objetivo de estos casos de prueba es evaluar la funcionalidad del sitio web, y por consiguiente identificar y listar cualquier defecto que pueda ser descubierto durante el proceso de pruebas.

CrombieWallet es un proyecto que fue desarrollado en el marco de la Escuela de Programación de Crombie como práctica para desarrollo web, y las historias de usuario han sido copiadas textualmente del repositorio original.

Aparte de las pruebas descritas en el documento, también se realizará una serie de pruebas exploratorias con la intención de cubrir la mayor parte del proyecto como sea posible, teniendo en cuenta que cuanto mayor es la extensión de un proyecto, más difícil es cubrir el 100% de las posibilidades de valores de entrada en cada escenario.

Los defectos encontrados a lo largo de la ejecución de estas pruebas y del testing exploratorio pueden verse en la sección Issues del repositorio.





## Historias de Usuario
### HU1 - Registro de Usuario
La aplicación deberá tener un formulario de registro de usuario que solicita los siguientes datos:

* Nombre de usuario.
* Email (debe ser un correo válido).
* Contraseña (debe tener al menos 8 caracteres, incluyendo letras, números y al menos un carácter especial).

Agregado de valor:
Enviar un email al usuario para confirmar la activación de la cuenta.

### HU2 - Inicio de Sesión
La aplicación deberá tener un formulario de inicio de sesión que solicita los siguientes datos:

* Email.
* Contraseña.
Ambos campos son necesarios para iniciar sesión.

### HU3 - Registrar Movimiento de Dinero
La aplicación cuenta con un formulario para registrar un movimiento de dinero, ya sea de ingreso o egreso. Los detalles del movimiento son:

* Monto (puede tener como máximo dos decimales).
* Título del movimiento.
* Descripción para justificar el movimiento.

### HU4 - Home
En la página principal se le muestra al usuario:

* El balance total de su dinero.
* Su nombre de usuario.
* Un botón para registrar un movimiento.
* Un botón para ocultar el balance.
* Un listado de los últimos movimientos. El listado de movimientos está paginado, ordenado por fecha e indica el monto, el tipo de movimiento y la fecha.

Agregados de Valor Generales
* Gráfico de tortas y de gráfico de areas que indican el movimiento del dinero en el tiempo.
* API que detalla el valor actual del dólar para conocer el valor dolarizado.
* Notificador de gastos que genera una notificación cuando el usuario supera un cierto monto de dinero establecido por el usuario.
* Internacionalización: Se puede elegir el idioma con un toggle en donde podrás ver la aplicación en español o en inglés.
* Extra: Se puede elegir entre tema claro/oscuro con un toggle donde podras visualizar la aplicación en los distintos modos.
