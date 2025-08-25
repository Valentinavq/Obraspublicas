# Descripción del proyecto

El proyecto consiste en el desarrollo de un **sistema digital de seguimiento y reparación de baches** para la ciudad de Bahía Blanca.  
El sistema permitirá a los ciudadanos reportar baches mediante una aplicación web y móvil, adjuntando información como ubicación, tamaño, fotos y datos de contacto.  

A su vez, el Departamento de Obras Públicas podrá gestionar dichos reportes, asignar cuadrillas, registrar órdenes de trabajo, calcular costos y generar informes.  

El objetivo principal es **mejorar la eficiencia en la gestión de reclamos y reparaciones viales**, garantizando una respuesta más ágil y transparente ante los problemas urbanos.  
## Requerimientos principales

### Requerimientos funcionales
- Registro de usuarios (ciudadanos y personal municipal).  
- Creación de reportes de baches con **ID automático**, ubicación, tamaño, distrito, fotos y prioridad.  
- Registro y seguimiento de **órdenes de trabajo** (equipo asignado, horas, materiales, costo, estado del bache).  
- Gestión de un **archivo de daños** reportados por los ciudadanos.  
- Posibilidad de **editar o eliminar reclamos**.  
- Generación de **reportes** y exportación de datos (CSV/Excel).  

### Requerimientos no funcionales
- **Alta disponibilidad** y funcionamiento offline mediante *KoBoToolbox*.  
- **Interoperabilidad** con otros sistemas municipales (ej. *MiBahía*).  
- **Seguridad** y protección de datos ciudadanos.  
- **Usabilidad sencilla**, accesible con mínima capacitación.  
- **Compatibilidad** con navegadores (Chrome y Firefox) y dispositivos móviles con GPS y cámara.  
