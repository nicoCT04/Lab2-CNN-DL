# Laboratorio #2 — Redes Neuronales Convolucionales (CNN)

**CC3092 - Deep Learning y Sistemas Inteligentes** · Universidad del Valle de Guatemala

Clasificación de dígitos manuscritos del dataset **MNIST** (0-9), comparando dos
arquitecturas de red neuronal:

- **MLP** — recibe la imagen aplanada (784) como vector de entrada.
- **CNN** — recibe la imagen como tensor 2D y usa capas convolucionales.

## Contenido

| Ruta | Descripción |
|------|-------------|
| `notebook/Lab2_CNN_MNIST.ipynb` | Notebook completo: carga y preparación de datos, investigación de capas, definición de ambos modelos, 12 iteraciones de búsqueda de hiperparámetros y evaluación final sobre test. |
| `reports/` | Figuras y tablas exportadas para el informe. |
| `requirements.txt` | Dependencias del proyecto. |

## Reproducir

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab   # abrir notebook/Lab2_CNN_MNIST.ipynb
```

El dataset MNIST se descarga automáticamente vía `torchvision.datasets.MNIST`
(no se versiona; ver `.gitignore`).

## Autor

Nicolás Concuá
