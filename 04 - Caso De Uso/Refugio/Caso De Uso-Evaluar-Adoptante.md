**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso: Evaluacion del adoptante**

**Actor: Refugio** 

**Precondición:** El adoptante debe haber enviado la solcitud de adopción y se debe haber iniciado sesión.

**Camino básico:**

1. El refugio recibe todos los datos personales del adoptante y consulta con el sistema que no haya adoptado recientemente.
2. El sistema aprueba que no haya adoptado recientemente y valida que los datos sean correctos y existan.
3. El refugio valida que no tenga antecedentes penales ni causas, en especial las vinculadas a maltrato animal.
4. El sistema aprueba que no tiene antecedentes ni causas.
5. El refugio realiza un cuestionario a el adoptante, en el que evalua sus condiciones.
6. El sistema devuelve todo lo respondido por el adoptante.
7. El refugio aprueba las condiciones del potencial adoptante.
8. El sistema le muestra los animales disponibles al adoptante.

**Camino alternativo:** 

2. Alguno de los datos del adoptante son incorrectos, incompletos o erróneos.

   2a. El sistema advierte al refugio.

2. El adoptante ya ha adoptado recientemente y no puede adoptar por el momento.

   2a. El sistema bloquea el proceso de adopción y advierte al refugio.

4. El adoptante tiene antecedentes penales vinculados.
   
   4a. El sistma bloquea el proceso de adopcion y advierte al refugio.

6. El adoptante no cumple con algunas de las condiciones requeridas para hospedar el animal.
   
   6a. Se bloquea el proceso de adopcion y se registra el rechazo.

**Escenario de éxito:**

El adoptante es aprobado y apto para adoptar.

**Escenario de fracaso:**

El adoptante es desaprobado y no apto para adoptar.

**Post condiciones:**

El adoptante ya esta apto para adoptar.