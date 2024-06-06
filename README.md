# Integradora-Practica02-3B
En esta práctica aprenderemos a utilizar las herramientas de Git y Github para el control de Versiones, Documentación, Desarrollo Colaborativo y Respaldo del Proyecto Integrador para la Asignatura de Integradora I
## Comandos Básicos para la Documentación, utilizando el estandar se Markdown (md)
Markdown es el estandar utilizado por Git y Github, para maquetar la documentacion de proyectos, lo que permite a usuarios y colaboradores del proyecto entender el contexto y operacion del mismo
### 1. Encabezados o Titulos (Headers)
Para poder realizar una buena documentacion del proyecto debemos, distribuir correctamente el contenido, para poder delimitar o hacer enfasis (enfatizar), es deir resaltar las secciones importantes, podemos utilizar los siguientes:
EJEMPLOS:
# Encabezado de Nivel 1 - Similar a H1 en HTML
## Encabezado de Nivel 2 - Similar a H2 en HTML
### Encabezado de Nivel 3 - Similar a H3 en HTML
#### Encabezado de Nivel 4 - Similar a H4 en HTML
##### Encabezado de Nivel 5 - Similar a H5 en HTML
###### Encabezado de Nivel 6 - Similar a H6 en HTML
####### Encabezado de Nivel 7 - Solo 6 niveles son permitidos dentro de la sintaxis, a partir de este el maquetado sera ignorado
### 2. Separadores (SEPARATORS)
Si se desea marcar una separacion mas visual de contenidos podemos utilixarlos indicando tres caracteres de "-" continuos en el maquetado
EJEMPLO:
---
"Esto es similar a un tag de <"hr"> en HTML.
### 3. Párrafos (Paragraphs)
Son utilizafos para poder presentar grandes secciones de texto que describen deetalladamentelas secciones de la documentacion del proyecto
EJEMPLOS:
Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1. Este texto pretenece al Parrafo 1.
<p>
Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2. Este texto pretenece al Parrafo 2.  </p>
Lo que en una pagina utilizariamos la etiqueta < P >
tambien podemos aplicar estilos de alineacion:

<p align = left>
Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.Parrafo de alineacion derecha.
</p>
<p align = center>
Parrafo de alineacion central. Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.Parrafo de alineacion central.
</p>
<p align = right>
Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. Parrafo de alineacion izquierda. 
</p>
<p align = justify>
Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. Parrafo de alineacion justificada. 
</p>
### 4. Texto Enfatizado (BOLD, ITALIC, BOLD/ITALIC)
Si el texto que deseamos enfatizar se encuentra en un parrafo podemos utilizar algunos trucos para ubicarlos en la documentación
#### Texto en negrita (BOLD)
Para poder poner el texto en negrita este debera ser encerrado entre dos *.
EJEMPLO:
Texto Texto Texto *Texto* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto
#### Texto en cursiva (ITALIC)
Para poder poner el texto en cursiva este debera ser encerrado entre dobles **.
EJEMPLO:
Texto Texto Texto *Texto* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto **Texto** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto
#### Texto en negrita cursiva (BOLD/ITALIC)
Para poder poner el texto en negrita y ademas en cursiva este debera ser encerrado entre triples ***.
EJEMPLO:
Texto Texto Texto ***Texto*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto ***Texto*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto
