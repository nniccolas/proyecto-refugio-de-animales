**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso:**

**Actor: Refugio** 

**Precondición:** Debe haber un animal devuelto por arrepentimiento y haber iniciado sesión.

**Camino básico:**

1. El refugio busca el registro del animal y lo marca como devuelto.
2. El sistema elimina la adopcion y el plazo de devolucion.
3. El refugio lo situa en un corral nuevo y lo marca como adoptable nuevamente si esta en condiciones.

**Camino alternativo:** 

1. El alias ya esta en uso.

   2a. El sistema muestra mensaje de error y vuelve al paso 1.

1. El numero de corral no existe o esta erroneo.

   3a. El sistema muestra mensaje de error y vuelve al paso 3

3. No hay corrales disponibles.

   3a. El sistema muestra mensaje de error y vuelve al paso 3.

3. El animal no esta en condiciones de ser adoptado.

   3a. La condicion de adoptable va a estar pendiente. 

**Escenario de éxito:**

El animal es registrado y esperando a ser adoptado nuevamente.

**Escenario de fracaso:**

El animal no esta apto para ser adoptado.

**Post condiciones:**

El animal queda en la lista de adoptables.