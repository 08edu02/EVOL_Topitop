# Topitop ERP

Bienvenido al repositorio del sistema ERP de **Topitop**, una empresa peruana líder en manufactura textil y exportación de prendas de vestir en tejido de punto 100% algodón.

Este repositorio contiene los módulos y componentes necesarios para el desarrollo y mantenimiento del ERP que gestiona las operaciones, ventas, soporte y administración de Topitop.

## Estructura del Proyecto

La estructura del repositorio se organiza en cuatro áreas principales, cada una con submódulos específicos:

- **Administración**
  - `Finanzas_Contabilidad`: Gestión de finanzas, contabilidad y presupuestos.
  - `Legal_Cumplimiento`: Control de normativas legales y cumplimiento.
  - `Recursos_Humanos`: Administración de personal, nóminas y beneficios.

- **Comercial**
  - `Ventas`: Gestión de ventas y seguimiento de clientes.
  - `Marketing_Publicidad`: Estrategias de marketing y campañas publicitarias.
  - `Servicio_Cliente`: Atención y soporte a clientes.

- **Soporte**
  - `Investigacion_Desarrollo`: Innovación de productos y procesos.
  - `Calidad`: Control de calidad de los productos.
  - `IT`: Gestión de infraestructura tecnológica y soporte.

- **Operación**
  - `Produccion`: Control de procesos de manufactura y producción.
  - `Logistica_Distribucion`: Logística de almacenes y distribución.
  - `Compras_Proveedores`: Gestión de proveedores y adquisición de materiales.

Cada módulo tiene un propósito específico, y esta organización facilita el trabajo en equipo y el mantenimiento del sistema.

## Flujo de Trabajo de Desarrollo

Para mantener un flujo de trabajo claro y organizado, el repositorio utiliza un enfoque de ramas que asegura la calidad y estabilidad del código. A continuación, se detalla el propósito de cada rama:

- **main**: La rama principal que contiene el código en estado estable, listo para producción.
- **dev**: Rama de desarrollo, donde se realizan cambios y se integran nuevas funcionalidades.
- **calidad**: Rama de pruebas de calidad. Desde `dev`, se fusionan los cambios aquí para revisión y pruebas antes de pasarlos a producción.
- **produccion**: Rama para la versión final del código, que contiene el código listo para ser desplegado en el entorno de producción.

### Pasos para Contribuir

1. Crea una nueva rama a partir de `dev` para trabajar en una característica o cambio específico.
   git checkout -b nombre-de-la-rama
2. Una vez completados los cambios, súbelos a dev y crea un Pull Request para revisión.
3. Después de aprobar el Pull Request, fusiona los cambios en dev.
4. Cuando dev esté listo para pruebas, fusiona en calidad para la revisión de calidad.
5. Finalmente, después de pasar las pruebas, los cambios se fusionan en produccion para el despliegue.

## Convenciones de Nombres
### Para mantener consistencia:
Las ramas deben tener nombres descriptivos, como feature/nueva-funcionalidad o fix/correccion-bug.
Los commits deben ser claros y concisos, indicando el propósito del cambio (por ejemplo, Add módulo de ventas).

## Contribuciones y Mantenimiento
Este repositorio sigue las mejores prácticas para desarrollo colaborativo. Si tienes sugerencias o encuentras problemas, no dudes en abrir un Issue o contribuir mediante un Pull Request.
Revisa los documentos de contribución y las guías de estilo antes de enviar cambios.


# Este proyecto es propiedad de Topitop y su código está protegido bajo políticas de confidencialidad y seguridad de la empresa.