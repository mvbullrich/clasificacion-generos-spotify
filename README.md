# Clasificación de géneros musicales (Spotify)

Trabajo práctico de la materia Tecnología Digital VI: Inteligencia Artificial (UTDT, 2026).
Integrantes: María Victoria Bullrich, Candela Guinzburg y Oliverio Werb.

## Objetivo
Predecir el género musical de una canción (6 géneros) a partir de sus características acústicas y de popularidad.

## Qué hicimos
- Análisis exploratorio: distribuciones por género, PCA, correlaciones y asimetría.
- Limpieza: detección de 908 registros duplicados ocultos bajo IDs distintos.
- Feature engineering con variables de interacción y prevención de data leakage.
- Árbol de Decisión y Random Forest con búsqueda de hiperparámetros (RandomizedSearchCV) y model selection por cross-validation.
- Random Forest optimizado: F1-macro de 0,81 en cross-validation.
- Evaluación complementaria con MAP@3 y discusión de qué métrica conviene según el objetivo de negocio.

## Tecnologías
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Jupyter.

## Datos
Dataset de la competencia de Kaggle de la materia (no incluido en el repositorio).
