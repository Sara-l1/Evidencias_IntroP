<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->

## Actividad: Aplicando estilos con selectores CSS

El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

### Pasos:

### Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado <header>
- Tres párrafos <p>
- Una imagen <img>
- Un pie de página <footer>

### Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados <h1>
- Color azul a los párrafos <p>
- Borde grueso negro a la imagen <img>

### Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"

### Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"

### Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un <div>
- Centrar el contenido de la sección <section>

## Solución
### INDEX.html

~~~html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Actividad8</title>
    <link rel="stylesheet" href="stylo.css">
</head>

<body>

    <header>
        <h1 style="text-transform: capitalize; text-align: center; background-color: azure;">Peliculas iconicas de los
            2000</h1>
    </header>
    <section>
        <h3 class="destacado">American Psycho</h3>
        <p>Una experiencia inolvidable, ¿verdad? La directora Mary Harron adaptó la novela homónima de Bret Easton Ellis
            sobre un joven, atractivo y exitoso ejecutivo de Wall Street con un oscuro secreto: sus instintos asesino.
            Fue además el primer gran personaje de Christian Bale.</p><br>

        <h3 class="destacado">Scary Movie</h3>
        <p>Hablando de slashers y sagas divertidas, 'Scary Movie'. Si no te convence verla en esta lista, recuerda las
            carcajadas que te echaste.</p><br>
        
        <h3 class="destacado">Memento</h3>
        <p>Antes de ser mundialmente aclamado por su revisión de 'Batman', Christopher Nolan llamó la atención de los
            críticos con 'Memento', thriller sobre un hombre con amnesia que se tatúa lo que recuerda para investigar el
            asesinato de su esposa.</p><br>
<h3 class="destacado">UN POCO DEL 200</h3>
        <img src="imagenes/2000.png" alt="300" height="300"> 
    </section>

    <footer>
        <p class="grande">Sara Lopera Perez</p>
        <p id="principal">Peliculas Iconicas de los 2000</p>
        <p id="sombras">2023</p>
    </footer>

</body>

</html>

~~~

### stylo.css

~~~css

h1 {
    color: red;
}

p {
    color: blue;
}

img {
    border: 10px solid black;
}

/*seleccionadores de clase*/

.destacado {
    color: green;
}

.grande {
    font-size: large;
}

/*seleccionadores de ID*/

#principal {
    color: yellow;
}

#sombras {
    color: yellow;
    font-weight: 900;
    text-shadow: 3px 3px 0px green, 5px 5px 0px black;
}

/*seleccionadores descendientes*/
div p {
    color: gray;
    text-align: center;
}
section h3, p {
    text-align: center;
}


~~~

