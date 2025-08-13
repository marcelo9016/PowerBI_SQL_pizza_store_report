# Reporte de ventas para una pizzeria

## Tabla de contenido

- [Descripción general del proyecto](#descripción-general-del-proyecto)
- [Fuente de datos](#fuente-de-datos)
- [Herramientas](#herramientas)
- [Limpieza de datos y preparacion](#limpieza-de-datos-y-preparacion)
- [EDA Analisis exploratorio de datos](#eda-analisis-exploratorio-de-datos)
- [Graficos requeridos](#graficos-requeridos)

### Descripción general del proyecto

Necesitamos consultar indicadores clave de nuestros datos de ventas de pizza en base a nuestros datos para obtener información sobre nuestro negocio para lo cual usaremos cunsultas en SQL.

Tambien nos gustaría visualizar varios aspectos de nuestros datos de ventas de pizza para obtener información y comprender los factores clave por medio de Power BI.

<img width="1318" height="722" alt="image" src="https://github.com/user-attachments/assets/ec5b04b2-0c07-4236-84b4-289f07b237d3" />

<img width="1316" height="720" alt="image" src="https://github.com/user-attachments/assets/ee70f7d5-c986-4b5e-8d99-df769363eed2" />






### Fuente de datos

pizza_sales: Este dataset contiene registros detallados de pedidos de pizza, incluyendo información como el tipo y tamaño de la pizza, cantidad pedida, fecha y hora del pedido, precio unitario y total, así como ingredientes y categoría. Es ideal para análisis de ventas, comportamiento del cliente, segmentación de productos y visualización de KPIs en herramientas como Power BI o SQL. Su estructura limpia y granular permite explorar patrones de consumo, optimizar inventario y diseñar dashboards interactivos para toma de decisiones en negocios de alimentos.


### Herramientas

  - Excel - Limpieza de datos
  - Power BI - Reporte y visualizacion
  - SQL - Consultas y visualizaciones de KPI's

### Limpieza de datos y preparacion 

En la fase inicial realizamos las siguientes tareas:
1. Carga e inspección de datos
2. Manejo de valores nulos y duplicados
3. Correccion de valores a un formato adecuado

### EDA Analisis exploratorio de datos

EDA implica explorar los datos de ventas para responder preguntas clave, como:
1. Ingresos totales: la suma del precio total de todos los pedidos de pizza.

2. Valor promedio del pedido: el monto promedio gastado por pedido, calculado dividiendo el
ingresos totales por el número total de pedidos.

3. Total de pizzas vendidas: La suma de las cantidades de todas las pizzas vendidas.

4. Total de pedidos: el número total de pedidos realizados.

5. Promedio de pizzas por pedido: el número promedio de pizzas vendidas por pedido, calculado por dividiendo el número total de pizzas vendidas por el número total de pedidos.


### Graficos requeridos

#### Tendencias.
Hemos identificado los siguientes requisitos para la creación de gráficos:

### 1. Tendencia diaria de pedidos totales:
Cree un gráfico de barras que muestre la tendencia diaria del total de pedidos durante un período específico. Este gráfico nos ayudará a identificar patrones o fluctuaciones en el volumen de pedidos a diario.
### 2. Tendencia mensual del total de pedidos:
Cree un gráfico de líneas que ilustre la tendencia horaria del total de pedidos a lo largo del día. Este gráfico nos permitirá identificar las horas punta o los periodos de mayor actividad de pedidos.
### 3. Porcentaje de ventas por categoría de pizza:
Cree un gráfico circular que muestre la distribución de las ventas entre las diferentes categorías de pizza. Este gráfico proporcionará información sobre la popularidad de las distintas categorías de pizza y su contribución a las ventas totales.
### 4. Porcentaje de ventas por tamaño de pizza:
Genere un gráfico circular que represente el porcentaje de ventas atribuido a los diferentes tamaños de pizza. Este gráfico nos ayudará a comprender las preferencias de los clientes por los tamaños de pizza y su impacto en las ventas.
### 5. Total de pizzas vendidas por categoría:
Cree un gráfico de embudo que presente el número total de pizzas vendidas para cada categoría. Este gráfico nos permitirá comparar el rendimiento de las ventas de las diferentes categorías.
### 6. Los 5 más vendidos por ingresos, cantidad total y pedidos totales
Crea un gráfico de barras que resalte las 5 pizzas más vendidas según los ingresos, la cantidad total y los pedidos totales. Este gráfico nos ayudará a identificar las pizzas más populares.
### 7. Las 5 pizzas más vendidas por ingresos, cantidad total y pedidos totales
Crea un gráfico de barras que muestre las 5 pizzas menos vendidas según los ingresos, la cantidad total y los pedidos totales. Este gráfico nos permitirá identificar las pizzas con menor rendimiento o menos populares.
