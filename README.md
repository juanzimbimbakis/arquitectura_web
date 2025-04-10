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

Endpoints: 

Producto.

-->get
   descripción: listar todos los productos
   parametros: ninguno
   payload: ninguno
   path: /products
   status code: 200 OK, 500 Internal server error

-->get 
   descripción: devuelve un producto con determinado id
   parametros: id del producto que se quiere solicitar 
   payload: ninguno
   path: /products/{id}
   status code: 200 OK, 404 not found 

-->post 
   descripción: crea un nuevo producto 
   parametros: ninguno 
   payload: JSON con el nuevo producto a crear 
   path: /products 
   status code: 201 created, 400 bad request, 409 conflict, 500 Internal server error 








            
