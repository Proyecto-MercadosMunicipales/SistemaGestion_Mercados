# 11. Solicitud de Cambio Formal: Módulo de Geolocalización

*   **Código de Solicitud:** CRF-001
*   **Fecha de la Solicitud:** Semana 10 (Junio de 2026)
*   **Solicitante:** Dirección de Ingresos - Gobierno Autónomo Municipal de Sucre
*   **Estado Actual:** En Evaluación de Impacto


## 11.1. Descripción del Cambio Solicitado
La Alcaldía de Sucre solicita formalmente la inclusión de un Módulo de Geolocalización de Puestos dentro de la plataforma web. Este requerimiento exige mapear visualmente e interactivamente (mediante un mapa digital) la ubicación exacta de cada puesto físico dentro de las instalaciones de los mercados Campesino, Central y Entre Ríos.


## 11.2. Justificación del Cambio
Según el solicitante, este módulo permitirá a los inspectores municipales realizar fiscalizaciones físicas más eficientes en el terreno, contrastando visualmente en una pantalla qué puestos físicos están al día con sus pagos y cuáles presentan deudas acumuladas, agilizando el control operativo diario.


## 11.3. Evaluación de Impacto (Análisis del Project Manager)

El análisis técnico y de gestión revela un impacto crítico en la **Triple Restricción** del proyecto debido a la coincidencia con la renuncia de dos desarrolladores clave en la misma semana:

*   **Impacto en Alcance:** Amplía significativamente el alcance del MVP. Requiere integrar librerías de mapas (ej. Leaflet o Google Maps API) y diseñar una base de datos geoespacial que no estaba planificada.
*   **Impacto en Tiempo:** El desarrollo, pruebas y estabilización de este módulo requiere un estimado de **3 semanas adicionales de trabajo**. Al estar en la semana 10 con el equipo reducido a la mitad, aceptar este cambio sin modificar la fecha de entrega provocaría un retraso catastrófico en los módulos esenciales de Cobros y Reportes.
*   **Impacto en Costo:** La implementación técnica requiere consumir la **Reserva de Gestión (3,000 Bs)** para cubrir el costo de APIs de mapas y horas extra del equipo remanente.


## 11.4. Proceso Formal de Gestión y Resolución Sugerida

Para procesar este cambio formalmente, el equipo debe seguir los siguientes pasos:
1. Registro formal del cambio
2. Evaluación de impacto por el PM
3. Negociación con la Alcaldía (CCB)
4. Resolución formal (Aprobado / Rechazado)
5. Implementación del cambio aprobado
6. Actualizacion de líneas base en git

## Alternativas de Resolución Propuestas para el Comité de Control de Cambios:
    Alternativa A (Recomendada): Diferir el módulo de geolocalización para una "Fase 2" post-MVP. Se mantiene el cronograma original de 6 meses para asegurar la estabilidad del motor de cobros y reportes, protegiendo el proyecto del colapso técnico por la falta de personal.

    Alternativa B (Aceptación con Ajuste): Aprobar el módulo, pero la Alcaldía debe autorizar formalmente una extensión del plazo de entrega de 3 semanas adicionales y transferir los 3,000 Bs de la Reserva de Gestión al presupuesto operativo para compensar la carga técnica.

## 11.5. Roles Involucrados en la Decisión
Gerente de Proyecto (PM): Responsable de presentar esta evaluación de impacto, defender la estabilidad del MVP y coordinar la mesa de negociación.

Comité de Control de Cambios (CCB) / Dirección de Ingresos: Representantes de la Alcaldía con el poder legal para decidir si prefieren extender el plazo del proyecto o postergar el requerimiento en beneficio de la calidad del MVP.