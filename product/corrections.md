# Correcciones

Decisiones humanas sobre lo que propuso la IA.

## 2026-10-25 — personas

- **Artefacto:** `personas/jorge-medina.md` (Jorge Medina, Jefe de Operaciones de un centro de distribución, `primary`)
- **Qué propuso la IA:** un set con dos personas `primary` (Valeria Sosa y Jorge Medina), con Jorge cubriendo la creencia 2 desde el lado usuario, la creencia 5 y las cuentas grandes (más de 1.000 licencias).
- **Qué decidió el humano:** descartar a Jorge y dejar a Valeria como única `primary`.
- **Por qué:** "no podemos dejar dos primarias".

## 2026-10-27 — /review-evidence

- Primera revisión de evidencia (cubrió todo `product/` hasta la fecha). Sin correcciones.
- Anotación aplicada: creencia 2 → `weakened` (research secondary + persona sintética de Raúl).

## 2026-10-28 — personas (/derive-personas y revisión con insights)

- **Artefacto:** `personas/marta-benitez.md` (`secondary`)
- **Qué propuso la IA:** el 2026-10-25, Marta en una manufacturera, fuera del segmento; el 2026-10-28, moverla a una SaaS B2B multipaís (soporte) porque las entrevistas muestran el mismo patrón de participante que queda afuera dentro del segmento.
- **Qué decidió el humano:** moverla al segmento. El tipo se mantiene.
- **Por qué:** cierra el hueco "participante del segmento (secondary)" declarado en `opportunities/2026-10-25-1803-colaboracion-en-vivo.md`.

- **Artefacto:** `personas/gabriela-rios.md` (nueva, `source: derived`, `primary`)
- **Qué propuso la IA:** derivar personas de 3 grupos sin representar (maneja el sistema donde ya vive el trabajo, solo puede usar lo nativo, informa en la reunión grande y decide en chico) y sumar evidencia a Valeria Sosa y Marta Benítez.
- **Qué decidió el humano:** derivar solo el grupo "maneja el sistema donde ya vive el trabajo", como `primary`. Luego, sumar evidencia a Valeria, Marta y Raúl.
- **Nota:** el set vuelve a tener dos `primary` (Valeria Sosa y Gabriela Ríos), lo que difiere de la decisión del 2026-10-25 ("no podemos dejar dos primarias").
- **Qué decidió el humano (2026-10-28):** mantener las dos `primary` y reinterpretar la regla del 2026-10-25 como **una `primary` por oportunidad**: Valeria Sosa para `colaboracion-en-vivo`, Gabriela Ríos para `decisiones-sin-ejecutar`.
