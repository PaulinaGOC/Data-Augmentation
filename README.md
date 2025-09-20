# 📸 Data Augmentation Geométrico

Este proyecto implementa aumentación de datos para un dataset pequeño de imágenes (8) aplicando transformaciones geométricas como rotación, escalamiento, traslación, espejos y conversión a escala de grises.  
El objetivo es **generar más datos de entrenamiento** para modelos de visión por computadora a partir de un conjunto limitado de imágenes originales.

---

## ✨ Transformaciones implementadas
- 🔄 **Rotación** con ajuste de tamaño  
- 📏 **Escalamiento uniforme** (a=b)  
- 📐 **Escalamiento anisotrópico** (fx ≠ fy)  
- ➡️ **Traslación** en x, y  
- 🪞 **Espejo en eje X o en eje Y**  
- ⚫ **Conversión a escala de grises**  

Cada imagen puede recibir **una o varias transformaciones aleatorias**, generando nuevas versiones y aumentando el dataset.
