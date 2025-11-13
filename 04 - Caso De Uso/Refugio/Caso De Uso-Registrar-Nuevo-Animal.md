**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso:**

**Actor: Refugio** 

**Precondición:** Debe haber un nuevo animal rescatado y haber iniciado sesión.

**Camino básico:**

1. El refugio entra en la seccion de animales.
2. El sistema muestra el registro al dia de todos los animales en el refugio.
3. El refugio selecciona la opcion de agregar nuevo animal.
4. El sistema abre al refugio una ventana para ingresar los datos del animal.
5. El refugio registra su nombre, sexo y especie en el sistema, ademas de asignar un alias unico e identificador.
6. El sistema procesa todos los datos, valida que el alias no este repetido y pide numero de corral.
7. El refugio lo situa en un corral y añade el numero del corral en el que esta ubicado.
8. El sistema valida que haya espacio en el corral, que el numero sea correcto y pregunta si lo añade a la lista de adoptables.
9. El refugio evalua su condicion y lo añade a la lista de adoptables, pendiente de adopcion.
10. El sistema culmina el registro y vuelve a la seccion de inicio.

**Camino alternativo:** 

6. El alias ya esta en uso.

   6a. El sistema muestra mensaje de error y vuelve al paso 5.

8. El numero de corral no existe o esta erroneo.

   8a. El sistema muestra mensaje de error y vuelve al paso 7.

8. El corral esta lleno.

   8a. El sistema muestra mensaje de error y vuelve al paso 7.

9. El animal no esta en condiciones de ser adoptado.

   9a. La condicion de adoptable va a estar pendiente. 

**Escenario de éxito:**

El animal es registrado y esperando a ser adoptado.

**Escenario de fracaso:**

El animal es rechazado y no es apto para ser adoptado.

**Post condiciones:**

El animal queda en la lista de adoptables y todos sus datos estan en el sistema.