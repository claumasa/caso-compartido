---
opportunity: colaboracion-en-vivo
beliefs: "[product] [value] Quienes conducen sacan al grupo de Teams porque lo nativo no les alcanza; [opportunity: colaboracion-en-vivo] [viability] (insumo lateral)"
status: draft
date: 2026-10-27
---

# Survey: Por qué quienes conducen sacan al grupo de Teams durante las sesiones de trabajo

- **Learning goals:**
  1. **Dónde nace el contenido.** En la última sesión de trabajo de 5 o más personas, ¿el tablero o documento externo ya existía antes de la reunión o se creó durante la llamada? ¿Qué pasó con él después? → Define si la oportunidad sigue como "lo nativo no alcanza para producir juntos" o se reformula como "traer a la reunión el contenido que vive afuera". Cambia qué alternativas compiten en `/explore-solutions`.
  2. **Si conocen, probaron o abandonaron lo nativo** (Whiteboard en modo Colaborar, notas colaborativas, Excel Live, Polls, apps en el stage) y por qué. → Separa un problema de descubrimiento ("no sé que existe") de uno de capacidad ("lo probé y no alcanza").
  3. **Qué impide participar.** Externos o invitados, límite de personas, cuentas bloqueadas, celular. → Dice si los límites conocidos de lo nativo (Excel Live con ≤25 personas y sin externos, apps en el stage sin invitados) explican la salida.
  4. **Asientos pagos de pizarras externas.** Cuántos asientos y quién los paga. → Insumo lateral para comparar ese gasto con el salto de USD 8 (creencia de viabilidad). Es una señal débil: quien conduce muchas veces no conoce el gasto; el dato firme sale de las conversaciones con compradores.
- **Target respondents:** Team Leads y mandos medios que condujeron al menos una sesión de trabajo de 5 o más personas en los últimos 30 días (sesión de trabajo = el grupo tenía que producir algo juntos: idear, priorizar o editar; no solo informar), en cuentas que usan Teams para reuniones, del sector tecnología, con 100 o más empleados y operación en 3 o más países. Persona de referencia: Valeria Sosa (primary). El plan Business Premium no se pregunta porque quien conduce no lo sabe: en el canal in-product se toma de telemetría (campo oculto); en comunidades queda como limitación.
- **Segmentos de análisis:** (A) quienes en la última sesión llevaron al grupo a una herramienta externa (Q1 = c) y (B) quienes no (Q1 = a, b).
- **Estimated length:** 5 de screening + 11 preguntas (5 condicionales) + 3 de opt-in; ~5 min.
- **Idioma:** español neutro con tuteo (el segmento reparte equipos entre AR, CO, MX y otros países).

## Screening

> En el canal in-product, S2 a S5 se completan desde telemetría con campos ocultos y no se muestran. En comunidades se muestran todas.

S1. En los últimos 30 días, ¿condujiste al menos una reunión de 5 o más personas en la que el grupo tenía que producir algo juntos (por ejemplo, idear, priorizar o editar un documento)? [single choice]
   - Sí, conduje al menos una
   - No; solo participé en reuniones que condujo otra persona
   - No; las reuniones que conduje fueron solo informativas
   - No conduje reuniones de 5 o más personas

   → descalificar si no es "Sí"

S2. ¿Tu equipo usa Microsoft Teams para sus reuniones? [single choice]
   - Sí, para todas o casi todas
   - Sí, para algunas
   - No

   → descalificar si "No"

S3. ¿A qué sector pertenece la empresa donde trabajas? [single choice]
   - Software o servicios de tecnología
   - Fintech o servicios financieros digitales
   - Telecomunicaciones
   - Banca o seguros tradicionales
   - Manufactura o industria
   - Comercio o retail
   - Otro

   → descalificar si no es una de las tres primeras

S4. ¿Cuántas personas trabajan en tu empresa? [single choice]
   - Menos de 100
   - Entre 100 y 999
   - 1.000 o más
   - No sé

   → descalificar si "Menos de 100"; "No sé" sigue y se marca para revisar

S5. ¿En cuántos países opera tu empresa? [single choice]
   - 1
   - 2
   - 3 o más
   - No sé

   → descalificar si 1 o 2; "No sé" sigue y se marca para revisar

## Questions

> Q1–Q4 se refieren a una sola sesión concreta (la última) para anclar en comportamiento y no en opinión general.

Piensa en **la última reunión de 5 o más personas que condujiste** en la que el grupo tenía que producir algo juntos.

Q1. En esa reunión, ¿dónde trabajó el grupo lo que había que producir? [single choice]
   - a) En herramientas dentro de Teams (pizarra, notas de la reunión, una planilla o documento abierto en la reunión, encuestas)
   - b) Compartí pantalla y yo (u otra persona) anoté lo que el grupo decía
   - c) En una herramienta externa a Teams que el grupo abrió durante la reunión (por ejemplo Miro, Mural, FigJam, Google Docs, Jira, Notion)
   - d) Otro: ___

   > Goal: 1 — define los segmentos A (c) y B (a, b). Separa "presento y alguien anota" (b), la alternativa de costo cero que el research señaló como posiblemente dominante.

