# Predicción del precio de venta de hogares

## Descripción
La regresión es unas de las técnica más utilizadas en estadística y machine learning. Sin embargo, cuando se aplica a observaciones distribuidas espacialmente, se puede perder mucho poder predictivo al ignorar la presencia de autocorrelación espacial.

Con el objetivo es estudiar estas correlaciones espaciones, utilizaremos una base de datos sobre precios de inmuebles en California. La fuente de los datos proviene de Pace y Barry (1997). El objetivo es generar predicciones del precio de los inmuebles en California, dado su posición geográfica.

Referencia: **Pace, R. K., y Barry, R.** (1997). Sparse spatial autoregressions. Statistics & Probability Letters, 33(3), 291-297.

## Atributos
- `Longitud`: medida (en grados º) de qué tan al oeste está una casa; un valor más alto implica un hogar más oeste
- `Latitud`: medida (en grados º) de qué tan al norte está un hogar; un valor más alto implica un hogar más al norte
- `AntiguedadMedia`: promedio de la antiguedad de los hogares en ese bloque (un nº menor implica inmuebles construidos más recientemente)
- `Habitaciones`: nº total de habitaciones en ese bloque (por ejemplo: una cuadra)
- `Banos`: nº total de baños en ese bloque (por ejemplo: una cuadra)
- `Poblacion`: nº total de personas que viven en ese bloque (por ejemplo: una cuadra)
- `Hogares`: nº total de hogares para un bloque (por ejemplo: una cuadra)
- `IngresoMedio`: promedio del ingresos de los hogares dentro del bloque (medido en decenas de miles de dólares americas USD) [USD 10.000]
- `ValorMedioHogar`: promedio del precios de los inmuebles para los hogares dentro de un bloque (medido en dólares americanos USD) [USD]