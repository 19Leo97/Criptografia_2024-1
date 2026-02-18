# Criptografía Musical: Configuración de Brauer

Este repositorio contiene una implementación en Python (Jupyter Notebook) diseñada para el análisis, cifrado y descifrado de mensajes utilizando conceptos de **Criptografía** y la teoría de **Configuraciones de Brauer** aplicada a la música.

El proyecto permite transformar mensajes de texto en secuencias de notas musicales (tonos y tiempos) y viceversa, calculando propiedades algebraicas y generando representaciones visuales de las estructuras resultantes.

## 🚀 Contenido del Proyecto

* **`Configuracion_Brauer.ipynb`**: Notebook principal con la lógica del sistema:
    * Diccionarios musicales para **Clave de Sol** y **Clave de Fa**.
    * Funciones de mapeo entre caracteres y tuplas de (nota, duración).
    * Cálculo de la **Valencia**, **Multiplicidad** y **Dimensión del Álgebra**.
    * Generación automática de **Quivers** (grafos dirigidos) para visualizar sucesores.

## 🛠️ Funcionalidades

### 1. Cifrado y Descifrado Musical
El sistema utiliza diccionarios especializados que permiten la conversión técnica de mensajes:
- **Clave de Fa**: Orientada a registros bajos (ej. Bajo Continuo).
- **Clave de Sol**: Orientada a melodías estándar.

### 2. Análisis de Configuración de Brauer
La clase `Mensaje` procesa las secuencias musicales para:
- Limpiar y normalizar los datos de entrada.
- Determinar la estructura algebraica de la configuración.
- Generar el Quiver asociado mediante la librería `graphviz`.

### 3. Visualización
Utiliza `matplotlib` y `IPython.display` para mostrar los resultados del descifrado y las propiedades del álgebra de una manera clara y académica.

## 📦 Requisitos

Para ejecutar el código, asegúrate de tener instaladas las siguientes dependencias:

```bash
pip install matplotlib graphviz
