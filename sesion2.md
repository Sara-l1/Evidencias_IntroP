<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->
# Actividad: Creando mi primer sitio web
Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

Index o página de inicio
Acerca
Contacto

# DESARROLLO

## index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Document</title>
</head>Mi primer sitio WEB</head>
<body>
    <header>
        <h1>Mi sitio WEB</h1>
    </header>

    <Nav>
        <a href="about.html">Acerca</a>
        <a href="contact.html">Contacto</a>
    </Nav>

    <main>
        <p>Bienvenidos a mi sitio sobre empresas XYZ</p>
        <P>Aqui encontraran información sobre nuestros servicios y productos</P>
    </main>

    <footer>
        <p>Copyright 2023 - Juan Perez</p>
        <p>juanperez@email.com</p>
    </footer>

</body>

</html>

## contac.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<title>Contacto</title>
</head>

<body>
    <header>
        <h1>Contacto</h1>
    </header>

    <nav>
        <a href="index.html">Inicio</a>
        <a href="about.html">Acerca</a>
    </nav>

    <main>
        
       <form>
        <label for="nombre">Nombre</label>
        <input type="text" id="nombre"><br>

        <label for="email">Email</label>
        <input type="email" id="email"><br>

        <label for="mensaje">Mensaje</label>
        <textarea id="mensaje"></textarea><br>

        <input type="submit"> value="Enviar"
       </form>

       <aside>
        <h3>Ubicación</h3>
        <h3>Calle falsa 123</h3>
       </aside>

    </main>

    <footer>
        <p>Copyright 2023 - juan Perez</p>
    </footer>
    
</body>

</html>

## about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head> 
<title>Sobre nosotros</title>
</head>

<body>

    <header>
        <h1>Sobre nosotros</h1>
    </header>

    <nav>
       <a href="index.html">Inicio</a> 
       <a href="contact.html">Contacto</a>
    </nav>

    <section>
        <h2>Historia</h2>
        <p>Fundada en 2010...</p>

        <article>
            <h3>Misión y visión</h3>
            <p>Nuestra misión es...</p>
        </article>

    </section>

    <footer>
        <p>Copyright 2023 - Juan Perez</p>
    </footer>

</body>

</html>