# Botones Emotivos

¡Vamos a crear botones emotivos! ◿🙂  ◸🙁

## {Paso 1}

En la sección ``||input:Input||`` arrastra el bloque  ``||input.on button A pressed||`` hasta el espacio de trabajo. 
Puedes eliminar el bloque ``||basic.on start||`` no lo necesitaremos.

```blocks
input.onButtonPressed(Button.A, function () { 
})
```

## {Paso 2}

En la sección ``||basic:Basic||`` arrastra el bloque  ``||basic.show icon||`` dentro del bloque ``||input.on button A pressed||`` .
Toca sobre el ícono del corazón para desplegar las opciones y elige un ícono de cara feliz 🙂. 

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.Happy)
})
```

## {Paso 3}

Arrastra otro bloque ``||input.on button A pressed||`` hasta el espacio de trabajo.
Puedes ponerlo en cualquier sitio. En este nuevo bloque, toca el menú ``||input.A ▼||``  para ver las opciones disponibles y elige el opción ``||input.B ▼||``.

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.Happy)
})
input.onButtonPressed(Button.B, function () {
})
```

## {Paso 4}

En la sección ``||basic:Basic||`` arrastra el bloque  ``||basic.show icon||`` dentro del bloque ``||input.on button B pressed||`` .
Toca sobre el ícono del corazón para desplegar las opciones y elige un ícono de cara triste 🙁. 

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showIcon(IconNames.Happy)
})
input.onButtonPressed(Button.B, function () {
basic.showIcon(IconNames.Sad)
})
```

## {Paso 5}

Vamos al simulador de @boardname@, presiona el botón A. ¿Viste una carita feliz 🙂? 
Ahora presiona el botón B  ¿Viste una carita triste 🙁? ¡Bien! Tenemos botones emotivos! 😍
¡Buen trabajo!

## {Step 4}

Haz clic en el botón ``|Download|`` y descarga el programa en tu @boardname@. 
Asegúrate de que esté conectada a la computadora.

¡Explora 🌍, Crea 🎨, Prueba nuevas animaciones 💡! ¡Diviértete 💻!

