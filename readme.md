PARTE 1..............................
![alt text](image.png)

PARTE 2..............................
![alt text](image-1.png)

PARTE 3..............................
UML

Entidades y Atributos
Clasificación

ClasificacionID (PK)

Nombre (ej. PG-13, R)

Género

GeneroID (PK)

Nombre

Película

PeliculaID (PK)

Titulo

DuracionMinutos

ClasificacionID (FK)

GeneroID (FK)

Sala

SalaID (PK)

Nombre

Capacidad

Función

FuncionID (PK)

Fecha

Hora

PeliculaID (FK)

SalaID (FK)

Cliente

ClienteID (PK)

Nombre

Correo

Telefono

MedioPago

MedioPagoID (PK)

Metodo (ej. Tarjeta de Crédito, Efectivo)

Venta

VentaID (PK)

CantidadBoletos

PrecioUnitario

FechaVenta

/MontoTotal (Atributo derivado: CantidadBoletos * PrecioUnitario)

FuncionID (FK)

ClienteID (FK)

MedioPagoID (FK)

