#Sesión 1. Introducción e instalación

Recorrido express para llegar a la parte de la instalación 

## Índice de la sesión

- Presentación
- Introducción
- Premisa general: el software como partitura y como ejecución
- Instalación e introducción a SuperCollider y OpenFrameworks

## Presentación

- [Emilio Ocelotl](https://emilioocelotl.github.io)
- [PiranhaLab](https://piranhalab.github.io)
- [RGGTRN](https://rggtrn.github.io)
- [LCNE](https://livecodenetensamble.wordpress.com/)

## Introducción

### Live coding como antecedente. Show us your screens, diálogo con el error y el texto como interfaz.

PLab toma como antedente tres aspectos del live coding como práctica artística.

#### El obscurantismo es peligroso. Muéstrenos sus pantallas. 

Es uno de los puntos del manifiesto del live coding. Aparece en uno de los documentos más antiguos que marcan los principios de la práctica.
¿Este punto coincide ambiguamente con la propuesta del Software Libre y del Código Abierto?
Expandir la pantalla.

[Manifiesto Draft](https://toplap.org/wiki/ManifestoDraft)

#### El error como interlocutor

Un texto inédito escrito por Rossana Lara, Raúl Dávila, Alejandro Franco y Emilio Ocelotl  da cuenta de esta situación. Igual es muy clavado, aquí un resumen.
¿El error es una justificación ante la falta de habilidad técnica?
Escribir texto y debuggeo.
Códigos parchados y modernidad barroca.
El error como condición creativa.

[El rey ha muerto ¡Viva el rey! (extracto)]

#### El texto como interfaz

Interés técnico personal en esta práctica: En vivo ¿cómo mover 15 perillas al mismo tiempo si tengo solamente 10 dedos (en las manos)?
También hay otros aspectos. el texto puede estar mucho más cercano al código con el que interactúa que la interfaz que lo programa.
La interfaz de texto implica más elementos que solamente un editor de texto. La ventana en la que se postean los errores es el output de la interlocución que ya hemos mencionado.
Texto permite comunicación y llevar a cabo el términos técnicos el "muestranos tu pantalla"

[Saborítmico: A Report From the Dance Floor in Mexico](https://dj.dancecult.net/index.php/dancecult/article/view/1066/962)

#### Finalmente... ¿Dónde se ha visto y dónde ha sonado el live coding? 

Alexandra Cárdenas
Michel Soto
Marianne Teixido
Alejandro Franco

La práctica en otras latitudes

Shelly Knotts
Kindohm
OFFAL
Renick Bell
Olivia
Los algoritmos

#### Más recursos de interés

- [TOPLAP](https://toplap.org/wiki/ManifestoDraft)
- [Taller de Audio del CMM](http://cmm.cenart.gob.mx/tallerdeaudio/)(CENART, no quites el sitio en línea por favor :P)
- [Live coding en México. Hernani Villaseñor](http://www.hernanivillasenor.com/archivos/html/livecoding.html) (en constante actualización)
- [La tesis de Jessica Rodríguez](http://www.repositorio.ugto.mx/handle/20.500.12059/412?fbclid=IwAR2RMkm_xxsy7jKNXGFGv67CS98AlGZvvvLMYrHrWA3RyIAqiiPHg7HFX9k)

### Premisa general: el software como partitura y como ejecución.

## Instalación

SuperCollider, fácil. Compilar Orbit desde cero... problemático pero posible.
	
### SuperCollider

Hoy en día SuperCollider corre en todas las plataformas más populares. Basta consultar la [sección de descargas](https://supercollider.github.io/download) de la página de SuperCollider. 

#### Recursos para aprender otros aspectos de SuperCollider

- [David Cottle](http://rhoadley.net/courses/tech_resources/supercollider/tutorials/cottle/CMSC7105.pdf)
- [Taller de Alexandra Cárdenas(esp)](https://basicsupercollider.wordpress.com/clases/clase1/)
- [A gentle Introduction](https://ccrma.stanford.edu/~ruviaro/texts/A_Gentle_Introduction_To_SuperCollider.pdf)

### OpenFrameworks

Complicado. Para este entonces ya deberían existir lanzamientos estables de Orbit para linux, mac y windows.

Liga a los lanzamientos

#### Modo manual

Descargar la carpeta de la última versión de OF de acuerdo a la plataforma preferida.

[OpenFrameworks](https://openframeworks.cc/download/)

OF es un marco de trabajo y requiere de algunos programas extras que puedan compilar código escrito en c++. En esa misma liga se pueden encontrar guìas de configuración para los programas que compilarán nuestro programa (visual studio, xcode, make). 

Una forma de saber que todo está en orden y que ya estamos listos para compilar Orbit: compilar un ejemplo.

Las bibliotecas externas en OF se llaman addons y Orbit utiliza algunas de ellas. Esas librerías se encuentran en la carpeta addons. 