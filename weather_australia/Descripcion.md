# Weather Australia

## Contexto

En este desafío realizaremos predicciones sobre si lloverá un día, en base a la información disponible del día anterior. Por tanto, en este desafío nos enfrentamos a un problema de clasificación.

Para este desafío, utilizaremos un conjunto de datos que contiene 10 años de observaciones meteorológicas diarias de múltiples zonas de Australia. En este dataset, `LlueveManana` es la etiqueta a predecir, donde los valores que puede tomar son `Si` o `No`, donde `Sí` significa que al día siguiente llueve y `No`, que al día siguiente no lleuve.

## Datos y agradecimientos

Las observaciones se extrajeron de numerosas estaciones meteorológicas. Las observaciones diarias están disponibles en http://www.bom.gov.au/climate/data.

Definiciones adaptadas de: [http://www.bom.gov.au/climate/dwo/IDCJDW0000.shtml](http://www.bom.gov.au/climate/dwo/IDCJDW0000.shtml)

## Fuentes de datos original

- Oficina de meteorología Australiana, *Daily Weather Observations*: [http://www.bom.gov.au/climate/dwo/](http://www.bom.gov.au/climate/dwo/)
- Oficina de meteorología Australiana, *Climate Data Online*: [http://www.bom.gov.au/climate/data](http://www.bom.gov.au/climate/data)

*Copyright Commonwealth of Australia 2010, Oficina de Meteorología.*

## Atributos
- `Fecha`: fecha de la observación.
- `MinTemp`: temperatura mínima para ese día (º Celsius).
- `MaxTemp`: temperatura máxima para ese día (º Celsius).
- `LluviaHoy`: cantidad de lluvia registrada para el día en milímetros (mm).
- `Presion9am`: presión atmosférica (hpa) reducida al nivel medio del mar a las 9 a.m.
- `Presion3pm`: presión atmosférica (hpa) reducida al nivel medio del mar a las 3 a.m.
- `Humedad9am`: humedad a las 9 a.m (porcentual).
- `Humedad3pm`: humedad a las 3 p.m (porcentual).
- `DirViento9am`: dirección del viento a las 9 a.m.
- `DirViento3pm`: dirección del viento a las 3 p.m.
- `LlueveManana`: indica si al siguiente día llueve o no.
