Francisco Lencina, Alexis Gomez y Nicolas Bruno

**Diccionario de datos:**

Registro: IDAnimal + nombre + corral
Animal: nombre + tipo_Animal [ gato | perro | ave | tortuga | cuis ]
Adopci�n : IDadoptante + fecha_Adopcion + estado_Adopcion 
Devoluci�n: periodo + fecha_Devolucion

| Nombre      | Descripci�n                            | Longitud | Tipo       | Dominio  |
|-------------|----------------------------------------|----------|------------|----------|
| IDAnimal    | identificador del animal               | 10       | int        | continuo |
| nombre      | nombre del animal                      | 10       | String     | discreto |
| corral      | corral asignado a los animales         | 3        | String     | discreto |
| tipo_Animal | tipo de animal                         | 10       | String     | discreto |
| IDadoptante | identificador del adoptante            | 10       | int        | continuo |
| fecha_Adop  | fecha de adopci�n                      | -        | date-time  | continuo |
| estado_Adop | estado de la adopci�n (adoptado        | -        |    bool    | discreto |
|             |  + disponible)                         |          |            |          |
| periodo     | d�as de devoluci�n disponibles         | 14       | int        | discreto |
| fecha_Devol | fecha de la devoluci�n                 | -        | date-time  | continuo |
|-----------------------------------------------------------------------------------------|