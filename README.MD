```mermaid
graph LR;
  ordersDB[(Reserva)]
  BDSkyRouteSRL-->RazonSocial;
  BDSkyRouteSRL-->Ciudad
  BDSkyRouteSRL-->Realizadas
  NombreyApellido-->DatosdeContacto;
  DatosdeContacto-->Clientes;
  Clientes-->Reserva;
  Ciudad-->Pais;
  Pais-->CostoBasedelViaje;
  CostoBasedelViaje-->Destinos;
  Destinos-->Reserva;
  Cantidad de Pasajeros-->Ventas;
  Ventas-->Reserva;
  Dia-->Mes;
  Mes-->Fecha;
  Fecha-->Reserva;
```
