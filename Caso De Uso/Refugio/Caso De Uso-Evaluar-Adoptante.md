**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso:**

**Actor: Refugio** 

**Precondición:** El adoptante debe haber enviado la solcitud de adopción.

**Camino básico:**

1. El refugio valida todos los datos personales del adoptante.
2. El refugio toma los datos del adoptante y valida que no haya adoptado recientemente.
3. El refugio valida que no tenga antecedentes penales ni causas, en especial las vinculadas a maltrato animal.
4. El refugio realiza un cuestionario a el adoptante, evalua sus ingresos, su condicion de vida, y su estado psicofisico.
5. El refugio pide prueba de todo lo que el potencial adoptante responde (Facturas, acta de nacimiento, analisis psicofisico, titulo de propiedad y dni fisico).
6. El refugio realiza una inspeccion al hogar del adoptante, evaluando que cada centimetro sea adecuado para el animal.
7. El refugio aprueba las condiciones del potencial adoptante.
8. El refugio le muestra los animales disponibles.

**Camino alternativo:** 

1. Alguno de los datos del adoptante son incorrectos, incompletos o erróneos.

   1a. El sistema advierte al adoptante.

2. El adoptante ya ha adoptado recientemente y no puede adoptar por el momento.

   2a. Se bloquea el proceso de adopción y se registra el rechazo.

3. El adoptante tiene antecedentes penales vinculados.
   
   3a. Se bloquea el proceso de adopcion y se registra el rechazo.

4. El adoptante no cumple con algunas de las condiciones requeridas para hospedar el animal.
   
   4a. Se bloquea el proceso de adopcion y se registra el rechazo.

5. La documentacion y el testimonio del adoptante no coinciden.
  
   5a. Se bloquea el proceso de adopcion y se registra el rechazo.

6. El hogar del adoptante no esta en condiciones.
  
   6a. Se bloquea el proceso de adopcion y se registra el rechazo.

**Escenario de éxito:**

El adoptante es aprobado y apto para adoptar.

**Escenario de fracaso:**

El adoptante es desaprobado y no apto para adoptar.

**Post condiciones:**

El adoptante ya esta apto para adoptar.