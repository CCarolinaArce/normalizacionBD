PARTE 1..............................
![alt text](image.png)

FORMA NORMAL #1:  Lo primero que hacemos es asegurarnos de que cada celda tenga un solo dato, dejando mas en claro que cada registro tenga su propio identificador.

FORMA NORMAL #2:  Aqui colocamos cada cosa en su lugar, empezando desde el fundamento de que cada caracteristica en cada tabla debe depender unicamente de su clave principal o ID. Asi que dividimos cada tabla entidad en su propia tabla y con sus propios atributos y caracteristicas, dejando cada tabla con su propio ID (clave-primaria).

FORMA NORMA #3:

Por ultimo, devidimos las tabla ventas, de las cuales se pueden sacar la tabla pagos y reservaciones, eliminando asi las dependencias transitivas.

PARTE 2..............................
![alt text](image-1.png)

PARTE 3..............................
UML
![alt text](https://cdn.discordapp.com/attachments/
1167558045216288848/1499508753639149770/image.png?ex=69f7081a&is=69f5b69a&hm=b62f91e9d9e21733be160f3e36599794e92d573093ad4f04359457a468b700ae)

Entidades y Atributos
Clasificación

ClasificacionID (PK)git

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

