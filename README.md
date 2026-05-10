# 📸 Organización Inteligente de Fotos

Sistema de clustering automático de fotografías personales sin enviar datos a la nube.

## 🎯 ¿Qué hace?

Agrupa automáticamente tus fotos por similitud visual (eventos, personas, lugares) usando deep learning y clustering no supervisado. Todo se ejecuta en tu ordenador o en Google Colab gratuito.

## 🚀 Cómo usarlo

### Opción 1: Google Colab (recomendado si no tienes experiencia)

1. Sube el documentom .ipynb a Google Drive
2. Sube tus fotos a Google Drive
3. Ejecuta el notebook celda por celda
4. Etiqueta los clusters cuando te lo pida
5. Descarga las carpetas ya organizadas

### Opción 2: Local (si tienes Python instalado)

```bash
# Clonar el repositorio
git clone https://github.com/TU-USUARIO/tfm-photo-clustering.git
cd tfm-photo-clustering

# Instalar dependencias
pip install -r requirements.txt

# Abrir el notebook
jupyter notebook .ipynb
```

## 📋 Requisitos

- Python 3.10 o superior

## 🛠️ Tecnologías

- **Extracción de características**: CLIP, MobileNetV3, EfficientNet
- **Detección facial**: InsightFace (ArcFace)
- **Reducción dimensional**: PCA + UMAP
- **Clustering**: HDBSCAN
- **Almacenamiento**: ChromaDB

## 📄 Licencia

Este proyecto es parte de un TFM del Máster en Ciencia de Datos (UOC).

## 🤝 Contribuciones

Si encuentras algún bug o quieres proponer mejoras, abre un issue.
