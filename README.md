# 📈 Estrategia de Inversión en Videojuegos: Análisis de Tendencias Globales (2013-2016)

## 📌 Contexto de Negocio
La industria del videojuego opera en ciclos de vida de consolas (plataformas). El objetivo de este proyecto es **filtrar el ruido histórico** y analizar el desempeño de las ventas globales, regionales, y las preferencias de los usuarios en el **período más reciente y relevante (2013-2016)** para pronosticar las plataformas y géneros con mayor retorno de inversión (ROI) para el próximo año.

## 🎯 Metodología Aplicada

1.  **Limpieza y Preprocesamiento:** Normalización de nombres de columnas, manejo de valores nulos, y estandarización del campo `user_score` (convirtiendo 'tbd' a valor nulo).
2.  **Definición del Período Relevante:** Se aplica un filtro estricto para incluir solo datos a partir de **2013** para enfocarse en el ciclo de vida actual de las consolas (e.g., PS4, Xbox One, Switch predecesoras).
3.  **Análisis de Segmentación Regional:** Evaluación detallada de las ventas y las preferencias de género y clasificación (Rating) para **Norteamérica (NA), Europa (EU) y Japón (JP)**.
4.  **Inferencia Estadística:** Prueba T de Student y análisis de correlación para determinar el impacto real de las **calificaciones de críticos y usuarios** en el volumen de ventas.

## 💡 Insights Estratégicos Clave (Resultados para Inversores)

* **Plataformas de Alto Retorno:** Solo **[Plataforma Dominante]** y **[Segunda Plataforma]** mostraron crecimiento sostenido en el período 2013-2016, señalando que las inversiones deben priorizar estos ecosistemas.
* **Dominio Regional de Géneros:** El género **Shooter** es crucial para el mercado de NA y EU, mientras que **Role-Playing (RPG)** es la prioridad absoluta para el mercado japonés.
* **Influencia del Crítico:** El análisis estadístico demuestra que la **calificación de los críticos** tiene una correlación **significativa** con las ventas globales, lo que no sucede con la calificación de los usuarios.

**Conclusión Final:** La inversión debe alinearse con el ciclo de vida de las plataformas actuales y la estrategia de contenido debe ser adaptada regionalmente.

## 🛠️ Tecnologías
`Python` | `Pandas` | `NumPy` | `SciPy.stats` (Inferencia Estadística) | `Matplotlib`/`Seaborn`

