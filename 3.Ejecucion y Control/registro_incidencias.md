# 13. Registro de Incidencias (Issue Log)

Este documento registra los problemas o incidentes reales surgidos durante la ejecución del proyecto, detallando su impacto, solución y responsables.


## 13.1. Registro de Incidencias Activas y Resueltas

### Incidencia ID: INC-001
*   **Fecha de Reporte:** Lunes de la Semana 10
*   **Descripción del Problema:** Presentación formal de renuncia irrevocable por parte de los dos Desarrolladores Senior Clave del proyecto por ofertas externas.
*   **Impacto en el Proyecto:** Alto / Crítico. Paraliza el desarrollo del núcleo del Módulo de Cobros y Recaudación planificado para los Sprints 3 y 4. Riesgo inminente de retraso en la entrega final del MVP.
*   **Acción de Resolución:** 
    *   Se negoció una salida de 5 días con los desarrolladores salientes para realizar sesiones intensivas de *Code Review* y entrega de credenciales de servidores al PM.
    *   Se reasignó al desarrollador Mid-Level para liderar temporalmente la continuidad del código.
    *   Se inyectó el fondo de la reserva de contingencia para el pago de un programador externo por un periodo de 6 semanas.
*   **Responsable:** Gerente de Proyecto (PM)
*   **Estado:** Cerrado (Mitigado)

### Incidencia ID: INC-002
*   **Fecha de Reporte:** Miércoles de la Semana 10
*   **Descripción del Problema:** Notificación formal por parte de la Alcaldía sobre cambios de última hora en la normativa de Licencias Sanitarias Municipales, afectando los requisitos de validación técnica pre-acordados.
*   **Impacto en el Proyecto:** Medio. Requiere modificar la validación de campos de la base de datos y los flujos de alerta del Módulo 3.
*   **Acción de Resolución:** Se actualizó el documento de Especificación de Requerimientos (`05_especificacion_requerimientos.md`) incorporando la nueva norma legal de Sucre. Al no estar desarrollado aún el módulo de licencias (programado para el Sprint 5), el impacto en el código fue de 0 horas.
*   **Responsable:** Analista de Requerimientos / PM
*   **Estado:** Cerrado