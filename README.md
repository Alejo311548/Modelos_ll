#  Predicción de Constantes de Acoplamiento Escalar entre Átomos usando Machine Learning

> Proyecto final de la asignatura **Modelos y Simulación de Sistemas Dos**

---

###  Estudiante
**Alejandro Vargas Ocampo**  
Facultad de Ingeniería  
Universidad de Antioquia

---

###  Video del Proyecto

Puedes ver la presentación del proyecto en el siguiente enlace:  
[![Ver Video](https://img.shields.io/badge/VIDEO%20DEL%20PROYECTO-CLICK%20AQUÍ-red?style=for-the-badge&logo=youtube)](https://drive.google.com/file/d/1nHy2ABit88ftolwGI6vAQ87-3K9ES3MD/view?usp=sharing)

---

###  Código del Proyecto

📄 El código completo, con anotaciones y visualizaciones, se encuentra disponible en Google Colab:  
[![Ver Código](https://img.shields.io/badge/C%C3%93DIGO%20DEL%20PROYECTO-GOOGLE%20COLAB-blue?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/drive/1g-uXzKMvr2MNlPNvKKrE-AdZctdoZ1F4?usp=sharing)

---

###  Descripción del Proyecto

Este proyecto aplica técnicas de **aprendizaje automático** para predecir las **constantes de acoplamiento escalar** entre átomos en compuestos orgánicos, a partir de un dataset basado en simulaciones de química cuántica (CHAMPS).

Se utilizaron los siguientes enfoques:

- Análisis exploratorio de datos
- Ingeniería de características
- Entrenamiento de modelos supervisados (regresión, ensambles, redes neuronales y más)
- Selección y extracción de variables (PCA, búsqueda secuencial)
- Validación cruzada y ajuste de hiperparámetros

---

###  Dataset

Se trabajó con tres subconjuntos del conjunto CHAMPS, correspondientes a distintos tipos de interacciones **H-N**:

| Dataset | Muestras | Variables |
|---------|----------|-----------|
| 1JHN    | 43,680   | 73        |
| 2JHN    | 119,059  | 73        |
| 3JHN    | 166,613  | 73        |

---

###  Modelos Evaluados

- **Regresión Lineal y Ridge**
- **K-Nearest Neighbors (KNN)**
- **Random Forest**
- **Redes Neuronales (MLPRegressor)**
- **Support Vector Regression (SVR)**

---

###  Técnicas de Reducción de Dimensión

- **Análisis de varianza (ANOVA)**
- **Búsqueda secuencial (SFS y SBS)**
- **Análisis de Componentes Principales (PCA)**

---

###  Métricas de Evaluación

- **MSE **
- **R² Score**

Todos los modelos fueron evaluados con validación cruzada y análisis gráfico de resultados.

---



