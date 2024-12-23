# **Análisis de Audio con FFT y Espectrograma**

Este proyecto es un programa en Python que permite analizar un archivo de audio mediante la **Transformada Rápida de Fourier (FFT)** y la generación de un **espectrograma**. El programa es ideal para analizar archivos de audio en formato  `.mp3`, `.m4a`, `.flac`, `.ogg` o `.wav`, y está diseñado para ejecutarse de manera ordenada en **Google Colab**.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lm9JrLej9Hl1wmHz5W-hrKvel5DmXF11#scrollTo=_JQu9bGiVt75)
---

## **Características principales**

1. **Transformada Rápida de Fourier (FFT)**:
   - Calcula la FFT del audio para analizar las frecuencias dominantes.
   - Muestra una gráfica de las magnitudes de las frecuencias.

2. **Espectrograma**:
   - Genera un espectrograma para visualizar la distribución de frecuencias a lo largo del tiempo.
   - Muestra la intensidad de las frecuencias en diferentes momentos del audio.

3. **Procesamiento automático**:
   - Carga automáticamente el archivo de audio desde la carpeta `transcribir`.
   - Verifica si el archivo está en formato `.mp3`, `.m4a`, `.flac`, `.ogg` o `.wav`.

4. **Resultados del Análisis**:


---

## **Cómo usar el programa**

### **1. Configuración del entorno**

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   cd tu-repositorio

2. **Instala las dependencias:**:
   ```bash
   pip install librosa matplotlib numpy scipy

3. **Crea la carpeta EVIDENCIAS:**: Coloca tu archivo de audio (`.mp3`, `.m4a`, `.flac`, `.ogg` o `.wav`) en la carpeta EVIDENCIAS.

**Créditos**
Este proyecto fue desarrollado por José R. Leonett. Si tienes alguna duda o sugerencia, no dudes en contactarme.

**Licencia**
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
