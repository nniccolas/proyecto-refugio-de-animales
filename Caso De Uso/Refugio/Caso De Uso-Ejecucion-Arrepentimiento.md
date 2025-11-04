**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso:**

**Actor: Refugio** 

**Precondición:** El adoptante debe tener una adopcion realizada.

**Camino básico:**

1. El refugio recibe el mensaje de arrepentimiento de parte del adoptante junto con su motivo.
2. El refugio valida en el sistema que el plazo no haya vencido y la adopcion haya sido exitosa.
3. El sistema del refugio valida y registra el arrepentimiento.
4. El refugio recibe el animal y lo marca como devuelto.
5. El sistema elimina la adopcion del refugio y el plazo de devolucion.
6. El refugio vuelve a hacer el proceso de registro con el animal y es registrado como adoptable. 

**Camino alternativo:** 

1. El plazo de arrepentimiento ya vencio.

   1a. El sistema no puede ejecutar el arrepentimiento y se lo comunica al refugio y al adoptante.

2. El refugio no logra validar el arrepentimietno.

   2a. Se muestra un mensaje de error.

3. El animal no es devuelto.
   
   3a. El arrepentimiento se bloquea y el refugio se comunica con el adoptante.

**Escenario de éxito:**

El arrepentimiento es ejecutado a tiempo y con exito.

**Escenario de fracaso:**

El arrepentimiento no es ejecutado a tiempo.

**Post condiciones:**

El animal vuelve al refugio y se marca como adoptable.