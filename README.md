# Analisis de marketing: Y.Afisha
__Análisis de marketing para Y.Afisha, análisis de cohortes, cálculo de métricas clave (CAC, ROMI, LTV) y visualización con mapa de calor__

<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/banner.png" alt="Collage de gráficos">

_Para ver desarrollo en código hacer click [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/P8.html)_

## Descripción del proyecto
Este proyecto se centra en analizar los datos de la empresa Y.Afisha para evaluar el comportamiento de los usuarios, las compras realizadas y los costos de marketing asociados. Se utilizaron tres datasets que contienen información sobre visitas al sitio web, compras realizadas y gastos en diversas campañas de marketing. Después de limpiar y analizar los datos, se realizó una comparación detallada del rendimiento de varias campañas para hacer recomendaciones sobre en cuáles invertir de manera más efectiva y los beneficios esperados.
  
## Herramientas Utilizadas
- __Lenguaje de Programación:__ Python.
- __Entorno de Desarrollo:__ Jupyter Notebook.
- __Bibliotecas:__ Pandas, Numpy, Matplotlib, Seaborn.
  
## Proceso del Proyecto
- __Pre-análisis de los datos:__ Los datos fueron extraídos de tres archivos proporcionados por la compañía (`orders`, `visits` y `costs`). Además, se llevaron a cabo operaciones de limpieza, como la búsqueda y eventual manejo de valores nulos, duplicados y formateo de datos.
- __Análisis de los datos:__ .
  - __Visitas:__ Se estudia la duración y frecuencia de las visitas de forma diaria, semanal y mensual, durante el año estudiado. También, se estudia la tasa de retención de cada cohorte mensual.
  - __Ventas:__ Se analiza en qué momento la gente comienza a comprar, el tamao promedio de pedido y el LTV de cada cohorte mensual.
  - __Marketing:__ Se compararon, usando métricas clave como CAC, LTV y ROMI, los costos y el rendimiento de diferentes campañas de marketing. Además, se generaron visualizaciones ilustrativas, tales como, mapas de calor por cohorte y gráficos de barra para el CAC y un gráfico de líneas con los costos de todas las campañas por mes.
- __Conclusión:__ Con base en el análisis, se proporcionaron recomendaciones sobre las campañas en las que sería más rentable invertir.
  
## Descubrimientos importantes
Se presentarán los principales descubrimientos del análisis en diferentes ámbitos.

### Visitas
- La distribución mensual de visitas es muy variable, teniendo su peak en noviembre (antes de las fiestas de fin de año) y su punto más bajo en agosto.
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_65_0.png" alt="Collage de gráficos">

- La tasa de retención es __muy baja__, ninguna cohorte supera el 10% de retención mensual, lo anterior indica que se deben tomar medidas para retener a los visitantes y a los clientes que hacen su primera compra.
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_91_0.png" alt="Collage de gráficos">
  
- El ASL (tiempo de sesión promedio) es de 60 segundos, lo cual es suficiente para que un cliente haga una compra.
- En promedio, cada visitante entra 1.08 veces al día a la web.

### Ventas
- Una gran mayoría de clientes hace su compra el mismo día de la primera visita a la web, y en específico durante los primeros 5 minutos.
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_101_0.png" alt="Collage de gráficos">
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_103_0.png" alt="Collage de gráficos">

- La mediana en cuanto a tamaño de ventas es 2.5 dólares y en general las compras son por valores bajos, hay un numero pequeño de compras muy grandes (por sobre los mil dolares) pero estas no afectan significativamente las metricas finales como el ROMI y el LTV.
- el LTV de un cliente captado en junio de 2017 (la cohorte más antigua) es de 11.88 dólares.

### Gastos de marketing
- El CAC tiende a subir en los peores meses, lo que indica que es probable que por el rubro de la tienda, estos sean simplemente malos meses para la venta de estos productos.
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_151_0.png" alt="Collage de gráficos">

- El Costo de adquisición de cliente de la fuente 3 es de más de 13 dólares, lo que nos da un indicio de lo poco rentable que está resultando esta fuente de anuncios.
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_149_0.png" alt="Collage de gráficos">

### Recomendaciones de inversión
- Se recomienda __eliminar la fuente de anuncios 3 debido a que tiene CAC muy alto y no es capaz de generar ganancias sino al contrario, están generando pérdidas para la empresa__, en la cual se gastaron 140.000 dólares durante el año estudiado.
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_164_0.png" alt="Collage de gráficos">

- __La fuente 1 funciona bien__ y se debe invertir más en ella, genera ganancias la mayoría del año, salvo unos pocos meses (de diciembre a febrero y abril).
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_158_0.png" alt="Collage de gráficos">

- La fuente 2 trae buenos resultados sólo en __septiembre y diciembre__.
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_161_0.png" alt="Collage de gráficos">

- La fuente 4 trae buenos resultados sólo en __noviembre__.
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_167_0.png" alt="Collage de gráficos">

- __La fuente 5 funciona bien para atraer compradores para navidad en el mes de septiembre, el resultado muestra que los clientes atraídos en esta fecha generaron muy buenos resultados__, sin embargo el resto del año la campaña no funciona bien.
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_170_0.png" alt="Collage de gráficos">
  
- La fuente 9 trae resultados relativamente buenos __desde junio hasta octubre__.
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_173_0.png" alt="Collage de gráficos">

- La fuente 10 ha mostrado buenos números en __marzo y mayo__.
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_176_0.png" alt="Collage de gráficos">

- Según los resultados anteriores es que se propone el siguiente esquema de distribución de recursos entre las campañas de marketing.
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_188_0.png" alt="Collage de gráficos">

- El porcentaje de fondos a redistribuir sería por lo bajo un 42.9%

## Ejecuta el proyecto [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/P8.html)
Para ver el diccionario de datos, el desarrollo completo en código, todos los gráficos y las conclusiones, haga click en el enlace de arriba
