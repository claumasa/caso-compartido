---
date: 2026-10-28
source: survey
survey: product/surveys/2026-10-21-1944-colaboracion-en-vivo-fuera-de-teams.md
results: product/surveys/2026-10-25-1800-respuestas-colaboracion-en-vivo-fuera-de-teams.csv
n: 215 válidas (210 completas + 5 parciales) de 249 iniciadas
opportunity: colaboracion-en-vivo
---

# Análisis de encuesta: trabajo colaborativo fuera de Teams en reuniones de más de 5

## Denominador y límites

| | Email (canal propio) | Panel externo | Total |
|---|---|---|---|
| Iniciadas | 85 | 164 | 249 |
| Descalificadas | 8 | 26 (15 por firmografía, 6 contratistas) | 34 |
| Válidas (completas + parciales) | 77 | 138 | 215 |
| Salen de Teams (Q1 ≠ "En ninguna") | 66 | 121 | 187 — meta ≥150 ✓ |
| "En ninguna" | 11 | 17 | 28 — meta ≥30 ✗, **direccional** |

- **Tasa de respuesta del email: no calculable.** El alcance quedó `unknown` en el diseño. El email aportó 77 válidas, lejos de las ~150 que el chequeo de alcance le pedía; la meta de "salen" se cumplió gracias al panel.
- **Panel:** cuota completa. Firmografía autodeclarada: no se puede verificar plan Business Premium ni facturación.
- **Período:** 21 al 23/10/2026.
- **Calidad:** 9 respuestas completadas en menos de 90 segundos (mediana: 233 s). Se mantienen porque son consistentes. Hay 4 pares de respuestas abiertas casi idénticas (R-046/R-170, R-207/R-224, R-077/R-196, R-009/R-143) que son de personas distintas, con otro país y otro contacto. Se mantienen, con esta nota.
- **Las preguntas de detalle (Q2 a Q9) son sobre "la última reunión"**, no sobre todas. Los porcentajes describen reuniones recordadas, no la población de reuniones.
- **Diferencia entre canales.** El panel sale de Teams con más frecuencia ("más de la mitad" o "todas": 40% contra 22% en email). También trabaja más sobre artefactos que ya existían (60% contra 42%), usa más dashboards (22% contra 8%) y registra menos en Teams (7% contra 23%). Coincide con el sesgo declarado: el email sobrerrepresenta a quienes están conformes con Teams. Los hallazgos se sostienen en los dos canales, pero son **más fuertes en el panel**.

Con n ≥ 30 por canal y 187 en el segmento que sale, los totales son orientativos. Los subgrupos de menos de 30 (España, "En ninguna", app dentro de Teams) son direccionales.

## O1. Origen del artefacto

**Creíamos:** quienes conducen sacan al grupo de Teams porque lo nativo no alcanza para el trabajo de la reunión, y no solo porque el contenido ya vivía afuera.

**Los datos (Q4, n=187):**
- Ya existía antes de la reunión: **53%** (100). De ellos, 95 se siguieron usando después.
- Se creó para la reunión: **40%** (74). 45 se siguieron usando y 29 no se volvieron a usar.
- No lo sé: 7% (13).

Al cruzar Q4 con Q2, Q5 y Q6 aparecen **dos patrones distintos**:

| | Preexistente (≈53%) | Creado para la reunión (≈40%) |
|---|---|---|
| Herramientas | Dashboards 78% preexistentes, Confluence 77%, Jira 73%, Notion 52%, Google Docs 53% | Miro 87% creados, Slido 78%, FigJam 77%, Mural 75% |
| Qué hace el grupo | Revisar datos y señalar algo 57%, editar entre varios 38%, anotar decisiones 38%, actualizar tickets 35% | Votar o priorizar 54%, aportar ideas 49%, agrupar ideas 49% |
| Tardan ≥5 min en estar todos dentro | 15% | 45% |

La intensidad no cambia el patrón: entre quienes salen "en todas" las reuniones, el 62% trabaja sobre algo preexistente (n=16, direccional).

