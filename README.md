# 📚 Microservicios para Sistema de Biblioteca

Este repositorio contiene la implementación de múltiples **microservicios** diseñados para gestionar los distintos procesos de una **biblioteca**, siguiendo una arquitectura **desacoplada** y **escalable**.

Cada microservicio está enfocado en una entidad específica del dominio y proporciona un conjunto completo de operaciones **CRUD** (_Crear, Leer, Actualizar, Eliminar_) a través de una **API RESTful**.

---

## 🧩 Microservicios incluidos

### 🔐 `user-service`
- **Configurar permisos**: Asignación y modificación de permisos de acceso a los distintos módulos y funcionalidades del sistema.

### 🛒 `sales-service`
- **Registrar ventas**: Procesamiento de transacciones, aplicando descuentos y ofertas si corresponde.
- **Atender devoluciones y reclamaciones**: Gestión de devoluciones de productos y reclamos de clientes.
- **Generar facturas**: Emisión de facturas electrónicas y envío por correo electrónico.

### 🚚 `shipping-service`
- **Gestionar envíos**: Crear, actualizar y rastrear envíos desde bodega hasta destino.
- **Optimizar rutas de entrega**: Planificación y optimización de rutas para entregas locales y regionales.
- **Actualizar estado de pedidos**: Cambio de estado de pedidos desde el procesamiento hasta la entrega final.

> Cada servicio está desarrollado de forma **independiente**, lo que permite su despliegue, escalamiento y mantenimiento autónomos.

---

## ⚙️ Características técnicas

- **APIs RESTful** por microservicio  
- **Separación de responsabilidades**  
- Soporte para **persistencia de datos**  
- **Documentación individual** por servicio  (Pendiente)
