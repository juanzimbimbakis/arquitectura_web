# arquitectura_web

Administracion de stock. 

Clases: 
  - Producto 
  - Proveedor 
  - MovimientoStock
  - Cliente
  - Venta 
  - OrdenDeCompra 
  - Usuario

Servicios: 
  - CRUD de c/u
  - buscar que usuario administrador hizo movimiento de stock de un producto
  - listar todos los movimientos de stock de un usuario administrador
  - buscar proveedor de una orden de compra
  - obtener historial de movimientos de un producto (o stock)

Clientes del sistema: 
- app mobile de usuarios administradores
- portal web de usuarios administradores 

Ejemplo: 
Si queremos listar clientes que compraron un producto: 
- input --> idProducto
- output --> lista de clientes 
