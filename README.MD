```mermaid
graph LR;
  ordersDB[(BD SkyRoute SRL)]
  BD SkyRoute SRL-->Razon Social;
  BD SkyRoute SRL-->Ciudad
  BD SkyRoute SRL-->Realizadas
  Razon Social-->CUIT;
  CUIT-->Correo de Contacto;
  Correo de Contacto-->Clientes;
  Ciudad-->Pais;
  Pais-->Costo Base del Viaje;
  Costo Base del Viaje-->Destinos;
  Realizadas-->Ventas;
```
