# **Análisis de audio con FFT y Espectrograma**

Este proyecto es un programa en Python que permite analizar un archivo de audio mediante la **Transformada Rápida de Fourier (FFT)** y la generación de un **espectrograma**. El programa es ideal para analizar archivos de audio en formato  `.mp3`, `.m4a`, `.flac`, `.ogg` o `.wav`, y está diseñado para ejecutarse de manera ordenada en **Google Colab**.

![image](https://drive.google.com/uc?export=view&id=1-4nfcJj0xPyVQ82EkxGZbPWw6L2Vy44o)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lm9JrLej9Hl1wmHz5W-hrKvel5DmXF11#scrollTo=_JQu9bGiVt75)
---
# Transformada Rápida de Fourier (FFT) y Espectrograma.

La **Transformada Rápida de Fourier (FFT)** es un algoritmo eficiente para calcular la **Transformada de Fourier Discreta (DFT)**, que convierte una señal del dominio del tiempo al dominio de la frecuencia. En términos simples, descompone una señal en sus componentes de frecuencia, permitiendo analizar qué frecuencias están presentes y con qué intensidad.

Un **espectrograma** es una representación visual de cómo las frecuencias de una señal varían con el tiempo. Se genera aplicando la FFT a segmentos cortos de la señal (ventanas de tiempo) y luego mapeando la intensidad de cada frecuencia en una gráfica 2D, donde:

- El eje **horizontal** representa el tiempo.
- El eje **vertical** representa la frecuencia.
- El **color o intensidad** indica la magnitud de cada componente frecuencial.

## **Características principales.**

1. **Transformada Rápida de Fourier (FFT)**:
   - Calcula la FFT del audio para analizar las frecuencias dominantes.
   - Muestra una gráfica de las magnitudes de las frecuencias.

2. **Espectrograma**:
   - Genera un espectrograma para visualizar la distribución de frecuencias a lo largo del tiempo.
   - Muestra la intensidad de las frecuencias en diferentes momentos del audio.

3. **Procesamiento automático**:
   - Carga automáticamente el archivo de audio desde la carpeta `transcribir`.
   - Verifica si el archivo está en formato `.mp3`, `.m4a`, `.flac`, `.ogg` o `.wav`.

---

## **Cómo usar el programa.**

### **1. Configuración del entorno.**

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/tu-repositorio.git
   cd tu-repositorio

2. **Instala las dependencias:**
   ```bash
   pip install librosa matplotlib numpy scipy

3. **Crea la carpeta llamada EVIDENCIAS:**

Coloca tu archivo de audio (`.mp3`, `.m4a`, `.flac`, `.ogg` o `.wav`) en la carpeta EVIDENCIAS y luego, pulsa el siguiente paso para que arroje el análisis en pantalla y en formato ZIP.


4. **Previo a darte el analisis espectografico y de fft, veras esto:**
  ```bash
  Procesando archivo: EVIDENCIAS/archivo_audio.audio
  Información técnica del archivo:

  [FORMAT]
   filename=EVIDENCIAS/archivo_audio.audio
   nb_streams=1
   nb_programs=0
   format_name=wav
   format_long_name=WAV / WAVE (Waveform Audio)
   start_time=N/A
   duration=616.360000
   size=29585324
   bit_rate=384000
   probe_score=99
  [/FORMAT]

  Análisis de transcodificación:
  El archivo ESTÁ transcodificado. El codec 'pcm_s16le' NO coincide con el formato 'wav'.
  ```
---
# Cómo citar este trabajo.
Usa la siguiente entrada BibTeX si utilizas este trabajo en tu investigación:
```bash
@article{joséRLeonett,
  title={Análisis FFT y Espectrográfico de audios},
  author={José R. Leonett},
  year={2024}
}
```

**Licencia.**
- Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
