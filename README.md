# Construcción de compiladores 2
Bryan Carlos Roberto España Machorro - 21550

## Análisis de gramática de ANTLR y Driver

La gramática ANTLR significa Another Tool of Language Recognition es un conjunto de reglas que describe la estructura de un lenguaje como un lenguaje de programación, un DSL o un formato de archivo y es utilizada por ANTLR para generar analizadores léxicos y sintácticos. En el laboratorio con Python utilizando esto se puede crear una gramática ANTLR.

El driver genera un conjunto de archivos lexer, parser y en algunos casos Visitor y Listener el cual es bastante completo para realizar un analizador léxico y sintáctico, y tiene muchas ventajas como la automatización total de los dos generadores, modularidad como por ejemplo que está dividida bien la estructura entre el lexer y el parser lo cual facilita muchísimo extender y personalizar el comportamiento logrando terminar un compilador bien hecho.

## Video explicativo
[Ver el video en YouTube](https://youtu.be/4xQPz_zkGgI?si=zgVTbgisGfjg-dlz)