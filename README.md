# 📸 Data Augmentation Geométrico

Este proyecto implementa aumentación de datos para un dataset pequeño de imágenes (8) aplicando transformaciones geométricas como rotación, escalamiento, traslación, espejos y conversión a escala de grises.  
El objetivo es **generar más datos de entrenamiento** para modelos de visión por computadora a partir de un conjunto limitado de imágenes originales.

## 🎯 Objetivos
- Comprender y aplicar transformaciones geométricas básicas.  
- Implementar rotación, escalamiento, traslación y simetrías.  
- Guardar las imágenes resultantes para su posterior análisis.


## ✨ Transformaciones implementadas
- 🔄 **Rotación** con ajuste de tamaño  
- 📏 **Escalamiento uniforme** (a=b)  
- 📐 **Escalamiento anisotrópico** (fx ≠ fy)  
- ➡️ **Traslación** en x, y  
- 🪞 **Espejo en eje X o en eje Y**  
- ⚫ **Conversión a escala de grises**  

Cada imagen puede recibir **una o varias transformaciones aleatorias**, generando nuevas versiones y aumentando el dataset.

## 📂 Organización
📦 Vision_en_Robotica
- 📂 Mini_Proyecto_1
  - 📂 imagenes # Carpeta con resultados
  - 📜  main.py # Código fuente
  - 📜 README.md # Documento explicativo

Como resultados, se genera una carpeta que contiene las imágenes modificadas


## Autores:
Paulina Gómez Olvera Carpinteyro [paulina.gomezolveraco@udlap.mx]
David León Céspedes [david.leoncso@udlap.mx]
Juan Pablo Rosas Pineda [juan.rosaspa@udlap.mx]