**Decisión:** la creencia se **debilita**. La mayoría de las salidas van a sistemas de registro donde el trabajo ya vive, y ahí el problema es de integración. Queda un 40% donde el grupo sí produce junto en un lienzo creado para la ocasión, y ahí se concentra la fricción. La oportunidad tiene dos ramas que compiten en `/explore-solutions`:
- **traer a la reunión** lo que ya vive afuera (revisar datos, actualizar tickets);
- **un espacio nativo para converger** (aportar, agrupar, votar).

## O2. Costo de acceso

**Creíamos:** hacen falta 5 minutos o más para que todos entren, y eso le pasa al Team Lead en reuniones internas.

**Los datos (Q6 a Q8, n≈185):**
- Tardan 5 minutos o más: **29%** (51/173, sin "No lo sé"). Menos de 2 minutos: 49%.
- Al menos un participante no logró entrar y miró la pantalla de otro: **51%**.
- Hubo externos en el 22% de las reuniones.

| | Sin externos (n=137) | Con externos (n=41) |
|---|---|---|
| ≥5 min hasta que todos entran | 18% | **61%** |
| ≥1 participante afuera | 46% | 63% |

- **Cómo llegaron (Q3):** enlace pegado en el chat 54%, ya la tenían abierta 21%, pantalla compartida y cada uno la abrió 16%, app dentro de Teams 8%. Para la telemetría, que solo ve enlaces pegados en el chat, el 46% de las salidas pasa inadvertido.
- **Señal direccional (n=15):** quienes abrieron la herramienta como app dentro de Teams reportan ≥1 participante afuera en 13 de 15 casos, más que con enlace pegado (50%).

**Decisión:** el umbral de 5 minutos **no se sostiene para las reuniones internas**: le pasa a menos de 1 de cada 5. Donde se cumple es en reuniones con externos, que son otro segmento (consultores y agencias), como el diseño anticipaba. El dolor de que alguien quede afuera sí es transversal (46% aun sin externos), aunque sea de 1 persona.

## O3. Qué se hace afuera y dónde queda la decisión

**Actividades (Q5, n=185):** votar o priorizar 39%, editar un documento entre varios 35%, revisar datos o métricas 34%, anotar decisiones 32%, aportar ideas 30%, actualizar tickets 25%, agrupar ideas 23%, dibujar un diagrama 14%. "Otro" 5% (revisar incidentes, planning poker o estimación, roadmap, presupuesto): la lista estaba completa.

**Dónde quedó lo decidido (Q9, n=182, múltiple):**
- No quedó registrado en ningún lado: **24%**
- En un chat fuera de Teams: 23%
- En Jira u otro gestor: 23%
- **Otro: 18%** (supera el umbral del 15%; ver abajo)
- En la misma herramienta externa: 15%
- En el chat o las notas de Teams: 13%
- En un documento de actas: 12%
- En un correo: 10%
- No se tomaron decisiones: 7%

**"Otro" codificado (32 respuestas):**
- Resumen o recap de IA, o transcripción: **22**. Unas 11 mencionan un defecto sin que se les pregunte: no distingue lo decidido, mezcla todo, tiene errores, nadie lo lee, falta quién hace qué.
- Grabación: 4.
- Otros (OneNote, cuaderno, nota de voz, "en la cabeza"): 6.

A la lista le faltaba "en el resumen o recap automático de la reunión". Si la encuesta se repite, hay que agregarla.

> "En el recap de Copilot, que resume todo pero no distingue lo decidido" (R-097)
> "En el recap pero le faltaba quién hacía qué" (R-231)

**Lo más difícil para trabajar juntos y decidir (Q11, 95 respuestas; un tema principal por respuesta):**

