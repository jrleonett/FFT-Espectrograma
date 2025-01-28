# **Análisis de audio con FFT y Espectrograma**
![Licencia](https://img.shields.io/badge/Licencia-GNU%20GPL%20v3-blue)
![GitHub](https://img.shields.io/badge/Python-3.8%2B-green)
![GitHub](https://img.shields.io/badge/Estado-Activo-brightgreen)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)


Este proyecto es un programa en Python que permite analizar un archivo de audio mediante la **Transformada Rápida de Fourier (FFT)** y la generación de un **espectrograma**. El programa es ideal para analizar archivos de audio en formato  `.mp3`, `.m4a`, `.flac`, `.ogg` o `.wav`, y está diseñado para ejecutarse de manera ordenada en **Google Colab** o en **Gradio**. Desarrollado por **José R. Leonett** para la comunidad de Peritos Forenses Digitales de Guatemala www.forensedigital.gt 

<p align="center">
  <img src="https://github.com/jrleonett/FFT-Espectrograma/blob/main/congradio.png?raw=true">
</p>
👉 <strong>Pruébalo aquí</strong>: <a href="https://huggingface.co/spaces/leonett/FFT-Espectrograma">FFT-Espectrograma</a>


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

El programa utiliza **Gradio** para proporcionar una interfaz gráfica fácil de usar. Gradio permite cargar archivos de audio, procesarlos y mostrar los resultados en tiempo real. La aplicación está alojada en **Hugging Face Spaces** para que puedas usarla directamente desde tu navegador sin necesidad de instalar nada.

## **Funcionalidades de la interfaz**
- **Carga de archivos**: Permite subir archivos de audio en formatos compatibles (.mp3, .wav, etc.).
- **Procesamiento**: Realiza el análisis de FFT (Transformada Rápida de Fourier) y genera el espectrograma del archivo de audio.
- **Resultados**: Muestra las gráficas de la forma de onda, FFT y espectrograma, junto con información técnica del archivo.

## **Cómo usar la interfaz**
1. Accede a la aplicación en Hugging Face Spaces. 👉 <strong>Pruébalo aquí</strong>: <a href="https://huggingface.co/spaces/leonett/FFT-Espectrograma">FFT-Espectrograma</a>
2. Sube un archivo de audio utilizando el botón de carga.
3. Espera a que el programa procese el archivo y muestre los resultados.

![image](https://drive.google.com/uc?export=view&id=1-4nfcJj0xPyVQ82EkxGZbPWw6L2Vy44o)

----

## **Previo a darte el analisis espectografico y de fft, veras esto:**
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
- Este proyecto está bajo la licencia GNU General Public License v3.0. Consulta el archivo LICENSE para más detalles.
