@startchen
left to right direction

entity Refugio {
  Localizacion
  Nombre
  Contacto
  Responsable
  Horario
}

entity Empleado {
  Nombre
  Apellido
  Rol
  Telefono
}

entity Veterinario {
  Id_Vet
  Nombre
  Matricula
  Telefono
}

entity Animal {
  Alias
  Tipo
  Nombre
  Raza
  Sexo
}

entity Corral {
  Id_Corral
}

entity Adopcion {
  Estado
  Fecha
}

entity Devolución {
  Plazo
  Motivo
}

entity Adoptante {
  Nombre
  Telefono
  Direccion
  Aptitud_Adop
}

relationship Registra {
}

relationship Incluye {
}

relationship Situado {
}

relationship Solicita {
}

relationship Contiene {
}

relationship Contrata {
}

relationship Atiende {
}

relationship Cuenta_Con {
}


Refugio -- Registra
Registra -- Animal

Refugio -- Contrata
Contrata -- Empleado

Refugio -- Cuenta_Con
Cuenta_Con -- Veterinario

Veterinario -- Atiende
Atiende -- Animal

Animal -- Situado
Situado -- Corral

Adopcion -- Incluye
Incluye -- Animal

Adopcion -- Contiene
Contiene -- Devolución

Adoptante -- Solicita
Solicita -- Adopcion

@endchen