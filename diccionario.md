**Francisco Lencina, Alexis Gomez y Nicolas Bruno**

**Diccionario de datos:**

Registro: IDAnimal + nombre + corral

Animal: nombre + tipo_Animal [ gato | perro | ave | tortuga | cuis ]

Adopción : IDadoptante + fecha_Adopcion + estado_Adopcion 

Devolución: periodo + fecha_Devolucion

| Nombre      | Descripción                            | Longitud | Tipo       | Dominio  |
|-------------|----------------------------------------|----------|------------|----------|
| IDAnimal    | identificador del animal               | 10       | int        | continuo |
| nombre      | nombre del animal                      | 10       | String     | discreto |
| corral      | corral asignado a los animales         | 3        | String     | discreto |
| tipo_Animal | tipo de animal                         | 10       | String     | discreto |
| IDadoptante | identificador del adoptante            | 10       | int        | continuo |
| fecha_Adop  | fecha de adopción                      | -        | date-time  | continuo |
| estado_Adop | estado de la adopción (adoptado + disponible) | - |    bool    | discreto |
| periodo     | días de devolución disponibles         | 14       | int        | discreto |
| fecha_Devol | fecha de la devolución                 | -        | date-time  | continuo |
