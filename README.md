# Red Neuronal Convolucional para la identificación de Malaria en Células

Este repositorio contiene un cuaderno de Jupyter (`on6.ipynb`) que implementa una CNN (Convolutional Neural Network) para detectar malaria en imágenes de frotis sanguíneo usando TensorFlow y Keras.

## Contenido
- `on6.ipynb`: Notebook principal con la explicación y el código completo para cargar el dataset, construir y entrenar la CNN, realizar predicciones y evaluar el modelo.
- `base.md`: (Documento auxiliar) - excluido del control de versiones por privacidad o formato intermedio.

## Requisitos (sistema)
- Python 3.8+ (recomendado 3.10+)
- Pip (gestor de paquetes)

## Instalación (entorno recomendado)
1. Crear un entorno virtual (opcional, recomendado):

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

2. Instalar dependencias (ejemplo):

```bash
pip install --upgrade pip
pip install tensorflow tensorflow-datasets matplotlib seaborn scikit-learn
```

> Nota: Ajusta las versiones de `tensorflow` si usas GPU o una versión concreta de CUDA.

## Uso
1. Abrir el cuaderno `on6.ipynb` en Jupyter Notebook o JupyterLab:

```bash
jupyter notebook on6.ipynb
# o
jupyter lab
```

2. Ejecutar las celdas en orden: carga y preprocesamiento, construcción del modelo, entrenamiento y evaluación.

3. Configura parámetros como `IMG_SIZE`, `BATCH_SIZE`, y `epochs` en el notebook según tus recursos.

## Notas sobre `base.md`
`base.md` es un documento con información adicional. Se excluye del control de versiones por contener contenidos auxiliares no necesarios en el repositorio público.

Si ya está en el historial de Git y deseas eliminarlo del control de versiones, ejecuta:

```bash
# Eliminarlo del tracking conservando el archivo localmente
git rm --cached base.md
git commit -m "Excluir base.md del control de versiones"
```

## Mejoras futuras
- Data augmentation y regularización para evitar overfitting.
- Transfer learning con modelos preentrenados (ResNet, EfficientNet).
- Experimentos con distintos tamaños de imagen y aumentos.

## Autor
- Eduardo Efrain Garcia Sarez  — Instituto Tecnológico Superior de Jalisco (TSJ)

---
Fecha: 12/12/2025
