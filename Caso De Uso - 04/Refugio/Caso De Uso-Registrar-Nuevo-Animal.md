**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso:**

**Actor: Refugio** 

**Precondición:** Debe haber un nuevo animal rescatado y haber iniciado sesión.

**Camino básico:**

1. El refugio entra en la seccion de animales.
2. Selecciona la opcion de agregar nuevo animal.
3. El refugio registra su nombre, sexo y especie en el sistema.
4. El refugio le asigna un alias y lo registra junto con sus datos.
5. El refugio lo situa en un corral y tambien añade el numero del corral en el que esta ubicado.
6. El refugio evalua su condicion y lo añade a la lista de adoptables, pendiente de adopcion.

**Camino alternativo:** 

4. El alias ya esta en uso.

   4a. El sistema muestra mensaje de error y vuelve al paso 2

5. El numero de corral no existe o esta erroneo.

   5a. El sistema muestra mensaje de error y vuelve al paso 3

5. No hay corrales disponibles.

   5a. El sistema muestra mensaje de error y vuelve al paso 3.

6. El animal no esta en condiciones de ser adoptado.

   6a. La condicion de adoptable va a estar pendiente. 

**Escenario de éxito:**

El animal es registrado y esperando a ser adoptado.

**Escenario de fracaso:**

El animal es desaprobado y no apto para ser adoptado.

**Post condiciones:**

El animal queda en la lista de adoptables y todos sus datos estan en el sistema.