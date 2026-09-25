# Requisitos funcionales

## RF01 — Gestión de usuarios

El sistema debe permitir que los clientes se registren, inicien sesión y actualicen sus datos personales.

**Historia relacionada:** HU01.

## RF02 — Consulta del catálogo

El sistema debe mostrar el catálogo de productos disponibles con su nombre, descripción, precio, categoría y existencias.

**Historia relacionada:** HU02.

## RF03 — Búsqueda y filtrado

El sistema debe permitir buscar productos por nombre y filtrarlos por categoría.

**Historia relacionada:** HU02.

## RF04 — Gestión del carrito

El sistema debe permitir agregar, modificar y eliminar productos del carrito, además de calcular automáticamente el importe total.

**Historia relacionada:** HU03.

## RF05 — Gestión de pedidos

El sistema debe generar un pedido con un identificador único a partir de los productos confirmados por el cliente.

**Historia relacionada:** HU04.

## RF06 — Procesamiento de pagos

El sistema debe conectarse con una pasarela de pago para procesar la transacción y registrar su resultado.

**Historia relacionada:** HU04.

## RF07 — Gestión de productos

El sistema debe permitir que el vendedor registre, consulte y actualice la información, el precio y las existencias de sus productos.

**Historia relacionada:** HU05.

## RF08 — Seguimiento de pedidos

El sistema debe consultar el servicio de envío y mostrar al cliente el estado y el código de seguimiento de su pedido.

**Historia relacionada:** HU06.

## RF09 — Emisión de comprobantes

El sistema debe solicitar al servicio de facturación la generación del comprobante correspondiente después de confirmar el pago.

**Historia relacionada:** HU04.

## RF10 — Administración del marketplace

El sistema debe permitir que el administrador gestione usuarios, vendedores, productos, categorías e incidencias.

## Matriz de trazabilidad

| Historia de usuario | Requisitos funcionales |
|---|---|
| HU01 | RF01 |
| HU02 | RF02, RF03 |
| HU03 | RF04 |
| HU04 | RF05, RF06, RF09 |
| HU05 | RF07 |
| HU06 | RF08 |