| Tema | Menciones | Cita |
|---|---|---|
| Registro y seguimiento de lo decidido (quién hace qué, entendimiento común, por qué se decidió). Incluye el subtema trabajo manual post-reunión: pasar del tablero a Jira o armar el acta (4) | 17 | "Muchas veces creemos que decidimos y en realidad cada uno entendió algo distinto. Lo descubrimos en la siguiente reunión" (R-099) · "Después de la planning me paso casi una hora pasando lo del FigJam a Jira" (R-024) |
| Continuidad entre reuniones / encontrar lo anterior | 12 | "Cada reunión es una isla. Lo que se trabajó en la anterior está en otro lado" (R-166) |
| Converger, votar, priorizar | 12 | "Votar. Usamos reacciones en el chat pero nadie sabe cuántos votaron ni qué ganó" (R-053) |
| Acceso a la herramienta externa (externos, permisos, SSO, celular, licencias por filial) | 12 | "Los permisos del Miro. Siempre hay alguien que no puede editar y pierde los primeros 10 minutos" (R-244) |
| Participación desigual (hablan los mismos, cámaras apagadas, juniors callados) | 9 | "Hay 12 personas y opinan 3, el resto escucha o está en otra cosa" (R-049) |
| Límites de Whiteboard o de lo nativo | 9 | "Probamos la whiteboard de Teams hace un tiempo, no tenía plantillas ni votación y a la retro siguiente no la encontramos. Desde ahí todo en Miro" (R-113) |
| Compliance o normativa que limita herramientas externas | 3 (+2 en Q12) | "Compliance no nos deja meter datos de clientes en Miro, así que o lo hacemos en Teams o no se hace. Y en Teams cuesta" (R-190) |
| Resumen de IA que no separa decisiones de conversación | 3 | "Marca como decisión cosas que eran solo ideas, lo tengo que revisar siempre" (R-153) |
| Fuera de alcance (cultura de reuniones, husos horarios, idioma, audio, rendimiento) | 14 | "Honestamente la mayoría de estas reuniones podrían ser un mail" (R-157) |
| Sin problema / no aplica | 3 | — |

**Decisión:**
- El dolor más mencionado **no ocurre durante la reunión sino después**: registro, seguimiento y continuidad suman 29 de 95 menciones. A eso se suma el 24% sin registro en Q9.
- Le siguen converger y votar (12) y acceso (12).
- Cualquier solución tiene que cubrir *votar o priorizar* y *dejar la decisión registrada y encontrable para la reunión siguiente*.
- La IA tiene un lugar concreto: separar lo decidido de lo conversado y asignar dueño. Hoy los recaps lo intentan y fallan, según los propios usuarios.

## O4. Conocimiento y uso de lo nativo

**Q10 (n=210):**

| | No sabía | Sabe, nunca usó | Usó y dejó | Usa (algunas + mayoría) |
|---|---|---|---|---|
| Whiteboard | 8% | 27% | **43%** | 21% |
| Notas de la reunión (Loop) | **31%** | 28% | 14% | 27% |
| Apps de otras herramientas en la reunión | **40%** | 28% | 9% | 22% |
| Resumen o asistente de IA | 12% | 39% | 13% | **36%** |

Por qué abandonan Whiteboard (menciones espontáneas en Q11 y Q12):
- no se encuentra después, porque queda colgada del chat de esa reunión (5);
- no tiene votación, agrupación ni plantillas (4);
- cuesta abrirla durante la reunión (2);
- se traba con más de 8 personas (2);
- se ve mal en pantallas chicas (1).

**Decisión:** en Whiteboard el problema es de **capacidad y persistencia**, no de descubrimiento: casi la mitad la probó y la dejó. "Hacerla más fácil de encontrar", la idea candidata de la oportunidad, ataca el problema menor. En notas y apps dentro de la reunión el problema sí es de **descubrimiento** (31% y 40% no sabían que existían).

## Cortes adicionales (direccionales)

