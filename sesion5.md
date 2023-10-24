<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->

# Actividad: Diseñar un formulario de pedido de un producto
### Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

### Instrucciones:

1. Crear un nuevo documento HTML.
2. Crear un formulario con los siguientes campos:
- Nombre del producto
- Cantidad
- Precio unitario
- Precio total
- Dirección de envío
- Información de contacto (nombre, correo electrónico, número de teléfono)
3. Agregar los siguientes campos relacionados al formulario:
* Método de pago
* Fecha de entrega
* Comentarios
4. Utilizar las etiquetas HTML apropiados para cada campo.

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
    <form action="" method="" autocomplete="off">
    
    <div>
        <h1><i><strong>THE MAKEUP HOUSE SLP</strong></i></h1>
        <h3>Añade tu producto</h3>
    </div>

    <div>
        <label for="producto"></label>
        <select name="producto" required aria-readonly="false">
            <option value="">Seleccione producto</option>
            <option value="Pestañina Maybelline">Pestañina Maybelline</option>
            <option value="Labial Maybelline">Labial Maybelline</option>
            <option value="Plumón Para Cejas Physicians">Plumón Para Cejas Physicians</option>
            <option value="Paleta De Sombras Bys 12 Tonos">Paleta De Sombras Bys 12 Tonos </option>
        </select>
        <br>
        <br>
        <div>
            <label for="Cantidad del producto:">Cantidad del producto:</label> <br>
            <input type="number" name="idcantidaddelprodcto" id="Cantidad del producto:" class="input" min="0" max="100">
        </div>

        <div>

        <label for="Precio unitario">Precio unitario:</label> <br>
        <input type="number" name="idpreciounitario" id="Precio unitario" class="input" min="0" max="1000000"> 

        </div>

        <div>

            <label for="Precio total">Precio total:</label> <br>
            <input type="number" name="idpreciototal" id="Precio total" class="input" min="0" max="1000000"> <br>
            <br>
            </div>

              <h3><I>Datos personales: </I></h3>
              <div>
                <label for="Nombre completo:">Nombre completo:</label> <br>
                <input type="text" name="idnombrecompleto:" id="Nombre completo:" class="input" required> 
        
                </div>

            <div>
                <label for="Dirección de envio:">Dirección de envio:</label> <br>
                <input type="text" name="iddirecciondeenvio:" id="Dirección de envio:" class="input" required> 
        
                </div>
           
            <div>
                    <label for="Correo Electronico:">Correo Electronico:</label> <br>
                    <input type="email" name="idcorreoelectronico:" id="Correo Electronico:" class="input" required> 
            
             </div>
    
             <div>
                <label for="Número de teléfono:">Número de teléfono:</label> <br>
                <input type="number" name="idnumerodetelefono:" id="Número de teléfono:" class="input" required> <br>
                <br>
                </div>


            <div>
                <label for="Metodo de pago:">Metodo de pago:</label> <br>
                <input type="radio" name="Metodo de pago:">Pago Contraentrega <br>
                <input type="radio" name="Metodo de pago:">Pago Tarjeta Credito/Debito <br>
                <input type="radio" name="Metodo de pago:">Pago Transferencia Bancaria <br>
              </div>
              <br>

              <div>
                <label for="Fecha estipulada de entrega:">Fecha estipulada de entrega:</label> <br>
                <input type="date" name="idfechaestipuladadeentrega:" id="Fecha estipulada de entrega:" class="input" required> <br>
                <br>
                </div>
            
                <div>
                    <label for="Comentario - Mensaje:">Comentario - Mensaje:</label> <br>
                    <textarea name="Comentario - Mensaje:" id="Comentario - Mensaje:" placeholder="Ingrese su comentario aquí:" cols="30" rows="10" required></textarea>




                </div>


     <input type="submit">
    </div>



    </form>
</body>
</html>
```




