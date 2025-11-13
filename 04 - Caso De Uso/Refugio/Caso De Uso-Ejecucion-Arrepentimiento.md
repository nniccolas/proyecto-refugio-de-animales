**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso:**

**Actor: Refugio** 

**Precondición:** El adoptante debe tener una adopcion realizada y se debe haber iniciado sesión.

**Camino básico:**

1. El refugio valida en el sistema que el plazo no haya vencido y la adopcion haya sido exitosa.
2. El sistema del refugio valida y ejecuta el arrepentimiento.
3. El refugio recibe el animal y lo marca como devuelto.
4. El sistema elimina la adopcion del refugio y el plazo de devolucion.
5. El refugio vuelve a hacer el proceso de registro con el animal y es registrado como adoptable. 

**Camino alternativo:** 

1. El plazo de arrepentimiento ya vencio.

   1a. El sistema no puede ejecutar el arrepentimiento y se lo comunica al refugio y al adoptante.

2. El refugio no logra validar el arrepentimietno.

   2a. Se muestra un mensaje de error.

3. El animal no es devuelto.
   
   3a. El arrepentimiento se bloquea.

**Escenario de éxito:**

El arrepentimiento es ejecutado a tiempo y con exito.

**Escenario de fracaso:**

El arrepentimiento no es ejecutado a tiempo.

**Post condiciones:**

El animal vuelve al refugio y se marca como adoptable.