# 🎧 Déjame escuchar la música

## Descripción del proyecto

En este proyecto se analiza el comportamiento de escucha musical en línea de usuarios de dos ciudades ficticias: Springfield y Shelbyville. A partir de datos reales, el objetivo fue comprobar si existen diferencias significativas en la actividad musical de los usuarios según la **ciudad** y el **día de la semana**.

Este proyecto forma parte de mi formación en Ciencia de Datos con TripleTen, y está enfocado en la exploración, limpieza de datos y prueba de hipótesis.

---

## 📊 Dataset

- **Archivo**: `music_project_en.csv`
- **Columnas**:
  - `user_id`: identificador del usuario
  - `track`: canción reproducida
  - `artist`: artista de la canción
  - `genre`: género musical
  - `city`: ciudad del usuario
  - `time`: hora de reproducción
  - `day`: día de la semana

---

## 🛠 Tecnologías y librerías utilizadas

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-Used-green)
![Análisis de Datos](https://img.shields.io/badge/Análisis-Exploratorio-yellow)

- Python
- Pandas
- Jupyter Notebook o script `.py`
- Dataset ficticio proporcionado por TripleTen

---

## 🔍 Metodología

El proyecto se desarrolló en tres etapas principales:

1. **Descripción de los datos**  
   - Inspección del dataset.
   - Identificación de encabezados inconsistentes y valores faltantes.

2. **Preprocesamiento**
   - Limpieza de nombres de columnas.
   - Reemplazo de valores ausentes con `'unknown'`.
   - Eliminación de duplicados explícitos e implícitos (géneros como `hip`, `hop`, `hip-hop` → `hiphop`).

3. **Prueba de hipótesis**  
   - Hipótesis: “La actividad de los usuarios difiere según el día de la semana y la ciudad”.
   - Se evaluaron los datos de lunes, miércoles y viernes.
   - Se agruparon reproducciones por ciudad y día.
   - Se creó una función para contar el número de canciones reproducidas por ciudad/día.

---

## 📈 Resultados y conclusiones

- **Los datos mostraron que sí existen diferencias notables** en la actividad musical según la ciudad y el día.
- Springfield mostró mayor actividad ciertos días y Shelbyville en otros.
- La hipótesis se considera **válida**, aunque se recomienda en proyectos reales aplicar pruebas estadísticas más robustas.

---

## 🧠 Aprendizajes y desafíos

- Práctica intensiva de limpieza de datos con Pandas.
- Aplicación del enfoque dividir-aplicar-combinar (`groupby`).
- Primer acercamiento estructurado a la prueba de hipótesis.
- Corrección de errores comunes en entradas textuales y valores duplicados.

---

## 🚀 Cómo ejecutar este proyecto

1. Clona este repositorio:
```bash
git clone https://github.com/tu-usuario/dejame-escuchar-la-musica.git
cd dejame-escuchar-la-musica
