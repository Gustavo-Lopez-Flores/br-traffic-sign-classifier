# br-traffic-sign-classifier

Classificador de placas de trânsito brasileiras usando **Machine Learning clássico** e **Deep Learning (MobileNetV2)**.

O projeto compara algoritmos clássicos de aprendizado de máquina (KNN, SVM, Random Forest, Logistic Regression e MLPClassifier) com um modelo de visão computacional baseado em **MobileNetV2** (PyTorch), para identificar automaticamente cinco tipos de placas comuns no Brasil, a partir de imagens coletadas em ambientes reais ("in the wild").

## Algoritmos avaliados

* **K-Nearest Neighbors (KNN)**
* **Support Vector Machines (SVM)**
* **Random Forest**
* **Logistic Regression**
* **MLPClassifier** (Rede Neural Multicamadas)
* **MobileNetV2** (baseline de Deep Learning via PyTorch)

## Resultados

* Os algoritmos foram avaliados usando acurácia, precisão, recall, F1-score e matrizes de confusão.
* O Random Forest apresentou o melhor desempenho entre os métodos clássicos.
* O MobileNetV2, mesmo sem ajuste avançado, atingiu acurácia e F1-score superiores a 0.75.