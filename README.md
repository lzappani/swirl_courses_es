# cursos de swirl

Esta es una colección de cursos interactivos para usar con el [paquete de R swirl] (http://swirlstats.com). Encontrará instrucciones para instalar cursos más abajo en esta página. Algunos cursos están aun en desarrollo y nos encantaría escuchar cualquier [sugerencia] (https://github.com/swirldev/swirl_courses/issues/new) que tenga mientras los realiza.

Para obtener más información sobre swirl, visite [swirlstats.com](http://swirlstats.com) o el [repositorio de swirl en GitHub](https://github.com/swirldev/swirl). Si desea escribir su propio contenido interactivo, visite la [página de instructores] (http://swirlstats.com/instructors.html) de nuestro sitio web.

Estos son los cursos que ofrecemos actualmente, organizadas por nivel de dificultad:

#### Principiante

- **Programación en R**: Los fundamentos de la programación en R
- [**Programación en R E**](https://github.com/swirldev/R_Programming_E): Es igual que el original, pero ligeramente modificado para uso en clase (ver más abajo ***)
- [**El entorno de programación R**](https://swirlstats.com/scn/rpe.html)
<!-- - **Análisis de datos**: Conceptos básicos de estadística y visualización de datos -->
<!-- - **Campamento de entrenamiento de bioestadística matemática**: pruebas t con una o dos muestras, potencia y tamaño de la muestra -->
<!-- - **Introducción abierta**: una introducción muy básica a las estadísticas, el análisis de datos y la visualización de datos -->

\*\*\* *Programación R E es idéntica a Programación R, excepto que eliminamos las solicitudes de credenciales de Coursera al final de cada lección y, en su lugar, brindamos a los estudiantes la opción de enviar un correo electrónico a su instructor para notificarles que lo completaron. EN realidad es una especie de truco hasta que encontremos una solución más robusta para uso en clase (por ejemplo, un "panel de control" para el instructor).*

#### Intermedio

- **Modelos de regresión**: los conceptos básicos del modelado de regresión en R
- **Obtención y limpieza de datos**: dplyr, tidyr, lubridate, ¡vaya!

#### Avanzado

- **Inferencia Estadística**: Este curso de nivel intermedio-avanzado sigue de cerca el
[Curso de Inferencia Estadística](https://www.coursera.org/course/statinference) de la
[Especialización en ciencia de datos](https://www.coursera.org/specialization/jhudatascience/1) de la Universidad Johns Hopkins en Coursera. Este curso
introduce al estudiante a los conceptos básicos de la inferencia estadística
incluyendo probabilidad, prueba de hipótesis, intervalos de confianza y
valores p. Concluye con una iniciación a temas de particular
relevancia para big data, problemas de testeo múltiple y remuestreo.
- [**Programación R avanzada**](https://swirlstats.com/scn/arp.html)

Dado que nuestros usuarios provienen de una variedad de entornos, es muy difícil etiquetar el material como **Principiante**, **Intermedio** o **Avanzado**. Si encuentra que algo que está etiquetado como **Principiante** es un reto, no se desanime. El primer paso para aprender algo es reconocer que eres capaz de entenderlo. La verdadera comprensión vendrá con el tiempo y la práctica.

#### Autores del curso

- **Escribiendo Cursos de swirl**: Guías interactivas y ejemplos
   para autores de cursos de swirl. El primer grupo de lecciones cubre los conceptos básicos. El resto cubre
   temas especiales útiles principalmente como ejemplos o puntos de partida para el material propio.
   Para obtener documentación más completa sobre cómo escribir sus propios cursos de swirl, consulte http://swirlstats.com/swirlify/.

## Instalar y ejecutar un curso automáticamente desde swirl

**Este es el método preferido para instalar cursos.** Automatiza el proceso al permitirle hacer todo directamente desde la consola R.

1) Asegúrese de tener una versión reciente de swirl:

```
install.packages("swirl")
```

2) Ingrese lo siguiente desde la consola R, **sustituyendo el nombre del curso** que desea instalar:

```
biblioteca (swirl)
install_course("Nombre del curso")
swirl()
```

Por ejemplo, `install_course("R_Programming")` instalará el curso de Programación en R. **¡Tenga en cuenta que los nombres de los cursos están en inglés y distinguen entre mayúsculas y minúsculas!**

Si eso no funciona...

## Instalar y ejecutar un curso manualmente

Si el método de instalación automática del curso descrito anteriormente no funciona para usted, entonces hay una alternativa simple.

1. Busque el curso que desea instalar en el [sitio web de la red de cursos swirl](https://swirlstats.com/scn/title.html).
2. Siga las instrucciones de instalación manual en la página del curso.

Si eso no funciona para usted, considere echar un vistazo a la
[instrucciones de instalación del manual heredado](https://github.com/swirldev/swirl_courses/wiki/Legacy-Manual-Install-Instructions-for-swirl-Courses).

## Desinstalar un curso

Si desea eliminar un curso en cualquier momento, puede usar `uninstall_course("Nombre del curso")`.

## Uso de swirl en el aula

Instructores de todo el mundo están utilizando swirls en sus aulas. Creemos que esto es genial. Si eres un instructor, siéntete libre de hacer lo mismo, sin cargo. Si bien es posible que sus estudiantes paguen para tomar su curso o asistir a su institución, simplemente le pedimos que no cobre a las personas *directamente* por el uso de nuestro software o contenido instructivo.

Si no está seguro acerca de algún caso de uso en particular, no dude en enviar una
pregunta a nuestro [Grupo de Google](https://groups.google.com/forum/#!forum/swirl-discuss).
