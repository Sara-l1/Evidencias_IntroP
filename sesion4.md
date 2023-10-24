<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->

# Actividad: Crear una tabla HTML con información sobre productos.

Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- ódigo
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

*Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.*

# DESARROLLO:

```html 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <table border="1" cellpadding="5" cellspacing="10">
        <thead style="background-color: antiquewhite;">
            <tr> 
                <th>Código</th>
                <th>Nombre</th>
                <th>Descripción</th>
                <th>Precio</th>
                <th>Stock</th>
                <th>Fecha de creación</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>0001</td>
                <td>Pestañina Maybelline Sky High Black</td>
                <td>¡Efecto EXTRALARGO en tus pestañas! La Pestañina Maybelline Sky High cuenta con una fórmula de color
                    negro intenso y profundo que resalta tu mirada. Esta pestañina separa una a una tus pestañas
                    haciéndolas lucir más largas y voluminosas.</td>
                <td>$54.900 COP</td>
                <td>10</td>
                <td>01-01-2023</td>
            </tr>
            <tr>
                <td rowspan="2">0002</td>
                <td rowspan="2">Labial Maybelline Superstay Vinyl Ink</td>
                <td>¡Nuevo Labial líquido Brillante Vinyl Ink!. Este labial líquido de larga duración te brinda un color
                    de vinilo sin movimiento y hasta 16 horas de uso, gracias a nuestra fórmula de bloqueo de color que
                    desafía las manchas y la transferencia; simplemente agita y coloca</td>
                <td>$55.900 COP</td>
                <td>20</td>
                <td>06-05-2023</td>
            </tr>
            <tr>
                <td colspan="1">Disponibles en los siguientes colores: rojo, morado y café.</td>
                <td>70</td>
            </tr>

            <tr>
                <td rowspan="2">0003</td>
                <td rowspan="2">Plumón Para Cejas Physicians Formula 0.5ml</td>
                <td> ¡Efecto microblading en minutos! El Plumón Para Cejas Physician Formula brinda un color ultra
                    preciso, resistente a la transpiración que no se transfiere, ni mancha. demás, este lápiz para cejas
                    acondiciona y humecta las cejas, dejándolas suaves y de aspecto natural mientras perfila y rellena
                    los espacios vacíos. Este maquillaje es indicado para piel y ojos sensibles gracias a su fórmula
                    hipoalergénica cuida e hidrata la piel.</td>

                <td>$63.900 COP</td>
                <td>15</td>
                <td>03-02-2023</td>
            </tr>

            <tr>
                <td colspan="1">Disponibles en los tonos: Negros, marrones y cafeces claros.</td>
                <td>85</td>
            </tr>

            <tr>
                <td>0004</td>
                <td>Paleta De Sombras Bys 12 Tonos Nude 4</td>
                <td>BYS Nude 4 Eyeshadow Palette presenta una gama de 12 sombras de ojos mate y metálicas de alta
                    pigmentación. Este maquillaje para ojos maneja una gama de colores cálidos y neutros. La paleta Nude
                    de 12 piezas cuenta con un empaque en lata con relieve de mariposa, un espejo y 2 aplicadores de
                    doble extremo.</td>
                <td>$78.900 COP</td>
                <td>20</td>
                <td>01-12-2022</td>
            </tr>

            <tr>
                <td>0005</td>
                <td>Caja De Maquillaje Salon Expert Mini Black</td>
                <td>¡Con Caja De Maquillaje Salon Expert Mini Black Organiza y protege tus cosméticos y accesorios
                    favoritos y llévalos a donde quieras! Este maletín de viaje de belleza es resistente y fácil de
                    limpiar hecho de forro aislante de nailon y espuma negra</td>
                <td>$219.900 COP</td>
                <td>15</td>
                <td>10-10-2022</td>
            </tr>

            <tr>
                <td rowspan="2">0006</td>
                <td rowspan="2">Base Liquida Bys Full Coverage Ácido Hialurónico</td>
                <td>¡Logra piel impecable con la Base Liquida Bys Full Coverage Ácido Hialurónico! Su fórmula de
                    cobertura total perfecciona la piel con un acabado mate natural. Esta base liquida contiene vitamina
                    E, aloe vera y agua de coco, ingredientes que ayudan a nutrir e hidratar tu piel evitando que tu
                    cutis se sienta pesado, mientras el ácido hialurónico previene y disminuye el envejecimiento
                    prematuro de la piel.</td>
                <td>$56.900 COP</td>
                <td>30</td>
                <td>05-02-2023</td>
            </tr>

            <tr>
                <td colspan="1">Disponibles en los tonos: 001, 002, 003 y 004.</td>
                <td>85</td>
            </tr>

            <tr>
                <td>0007</td>
                <td>Bronzer The Balm Bahama Mama 7.08g</td>
                <td>La fórmula mate del Bronzer The Balm Bahama Mama se desliza suavemente por tu piel y se difumina
                    totalmente, para un maquillaje libre de lineas y marcas. Este Bronzer mate crea aspecto bronceado
                    sin matices naranjas para un maquillaje fresco y suave. ¡Ideal para usar en la playa! Funciona como
                    sombra de ojos, contorno y para rellenar las cejas. Ad</td>
                <td>$99.900 COP</td>
                <td>8</td>
                <td>11-06-2023</td>
            </tr>

            <tr>
                <td>0008</td>
                <td>Pestañina Nee Deep Extension Black 9 Ml</td>
                <td>¡Dile adiós a las extensiones de pestañas! con la Pestaniña Nee Extension Deep luce unas pestañas
                    más largas, con volumen y curvas. Esta pestañina lavable cuenta con un cepillo en silicona que curva
                    tus pestañas, incluso las más pequeñas. Su formula ligera deja tus pestañas más grandes, naturales,
                    elásticas y sin grumos. </td>
                <td>$94.900 COP</td>
                <td>20</td>
                <td>20-07-2022</td>
            </tr>

            <tr>
                <td rowspan="2">0009</td>
                <td rowspan="2">Lápiz Delineador De Ojos Divva</td>
                <td>l lápiz Divva cuenta con una fórmula enriquecida con vitamina E y C, que cuida tus pestañas. Este
                    delineador de alta duración resistente a la transpiración y no deja manchas. Este lápiz de ojos
                    posee una textura cremosa que permite una aplicación precisa y facilita el difuminado a ras de las
                    pestañas. </td>
                <td>$19.900 COP</td>
                <td>18</td>
                <td>10-02-2023</td>
            </tr>

            <tr>
                <td colspan="1">Disponibles en los colores: Azul, blanco, café, rojo.</td>
                <td>40</td>
            </tr>


            <tr>
                <td>0010</td>
                <td>Iluminador Palladio I'm Glowing</td>
                <td>Este iluminador en barra refleja la luz y resalta los puntos altos del rostro permitiendo que este
                    se vea más perfilado con un toque de luz. Este highlight cuenta con una textura ligera, que se
                    compacta perfectamente con tu piel, difumínalo en el día, para un look sutil y luce un color intenso
                    y concentrado en la noche. Este iluminador también puede ser usado en los labios, gracias a su
                    fórmula hidratante enriquecida con agentes botánicos, libre de parabenos, para cuidar tu piel. </td>
                <td>$62.900 COP</td>
                <td>10</td>
                <td>03-04-2023</td>
            </tr>

        </tbody>
    </table>

</body>

</html>
```




