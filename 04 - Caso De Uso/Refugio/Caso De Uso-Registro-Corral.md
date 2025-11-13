**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso: Registrar Corrales**

**Actor: Refugio** 

**Precondición:** Debe haber iniciado sesión.

**Camino básico:**

1. El refugio entra en la seccion de animales.
2. El sistema muestra el registro de todos los animales al dia.
3. El refugio entra en un espacio para corrales.
4. El sistema muestra todos los corrales, si estan ocupados o no y cuantos animales hay.
5. El refugio selecciona la opcion agregar nuevo corral.
6. El sistema otorga una ventana para el registro de corrales.
7. El refugio agrega el numero del nuevo corral.
8. El sistema corrobora que no exista el numero, registra el corral y da la opcion en caso de haber animales dentro.
9. El refugio responde negativo y culmina el registro.

**Camino alternativo:** 

6. No hay espacio en el sistema para corrales nuevos.
   
   6a. El sistema muestra mensaje de error y da la opcion de borrar corrales.

8. El numero de corral ya esta en uso.

   8a. El sistema muestra mensaje de error y vuelve al paso 7.

9. El corral ya tiene animales dentro.

   9a. El refugio responde afirmativo y da los animales que estan dentro por alias, el sistema lo añade al registro del corral y de los animales.

**Escenario de éxito:**

El corral es registrado correctamente.

**Escenario de fracaso:**

No hay espacio en el sistema para agregar un nuevo corral.

**Post condiciones:**

El corral queda correctamente registrado y disponible para agregar animales.