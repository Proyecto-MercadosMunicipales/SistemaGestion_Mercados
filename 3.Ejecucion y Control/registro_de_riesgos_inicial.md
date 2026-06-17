# 10. Registro de Riesgos Inicial (Línea Base)

Este documento identifica de forma proactiva los riesgos potenciales al inicio del proyecto, estableciendo planes de mitigación y contingencia antes de comenzar la fase de desarrollo.


## 10.1. Matriz de Riesgos Inicial

| ID | Descripción del Riesgo | Categoría | Probabilidad | Impacto | Puntuación (PxI) | Plan de Mitigación / Acción Preventiva |
|---|---|---|---|---|---|---|
| **R-01** | Cambios drásticos o adición de requisitos fuera del alcance original por parte de la Alcaldía. | Alcance | Alta | Medio | **Alto** | Establecer un proceso rígido de control de cambios desde el día 1 con firmas de aprobación del patrocinador. |
| **R-02** | **Renuncia de personal técnico clave (Desarrolladores Senior) durante la fase de desarrollo.** | **Recursos H.** | **Media** | **Alto** | **Alto** | **Mitigación:** Documentar el código diariamente usando Git, mantener estándares de arquitectura claros y asegurar que los desarrolladores Junior participen en la revisión de código para evitar silos de conocimiento. |
| **R-03** | Modificaciones repentinas en las normativas municipales de licencias sanitarias. | Legal | Media | Medio | **Medio** | Mantener reuniones quincenales con el equipo legal de la Dirección de Ingresos para prever cambios normativos. |
| **R-04** | Resistencia de los comerciantes de los mercados a registrarse en la plataforma digital. | Social | Baja | Alto | **Medio** | Coordinar con los dirigentes de los mercados (Central, Campesino, Entre Ríos) talleres de socialización y sensibilización. |


## 10.2. Estrategia de Contingencia para el Riesgo R-02 (Bajas de Personal)
*   **Trigger:** Notificación formal de renuncia por parte de uno o más desarrolladores clave.
*   **Acción de Contingencia:** 
    1. Congelar inmediatamente los entregables no críticos del sprint actual.
    2. Utilizar de forma inmediata la **Reserva de Contingencia Financiera (5,000 Bs)** para lanzar una convocatoria de contratación de emergencia o subcontratación de un consultor externo por producto.
    3. Promover temporalmente al desarrollador Mid/Junior con mayor experiencia para asegurar la continuidad de la arquitectura de la base de datos.