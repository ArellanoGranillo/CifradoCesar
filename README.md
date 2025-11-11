🔐 Proyecto: Cifrado César
📖 Descripción

Este proyecto implementa el algoritmo clásico de Cifrado César, un método de encriptación simple utilizado desde la época del Imperio Romano.
Permite encriptar y desencriptar mensajes desplazando las letras del alfabeto un número determinado de posiciones.

El usuario puede ingresar un texto y elegir el número de desplazamientos. El programa devolverá el mensaje encriptado o desencriptado según la opción seleccionada.

⚙️ Características

Encripta y desencripta textos en español.

Preserva:

Mayúsculas,

tildes,

signos de puntuación y espacios (no se alteran).

El desplazamiento se aplica solo a letras minúsculas del alfabeto español (a–z, incluyendo ñ).

Permite elegir cualquier valor de desplazamiento, por ejemplo:

Desplazamiento de 3 → “hola” → “krñd”

Desplazamiento de 10 → “hola” → “ryvk”

🧠 Funcionamiento del algoritmo

El Cifrado César reemplaza cada letra del texto original por otra que se encuentra n posiciones adelante en el alfabeto.
Si el desplazamiento excede la ‘z’, el conteo vuelve al inicio del alfabeto.

Ejemplo:

Alfabeto: a b c d e f g h i j k l m n ñ o p q r s t u v w x y z
Texto original: hola
Desplazamiento: 10
Resultado: ryvk


Para desencriptar, se aplica el desplazamiento en sentido contrario.

🧩 Tecnologías utilizadas

Lenguaje: Java

Paradigma: Programación Orientada a Objetos

Estructuras: listas (List<Character>), bucles y control de flujo

Clases sugeridas:

CifradoCesar → contiene los métodos encriptar() y desencriptar()

Main → gestiona la interacción con el usuario
