# 🛰️ Prueba Técnica – Análisis de Imágenes TIFF y Cálculo NDVI

## 🎯 Objetivo

Evaluar las habilidades del candidato en:
- Procesamiento de imágenes raster (formato TIFF).
- Manipulación de datos geoespaciales.
- Desarrollo de funcionalidades interactivas orientadas al análisis visual y cuantitativo de imágenes satelitales.

---

## 📋 Requerimientos Técnicos

### 1. Carga de Imagen TIFF Multiespectral
- El sistema debe cargar y visualizar imágenes en formato TIFF.

### 2. Selección de Área de Interés (ROI – Region of Interest)
- El usuario debe poder seleccionar manualmente un área rectangular dentro de la imagen mediante una herramienta gráfica (ej. "marquee tool").
- La selección debe ser visible (resaltada con borde o sombreado).

### 3. Marcado y Comentario
- Tras seleccionar una región, el usuario podrá etiquetarla con un comentario personalizado (ej: “Vegetación densa”, “Área deforestada”).
- Se debe guardar el comentario junto con las coordenadas de la región seleccionada.

### 4. Cálculo de NDVI (Índice de Vegetación de Diferencia Normalizada)
- Sobre el área seleccionada, el sistema calculará el índice NDVI.
- Se debe mostrar un resumen estadístico del NDVI:
  - Valor mínimo
  - Valor máximo
  - Promedio
  - Desviación estándar
- **Opcional:** Visualización del mapa NDVI completo como imagen de calor (heatmap).

---

## 🚚 Entrega Esperada

- Código fuente bien estructurado y comentado.
- Código desplegado y accesible mediante un enlace de prueba (test link).
- Interfaz gráfica funcional (web o escritorio).
- Instrucciones claras para ejecutar la aplicación localmente.
- Documentación técnica breve describiendo:
  - Dependencias
  - Supuestos realizados

---

## 🛠️ Tecnologías Sugeridas (no obligatorias)

### Python
- `rasterio`
- `numpy`
- `matplotlib`
- `PyQt5` o `Streamlit`

### Alternativamente, JavaScript
- `GeoTIFF.js`
- `Leaflet`
- WebGL

---

## 🗓️ Duración Estimada

- Fecha límite de entrega: **Lunes 12 de Mayo de 2025**

---

