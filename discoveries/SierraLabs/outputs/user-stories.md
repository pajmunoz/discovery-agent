# User stories — SierraLabs

Historias del núcleo de valor del MVP: organizar los contactos que ya llegan por
WhatsApp/redes y conectar esa actividad con conversiones reales. Es el dolor que
se repite en dos de las tres personas (Consultora Independiente y Propietario de
Pyme); ver `mvp-canvas.md` para la justificación de alcance.

- **[US-01]** Como consultora independiente o propietario de pyme, quiero
  registrar en un solo lugar los contactos que me escriben, para dejar de
  depender de conversaciones sueltas de WhatsApp y no perder prospectos.
  - Criterios de aceptación:
    - Dado que recibo un mensaje de alguien interesado, cuando lo registro en
      el sistema, entonces queda guardado con su nombre/contacto y la fecha de
      ingreso.
    - Dado un contacto ya registrado, cuando actualizo su estado (nuevo, en
      conversación, cerrado), entonces el sistema refleja ese estado.
  - Fuente: consultora.md, propietario.md

- **[US-02]** Como consultora independiente, quiero recibir un recordatorio
  cuando un contacto lleva varios días sin seguimiento, para no dejar que los
  prospectos "desaparezcan" sin que yo actúe.
  - Criterios de aceptación:
    - Dado un contacto sin actividad registrada por más de N días, cuando se
      cumple ese plazo, entonces el sistema me notifica que debo darle
      seguimiento.
  - Fuente: consultora.md

- **[US-03]** Como consultora independiente o propietario de pyme, quiero saber
  qué canal o publicación originó cada contacto que se convirtió en cliente,
  para decidir dónde enfocar mi esfuerzo de marketing en vez de hacerlo por
  intuición.
  - Criterios de aceptación:
    - Dado que registro el origen de un contacto (p. ej. "publicación X",
      "campaña Y"), cuando ese contacto pasa a estado "cliente", entonces el
      sistema asocia esa conversión a su origen.
    - Dado un rango de fechas, cuando consulto el reporte, entonces veo cuántos
      contactos y cuántas conversiones hubo por cada origen.
  - Fuente: consultora.md, propietario.md

## Fuera del MVP por ahora

No se escriben historias para R-01 a R-04 (mantenimiento del sitio
institucional, hallazgo de información, rendimiento móvil, imagen visual —
Coordinador Administrativo), ni para R-05 (canal propio de generación de leads)
ni R-08 (recordatorio de cadencia de publicación): ninguno se repite entre
personas y no son el núcleo de valor del MVP. Ver `mvp-canvas.md`.
