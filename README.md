#  Spotify Hit Predictor
Implementación de un predictor de si una canción será un hit o no, con un dataset obtenido de la API de Spotify. </br>
Se realizó un procesamiento previo de los datos, que incluye remover las columnas que tengan muy poca correlación, y una codificación One Hot para los artistas.</br>
Además, se realizó una validación cruzada y para cada sub-Dataset se entrenó con los algoritmos de clasficación: MLP, K-Nearest, Decision Tree, SVC y Random Forest, entre otros, utilizando la librería Scikit-Learn. </br> Para cada uno se calculó el Accuracy, Recall y F1. </br>
Ejecutado en Google Colab.
