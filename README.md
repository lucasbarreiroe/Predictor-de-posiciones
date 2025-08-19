# Trabajo práctico: Predictor de posiciones de jugadores

## Integrantes
Lucas Barreiro, Luca Gaziglia y Agustín Viullet

## Descripción del proyecto
Desarrollo de un modelo de clasificación en Python para predecir la posición (en el campo de juego) de jugadores de fútbol a partir de sus características físicas y estadísticas. El objetivo es, por ejemplo, identificar reemplazos adecuados o jugadores versátiles que cumplan ciertos roles.

## Contenido del repositorio
- **`Predictor de posiciones.ipynb`**  
  Notebook con análisis exploratorio de datos (EDA) y la implementación del modelo. Incluye visualizaciones, selección de features y pruebas con diferentes algoritmos.

- **`df_players.xlsx`**  
  Dataset con información numérica de jugadores (e.g. altura, peso, estadísticas en cancha) usado como base para el entrenamiento y evaluación del modelo.

## Tecnologías utilizadas
- Python (Jupyter Notebook)
- Bibliotecas: `pandas`, `numpy`, `seaborn`, `matplotlib`, `XGBoost`, `Random Forest`, entre otras

## Metodología y flujo de trabajo
1. Lectura y limpieza de datos desde `df_players.xlsx`.
2. Análisis exploratorio con visualizaciones y estadísticas descriptivas.
3. Entrenamiento de modelos de clasificación (Random Forest, XGBoost).
4. Evaluación mediante métricas relevantes.
5. Optimización y validación de desempeño con análisis de errores.

## Cómo ejecutar el proyecto
1. Clonar el repositorio.
2. Abrir el notebook `Predictor de posiciones.ipynb` en Jupyter.
3. Ejecutar las celdas en orden para reproducir el análisis completo.

## Posibles aplicaciones
- Localizar automáticamente jugadores con perfiles adecuados para reemplazar posiciones específicas.
- Identificar jugadores versátiles con características compatibles para diferentes roles.

## Recomendaciones futuras
- Añadir validación cruzada (cross-validation) más robusta.
- Explorar más modelos (por ejemplo, redes neuronales).
- Implementar pipeline reproducible y exportar los mejores modelos entrenados.



