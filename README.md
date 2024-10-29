# Sistemas de Recoemndación: KNN y Métricas de Similitud
## Pregunta 1
**Explica como el algoritmo KNN utiliza métricas de similitud para generar recomendaciones. Indica dos ventajas y dos limitaciones del uso de KNN en un sistema de recomendacion con datos de películas.**

De modo general con KNN se calcula la similitud del usuario actual con todos los usuarios, luego se selecciona los k usuarios mas similares , finalmente se agrega las preferencias  a los usuarios con mas similitudes, estas preferencias vienen a ser las recomendaciones.

Ventajas:
- Es facil de entrenar
- Se puede reconocer rápidamente las similitudes

Desventajas:
- Hay problemas cuando se tienen usuarios que tienen seleccionadas pocas peliculas
- Puede haber dificultad para encontrar vecinos relevantes
