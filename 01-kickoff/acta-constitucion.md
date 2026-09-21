# Acta de constitución (Project Charter)

**Unidad 3 · Sesión 1 · Ingeniería de Requisitos**

| Campo | Detalle |
|---|---|
| Nombre del proyecto | Sistema de información para la gestión de obras — CIA Ingeniería |
| Patrocinador | Gerencia general — CIA Ingeniería |
| Responsable de la iniciativa | Área administrativa (administradora de proyectos) — CIA Ingeniería |
| Fecha del acta | 20 de septiembre de 2026 |

## 1. Objetivo del proyecto

Definir y dejar especificados los requisitos de un sistema centralizado que unifique la gestión operativa y administrativa de CIA Ingeniería, de modo que procesos como la contratación, la presupuestación y el seguimiento de obra puedan migrarse gradualmente a él. En el marco de la asignatura se llega hasta la especificación y validación de requisitos; la implementación del sistema queda fuera de este trabajo.

## 2. Alcance preliminar

**Dentro de esta fase**

- Módulo de Presupuestación y Control de Costos.
- Módulo de Contratación y Adquisiciones.
- Módulo de Control de Obra y Avance Financiero vs. Físico.
- Base de datos centralizada con control de acceso y trazabilidad de cambios.

**Fuera de esta fase (y por qué queda fuera)**

- **Conexión con planos:** el alcance se limita al manejo de información dentro de la obra.
- **Firma digital legal / avanzada:** las firmas de contratos se harán en físico o por el método tradicional, para no pagar licencias de firma digital de terceros.
- **Notificaciones automáticas:** por complejidad e infraestructura, se prioriza primero el sistema de base de datos.

## 3. Supuestos y restricciones

**Supuestos**

- El personal que maneja los Excel estará disponible para enseñarnos cómo calculan los costos actualmente.
- Los archivos de Excel actuales están completos y no contienen datos contradictorios.

**Restricciones**

- El sistema debe estar terminado dentro del tiempo y presupuesto asignados.
- Al tratarse de información sensible, se prioriza proteger la información de clientes y proveedores.

## 4. Stakeholders y roles

| Stakeholder | Rol en el proyecto |
|---|---|
| Gerente general | Patrocinador — aprueba el proyecto y puede detenerlo. |
| Gerente de obra | Autoriza compras y presupuesto de obra. |
| Contador | Responsable financiero y de soportes contables. |
| Director de obra | Autoridad técnica y financiera en el frente de obra. |
| Residente de obra | Usuario operativo — fuente principal de requisitos de campo. |
| Administradora de proyectos | Responsable de la iniciativa — usuaria administrativa principal. |
| Ingeniero de obra | Usuario técnico — participa en decisiones técnicas semanales. |
| Responsable de SST y calidad | Control documental normativo (seguridad, salud y calidad). |
| Proveedores de materiales | Externo — sin rol formal en el proyecto; se monitorea. |
| Cliente de la obra | Externo — beneficiario indirecto; sin rol formal en el proyecto. |

## 5. Cronograma de alto nivel

| Hito | Fecha estimada |
|---|---|
| Inicio y reuniones (kick-off) | 20 sep – 2 oct 2026 |
| Diseño del sistema | 5 oct – 23 oct 2026 |
| Desarrollo Módulo de Presupuestos | 26 oct – 13 nov 2026 |
| Desarrollo Módulo de Compras y Contratos | 16 nov – 11 dic 2026 |
| Desarrollo Módulo de Control de Obra | 12 ene – 12 feb 2027 |
| Pruebas con usuarios | 15 feb – 5 mar 2027 |
| Capacitación y salida a producción | 8 mar – 19 mar 2027 |

## 6. Riesgos iniciales

| Riesgo | Impacto si ocurre | Estrategia inicial |
|---|---|---|
| Que los empleados prefieran seguir usando sus propios archivos de Excel por costumbre o desconfianza. | **Alto:** no usarían el sistema y se mantendrían los problemas actuales. | Involucrar a los usuarios desde el diseño de las pantallas y capacitarlos antes del lanzamiento. |
| Datos desordenados en el Excel: errores, fórmulas rotas o datos contradictorios. | **Medio:** retrasos en el diseño, inconsistencia de la información y reportes con errores. | Revisar los archivos de Excel antes de modelar el sistema. |
| Poca disponibilidad del personal de obra: residentes e ingenieros sin tiempo para revisar o probar el sistema. | **Medio:** fallas operativas por no probarlo a tiempo en un entorno real. | Sesiones cortas de 30 a 45 minutos en momentos fijos de la semana, sin interrumpir el trabajo de campo. |
| Problemas de conectividad en obra. | **Medio:** dificultad para registrar avances o presupuestos en tiempo real desde el terreno. | Diseñar la plataforma de forma ligera para que cargue rápido hasta con internet lento. |

## 7. Criterios de éxito

- **Abandono del Excel en obras nuevas:** los presupuestos, órdenes de compra y contratos de las nuevas obras se registran exclusivamente en el nuevo sistema.
- **Ahorro de tiempo en reportes:** reducir a la mitad (50 %) el tiempo que toma a gerencia y finanzas revisar costos vs. presupuestos de las obras.
- **Adopción rápida:** residentes de obra, compradores y auxiliares capacitados y usando el sistema en su trabajo diario dentro de los primeros 30 días tras el lanzamiento.
- **Información central y no duplicada:** eliminar los datos duplicados o contradictorios entre la oficina principal y el personal de campo.

## 8. Aprobación

| Rol | Fecha de aprobación |
|---|---|
| Patrocinador — Gerencia general, CIA Ingeniería | 20 de septiembre de 2026 |
| Responsable técnico — CIA Ingeniería | 20 de septiembre de 2026 |
