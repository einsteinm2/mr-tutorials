# Corazón Palpitante

¡Vamos a crear una animación de un corazón palpitante! 💗

## {Paso 1}

Haz clic en la sección ``||basic:Basic||`` y arrastra el bloque  ``||basic.show icon||`` dentro del bloque ``||basic:forever||``. 

```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
})
```

## {Paso 2}

Añade una pausa arrastrando el bloque  ``||basic.pause (ms)||``  y colocalo debajo del primer  bloque.
```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
    basic.pause(100)
})
```

## {Paso 3}

Arrastra otro bloque ``||basic:show icon|`` y colocalo debajo de la pausa de tiempo. 
Abre el menu de iconos del bloque y escoge un corazón pequeño.

```blocks
basic.forever(function () {
    basic.showIcon(IconNames.Heart)
    basic.pause(100)
    basic.showIcon(IconNames.SmallHeart)
})

```

## {Paso 4}

¿Puedes dar un vistazo al simulador de @boardname@? ¡Tenemos un corazón palpitante!😍

## {Paso 5}

Haz clic en el botón ``|Download|`` y descarga el programa en tu @boardname@. 
Asegúrate de que esté conectada a la computadora.

¡Explora 🌍, Crea 🎨, Prueba nuevas animaciones 💡! ¡Diviértete 💻!
