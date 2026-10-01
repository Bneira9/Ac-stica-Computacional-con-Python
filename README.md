# Exploración y Clasificación Acústica de Géneros Musicales

## Integrantes
- Benjamín Neira Provoste

## Idea del proyecto
Construir un programa que analice canciones y permita identificar a qué género musical pertenecen mediante la extracción de sus características sonoras.

## Pregunta principal
¿Qué características acústicas y visuales (espectrogramas) permiten describir y diferenciar mejor los distintos géneros musicales?.

## Motivación
El interés principal es aplicar herramientas computacionales a un problema cotidiano como la música, aprendiendo en el proceso sobre procesamiento de señales de audio y conceptos básicos de aprendizaje de máquina.

## Datos
- Fuente: Dataset público (posiblemente GTZAN o algún otro, todavía por confirmar).
- Tipo de datos: Grabaciones musicales.
- Formato: Archivos de audio (esperamos `.wav` o `.mp3`).
- Cantidad aproximada: Por definir según el dataset seleccionado. De momento el mínimo de 1 canción para pruebas.
- Etiquetas disponibles: Sí, géneros predefinidos (rock, jazz, clásica, etc.).
- Aspectos que todavía debemos investigar: La efectiva búsqueda de Datasets confiables y de buena calidad, y cómo descargar y cargar estos datos eficientemente en Python.

## Alcance inicial
**Objetivo inicial:**
Obtener el dataset de canciones, comprender su estructura, generar espectrogramas para comparar visualmente los géneros y extraer características acústicas clave usando `librosa` o algún similar.

**Si existe tiempo:**
Implementar un modelo básico de clasificación y evaluar su desempeño para predecir géneros nuevos.

## Pipeline provisional
búsqueda y descarga de audios
↓
auditoría de los datos
↓
generación de espectrogramas
↓
extracción de características acústicas
↓
exploración visual de diferencias
↓
¿clasificación automática?

## Posibles dificultades
- Capacidad computacional para procesar cientos de archivos de audio.
- Desconocimiento inicial de metodologías de clasificación.
- Tiempo disponible para entrenar modelos complejos.

## Estado actual
Hemos configurado el entorno aislado (`acus220_2026`) con las librerías necesarias, comprobado su funcionamiento en Jupyter y estructurado el documento base del proyecto.

## Próximos pasos
1. Crear un repositorio en GitHub para respaldar esta estructura inicial[cite: 61].
2. Buscar, descargar y explorar el primer archivo de audio de prueba[cite: 61].
3. Crear un notebook de exploración para visualizar el primer espectrograma musical[cite: 61].

cambiar estos ultimos dos puntos!!!!