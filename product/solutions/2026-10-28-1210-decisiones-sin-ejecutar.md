---
opportunity: decisiones-sin-ejecutar
status: testing-several
chosen: cierre-confirmado, decisiones-propuestas
tests:
---

# Soluciones para: Las decisiones de la reunión no llegan a ejecutarse como se acordaron

## Qué dice la evidencia ahora

- [value] de la oportunidad: sostenida, sin anotación. 10/10 contaron un incidente (7 con costo medido) y 8/10 reconstruyen a mano entre 20 y 60 min (real, `product/insights/2026-10-28-1124-entrevistas-colaboracion-en-vivo.md`, insight 1). Los umbrales "1 de cada 3" y "30 min o más" no se midieron: el seguimiento de 2 semanas está en la agenda (2026-12-15).
- [viability] de la oportunidad: abierta, sin evidencia directa. La gemela de `colaboracion-en-vivo` está `weakened`, y el recap y Facilitator se cobran en el add-on de Copilot, no en Max (secondary, `product/research/2026-10-25-1836-colaboracion-en-vivo.md`).
- Las Collaborative Notes ya existen sin Copilot y sincronizan tareas con Planner (secondary, ídem). Hay quienes no las conocen (Andrés; real, insights "Otras señales").
- Hueco: quien ejecuta sin haber estado; cometió el error en 5 de los 10 incidentes y no fue entrevistado.

## Punto de comparación: qué hacen hoy

Quien conduce reescribe lo decidido después de la reunión, entre 20 y 60 min, y lo manda por correo, Slack o Jira. Lo hace siempre una sola persona; si no lo hace, nadie lo hace (real, insight 1). Quienes usan el recap de IA le suman una revisión manual de 10 a 30 min: "trabajo que yo pensaba que me estaba ahorrando" (real, insight 2: Paula).

## Alternativas

### A1. Cierre con lista confirmada en las notas que ya existen (`cierre-confirmado`)

Ritual sin software nuevo: los últimos 5 min se completa una plantilla con decisión, responsable, fecha y motivo en las Collaborative Notes, y el grupo la confirma en voz alta. Las tareas pasan a Planner. Ataca la pérdida del quién y del por qué en el momento del cierre. Para Gabriela Ríos (primary) y Valeria Sosa (primary). Reemplaza la reconstrucción posterior. Incluye la idea del brief "lista confirmada por el grupo antes de cerrar". Es la alternativa más chica que podría funcionar.

### A2. La IA propone decisiones en vivo y quien conduce confirma (`decisiones-propuestas`)

Durante la reunión, la IA marca decisiones candidatas, avisa cuando una no tiene responsable y toma como fuente el artefacto sobre el que se trabaja (tablero, dashboard, documento), no solo el audio. Quien conduce confirma o descarta cada una en el momento. Ataca las tres fallas del recap (mezcla lo decidido con lo conversado, no asigna responsable, no ve el artefacto). Para Gabriela Ríos (primary). Reemplaza la revisión manual del recap. Incluye las ideas del brief "recap que propone y quien conduce confirma", "detectar decisiones sin responsable" y "recap desde el artefacto". Usar el artefacto como fuente se dejó dentro de A2 porque no aporta nada sin la confirmación en vivo (decisión del usuario, 2026-10-28).

### A3. Envío de lo decidido al sistema donde vive el trabajo (`decisiones-al-sistema`)

Cada decisión confirmada llega sola, con su motivo, al ticket de Jira, a la página de Confluence, a Planner o a un correo auditable. Ataca la transcripción y el motivo perdido en un hilo. Para Gabriela Ríos. Reemplaza el copiado a mano.

### A4. Entrega a quien ejecuta sin haber estado, con acuse de recibo (`aviso-a-quien-ejecuta`)

El responsable que no estuvo en la reunión recibe la decisión con su motivo y tiene que confirmar "lo tomo" o "no es mío". Ataca los casos de "cada uno creyó que lo hacía el otro" y los errores de quien leyó el registro. Para quien ejecuta sin haber estado (secondary, persona por crear). Reemplaza el correo que nadie confirma.

