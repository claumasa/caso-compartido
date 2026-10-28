---
status: framed
segment: Team Leads y mandos medios que conducen reuniones de más de 5 personas en las que se decide algo (con o sin herramienta compartida), en cuentas Business Premium del sector tecnología, con 100 o más licencias, operación en 3 o más países y facturación superior a USD 100M
personas: valeria-sosa, gabriela-rios, marta-benitez, raul-quintero, camila-ferreyra
primary_focus: gabriela-rios
---

# Opportunity: Las decisiones de la reunión no llegan a ejecutarse como se acordaron

Entre el final de la reunión y el sistema donde se hace el trabajo, lo decidido pierde su responsable, su fecha o su motivo: quien conduce lo reconstruye a mano (20 a 60 minutos por reunión) y aun así quien ejecuta recibe otra versión, con costos de semanas de trabajo, releases movidas y clientes esperando. Es urgente ahora porque el resumen de IA, la respuesta actual de Microsoft, no lo resuelve según sus propios usuarios, los competidores ya ofrecen captura de decisiones conectada a Jira, y en 5 meses se presentan features en CollabCon.

## Segment and personas

Las mismas cuentas que `colaboracion-en-vivo`, pero el problema no depende de que haya una herramienta compartida: pasa también en reuniones donde solo se habla (la sync de Ricardo, el comité de arquitectura de Javier, el comité de releases de Lucía).

- Valeria Sosa (primary; su oportunidad en foco es `colaboracion-en-vivo`) — lo sufre: pierde cerca de una hora los viernes reconstruyendo qué se acordó; su meta es "un único lugar donde vivan las decisiones".
- Gabriela Ríos (primary en foco de esta oportunidad; derivada de 4 entrevistas reales) — lo sufre: el qué queda en Jira o en el documento, pero el por qué y el quién se pierden; reconstruye por correo entre 20 y 30 minutos y los incidentes los pagan otros (un cliente 4 días esperando, 2 semanas de trabajo de otro equipo, 3 días de campaña de más).
- Marta Benítez (secondary) — no lo sufre: su problema es participar durante la reunión, no que se pierda lo decidido.
- Raúl Quintero (tertiary) — no lo sufre; responde la creencia de viabilidad: decide entre Max, el add-on de Copilot o bajar de plan.
- Camila Ferreyra (negative) — no lo sufre dentro del alcance; marca el borde (externos).
- Missing: quien **ejecuta sin haber estado en la reunión** (secondary): un tech lead de otro país o un equipo de otra área que recibe lo decidido por un resumen, un correo o un ticket. Es quien comete el error en 5 de los 10 incidentes.

## Signals

| Signal | Provenance | Source |
|---|---|---|
| Lo decidido "no quedó registrado en ningún lado" en el 24% de las últimas reuniones | survey (n=182) | product/insights/2026-10-28-1045-colaboracion-en-vivo-fuera-de-teams.md, Q9 |
| "Registro y seguimiento de lo decidido" es el tema más mencionado de lo más difícil: 17 de 95; continuidad entre reuniones suma 12 más | survey (n=95) | ídem, Q11 |
| 22 de 32 respuestas "Otro" en dónde quedó lo decidido son el recap de IA; unas 11 mencionan sin que se les pregunte que no distingue lo decidido, no dice quién hace qué o nadie lo lee | survey (n=32) | ídem, Q9 "Otro" |
| El 36% usa el resumen o asistente de IA en algunas reuniones o en la mayoría | survey (n=210) | ídem, Q10 |
| 10 de 10 contaron un incidente concreto de algo decidido que se ejecutó distinto o no se ejecutó; 7 con costo medido (1 a 2 semanas de trabajo descartado, una release movida, un cliente esperando 4 días, presupuesto de campaña gastado, 2 días más una guardia de fin de semana) | real | product/insights/2026-10-28-1124-entrevistas-colaboracion-en-vivo.md, insight 1 |
| 8 de 10 reconstruyen lo decidido a mano después de la reunión (de 2 a 60 minutos); lo hace siempre una sola persona | real | ídem, insight 1 |
| En 5 de los incidentes el error lo cometió quien leyó el registro, no quien estuvo en la reunión | real | entrevistas de Javier, Diego, Sofía, Valeria y Paula |
| En 4 incidentes cada uno creyó que el responsable era otro | real | entrevistas de Andrés, Lucía, Ricardo y Tomás |
| 6 de 10 dejaron de usar el recap de IA o lo corrigen a mano porque mezcla lo decidido con lo conversado, no asigna responsable o no ve lo que pasó en el tablero o el dashboard | real | ídem, insight 2 |
| El 22% de los comentarios negativos post-reunión del segmento menciona la colaboración en vivo, incluido "pierdo tiempo pasando lo que decidimos a un documento" | survey (n no informado) | Info complementaria del caso, §2 |
| El recap y el Facilitator de Teams requieren el add-on de Copilot (unos USD 30), no dependen del plan | secondary | product/research/2026-10-25-1836-colaboracion-en-vivo.md |
| Zoom ofrece una pizarra que escucha la reunión, crea notas de decisiones y próximos pasos, y se integra con Jira, Confluence y Notion (con licencia paga) | secondary | ídem |
| Los huddles de Slack tienen notas que quedan guardadas después de la llamada, con IA | secondary | ídem |
| Valeria reconstruye lo decidido los viernes durante cerca de una hora | synthetic | product/personas/valeria-sosa.md |
| Gabriela pierde el por qué y el quién de lo decidido sobre artefactos que ya existen (Jira, Power BI, Excel, Confluence) | real (persona derivada) | product/personas/gabriela-rios.md |

## Business outcome

Comercial.

