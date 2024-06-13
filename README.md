# Práctica 2 FSI 

**Curso**: Segundo  
**Grado**: Grado en Ciencia e Ingeniería de Datos  
**Escuela**: Escuela de Ingeniería Informática  
**Universidad**: Universidad de Las Palmas de Gran Canaria (ULPGC)  
**Autor**: Pablo Guilló

## Descripción
Detector de personas desarrollado en python con opencv. Combina detección con Haar Cascade, seguimiento con `cv2.TrackerKCF_create`, y re-identificación usando Template Matching.

## Funcionalidades
- **Detección con Haar Cascade**: Identifica personas en un video utilizando el clasificador Haar.
- **Seguimiento con KCF Tracker**: Rastrea personas detectadas a lo largo del tiempo.
- **Re-identificación con Template Matching**: En caso de pérdida de seguimiento, utiliza Template Matching para relocalizar a la persona.
- **Gestión de Trackers**: Mantiene y actualiza trackers basándose en su "vida" implementando tiempos máximos.
- **Identificación Visual**: Cada persona es identificada con un color único y un ID.

## Tecnologías Utilizadas
- Python: Lenguaje de programación principal del proyecto.
- OpenCV: Biblioteca de visión por computadora utilizada para todas las operaciones de detección, seguimiento y re-identificación.

## Recursos Utilizados
- [Chat de OpenAI](https://chat.openai.com)
