**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso:**

**Actor:** Adoptante

**Precondición:** El adoptante debe tener una adopcion realizada.

**Camino básico:**
1. El adoptante comunica su arrepentimiento con el refugio.
2. El sistema valida y registra el arrepentimiento.
3. El adoptante devuelve el animal.
4. El sistema elimina la adopcion de su registro y el plazo de devolucion.

**Camino alternativo:** 

1. El plazo de arrepentimiento ya vencio.

   2a. El sistema no puede ejecutar el arrepentimiento y se lo comunica al adoptante

2. El sistema no logra validar el arrepentimiento.

   2a. Se muestra un mensaje de error

3. El animal no es devuelto
   
   3a. El Arrepentimiento se bloquea y el sistema se comunica con el adoptante

**Escenario de éxito:**

El adoptante logra ejecutar el arrepentimiento a tiempo.

**Escenario de fracaso:**

El adoptante no logra ejecutar el arrepentimiento a tiempo.

**Post condiciones:**

El animal vuelve a el refugio y se marca como adoptable