#Francisco Lencina  y Nicolas Bruno#
**Regla de negocio:**
1. Hechos: Cada animal tiene un n�mero de identificaci�n �nico, un nombre y un corral asignado.
Cada corral tiene una identificaci�n �nica (Ej: A1, B2).
Las personas interesadas en adoptar deben pasar una evaluaci�n previa.
Cuando un animal es adoptado, su registro es eliminado del sistema.
Si el adoptante se arrepiente dentro del tiempo permitido, el animal puede ser devuelto al refugio.
2. Restricciones: No puede haber dos animales ni corrales con el mismo n�mero de identificaci�n.
Un animal solo puede estar asignado a un �nico corral a la vez tampoco conserva su anterior n�mero de identificaci�n ni su corral original.
No se permite la adopci�n si el interesado no aprueba la evaluaci�n.
3. Acci�n disparadora: Al registrar una solicitud de adopci�n se eval�a al interesado.
Despu�s de registrar un nuevo animal o al devolver uno autom�ticamente se le asigna corral.
Si el adoptante se arrepiente dentro del plazo establecido se devuelve la mascota.
4. C�lculos: La disponibilidad del corral se calcula en base a la ocupaci�n actual; un corral ocupado no puede ser asignado a otro animal.
La cantidad de animales por corral se puede contabilizar para an�lisis o alertas (por ejemplo, sobrepoblaci�n).
El promedio de adopciones exitosas por mes se puede calcular para reportes y estad�sticas.
5. Inferencias: Si no hay corrales disponibles, entonces el sistema debe rechazar autom�ticamente nuevas admisiones de animales.
 Si un animal es adoptado y luego devuelto, su anterior corral puede ser reutilizado, pero no necesariamente para �l mismo.