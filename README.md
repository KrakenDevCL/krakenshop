# 💳 Simulador de Compras con Tarjeta de Crédito

Este proyecto es una aplicación de consola simple escrita en Java que simula el uso de una tarjeta de crédito. Permite al usuario establecer un límite de crédito y luego registrar compras una por una. El programa valida cada compra contra el saldo disponible y, al finalizar, muestra una lista ordenada de todas las compras realizadas y el saldo restante.

## ✨ Características

* **Límite de Crédito:** El usuario define el límite total de la tarjeta al iniciar el programa.
* **Registro de Compras:** Permite ingresar la descripción y el valor de múltiples compras.
* **Validación de Saldo:** Comprueba si el usuario tiene saldo suficiente para cada compra. Si una compra excede el límite, se rechaza y el programa finaliza.
* **Resumen Final:** Al terminar, el programa muestra:
    * Una lista de todas las compras realizadas, ordenadas por valor.
    * El saldo final restante en la tarjeta.

## 💻 Tecnologías Utilizadas

* **Java**
* **POO (Programación Orientada a Objetos):** El código está estructurado en clases (se asume `Principal`, `TarjetaDeCredito`, `Compra`).
* **`java.util.Scanner`:** Para recibir la entrada del usuario por consola.
* **`java.util.Collections`:** Para ordenar la lista de compras.

## 🚀 Cómo Usar

1.  Asegúrate de tener todas las clases necesarias (`Principal.java`, `TarjetaDeCredito.java`, `Compra.java`) en tu proyecto.
2.  Compila y ejecuta la clase `Principal.java`.
3.  Sigue las instrucciones en la consola para ingresar el límite de tu tarjeta y registrar tus compras.

## 📄 Ejemplo de Ejecución

Así es como se ve el programa en funcionamiento:

Escriba el limite de la tarjeta: 1500 Escriba el articulo que va a comprar: Audifonos Escriba el valor de la compra: 300 Compra realizada! Escriba 0 para salir o 1 para continuar 1 Escriba el articulo que va a comprar: Teclado Escriba el valor de la compra: 500 Compra realizada! Escriba 0 para salir o 1 para continuar 1 Escriba el articulo que va a comprar: Monitor Escriba el valor de la compra: 800 Saldo insuficiente!

COMPRAS REALIZADAS:

Audifonos - 300.0 
Teclado - 500.0

*******************************
Saldo de la tarjeta: 700.0
