# Analisis de marketing: Y.Afisha
__Análisis de marketing para Y.Afisha, análisis de cohortes, cálculo de métricas clave (CAC, ROMI, LTV) y visualización con mapa de calor__

<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/banner.png" alt="Collage de gráficos">

_Fragmentos del notebook, para ver proyecto completo hacer click [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/P8.html)_

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
<image src="https://github.com/BastianLQ/Analisis-de-Marketing-Y.Afisha/blob/main/Images/output_91_0.png" alt="Collage de gráficos">
  
- La tasa de retención es muy baja, ninguna cohorte supera el 10% de retención mensual, lo anterior indica que se deben tomar medidas para retener a los visitantes y a los clientes que hacen su primera compra.
- El ASL es de 60 segundos, lo cual es suficiente para que un cliente haga una compra.
- En promedio, cada visitante entra 1.08 veces al día a la web, lo cual también es suficiente para hacer una compra.

## Ejecuta el proyecto [aquí](https://portfoliodabastianlopez.on.drv.tw/Portafolio/P8.html)
Para ver el diccionario de datos, el desarrollo completo en código, todos los gráficos y las conclusiones, haga click en el enlace de arriba
