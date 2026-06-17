# 15. Tablero de Seguimiento y KPIs del Proyecto

Este tablero centraliza los Indicadores Clave de Rendimiento (KPIs) utilizados por el Jefe de Proyecto para monitorear la salud técnica, financiera y operativa del desarrollo en la Semana 10.


## 15.1. KPIs Financieros y de Cronograma (Gestión del Valor Ganado - EVM)

Para rendir cuentas de manera exacta a la Dirección de Ingresos de la Alcaldía de Sucre sobre los **70,000 Bs**, se calculan los siguientes índices cuantitativos:

| Métrica | Nombre Técnico | Valor Actual | Interpretación Técnica | Status |
|---|---|---|---|---|
| **PV** (Planned Value) | Valor Planificado | 29,400 Bs | Presupuesto que se debió haber invertido hasta la semana 10 según el plan. | - |
| **EV** (Earned Value) | Valor Ganado | 27,300 Bs | Valor real del software desarrollado hasta el momento (39% de avance del MVP). | - |
| **AC** (Actual Cost) | Costo Real | 28,500 Bs | Lo gastado en total (incluye planilla y el inicio de la contingencia). | - |
| **SPI** (Schedule Performance Index) | Índice de Rendimiento del Cronograma | **0.93** | $SPI = \frac{EV}{PV}$. Al ser menor a 1.0, indica un ligero retraso del 7% debido a las renuncias. | Alerta |
| **CPI** (Cost Performance Index) | Índice de Rendimiento del Costo | **0.96** | $CPI = \frac{EV}{AC}$. Al ser menor a 1.0, indica un leve sobrecosto temporal por el uso del fondo de contingencia. | Estable |


## 15.2. KPIs de Desarrollo Ágil (Rendimiento del Equipo)

Métricas utilizadas internamente en los Sprints de 2 semanas para medir la adaptación tras la baja de los 2 desarrolladores clave:

*   **Velocidad del Equipo (Sprint Velocity):**
    *   *Sprints 1 y 2 (Línea base con equipo completo):* 35 Puntos de Historia (SP) promedio por Sprint.
    *   *Sprint 3 (Semana 10 - crisis de personal):* Cayó a **18 Puntos de Historia (SP)**.
    *   *Meta de estabilización (Sprint 4):* 25 SP (con el consultor backend externo integrado).
*   **Cumplimiento de Compromiso del Sprint (Sprint Burnup):** **76%** de las historias de usuario planificadas para el Sprint 3 fueron terminadas a tiempo. El 24% restante (módulo de cobros avanzado) se movió al Sprint 4 debido a la transición técnica.


## 15.3. KPIs de Calidad de Software (Aseguramiento de Calidad - QA)

Garantizan que el sistema web para los mercados Central, Campesino y Entre Ríos sea seguro y libre de fraudes fiscales antes de su entrega:

*   **Densidad de Defectos (Bugs Abiertos):** 4 bugs críticos detectados en pruebas internas de integración del Módulo de Registro (todos en proceso de resolución por el equipo remanente).
*   **Cobertura de Pruebas Unitarias (Code Coverage):** **78%** del código fuente cuenta con pruebas automatizadas, asegurando que el cambio en la lógica de las licencias sanitarias no rompa otras funcionalidades del sistema.
*   **Índice de Deuda Técnica:** 4.2% (Tiempo estimado de refactorización de código crítico dejado por los programadores salientes).


## 15.4. Resumen Visual de Alertas Gerenciales

```text
ALCANCE (Geolocalización) : En Proceso de Negociación (CRF-001)
TIEMPO (Cronograma)       : SPI 0.93 (7% de retraso acumulado)
COSTO (Presupuesto)       : CPI 0.96 (Ajustado dentro de los 70,000 Bs)
RECURSOS HUMANOS          : 2 Bajas Críticas (Contingencia Ejecutada)