**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso:**

**Actor: Refugio** 

**Precondición:** Debe haber un nuevo empleado contratado y se debe iniciar sesion en el sistema.

**Camino básico:**

1. El refugio ingresa en la seccion de empleados.
2. El refugio registra los datos personales y academicos del empleado, junto con su rol y puesto en la empresa.
3. En caso de querer adoptar se adjunta la aptitud del adoptante.
4. El sistema valida los datos del empleado.
5. El empleado queda registrado y habilitado para operar en el sistema.

**Camino alternativo:** 

3. El empleado no esta interesado o no es apto para adoptar hasta en un futuro cercano.

   3a. El sistema lo registra sin problema y continua con el paso 4.

4. Los datos son erroneos o incorrectos o incompletos.

   4a. El sistema muestra mensaje de error y vuelve al paso 2.

**Escenario de éxito:**

El empleado es registrado y habilitado correctamente.

**Escenario de fracaso:**

El sistema rechaza al empleado.

**Post condiciones:**

El empleado puede iniciar sesion y todos sus datos estan dentro del sistema (ya forma parte del refugio).