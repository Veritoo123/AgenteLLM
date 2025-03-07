# AgenteLLM

**Descripción General del Sistema**

Este sistema es un agente inteligente basado en modelos de lenguaje (LLM) diseñado para la generación automatizada de materiales educativos a partir de un plan de estudios (syllabus). Su objetivo es analizar documentos académicos estructurados, extraer información clave y generar contenido pedagógico de alta calidad en formato JSON y PDF.

**Principales Funcionalidades**

*Extracción de Información:*

- El sistema puede procesar documentos en PDF, DOCX y TXT, extrayendo su contenido mediante técnicas de procesamiento de texto.
- Extrae elementos clave del syllabus, como objetivos, competencias, metodologías y evaluaciones.
  
*Generación de Materiales Educativos:*

- Divide el curso en módulos y clases, asignando un número de sesiones adecuado según la duración del curso y la cantidad de clases por semana.
- Para cada clase, genera contenido estructurado, incluyendo:
  - Título de la clase
  - Objetivos específicos
  - Explicación teórica con ejemplos
  - Ejercicios prácticos con soluciones
  - Materiales complementarios

*Uso de Modelos de Lenguaje (LLM):*

- Utiliza un modelo de Google Gemini para generar contenido basado en instrucciones detalladas.
- Mantiene coherencia entre las clases a través de resúmenes acumulativos.

*Conversión de Materiales a PDF:*

- Convierte los materiales generados en formato Markdown a archivos PDF para facilitar su distribución y consulta.

*Automatización y Estructuración:*

- Todo el contenido se organiza en un formato JSON estructurado, lo que permite una fácil integración con otros sistemas de gestión educativa.
- Se genera un resumen del curso completo al finalizar el proceso.

**Objetivo del Sistema**

Facilitar la creación de materiales académicos estructurados para docentes y estudiantes, asegurando calidad pedagógica, accesibilidad y automatización en la generación de contenido educativo.
