Acceder al código desde Google Colab para poder ver de manera adecuada todas las visualizaciones y poder interactuar con ellas.
Link de acceso: https://colab.research.google.com/drive/17kuc85L9f7uhK0KJUgE9tuNuewoqWKgg?usp=sharing

Corto video explicativo: https://youtu.be/Y64m9ZUMhEo


# Proyecto - PROCESO ESTADÍSTICO “MATRICULA DE EDUCACIÓN PREESCOLAR, BÁSICA Y MEDIA”
Proyecto por el cual el Ministerio de Educación Nacional de Colombia quiere contar con información estadística oportuna y confiable de la población atendida en el sector oficial y no oficial en los niveles educativos de preescolar, básica (primaria y secundaria) y media; información fundamental para la formulación, implementación y seguimiento de políticas públicas y para la toma de decisiones a nivel nacional y regional.

# **1. Entendimiento del negocio**
## **Objetivos de negocio y situación actual**

El Ministerio de Educación Nacional de Colombia (Mineducación) es un ministerio de la República de Colombia y tiene como Misión “Liderar la formulación, implementación y evaluación de políticas públicas educativas, para cerrar las brechas que existen en la garantía del derecho a la educación, y en la prestación de un servicio educativo con calidad, esto en el marco de la atención integral que reconoce e incorpora la diferencia de los territorios y sus contextos, para permitir trayectorias educativas completas que impulsan el desarrollo integral de los individuos y la sociedad.

En el marco de la Ley General de educación, Ley 115 de 1994, el Ministerio de Educación Nacional – MEN como ente formulador de la política educativa nacional y como regulador e instaurador de los criterios y parámetros técnicos cualitativos que contribuyan al mejoramiento del acceso, equidad, calidad, pertinencia y eficiencia de la educación, tiene la responsabilidad de definir, diseñar, reglamentar y mantener un sistema de información del sector educativo.

Así mismo, la Ley 715 de 2001 le asigna al MEN la competencia de definir, diseñar, reglamentar y mantener un sistema de información del sector educativo, el cual se nutre de todos aquellos datos necesarios para la toma de decisiones en los niveles nacional, departamental, distrital y municipal. Siendo así, los municipios mantendrán su sistema con la información que les proporcionen las instituciones educativas y los departamentos lo harán a su vez con la información que le suministren los municipios. El nivel nacional recibirá la información de los departamentos, distritos y de los municipios certificados en educación (Ley 715, art. 20).

Los datos recolectados a través de los diferentes sistemas que administra el MEN son la base fundamental para el cálculo de múltiples indicadores e información estadística. Esta información es fundamental para la formulación, ejecución y evaluación de las políticas públicas, y por ende es de gran importancia contar con información objetiva que permita conocer la realidad educativa del país, a fin de eliminar las brechas regionales que se presentan en materia educativa.

El MEN ha estructurado un proceso estadístico con base en el registro administrativo de la matrícula que da cuenta de la calidad y confiabilidad de la información, que comprende el diseño, recolección, procesamiento, análisis y difusión, de acuerdo con lo establecido en la Norma Técnica de la calidad del proceso estadístico (NTC PE: 1000 de 2020).

De acuerdo con lo establecido en la NTC PE:1000 de 2020 como atributos de la calidad estadística, el MEN reconoce, entre otros, la importancia de producir información precisa y oportuna, que pueda ser ubicada y obtenida por las partes interesadas y grupos de interés (accesibilidad), de garantizar la producción permanente de la operación estadística y de generar credibilidad con políticas y prácticas transparentes.
En este contexto, el gobierno nacional en cabeza del MEN y en el ámbito de sus competencias, diseñó e implementó el Sistema de Información Nacional de Educación Básica y Media - SINEB. El SINEB está integrado por diversos formatos, instrumentos, aplicativos y procedimientos, que permiten recolectar información importante de los establecimientos educativos oficiales y no oficiales de las Secretarías de Educación de las Entidades Territoriales Certificadas – ETC. Un componente esencial del SINEB es el Sistema Integrado de Matrícula – SIMAT, como sistema de gestión de la matrícula de los alumnos de instituciones educativas de educación preescolar, básica y media, que registra la información niño a niño, desde su inscripción como alumno nuevo en el sistema educativo, hasta su traslado, salida o graduación; lo que permite realizar el seguimiento a su  trayectoria educativa.

La información reportada por los establecimientos sobre la población atendida en el sistema educativo y capturada a través del SIMAT, conforma el registro administrativo de la “matrícula de educación preescolar, básica y media”, la cual es la base de la operación estadística que comprende la identificación de necesidades, diseño, construcción, recolección o acopio, procesamiento, análisis, difusión y evaluación, el cual conduce a la producción de información estadística sobre un tema de interés nacional y/o territorial.

