# Aspectos para pensar/trabajar en libro
Este es un registro de la charla entre MFR, JDL y WJ. @Uniandes 
El objetivo es trazar un plan de trabajo para la edición de un libro de enseñanza de la herramienta R para el análisis de datos en el contexto de la iniciativa de Aula Psicológica. 

## Instrucciones, filosofía y línea editorial
Si bien fue de lo que menos hablamos, debemos acordar una descripción de las cosas. Acordamos que este no es un libro de estadística *per se*, será un libro de estadistica en R. Al respecto, las invitaciones para los colaboradores deberan dejar en claro que se debe minimizar la justificación matemática de las técnicas estadísticas y destacar el aspecto de aplicación, y sus contextos, así como introducir de manera clara las rutinas y códigos de R respectivo. Sobre esto pensamos lo siguiente:
- Debe ser un libro abierto
- Debe tener un formato electrónico y potencialmente uno físico, pero este último es dispensable
- Debemos acordar unas instrucciones en las que se aclaren, al menos, los siguientes puntos:
    - Extensión
    - Plantilla de Rmarkdown para distribuir
    - Recomendaciones de escritura y estructuración del código. Al respecto podemos pensar en el standard de google (https://google.github.io/styleguide/Rguide.html), lo de Wickham (http://adv-r.had.co.nz/Style.html) o tal vez el que no logro recordar :/
    - Presencia web, formato y caracteristicas (vlog? video? demostración en pantalla?)
- **Propuesta JD:** Potencialmente podría ser bueno usar un formato que sea actualizable cuando sea necesario (por ejemplo, cambios en funciones, o aparición de nuevas funciones/paquetes que mejoren un proceso), sin necesidad de esperar a hacer una nueva edición. Esto podría ser complicado, pero lo propongo para discutirlo 

## Tareas administrativas 
Listar aquí las cosas que deben pasar a nivel institucional para hacer una co edición
- Determinar responsable uniandes de alianzas editoriales 
- Determinar posibilidad de alianza desde unibosque 

## Estructura libro (plan preliminar)
1.	Intro a R
2.	Análisis exploratorio de datos
    *	Incl. distribuciones
3.	Correlaciones en R
4.	Modelo lineal general (lm en R)
    *	Summary
    *	anova y car::Anova
    *	Regresión múltiple
5.	Regresión logística
6.	Interacciones
7.	Poder estadístico en R
8.	Análisis factorial
    *	Exploratorio
    *	Confirmatorio
9.	Metanálisis de correlaciones en R

## Posibles colaboradores - técnicas
Identificar posibles colaboradores y técnicas que potencialmente podemos incluir. En este momento todo y todos valen! 
- Francisco Cardozo - regresión
- Andrés Molano - Redes?
- Natalia Maldonado - Psicometria 
- Andres Montealegre - Test de equivalencia 
- JC Correa - Modelamiento 
- Javier Corredor - Score matching y similares
- Eugenio Valderrama - ??
- Juan David -- Simulación, poder estadístico, metanálisis de correlaciones y meta-regresión
- William & Maria Fernanda? - Ecuaciones estructurales
Maria Fernanda & Sandra? - Analisis exploratorio de datos
- Juan David & William - Visualización de datos en ggplot
- Bayes?
- Machine learning? (no sé si valga la pena, pero en tal caso yo incluiría solo algoritmos *out-of-the-box*)

## Libros publicados que sirvan como inspiración
Identificar recursos que sirvan como guia 

- [Learning Statistics with R](https://learningstatisticswithr.com/) - Navarro, D
- [Discovering Statistics with R](https://www.discoveringstatistics.com/books/discovering-statistics-using-r/) - Field
- [An adventure in statistics](https://www.discoveringstatistics.com/books/an-adventure-in-statistics/)  - Field
- [PsyTeachR](https://psyteachr.github.io/) - School of Psychology and Neuroscience, University of Glasgow 
