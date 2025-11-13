**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso: Inicio De Sesión**

**Actor: Refugio** 

**Precondición:** Se debe estar ya registrado en el sistema.

**Camino básico:**

1. El empleado ingresa su DNI.
2. El empleado ingresa su contraseña.
3. El sistema verifica los datos y permite el acceso al sistema, mostrando un mensaje de "Bienvenido".

**Camino alternativo:** 

3. El empleado no encuentra al empleado en el sistema.

   3a. El sistema muestra un mensaje de error y vuelve al paso 1.

3. Alguno de los campos es incorrecto.

   4a. El sistema muestra mensaje de error y vuelve al paso 1.

**Escenario de éxito:**

El empleado ingresa exitosamente al sistema.

**Escenario de fracaso:**

El sistema rechaza al empleado.

**Post condiciones:**

El empleado ya puede realizar sus tareas.