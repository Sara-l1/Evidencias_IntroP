<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->

# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame

Utiliza encabezados para títulos en cada elemento (<h1>...<h6>).
Crea una descripción para cada elemento utilizando párrafos (<p>).

# DESARROLLO

### Link para descargar el archivo completo

https://drive.google.com/drive/folders/17Sx0IoA7AWy8JvoBmCv1iqSR7AFx3J8s?usp=drive_link

```html  
<!DOCTYPE html>
<html>

<head>
    <title>Tipos de perros en el mundo</title>
    <link rel="stylesheet" href="style.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url(https://img.freepik.com/vector-premium/patron-repeticion-pata-huella-gato-perro-costuras-fondo-azul_604817-259.jpg);
        }

        header {
            background-color: #3977db;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: rgb(4, 4, 184);
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>CLASES DE PERROS EN EL MUNDO 🌎🐶</h1>
    </header>

    <section>
        <h1 style="color: #21059c;"> <strong>CLASES DE PERROS MÁS EXTRAÑOS DEL MUNDO: </strong> </h1>

        <h2> <i>1. Crestado Chino</i></h2>
        <p style="font-size: 21px;"> El crestado chino es una raza feliz, amigable y de buen carácter que disfruta en
            compañía de las personas y
            no le gusta quedarse solo durante mucho tiempo. Es de naturaleza juguetona y nunca está más feliz que
            sentado en el regazo de su dueño. <br><strong>Se caracteriza por ser uno de los perros más raros por su
                apariencia física,</strong> existen dos variedades de esta raza, una con un pelaje suave y otra sin
            pelo.
            <a href="https://www.purina.es/encuentra-mascota/razas-de-perro/crestado-chino" target="_blank"> <br>
                <br>Conoce más de sus caracteristicas <strong>aquí</strong></a>
        </p>

        <div class="Content">

            <img class="img" src="Imagenes/CrestadoC1.jpg" alt="400" height="200">

            <img class="img" src="Imagenes/CrestadoC2.webp" alt="400" height="200">

            <img class="img" src="Imagenes/CrestadoC3.jpg" alt="400" height="200">

        </div>




        <h2> <i>2. Puli Hungaro</i></h2>
        <P style="font-size: 21px;"> A pesar de estar considerada como una raza rara, es fácil de reconocer por su
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

            <img class="img" src="Imagenes/PuliH2.jpg" alt="400" height="200">

            <img class="img" src="Imagenes/PuliH3.webp" alt="400" height="200">

        </div>


        <h2> <i>3. Tigre Andino de Doble Nariz</i></h2>
        <P style="font-size: 21px;"> Este perro se desarrolló para ayudar a rastrear a los jaguares, a menudo
            denominados tigres por los
            lugareños. Aunque algunos no la presentan, la mayoría de estos perros tienen una <strong>nariz
                partida</strong> que se cree
            que aumenta su sentido del olfato. Hasta hace poco, esta raza era considerada por muchos como miembro de la
            criptología.
            <a href="https://petyzoo.com/perro-tigre-andino-dos-narices/" target="_blank"><strong>más</strong></a>
        </P>

        <div class="Content">

            <img class="img" src="Imagenes/TAndino1.jpg" alt="400" height="200">

            <img class="img" src="Imagenes/TAndino2.jpg" alt="400" height="200">

            <img class="img" src="Imagenes/TAndino3.webp" alt="400" height="200">

        </div>



        <h2> <i>4. Mastín Napolitano</i></h2>
        <P style="font-size: 21px;"> <Strong>Perro de gran tamaño pero cariñoso,</Strong> Adora a su familia y desconfía
            de los extraños. Esto
            les convierte en
            grandes perros guardianes, ya que son muy protectores y no dudarán en alejar a cualquier visitante no
            deseado. Estos perros no requieren mucho mantenimiento. <br>Es uno de los perros más grandes del mundo,
            requiere
            un dueño experimentado y es tranquilo e inteligente. Debe ser socializado desde muy pequeño y sin un
            entrenamiento adecuado, pueden volverse agresivos o destructivos,No son perros adecuados para dueños
            primerizos, ya que es necesario tener experiencia con perros dominantes.
            <a href="https://www.purina.es/encuentra-mascota/razas-de-perro/mastin-napolitano"
                target="_blank"><strong>más</strong></a>
        </P>

        <div class="Content">

            <img class="img" src="Imagenes/Mastin1.jpg" alt="400" height="200">

            <img class="img" src="Imagenes/Mastin2.jpg" alt="400" height="200">

            <img class="img" src="Imagenes/Mastin3.jpg" alt="400" height="200">

        </div>

    </section>

    <section>
        <h2><i>Perro compañero de gimnasio</i></h2>
        <p style="font-size: 23px;"> Con una actividad regular los animales mejoran el desarrollo musculoesquelético,
            evitan la obesidad y
            reducen
            patologías asociadas al sobrepeso como diabetes. <br> En definitiva, el ejercicio hace que se consigan
            mascotas
            más sanas y más felices.</p>

        <div class="Videos">

            <video src="Videos/Gym.mp4" autoplay loop controls width="400" height="400"></video>
            <video src="Videos/gym2.mp4" autoplay loop controls width="400" height="400"></video>

        </div> <br><br>



        <h2><i>El perro y la música</i></h2>
        <p style="font-size: 23px;"> A los perros les gusta la música, pero el <strong>tipo de música marca la
                diferencia,</strong> prefieren los ritmos más lentos, patrones simples y las frecuencias más bajas.
            <br>La música se puede usar como
            herramienta para ayudar a los perros que sufren problemas de ansiedad (incluyendo el <strong>estrés por
                separación</strong>)
            Si tienes un perro hiperactivo también puedes ponerle música
            para mantenerlo tranquilo.
        </p>

        <div class="Videos">

            <video src="Videos/Music.mp4" autoplay loop controls width="400" height="400"></video>
            <video src="Videos/Music2.mp4" autoplay loop controls width="400" height="400"></video>

        </div>

    </section>

    <section>
        <h2>Sonidos para que tu perro se sienta más tranquilo: </h2>

        <p style="font-size: 21px;">La música para perros es una forma de estimulación auditiva que puede ayudar a
            relajar y calmar a tu mascota
            en situaciones difíciles o estresantes. Al igual que la música para las personas, hay una amplia variedad de
            opciones disponibles, desde música clásica hasta sonidos relajantes de la naturaleza.</p>

        <ul>

            <li><audio src="Audios/R1.mp3" controls></audio></li> <br>

            <li><audio src="Audios/R2.mp3" controls></audio></li> <br>

            <li><audio src="Audios/R3.mp3" controls></audio></li> <br>

            <li><audio src="Audios/R4.mp3" controls></audio></li> <br>

        </ul>

    </section>

    <section>
        <h3 style="color: #2908be;"><i>CONOCE COMO HACER DORMIR TU PERRO: </i></h3>

        <iframe width="560" height="315" src="https://www.youtube.com/embed/vXl4M5qLTuM?si=lD6WGsAYKhd19K8r?controls=0"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe> <br>



        <h3 style="color: #2908be;"><i>JUGETES DE VERANO PARA TU PERRO: </i></h3>

        <iframe width="560" height="315" src="https://www.youtube.com/embed/JAKaUkxaCHg?si=JtNizpQKT5m0v6Tw"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>


        <h3 style="color: #2908be;"><i>CURIOSIDADES SOBRE LOS PERROS: </i></h3>

        <iframe width="560" height="315" src="https://www.youtube.com/embed/ALTmbR22LrU?si=Ui34WYsFJkoP2wkB"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>


        <h3 style="color: #2908be;"><i>RAZAS DE PERROS: </i></h3>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/8Uot6Ic3mHA?si=HuQsa7B_NkXW-9zm"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>


    </section>

    <footer>
        Sara Lopera Pérez
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>

```

