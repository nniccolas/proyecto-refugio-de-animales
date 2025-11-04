**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso:**

**Actor: Refugio** 

**Precondición:** Debe haber un nuevo animal rescatado.

**Camino básico:**

1. El refugio registra su nombre, sexo y especie en el sistema.
2. El refugio le asigna un alias y lo registra junto con sus datos.
3. El refugio lo situa en un corral y tambien añade el numero identificatorio del corral en el que esta.
4. El refugio evalua su condicion lo añade a la lista de adoptables, pendiente de adopcion.

**Camino alternativo:** 

2. El alias ya esta en uso.

   2a. El sistema muestra mensaje de error y vuelve al paso 2

3. El numero de corral no existe o esta erroneo.

   3a. El sistema muestra mensaje de error y vuelve al paso 3

3. No hay corrales disponibles.

   3a. El sistema muestra mensaje de error y vuelve al paso 3.

4. El animal no esta en condiciones de ser adoptado.

   4a. La condicion de adoptable va a estar pendiente. 

**Escenario de éxito:**

El animal es registrado y esperando a ser adoptado.

**Escenario de fracaso:**

El animal es desaprobado y no apto para ser adoptado.

**Post condiciones:**

El animal queda en la lista de adoptables y todos sus datos estan en el sistema.