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

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Document</title>
</head>Mi primer sitio WEB</head>
<body>
    <header>
        <h1>Mi sitio WEB - COSMETICOS SLP</h1>
    </header>

    <Nav>
        <a href="about.html">Acerca</a> 
        <br>
        <a href="contact.html">Contacto</a>
    </Nav>

    <main>
        <p>Bienvenidos a mi primer sitio Web</p>
        <P>Aqui encontraras paginas e información</P>
    </main>

    <footer>
        <strong><p>Sara Lopera</p></strong>
        <strong><p>loperasara00@gmail.com</p></strong>
        <strong><p>CESDE</p></strong>
    </footer>

</body>

</html>
```



## contac.html
```html
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
        <br>
        <a href="about.html">Acerca</a>
    </nav>

    <main>
        
       <form>
        <label for="Nombre">Nombre</label>
        <input type="text" id="nombre"><br>

        <label for="Email">Email</label>
        <input type="email" id="email"><br>

        <label for="Mensaje">Mensaje (Que producto te interesa)</label> <br>
        <textarea id="mensaje"></textarea><br>

        <input type="submit">
       </form>

       <aside>
        <h3>Ubicación:</h3>
        <h4>Calle 53 a #55 - 73 Rosalpi</h4>
       </aside>

    </main>

    <footer>
        <strong><p>Sara Lopera</p></strong>
        <strong><p>Loperasara00@gmail.com</p></strong>
        <strong><p>CESDE</p></strong>
    </footer>
    
</body>

</html>
```

## about.html
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<title>Sobre Nosotros</title>
</head>

<body>

    <header>
        <h1>Sobre nosotros</h1>
    </header>

    <nav>
        <a href="index.html">Inicio</a>
        <br>
        <a href="contact.html">Contacto</a>
    </nav>

    <section>
        <h2>La Historia de COSMETICOS SLP</h2>
        <p>Proyecto innovador, tus mejores amigos para tu piel y lucir bella los encontraras aquí <br> Realizaremos de
            esta pagina lo mejor para que puedan disfrutar de ella</p>

        <article>
            <h3>Misión y visión</h3>

            <h4>Misión:</h4>
            <p>Satisfacer la necesidad de sentirse y verse bien. Estar a la vanguardia con las nuevas tendencias
                en belleza, satisfaciendo a nuestros clientes con productos innovadores a precios competitivos y que
                nuestro cliente encuentre todo lo que busca en belleza en un solo lugar </p>

            <h4>Visión</h4>
            <p>Estar a la vanguardia con las nuevas tendencias en belleza, satisfaciendo a nuestros clientes con
                productos innovadores a precios competitivos y que nuestro cliente encuentre todo lo que busca en
                belleza en un solo lugar</p>
        </article>

    </section>

    <footer>
        <strong>
            <p>Sara Lopera Pérez</p>
        </strong>
        <strong>
            <p>2023 - CESDE</p>
        </strong>
    </footer>

</body>

</html>
```