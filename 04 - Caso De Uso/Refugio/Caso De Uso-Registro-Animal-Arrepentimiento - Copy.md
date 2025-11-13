**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso: Registrar Animal Devuelto**

**Actor: Refugio** 

**Precondición:** Debe haber un animal devuelto por arrepentimiento y haber iniciado sesión.

**Camino básico:**

1. El refugio entra en la seccion de animales.
2. El sistema muestra el registro de todos los animales al dia.
3. El refugio busca al animal por su alias y lo marca como devuelto.
4. El sistema elimina la adopción, el plazo de devolucion y pide un nuevo numero de corral.
5. El refugio lo situa en un corral nuevo y agrega el numero de corral.
6. El sistema corrobora el numero de corral y da la opcion de marcarlo como adoptable.
7. El refugio evalua al animal y lo marca como adoptable.
8. El sistema lo añade a la seccion de adoptables y culmina el registro.

**Camino alternativo:** 

6. El numero de corral no existe o esta erroneo.

   6a. El sistema muestra mensaje de error y vuelve al paso 5.

6. El corral esta lleno.

   6a. El sistema muestra mensaje de error y vuelve al paso 3.

7. El animal no esta en condiciones de ser adoptado.

   7a. La condicion de adoptable va a estar pendiente. 

**Escenario de éxito:**

El animal es registrado y esperando a ser adoptado nuevamente.

**Escenario de fracaso:**

El animal no esta apto para ser adoptado.

**Post condiciones:**

El animal queda en la lista de adoptables.