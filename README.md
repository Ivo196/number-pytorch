# Tutorial PyTorch desde Cero

Este proyecto contiene un tutorial completo de PyTorch para clasificación de dígitos manuscritos usando el dataset MNIST.

## Descripción

El tutorial incluye:
- Introducción a tensores en PyTorch
- Carga y procesamiento de datos con torchvision
- Implementación de redes neuronales
- Entrenamiento y validación de modelos

## Estructura del Proyecto

```
Pythorch/
├── model.ipynb          # Notebook principal con el tutorial
├── requirements.txt     # Dependencias del proyecto
├── .gitignore          # Archivos ignorados por Git
└── README.md           # Este archivo
```

## Instalación

1. Clona el repositorio:
```bash
git clone <url-del-repositorio>
cd Pythorch
```

2. Instala las dependencias:
```bash
pip install -r requirements.txt
```

3. Ejecuta el notebook:
```bash
jupyter notebook model.ipynb
```

## Datos

El proyecto utiliza el dataset MNIST que se descarga automáticamente cuando ejecutes el notebook. Los datos se guardan en la carpeta `data/` (que está excluida del control de versiones).

## Notas

- Los datos de entrenamiento (carpeta `data/`) no se incluyen en el repositorio para mantener el tamaño reducido
- Los datos se descargan automáticamente al ejecutar el notebook
- Asegúrate de tener suficiente espacio en disco para los datos MNIST (~100MB) 