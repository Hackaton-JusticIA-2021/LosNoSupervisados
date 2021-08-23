# Hackathon RIIAA 2021 "JusticIA para los desaparecidos"
# Extracción de texto

**Nombre del equipo**  
Los No Supervisados

**Integrantes**
* Juan Francisco Mandujano Reyes
* Daniela Andaluz Ramírez
* Judith Tabarez Rodríguez
* Erick Salvador Alvarez Valencia
* José Daniel Maldonado Núñez

## Descripión
Este flujo de trabajo resuelve la tarea de procesar imágenes, extraer texto e identificar entidades (nombres, lugares, organizaciones y fechas) de capturas de fichas de información tomadas entre 1965 y 1984 relacionadas con individuos desaparecidos en México

## Pipeline
1. La imagen entra al modelo, se corrige la calidad rotándola si es necesario y cambiando la escala de colores a blanco y negro.
2. Posteriormente se extrae el texto utilizando el framework pytesseract.
3. Luego, el texto extraído se somete a un proceso de limpieza: corrección ortográfica utilizando la librería de autocorrect de python y retirando caracteres especiales.
4. Finalmente el texto limpio entra al modelo para reconocer entidades generando un resultado en un archivo CSV.

## Cómo correr el código
Ejecutar el ipynb

## Notas
Acerca de los [README](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-readmes)

