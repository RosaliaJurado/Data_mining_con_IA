# Data_mining_con_IA
Curso data mining EAN
Proyecto: Minería de Datos con IA
De la pregunta al insight (usando Excel)

1. Objetivo del proyecto
Analizar si el precio de un libro bestseller en Amazon influye en su calificación promedio (User Rating), utilizando técnicas de minería de datos básicas en Excel, con apoyo de inteligencia artificial para la formulación del problema, el análisis y la interpretación de resultados.

2. Pregunta de investigación
¿El precio afecta la calificación del libro?

3. Hipótesis
Hipótesis nula (H₀): El precio del libro no tiene impacto significativo en su calificación.
Hipótesis alternativa (H₁): El precio del libro sí influye en la calificación.

4. Dataset
Fuente: Amazon Best Sellers Dataset
Registros: Dataset filtrado a máximo 500 filas
Variables relevantes:
Price: Precio del libro
User Rating: Calificación promedio otorgada por los usuarios
Year, Genre, Reviews, Author, Name
El dataset fue limpiado y estructurado en Excel antes del análisis.

5. Proceso de limpieza y preparación de datos
El proceso de preparación se realizó completamente en Microsoft Excel:
Validación de valores faltantes
Revisión y eliminación de duplicados
Filtrado del dataset para cumplir con el límite de registros
Creación de una nueva variable categórica de rangos de precio:
Bajo
Medio
Alto
La versión final fue guardada como dataset limpio para el análisis.

6. Técnica de minería de datos aplicada
Técnica utilizada:
Análisis descriptivo y segmentación por rangos (minería de datos exploratoria)
Herramienta:
Microsoft Excel
Método de análisis:
Agrupación de los libros por rango de precio
Cálculo del promedio de la calificación (User Rating) por cada grupo
Comparación de resultados entre segmentos

7. Resultados obtenidos
Promedio de calificación por rango de precio:
Rango de precio	Promedio User Rating
Bajo	4.61
Medio	4.61
Alto	4.60
Adicionalmente, se generó un gráfico de columnas en Excel que evidencia que las diferencias entre los rangos son mínimas.

8. Interpretación de resultados
Las calificaciones promedio son prácticamente iguales en los tres rangos de precio.
No se observa una relación clara entre el aumento del precio y una mejor calificación.
Las diferencias encontradas no son estadísticamente ni prácticamente significativas.

9. Conclusiones
El precio del libro no influye de manera significativa en su calificación promedio.
Los usuarios califican de forma similar libros económicos, de precio medio y de precio alto.
La percepción de calidad de un libro parece depender más de factores como el contenido, el autor o la experiencia del lector, y no del precio.
El análisis en Excel permite concluir que el precio no es un predictor relevante del User Rating.

10. Limitaciones del análisis
El estudio se limita a libros que fueron bestseller.
No se incluyen variables cualitativas como reputación del autor o campañas de marketing.
La variable User Rating tiene baja variabilidad al estar limitada a una escala de 1 a 5.

11. Uso de inteligencia artificial
Se utilizó inteligencia artificial (ChatGPT) como apoyo para:
Refinar la pregunta de investigación.
Definir hipótesis.
Sugerir técnicas de análisis en Excel.
Apoyar la interpretación de resultados y la redacción de conclusiones.

12. Recomendaciones futuras
Incluir variables adicionales como ventas reales o reseñas cualitativas.

Analizar el efecto combinado de precio y número de reseñas.

Aplicar técnicas más avanzadas como regresión múltiple o análisis por género literario.
