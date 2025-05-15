**[Francisco Lencina, Alexis Gomez y Nicolas Bruno]{.mark}**

**Diccionario de datos:**

Registro: ID + nombre + corral

Animal: nombre + tipoA \[ gato \| perro \| ave \| tortuga \| cuis \]

Adopciòn : IDadoptante + fechaA + estado

Devoluciòn: periodo + fechaD

  ---------------------------------------------------------------------------
  Nombre         Descripciòn     Longitud       Tipo           Dominio
  -------------- --------------- -------------- -------------- --------------
  ID             identificador   10             Int            continuo
                 del animal                                    

  nombre         nombre del      10             String         discreto
                 animal                                        

  corral         corral asignado 3              String         discreto
                 a los animales                                

  tipoA          tipo de animal  10             String         discreto

  IDadoptante    identificador   10             Int            continuo
                 del adoptante                                 

  fechaA         fecha de        \-             data-time      continuo
                 adopciòn                                      

  estadoA        estado de la    \-             bool           discreto
                 adopciòn                                      
                 (adoptado +                                   
                 disponible)                                   

  periodo        días de         14             int            discreto
                 devolución                                    
                 disponibles                                   

  fechaD         fecha de la     \-             data-time      continuo
                 devoluciòn                                    
  ---------------------------------------------------------------------------
