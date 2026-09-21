# Evaluación Parcial 1 - Deep Learning (Fashion MNIST)

Este repositorio contiene el desarrollo y la implementación de un modelo de **Deep Learning** basado en un Perceptrón Multi-Capa (MLP) para la clasificación de imágenes del conjunto de datos **Fashion MNIST**.

---

## Integrantes del Equipo

* **Gabriel González Mundaca**
* **Sebastián Cornejo**
* **Alain González García**

* **Sección:** 003D
* **Docente:** Guillermo Pinto Fuentes

---

## Descripción del Proyecto

El objetivo del proyecto es solucionar un problema de clasificación multiclase utilizando un Perceptrón Multi-Capa (MLP) implementado en TensorFlow/Keras.

### El Dataset (Fashion MNIST)
* **Tamaño:** 70.000 imágenes en escala de grises de $28 \times 28$ píxeles.
* **Clases:** 10 categorías de prendas e indumentaria (T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot).
* **División de datos:**
  * **Entrenamiento:** 50.000 imágenes
  * **Validación:** 10.000 imágenes
  * **Prueba (Test):** 10.000 imágenes

---

## Requisitos Previos e Instalación

Para ejecutar este código de manera local o en la nube, asegúrate de tener instalados los siguientes requerimientos:

### Opción 1: En tu equipo local

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/alainfgg/DL_FashionMnist_EV1.git
   cd DL_FashionMnist_EV1
   ```

2. **Crear y activar un entorno virtual (recomendado):**
   ```bash
   # En Linux/macOS
   python -m venv venv
   source venv/bin/activate

   # En Windows
   python -m venv venv
   venv\Scripts\activate
   ```

3. **Instalar las librerías necesarias:**
   ```bash
   pip install tensorflow numpy pandas matplotlib seaborn scikit-learn jupyter
   ```

---

## Instrucciones de Ejecución

### 1. Ejecución Local con Jupyter Notebook / JupyterLab

Una vez instalado el entorno y sus dependencias, inicia Jupyter ejecutando:

```bash
jupyter notebook
```

Abre el archivo del notebook `.ipynb` presente en el repositorio y ejecuta las celdas en orden (de arriba a abajo).

### 2. Ejecución en Google Colab (Recomendado)

Si prefieres no instalar dependencias de forma local:

1. Ve a [Google Colab](https://colab.research.google.com/).
2. Selecciona la pestaña **GitHub**.
3. Pega la URL del repositorio: `https://github.com/alainfgg/DL_FashionMnist_EV1`.
4. Abre el notebook e inicia la ejecución de las celdas.

---

## Librerías Utilizadas

El proyecto utiliza los siguientes módulos de Python:
* `tensorflow` (Keras): Carga del dataset y construcción/entrenamiento del modelo.
* `numpy` & `pandas`: Manipulación y tratamiento de datos numéricos y estructuras de datos.
* `matplotlib` & `seaborn`: Visualización de imágenes, curvas de entrenamiento y gráficos.
* `scikit-learn`: Métricas de evaluación (matriz de confusión y reporte de clasificación).