## Comparación

| Alternativa | Deseable | Factible | Viable | Creencia más riesgosa |
|---|---|---|---|---|
| A1 cierre-confirmado | mixed: pain evidenced, relief not tested (real, insights/2026-10-28-1124 insight 1). Indicio en contra: los rituales se caen ("la primera semana todos con el filtro bien, la segunda ya no", real, personas/gabriela-rios.md). No llega a quien no estuvo. | strong: Collaborative Notes GA, sin Copilot, sincroniza con Planner (secondary, research/2026-10-25-1836). Límite: las notas quedan atadas a una reunión puntual (real, insight 3); llega a Planner, no a Jira. | weak: incluido en todos los planes, no mueve el paso a Max; quizás la retención (assumption). | Al menos 7 de 10 quienes conducen cierran con la lista confirmada en el 80% o más de sus reuniones durante 4 semanas, y las decisiones que se ejecutan distinto bajan a la mitad. |
| A2 decisiones-propuestas | mixed: pain evidenced, relief not tested. El sustituto más cercano (recap) tiene evidencia en contra: 6/10 lo abandonan o lo corrigen (real, insight 2). La confirmación humana se apoya en el hábito de Paula (real). | to check with tech: precisión de la detección, lectura de artefactos externos, tiempo real sin afectar la reunión, privacidad. Facilitator cubre parte (secondary). | mixed: Zoom lo cobra en licencia paga (secondary); el ancla de Microsoft es Copilot a unos USD 30 (secondary). | Las propuestas aciertan lo suficiente para confirmarse en la reunión: el 70% o más se acepta sin editar y la revisión posterior baja de 10 a 30 min a menos de 5. |
| A3 decisiones-al-sistema | mixed: pain evidenced, relief not tested. "Que eso quede en el ticket" es un deseo, no una reacción (real, Martina). | to check with tech: conectores con Jira y Confluence; en cuentas reguladas, sistema aprobado y auditable (constraint del brief). | mixed: la competencia lo cobra en licencia paga (secondary); empaquetarlo en Max es assumption. | Al menos la mitad de las decisiones que se ejecutan distinto estaban bien registradas al cerrar la reunión (el error está en pasarlas al sistema). |
| A4 aviso-a-quien-ejecuta | mixed: pain evidenced, relief not tested. 5 errores de lectura y 4 de responsable ambiguo (real), contados por quien conduce; quien ejecuta no fue entrevistado. | to check with tech: responsables de otras áreas u organizaciones; necesita un responsable ya registrado. | weak (assumption): un aviso difícilmente justifica USD 8 más. | Al menos 1 de cada 2 decisiones que se ejecutan distinto tiene un responsable que no estuvo en la reunión. |

## Decisión

Se eligen para probar A1 y A2 en paralelo (decisión del usuario, 2026-10-28; coincide con la recomendación). Las dos compiten por el mismo momento, el registro en el cierre, y la prueba responde si hace falta IA o si alcanza un ritual sobre una función que ya existe. A1 es el punto de comparación de A2: si gana A1, el problema es de descubrimiento y adopción, y el resultado empuja la retención, no el paso a Max. A3 y A4 actúan después del registro y dependen de A1 o A2.

Qué cambiaría la decisión: que el seguimiento de decisiones muestre que el error nace al pasar lo decidido al sistema (sube A3) o en quien no estuvo (sube A4), o que la investigación con quienes compran muestre que esperan esto dentro de Copilot (A2 pierde viabilidad para Max).

## Para probar

- A1 — "Al menos 7 de 10 quienes conducen cierran con la lista confirmada en el 80% o más de sus reuniones durante 4 semanas, y las decisiones que se ejecutan distinto bajan a la mitad": es la que mata A1. Si el ritual no se sostiene, la función existe y no sirve, como pasó con la guía de filtros de Diego. Se diseña en /design-solution-tests.
- A2 — "El 70% o más de las decisiones propuestas se acepta sin editar y la revisión posterior baja a menos de 5 min": es la que mata A2. Si quien conduce tiene que corregir como hoy corrige el recap, A2 repite la falla que llevó a 6 de 10 a abandonarlo. Se diseña en /design-solution-tests.

