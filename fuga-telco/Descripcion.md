# Fuga clientes Telco

## Descripción
Los datos de fuga de clientes de Telco contienen información sobre una empresa de telecomunicaciones que proporciona servicios de Telefonía e Internet. 
El objetivo es identificar que clientes se van a fugar. Se incluyen datos demográficos importantes para cada cliente, los servicios contratados, métodos y montos de pago. Finalmente se indica si el cliente se fuga al final de un periodo.

## Atributos
- `ID`: identificador del cliente
- `Sexo`: sexo del cliente
- `CiudadanoSenior`: indica si el cliente es mayor a 65 años (si/no)
- `Partner`: si el cliente pertenece a la categoría "Partner" (si/no)
- `Dependientes`: si el cliente vive con algún dependiente: si, no. Los dependientes pueden ser hijos, padres, abuelos, etc.
- `Antiguedad`: nº de meses que el cliente ha estado en la compañía
- `Telefonia`: indica si el cliente tiene contratado el servicio de telefonía (si/no)
- `MultiplesLineas`: indica si el cliente tiene múltiples lineas telefónicas con la compañía
- `Internet`: indica si el cliente tiene contratado el servicio de internet (si/no)
- `ProteccionDispositivos`: si el cliente cuenta con un plan adicional de protección de dispositivos para sus equipos de internet (si/no)
- `SoporteTecnico`: si el cliente ha contratado un plan de soporte técnico personalizado (si/no)
- `StreamingTV`: si el cliente ha contratado un servicio de streaming de un tercero a través de la compañía (si/no)
- `TipoContrato`: el tipo de contrato del clientes: mensual, anual o bianual
- `E-Boleta`: si el cliente ha solicitado facturación electronica (si/no)
- `MetodoPago`: tipo de pago que ha suscrito el cliente: tarjeta crédito (TC), cuenta corriente (CC), pago online, boleta
- `PagoMensual`: monto del cobro mensual por servicios (en USD)
- `PagoTotal`: monto del pago total en un trimestre (incluye otros cobros no observables) (en USD)
- `Fuga`: si el cliente se mantiene en la compañía al final del periodo (si/no)