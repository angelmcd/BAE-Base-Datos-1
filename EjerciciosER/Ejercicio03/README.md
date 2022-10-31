# Sistema de Artículos
Se desea crear una base de datos para una pequeña empresa debe contener información acerca de clientes, artículos y pedidos. Hasta el momento se registran los siguientes datos en documentos varios:

- Para cada cliente: Número de cliente (único), Direcciones de envío (varias por cliente), Saldo, Límite de crédito (depende del cliente, pero en ningún caso debe superar los 3.000.000 €), Descuento.
- Para cada artículo: Número de artículo (único), Fábricas que lo distribuyen, Existencias de ese artículo en cada fábrica, Descripción del artículo.
- Para cada pedido: Cada pedido tiene una cabecera y el cuerpo del pedido. La cabecera está formada por el número de cliente, dirección de envío y fecha del pedido. El cuerpo del pedido son varias líneas, en cada línea se especifican el número del artículo pedido y la cantidad.
- Además, se ha determinado que se debe almacenar la información de las fábricas. Sin embargo, dado el uso de distribuidores, se usará: Número de la fábrica (único) y Teléfono de contacto. Y se desean ver cuántos artículos (en total) provee la fábrica. También, por información estratégica, se podría incluir información de fábricas alternativas respecto de las que ya fabrican artículos para esta empresa.

## Paso 1
Proponer las frases que describan el problema y generar las entidades y relaciones.

- El client ehace un pedido.
- Cada pedido incluye como mínimo un producto. 
- El producto puede provenir de una fábrica.

![<>](img/Captura%20de%20pantalla%202022-10-29%20141419.png)

## Paso 2
Montar correctamente todas las entidades y sus relaciones y colocar los atributos a cada entidad e interrelación.

![<>](img/Captura%20de%20pantalla%202022-10-29%20141454.png)