## Propuesta de valor: cierre-confirmado (A1)

- **Dolor que alivia:** el quién y el por qué se pierden entre el final de la reunión y el sistema; 4 casos de "creí que lo hacía el otro" y 20 a 60 min de reconstrucción (real, insight 1).
- **Ganancia:** la reunión termina con la lista ya hecha y confirmada por todos, también por quienes no hablaron ("que lo sepan todos, incluso los que no hablaron", Sofía).
- **Reemplaza:** el correo de reconstrucción del día siguiente. Se cambiaría porque cuesta 5 minutos dentro de la reunión y no 30 fuera de ella, y no depende de que quien conduce se acuerde.
- **Deliberadamente no:** no construye nada nuevo, no usa IA, no integra con Jira ni avisa a quien no estuvo.

## Propuesta de valor: decisiones-propuestas (A2)

- **Dolor que alivia:** el recap mezcla lo decidido con lo conversado, no asigna responsable y no ve el artefacto; quienes lo usan lo revisan 10 a 30 min (real, insight 2).
- **Ganancia:** quien conduce confirma decisiones a medida que aparecen, con el responsable y el artefacto de contexto, y sale de la reunión con el registro cerrado.
- **Reemplaza:** el recap revisado a mano y la reconstrucción posterior. Se cambiaría porque confirmar en vivo cuesta segundos y evita errores como el de Paula (una idea que apareció como decidida, una semana de dos desarrolladores).
- **Deliberadamente no:** no decide por el grupo (sin confirmación no hay decisión), no resume la conversación y no envía nada al sistema donde vive el trabajo (eso es A3, en espera).

## Creencias

- [opportunity: decisiones-sin-ejecutar] [value] En las reuniones de más de 5 del segmento en las que se decide algo, al menos 1 de cada 3 decisiones llega a ejecutarse con un responsable, una fecha o un motivo distinto del acordado, y quien conduce dedica 30 minutos o más por reunión a reconstruir lo decidido. (registrada)
- [opportunity: decisiones-sin-ejecutar] [viability] Para quienes compran en las cuentas del segmento (IT y finanzas), que las decisiones de las reuniones se registren y lleguen bien a quien ejecuta es un motivo para pagar los USD 8 del paso a Max […]. (registrada)
- [feature: cierre-confirmado] [usability] Al menos 7 de 10 quienes conducen sostienen el cierre con lista confirmada en las Collaborative Notes en el 80% o más de sus reuniones durante 4 semanas. (registrada 2026-10-28)
- [feature: cierre-confirmado] [value] Con el cierre confirmado, las decisiones que se ejecutan con un responsable, una fecha o un motivo distinto bajan a la mitad respecto del seguimiento sin intervención. (registrada 2026-10-28)
- [feature: decisiones-propuestas] [value] En reuniones reales del segmento, quien conduce acepta sin editar el 70% o más de las decisiones que propone la IA, y la revisión posterior baja de 10 a 30 min a menos de 5. (registrada 2026-10-28)
- [feature: decisiones-propuestas] [feasibility] La detección de decisiones y responsables funciona en tiempo real en reuniones de más de 5, tomando el artefacto compartido como fuente, sin degradar el rendimiento de la reunión. (en el archivo, no se registra: to check with tech)

## Descartadas o en espera

- A3 decisiones-al-sistema — parked: actúa después del registro y depende de A1 o A2. Vuelve si el seguimiento de decisiones (agenda, 2026-12-15) muestra que la mitad o más de las decisiones que se ejecutan distinto estaban bien registradas al cerrar.
- A4 aviso-a-quien-ejecuta — parked: la persona que sufre el problema no fue entrevistada. Vuelve con las entrevistas a quienes ejecutan (agenda, 2026-11-30) y si el seguimiento muestra que 1 de cada 2 decisiones que se ejecutan distinto tiene un responsable que no estuvo.

## Resultado
