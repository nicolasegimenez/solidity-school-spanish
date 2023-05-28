# Hola mundo
## Declaración de problema

Escriba un contrato para imprimir una cadena "Hello World!". La impresión no debe involucrar uso de gas. Vas a tener que usar [Remix](https://remix.ethereum.org/).
Si sos medio opa, no googleaste nada  y no sabes como usar remix acá te dejo un [mini tutorial](https://collectednotes.com/nicoarkano/hola-mundo-en-solidity).

Ojo el Hola Mundo no es exactamente el mismo. Te aviso por si te pinta el Kakashi. 


## Sugerencia informativa
Para definir una función que no debe consumir ningún gas y devolver la respuesta inmediatamente, debemos usar la función `view` o `pure`.

* <b> Ver funciones: </b> Las funciones se pueden declarar vista en cuyo caso prometen no modificar el estado.
* <b> Funciones puras: </b> Las funciones pueden declararse puras, en cuyo caso prometen no leer o modificar el estado.
