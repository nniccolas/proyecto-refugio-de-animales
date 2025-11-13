**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso: Registrar empleado entrante.**

**Actor: Refugio** 

**Precondición:** Debe haber un nuevo empleado contratado y se debe iniciar sesion en el sistema.

**Camino básico:**

1. El refugio ingresa en la seccion de empleados.
2. El sistema muestra toda la lista de los empleados actuales.
3. El refugio ingresa en registrar nuevo empleado.
4. El sistema le otorga una ventana para ingresar todos los datos del empleado.
5. El refugio da los datos personales y academicos del empleado, junto con su rol y puesto en la empresa, mas su contraseña de inicio de sesión.
6. El sistema valida los datos del empleado.
7. El empleado queda registrado y habilitado para operar en el sistema.

**Camino alternativo:** 

5. El empleado esta interesado y es apto para adoptar en un futuro cercano.

   5a. El sistema registra su aptitud y continua con el registro.

6. Los datos son erroneos o incorrectos o incompletos.

   6a. El sistema muestra mensaje de error y vuelve al paso 5.

**Escenario de éxito:**

El empleado es registrado y habilitado correctamente para iniciar sesión.

**Escenario de fracaso:**

El sistema rechaza al empleado.

**Post condiciones:**

El empleado puede iniciar sesion y todos sus datos estan dentro del sistema (ya forma parte del refugio).