---
status: framed
segment: Team Leads y mandos medios que conducen sesiones de trabajo en cuentas Business Premium del sector tecnología, con 100 o más licencias, operación en 3 o más países y facturación superior a USD 100M
personas: valeria-sosa, marta-benitez, raul-quintero, camila-ferreyra
---

# Opportunity: Colaboración en vivo durante las sesiones de trabajo

En las sesiones de trabajo de más de cinco personas, cuando el grupo necesita producir algo juntos (idear, priorizar, editar), quien conduce lo lleva a otra herramienta durante la llamada: el grupo se reparte entre pestañas, hay participantes que no pueden editar la herramienta externa y lo decidido se pasa a mano a un documento después. Es urgente ahora porque el segmento tiene un upgrade a Max de solo 3,1% y en 5 meses se presentan features en CollabCon.

## Segment and personas

Segmento en foco: cuentas Business Premium del sector tecnología, con 100 o más licencias, operación en 3 o más países y facturación superior a USD 100M. Son 12.400 cuentas y 2,1M de licencias, con equipos distribuidos en trabajo remoto o híbrido. Las reuniones las convocan y conducen Team Leads y mandos medios; los participantes sufren el problema de forma secundaria.

- Valeria Sosa (primary) — lo sufre: lleva a su equipo a Miro y Jira durante las reuniones y reconstruye lo decidido los viernes. Está dentro del segmento.
- Marta Benítez (secondary) — lo sufre del lado de quien participa: cuando la planilla es de Google Sheets no puede editarla (IT bloquea la cuenta) y dicta los cambios en voz alta; en un Excel nativo participa sin problema. Está fuera del segmento por sector (manufactura).
- Raúl Quintero (tertiary) — no lo sufre; responde la creencia de viabilidad desde quien propone la renovación. Es la misma fintech que Valeria y está dentro del segmento.
- Camila Ferreyra (negative) — no lo sufre dentro del alcance; es invitada externa con sus propias herramientas y marca el borde de la oportunidad.
- Missing: participante del segmento (secondary), por ejemplo desarrollo o diseño en un equipo distribuido de una tecnológica multinacional.

## Signals

| Signal | Provenance | Source |
|---|---|---|
| El 38% de las reuniones de más de 5 personas del segmento comparte en el chat un enlace a Miro, Mural o FigJam; mientras dura, la actividad en Teams cae | real | Telemetría del segmento — info complementaria del caso, §2 |
| Whiteboard se abre en el 6% de las reuniones del segmento; en la mitad de esas se cierra antes de 2 minutos | real | Telemetría del segmento — info complementaria, §2 |
| "Colaboración durante reuniones" es la 3.ª categoría del portal de feedback: 4.700 solicitudes del segmento en 12 meses (editar un documento entre varios en la llamada, votar o priorizar en vivo, no salir de Teams) | real | Portal de feedback — info complementaria, §2 |
| El 22% de los comentarios negativos post-reunión del segmento menciona la colaboración en vivo ("terminamos en otra herramienta", "la pizarra es difícil de encontrar y nadie la usa", "pierdo tiempo pasando lo que decidimos a un documento") | survey (n no informado) | Encuestas post-reunión — info complementaria, §2 |
| En general, el 29% de las reuniones de más de 5 personas comparte enlaces externos; Whiteboard está en el 5% y las notas en el 8% | real | Brief del caso, §4 |
| En las renovaciones de cuentas grandes, "colaboración" aparece en las conversaciones sobre Max | unverified | Info complementaria, §2 — sin registro de cuántas veces |
| Valeria lleva al equipo a Miro y Jira y reconstruye lo decidido | synthetic | product/personas/valeria-sosa.md |
| Marta no puede editar una planilla de Google Sheets (cuenta bloqueada por IT) y dicta los cambios; en un Excel nativo participa | synthetic | product/personas/marta-benitez.md |
| Raúl solo justificaría Max (~USD 38.400/año) si le permite dar de baja Miro y Slack; finanzas le sugiere bajar a Standard | synthetic | product/personas/raul-quintero.md |

## Business outcome

Comercial.

- **Principal:** tasa de upgrade de Premium a Max en el segmento (hoy 3,1% de las cuentas en 12 meses; el salto cuesta USD 8 por usuario por mes).
- **Secundario:** retención en la renovación.
- Los ingresos por licencia suben como consecuencia del upgrade.

