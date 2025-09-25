@startchen  
left to right direction

entity Refugio {  
}  
entity Animal {  
Id  
Tipo  
Nombre  
Corral {  
Id_Corral  
}  
entity Adopcion {  
Estado  
Devolución {  
Plazo  
}  
entity Adoptante {  
Aptitud_Adop  
Telefono  
Nombre  
Direccion  
}

relationship Registra {  
}

relationship Incluye {  
}

relationship Solicita {  
}

Refugio -- Registra  
Registra -- Animal  
Adopcion -- Incluye  
Incluye -- Animal  
Adoptante -- Solicita  
Solicita -- Adopcion  
@endchen  
