# Taller Integrador — Módulo 1: Análisis de Salud Mundial
## Máster en IA & Data Science | DevSeniorCode

**Estudiante:** Erick Santiago Muñoz Daza  
**Fecha de entrega:** 29 de marzo de 2026  
**Repositorio GitHub:** [https://github.com/Erick6485/IA_Data_Science_Dev.git](https://github.com/Erick6485/IA_Data_Science_Dev.git)

---

## Descripción del Proyecto
Este proyecto forma parte del Módulo 1 del Máster en IA & Data Science. Consiste en un análisis exploratorio de datos (EDA) aplicado a un dataset de indicadores de salud global para **159 países**. 

El objetivo es demostrar el dominio de:
*   **Python Fundamental:** Estructuras de control, funciones y diccionarios.
*   **Pandas:** Carga, limpieza, filtrado, agrupación y transformación de datos.
*   **Git & GitHub:** Control de versiones y documentación profesional.

## Contenido del Dataset
El archivo `salud_mundial.csv` incluye variables críticas como:
*   **Demográficas:** Nombre del país, región y nivel de ingresos.
*   **Salud:** Esperanza de vida, gasto en salud (USD), mortalidad infantil y médicos por cada 1,000 habitantes.
*   **Hábitos y Entorno:** % de obesidad, diabetes, tabaquismo y población urbana.

## Instrucciones de Ejecución
Para replicar este análisis en tu entorno local:

1. **Clonar el repositorio:**
    git clone [https://github.com/Erick6485/IA_Data_Science_Dev.git](https://github.com/Erick6485/IA_Data_Science_Dev.git)

2. **Instalar las dependencias necesarias:**
    - Abre el archivo `.ipynb` en VS Code.
    - Verifica que el archivo `salud_mundial.csv` se encuentre.
    - Ejecuta todas las celdas (Kernel → Restart & Run All).

3. **Instalar las dependencias necesarias:**
    Asegurarse de tener Instalada la libreria de Pandas:
    `pip install pandas`

## Hallazgos y Conclusiones
1. **Desigualdad en el Gasto:** Existe una correlación marcada entre el nivel de ingresos y el gasto en salud, lo que impacta directamente en la esperanza de vida de las regiones analizadas.

2. **Mortalidad e Ingresos:** Los países con nivel de ingresos "Low" presentan las tasas de mortalidad infantil más elevadas, subrayando la necesidad de fortalecer los sistemas de salud primaria en esas zonas.

3. **Éxito en Vacunación:** Se identificó un alto porcentaje de países que superan el 90% de cobertura de vacunación, lo cual coincide con una mejor clasificación en la categoría de esperanza de vida "Alta".

## Tecnologías Usadas
- Python 3.11.5
- Pandas (Análisis de datos)
- Jupyter Notebook (Entorno de desarrollo)
- Git & GitHub (Control de versiones)