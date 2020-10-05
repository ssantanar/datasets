# Bankloan

## Descripción
Muestra de la base de datos de una institución financiera tradicional de clientes que han contraído un crédito con dichas institución. Se posee información que caracteriza a los clientes e información sobre su comportamiento de pago (*default*).

## Atributos
- `CUSTOMER_ID`: id único del cliente (numerico).
- `AGE`: edad del cliente al contraer el crédito.
- `EDUCATION`: nivel educacional del cliente al contraer el crédito. Se observan los siguientes niveles:
    * **Bas**: educación básica completa.
    * **Med**: educación media completa.
    * **SupInc**: educación superior incompleta.
    * **SupCom**: educación superior completa.
    * **Posg**: postgrado universitario completo.
- `NATIONALITY`: nacionalidad del cliente.
- `YRS_WORK`: número de años trabajando en la empresa que declara el cliente al momento de solicitar el crédito.
- `YRS_ADDRESS`: número de años viviendo en la misma morada al momento de solicitar el crédito.
- `INCOME`: ingreso en miles de dólares americanos (valor estimado).
- `DEBT_INCOME`: deuda en consumo (en miles).
- `CREDIT_DEBT`: deuda en tarjetas de credito (en miles).
- `OTHER_DEBT`: otras deudas (en miles).
- `DEFAULT`: etiqueta si cliente ha caído en default en el periodo de observación o no (`N`: no ha caído en *default*, `S`: si ha caído en *default*).
