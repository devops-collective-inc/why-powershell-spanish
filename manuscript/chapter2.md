# ¿Por qué el Scripting? ¿Por qué un Shell?

Antes de sumergirnos en PowerShell, abordemos  la importancia del scripting y de la automatización, una faceta integral de PowerShell.

Probablemente usted conozca este [XKCD comic](http://xkcd.com/1205/) o algo similar para justificar el Scripting. Mientras que el ahorro de tiempo es sin duda un factor importante del scripting y la automatización, no es la única justificación. 

Otros factores a considerar:

* **Consistencia**. Una solución de secuencias de comandos ejecutará siempre el mismo script de manera exacta. Sin riesgo de errores tipográficos, o de olvidarse completar la tarea, o haciendo la tarea incorrectamente. _Reducir el error humano_. 
* **Registros de auditoría**. Hay muchas tareas en las que sería útil tener un registro de auditoría, tal vez incluyendo qué tarea se realizó, resultados importantes, errores que ocurrieron, cuándo se ejecutó la tarea, quién la ejecutó y así sucesivamente. Los scripts pueden proporcionar estos registros, y en PowerShell v5 y posteriores, el propio Shell cuenta con amplias capacidades de registro.
* **Código modular**. Al principio usted podría pasar más tiempo escribiendo una función particular de lo que justifique el ahorro de tiempo, pero generalmente usted podrá reutilizar o tomar prestadas ideas de ese mismo código más adelante.
* **Documentación**. ¿Se tiene documentación para la tarea? ¿Está actualizada? Un script bien escrito y comentado puede servir como una base útil de documentación, que podría no existir para una tarea manual. En algunos casos, el script puede documentar el proceso que automatiza, ayudando a preservar el conocimiento institucional.
* **Educación**. Los administradores que pueden automatizar las tareas, al final se vuelven expertos en tecnologías como resultado de sus conocimientos. Eso los convierte en mejores planificadores, arquitectos, solucionadores de problemas y operadores, lo cual resulta beneficioso para la organización.
* **Delegación**. Con una solución basada en scripts, típicamente se pueden delegar más funciones a los equipos mejor preparados. Con PowersShell v3 y posteriores, estos scripts permiten la delegación de tareas de forma extremadamente granular, ayudando al equipo a ser más eficiente y sensible.

La moraleja de la historia es que el Scripting y la automatización son importantes, y se convierten en factores importantes y de alto valor para aprender PowerShell.
