# Identificación de stakeholders y matriz de poder-interés

**Unidad 3 · Sesión 1 · Ingeniería de Requisitos**

| Campo | Detalle |
|---|---|
| Proyecto | Sistema de información para la gestión de obras — CIA Ingeniería |
| Equipo | Paola Andrea Camacho González · Sebastián Felipe Huertas Salas · Juan Miguel Blanco Perilla |
| Fecha | Septiembre de 2026 |

> **Criterio de puntuación.** Poder e interés se califican de 1 a 5. ALTO = 4 o 5; BAJO = 1 a 3. El interés se mide por afectación directa en el trabajo diario, no por opinión favorable hacia el proyecto: alguien puede querer el sistema y aun así tener interés medio, si el problema no lo toca todos los días.

## 1. Identificación de stakeholders

Partimos del mapeo organizacional que la empresa entregó en el cuestionario preliminar y lo ampliamos con bola de nieve durante la entrevista a la administradora de proyectos.

| Stakeholder | Categoría | Cómo se identificó |
|---|---|---|
| Gerente general | Alta dirección / patrocinador | Mapeo organizacional: toma las decisiones a nivel empresarial y aprueba los presupuestos. |
| Gerente de obra | Mando medio administrativo | Mapeo organizacional: responsable de presupuestos y compras, junto con el contador. |
| Contador | Área financiera y contable | Mapeo organizacional, confirmado por bola de nieve: la administradora lo nombró al cierre de la entrevista («el contador, que es el que sufre con las facturas»). |
| Director de obra | Mando medio operativo | Mapeo organizacional: ubicado en campo junto con los residentes; afectado por no recibir información a tiempo. |
| Residente de obra | Usuario final operativo | Bola de nieve: la administradora lo nombró como la siguiente persona a entrevistar. La empresa ya lo había señalado como el más afectado. |
| Administradora de proyectos | Usuaria final administrativa | Mapeo organizacional. Fue la persona entrevistada en la primera sesión de elicitación. |
| Ingeniero de obra | Usuario técnico | Mapeo organizacional: participa en las reuniones semanales donde se toman las decisiones técnicas a partir del informe del residente. |
| Responsable de SST y control de calidad | Área de apoyo normativo | Pregunta de rescate al cierre de la entrevista: calidad y SST también generan documentación y no se habían mencionado. |
| Proveedores de materiales | Externo — proveedor | Análisis de impacto: roces por retrasos en la validación de procesos y facturas fuera de término. |
| Cliente de la obra | Externo — cliente | Análisis de impacto: los retrasos en las entregas han costado imagen frente a los clientes. |

Se llegó a saturación cuando las dos últimas preguntas de «¿quién más debería opinar sobre esto?» no agregaron roles nuevos. Las categorías deben contrastarse con el checklist de la guía teórica de la Sesión 1 antes de dar la lista por cerrada.

## 2. Matriz de poder-interés

