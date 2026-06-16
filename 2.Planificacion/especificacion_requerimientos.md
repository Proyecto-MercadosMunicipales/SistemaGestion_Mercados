# 5. Especificación de Requerimientos de Software (ERS)

## 5.1. Requerimientos Funcionales (RF)

### Módulo 1: Registro de Puestos y Comerciantes
* **RF-1.1:** El sistema debe permitir el alta, baja y modificación de comerciantes, capturando: C.I., Nombre Completo, Teléfono, Rubro y Mercado Asignado.
* **RF-1.2:** El sistema debe permitir la creación de puestos virtuales agrupados por Mercado (Campesino, Central, Entre Ríos) y Sector (Carnes, Verduras, Abarrotes, etc.).
* **RF-1.3:** El sistema debe permitir la vinculación formal de un comerciante a uno o más puestos específicos, validando que no existan duplicidades de asignación.

### Módulo 2: Cobro de Tarifas y Patentes
* **RF-2.1:** El sistema debe permitir el registro diario del cobro de la tarifa municipal por puesto.
* **RF-2.2:** El sistema debe emitir un comprobante digital/recibo de pago imprimible con un código único de auditoría interna.
* **RF-2.3:** El sistema debe alertar visualmente (color rojo) en el panel del administrador aquellos puestos que presenten deudas acumuladas de más de 5 días.

### Módulo 3: Control de Licencias Sanitarias
* **RF-3.1:** El sistema debe permitir registrar la fecha de emisión y vencimiento del carnet sanitario de cada comerciante.
* **RF-3.2:** El sistema debe enviar una alerta interna en el tablero principal 15 días antes de que expire la licencia sanitaria de un comerciante.

### Módulo 4: Informes para la Dirección de Ingresos
* **RF-4.1:** El sistema debe generar automáticamente el "Informe de Recaudación Mensual" desglosado por mercado, sector y fecha.
* **RF-4.2:** El sistema debe permitir la exportación de todos los reportes consolidados a formatos PDF y Excel para su fiscalización externa.


## 2. Requerimientos No Funcionales (RNF)
* **RNF-1 (Seguridad):** El sistema debe implementar un control de acceso basado en roles (RBAC), distinguiendo entre: SuperAdministrador (Alcaldía), Administrador de Mercado, e Inspector Sanitario.
* **RNF-2 (Disponibilidad):** La plataforma web debe garantizar una disponibilidad del 99.5% durante el horario de operación de los mercados (05:00 a 22:00).
* **RNF-3 (Rendimiento):** El tiempo de carga de las consultas de reportes mensuales no debe exceder los 3 segundos con un volumen de hasta 5,000 registros simultáneos.
* **RNF-4 (Portabilidad):** El sistema debe ser responsivo y compatible con los navegadores modernos (Google Chrome, Mozilla Firefox, Microsoft Edge) sin requerir plugins adicionales.