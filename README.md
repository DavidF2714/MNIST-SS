# Semantic Segmentation - PyTorch Lightning

Este proyecto implementa una red de segmentación semántica utilizando PyTorch Lightning. El modelo está entrenado para identificar clases a nivel de píxel en imágenes, con una arquitectura basada en U-Net.

## Características
- Arquitectura: U-Net personalizada
- Framework: PyTorch Lightning
- Entrenamiento con EarlyStopping y ModelCheckpoint
- Métricas de entrenamiento guardadas en logs

## Archivos
- `semantic_segmentation.ipynb`: Notebook con todo el pipeline de entrenamiento, validación y prueba.

## Checkpoints del modelo
Puedes descargar los checkpoints entrenados desde el siguiente enlace:

🔗 [Model Checkpoints (.ckpt)](https://drive.google.com/drive/folders/1IXDOamN5TuEwrCO59mYQUg889QCIms4G?usp=drive_link)

## Requisitos
- Python ≥ 3.8
- PyTorch ≥ 1.12
- pytorch-lightning
- torchvision
- PIL
