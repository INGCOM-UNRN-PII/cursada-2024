# Practicas 2024

Aquí se encuentran todas las practicas emitidas durante el ciclo lectivo 2024.

## Proyectos

Todas las practicas hacen uso del [proyecto-gradle](proyecto-gradle-main.zip),
un proyecto de Gradle con herramientas de revisión y verificación automática
ya configurado.

Este proyecto ha ido mejorando con el tiempo y probablemente lo siga haciendo
por lo que se aceptan cambios, sugerencias y mejoras en su propio repositorio,
[INGCOM-UNRN-PII/proyecto-gradle](https://github.com/INGCOM-UNRN-PII/proyecto-gradle)

## La revisión de las practicas

La corrección de las practicas, se apoya en gran medida en el Proyecto Gradle,
pero la otra parte, esta en la herramienta 
[Miracomotecorrigeconan](https://github.com/INGCOM-UNRN-PII/miracomotecorrigeconan)
la cual se encarga de clonar el repositorio, ejecutar `gradle check` y emitir un
comentario en el Pull Request creado por Github Classroom con el resultado de
Checkstyle, SpotBugs, PMD y JaCOCO, asi como ejecutar los tests presentes en la
entrega, como la base de la corrección.

Esta previsto que esto sea completamente automático, pero de momento esta solo
automatizado, la corrección en sí, es hecha a mano.

## TP1-2024 - Puesta en marcha

El objetivo de esta practica es garantizar que todos estemos en la misma página
con respecto a las herramientas que utilizaremos en el cuatrimestre, así como
familiarizarnos con el ciclo de trabajo.

Durante la cursada, utilizaremos la versión del 
[JDK 17](https://download.oracle.com/java/17/latest/jdk-17_windows-x64_bin.exe),
la misma es una versión de 
[soporte extendido (LTS)](https://www.oracle.com/java/technologies/java-se-support-roadmap.html) 

Utilizaremos [IntelliJ Idea 2024 Community Edition](https://download.jetbrains.com/idea/ideaIC-2023.3.4.exe) 
como entorno de desarrollo integrado, y los proyectos individuales están basados 
en Gradle.

[TP1-2024](TP1-2024.md)

## TP2-2024 - Java desde C

El objetivo de esta practica es aprovechar que la sintaxis del lenguaje que
utilizaremos es practicamente la misma para familizarizarnos con las diferencias
del lenguaje con respecto a C, reutilizando consignas de Programación 1.

En esta practica, no esta permitido el uso de la librería estándar de Java, más
allá del [`java.util.Scanner`]

[TP2-2024](TP2-2024.md)

## TP3-2024 - Arreglos y excepcione

El objetivo de esta práctica es familiarizarnos con los arreglos en Java, viendo
las diferencias con los de C y también tener el primer contacto con Excepciones,
siendo que las operaciones con arreglos _naturalmente_ lanzan excepciones sin
tipo.

[TP3-2024](TP3-2024.md)

## TP4-2024 - Archivos y excepciones

El objetivo de esta practica es comenzar a utilizar más clases y trabajar con
archivos empleando la API `java.nio` y seguir trabajando con excepciones, ya que
los mismos lanzan excepciones con tipo.

[TP4-2024](TP4-2024.md)

## TP5-2024 - Análisis Orientado a Objetos I

El objetivo de esta práctica es ir introduciéndonos en los conceptos de clases 
y objetos a través del análisis de diferentes contextos, pero también para ir 
viendo como otras personas ven la misma cosa, al requerir de la revisión entre
pares.

[TP5-2024](TP5-2024.md)

## TP6-2024 - Arreglos III

El objetivo de esta practica es tomar las funciones de los prácticos 3 y 4 en
clases que encapsulen un arreglo en uno propio, incluyendo funcionalidad para
guardar en archivos a partir del mismo.

[TP6-2024](TP6-2024.md)

## TP7-2024 - Análisis Orientado a Objetos II

En este trabajo, le daremos una nueva vuelta de tuerca a los contextos analizados
en el TP5, incorporando lo visto de Orientación a Objetos. Esta práctica también
se desarrolló con revisión de pares en el Campus.

[TP7-2024](TP7-2024.md)

## TP8-2024 - Calculadora

El objetivo de esta practica es implementar una calculadora orientada a objetos
aplicando polimorfismo, una de las técnicas más importantes del paradigma.

[TP8-2024](TP8-2024.md)

## TP9-2024 - Arreglos Genéricos

El objetivo de esta practica, es continuar desarrollando el arreglo desarrollado
en el TP6, haciendo que el mismo emplee Genéricos, para que pueda almacenar
cualquier tipo de referencia.

[TP9-2024](TP9-2024.md)

## TP10-2024 - Patrones de Diseño

En esta practica, extenderemos el arreglo del TP anterior, para que el mismo
emplee patrones de diseño 

[TP10-2024](TP10-2024.md)

## TP11-2024 - Estructuras basadas en Nodos.

En esta practica, implementaremos estructuras de datos basadas en Nodos y les
daremos uso en aplicaciones simples.

[TP11-2024](TP11-2024.md)