Q2. *(solo si Q1 = c)* ¿Qué tipo de herramienta externa usaron? [multiple choice]
   - Pizarra o tablero visual (Miro, Mural, FigJam, Lucidspark)
   - Documento o planilla de Google (Docs, Sheets, Slides)
   - Gestor de tareas o tickets (Jira, Asana, Linear, Trello)
   - Documento o wiki (Notion, Confluence, Coda)
   - Otra: ___

   > Goal: 1 — permite cortar Q3 y Q4 por tipo: una pizarra que reemplaza a Whiteboard no es lo mismo que un backlog que vive en Jira.

Q3. *(solo si Q1 = c)* ¿Cuándo se había creado ese tablero o documento? [single choice]
   - Ya existía y el equipo lo venía usando antes de esa reunión
   - Lo creé (o alguien lo creó) antes de la reunión, especialmente para ella
   - Es una copia de una plantilla o del tablero de la reunión anterior
   - Se creó durante la reunión
   - No sé

   > Goal: 1 — **la pregunta central de la creencia de valor.** "Ya existía" apoya "el contenido vive afuera"; "durante", "especialmente para ella" o "copia de una plantilla" apoyan "lo nativo no alcanza" (la plantilla trae la estructura, el contenido nace en la sesión; criterio alineado con la falsificación del objetivo 1 del guion de entrevista). "Copia de una plantilla" se reporta también por separado como señal de costumbre. Se cruza con la medición en datos propios (enlace en la invitación o el chat antes de la reunión).

Q4. *(solo si Q1 = c)* Después de la reunión, ¿qué pasó con ese tablero o documento? [single choice]
   - El equipo lo siguió usando en la misma herramienta
   - Pasamos lo decidido a otro lugar (documento, Jira, chat de Teams, Slack)
   - No se volvió a usar
   - No sé

   > Goal: 1 — mide persistencia, la segunda explicación del research ("Miro gana porque el tablero queda y es el estándar del equipo").

Q5. ¿Qué tan familiarizado estás con cada una de estas funciones de Teams? [matriz, una respuesta por fila]

   Filas:
   - Pizarra (Whiteboard) en modo "Colaborar", donde todos pueden dibujar y escribir
   - Notas de la reunión colaborativas (botón "Notas")
   - Excel Live (todos editan una planilla dentro de la reunión)
   - Encuestas en la reunión (Polls)
   - Abrir Miro, Mural o Lucid dentro de la reunión ("Compartir en el escenario")

   Columnas (iguales para todas las filas):
   - No sabía que existía
   - Sabía que existía, pero nunca la usé en una reunión
   - La usé y dejé de usarla
   - La uso al menos una vez por mes

   > Goal: 2 — descubrimiento vs. capacidad. "No sabía que existía" apoya el problema de descubrimiento; "La usé y dejé de usarla" (sobre todo en Whiteboard) apoya "no alcanza" y marca candidatos prioritarios para entrevista.

Q6. *(solo si marcó "La usé y dejé de usarla" en alguna fila de Q5)* ¿Por qué dejaste de usarla? Marca todas las que apliquen. [multiple choice]
   - Le faltaba algo que necesitaba para el trabajo de la reunión
   - Se trababa o andaba lenta con varias personas editando
   - Algunos participantes no podían entrar o editar
   - Después no encontraba dónde había quedado
   - El equipo ya trabajaba en otra herramienta
   - IT no la habilitó o la restringió
   - Era difícil de encontrar o de abrir durante la reunión
   - Otro: ___

   > Goal: 2 — las opciones salen de las quejas ya registradas (G2 y foros, la encuesta post-reunión, Valeria). Es general y no por función, para mantener la encuesta corta; el detalle por función queda para la entrevista.

Q7. En el último mes, en las sesiones de trabajo que condujiste, ¿cuántas veces alguien **no pudo editar** lo que el grupo estaba trabajando y tuvo que dictar o mandar sus aportes por otro medio? [single choice]
   - Nunca
   - 1 vez
   - 2 o 3 veces
   - 4 veces o más
   - No sé

   > Goal: 3 — frecuencia observada, no opinión. Es el problema de Marta visto desde quien conduce.

Q8. *(solo si Q7 = 1 vez o más)* ¿Por qué no podía editar? Marca todas las que apliquen. [multiple choice]
   - Era externo o invitado a la organización
   - Su cuenta o IT bloquea esa herramienta
   - No tenía licencia o asiento en esa herramienta
   - Estaba conectado desde el celular
   - Había más personas que las que la herramienta permite editar a la vez
   - No sé
   - Otro: ___

   > Goal: 3 — mapea contra los límites conocidos: Excel Live (≤25, sin externos ni invitados, no desde el celular) y apps en el stage (sin invitados).

Q9. Pensando en Miro, Mural, FigJam, Lucidspark u otra pizarra externa: ¿cuántas personas de tu equipo tienen un **asiento pago**? [single choice]
   - Ninguna; usamos el plan gratuito o no usamos pizarras externas
   - Solo yo (o solo quienes facilitan)
   - Algunas personas del equipo
   - Todo el equipo
   - No sé

   > Goal: 4 — "solo quienes facilitan" contra "todo el equipo" decide si el gasto externo se compara con USD 8 por facilitador o por toda la plantilla.

