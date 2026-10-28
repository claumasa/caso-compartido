---
date: 2026-10-28
source: real
opportunity: colaboracion-en-vivo
guide: product/interview-guides/2026-10-21-2030-colaboracion-en-vivo-fuera-de-teams.md
sources:
  - product/interviews/2026-10-26-0900-javier-molina.md (real · R-097 · España)
  - product/interviews/2026-10-26-0930-martina-rojas.md (real · R-224 · Chile)
  - product/interviews/2026-10-26-1000-diego-paredes.md (real · R-036 · Perú)
  - product/interviews/2026-10-26-1000-tomas-aguirre.md (real · R-113 · Argentina)
  - product/interviews/2026-10-26-1100-andres-quintero.md (real · R-170 · Colombia)
  - product/interviews/2026-10-26-1200-sofia-martinez.md (real · R-151 · México)
  - product/interviews/2026-10-26-1400-paula-benitez.md (real · R-153 · Argentina)
  - product/interviews/2026-10-26-1500-valeria-castro.md (real · R-024 · Colombia)
  - product/interviews/2026-10-26-1600-lucia-fernandez.md (real · R-143 · España)
  - product/interviews/2026-10-26-1700-ricardo-salinas.md (real · R-196 · México)
n: 10 entrevistas de exploración (26/10/2026), ~30 min cada una
---

# Insights de entrevistas: colaboración en vivo en reuniones de más de 5

Diez personas que conducen reuniones de más de cinco participantes, reclutadas de la encuesta. Seis vienen del panel y cuatro del email. Los insights están ordenados por impacto. La recurrencia (cuántas de las 10 personas lo mencionan) es la señal principal de prioridad.

## 1. La decisión se pierde entre el final de la reunión y el sistema donde se ejecuta, y cuesta semanas de trabajo

Las 10 personas contaron un caso concreto en el que algo decidido en la reunión terminó hecho distinto o no se hizo. En 7 casos hay un costo cuantificado: una release movida, entre 1 y 2 semanas de trabajo descartado, un cliente esperando 4 días, presupuesto de campaña gastado de más, 2 días de arreglos más una guardia de fin de semana. Lo que se pierde no es el *qué*, que suele quedar en algún lado. Se pierde el **quién**: hay 4 casos de "cada uno pensó que lo hacía el otro". Y se pierde el **por qué**, que queda en un hilo de Slack o en un comentario resuelto. Hoy el cierre depende de una sola persona, la que conduce, que pasa entre 20 y 60 minutos después de cada reunión reescribiendo en Jira, en un correo o en Slack. Si no lo hace, nadie lo hace. **Implicación:** cualquier solución de la oportunidad tiene que dejar, antes de que termine la reunión, una lista de decisiones con responsable, fecha y motivo, confirmada por el grupo. Esa lista tiene que llegar al sistema donde vive el trabajo (Jira, Confluence, correo) sin que nadie la transcriba.

> Evidencia: "En el recap quedó como 'se habló de la API de geocercas'. El equipo de México leyó el recap […] Entregaron dos semanas tarde. Nosotros tuvimos que mover una release entera. Desde entonces, después de cada planning, reescribo el recap. Media hora […] decisión, responsable, fecha. […] Es trabajo mío, nadie más lo hace." — Javier Molina
>
> "En mi correo quedó, pero el líder de Ecuador entendió que lo pasaba yo, y yo entendí que lo pasaba él. Nadie lo pasó. […] El cliente esperó cuatro días." — Andrés Quintero
>
> "El qué queda en Jira. El problema es el por qué." — Martina Rojas
>
> "Lo que nos falla es cómo se cierra la reunión: que quede claro qué se decidió, que lo sepan todos, incluso los que no hablaron." — Sofía Martínez

**Recurrencia:** 10/10 con un incidente; 8/10 hacen trabajo manual después de la reunión (Sofía, 2 min; Valeria, ~60 min). También aparecen casos de responsable ambiguo (Andrés, Lucía, Ricardo, Tomás) y de motivo perdido (Martina, Sofía).

## 2. El recap de IA no sirve como registro de decisiones: no separa lo decidido de lo conversado y no ve los artefactos

6 de 10 usan o probaron el resumen automático (Copilot) y ninguno lo usa tal cual como registro. Fallan tres cosas, y cada una se repite: (a) **mezcla decisión con conversación**, o inventa decisiones, como el caso de Paula, donde una idea apareció como decidida y se perdió una semana de dos desarrolladores; (b) **no asigna responsable**; (c) **no ve lo que pasó fuera del audio**: la votación en FigJam, el filtro del dashboard, el hilo de Slack. Quienes lo siguen usando le agregaron una revisión manual de entre 10 y 30 minutos ("trabajo que yo pensaba que me estaba ahorrando"). **Implicación:** el lugar de la IA no es resumir. Es *proponer* decisiones con responsable durante la reunión, para que quien conduce las confirme en el momento, y tomar como fuente el artefacto sobre el que se trabajó, no solo la transcripción. La confirmación humana no es un parche: es el hábito que Paula ya construyó.

