# Análisis de Datos 

## 1. Resumen Estadístico y Revisión de Valores Nulos

### Variabilidad del Dataset:
El dataset muestra una gran variabilidad en presupuesto, ingresos y popularidad. La mayoría de las películas tienen presupuestos y retornos bajos, mientras que algunos datos presentan valores atípicos extremos. La cobertura temporal es extensa, desde el siglo XIX hasta la actualidad, con significativas variaciones en votos y calificaciones.

### IDs de Películas:
Los IDs varían ampliamente, con una alta desviación estándar que indica dispersión significativa. La mayoría de los IDs están en el rango medio, con valores extremos menos frecuentes. El rango de IDs va de 2 a 469,172, sugiriendo una amplia cobertura en los identificadores únicos.

## 2. Visualización de Distribuciones y Detección de Outliers

### Distribución del Presupuesto:
La mayoría de las películas tienen presupuestos bajos, con una distribución sesgada a la derecha, indicando que hay pocas películas con presupuestos muy altos.

### Distribución de la Popularidad:
La popularidad de las películas muestra una distribución sesgada a la derecha, con la mayoría de las películas teniendo baja popularidad y pocas siendo muy populares.

### Distribución de la Votación Promedio:
Las votaciones promedio se concentran entre 5 y 8, mostrando una distribución más simétrica en comparación con otras variables.

### Boxplot del Presupuesto:
El boxplot revela varios outliers en el presupuesto, indicando que algunas películas tienen presupuestos significativamente más altos que la mayoría.

## 3. Análisis de Correlaciones y Mapa de Calor de Correlaciones

### Correlación entre Presupuesto e Ingresos:
Fuerte correlación positiva (0.75), indicando que películas con presupuestos más altos tienden a generar mayores ingresos.

### Correlación entre Número de Votos e Ingresos:
Fuerte correlación positiva (0.78), sugiriendo que películas con mayores ingresos también tienden a recibir más votos.

### Correlación entre Presupuesto y Número de Votos:
Correlación positiva moderada (0.68), indicando que películas con mayor presupuesto suelen recibir más votos.

### Correlación entre Popularidad y Presupuesto:
Correlación moderada (0.45), sugiriendo que películas con mayor presupuesto tienden a ser más populares, aunque la relación no es tan fuerte.

### Relación Débil del Retorno con Otras Variables:
La columna de retorno muestra correlaciones bajas con otras variables, indicando que el retorno no está fuertemente relacionado con presupuesto, popularidad, número de votos o ingresos.

### Correlaciones Bajas o Negativas:
Variables como ID y año de lanzamiento no tienen correlaciones fuertes con otras métricas, como es de esperar.

## 4. Análisis de Relaciones entre Variables

### Relación entre Presupuesto e Ingresos:
Tendencia positiva en el scatter plot, sugiriendo que películas con presupuestos más altos tienden a generar mayores ingresos. La mayoría de los datos se concentran en la parte inferior izquierda, indicando presupuestos e ingresos bajos.

### Relación entre Popularidad y Votación Promedio:
No hay una correlación clara entre popularidad y votación promedio. Las películas populares pueden tener una amplia gama de votaciones.

## 5. Nube de Palabras

### Temáticas Comunes:
Palabras grandes como "Love", "Man", "Girl", "Story", y "Night" indican temáticas recurrentes en los títulos de las películas. Las palabras representan temas comunes, como historias de amor o personajes masculinos.

### Valor para el Análisis:
Esta visualización ayuda a identificar las temáticas predominantes en el dataset, lo cual es útil para sistemas de recomendación y análisis de tendencias.

## 6. Análisis de Datos de Reparto y Equipo Técnico

### Actores Más Frecuentes:
Actores como Samuel L. Jackson y Steve Buscemi aparecen repetidamente, mostrando una diversidad de talentos en el reparto.

### Directores Más Frecuentes:
Alfred Hitchcock lidera la lista de directores con una frecuencia notablemente mayor que otros.

## 7. Detección de Anomalías

### Presupuestos Altos:
Hay una gran variabilidad en el éxito financiero de las películas con presupuestos altos, con algunos fracasos y otros éxitos.

### Ingresos Bajos Relativos al Presupuesto:
Películas con ingresos bajos en comparación con su presupuesto pueden haber enfrentado problemas en el mercado o en promoción.

## 8. Exploración de Patrones en el Tiempo

### Popularidad:
Ha aumentado significativamente desde el año 2000, con picos en lanzamientos de películas muy populares.

### Número de Votos:
También ha aumentado, especialmente después del año 2000, sugiriendo un mayor compromiso de la audiencia con las películas.

## Conclusión:
Las visualizaciones y análisis muestran que tanto la popularidad como el número de votos han crecido con el tiempo. Este crecimiento está relacionado con el acceso a internet y plataformas de streaming, y es esencial para comprender las tendencias en el mercado cinematográfico.

