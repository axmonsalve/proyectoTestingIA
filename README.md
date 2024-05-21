# Proyecto de Testing de IA

Este proyecto tiene como objetivo desarrollar un conjunto de pruebas automatizadas para evaluar el rendimiento y la precisión de un sistema de inteligencia artificial. El enfoque principal es probar la capacidad del sistema para proporcionar respuestas precisas y relevantes a una serie de preguntas predefinidas.

## Características

- **Pruebas Automatizadas**: Uso de Selenium para automatizar la interacción con la interfaz de usuario del sistema de IA.
- **Evaluación de Desempeño**: Análisis de la precisión, recall y F1-score de las respuestas del sistema usando scikit-learn.
- **Generación de Informes**: Visualización de los resultados de las pruebas con pandas y matplotlib.
- **Feedback Continuo**: Sistema simple de recolección de feedback para mejorar continuamente las pruebas.

## Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal.
- **Selenium**: Herramienta para la automatización de navegadores.
- **pandas**: Biblioteca para manipulación y análisis de datos.
- **scikit-learn**: Biblioteca para aprendizaje automático y métricas de evaluación.
- **matplotlib**: Biblioteca para visualización de datos.

## Estructura del Proyecto

- `test_ia.py`: Script principal para la ejecución de las pruebas.
- `preguntas_respuestas.csv`: Archivo con el conjunto de preguntas y respuestas esperadas.
- `README.md`: Documentación del proyecto.
- `.gitignore`: Archivo para excluir archivos innecesarios del repositorio.
- `venv/`: Entorno virtual para gestionar las dependencias.

## Instalación y Configuración

1. Clona el repositorio:
   ```sh
   git clone https://github.com/tu-usuario/proyectoTestingIA.git
   cd proyectoTestingIA
   ```

2. Crea y activa un entorno virtual:
   ```sh
   python3 -m venv venv
   source venv/bin/activate  # En Windows usa `venv\Scripts\activate`
   ```

3. Instala las dependencias:
   ```sh
   pip install -r requirements.txt
   ```

## Ejecución de Pruebas

1. Ejecuta el script de prueba inicial para verificar las instalaciones:
   ```sh
   python test_ia.py
   ```

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para sugerencias y mejoras.

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).

