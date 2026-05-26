# Predicción de Demanda para Retail

## Setup

### Requisitos previos
- Python 3.11.9
- pip

### Instalación

1. **Clonar o descargar el repositorio**
   ```bash
   cd Predicci-n-de-demanda-para-Retail
   ```

2. **Crear entorno virtual**
   ```bash
   python -m venv venv
   ```

3. **Activar el entorno virtual**
   
   En Windows:
   ```bash
   venv\Scripts\activate
   ```
   
   En macOS/Linux:
   ```bash
   source venv/bin/activate
   ```

4. **Instalar dependencias**
   ```bash
   pip install -r requirements.txt
   ```

5. **Preparar datos**
   - Coloca los archivos CSV (`productos.csv`, `ventas.csv`) en la carpeta `data/`
   - Para pruebas rápidas, usa los datos de muestra en `data_sample/`

6. **Ejecutar los cuadernos**
   ```bash
   jupyter notebook notebooks/
   ```

## Estructura del Proyecto

```
.
├── requirements.txt          # Dependencias del proyecto
├── README.md                 # Este archivo
├── .gitignore               # Archivos a ignorar en git
│
├── data/                    # Datos reales
├── data_sample/             # Datos para test
│   ├── productos.csv
│   └── ventas.csv
│
├── models/                  # Modelos entrenados
└── notebooks/               # Cuadernos Jupyter
    ├── EDA.ipynb           # Análisis exploratorio de datos
    └── Modelado.ipynb      # Desarrollo y entrenamiento de modelos
```