## Constraints

- Presupuesto máximo: USD 5M.
- Fecha: se presentan features en CollabCon dentro de 5 meses (hacia fines de marzo de 2027). Es una fecha que fija los tiempos, no una decisión sobre qué construir.
- Límites para cualquier solución: facilidad de uso, accesibilidad, compatibilidad con Microsoft 365, privacidad y seguridad corporativas, tiempo real e impacto mínimo en el rendimiento de la reunión.

## Beliefs

Referencias a product/overview.md, el único registro de creencias.

- [product] [value] Quienes conducen reuniones sacan al grupo de Teams (Miro, Google Docs, Jira…) porque las herramientas nativas de colaboración en vivo no les alcanzan para el trabajo que hacen en la reunión, y no solo porque ese contenido ya vivía fuera antes de la reunión. — creencia de valor de esta oportunidad.
- [opportunity: colaboracion-en-vivo] [viability] En las cuentas del segmento, la colaboración en vivo durante las reuniones es un motivo con peso propio para pasar de Premium a Max: aparece como razón en al menos 1 de cada 4 conversaciones de renovación o upgrade, y las cuentas donde quienes conducen la reclaman pagarían los USD 8 por usuario por mes.
- Depende de: [product] [viability] La experiencia de Team Leads y mandos medios pesa en la decisión de IT de renovar, subir o bajar de plan; IT no decide solo por precio y paquete de Microsoft 365.

## Research agenda

| Belief | Instrument | Decision it unlocks | By when |
|---|---|---|---|
| [product] [value] Quienes conducen sacan al grupo de Teams porque lo nativo no les alcanza | 1) **Datos propios:** en las reuniones del 38%, ver si el enlace ya estaba en la invitación o en el chat antes de la reunión (el contenido ya vivía afuera) o si aparece por primera vez durante la llamada. 2) `/research-market`: qué hacen Zoom, Meet y Slack con la colaboración en vivo, y cuánto se usan las integraciones de Miro en Teams. 3) `/design-survey` a quienes conducen en el segmento: por qué salen de Teams, con un bloque de opt-in. 4) `/design-interview` con los que hayan dado opt-in, priorizando a quienes probaron Whiteboard y lo abandonaron. | Si la oportunidad sigue como "lo nativo no alcanza para producir juntos" o se reformula como "el contenido vive afuera y hay que traerlo a la reunión". Esto cambia qué alternativas compiten en `/explore-solutions`. | 2026-12-15 |
| [opportunity: colaboracion-en-vivo] [viability] | 1) **Datos propios:** contar en el CRM las menciones de "colaboración" en las conversaciones de renovación y upgrade del segmento de los últimos 12 meses. Hoy no hay registro: hay que etiquetar las notas. 2) **Datos propios:** comparar la tasa de upgrade a Max entre cuentas con mucho y poco uso de pizarras externas. 3) **Datos propios:** comparar en las cuentas del segmento el gasto en pizarras externas con el costo del salto a Max. 4) Conversaciones con compradores (IT o compras) de cuentas del segmento. | Si la oportunidad se persigue para mover el upgrade a Max o solo para la retención; si lo que salga va en Max o en Premium; y si el upgrade se sostiene como reemplazo de herramientas o como valor nuevo. | 2026-12-31 |
| [product] [viability] La experiencia de Team Leads y mandos medios pesa en la decisión de IT (dependencia) | Las mismas conversaciones con compradores: cuánto pesa la opinión de quienes conducen frente al precio y al paquete. | Si conviene apuntar el valor a quien conduce o a IT. | 2026-12-31 |
| Hueco: n de la encuesta post-reunión | **Datos propios:** pedir el n y el período del 22%. | Cuánto peso darle a esa señal. | 2026-11-15 |

## Candidate ideas (not evaluated)

- Herramientas colaborativas integradas en las reuniones (la oportunidad como llegó)
- Edición conjunta de un documento durante la llamada (portal de feedback)
- Votar o priorizar en vivo (portal de feedback)
- Poder hacer una sesión de trabajo sin salir de Teams (portal de feedback)
- Hacer Whiteboard más fácil de encontrar (encuesta post-reunión: "la pizarra es difícil de encontrar")
