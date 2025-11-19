# Hooke

Repositorio con una evaluación práctica de la Ley de Hooke para la asignatura Física General I – Laboratorio.

## Contenido
- `Evaluacion_Ley_de_Hooke_Aleatoria_executable.ipynb`  
  Cuaderno Jupyter/Colab que:
  - Genera datos aleatorios simulando mediciones para la Ley de Hooke.
  - Grafica la fuerza vs elongación y realiza un ajuste lineal.
  - Calcula la constante elástica estimada (k_estimada).
  - Incluye una validación automática que compara k_estimada con k_real (±5%).

## Requisitos
- Python 3
- Paquetes de Python:
  - numpy
  - pandas
  - matplotlib
  - scipy

Instalación rápida:
```bash
pip install numpy pandas matplotlib scipy
```

## Uso
- Google Colab:
  1. Subir o abrir `Evaluacion_Ley_de_Hooke_Aleatoria_executable.ipynb` en Colab.
  2. Runtime → Run all para ejecutar todas las celdas.
  3. Revisar la tabla de datos, la gráfica y los mensajes impresos (k_estimada, R y resultado de validación).

- Local:
  1. Abrir el notebook en Jupyter Notebook / JupyterLab.
  2. Ejecutar las celdas en orden.
  3. Asegurarse de tener las dependencias instaladas.

## Sugerencias para el docente
- Para entregar a estudiantes: reactivar la celda con `input()` si se desea que ingresen su propio k.
- Para evaluación automática: ajustar la tolerancia en la celda de validación (actualmente ±5%).

## Contacto
Para cualquier ajuste (cambiar tolerancia, modificar validación a interactiva, añadir salidas ejecutadas) contactar al mantenedor del repositorio.
README.md
