# Análisis de Diagnóstico de Diabetes con el Teorema de Naïve Bayes

## Descripción del Proyecto
Este proyecto analiza un conjunto de datos de Kaggle sobre el diagnóstico de diabetes utilizando el Teorema de Naïve Bayes. Los datos provienen originalmente del Instituto Nacional de Diabetes y Enfermedades Digestivas y Renales. El objetivo es predecir si un paciente tiene diabetes en función de diversas mediciones diagnósticas.

## Conjunto de Datos
El conjunto de datos se compone de información recopilada de mujeres de al menos 21 años de edad de ascendencia indígena Pima. Contiene las siguientes características:

- **Embarazos**: Número de veces embarazadas  
- **Glucosa**: Concentración de glucosa plasmática a 2 horas en una prueba de tolerancia oral a la glucosa  
- **Presión arterial**: Presión arterial diastólica (mm Hg)  
- **Grosor de la piel**: Grosor del pliegue cutáneo del tríceps (mm)  
- **Insulina**: Insulina sérica de 2 horas (mu U/ml)  
- **IMC**: Índice de masa corporal (peso en kg/(altura en m)^2)  
- **DiabetesPedigríFunción**: Función del pedigrí de la diabetes  
- **Edad**: Edad en años  
- **Resultado**: Variable de clase (0: No tiene diabetes, 1: Tiene diabetes)  

## Tecnologías Utilizadas
- Python 3  
- Pandas y NumPy para manipulación y análisis de datos  
- Scikit-learn para la implementación del clasificador Naïve Bayes  
- Matplotlib y Seaborn para visualización de datos
  
## Estructura del Proyecto
```
📂 Abalisis-Datos-Naives
│── 📂 data  # Datos generados para las pruebas
│── 📂 results  # Resultados y análisis comparativo
│── 📄 README.md  # Documentación del proyecto
│── 📄 Diabetes_Analisis con Bayes.ipynb  # Implementación en Jupyter Notebook
```

## Instalación y Requisitos
Para ejecutar el proyecto, necesitas tener instalado:
- **Python 3.x**
- **Jupyter Notebook**
- **Librerías necesarias** (se pueden instalar con pip):
  ```bash
  pip install notebook
  ```

## Uso
1. Clona este repositorio:
   ```bash
   git clone https://github.com/Jair-Artreaga/Analisis-Datos-Naives.git
   ```
2. Accede al directorio del proyecto:
   ```bash
   cd Diabetes_Analisis con Bayes
   ```
3. Ejecuta Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Abre el archivo `Diabetes_Analisis con Bayes.ipynb` y ejecuta las celdas para ver los resultados.

## Resultados y Conclusiones
Se evaluó la precisión del modelo utilizando una división de datos de entrenamiento y prueba.
Se analizaron las principales variables que influyen en la predicción de diabetes.
Se identificaron posibles mejoras en la calidad de los datos y técnicas para optimizar el rendimiento del modelo.
Contribuciones
Las contribuciones son bienvenidas. Para colaborar:

## Contribuciones
Si deseas contribuir a este proyecto:
1. Haz un fork del repositorio.
2. Crea una rama con tus cambios: `git checkout -b nueva-funcionalidad`
3. Realiza un commit de los cambios: `git commit -m 'Añadir nueva funcionalidad'`
4. Sube los cambios: `git push origin nueva-funcionalidad`
5. Abre un Pull Request.

## Autor
**[Roberto Jair Arteaga Valenzuela]**
