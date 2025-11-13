**Francisco Lencina, Nicolas Bruno y Alexis Gomez**

**Caso de uso:**

**Actor:** Adoptante

**Precondición:** El adoptante debe haber aprobado las evaluaciones de adopcion, teniendo aptitud para adoptar.

**Camino básico:**

1. El sistema muestra el registro de los animales disponibles al dia(alias, nombre, especie, sexo).
2. El adoptante selecciona el animal disponible.
3. El sistema avisa la adopción, la registra en el sistema, eliminando de la lista de adoptables al animal y genera el período de arrepentimiento.
4. El adoptante recibe al animal y culmina la adopción.

**Camino alternativo:**

2a. El adoptante no encuentra un animal que le guste.

   2a. La adopcion no ocurre.

**Escenario de éxito:**

El adoptante está conforme con su adopción, decide no devolver al animal hasta que cierra el período de arrepentimiento.

**Escenario de fracaso:**

Se arrepiente antes/luego de la adopción.

**Post condiciones:**

El animal queda marcado como adoptado, se lo elimina de la lista de adoptables de manera temporalmente indefinida (en caso de devolucion) y la adopcion junto con el adoptante quedan registrados en el refugio.