- **España (n=27; identifica cuentas con operación en el EEE):** 55% creó el artefacto para la reunión (resto: 38%), y 30% usa Whiteboard en algunas reuniones (resto: 15%). Coincide con las menciones espontáneas de compliance y normativa europea (R-143, R-173, R-190). Puede existir un subsegmento donde lo nativo no compite con Miro porque Miro no está permitido.
- **Grupo "En ninguna" (n=28; Q12, 16 respuestas):** hablan y alguien anota en OneNote, en el chat o en un Excel compartido (6); votan a mano alzada, con reacciones o con Forms (4); deciden antes por mail o en grupos más chicos (3); usan notas o Whiteboard de Teams (3). Dos no salen por compliance, no por elección.
- **Frecuencia de reuniones (R2):** no cambia la distribución de Q1.

## Insights priorizados

1. **Salir de Teams es mayormente integración, no colaboración.** El 53% de las salidas van a artefactos preexistentes (Jira, Confluence, dashboards) para revisar y actualizar. Los lienzos creados para la reunión son el 40% y concentran la fricción: 45% tarda 5 minutos o más, contra 15% en los preexistentes. → Partir la oportunidad en dos ramas antes de `/explore-solutions`.
2. **La decisión se pierde después de la reunión.** 24% sin registro, 29/95 menciones de registro y continuidad, y recaps de IA que "no distinguen lo decidido". → Candidata a oportunidad propia, o a criterio obligatorio de cualquier solución de esta oportunidad.
3. **Whiteboard se prueba y se abandona (43%)** por falta de votación y plantillas y porque no persiste entre reuniones. → Descartar "hacerla más fácil de encontrar" como idea principal.
4. **La fricción de 5 minutos o más es sobre todo de reuniones con externos** (61% contra 18%). → Queda fuera del segmento del Team Lead interno. En reuniones internas, el dolor de acceso es "1 persona se queda afuera".
5. **Compliance (UE) puede crear un subsegmento cautivo de lo nativo.** → Validar en entrevistas; si se confirma, es el primer lugar donde probar una solución nativa.

### "Por qué" que la encuesta no responde (candidatos para entrevistas)

- ¿Por qué se abre el artefacto preexistente *dentro* de la reunión en vez de revisarlo antes? ¿Qué parte de "revisar juntos" no resuelve compartir pantalla?
- ¿Por qué la app dentro de Teams deja más gente afuera que pegar un enlace? (n=15)
- ¿Qué tendría que tener un recap para que se confíe en él como registro de decisiones?
- ¿Qué faltó en Whiteboard en el momento exacto en que volvieron a Miro?
- En cuentas con compliance, ¿cómo deciden hoy y cuánto les cuesta?

## Pool de reclutamiento

De 77 que aceptaron una conversación, **64 son aptos** (no son IT y conducen 2 o más reuniones de más de 5 por semana). 10 ya fueron entrevistados el 26/10 (ver `interviews/`): R-024, R-036, R-097, R-113, R-143, R-151, R-153, R-170, R-196, R-224. 6 dejaron el contacto vacío y no se pueden reclutar: R-076, R-110, R-132, R-194, R-227, R-245.

Quedan **48 reclutables**. Los contactos están en el CSV de resultados. Etiqueta "contradice" según el criterio del diseño: Q1 "En ninguna", Q4 "Ya existía…" o Q6 menos de 2 minutos.

**Contradicen la creencia (entrevistar primero):**
- "En ninguna" (sin herramienta externa): R-046, R-085, R-088, R-120, R-242. Con compliance o sin poder usar externas: R-009, R-135.
- Preexistente y acceso rápido: R-057, R-094, R-102, R-128, R-131, R-144, R-176, R-180, R-229, R-234, R-235, R-240, R-247.
- Preexistente con acceso lento o desconocido: R-042, R-065, R-086, R-159, R-171, R-201, R-228, R-238, R-244.
- Lienzo creado con acceso rápido: R-013, R-074, R-089, R-090, R-093, R-230. R-173 suma normativa europea.

**Confirman la creencia:** R-006, R-011, R-019, R-031, R-038, R-070, R-077, R-099, R-101, R-103, R-204, R-205.
