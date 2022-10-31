# Sistema de ventas

Se desea realizar una BD que permita apoyar la gestión de un sistema de ventas. La empresa necesita llevar un control de proveedores, clientes, productos y ventas.

- Un proveedor tiene un identificador, nombre, dirección, teléfono y página web.
- Un cliente también tiene identificador, nombre, dirección, pero puede tener varios teléfonos de contacto. La dirección se entiende por calle, número, provincia y ciudad.
- Un producto tiene un identificador único, nombre, precio actual, stock y nombre del proveedor. Además se organizan en categorías, y cada producto va sólo en una categoría. Una categoría tiene id, nombre y descripción.
- Por razones de contabilidad, se debe registrar la información de cada venta con un id, fecha, cliente, descuento y monto final.
- Además se debe guardar el precio al momento de la venta, la cantidad vendida y el monto total por el producto.

## Paso 1
Proponer las frases que describan el problema y generar las entidades y relaciones.

- Cada producto pertenece sólo a una categoría.
- El proveedor provee el producto.
- Se detalla la venta de cada producto.
- El cliente hace una compra.

![<>](img/Captura%20de%20pantalla%202022-10-29%20134601.png)

## Paso 2
Montar correctamente todas las entidades y sus relaciones y colocar los atributos a cada entidad e interrelación.

![<>](img/Captura%20de%20pantalla%202022-10-29%20134643.png)