# Piedra, Papel, Tijeras.

¡Vamos a crear el juego de Piedra ✊, Papel ✋ Tijeras ✌️!

## {Paso 1}

En la sección ``||input:Input||`` arrastra el bloque ``||input:on shake||`` hacia
el espacio de trabajo. Puedes eliminar el bloque ``||basic.on start||`` no lo necesitaremos.

```blocks
input.onGesture(Gesture.Shake, function () {
})
```

## {Paso 2}

En la sección ``||variables:Variables||``  crea una nueva variable llamada ``||variables:shoot||``.
Usaremos esta variable para saber que elección obtuvimos, si Piedra ✊, Papel ✋ o Tijeras ✌️. 

## {Paso 3}

En la sección ``||variables:Variables||`` arrastra el bloque ``||variables:set shoot to||``
dentro del bloque ``||input:on shake||``.

```blocks
input.onGesture(Gesture.Shake, function () {
    shoot = 0
})
```

## {Paso 4}

Hagamos que la variable **shoot** tome un valor aleatorio entre 0 y 2.

1. Desde la sección ``||math:Math||`` arrastra el bloque ``||math:pick random 0 to 10||`` y colocalo sobre el valor **0**
que esta en el bloque ``||variables:set shoot to ||``. 
2. Cambia el valor **10** por **2**. 

```blocks
input.onGesture(Gesture.Shake, function () {
    shoot = randint(0, 2)
})
```

## {Paso 5}

En la sección ``||logic:Logic||`` arrastra el bloque condicional 
``||logic:if true then||`` y colocalo debajo del bloque 
``||variables:set shoot to ||``. 

```blocks
let shoot = 0
input.onGesture(Gesture.Shake, function () {
    shoot = randint(0, 2)
    if (true) {
    	
    }
})
```

## {Paso 6}

1. Has clic en el símbolo ``||logic: ⊕ ||`` del bloque ``||logic:if true then||``, esto
añadirá un campo mas de instrucciones. 
2. Vuelve hacer clic en ``||logic: ⊕ ||``, necesitaremos en total tres campos de instrucciones.

```blocks
let shoot = 0
input.onGesture(Gesture.Shake, function () {
    shoot = randint(0, 2)
    if (true) {
    	
    } else if (false) {
    	
    } else {
    	
    }
})
```

## {Paso 7}

Comparemos el valor de la variable **shoot** con 0, 1 y 2 el cual representara a Piedra, Papel y Tijera respectivamente.

1. En la sección ``||logic:Logic||`` arrastra el bloque lógico ``||logic: 0 =▾ 0 ||`` y colocalo sobre el valor  ``||logic: true▾ ||`` 
2. Arrastra otro bloque lógico ``||logic: 0 =▾ 0 ||``  y colocalo en el espacio disponible en  ``||logic: else if        then||``

```blocks
let shoot = 0
input.onGesture(Gesture.Shake, function () {
    shoot = randint(0, 2)
    if (0 == 0) {
    	
    } else if (0 == 0) {
    	
    } else {
    	
    }
})
```

## {Paso 8}

1. En la sección ``||variables:Variables||``  arrastra la variable ``||variables:shoot||`` y colocala sobre el **0** que esta a la
izquierda en el bloque lógico  ``||logic: 0 =▾ 0 ||`` . 
2. Repite el paso anterior para el siguiente bloque  lógico ``||logic: 0 =▾ 0 ||`` y cambia el valor **0** de la derecha por **1**.

```blocks
let shoot = 0
input.onGesture(Gesture.Shake, function () {
    shoot = randint(0, 2)
    if (shoot == 0) {
    	
    } else if (shoot == 1) {
    	
    } else {
    	
    }
})
```

## {Paso 9}

En la sección ``||basic:Basic||`` arrastra el bloque ``||basic.show icon||`` y colocalo
dentro del bloque ``||logic:if true then||``. Realiza este paso 3 veces, uno por cada campo disponible.

```blocks
let shoot = 0
input.onGesture(Gesture.Shake, function () {
    shoot = randint(0, 2)
    if (shoot == 0) {
        basic.showIcon(IconNames.Heart)
    } else if (shoot == 1) {
        basic.showIcon(IconNames.Heart)
    } else {
        basic.showIcon(IconNames.Heart)
    }
})
```

## {Paso 10}

Para cada uno de los bloques ``||basic.show icon||`` toca sobre el ícono del corazón para desplegar las opciones 
y elige un ícono diamante 🔹 para representar a Piedra ✊, en el siguiente elige el ícono 🔲 para representar a Papel ✋, y por último
elige el icono ✂ para representar a Tijera ✌️.

```blocks
let shoot = 0
input.onGesture(Gesture.Shake, function () {
    shoot = randint(0, 2)
    if (shoot == 0) {
        basic.showIcon(IconNames.Diamond)
    } else if (shoot == 1) {
        basic.showIcon(IconNames.Square)
    } else {
        basic.showIcon(IconNames.Scissors)
    }
})
```

## ¡Vamos jugar!

1. Conecta tu Micro:Bit a la computadora.
2. Haz clic en ``|Download|`` para transferir el código al @boardname@.
3. Agítalo para jugar Piedra, Papel y Tijera.

¡Explora 🌍, Crea 🎨, Prueba nuevas animaciones 💡! ¡Diviértete 💻!
