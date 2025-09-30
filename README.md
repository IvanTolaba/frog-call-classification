# Clasificación de cantos de anfibios con Deep Learning 🐸🎶

## 📌 Descripción
Este proyecto aborda la **bioacústica aplicada a la clasificación de anfibios**, utilizando técnicas de **Deep Learning** para identificar cantos del anuro *Boana riojana*.  

Se procesó un conjunto de **4300 audios**, aplicando pipelines de **ETL de señales acústicas** y extrayendo **coeficientes cepstrales en la escala Mel (MFCC)** como características principales.  

## ⚙️ Tareas realizadas
- Procesamiento y limpieza de un dataset de 4300 audios de *Boana riojana*.  
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
- `notebooks/` → Jupyter Notebooks con el preprocesamiento y entrenamiento.  
- `data/` → (No incluido por tamaño, pero se puede solicitar o recrear).  
- `models/` → Modelos entrenados en formato `.h5`.  
- `README.md` → Este documento.  

## 📈 Ejemplo de espectrograma MFCC
![Ejemplo MFCC](ruta/a/ejemplo_mfcc.png)

## 👨‍💻 Autor
Proyecto desarrollado por *[Tu Nombre]* en el marco de estudios en **Bioingeniería e Inteligencia Artificial aplicada a bioacústica**.
