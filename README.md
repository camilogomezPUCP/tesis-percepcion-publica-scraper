# Tesis: Sistema de Análisis de Percepción Pública

Prototipo de módulo de recopilación de datos para tesis de pregrado en Ingeniería Informática, orientada al análisis de percepción pública de figuras políticas peruanas en redes sociales mediante NLP.

**Asesor:** Prof. Edwin Villanueva Talavera  
**Institución:** Pontificia Universidad Católica del Perú

## Alcance de este prototipo

Este repositorio contiene un script de recopilación de datos vía PRAW (Reddit API) en modo **exclusivamente de lectura**, orientado a validar el repositorio estructurado (PostgreSQL) diseñado para el proyecto.

- No publica, comenta, vota ni interactúa con Reddit de ninguna forma.
- Recolecta publicaciones y comentarios públicos que mencionan un conjunto acotado de figuras políticas peruanas.
- Almacena los datos en una base de datos PostgreSQL local, de uso exclusivamente académico y privado.

## Estado

🚧 Prototipo en desarrollo — parte de un proyecto de tesis en curso.

## Stack

- Python
- PRAW (Python Reddit API Wrapper)
- PostgreSQL / psycopg2

## Estructura
├── scraper/ # Lógica de conexión y recolección vía PRAW <br>
├── db/ # Funciones de inserción a PostgreSQL <br> 
├── requirements.txt  <br>
└── .env.example # Variables de entorno necesarias (sin valores reales)  <br>

## Nota

Este repositorio no incluye credenciales, datos recolectados ni información personal de usuarios de Reddit.
