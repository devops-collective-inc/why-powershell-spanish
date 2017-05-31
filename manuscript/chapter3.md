# ¿Por qué PowerShell?

Microsoft describe PowerShell como "un shell de línea de comandos basado en tareas con un lenguaje de scripting ... construido en .NET Framework". ¿Qué es lo grandioso de PowerShell? ¿Por qué debería usarlo?

## PowerShell es un shell de línea de comandos y un lenguaje de secuencias de comandos (ambos)

“Apague incendios” rápidamente utilizando comandos existentes o personalizados de PowerShell, sin necesidad de compilar el código. Desarrolle sus soluciones desde la línea de comandos. Escriba scripts rápidamente, los usará muchas veces. Cree scripts legibles y documentados, capaces de ejecutarse en ambientes de producción. Le ayudaran a mantener sus servicios/ambientes durante años.

¿Cuál es el costo de esta inversión? Aprender PowerShell. Bastante razonable teniendo en cuenta que es probable que tenga que hacerlo independientemente de su lenguaje actual de programación, suponiendo que trabaja con el ecosistema de Microsoft.

## PowerShell puede interactuar con un sin número de tecnologías

.NET Framework, registro de Windows, COM, WMI, ADSI. Exchange, Sharepoint, System Center, Hyper-V, SQL. VMware vCenter, Cisco UCS, Citrix XenApp y XenDesktop, REST APIs, XML, CSV, JSON, sitios Web,  Excel,  aplicaciones Office. C # y otros lenguajes, DLLs y otros binarios, incluyendo Linux o herramientas Unix. Un lenguaje que puede trabajar con estas diversas tecnologías además de integrarlas puede ser increíblemente valioso.

Windows no está basado en texto. Tarde o temprano tendrá que hacer algo que no puede hacer con las herramientas de NIX y otros lenguajes basados en texto. Muchas de las tecnologías con las que PowerShell puede interactuar simplemente no tienen interfaces basadas en texto, y ni siquiera pueden ser accesibles directamente desde lenguajes más formales como Perl o Python.

El mensaje aquí es que PowerShell es el mejor "pegamento" que Microsoft nos ha proporcionado para unir sistemas diversos. Es mejor que las anteriores Shells basadas en Windows porque entiende y funciona con la naturaleza del API de Windows en sí, lo cual es muy diferente de lo que hicieron los Shells anteriores basados en texto.

## PowerShell está basado en objetos

Esto nos da una flexibilidad increíble. Filtrar, clasificar, medir, agrupar, comparar o tomar otras acciones sobre objetos a medida que pasan a través de la tubería (pipeline). Trabaje con propiedades y métodos en lugar de texto en bruto.

Si ha pasado tiempo programando y “descifrando” una salida basada en texto, sabe lo frustrante que puede ser. ¿Cuál delimitador utilizo? ¿Hay un delimitador? ¿Qué pasa si un resultado en particular tiene una entrada en blanco para una columna? ¿Necesito contar los caracteres en cada columna? ¿Este conteo variará dependiendo de la salida? Con objetos todo eso está resuelto, y hace que sea muy sencillo encadenar comandos y datos a través de diversas tecnologías.

## PowerShell llegó para quedarse

Microsoft está poniendo todo su empeño detrás de PowerShell.

El soporte de PowerShell es un requisito en los criterios comunes de ingeniería de Microsoft, y un producto de servidor no se puede liberar sin una interfaz de PowerShell. Eso significa que muy pocos productos de servidor de Microsoft no pueden ser manejados desde PowerShell - y los pocos que no pueden, podrán hacerlo pronto.

Otros proveedores de tecnologías Microsoft también tienen soporte para PowerShell. Esto incluye IBM, Cisco, Citrix, VMware, NetApp, Dell, y docenas más.

En muchos casos Microsoft utiliza PowerShell para construir las consolas de administración GUI para sus productos. Algunas tareas no se pueden realizar en el GUI y sólo se pueden completar desde PowerShell. Esto podría ser un problema: _en un número cada vez mayor de situaciones, no se puede administrar el producto totalmente a menos que utilice PowerShell._ Y esto se extiende a ofertas basadas en la nube como Azure y Office 365, también.

## Consolidar y multiplicar su aprendizaje

Su recompensa por aprender PowerShell es una habilidad mejorada para controlar y automatizar las muchas tecnologías con las que se integra. Puede usar el mismo conjunto de comandos para filtrar, exportar, redireccionar, modificar, extender y realizar acciones contra la salida para todas estas tecnologías. Puede aprovechar esas mismas habilidades de PowerShell y llevarlas en cualquier dirección que necesite: Hyper-V, vCenter, SQL, AD, XenApp y más.

Su recompensa por aprender herramientas específicas o ejecutables como net.exe o schtasks.exe, es la capacidad de trabajar con esas herramientas. Ni más, ni menos. En cambio, con PowerShell su inversión en el aprendizaje se convierte en un enorme ecosistema de múltiples capacidades.

## En Windows, PowerShell realmente es la única opción

VBScript está obsoleto, y su desarrollo se detuvo hace mucho. VBScript ya era anémico en términos de las cosas que podría "tocar", lo que lo convierte en un "pegamento" pobre para conectar sistemas y procesos.

Y nada más se acercó a las capacidades de VBScript. Python, Perl, <ponga el nombre que desee aquí> - son grandes en Linux, predominantemente basados en sistemas operativos orientados a texto, pero poco útiles en Windows, ya que no podían acceder a los muchos y variados usos de las APIs de Windows para su gestión.

PowerShell consolida todos esos APIs en una única interfaz, en gran medida coherente, que se centra en las operaciones de sistemas y su administración.

