# Clasificación de cantos de anfibios con Deep Learning 🐸🎶

## 📌 Descripción
Este proyecto aborda la **bioacústica aplicada a la clasificación de anfibios**, utilizando técnicas de **Deep Learning** para identificar cantos del anuro *Boana riojana*.  

Se procesó un conjunto de **4300 audios**, aplicando pipelines de **ETL de señales acústicas** y extrayendo **coeficientes cepstrales en la escala Mel (MFCC)** como características principales.  

## ⚙️ Tareas realizadas
- Procesamiento y limpieza de un dataset de 4300 audios de *Boana riojana*.
- Diseño de **pipelines ETL** : extracción, control de calidad, balanceo y normalización de señales.
- Extracción de características acústicas mediante **MFCC**.  
- Diseño y entrenamiento de modelos de **Deep Learning** (DNN, CNN y LSTM).  
- Evaluación del rendimiento de los modelos, obteniendo:
  - **Exactitud de hasta 97%**
  - **Precisión entre 0.89 y 0.97**  

## 🛠️ Tecnologías
- **Python**  
- **Keras / TensorFlow**  
- **Librosa** (procesamiento de audio)  
- **NumPy / Pandas / Matplotlib**  

## 📊 Resultados
- El modelo **CNN** alcanzó la mejor exactitud (97%).  
- Los modelos **DNN y LSTM** también presentaron métricas sólidas, con precisiones > 0.89.  

## 🚀 Estructura del repositorio
- `frog-call-classification.ypnb` → Notebooks con el preprocesamiento y entrenamiento del modelo CNN.  
- `data/` → (No incluido por tamaño y privacidad).    
- `README.md` 

---

## 📌 Autor  
👨‍💻 Iván Tolaba  
Data Science & Deep Learning aplicado a señales bioacústicas.   

🔗 [LinkedIn](https://www.linkedin.com/in/iv%C3%A0n-tolaba-b161927b) | [Portfolio Web](https://ivantolaba.github.io/Portfolio-IA) | Email: ivn.tlb@gmail.com  

