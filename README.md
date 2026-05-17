# Organización Inteligente de Fotos

Sistema de clustering automático de fotografías personales.

## ¿Qué hace?

Agrupa automáticamente tus fotos por similitud visual (eventos, personas, lugares) usando deep learning y clustering no supervisado. Todo se ejecuta en tu ordenador o en Google Colab gratuito.

## Requisitos

- Python 3.10 o superior

## Tecnologías

- **Extracción de características**: CLIP, MobileNetV3, EfficientNet
- **Detección facial**: InsightFace (ArcFace)
- **Reducción dimensional**: PCA + UMAP
- **Clustering**: HDBSCAN
- **Almacenamiento**: ChromaDB

## Licencia

Este proyecto es parte de un TFM del Máster en Ciencia de Datos (UOC).