Q10. *(solo si Q9 = solo yo, algunas o todo el equipo)* ¿Quién paga esos asientos? [single choice]
   - IT o compras, de forma centralizada
   - El presupuesto de mi área o equipo
   - Yo, con tarjeta personal o pidiendo reembolso
   - No sé

   > Goal: 4 + dependencia [product] [viability] — si el gasto sale del presupuesto del área y no de IT, es una pista (débil) de que el área tiene peso en las herramientas.

Q11. ¿Qué es lo más difícil de lograr que un grupo produzca algo juntos durante una reunión de Teams? [open, optional]

   > Goal: 1 y 2 — la única pregunta abierta. Capta explicaciones que las opciones no previeron; se codifica por tema en `/analyze-survey`.

D1. ¿Cuál describe mejor tu rol? [single choice]
   - Team Lead o líder técnico
   - Gerente o jefe de área
   - Product Manager o Product Owner
   - Scrum Master o Agile Coach
   - Otro: ___

   > Goal: corte de análisis — dentro del segmento, compara a quienes conducen por rol (Scrum Masters y Agile Coaches llegan sobre todo por el canal 2).

## Screening + opt-in (interview recruitment)

> Prioridad para `/design-interview`: quienes marcaron "La usé y dejé de usarla" en Whiteboard (Q5), y después quienes respondieron Q3 = "se creó durante la reunión". Entre los dos grupos, primero quienes contradicen la creencia (Q3 = "ya existía").

R1. ¿Trabajas en Microsoft o en una empresa que hace herramientas de colaboración o reuniones (por ejemplo Miro, Mural, Figma, Slack, Zoom, Google)? [yes / no] → no es candidato si "sí"

R2. En el último mes, ¿cuántas sesiones de trabajo de 5 o más personas condujiste? [single choice: 1 / 2 a 4 / 5 o más] → no es candidato si "1"

R3. ¿Aceptarías una conversación de 30 minutos por videollamada sobre cómo conduces estas sesiones? [yes / no]

R4. *(solo si R3 = sí)* ¿Cómo podemos contactarte? (email o LinkedIn) [open, optional]

## Distribution

| Channel | Who it reaches | Approx. reach | Link |
|---|---|---|---|
| In-product en Teams, muestra A: invitación al terminar una reunión de 5 o más personas en la que se compartió en el chat un enlace a una herramienta externa | Organizadores del segmento (cuentas Business Premium, tecnología, 100 o más licencias, 3 o más países, filtrado por telemetría) que sacan al grupo afuera. Canal propio: sobrerrepresenta a quienes siguen usando Teams para reuniones; subrepresenta a equipos que ya se mudaron a Slack, Zoom o Meet. Además, una invitación justo después de la reunión levanta el recuerdo de esa sesión (bueno para Q1–Q4) | unknown — pedir a telemetría cuántos organizadores del segmento cumplen el criterio por semana | `?canal=inapp-externo` |
| In-product en Teams, muestra B: igual, pero en reuniones de 5 o más personas sin enlace externo | Organizadores del segmento que no salen de Teams (o anotan en pantalla compartida). Mismo sesgo de canal propio | unknown | `?canal=inapp-nativo` |
| Comunidades ágiles y de facilitación: grupos de LinkedIn y espacios de Slack de Scrum Masters, Agile Coaches y Product Leads (nombrar cada grupo antes de publicar) | Perfiles como Valeria que conducen desde Miro o Slack, incluidos los que el in-product no ve. Sobrerrepresenta a entusiastas de Miro y a facilitadores profesionales; el segmento de la cuenta no se puede verificar y depende de S3 a S5 (autodeclarado) | unknown — y se espera que una parte importante quede afuera en el screening por sector, tamaño o países | `?canal=comunidad-{nombre}`, un parámetro por grupo |

- **Target n:** al menos 30 completas por segmento de análisis: **A** (llevaron al grupo afuera, Q1 = c) y **B** (no lo hicieron, Q1 = a/b). Las dos muestras in-product existen para llenar A y B, pero el segmento se asigna por la respuesta a Q1, no por el canal. Menos de 30 en A o B = resultados direccionales. Para Q6 (solo quienes abandonaron algo) y Q3 cortada por tipo de herramienta, el n va a ser menor: direccional por diseño.
- **Factibilidad:** el alcance de los tres canales es unknown, así que no se puede verificar antes de publicar que lleguen al n. El in-product es el que más probablemente lo cubra (12.400 cuentas en el segmento). Las comunidades son el único canal que llega a quienes ya se fueron, pero con screening estricto pueden aportar pocas respuestas válidas: si en la primera revisión tienen menos de 10 válidas, se lee como límite de la muestra y no se presenta el resultado como representativo del segmento.
- **First review:** 2026-11-17
- **Closes:** abierta hasta llegar al n objetivo, con tope el 2026-11-24 (deja unas tres semanas para entrevistas antes de la fecha de decisión del 2026-12-15).
