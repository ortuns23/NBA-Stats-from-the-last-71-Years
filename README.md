**Estadísticas de la NBA de los últimos 71 años**

Este repositorio contiene un conjunto de datos detallado sobre las estadísticas de jugadores y equipos de la NBA de las últimas 71 temporadas. Los datos incluyen una amplia gama de estadísticas, como puntos, asistencias, rebotes y más.

Descripción del Conjunto de Datos

Fuente: Kaggle - Estadísticas de la NBA de los últimos 71 años
Cobertura Temporal: Desde la temporada 1951-1952 hasta la temporada 2021-2022

Contenido:

Estadísticas de jugadores: puntos, asistencias, rebotes, robos, tapones, porcentaje de tiros, entre otros.
Estadísticas de equipos: victorias, derrotas, puntos por juego, eficiencia ofensiva y defensiva, entre otros.

Archivos Incluidos

players_stats.csv: Estadísticas individuales de jugadores por temporada.
teams_stats.csv: Estadísticas de equipos por temporada.
games_stats.csv: Estadísticas detalladas de juegos específicos.
playoffs_stats.csv: Estadísticas de jugadores y equipos en playoffs.

Requisitos Previos

Para utilizar este conjunto de datos, necesitarás tener instalado:

Python
pandas

Uso

Clona este repositorio en tu máquina local:
bash
Copiar código
git clone https://github.com/tu_usuario/nba-stats-71-years.git

Navega al directorio del proyecto:

bash
Copiar código
cd nba-stats-71-years

Carga los datos en tu entorno de análisis preferido. Aquí hay un ejemplo utilizando pandas:

python
Copiar código
import pandas as pd

players_stats = pd.read_csv('players_stats.csv')
teams_stats = pd.read_csv('teams_stats.csv')
games_stats = pd.read_csv('games_stats.csv')
playoffs_stats = pd.read_csv('playoffs_stats.csv')

Análisis Ejemplares

Comparación de Jugadores: Compara el rendimiento de jugadores legendarios a lo largo de los años.
Tendencias de Juego: Analiza cómo han cambiado las tendencias y estrategias de juego en diferentes épocas.
Eficiencia de Equipos: Evalúa la eficiencia ofensiva y defensiva de equipos en distintas temporadas.

Contribuciones

Las contribuciones son bienvenidas. Si encuentras algún problema o tienes sugerencias para mejorar este conjunto de datos, por favor abre un issue o envía un pull request. Asegúrate de seguir las pautas de contribución del proyecto.

Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para obtener más detalles.

Agradecimientos
Agradecimientos especiales a Ricardo Torres Heredia por compilar y compartir este valioso conjunto de datos en Kaggle.

