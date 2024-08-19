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
La columna de retorno muestra correlaciones ba
