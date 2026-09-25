# Historias de usuario

## HU01 — Registro e inicio de sesión

**Como** cliente,  
**quiero** registrarme e iniciar sesión en el marketplace,  
**para** realizar compras y consultar mis pedidos.

### Criterios de aceptación

- El sistema debe validar los datos obligatorios.
- El correo electrónico no debe estar registrado previamente.
- El cliente debe poder iniciar sesión con credenciales válidas.
- El sistema debe mostrar un mensaje cuando las credenciales sean incorrectas.

## HU02 — Consulta del catálogo

**Como** cliente,  
**quiero** consultar y buscar productos por nombre o categoría,  
**para** encontrar productos adecuados para mi mascota.

### Criterios de aceptación

- El sistema debe mostrar los productos disponibles.
- El cliente debe poder filtrar los productos por categoría.
- Cada producto debe mostrar nombre, precio, descripción y disponibilidad.

## HU03 — Administración del carrito

**Como** cliente,  
**quiero** agregar, actualizar y retirar productos del carrito,  
**para** preparar mi pedido antes de realizar la compra.

### Criterios de aceptación

- El sistema debe permitir agregar productos disponibles.
- El cliente debe poder modificar la cantidad.
- El sistema debe calcular automáticamente el total.
- El cliente debe poder eliminar productos del carrito.

## HU04 — Compra y pago

**Como** cliente,  
**quiero** confirmar mi pedido y realizar el pago,  
**para** completar la compra de los productos seleccionados.

### Criterios de aceptación

- El sistema debe validar la disponibilidad de los productos.
- El sistema debe enviar la transacción a la pasarela de pago.
- El pedido debe confirmarse únicamente cuando el pago sea aprobado.
- El cliente debe recibir el número de su pedido.

## HU05 — Gestión de productos

**Como** vendedor,  
**quiero** registrar y actualizar mis productos,  
**para** mantener vigente el catálogo ofrecido a los clientes.

### Criterios de aceptación

- El vendedor debe poder registrar el nombre, descripción, precio y existencias.
- El vendedor debe poder modificar los datos de sus productos.
- El sistema debe impedir valores de precio o existencias inválidos.
- Los cambios deben reflejarse en el catálogo.

## HU06 — Seguimiento de pedidos

**Como** cliente,  
**quiero** consultar el estado de mis pedidos,  
**para** conocer el avance de la entrega.

### Criterios de aceptación

- El sistema debe mostrar el estado actual del pedido.
- El sistema debe mostrar el código de seguimiento cuando esté disponible.
- La información debe actualizarse a partir del servicio de envío.