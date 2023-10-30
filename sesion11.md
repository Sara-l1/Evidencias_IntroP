<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


<!-- Su documentación aquí -->

# Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css

* Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11


### DESARROLLO:

>page github
[Link Sesion 11](https://sara-l1.github.io/Actividad11IntroP/) 

~~~html
<!DOCTYPE html>
<html>

<head>
    <title>Tipos de perros en el mundo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>CLASES DE PERROS EN EL MUNDO 🌎🐶</h1>
    </header>
    <section>
        
        <h1> <strong>CLASES DE PERROS MÁS EXTRAÑOS DEL MUNDO: </strong> </h1>
<br>
        <h2> <i>1. Crestado Chino</i></h2>
        <p> El crestado chino es una raza feliz, amigable y de buen carácter que disfruta en
            compañía de las personas y
            no le gusta quedarse solo durante mucho tiempo. Es de naturaleza juguetona y nunca está más feliz que
            sentado en el regazo de su dueño. <br><strong>Se caracteriza por ser uno de los perros más raros por su
                apariencia física,</strong> existen dos variedades de esta raza, una con un pelaje suave y otra sin
            pelo.
            <a href="https://www.purina.es/encuentra-mascota/razas-de-perro/crestado-chino" target="_blank"> <br>
                <br>Conoce más de sus caracteristicas <strong>aquí</strong></a>
        </p>
<br>
<br>
<br>
        <div class="Content">

            <img class="img" src="Imagenes/CrestadoC1.jpg" alt="400" height="200">

        </div>

        <h2> <i>2. Puli Hungaro</i></h2>
        <P> A pesar de estar considerada como una raza rara, es fácil de reconocer por su
            curioso pelaje, repleto de
            <strong>largos rizos similares a unas rastas</strong> que llegan hasta el suelo. Normalmente suelen ser de
            color <strong>negro, negro
                óxido, blando o de varios tonos como el albaricoque o gris.</strong> <br> Debajo del pelaje se esconde
            un cuerpo <strong><i>robusto y musculoso.</i></strong> Además, destacan por su personalidad, ya que
            suelen crear un vínculo muy especial con los miembros de su familia.
            <a href="https://www.purina.es/encuentra-mascota/razas-de-perro/puli-hungaro" target="_blank"> <br>
                <br>Conoce más
                <strong>aquí</strong></a>
        </P>

        <div class="Content">

            <img class="img" src="Imagenes/PuliH1.jpg" alt="400" height="200">
        </div>


        <h2> <i>3. Tigre Andino de Doble Nariz</i></h2>
        <P> Este perro se desarrolló para ayudar a rastrear a los jaguares, a menudo
            denominados tigres por los
            lugareños. Aunque algunos no la presentan, la mayoría de estos perros tienen una <strong>nariz
                partida</strong> que se cree
            que aumenta su sentido del olfato. Hasta hace poco, esta raza era considerada por muchos como miembro de la
            criptología.
            <a href="https://petyzoo.com/perro-tigre-andino-dos-narices/" target="_blank"><strong>más</strong></a>
        </P>

        <div class="Content">

            <img class="img" src="Imagenes/TAndino1.jpg" alt="400" height="200">

        </div>
        <div>
            <ul>
                <li>PERRO 1</li>
                <li>PERRO 2</li>
                <li>PERRO 3</li>
            </ul>
        </div>
        
~~~

~~~css
body {
    font-family: Arial, sans-serif;
    width: 100%;
    height: 100vh;
    margin: 0;
    padding: 0;
    color: #000;
    background-color: #fff;
    font-family: sans-serif;
    font-size: 16px;
    border: 1px solid black;
    background-image: url(https://img.freepik.com/vector-premium/patron-repeticion-pata-huella-gato-perro-costuras-fondo-azul_604817-259.jpg);
}
header {
    background-color: #3977db;
    color: white;
    padding: 20px;
    text-align: center;
}
section {
    border: 80px solid #ddd;
    padding: 170px;
    margin-bottom: 3000px;
}
h1 {
    width: 50%;
    height: 100px;
    margin: 30px auto;
    padding: 20px;
    color: #fff;
    background-color: #000;
    font-family: 'Times New Roman', serif;
    font-size: 24px;
    font-weight: bold;
    text-align: center;
    border-width: 20x;
    border-style: dashed;
    border-color: red;
}
h2 {
    color: rgb(4, 4, 184);
}
footer {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
    margin: 400px;
    margin-top: 4000px;
}
p {
    float: left;
    width: 50%;
    height: 400px;
    margin: 80px;
    padding: 100px;
    background-image: url(image.jpg);
    background-repeat: repeat-y;
    background-position: center;
    font-style: italic;
    font-variant: small-caps;
    text-align: justify;
    border-radius: 190px;
    background-color: white;
}
a {
    border: 1000px coral;
    margin: 200px;
    color: blue;
}
Content {
    border: 100px solid #ddd;
    padding: 60000px;
    margin: 400px;
    color: #21059c;
}
a:link {
    background-color: red;
}
a:active {
    background-color: green;
}
p:hover {
    background-color: gray;
}
button {
    cursor: pointer;
    background-color: blue;
}
button:active {
    background-color: red;
}
button {
    cursor: pointer;
    background-color: blue;
}
button:disabled {
    cursor: not-allowed;
    background-color: gray;
}
a {
    color: blue;
}
a:link {
    background-color: red;
}
a:active {
    background-color: green;
}
ul {
    list-style-type: none;
    background-color: white;
}
li:nth-of-type(1):hover {
    background-color: red;
}
li:nth-of-type(2):hover {
    background-color: green;
}
li:nth-of-type(3):hover {
    background-color: blue;
}
p::first-line {
    font-weight: bold;
    color: red;
}
p::first-letter {
    font-weight: bold;
    color: crimson;
    font-size: 60px;
}
p {
    font-size: 16px;
    line-height: 2;
}
p::after {
    content: "→";
    font-size: 20px;
    position: absolute;
    bottom: 0;
    right: 0;
}
body {
    color: black;
    background-color: white;
}
::selection {
    background-color: red;
}
h1::before {
    content: url("https://icons.iconarchive.com/icons/gartoon-team/gartoon-action/48/dialog-apply-icon.png");
}
~~~
