**Francisco Lencina  y Nicolas Bruno**

**Regla de negocio:**

**Hechos:** Cada animal tiene un número de identificación único, un nombre y un corral asignado.

Cada corral tiene una identificación única (Ej: A1, B2).

Las personas interesadas en adoptar deben pasar una evaluación previa.

Cuando un animal es adoptado, su registro es eliminado del sistema.

Si el adoptante se arrepiente dentro del tiempo permitido, el animal puede ser devuelto al refugio.

**Restricciones**: No puede haber dos animales ni corrales con el mismo número de identificación.

Un animal solo puede estar asignado a un único corral a la vez tampoco conserva su anterior número de identificación ni su corral original.

No se permite la adopción si el interesado no aprueba la evaluación.

**Acción disparadora:** Al registrar una solicitud de adopción se evalúa al interesado.

Después de registrar un nuevo animal o al devolver uno automáticamente se le asigna corral.

Al completar el proceso de adopción se elimina el registro del animal

Si el adoptante se arrepiente dentro del plazo establecido se devuelve la mascota.

**Cálculos:** La disponibilidad del corral se calcula en base a la ocupación actual; un corral ocupado no puede ser asignado a otro animal.

La cantidad de animales por corral se puede contabilizar para análisis o alertas (por ejemplo, sobrepoblación).

El promedio de adopciones exitosas por mes se puede calcular para reportes y estadísticas.

**Inferencias:** Si un corral está ocupado no puede asignarse a otro animal hasta estar libre.

Si el arrepentimiento se produce dentro del tiempo permitido el animal puede reingresar al sistema con nuevo ID y nuevo corral.

Si se devuelve una mascota y no hay corrales disponibles debe colocarse en lista de espera o corral temporal.

Si un animal ha sido adoptado y no se produce arrepentimiento dentro del plazo su registro no puede recuperarse.
