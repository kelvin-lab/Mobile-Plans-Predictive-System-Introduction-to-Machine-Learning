
# Mobile Plans Predictive System - Introduction to Machine Learning

## Descripción del Proyecto
Este proyecto tiene como objetivo desarrollar un modelo predictivo que ayude a la compañía de telecomunicaciones Megaline a recomendar uno de sus nuevos planes móviles a sus clientes: **Smart** o **Ultra**. Utilizando datos históricos de comportamiento de los suscriptores, se implementa un modelo de clasificación que selecciona el plan más adecuado para cada cliente.

## Funcionalidades Principales
- **Análisis exploratorio de datos** para comprender el comportamiento de los clientes.
- **Preprocesamiento de datos**, que incluye limpieza y codificación de variables categóricas.
- **Entrenamiento de modelos de clasificación** como árboles de decisión, regresión logística, entre otros.
- **Evaluación de modelos** mediante métricas de rendimiento como la precisión.
- **Selección del modelo óptimo** según su desempeño en los datos de prueba.

## Tecnologías Utilizadas
- **Python**: Lenguaje principal utilizado para la manipulación y análisis de datos.
- **Pandas**: Biblioteca para la manipulación y análisis de datos.
- **Scikit-learn**:  Biblioteca para implementar algoritmos de Machine Learning.
- **Jupyter Notebook**: Entorno de desarrollo interactivo.

## Instrucciones de Uso

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/kelvin-lab/Mobile-Plans-Predictive-System-Introduction-to-Machine-Learning.git
   ```

2. **Instalar dependencias:**

   Asegúrate de tener un entorno virtual configurado, luego instala las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

3. **Abrir el notebook en Jupyter:**

   Ejecuta Jupyter Notebook desde la terminal o utiliza una plataforma como Google Colab para abrir el archivo `.ipynb`:

   ```bash
   jupyter notebook
   ```

4. **Ejecutar las celdas:**

   Sigue el flujo de trabajo desde la limpieza de datos hasta el análisis y la visualización de los resultados.

## Contribuciones
Las contribuciones para mejorar el análisis o agregar nuevas funcionalidades son bienvenidas. Sigue estos pasos para contribuir:
1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request para revisión.

## Autores
Este proyecto fue desarrollado por **Kelvin Trujillo**.

## Licencia
Este proyecto está bajo la Licencia MIT. Para más información, revisa el archivo [LICENSE](./LICENSE).

## Conclusiones
Este sistema predictivo demuestra que es posible utilizar datos de comportamiento de usuarios para mejorar la asignación de productos o servicios, como los planes móviles. El modelo implementado puede ser ajustado y mejorado para optimizar su precisión y adaptarse a cambios en el comportamiento de los clientes.
