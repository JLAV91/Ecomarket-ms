📚 **Microservicios para Sistema de Biblioteca**
Este repositorio contiene la implementación de múltiples microservicios diseñados para gestionar los distintos procesos de una biblioteca, siguiendo una arquitectura desacoplada y escalable.

Cada microservicio está enfocado en una entidad específica del dominio y proporciona un conjunto completo de operaciones CRUD (Crear, Leer, Actualizar, Eliminar) a través de una API RESTful.

🧩 **Microservicios incluidos**

**User-service:** Configurar Permisos: Asignar y modificar permisos de acceso a 
diferentes módulos y funciones del sistema.

**Sales-service:**
• **Registrar Ventas:** Procesar transacciones de venta en el sistema, aplicando 
                    descuentos y ofertas cuando sea necesario.
• **Atender Devoluciones y Reclamaciones:** Procesar devoluciones de productos y 
                    gestionar reclamaciones de clientes.
• **Generar Facturas:** Emitir facturas electrónicas y enviarlas por correo 
                    electrónico a los clientes

**Shipping-service:** 
• **Gestionar envíos:** crear actualizar y seguir envíos de productos desde la 
                    bodegahasta las tiendas y los clientes.
• **Optimizar Rutas de Entrega:** Planificar y optimizar rutas de entrega para los 
                    pedidos locales y regionales.
• **Actualizar Estado de Pedidos:** Cambiar el estado de los pedidos en el sistema, 
                    desde el procesamiento hasta la entrega final.


Cada servicio está desarrollado de forma independiente, permitiendo su despliegue, escalamiento y mantenimiento autónomos.

⚙️ **Características técnicas**
APIs RESTful por microservicio

Comunicación entre servicios (si aplica)

Separación de responsabilidades

Soporte para persistencia de datos

Documentación individual por servicio 
