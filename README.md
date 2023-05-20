# Cifrado César - Santa Secreto

## Índice

* [1. Introducción](#1-introduccion)
* [2. Definición del proyecto](#2-definicion-del-proyecto)


***

## 1. Introducción

Este proyecto es un sitio web creado como primera actividad del bootcamp de Laboratoria. 
Con el fin de introducirnos al mundo de la programación, se nos dio la opción de elegir entre Validación de Tarjetas o un sistema de Cifrado César, siendo esta última la elección para este proyecto. En términos generales, el uso de un sistema de Cifrado César para un sitio web busca entregar al usuario una herramienta funcional para cifrar/codificar cualquier tipo de mensajes, dando también la opción de descifrarlo/decodificarlo, y además la posibilidad de seleccionar un número “clave” para usarlo en el sistema de cifrado.
El cifrado de tipo César se basa en un sistema de sustitución de las letras del abecedario, en el que el número usado como “clave” es la cantidad de espacios que una letra es desplazada y reemplazada por otra.


![caeser-cipher](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2b/Caesar3.svg/2000px-Caesar3.svg.png)

Por ejemplo, si tenemos el mensaje HOLA AMIGOS (_offset_) ("clave") de 3 posiciones:

* La letra A se cifra como K.
* La frase HOLA AMIGOS se cifra como KROD DPLJRV.
* Alfabeto sin cifrar: A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
* Alfabeto cifrado: D E F G H I J K L M N O P Q R S T U V W X Y Z A B C

En la actualidad, todos los cifrados de sustitución simple se descifran con
mucha facilidad y, aunque en la práctica no ofrecen mucha seguridad en la
comunicación por sí mismos; el cifrado César sí puede formar parte de sistemas
más complejos de codificación, como el cifrado Vigenère, e incluso tiene
aplicación en el sistema ROT13.

## 2. Definición del proyecto

La idea de esta aplicación web nació desde el hecho de que el sistema de cifrado César, actualmente, no es considerado una manera segura de proteger mensajes ni entregar confidencialidad en el mundo real, por lo mismo, pensé en darle un enfoque para que el cifrado cumpla su función y también uno con el que los usuarios objetivos de esta aplicación puedan quedar conformes con su funcionalidad. Así se me ocurrió la idea de enfocar el proyecto en el cifrado y descifrado de cartas de navidad dirigidas a Santa Claus (Papá Noel, Viejito Pascuero, etc.), con niñas, niños y niñes pequeños como principales usuarios del producto.
Esta aplicación web le entrega una posible solución al problema de que el usuario no quiera que algún adulto (sus padres, por ejemplo), sepan lo que le va a pedir a Santa para navidad. La intención es mantener el concepto del cifrado y descifrado simple para que así usuarios jóvenes puedan usarlo. Si el niño sabe leer, escribir e interactuar con sitios web de baja complejidad, entonces está capacitado para utilizar el sitio de Santa Secreto por sí mismo.
Asimismo, al ser una aplicación web centrada en la navidad, se eligieron colores asociados a estas fechas para ser usados en la interfaz. Finalmente, se optó por uso de fuente Arial para el título, instrucciones y para el texto sujeto a cifrado, ya que esta tipografía se encuentra entre las reconocidas como amigables para personas con dislexia, y por consiguiente, taclea la posibilidad de un usuario con dislexia todavía no diagnosticada por corta edad.