- **Principal:** tasa de paso de Premium a Max en el segmento (hoy 3,1% de las cuentas en 12 meses; USD 8 por usuario por mes).
- **Secundario:** retención en la renovación.
- **Riesgo explícito:** hoy el valor más cercano (el recap) se cobra en el add-on de Copilot, no en el plan; la creencia de viabilidad pone a prueba justamente eso.

## Constraints

- Presupuesto máximo: USD 5M.
- Fecha: CollabCon en 5 meses (hacia fines de marzo de 2027). Fija los tiempos, no decide qué construir.
- Límites para cualquier solución: facilidad de uso, accesibilidad, compatibilidad con Microsoft 365, privacidad y seguridad corporativas, tiempo real e impacto mínimo en el rendimiento de la reunión.
- En cuentas reguladas, el registro de lo decidido tiene que quedar en un sistema aprobado y auditable ("el correo es lo que auditoría revisa", Lucía), y no pueden llevarse datos de clientes a herramientas externas.

## Beliefs

Referencias a product/overview.md, el único registro de creencias.

- [opportunity: decisiones-sin-ejecutar] [value] En las reuniones de más de 5 del segmento en las que se decide algo, al menos 1 de cada 3 decisiones llega a ejecutarse con un responsable, una fecha o un motivo distinto del acordado, y quien conduce dedica 30 minutos o más por reunión a reconstruir lo decidido.
- [opportunity: decisiones-sin-ejecutar] [viability] Para quienes compran en las cuentas del segmento (IT y finanzas), que las decisiones de las reuniones se registren y lleguen bien a quien ejecuta es un motivo para pagar los USD 8 del paso a Max, y no algo que esperan que resuelva Copilot sin costo extra: aparece como razón en al menos 1 de cada 5 conversaciones de renovación o paso a Max.
- Depende de: [product] [viability] La experiencia de Team Leads y mandos medios pesa en la decisión de IT de renovar, subir o bajar de plan; IT no decide solo por precio y paquete de Microsoft 365.

## Research agenda

| Belief | Instrument | Decision it unlocks | By when |
|---|---|---|---|
| [value] 1 de cada 3 decisiones se ejecuta distinto + 30 min | 1) **Datos propios:** en el segmento, cuánto se abre, edita y reenvía el recap de Copilot; cuántas tareas de las notas de la reunión pasan a Planner; pedir el n del 22% post-reunión. 2) **Seguimiento de decisiones durante 2 semanas** con 8 a 10 personas que conducen, del pool de 48 que se pueden reclutar: cada decisión se registra con su responsable, fecha y motivo, y a las 2 semanas se compara con lo que se ejecutó. También se anotan los minutos de reconstrucción. Definir antes de correrlo qué se hace con un resultado intermedio (por ejemplo, 1 de cada 5 y 20 minutos). 3) Entrevistas con quienes **ejecutan sin haber estado** (la persona que falta). | Si A pasa a `/explore-solutions` antes que la colaboración en vivo, y si el foco es quien conduce o quien ejecuta. | 2026-12-15 |
| [viability] Max, no Copilot | 1) **Datos propios:** etiquetar en el CRM las notas de renovación y paso a Max del segmento (últimos 12 meses) con "decisiones / actas / recap", junto con la etiqueta "colaboración" que ya está en la agenda de `colaboracion-en-vivo`. 2) **Datos propios:** comparar la tasa de paso a Max entre cuentas con y sin el add-on de Copilot. 3) `/research-market`: precio y paquete de las herramientas de seguimiento de decisiones (notas de IA de Zoom, Slack huddles, herramientas de actas) y si se cobran aparte. 4) Conversaciones con quienes compran (IT y finanzas, como Raúl): ¿esto se paga en Max, en Copilot o "debería venir incluido"? | Si lo que salga va en Max, en Premium o en Copilot, y si A se persigue por el paso a Max o por la retención. | 2026-12-31 |
| [product] [viability] El peso de quienes conducen en la decisión de IT (dependencia) | Las mismas conversaciones con quienes compran. | Si el valor apunta a quien conduce o a IT. | 2026-12-31 |
| Hueco: la persona que ejecuta sin haber estado | `/generate-personas` para el hueco y entrevistas reales con 4 o 5 de esas personas (pedir contactos a quienes ya entrevistamos). | Si el problema se plantea desde quien conduce, desde quien ejecuta o desde los dos. | 2026-11-30 |

## Candidate ideas (not evaluated)

Evaluadas en [product/solutions/2026-10-28-1210-decisiones-sin-ejecutar.md](../solutions/2026-10-28-1210-decisiones-sin-ejecutar.md) (2026-10-28).

- Situación actual (punto de comparación): quien conduce reescribe a mano y lo distribuye por correo, Slack o Jira; Paula revisa el recap antes de mandarlo. — baseline
- Lista de decisiones con responsable, fecha y motivo, confirmada por el grupo antes de cerrar la reunión. — `chosen` para probar (A1 `cierre-confirmado`)
- Recap de IA que propone decisiones durante la reunión y quien conduce las confirma. — `chosen` para probar (A2 `decisiones-propuestas`)
- Recap que toma como fuente lo trabajado en la reunión (tablero, dashboard, documento), no solo el audio. — `chosen` para probar, dentro de A2
- Envío de las decisiones al sistema donde vive el trabajo (Jira, Confluence, correo, Planner). — `parked` (A3 `decisiones-al-sistema`)
- Aviso a quienes no estuvieron y tienen que ejecutar. — `parked` (A4 `aviso-a-quien-ejecuta`)
- Detectar decisiones sin responsable antes de que termine la reunión. — `chosen` para probar, dentro de A2