(Tomado de: MINISTERIO DE EDUCACIÓN NACIONAL - REPÚBLICA DE COLOMBIA. (2020, noviembre). DOCUMENTO METODOLÓGICO DEL PROCESO ESTADÍSTICO “MATRÍCULA DE EDUCACIÓN PREESCOLAR, BÁSICA Y MEDIA”.)

## **Objetivo del proyecto**

El MEN identifica de manera permanente los requerimientos de nueva información o de ajuste a la existente en las diferentes instancias o espacios en los que participan actores o grupos de interés, como por ejemplo las mesa técnicas de información, el comité de información, encuentros con secretarios de educación, asistencias técnicas y acompañamientos a funcionarios de las secretarías, mesas de diálogo interministerial y mesas interinstitucionales con otras entidades de gobierno a nivel nacional, comité sectorial y mesa nacional de educación privada, entre otros.

### **Objetivo general**

Contar con información estadística oportuna y confiable de la población atendida en el sector oficial y no oficial en los niveles educativos de preescolar, básica (primaria y secundaria) y media; información fundamental para la formulación, implementación y seguimiento de políticas públicas y para la toma de decisiones a nivel nacional y regional.

### **Objetivos específicos**

*   Proporcionar los datos necesarios para determinar la cobertura, equidad y eficiencia del servicio.
*   Servir de fuente de información para distribuir entre las Entidades Territoriales Certificadas los recursos de la participación para educación del Sistema General de Participaciones de acuerdo con la población atendida y la población por atender en condiciones de eficiencia.
*   Servir de registro público de la información relativa a los estudiantes de la educación formal.
*   Servir como base para la consolidación de estadísticas educativas y la construcción de indicadores.

(Tomado de: MINISTERIO DE EDUCACIÓN NACIONAL - REPÚBLICA DE COLOMBIA. (2020, noviembre). DOCUMENTO METODOLÓGICO DEL PROCESO ESTADÍSTICO “MATRÍCULA DE EDUCACIÓN PREESCOLAR, BÁSICA Y MEDIA”.)

## **Planeación del proyecto**

A partir de los datos recolectados y guiándonos por la metodología CRISP-DM (Cross-Industry Standard Process for Data Mining) el proyecto se llevará a cabo de la siguiente manera:


**1. Entendimiento del negocio:** Se definirá y se comprenderá el problema a resolver, se evaluará la situación actual y se plantearán objetivos del proyecto que se alineen con los objetivos de la organización. Acá también se conocerá del dominio de la aplicación. Por tanto, para esta etapa se hará una investigación exhaustiva sobre el Ministerio de Educación Nacional, sobre su principal objetivo para el Gobierno nacional de Colombia, con principal énfasis en su objetivo principal con la educación preescolar, básica y media y con esto evaluar los objetivos específicos que conllevan a cumplir el objetivo principal. Aquí determinamos la pertinencia del proyecto a realizar y se hará una planeación detallada del mismo para alcanzar los objetivos. (Esta etapa ya se realizó en este apartado)


**2. Entendimiento de los datos:** Se adquirirá los conjuntos de datos, en este caso se tomarán de la página www.datos.gov.co donde encontramos ‘datos abiertos’ de diversos campos sobre Colombia. Específicamente se tomarán los datasets ‘MEN_ESTADISTICAS_EN_EDUCACION_EN_PREESCOLAR, BÁSICA Y MEDIA_POR_MUNICIPIO’ y ‘MEN_ESTADISTICAS_EN_EDUCACION_EN_PREESCOLAR, BÁSICA Y MEDIA_POR_DEPARTAMENTO’ que contienen los principales indicadores de los niveles preescolar, básica y media discriminados por Municipio y Departamento respectivamente, desde el año 2011 hasta 2020. 

Links: 

https://www.datos.gov.co/Educaci-n/MEN_ESTADISTICAS_EN_EDUCACION_EN_PREESCOLAR-B-SICA/nudc-7mev

https://www.datos.gov.co/Educaci-n/MEN_ESTADISTICAS_EN_EDUCACION_EN_PREESCOLAR-B-SICA/ji8i-4anb

Se realizará un análisis exploratorio de los datos, se usará estadística descriptiva para caracterizar, inspeccionar y resumir los datos. También se usará técnicas de visualización para representar de manera gráfica y amigable los detalles ‘ocultos’ en los datos.


**3. Preparación de los datos:** Se analizará la calidad de los datos y se hará limpieza de estos porque se sabe de antemano que pueden haber datos perdidos o no diligenciados en algunos años por variaciones importantes en el número de sedes y establecimientos educativos o por el impacto de emergencias ambientales y desastres naturales que hace que algunas instituciones educativas cierren temporalmente y por tanto no generan información. 
Después de esta limpieza del conjunto de datos se seleccionarán las características importantes, que aporten más información para hacer un pre-proceso y transformación de los datos para su análisis y posterior modelado. 

Para este análisis nos apoyaremos de la estadística descriptiva e inferencial y del modelado estadístico como es el uso de análisis de correlaciones y de regresiones.
