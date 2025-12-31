# 📊 Proyecto 8. Análisis de Datos – Servicios de Taxi en Chicago 

## 🧠 Descripción del Proyecto
Este proyecto analiza datos reales de servicios de taxi en la ciudad de Chicago con el objetivo de identificar patrones de uso, empresas más relevantes y evaluar el impacto de las condiciones climáticas en la duración de los viajes. El análisis combina consultas SQL, análisis exploratorio de datos en Python y pruebas estadísticas de hipótesis.

El caso se desarrolla en el contexto de Zuber, una empresa de viajes compartidos interesada en comprender el comportamiento de los pasajeros y los factores externos que influyen en la demanda.

---

## 📂 Fuentes de Datos
- Información de viajes de taxi en Chicago (noviembre 2017)
- Empresas de taxis y número de viajes
- Barrios de recogida y destino
- Registros meteorológicos por hora

---

## 🔍 Análisis Realizados
- Identificación de las empresas de taxi más populares
- Análisis de viajes entre el 15 y 16 de noviembre de 2017
- Evaluación de compañías con nombres *Yellow* y *Blue*
- Ranking de los 10 barrios con mayor finalización de viajes
- Visualización de datos mediante gráficos de barras
- Integración de datos de clima y viajes mediante coincidencia temporal

---

## 📈 Análisis Estadístico
Se probó la hipótesis:
> *“La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O’Hare cambia los sábados lluviosos.”*

- Se utilizó una prueba t de Student para muestras independientes
- Nivel de significancia: α = 0.05
- Resultado: rechazo de la hipótesis nula
- Conclusión: los viajes en sábados lluviosos duran en promedio más tiempo que en sábados no lluviosos

---

## ✅ Principales Conclusiones
- Flash Cab y Taxi Affiliation Services dominan el mercado de viajes
- Zonas céntricas y turísticas como *Loop* y *River North* concentran la mayor demanda
- Las condiciones climáticas adversas impactan significativamente la duración de los viajes
- El análisis estadístico respalda decisiones basadas en datos reales

---

## 🚀 Aprendizajes Clave
- Integración de SQL y Python en un flujo de análisis completo
- Aplicación práctica de pruebas de hipótesis
- Comunicación efectiva de resultados mediante visualizaciones y conclusiones claras
- Enfoque analítico orientado a negocio

---

## 🛠️ Herramientas y Tecnologías
- SQL: consultas, filtros, agregaciones, `JOIN` y `CASE`
- Python:
  - Pandas y NumPy (manipulación de datos)
  - Matplotlib y Seaborn (visualización)
  - SciPy (pruebas estadísticas)
- Jupyter Notebook
