# Deepfake Detection com iNNvestigate

Este projeto usa redes pré-treinadas (VGG16, ResNet50, EfficientNetB0) para extrair características de imagens reais e falsas. Utiliza PCA + SVM para classificação e o pacote [iNNvestigate](https://github.com/albermax/innvestigate) para gerar explicações visuais do modelo.

## 🔍 Objetivo
Detectar e explicar visualmente a diferença entre vídeos reais e deepfakes por meio de mapas de calor gerados com técnicas como LRP (Layer-wise Relevance Propagation).

## 🧰 Tecnologias
- TensorFlow + Keras
- OpenCV
- Scikit-learn
- iNNvestigate
- Matplotlib

## ▶️ Como executar
1. Instale os pacotes:
```bash
  pip install -r requirements.txt
```
3. Execute o notebook:
```bash
  notebooks/Innvestigate.ipynb
```
## 🧠 Resultados
O classificador SVM teve desempenho razoável/ruim em detecções entre classes reais/falsas com baixo AUC e F1-Score.
