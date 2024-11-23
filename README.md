# Analisis-de-datos-con-Excel

## Analisis para CityBlend Ny

Comprender mejor el funcionamiento operativo de la cafetería "CityBlend", ubicada en Nueva York, se han recopilado datos sobre las transacciones realizadas durante seis meses consecutivos, desde enero hasta junio. La cafetería cuenta con tres sucursales distintas, y este análisis nos permitirá obtener una visión más clara del comportamiento general del negocio.

## Objetivos
- Comprender mejor el funcionamiento de operativo de sus cafeterias en 3 puntos diferentes
- Obtener conocimiento sobre los productos con mayor rotacion en sucursales
- Conocer en orden los movimientos por sucursal
- Transformar y visualizar los datos de manera que permita a los propietarios de la cafetería analizar patrones y detectar oportunidades de mejora para el negocio a partir de los datos recopilados.

## Pasos a Seguir

### Preparar los datos para el análisis.
1.- El primer objetivo es explorar el conjunto de datos para familiarizarte con ellos. ¿Cuántas transacciones se registraron y durante qué período de tiempo? ¿Qué productos y categorías de productos se vendieron? Una manera de realizar esto, es mediante el uso de filtros.
- Agrega una nueva columna para calcular los Ingresos (precio * cantidad).
- Agrega una columna para calcular el número de mes en función de la fecha de la transacción con la función MES (E.j. una transacción realizada en enero será = 1).
- Agrega formato condicional a cada una de las 3 diferentes sucursales:
    - Lower Manhattan - relleno rojo claro
    - Hell's Kitchen - relleno amarillo
    - Astoria - relleno azul

### Explorar los datos mediante tablas dinámicas.
- Inserta una tabla dinámica en una nueva hoja para mostrar los ingresos por mes.
- Añade una tabla dinámica en la misma hoja para mostrar el número de transacciones por categoría de producto, ordenada de manera descendente por transacciones.
- Agrega una tabla dinámica en la misma hoja para mostrar el número de transacciones e ingresos por tipo de producto, ordenada de manera descendente y filtrada a los 10 principales (por transacciones).

### Realizar Dashboard
- Agrega un gráfico de líneas para mostrar los ingresos por mes, llamado “Total de ingresos por mes”.
- Agrega un gráfico de barras para mostrar las transacciones por categoría de producto, llamado “Total de transacciones por categoría”.
- Agregar un gráfico donde muestre el comportamiento de ventas en el lapso de tiempo de un dia de operacion englobando las sucursales.
- *Opcional* Agregar un segmentador de datos para poder segmentar por ubicación de sucursal en las 3 tablas dinámicas.


### Redactar al menos 3 puntos claves encontrados provenientes del análisis de datos.

