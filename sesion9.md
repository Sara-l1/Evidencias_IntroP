<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->

# Actividad: Propiedades de espaciado y unidades de medida
### Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, agrega el siguiente código:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```

- En el archivo CSS, agrega el siguiente código:

```css
.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}
```

- Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.

- Practicar el uso de las propiedades de espaciado.

* Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.

~~~css

.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}

~~~

* Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.

~~~css

.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

~~~

* Border: Agrega un borde de 5 píxeles de color rojo.

~~~css

.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

~~~

* Border-radius: Agrega un radio de esquina de 10 píxeles.

~~~css

.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

~~~

* Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.

~~~css

.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}

~~~


### Preguntas:
1. ¿Qué es la propiedad margin?
2. ¿Qué es la propiedad padding?
3. ¿Qué es la propiedad border?
4. ¿Qué es la propiedad border-radius?
5. ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?


### Solución

1. La propiedad “margin” en CSS se utiliza para establecer los márgenes alrededor de un elemento. Los márgenes son el espacio vacío alrededor de un elemento, y se utilizan para separarlo de otros elementos en la página.

La propiedad “margin” se puede establecer en un solo valor (para establecer los márgenes en todas las direcciones), o en valores múltiples (para establecer los márgenes en cada dirección individualmente).

Los valores válidos para la propiedad “margin” son unidades de longitud (como px, em, etc.), porcentajes, o la palabra clave “auto”.

2. La propiedad “padding” en CSS es utilizada para establecer un espacio adicional alrededor del contenido de un elemento HTML. El padding se utiliza para crear distancia entre el borde del elemento y su contenido.

Puedes utilizar unidades absolutas como pixels o unidades relativas como porcentajes para establecer el tamaño del padding.

También es posible establecer el padding para cada lado individualmente (arriba, abajo, derecha, izquierda) utilizando las propiedades padding-top, padding-right, padding-bottom, y padding-left respectivamente.

3. La propiedad “border” de CSS se utiliza para establecer los bordes de un elemento HTML. Puedes especificar los valores de la propiedad “border” de varias maneras:

Utilizando la sintaxis abreviada: border: tamaño estilo color;
Utilizando las propiedades individuales: border-width, border-style y border-color.
La sintaxis abreviada de la propiedad border permite especificar todos los valores en una sola línea, en el orden: tamaño, estilo, color. 

4. La propiedad CSS border-radius permite a los desarrolladores Web definir qué tan redondeadas serán las esquinas. La redondez de cada esquina está definida usando uno o dos valores para el radio que define su forma dependiendo si es un círculo o una elipse.

5. Las unidades de medida en CSS de tipo absoluto hacen referencia a las unidades que no cambian, esas que en todos lo contextos son iguales. En CSS, existen siete unidades de medida absolutas, te las presentamos a continuación:

- **in:** hace referencia a las pulgadas, que son iguales a 2.54cm.
- **cm:** se refiere a los centímetros.
- **mm:** hace referencia a los milímetros.
- **q:** se refiere a un cuarto de la unidad mm. 1q=0.248mm.
- **pt:** un punto es igual a 1/72 de una pulgada o 0.35mm.
- **pc:** una pica es igual a 12 puntos, o sea 4.23mm.
- **px:** esta etiqueta se refiere a los píxeles que, aunque son absolutos (0.26mm), también  son relativos a la densidad de la pantalla.