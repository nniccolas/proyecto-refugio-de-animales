**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso:**

**Actor primario:** Empleado

**Actor secundario:** Adoptante

**Precondición:** El adoptante debe tener las condiciones para aprobar la evaluación.

**Camino básico:**

1. El empleado inicia sesión en la aplicación.
1. Se registra la evaluación del interesado en adoptar y sus datos personales.
1. Una vez aprobada su evaluación el sistema muestra los datos de los animales disponibles (nombre, id, corral).
1. El adoptante selecciona el animal disponible.
1. Se confirma la adopción.
1. El sistema elimina de la lista de adoptables al animal.
1. Se genera un período de arrepentimiento.

**Camino alternativo:** 

1. El empleado no puede iniciar sesión (credenciales incorrectas). 

   1a. El sistema muestra un mensaje de error

1. Alguno de los datos del adoptante son incorrectos, incompletos o erróneos.

   2a. El sistema advierte al empleado

1. El adoptante ya ha adoptado recientemente y no puede adoptar por el momento.

   2a. Se bloquea el proceso de adopción y se registra el intento fallido

**Escenario de éxito:**

El adoptante está conforme con su adopción, decide no devolver al animal hasta que cierra el período de arrepentimiento.

**Escenario de fracaso:**

Se arrepiente antes/luego de la confirmación y adopción.

**Post condiciones:**

El animal queda marcado como adoptado, se lo elimina de la lista de adoptables de manera temporalmente indefinida (en caso de devolucion) y la adopcion junto con el adoptante quedan registrados en la base de datos.