> Evidencia: "Marca como decisión cosas que eran solo ideas. […] El squad de Porto Alegre lo leyó y arrancó con la integración. […] Perdimos más o menos una semana de dos desarrolladores. Desde entonces reviso el resumen antes de mandarlo, siempre." — Paula Benítez
>
> "Como la votación fue en el tablero, el resumen decía algo como 'se discutieron prioridades'. Pues sí, gracias." — Valeria Castro
>
> "Dice 'se revisaron las ventas de Chile' y no dice con qué filtro ni qué gráfico." — Diego Paredes
>
> "Me resumió la conversación, no las decisiones." — Martina Rojas

**Recurrencia:** 6/10 (Javier, Martina, Diego, Paula, Valeria, Lucía). Confirma el patrón de la encuesta (Q9 "Otro": 22 menciones de recap, ~11 con defectos espontáneos).

## 3. Lo que se trabaja en la reunión tiene que sobrevivir a la reunión; Whiteboard y las notas se pierden porque quedan atadas a una instancia del calendario

Quienes eligen Miro no lo hacen por las funciones de lienzo. Lo hacen por la **continuidad**: un tablero por trimestre con un frame por sesión, para revisar los acuerdos de la vez anterior. Whiteboard y las notas de la reunión fallan justo ahí. Quedan colgadas del chat o de la invitación de *esa* reunión, y cuando la serie se recrea, se reprograma o se convoca de nuevo, desaparecen. Lucía, que por compliance solo puede usar lo nativo, perdió el trabajo de la primera sesión y una incidencia quedó sin responsable una semana. Esta falla de persistencia es la que hace abandonar la herramienta para siempre. Las otras (no hay votación ni plantillas, se traba con más de 10 personas, agrupar es lento, no se lee en pantallas de 13") se toleran una vez. **Implicación:** antes de agregar funciones al lienzo nativo, hay que anclarlo al equipo, al canal o a la serie, con historial entre sesiones. Ganar en "hacerla más fácil de encontrar dentro de la reunión" no resuelve que no se encuentre *después*.

> Evidencia: "A las dos semanas, para la retro siguiente, fui a buscarla y no estaba. Quedó colgada del chat de esa reunión, y justo en el medio se había recreado la serie […] Perdí los acuerdos, así de simple. Ahí dije: listo, volvemos a Miro." — Tomás Aguirre
>
> "Esa continuidad es la razón por la que estamos en Miro. Si tuviera que empezar de cero cada vez, perdería el hilo." — Tomás Aguirre
>
> "Queda atada al chat de esa reunión, y como la segunda sesión fue una convocatoria nueva, pues ahí no aparecía. […] Desde entonces hago captura de pantalla al terminar y la pego en Confluence." — Lucía Fernández
>
> "Lo único que me molesta es cuando reprogramamos. […] Las notas quedaron en la otra, en la original." — Paula Benítez (sobre las notas de la reunión, la herramienta nativa que sí usa)

**Recurrencia:** 6/10 probaron Whiteboard (Javier, Tomás, Sofía, Lucía, Ricardo, Valeria). 5 la abandonaron y Lucía la sigue usando porque no tiene alternativa. 4/10 perdieron trabajo nativo al buscarlo después (Tomás, Sofía, Lucía, Paula). 2/10 eligen Miro explícitamente por la continuidad entre sesiones (Javier, Tomás).

## 4. Sobre artefactos que ya existen, el dolor no es salir de Teams: es no poder señalar y que una sola persona maneje mientras el resto dicta

Cuando el trabajo vive en Jira, Power BI, Excel o Figma, nadie quiere moverlo ("el backlog vive en Jira, no tiene sentido sacarlo"). La fricción está en la pantalla compartida: el grupo no puede señalar ("la de abajo, no, la otra"), cada uno mira una vista distinta (Diego perdió 10 o 15 minutos discutiendo números con filtros diferentes) y todo pasa por quien maneja. El costo no son solo minutos. Andrés cerró el ticket equivocado y al cliente le llegó la notificación de cierre. **Implicación:** la rama de "integración" de la oportunidad no necesita un lienzo nuevo. Necesita que, sobre lo que ya se comparte, los participantes puedan **señalar y anotar** y que todos vean **la misma vista**. Es una capacidad nativa que no compite con Jira ni con Miro y que sirve aunque el artefacto viva afuera.

> Evidencia: "Lo peor es cuando edito la fila equivocada. […] Al cliente le llegó la notificación de cierre y el caso seguía abierto. […] Si pudieran apuntar con algo, me dirían 'esta' y listo." — Andrés Quintero
>
> "Uno decía 'las ventas bajaron ocho por ciento' y otro 'no, a mí me sale que subieron'. Y estábamos hablando de números distintos sin darnos cuenta." — Diego Paredes
>
> "Es 'el botón de arriba, no, el otro, el de la derecha, más abajo'. Y yo moviendo el mouse a ver si le atino. Perdemos un montón en eso." — Valeria Castro

**Recurrencia:** 4/10 mencionan no poder señalar (Andrés, Diego, Tomás, Valeria). 6/10 describen a alguien que dicta a quien maneja porque no puede o no se anima a tocar (Javier, Martina, Tomás, Andrés, Lucía, Valeria/Gloria).

## 5. Converger con más de 8 personas termina en que decide quien conduce, y el desacuerdo aparece después; pero no todos quieren decidir en la reunión grande

La votación nativa se improvisa con reacciones o con la mano levantada, y nadie confía en el conteo (Andrés, Lucía, Ricardo). En FigJam nada impide votar dos veces (Valeria). Cuando hay empate o discusión, quien conduce corta y decide (6/10). Quienes no hablaron (juniors, remotos, quienes no lograron entrar al tablero) expresan el desacuerdo días después y por otro canal. Pero hay un segmento opuesto: Paula y Ricardo sacan a propósito las decisiones de la reunión grande y las toman en grupos de 3 o 4 ("dar la sensación de que todos participaron"). **Implicación:** una votación nativa confiable (un voto por persona, resultado visible) y una forma de registrar objeciones de quienes no hablan tienen valor para el segmento que *construye* en la reunión. No hay que suponerlo para todas las reuniones de más de 5. Las reuniones "de informar y alinear" son otro trabajo, cuyo dolor está en el punto 1 y no en converger.

> Evidencia: "Como a la semana, me la encuentro en un café de la oficina y me dice que no estaba de acuerdo con sacar la reprogramación de citas por WhatsApp […] Una objeción importante, y yo ni me enteré en la reunión." — Valeria Castro
>
> "Contar reacciones de nueve personas con la mitad sin cámara… a ver, funciona, pero no te fías del todo del número." — Lucía Fernández
>
> "Sé que hay gente que arma tableros con votaciones y todo eso con veinte personas. A mí no me parece que eso sea decidir. Es dar la sensación de que todos participaron." — Paula Benítez

**Recurrencia:** 6/10 deciden solos al final (Javier, Martina, Tomás, Andrés, Sofía, Lucía). 3/10 mencionan desacuerdo posterior (Martina, Sofía, Valeria). 2/10 no deciden en reuniones grandes por diseño (Paula, Ricardo).

## Otras señales (no llegan a insight)

- **El acceso falla también en reuniones internas**, por fragmentación de cuentas y no solo con externos. Los casos: una instancia de Miro por filial (Javier, más de 10 min), licencias de invitado de solo lectura (Tomás, 5 a 7 min) y cuentas personales de Google en el navegador (Valeria, 6 a 8 min). Matiza el O2 de la encuesta (18% de reuniones internas con 5 min o más): el costo existe, concentrado en lienzos creados para la reunión. Donde hay SSO sobre un artefacto preexistente, el acceso tiene "cero fricción" (Martina, Diego). La consecuencia que más preocupa no son los minutos sino que **quien queda afuera no opina** (Valeria, Javier).
- **Compliance:** 1 caso claro (Lucía, España: "lo nativo es lo único que tengo"; aprobar una herramienta nueva lleva meses). Javier, también en España, sí tiene Miro aprobado. El subsegmento cautivo de lo nativo existe, pero no se explica por país, sino por el tipo de dato (datos de clientes).
- **Descubrimiento:** Andrés no conocía las notas de la reunión, Valeria no conocía Whiteboard, Ricardo no conocía las apps dentro de la reunión y Diego no conocía Loop. Coincide con la encuesta: en notas y apps el problema es de descubrimiento; en Whiteboard, de capacidad y persistencia.
- **Fuera de alcance:** cantidad de reuniones (Ricardo: 27 h por semana). Andrés, en cambio, atribuye la duración (1,5 h que "debería durar cuarenta minutos") a las fricciones de este estudio.
- **Saltar entre ventanas:** Javier lo señala como un costo que dura toda la reunión, no solo el arranque ("pierdes el vídeo, vuelves, ya pasó el tema"). Hay 1 mención; vale la pena preguntarlo en las próximas entrevistas.

## Calidad de los datos

- Tomás admitió que exageró en la encuesta: dijo que sale de Teams en todas sus reuniones y no es así. Las respuestas de frecuencia de Q1 pueden estar infladas.
- En la entrevista de Paula hay fechas inconsistentes: habla del "review de noviembre" y de notas del "lunes 13", pero la entrevista es del 26/10. Probablemente se refiere a septiembre u octubre. No cambia el contenido.
- Las 10 personas fueron reclutadas entre quienes salen de Teams. Nadie del grupo "En ninguna" fue entrevistado todavía. Los contactos que ofrecieron (Fernanda, Carla, Mariana, Natalia, Andrés de CS) cubren justamente ese perfil, el de quienes conducen sin tablero.