| Stakeholder | Poder | Evidencia de poder | Interés | Evidencia de interés | Cuadrante | Estrategia |
|---|:-:|---|:-:|---|---|---|
| Gerente general | 5 | Aprueba o rechaza el presupuesto de cada obra y puede detener o cancelar el proyecto del sistema. | 3 | Lo golpea por resultado (sobrecostos, multas, imagen) pero no opera el proceso a diario; declaró que usaría indicadores para decidir. | Alto poder, bajo interés | **Mantener satisfecho:** informe ejecutivo breve por hito (costo, alcance, beneficio). No saturarlo con detalle operativo. |
| Gerente de obra | 4 | Autoriza las compras junto con el contador; si no respalda el sistema, el flujo de aprobación no cambia. | 4 | Trabaja a diario contra el presupuesto de la obra y es parte del trámite que hoy demora las compras. | Alto poder, alto interés | **Gestionar de cerca:** validar con él el flujo de aprobación de compras y los estados de una orden antes de especificarlos. |
| Contador | 4 | Co-autoriza las compras; su aval condiciona cualquier cambio en facturas y soportes. | 5 | Las multas por facturas fuera de término caen sobre su gestión; hoy reconstruye soportes a mano. | Alto poder, alto interés | **Gestionar de cerca:** entrevistarlo en la siguiente ronda para definir soportes obligatorios y plazos. |
| Director de obra | 4 | Dirige el frente de obra; sin su respaldo los residentes no registrarán nada en un sistema nuevo. | 4 | No recibe la información a tiempo, lo que retrasa decisiones, sobre todo financieras. | Alto poder, alto interés | **Gestionar de cerca:** involucrarlo en definir qué información debe llegarle y con qué frecuencia. |
| Residente de obra | 2 | Ejecuta y reporta, pero no decide sobre presupuesto, compras ni adopción del sistema. | 5 | Anota a mano en obra y termina señalado cuando se pierde información; la empresa lo declara el más afectado. | Bajo poder, alto interés | **Mantener informado:** fuente principal de requisitos de campo. Riesgo de adopción: si registrar le cuesta más que la libreta, no lo usará. |
| Administradora de proyectos | 3 | Concentra contratos, órdenes de compra y soportes, pero no aprueba el proyecto. | 5 | Pierde media mañana buscando documentos que sabe que existen. | Bajo poder, alto interés | **Mantener informado:** validar con ella cada avance del modelo de requisitos (usuaria más intensiva). |
| Responsable de SST y calidad | 2 | No decide sobre el proyecto ni sobre el presupuesto de la obra. | 4 | Maneja formatos, registros y hojas de vida de maquinaria que hoy se desordenan igual que el resto. | Bajo poder, alto interés | **Mantener informado:** consultarlo para decidir si su documentación entra en el alcance de la primera versión. |
| Ingeniero de obra | 3 | Participa en decisiones técnicas semanales, pero no autoriza compras ni define el alcance. | 3 | Le afecta la información desactualizada, aunque su trabajo no depende del registro documental como el del residente. | Bajo poder, bajo interés | **Monitorear:** consultarlo puntualmente al modelar avances de obra y cronograma. |
| Proveedores de materiales | 2 | Son externos y no intervienen en decisiones internas. | 3 | Les afecta cobrar a tiempo, pero no usarían el sistema. | Bajo poder, bajo interés | **Monitorear:** no se entrevistan en esta fase; se revisa si se plantea un portal de proveedores. |
| Cliente de la obra | 2 | Contrata la obra, no el sistema; no influye en cómo la empresa organiza su información. | 2 | Le importa recibir la obra a tiempo; el sistema le llega solo de forma indirecta. | Bajo poder, bajo interés | **Monitorear:** no participa en la elicitación; beneficiario indirecto de los plazos. |

> El gerente general queda en «mantener satisfecho» y no en «gestionar de cerca» porque la escala mide el interés por afectación diaria, y él sufre el problema por resultado, no por uso. Al ser el patrocinador hay que asegurarle visibilidad: si su interés sube, se mueve de cuadrante y se replantea la estrategia.

## 3. Resumen por cuadrante

**Alto poder, alto interés — Gestionar de cerca**

- Gerente de obra: autoriza las compras y vive el trámite que hoy las demora.
- Contador: co-autoriza compras y asume las multas por facturas fuera de término.
- Director de obra: manda en el frente y decide con información que le llega tarde.

Con ellos se valida el alcance antes de especificar. Cualquier cambio en el flujo de compras pasa por ellos.

**Alto poder, bajo interés — Mantener satisfecho**

- Gerente general: aprueba el proyecto y puede detenerlo, pero no opera el proceso a diario.

Comunicación corta y espaciada, en términos de costo y beneficio. El riesgo no es que se oponga, sino que se desentienda y el proyecto quede sin respaldo.

**Bajo poder, alto interés — Mantener informado**

- Residente de obra: fuente principal de requisitos de campo y el más afectado.
- Administradora de proyectos: usuaria más intensiva; ya fue entrevistada.
- Responsable de SST y calidad: aporta una parte del alcance no contemplada.

Son los aliados naturales: no deciden, pero de ellos sale la mayoría de los requisitos y de ellos depende que el sistema se use.

**Bajo poder, bajo interés — Monitorear**

- Ingeniero de obra: se consulta solo al modelar avances y cronograma.
- Proveedores de materiales: fuera del alcance de esta fase.
- Cliente de la obra: beneficiario indirecto.

No se les dedica esfuerzo de elicitación ahora; se revisa su posición si el alcance crece.

## 4. Pendiente de confirmar con la empresa

- Si existe interventoría externa en alguna de las obras en curso: sería un stakeholder con poder alto que hoy no está en la lista.
- Si el gerente general y el gerente de obra son la misma persona en algunas obras (el cuestionario preliminar no lo aclara).
- Los puntajes de poder del contador y del gerente de obra: se asignaron a partir de lo declarado; verificarlos al entrevistarlos.
