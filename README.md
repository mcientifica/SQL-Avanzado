# SQL-Avanzado
SQL Avanzado

1.	Agregar una columna llamada “Ranking” con el ranking de ventas en función del monto (SalesOrderHeader.TotalDue)
2.	Agregar una columna llamada “Ranking” por territorio con el ranking de ventas en función del monto y territorio. Mostrar el nombre del Territorio, SalesOrderID, OrderDate, TotalDue y Ranking
3.	Agregar una columna en la tabla SalesPerson que muestre la contribución de esa persona a las ventas del año (SalesYTD / total de SalesYTD)
4.	En la tabla CurrencyRate, buscar los registros que reflejen el tipo de cambio Dólar a Euro y calcular cual fue la máxima fluctuación de un día a otro (considerar el AverageRate).
5.	De los dos vendedores (SalesPersonID) que hayan tenido mayor cantidad de ventas (TotalDue) en toda la historia, mostrar sus 5 ventas más altas. La tabla debe tener Nombre y apellido del vendedor (tabla Person), JobTitle, OrderDate y TotalDue
6.	En la tabla Production.WorkOrder mostrar el día (DueDate) que más piezas se hayan pedido (OrderQty) de las piezas que tengan un precio de lista mayor a 3000 (Product.ListPrice). Mostrar ProductID, DueDate, OrderQty y ListPrice
7.	Buscar cuales fueron los dos compradores que mayores compras realizaron por cada territorio (ver tabla Sales.SalesOrderHeader). Indicar nombre del territorio, id del cliente y cantidad de compras
8.	Mostar una tabla que tenga en las filas los territorios y en las columnas las categorías. La misma debe contener la cantidad de unidades vendidas por cada categoría y territorio respectivamente.


En estos ejercicios no se darán referencia de tablas, deben resolver el problema a partir de buscar entre las tablas
1.	Cuales fueron los 5 productos con más ventas en 2012. Mostrar los 3 compradores que compraron mayor cantidad (en dinero) de cada uno de estos durante este año.
2.	Cual es el nombre de los 5 mejores vendedores de cada territorio?
3.	Cuantos productos de la categoría bicicletas se vendieron con algún tipo de descuento?
4.	Buscar el top 5 de clientes que hayan comprado mayor cantidad de unidades de cascos (subcategoría Helmets) por:
a.	Cada territorio
b.	Cada región
5.	Se quiere entender si hay alguna relación entre el nombre del local y la cantidad de ventas. Separar los locales (stores) en dos grupos: los que contenga la palabra Bike y los que no contengan. Buscar los dos locales con mayor cantidad de ventas de bicicletas (categoría bikes) por cada región. Que porcentaje de estos contienen la palabra bike?
6.	El Scrap es el residuo en los procesos de producción. Cuantos productos (en cantidad de unidades) fueron scrappeados por haberse fabricado de un color incorrecto? 
7.	Cuantas horas fueron dedicadas en total para fabricar los productos scrappeados por haberse fabricado de un color incorrecto (ActualResourceHrs)?
8.	Cual fue el producto con mayor cantidad de unidades vendidas de las transacciones realizadas en dólares australianos
9.	Buscar cuales el país en el que viven menos empleados
10.	Buscar el id de la tarjeta que estaba más cerca de su vencimiento y mostrar cuantos días faltaban para el vencimiento. Suponer que las tarjetas vencen el último día del mes (posiblemente necesites usar las funciones DATEFROMPARTS, EOMONTH y DATEDIFF).
