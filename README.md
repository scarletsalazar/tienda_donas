Introducción
Este proyecto busca desarrollar una aplicación en Python para gestionar eficientemente el inventario y las ventas de una tienda de donas. La aplicación estará diseñada para registrar las transacciones de venta, controlar el stock de productos, generar reportes de ventas, y ofrecer una interfaz amigable para los clientes y los encargados del negocio.

Contexto del Problema
En una tienda de donas, la gestión eficiente del inventario es fundamental para asegurar la disponibilidad constante del producto y evitar pérdidas económicas. Actualmente, el sistema utilizado para llevar el control de las ventas y el stock es manual, lo que genera errores humanos, demora en el procesamiento de datos, y falta de capacidad para generar reportes detallados. Se necesita una solución automatizada que permita registrar las ventas, consultar el inventario en tiempo real, y realizar análisis que ayuden a tomar decisiones basadas en datos.

Análisis de Requerimientos
1. Requerimientos Funcionales:
Registro de Productos: Ingreso de la información básica como nombre, precio, categoría, y stock disponible.
Ventas: Registro de transacciones de venta, incluyendo la cantidad vendida, el total por venta, y la fecha.
Consulta de Inventario: Visualización del stock disponible en tiempo real con filtros por producto y rango de fechas.
Reportes: Generación de reportes sobre las ventas diarias, mensuales y anuales, mostrando los productos más vendidos y los períodos con mayor demanda.
Gestión de Usuarios: Control de acceso para los encargados del negocio, con roles de administrador, vendedor y gerente.
2. Requerimientos No Funcionales:
Seguridad: Protección de los datos contra accesos no autorizados, respaldos automáticos de la información.
Escalabilidad: Capacidad para añadir nuevos productos y usuarios sin afectar el rendimiento del sistema.
Interoperabilidad: Posibilidad de integrarse con sistemas externos como el servicio de contabilidad y pagos.

Modelo Relacional
Aquí te dejo un esquema básico del modelo relacional para la base de datos de la tienda de donas:

Entidades:
Usuarios: almacena la información de los usuarios que tienen acceso al sistema.

ID_Usuario (PK)
Nombre
Correo
Contraseña

Productos: contiene la información sobre los productos disponibles en la tienda.

ID_Producto (PK)
Nombre
Precio
Cantidad_Stock
Categoría
