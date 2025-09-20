#  Clasificación con Regularización – PC1

##  Descripción
Este proyecto implementa un clasificador de texto binario (*Positivo vs. No Positivo*) usando **Regresión Logística** con representaciones **Bag of Words (BoW)** y **TF-IDF**.  
Se comparan modelos con y sin **regularización L2**, y se reportan métricas de rendimiento: **F1, ROC-AUC y matriz de confusión**.  



##  Dependencias
El proyecto requiere **Python 3.10+** y las siguientes librerías (listadas en `requirements.txt`):  

- numpy==1.26.4  
- pandas==2.2.2  
- scikit-learn==1.5.1  
- scipy>=1.11  
- matplotlib  
- seaborn  

Instalación rápida en Colab o local:  
```bash
pip install -r requirements.txt
