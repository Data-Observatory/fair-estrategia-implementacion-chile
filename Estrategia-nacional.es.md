# Estrategia para la Implementación de una Política de Datos FAIR en Chile

Segunda Edición: Marzo de 2025

**Desarrollado por:**

- Data Observatory
- Pontificia Universidad Católica de Chile
- Universidad Central
- Universidad de los Andes

**Autores** (por orden alfabético):\
Abedrapo, I.; Carrasco, R.; Catalán, A.; Díaz, I.; Escapil-Inchauspé, P.; Hartley Belmar, R.; Keim, A.; Koelbl, M.; Meyers, N.; Quiroz, S.; Paredes, Á.; Rivera, M.; Roa, R.

**Colaboradores y revisores**\
Kirkpatrick, Christine R.; Cragin, Melissa H.; Meyers, Natalie.\
Muñoz, Patricia; Bravo, Soledad; Roa, Verónica; Muñoz, Francisca.

Este documento ha sido basado en la guía "FAIR Data Stewardship Plan Template for Organizations and Institutions", de la Colección de Materiales de los Servicios de Datos de Investigación de SDSC, UC San Diego Library Digital Collections (2021). [https://doi.org/10.6075/J0CV4G8C](https://doi.org/10.6075/J0CV4G8C)

Esta obra está bajo licencia CC BY-NC-SA 4.0. Para ver una copia de esta licencia, visite [creativecommons.org/licenses/by-nc-sa/4.0](http://creativecommons.org/licenses/by-nc-sa/4.0)

## Palabras del Director Ejecutivo

La colaboración entre diferentes instituciones se ha vuelto un pilar fundamental en el mundo actual para desarrollar proyectos que generen un impacto significativo a nivel nacional y que integren la sostenibilidad desde su concepción.

Cuando esta cooperación está alineada con objetivos estratégicos claros, se convierte en un catalizador para la innovación, favoreciendo la ejecución de acciones más efectivas y fortaleciendo la capacidad de enfrentar desafíos complejos.

Este documento representa el resultado del esfuerzo colaborativo entre la Pontificia Universidad Católica de Chile, la Universidad Central, la Universidad de Los Andes y el Data Observatory. Desde inicios de 2024, estas instituciones han trabajado juntas en el diseño de una propuesta robusta, inclusiva y orientada hacia el futuro.

Con una visión compartida sobre la optimización del uso de datos, este proyecto no solo traza un camino para implementar los principios FAIR, sino que también establece los fundamentos para un sistema avanzado de gestión de datos. Este sistema busca potenciar el desarrollo científico y fomentar el avance del conocimiento en Chile.

A través de este documento, Chile se posiciona como líder regional en la promoción de datos abiertos, impulsando la investigación, la innovación y el desarrollo sostenible. Asimismo, se resalta el papel de los datos como insumo esencial para la inteligencia artificial, mientras el país avanza en la construcción de un ecosistema digital ético y responsable.

Rodrigo Roa López de Heredia\
Director Ejecutivo\
Data Observatory

## 1. Introducción

En la era digital actual, los datos desempeñan un papel fundamental en prácticamente todos los aspectos de la sociedad y la economía. En este contexto, **la gestión efectiva de los datos se ha convertido en una necesidad** para garantizar la transparencia, la eficiencia y la innovación en diversos sectores.

En el año 2016, se publicó en la revista Scientific Data el documento titulado *"The FAIR Guiding Principles for scientific data management and stewardship”* [\[1\]](https://www.nature.com/articles/sdata201618). El objetivo de este documento fue proporcionar pautas para asegurar la encontrabilidad (Findability), accesibilidad (Accessibility), interoperabilidad, (Interoperability) y reutilización (Reusability) de los objetos digitales. Los principios FAIR enfatizan la capacidad de acción de las máquinas, es decir, la capacidad de los sistemas computacionales para encontrar, acceder, interoperar y reutilizar datos con ninguna o mínima intervención humana.

En un mundo cada vez más data-céntrico [\[2\]](https://doi.org/10.1016/j.ces.2021.117271) e impulsado por grandes volúmenes de datos, **estos principios son fundamentales** para maximizar el valor y el impacto de la información generada en diversas áreas.

Es imprescindible que Chile se adapte y se mantenga competitivo en el cambiante panorama global. Para lograrlo, es necesario diseñar y desarrollar una *Estrategia para la Implementación de una Política de Datos FAIR en Chile* (en adelante en este documento, *Estrategia FAIR*) para que estos cumplan con estándares internacionales que permitan compartir los datos eficientemente.

Al desarrollar la Estrategia FAIR, Chile podrá:

- Mejorar la calidad e impacto de su investigación y de sus resultados científicos;  
- Facilitar la colaboración interdisciplinaria y de frontera;  
- Posicionarse como un líder regional en la gobernanza de datos, acceso abierto y ética de datos;  
- Promover un ecosistema de datos robusto e innovador.

Cabe destacar que Chile ya se encuentra en una fase de crecimiento y transformación tecnológica.  Esto queda de manifiesto al revisar el quehacer de las distintas instituciones ligadas a la investigación y observar cómo surgen diversas iniciativas locales que buscan resguardar y poner en valor los datos. A continuación, se presentan algunas iniciativas de interés.

### Data Observatory

La [Fundación Data Observatory](https://dataobservatory.net/) (DO en adelante) es fruto de una colaboración público-privada-académica, que busca maximizar el beneficio que se puede obtener de los datos para la ciencia, la investigación y el desarrollo productivo, a través de la creación, administración y enriquecimiento de plataformas de datos abiertos que estén a disposición de la comunidad para la generación de políticas públicas e iniciativas que tengan impacto social en materias relativas al cambio climático, logística y transporte, minería, acuicultura, gestión territorial y prevención de desastres naturales, entre otros. La creación del Data Observatory facilita la interoperabilidad y el acceso a datos de alta calidad, promoviendo la reutilización de datos a nivel nacional e internacional. Además, esta iniciativa apoya la formación de capital humano avanzado en ciencia de datos, alineándose con los principios FAIR.

### Data Cube Chile

La Universidad Adolfo Ibáñez, CSIRO y Data Observatory formaron una alianza estratégica para desarrollar [Data Cube Chile](https://datacubechile.cl/), un proyecto pionero que utiliza Open Data Cube, o Cubo de Datos Abiertos, para el monitoreo satelital terrestre y marítimo de Chile. Data Cube Chile es una plataforma colaborativa que integra diversas imágenes satelitales y datos geoespaciales en un formato estandarizado y optimizado para la nube. El proyecto facilita la interoperabilidad y reutilización de datos geoespaciales, asegurando que los datos sean fácilmente accesibles y utilizables por diferentes actores y sectores.

### Proyecto de Ley sobre Transferencia de Tecnología y Conocimiento

El Gobierno de Chile, a través de esta iniciativa, busca promover un entorno de transferencia de tecnología y conocimiento equilibrado, basado en la interacción y colaboración de instituciones académicas, de investigación, agencias gubernamentales y la industria. Esto se fundamenta en factores que contribuyan a este proceso y promuevan el desarrollo sostenible. Es en este ámbito donde, a través de la legislación, se dictan políticas y directrices que aseguren el acceso abierto a los datos de investigación, mejorando su localización, acceso y reutilización.

### Portal datos.gob.cl

El portal [datos.gob.cl](https://datos.gob.cl/) es un repositorio centralizado de datos de las instituciones públicas, cuyo propósito es poner a disposición de diferentes actores datos generados con presupuesto público y en formatos abiertos, para libre consumo de los interesados. Los datos se pueden obtener  descargándolos desde la plataforma o accediendo directamente desde la API que genera datos.gob.cl. Esto permite la generación de valor como visualizaciones, aplicaciones, estudios, investigaciones y servicios, entre otros. Esta iniciativa proporciona un punto centralizado de acceso a datos gubernamentales, facilitando su descubrimiento, acceso, interoperabilidad y reutilización por parte de la comunidad.

### Instituto Milenio Fundamentos de los Datos

El [Instituto Milenio Fundamentos de los Datos](https://imfd.cl/) es una iniciativa conjunta de la Pontificia Universidad Católica y la Universidad de Chile, en la que colaboran, además, académicos de la Universidad Técnica Federico Santa María, Universidad de Concepción, Universidad de Talca y Universidad Diego Portales. Este proyecto busca abordar al dato en todas sus dimensiones, desde su origen, como una compleja unidad informática, pasando por el estudio de sistemas de almacenamiento, seguridad, disponibilidad y nuevos lenguajes de consulta, hasta su uso e impacto social.

Todas las iniciativas mencionadas anteriormente **dan fe del diverso ecosistema existente y del potencial de crecimiento** de la cultura FAIR dentro del territorio nacional de Chile.

## 2. La Necesidad Nacional

Considerando que la gestión eficiente de datos es esencial para la transparencia y la innovación, la necesidad de la Estrategia FAIR surge de la demanda de generarlos y utilizarlos adecuadamente en diversas áreas de la sociedad, tanto para la investigación científica como para el desarrollo económico y social, para **continuar posicionando a Chile como líder regional** en la Gobernanza de Datos.

Los principios FAIR hacen hincapié en la capacidad para localizar o entregar, acceder, interoperar y reutilizar datos sin intervención humana o con una intervención mínima, ya que, para procesar grandes volúmenes, se hace necesario el uso de poderosas máquinas procesadoras de información.

En general, estos 4 principios se aplican a 3 tipos de entidades:

- Datos, o cualquier objeto digital;  
- Metadatos, información sobre ese objeto digital;  
- Infraestructura utilizada para su procesamiento.

Chile es conocido por ser un "laboratorio a cielo abierto”, por su particular geografía, que facilita tanto la colaboración como el acceso a datos. Sin embargo, más allá de estos aspectos, una gestión e intercambio eficiente de los datos puede impulsar el crecimiento económico, mediante el fomento de industrias basadas en datos, por ejemplo, la inteligencia artificial o el análisis de *big data*, las cuales resultan fundamentales para abordar problemas sociales claves para Chile; donde mitigar los sesgos de información es fundamental, y los principios FAIR pueden constituir un gran apoyo [\[3\]](https://www.sciencedirect.com/science/article/pii/S0167739X24000694). A modo de ejemplo, podemos mencionar los desafíos en salud pública, las preocupaciones ambientales y las desigualdades sociales, donde mejores herramientas permitirían la toma de decisiones informadas y el desarrollo de políticas públicas más efectivas y equitativas.

Al adoptar los principios FAIR, y avanzar en estándares de datos abiertos, Chile puede mantenerse competitivo en la globalización de la investigación y también, impulsar su propia comunidad científica. Al compartir datos de manera abierta y accesible, se fomenta la transparencia y la reproducibilidad de los estudios, lo que fortalece la credibilidad de la investigación chilena a nivel mundial, favoreciendo y facilitando su uso por parte de investigadores de otros países, lo que puede conducir a colaboraciones internacionales más amplias y a un mayor impacto de la investigación nacional.

De esta forma, la Estrategia FAIR facilitará que Chile se adapte al cambiante panorama mundial de datos, promoviendo el establecer estándares de calidad para la gestión y el intercambio de datos, la formación de capital humano avanzado en el tratamiento de datos y analítica, crear incentivos para la publicación y uso de datos abiertos, fomentar la colaboración entre sectores público y privado en proyectos de datos, y fortalecer la infraestructura tecnológica.

En Chile, varias iniciativas hacen más relevante la necesidad de la Estrategia FAIR. Por ejemplo, se menciona la Política Nacional de Inteligencia Artificial [\[4\]](https://www.bcn.cl/leychile/navegar?i=1169399&f=2021-12-03) e iniciativas como la plataforma Conocimiento Público [\[5\]](https://www.conocimientopublico.cl), el trabajo de la Secretaría de Gobierno Digital y las políticas de la [Agencia Nacional de Investigación y Desarrollo](https://anid.cl/) (ANID en adelante) sobre datos abiertos [\[6\]](https://s3.amazonaws.com/documentos.anid.cl/estudios/Politica\_acceso\_a\_informacion\_cientifica\_2022.pdf); facilitando la conversación para la creación de un necesario marco regulatorio que garantice su cumplimiento a largo plazo, proporcionando claridad en las responsabilidades y obligaciones, y asegurando la sostenibilidad de las prácticas de gestión de datos.

Para complementar la justificación de la Estrategia FAIR, se destacan los siguientes aspectos claves:

1. **Alianzas internacionales y visibilidad:** Una estrategia nacional sólida puede mejorar la visibilidad y el atractivo de Chile como socio en proyectos y colaboraciones internacionales de investigación, fortaleciendo su papel de liderazgo.
2. **Colaboración regional y establecimiento de estándares:** Chile puede liderar iniciativas regionales para estandarizar las prácticas de datos, fomentando un ecosistema de datos colaborativos en América Latina.
3. **Innovación y Desarrollo Tecnológico:** Liderar las prácticas de datos FAIR puede estimular la innovación en tecnologías, como el desarrollo de soluciones con IA, y servicios de datos, posicionando a Chile como un centro de desarrollo tecnológico en la gestión de datos.
4. **Impacto de las políticas:** La experiencia y el conocimiento de Chile en la implementación de prácticas de datos FAIR pueden servir como referencia para el desarrollo de las políticas de gobernanza de datos a nivel regional, estableciendo estándares para la gestión de datos en América Latina. 
5. **Oportunidades económicas:** El liderazgo en la gobernanza de datos puede crear oportunidades económicas, incluida la atracción de inversiones en el sector tecnológico.  
6. **Desarrollo de capacidades e intercambio de conocimientos:** Al desarrollar experiencia en los principios de datos FAIR, Chile puede convertirse en un centro de capacitación e intercambio de conocimientos en la región, ayudando a elevar las competencias de datos en toda América Latina.  
7. **Modelo de Buenas Prácticas:** La implementación de una estrategia integral de datos FAIR puede posicionar a Chile como un modelo para otros países de América Latina, demostrando las mejores prácticas en la gestión de datos.

## 3. Beneficios

Los beneficios de incorporar los principios FAIR a los datos, generando oportunidades de colaboración, investigación interdisciplinaria e innovación, son inseparables de las necesidades de capacitación de quienes participan en los procesos de investigación e innovación; no sólo en el contexto de la Ciencia Abierta, sino también en el de investigación responsable. Esto se debe a que facilita que personas y diversas herramientas computacionales puedan encontrar, acceder, reusar datos y/o sus metadatos. 

Además, se debe tener presente que **los principios son orientadores y no un conjunto de reglas**, lo cual favorece su implementación y exige un trabajo colaborativo para resolver las particularidades [\[7\]](https://dx.doi.org/10.15497/RDA00050). Entre las oportunidades que presenta el adoptar estos principios están: facilitar el descubrimiento de datos y metadatos producidos en colaboración con Chile (instituciones e investigadores/as), su uso y reuso, su reconocimiento y valoración, y promover el uso de Identificadores Persistentes para facilitar no solo la trazabilidad de datos y metadatos, sino que su versionamiento y validez. Esto último en el contexto de credibilidad y transparencia es esencial, para tener certeza de que son los mismos encontrados y/o usados inicialmente. De esta forma **ofrecen un contexto robusto para maximizar el valor de los datos** generados y utilizados en todas las esferas de la investigación, la innovación y la toma de decisiones políticas, más allá de los contextos públicos o privados.

Junto con lo anterior, puede facilitar la integración y colaboración de las iniciativas surgidas tanto por la Política Nacional de Ciencia, Tecnología, Conocimiento e Innovación [\[8\]](https://minciencia.gob.cl/politicactci/documentos/Politica-Nacional-CTCi\_Chile-2020.pdf), el Proyecto de Ley sobre Transferencia de Tecnología y Conocimiento [\[9\]](https://www.camara.cl/legislacion/ProyectosDeLey/tramitacion.aspx?prmID=17258\&prmBOLETIN=16686-19), y a su vez, reforzar la implementación de la Política de Acceso Abierto ANID [\[6\]](https://s3.amazonaws.com/documentos.anid.cl/estudios/Politica\_acceso\_a\_informacion\_cientifica\_2022.pdf). En un contexto estratégico, podemos destacar los siguientes beneficios:

- **Mejora de la Calidad y Eficiencia en la Investigación y Desarrollo:** La aplicación de los principios FAIR promueve una mayor eficiencia y efectividad en la investigación, al facilitar el acceso y la reutilización de datos y metadatos entre disciplinas y sectores. Esto se traduce en una reducción de la duplicación de esfuerzos y en la aceleración del proceso de descubrimiento científico (Wilkinson et al., 2016). Esto considera que el manejo de datos es un proceso continuo a lo largo del proyecto de investigación, requiriendo planificación y documentación constante en un plan de gestión de datos. Esto facilita y complementa los alcances del plan de gestión de datos del sistema nacional de ciencia y tecnología, así como los de las diversas instituciones que han desarrollado uno propio. Ello implica un compromiso en el desarrollo de capacidades y formación dirigidos a investigadores, especialistas en datos y gestores de proyectos, con el objetivo de fomentar una profunda comprensión y aplicación de los principios FAIR, complementando así los planes de gestión de datos existentes a nivel nacional e institucional.

- **Fomento de la Innovación Abierta:** La Estrategia FAIR fomenta un ecosistema de innovación abierta al hacer que los datos y metadatos sean más accesibles y reutilizables no solo para la comunidad científica sino también para el sector privado y el público general. Esto es particularmente relevante para impulsar soluciones innovadoras en respuesta a desafíos sociales y económicos, en concordancia con concursos públicos, como el programa de innovación abierta que vincula ciencia y tecnología [\[10\]](https://www.gob.cl/noticias/desafios-publicos-minciencia-y-corfo-lanzan-el-primer-programa-de-innovacion-abierta-que-vincula-ciencia-y-tecnologia/), así como con convenios, como el existente entre el Ministerio de Defensa Nacional y el Ministerio de Ciencia, Tecnología, Conocimiento e Innovación [\[11\]](https://www.gob.cl/noticias/ministerios-de-defensa-y-ciencia-firman-convenio-para-fomentar-la-investigacion-y-la-innovacion-en-ciencia-y-tecnologia/) (OECD, 2019).

- **Promoción de la Colaboración Intersectorial:** Al favorecer la interoperabilidad de los datos y metadatos, los principios FAIR facilitan la colaboración intersectorial, permitiendo que distintos actores (academia, industria, gobierno) trabajen conjuntamente en proyectos de investigación y desarrollo, potenciando así los esfuerzos de innovación colaborativa. Esto facilitaría el acceso equitativo a los recursos técnicos necesarios para implementar FAIR, en concordancia con el Plan de Acción de la Política Nacional de Ciencia, Tecnología, Conocimiento e Innovación [\[12\]](https://minciencia.gob.cl/politicactci/documentos/Politica-Nacional-CTCI\_Plan\_Accion\_Chile\_2020.pdf) y con los desafíos planteados por el Laboratorio de Gobierno en su documento *Permitido innovar: ¿Cómo podemos desarrollar proyectos de ciencia de datos para innovar en el sector público?* [\[13\]](https://www.lab.gob.cl/permitido-innovar).

- **Aumento de la Transparencia y la Confianza en la Ciencia:** Implementar una gestión de datos que siga los principios FAIR aumenta la transparencia de los procesos de investigación y fortalece la confianza del público en la ciencia, al facilitar la verificación y replicación de resultados científicos [\[14\]](https://observa.minciencia.gob.cl/encuesta/encuesta-nacional-de-percepcion-social-de-la-ctci) (Mons et al., 2017).

- **Contribución al Desarrollo Sostenible:** La accesibilidad y reutilización de datos y metadatos según los principios FAIR apoyan los esfuerzos para abordar los Objetivos de Desarrollo Sostenible (ODS), proporcionando una base para facilitar el análisis de los productos de investigación, y de esta forma, favorecer su uso para la toma de decisiones informada por evidencia en áreas críticas como el cambio climático, la salud y la igualdad social (United Nations, 2015).

- **Posicionamiento Estratégico Internacional:** Al alinear su estrategia de gestión de datos con los principios FAIR, Chile se posiciona estratégicamente en el escenario internacional como un líder en la adopción de prácticas de datos abiertos y reutilizables, favoreciendo su integración en redes globales de investigación e innovación. A su vez, facilita la colaboración con iniciativas internacionales como la nube europea de ciencia abierta (EOSC) y la directiva de datos abiertos de la UE.

- **Desarrollo de Recursos Educativos Abiertos:** Se implementará una estrategia que centralice guías, mejores prácticas, herramientas recomendadas y estudios de caso sobre la gestión de datos. Estos recursos fortalecerán el acceso a información vital para la implementación de los principios FAIR, promoviendo el intercambio de conocimiento y la estandarización de prácticas en la gestión de datos a nivel nacional.

- **Reutilización Ética y Accesibilidad Segura**: Las Responsible AI Licenses (RAIL) son un conjunto de licencias diseñadas para promover el uso abierto de la inteligencia artificial, estableciendo restricciones que garantizan aplicaciones éticas y responsables, previniendo usos que puedan ser perjudiciales para la sociedad.

## 4. Stakeholders

Los stakeholders son individuos, grupos u organizaciones que tienen un interés en el desarrollo, implementación y resultados de la Estrategia FAIR. **Su participación es crucial para asegurar el éxito del proyecto**, ya que aportan recursos, conocimiento y apoyo. En el ecosistema abierto de Chile, estos stakeholders incluyen entidades del sector público, privado y mixto, cuyos objetivos y actividades son de dominio público y contribuyen activamente al acceso, uso y reutilización de datos abiertos.

### Clasificación según estrategia

#### Sector Público

- Alcance: Este sector comprende instituciones gubernamentales que trabajan en políticas públicas, regulación y promoción del acceso a datos abiertos.  
- Acciones: Desarrollar políticas de datos abiertos, regular el acceso y uso de datos, y promover la transparencia y la participación ciudadana.

#### Sector Privado

- Alcance: Incluye empresas y consorcios que generan, gestionan o utilizan datos para mejorar sus productos y servicios, y que están comprometidos con la responsabilidad social y la transparencia.  
- Acciones: Innovar en productos y servicios basados en datos abiertos, promover la responsabilidad social empresarial y contribuir al desarrollo económico mediante el uso de datos.

#### Sector Mixto

- Alcance: Incluye universidades, centros de investigación y ONGs que trabajan en colaboración con sectores públicos y privados para avanzar en la investigación, educación y políticas de datos abiertos.  
- Acciones: Apoyar la investigación y la educación abierta, impulsar la colaboración interdisciplinaria y promover la inclusión y el acceso equitativo a los datos.

### Roles de los Stakeholders respecto a datos / metadatos

- **Generación**: Producción de datos abiertos y de alta calidad.  
- **Uso**: Aplicación de datos abiertos en diferentes ámbitos para el desarrollo de productos, servicios y políticas.  
- **Investigación**: Estudio y análisis de datos abiertos para avanzar en el conocimiento y la innovación.  
- **Regulación**: Definición de políticas, normas y estándares para la gestión y uso de datos abiertos.  
- **Implementación**: Ejecución de proyectos y estrategias para la integración y uso de datos abiertos en diversos sectores.  
- **Innovación**: Desarrollo de nuevas tecnologías, métodos y prácticas basadas en datos abiertos para mejorar procesos y soluciones en diferentes sectores.

### Principales Stakeholders Identificados

| Organizaciones | Clasificación según estrategia | Rol |
| :---- | :---- | :---- |
| Red Centros / Iniciativa Ciencia de Datos UC | Mixto | Generación; Uso; Investigación |
| Instituto Milenio Fundamentos de los Datos IMFD | Mixto | Generación; Uso; Investigación |
| Infraestructura de Datos Geoespaciales de Chile IDE dependiente del Ministerio de Bienes Nacionales | Público | Generación; Uso; Regulación |
| Instituto Nacional de Estadísticas INE dependiente del Ministerio de Economía, Fomento y Turismo | Público | Generación; Uso; Regulación |
| ANID (Ministerio de Ciencia, Tecnología, Conocimiento e Innovación) | Público | Generación; Uso; Implementación |
| Ministerio de Economía, Fomento y Turismo MinEcon | Público | Generación; Uso; Regulación |
| Ministerio de Ciencia, Tecnología, Conocimiento e Innovación MinCyT | Público | Generación; Uso; Regulación |
| Ministerio de Salud MinSal | Público | Generación; Uso; Regulación |
| Consejo Nacional de Ciencia, Tecnología, Conocimiento e Innovación para el Desarrollo Consejo CTCI | Mixto | Generación; Uso; Investigación |
| GOFair US | Mixto | Generación; Uso; Investigación |
| Ministerio de Educación MinEduc | Público | Generación; Uso; Regulación |
| Infraestructura Nacional de Acceso a la Información Científica INA | Público | Regulación |
| Centro de Investigación para la Gestión Integrada de Riesgo de Desastres CIGIDEN | Mixto | Generación; Uso; Investigación |
| Asociación Chilena de Empresas de Tecnologías de Información A.G. (ACTI) | Privado | Generación; Uso; Implementación; Innovación |
| Sociedad de Fomento Fabril (SOFOFA) | Privado | Generación; Uso; Implementación; Innovación |
| Centro de Ciencia del Clima y la Resiliencia \- CR2 | Mixto | Generación; Uso; Regulación |

Adicionalmente, existen a nivel nacional, múltiples ejemplos de instituciones destacadas en publicación de datos:

- Dirección Meteorológica de Chile  
- Instituto para la Resiliencia ante Desastres (ITREND)  
- Ministerio de Hacienda  
- Ministerio de Medio Ambiente  
- Ministerio Secretaría General de la Presidencia

## 5. Brechas

En la labor diaria de los investigadores se evidencia la necesidad de avanzar en la reutilización segura y eficaz de los resultados de la investigación de la ciencia abierta. En la práctica, se han detectado brechas que es necesario cerrar para implementar los principios FAIR en nuestro país y así formar un ecosistema de conocimiento democrático y accesible para toda la comunidad. Estas brechas generan necesidades que deben atenderse, como la generación de políticas, directrices y estándares comunes para facilitar el acceso, descubrimiento y reutilización de los resultados de investigación, así como el cambio cultural que conlleva esta nueva práctica.

### Cambio cultural

Instalar un modelo que transite hacia los Datos Abiertos no es fácil; sin embargo, hoy en día resulta cada vez más necesario. Los investigadores al publicar sus datos, además de fortalecer su investigación, podrán contribuir al desarrollo del país, y como resultado se promoverá un desarrollo más equitativo y sostenible para toda la sociedad.

"El giro hacia la Ciencia Abierta es, como todos los cambios culturales de gran escala, un proceso complejo que \-para alcanzar justificados beneficios- no puede dejar de hacerse cargo de las tensiones, resistencias y ajustes ecosistémicos en nuestra institución. Por eso, el cambio tiene que ser gradual y progresivo, con participación de los distintos estamentos involucrados y con una mirada transversal que permita ir anticipando los desafíos que vayan surgiendo en su implementación” ([Bouchón, 2023](https://cienciaabierta.uc.cl/testimonios/vicerrector-de-investigacion/)).

### Reconocimientos e Incentivos

**Reconocimiento académico**: Se valora y reconoce la investigación abierta en los procesos de evaluación académica, como las promociones y los ascensos. Esto puede incluir la consideración de prácticas de investigación abierta en la evaluación de la calidad y el impacto de la investigación, así como en la evaluación de la contribución del investigador a la comunidad científica.

**Métricas tradicionales versus Métricas de calidad**: Actualmente, los investigadores deben demostrar el impacto de su investigación, que generalmente se mide a través de las métricas tradicionales como el factor de impacto. Para transitar de manera exitosa al modelo de datos abiertos, se requiere complementar incorporando nuevos criterios de evaluación académica. Migrar la evaluación de la ciencia desde el factor de impacto hacia la calidad de la investigación es esencial para promover un sistema más justo y riguroso.

La evaluación debería enfocarse en la calidad intrínseca de la investigación, en lugar de depender exclusivamente  de métricas cuantitativas como el factor de impacto de una revista, considerando aspectos como la originalidad, relevancia, rigor metodológico, transparencia y el impacto real en la comunidad científica y la sociedad. Este enfoque más holístico no solo reconoce la diversidad de la investigación científica, sino que también fomenta una cultura académica más inclusiva, colaborativa y orientada hacia el avance del conocimiento.

### Financiamiento institucional y gubernamental para la investigación abierta

El diseño de políticas públicas que garanticen el acceso a las publicaciones generadas con fondos públicos es uno de los temas que hoy copan la agenda de los organismos que financian las actividades de ciencia, tecnología, conocimiento e innovación (CTCI). Se requiere que las agencias de financiamiento, públicas y privadas, proporcionen fondos específicos para proyectos de investigación que adopten prácticas abiertas. Esto puede incluir financiamiento adicional para cubrir los costos asociados con la publicación en acceso abierto de sus artículos, alojamiento de datos en repositorios de acceso abierto y el desarrollo de infraestructuras de investigación abierta.  Además, esto tiene la externalidad positiva de fomentar la Innovación Abierta.

### Crecimiento y proyección de una red de investigación a nivel nacional

El documento publicado en 2024 por la Subdirección de Redes, Estrategia y Conocimiento de la ANID, en colaboración con el Comité Técnico Asesor de la Red de Apoyo a la Infraestructura Nacional de Acceso (INA), titulado: *Directrices de Metadatos y Mecanismos de Interoperabilidad*, representa el primer paso hacia la creación de un Nodo Nacional de Acceso. Por ello, es necesario optimizar este sistema/nodo nacional de investigación que permita proyectar la investigación chilena a nivel internacional como un esfuerzo conjunto, en lugar de depender de las capacidades individuales de cada institución.

#### Capacitación y apoyo

Se requieren programas de capacitación y apoyo para investigadores que desean adoptar prácticas de investigación abierta. Esto puede incluir talleres, recursos en línea y asesoramiento personalizado sobre cómo compartir datos de manera ética y efectiva, publicar en revistas de acceso abierto y cumplir con los requisitos de políticas de acceso abierto. Para lograr esto es necesario, como primer paso, desarrollar un programa de formación para formadores, para preparar a profesionales como "data stewards".

#### Fragmentación de datos

En la actualidad, los datos en laboratorios e instituciones suelen estar dispersos en diversas plataformas, repositorios genéricos o temáticos. Algunas disciplinas carecen de repositorios específicos, y los datos se presentan en distintos formatos, lo que complica su localización, acceso, reproducibilidad, reutilización e interoperabilidad. Los metadatos no estandarizados y la organización inconsistente de los datos obstaculizan el descubrimiento y reutilización efectiva de éstos.

#### Problemas de interoperabilidad

La incompatibilidad entre diferentes sistemas de software, herramientas y formatos dificulta la integración e interoperabilidad de datos. La falta de modelos de datos estandarizados, ontologías y vocabularios controlados obstaculiza el intercambio e integración de datos FAIR entre disciplinas y dominios de investigación. Este aspecto podría mejorar significativamente si se consensuan estándares entre diferentes disciplinas y contextos, independientemente de la fragmentación existente en los repositorios nacionales. Actualmente, el documento *Directrices de metadatos y mecanismos de interoperabilidad* publicado por la Subdirección de Redes, Estrategia y Conocimiento de la ANID, en colaboración con el Comité Técnico Asesor de la Red de Apoyo a la Infraestructura Nacional de Acceso ([INA](https://acceso-abierto.anid.cl/comites_tecnicos_asesores_ina/)), establece [lineamientos clave para el uso de metadatos y la interoperabilidad en infraestructuras abiertas](https://acceso-abierto.anid.cl/wp-content/uploads/sites/4/2024/05/Metadatos_para_la_Interoperabilidad_de_los_Repositorios_2024.pdf).

#### Accesibilidad limitada

El acceso a los datos está restringido debido a preocupaciones de propiedad o privacidad, lo que resulta en disponibilidad limitada y obstaculiza la colaboración y la reproducibilidad. Consideraciones legales y éticas, junto con preocupaciones sobre seguridad, confidencialidad y propiedad intelectual, representan barreras que podrían atenuarse al adoptar los principios FAIR y compartir datos abiertos.

#### Calidad de datos y falta de documentación

Una documentación inadecuada, metadatos incompletos y formatos de datos inconsistentes afectan la calidad y confiabilidad de los datos. Una documentación deficiente dificulta comprender el contexto de los mismos, complicando la validación e interpretación. La incorporación de herramientas de Machine Learning que permitan asistir al creador o encargado de los datos, podría facilitar, agilizar y mejorar el proceso.

#### Infraestructura y recursos

Algunas instituciones carecen de la infraestructura necesaria, recursos y experiencia técnica para implementar prácticas efectivas de gestión de datos según los principios FAIR. Esto abarca desafíos relacionados con el almacenamiento, la copia de seguridad, la curación y la preservación a largo plazo de los datos.

## 6. Componentes para reducir las brechas

La implementación de los principios FAIR es un proceso integral que incluye diversos niveles: la cultura en la gestión de datos, la formación en los principios FAIR y los requerimientos tecnológicos para construir un ecosistema FAIR. Estos tres pilares, según la iniciativa GO FAIR, mitigan las brechas y necesidades nacionales y posibilitan la transición a un sistema de datos FAIR. Este capítulo desarrolla la importancia de la política FAIR y las capacitaciones en estos principios como puntos clave en la ruta hacia un sistema FAIR.

### Apoyo institucional de la Estrategia FAIR

Para desarrollar una Estrategia FAIR que responda a las necesidades de Chile, es fundamental que la ANID y el Ministerio de Ciencia, Tecnología, Conocimiento e Innovación (MinCiencia) instalen una agenda FAIR oficial. La transformación de Chile en un país con un ecosistema FAIR, requiere un plan que integre aspectos técnicos, políticos y financiamiento específico para garantizar su implementación.

Una política oficial de FAIR en Chile permitiría incluir a más actores de la sociedad en este proceso de transformación de manera eficaz. Asimismo, una agenda FAIR a nivel nacional potenciaría los beneficios de contar con sistemas y datos FAIR, promoviendo, reconociendo y apoyando a diversas organizaciones en la implementación de estos principios.

### Cómo FAIR cubrirá las necesidades en Chile

El capítulo de brechas contempla los puntos claves en que Chile puede aprovechar dar un avance hacia los principios FAIR. En los párrafos siguientes se detalla cómo la iniciativa GO FAIR puede facilitar este proceso.

#### Prioridad de la agenda FAIR: Capacitación y entrenamiento

##### ¿A quién se dirigen las capacitaciones?

Para la mantención y el desarrollo del ecosistema FAIR, la formación de varias personas en diferentes roles será necesaria. Funcionarios y representantes necesitan comprender los principios FAIR a nivel estratégico, mientras que actores clave en universidades, centros de investigación y empresas pueden beneficiarse de entender las ventajas y aplicaciones de estos principios en sus organizaciones. A los/las profesionales de datos, llamados data stewards, hay que facilitarles un entrenamiento adecuado. Finalmente, se recomienda formar a los/las administradores de sistemas, ingenieros/as y desarrolladores de TI en los asuntos técnicos de los datos FAIR.

##### Los diferentes formatos de capacitación en FAIR

Desde la experiencia de GO FAIR US, se recomienda desarrollar planes de formación y entrenamiento específicos para estos roles clave, incluyendo su financiación. Mientras que la creación de sistemas e infraestructura para la gestión de datos requiere un apoyo puntual al momento de su implementación, la capacitación necesitará un financiamiento continuo, ya que siempre será necesario formar nuevos data stewards, o actualizar las competencias de los ya existentes, especialmente en los sistemas FAIR que se vayan desarrollando..

Por lo tanto, se recomienda dedicar fondos a la educación y formación FAIR. Con apoyo financiero, FAIR Chile podría implementar las siguientes medidas educativas, basándose en GO TRAIN, el segundo pilar del marco de GO FAIR:

- **Formación en agenda FAIR:** da una visión global del potencial de los principios FAIR, el desarrollo de políticas FAIR y sus puntos claves. La formación está dirigida a actores interesados, intermediarios y responsables de la toma de decisiones de diferentes áreas, del sector público y privado.  
- **Entrenamiento en data stewardship:** la formación para ejercer el rol de data steward o curador/a de datos científicos en universidades, centros de investigación, u otras entidades públicas y privadas.

- **Entrenamiento FAIR en la investigación**: para investigadores, enfocado en entregar el conocimiento y las herramientas para diseñar un flujo de investigación orientado a los principios FAIR en todas las fases de la investigación científica.

- **Talleres**: enfocados en herramientas y conocimiento técnico para equipos de TI. Los talleres pueden ser capacitaciones o formatos más colaborativos, como sesiones de programación conjunta.

#### Financiamiento gubernamental e institucional para la investigación abierta

Desde el año 2022, la Agencia Nacional de Investigación y Desarrollo (ANID) exige obligaciones de acceso abierto a proyectos que producen resultados científicos y que así lo indiquen sus bases. Se recomienda el desarrollo continuo de una política de fondos públicos que promueva la aplicación de los principios FAIR en los procesos de investigación, tomando en cuenta los diferentes tipos de resultados científicos en todas las fases del proceso investigativo.

Asimismo, la política vigente se alinea con los principios de la ciencia abierta, incorporando los principios FAIR. Hasta ahora, la ANID ha publicado dos documentos clave: la *"Política de acceso abierto a la información científica y a datos de investigación financiados con fondos públicos de la ANID”* y las *"Directrices de metadatos y mecanismos de Interoperabilidad”* (Agencia Nacional de Investigación y Desarrollo (ANID), 2022; Agencia Nacional de Investigación y Desarrollo (ANID), 2024). Aunque estos documentos abordan aspectos importantes como el acceso abierto y la interoperabilidad, no incluyen referencias explícitas a otros principios de los datos FAIR, como la reutilización o la localización de los datos.

Además, la entidad Data Observatory promueve el desarrollo de datos abiertos en Chile, para "maximizar el beneficio de los que se puede obtener de los datos para la ciencia, la investigación y el desarrollo productivo, a través de la creación, administración y enriquecimiento de plataformas de datos abiertos \[…\]”. (*Data Observatory*, s. f.) Se recomienda incluir otras instituciones y actores interesados que tengan una amplia experiencia como el Data Observatory en el desarrollo de una normativa.

#### Cambio cultural: el sector académico

Es fundamental, incluir "a todas las partes interesadas relevantes en todos los niveles” del sector académico dentro de este proceso (*GO FAIR Initiative*, s. f.).

Desde 2022, varias universidades chilenas están implementado culturas de ciencia abierta a través de proyectos **InES Ciencia Abierta**, financiados por la ANID. En estos proyectos, el cambio de cultura se efectúa a través de capacitaciones internas, la instalación de repositorios para publicaciones y datos, el cambio de la política de las universidades respecto a la ciencia abierta, y la creación de redes nacionales e internacionales. Varios proyectos InES lograron establecer propuestas para una política de ciencia abierta, sin embargo, estas carecen de carácter obligatorio. Se recomienda fortalecer y dar continuidad a estos esfuerzos en las universidades, ya que el apoyo de los fondos ANID termina con el cierre del proyecto. Con frecuencia, las unidades responsables de los proyectos InES no reciben respaldo adicional por parte de sus universidades, limitando su capacidad para promover la cultura académica más allá del alcance inicial del proyecto.

Aunque los cambios culturales inducidos por proyectos en las universidades, se han generado principalmente desde iniciativas ascendentes, se recomienda complementarlos e incentivar transformaciones descendentes. La **Comisión Nacional de Acreditación (CNA)** de Chile evalúa y acredita la calidad de las Instituciones de la educación superior de Chile que están bajo la responsabilidad del Ministerio de Educación. Se recomienda incluir los principios FAIR en los criterios e indicadores de la CNA. La ventaja de esta inclusión sería un reconocimiento de los principios FAIR en las políticas universitarias respecto a los datos, los tratamientos de los datos y la investigación. Además, las universidades podrían ser incentivadas a adherirse a la cultura de ciencia abierta.

#### Crecimiento y proyección de una red de investigación a nivel nacional

Bajo la creación de una red de investigación a nivel nacional, se recomienda la promoción y extensión del **Nodo Chile** (iniciativa liderada por ANID), y su conexión a redes globales de datos científicos, como la European Science Cloud. En Chile, se recomienda superar el aislamiento de los datos científicos almacenados en grandes silos, promoviendo una conexión nacional que, a través del Nodo Chile, facilite la integración de las bases de datos chilenas con redes globales, tanto para compartir como para recibir información.

#### Fragmentación de datos y problemas de interoperabilidad

Para enfrentar la fragmentación de datos y los problemas de interoperabilidad, se recomienda desarrollar **repositorios interoperables** con formatos y estándares que posibiliten el intercambio, localización, acceso y reutilización de los datos. Además, se recomienda revisar constantemente los **estándares de metadatos**, actualizando y manteniendo los metadatos en los repositorios del **Nodo Chile** compatibles para integrarse a los sistemas globales.

Por lo anteriormente expuesto, se propone desarrollar modelos de datos estandarizados, así como ontologías y vocabularios controlados, que faciliten el intercambio e integración de datos FAIR entre diversas disciplinas y áreas de investigación.

#### Calidad de datos y falta de documentación

La baja calidad y la falta de metadatos o documentación de datos sigue siendo un problema en Chile. Esto refleja la ausencia de políticas sólidas de datos en organizaciones públicas y privadas, tal como la falta de una **política nacional de gobernanza de datos**. Se recomienda establecer normativas claras sobre la gobernanza de datos y seguridad de datos a nivel nacional que respalden las políticas institucionales y garanticen un manejo adecuado y una mejora en la calidad de los datos..

Con el respaldo de leyes y directrices a nivel nacional se facilita la promoción e implementación de políticas institucionales en el sector público y privado, incluyendo la financiación de puestos clave, como responsables de gobernanza de datos, curadores/as de datos y otros especialistas. Grandes entidades públicas, como las universidades, que manejan una gran cantidad de datos, algunos de ellos sensibles, necesitan contar con una política de datos bien definida, además de profesionales dedicados que garanticen su implementación efectiva.

#### Accesibilidad limitada

De la misma manera, la accesibilidad limitada a los datos requiere medidas diferentes, según el motivo que existe detrás de esa limitación:

- **Preocupaciones respecto a la propiedad de datos**: Es importante clarificar las políticas institucionales respecto a la propiedad de datos. Para lograr esto, se hace necesario desarrollar acuerdos claros sobre el uso de datos en las diferentes organizaciones que los gestionan y utilizan. En el caso de las universidades, significa establecer directrices que definen de manera precisa a quién pertenecen los datos de investigación y en qué momento.
- **Preocupaciones respecto a la privacidad**: Para garantizar el adecuado manejo de datos, es esencial colaborar estrechamente con los comités éticos, para garantizar que cada conjunto de datos se publique tan abierto como puede ser, pero tan cerrado como sea necesario; es decir, se publique con el nivel de apertura permitido, pero con las restricciones necesarias para proteger la privacidad. Además, los datos deben estar acompañados de la licencia correspondiente que especifique claramente las condiciones de uso y reutilización. En el caso de organizaciones o institutos que tengan dudas sobre el impacto de los datos en la privacidad de las personas, se recomienda realizar evaluaciones de impacto en privacidad para mitigar posibles riesgos.  
- **Preocupaciones respecto a la seguridad de datos**: Es necesario desarrollar repositorios de acceso abierto que ofrezcan una alta protección contra ataques y fraudes, que sean mantenidos de manera regular y estén sujetos a auditorías y monitoreo constante. En ese contexto, existen repositorios certificados con diferentes sellos de seguridad, y se recomienda adoptar y usar esas mismas certificaciones para los repositorios de Chile.

La implementación de los principios FAIR es un proceso continuo que demanda un enfoque multifacético y colaborativo. Abordar de manera proactiva las preocupaciones sobre propiedad, privacidad y seguridad, junto con fomentar una cultura institucional que priorice la apertura y la transparencia, son pasos clave para avanzar en la implementación efectiva de los principios FAIR.

### Oficina GO FAIR Chile

#### La iniciativa GO FAIR international

GO FAIR es una iniciativa internacional autogestionada, cuyo objetivo es aplicar los principios de datos FAIR. Se basa en comunidades nacionales de expertos/as y partes interesadas, las llamadas redes de implementación, que llevan a cabo la definición y creación de materiales y herramientas FAIR en su país.

Las redes están acompañadas por Oficinas Nacionales de Apoyo, la representación más concreta de GO FAIR en los distintos países. El propósito de las Oficinas Nacionales de Apoyo es:

>*reconocer y apoyar los principios que constituyen la base de la Iniciativa GO FAIR de redes de implementación independientes, si bien coordinadas* (GO FAIR, s. f.).

Las oficinas garantizan la participación de todos/as los/las interesados/as a nivel nacional en la iniciativa y coordinan la organización. Por otra parte, las oficinas están en coordinación con las Oficinas Internacionales de Apoyo y Coordinación, instaladas actualmente en Leiden (Países Bajos), Hamburgo (Alemania) y París (Francia). Aparte de las oficinas en Holanda, Alemania y Francia, existe la Oficina GO FAIR US en San Diego, que promueve la coordinación con las iniciativas nacionales GO FAIR en todo el continente americano.

La Oficina Internacional de Apoyo y Coordinación da soporte a las Oficinas Nacionales de Apoyo en la planificación de sus actividades, pero no proporciona respaldo financiero. Las oficinas son responsables de sus propios gastos y se mantienen independientes de organizaciones con ánimo de lucro, aunque se pueden alojar físicamente en otras instituciones. Colaboran estrechamente con las autoridades nacionales para implementar los principios FAIR.

#### La Oficina Nacional de Apoyo en Chile

Se recomienda fundar y apoyar una Oficina Nacional de Apoyo en Chile. La oficina GO FAIR Chile conectará a todos los grupos de interés con las universidades e instituciones que formen parte de la red nacional FAIR, avanzando en la inclusión de los principios FAIR en la investigación. Apoyará en el intercambio de buenas prácticas entre la ANID, las universidades, centros y comunidades de investigación, organizaciones públicas y privadas de financiación de la investigación, junto con el Ministerio de Ciencia, Tecnología, Conocimiento e Innovación como facilitador. Además, coordinará las actividades de formación y capacitación en los principios FAIR.

La instalación de una oficina ayudaría así a establecer una comunidad FAIR en Chile, a trabajar en una directiva nacional clara para el ecosistema FAIR, y a coordinarse tanto a nivel nacional como internacional con las partes interesadas, las Oficinas Internacionales de Apoyo y Coordinación y las autoridades gubernamentales para desarrollar un ecosistema FAIR en Chile.

La oficina GO FAIR sería un apoyo sustancial para que en Chile se acelere la ciencia y la innovación, ahorre recursos en actividades de investigación y mejore el retorno de inversiones para los contribuyentes. Además, Chile podría ser la primera nación hispanohablante en tener una Oficina Nacional de Apoyo GO FAIR en todo el mundo y unirse a los países líderes en el movimiento FAIR.

El paso previo desde el lanzamiento de esta Estrategia será la generación de mesas de trabajo multidisciplinarias para poder definir el plan de acción y seguimiento del mismo.

### Divulgación

La estrategia de divulgación para implementar los principios FAIR en Chile debe articularse en tres niveles complementarios: institucional, educativo y técnico-cultural. A nivel institucional, es fundamental posicionar la iniciativa FAIR como una política nacional oficial respaldada por ANID y el Ministerio de Ciencia, a través de canales formales de comunicación gubernamental, eventos interministeriales y campañas digitales que destaquen cómo esta transformación beneficiará al ecosistema de datos nacional y en especial, al científico chileno. Este esfuerzo debe incluir webinars informativos para tomadores de decisiones, documentos de posición estratégica y la promoción de casos de éxito nacional e internacional que evidencien el retorno de inversión para quienes participan.

En el ámbito educativo, la divulgación se centrará en programas de capacitación diferenciados según el público objetivo: sesiones estratégicas para directivos de universidades, centros de investigación, sociedad civil y entidades gubernamentales, talleres prácticos para data stewards, y módulos formativos para investigadores y equipos técnicos. Estos programas serán difundidos a través de redes académicas existentes, plataformas educativas nacionales, alianzas con los proyectos InES de Ciencia Abierta, y difusión por parte de las entidades gubernamentales participantes, complementados con un repositorio centralizado de recursos educativos que incluya guías, infografías y videos tutoriales adaptados al contexto chileno, posicionando los beneficios concretos de los principios FAIR para cada segmento.

El tercer nivel abordará el cambio técnico-cultural mediante una estrategia de comunicación que incluya comunidades de práctica, grupos de trabajo interdisciplinarios y eventos participativos que promuevan la colaboración entre diferentes sectores. Esto se complementará con la difusión de estándares técnicos, buenas prácticas y herramientas para la implementación de repositorios interoperables, destacando las ventajas de Chile como potencial primer país hispanohablante con una Oficina Nacional GO FAIR. La estrategia incluirá boletines periódicos, presencia en redes sociales especializadas y un programa de embajadores y data stewards FAIR que actúen como multiplicadores del conocimiento en sus respectivas instituciones, creando así un movimiento nacional hacia la transformación digital del ecosistema de datos nacional.

La divulgación debe ser una actividad transversal que fomente una cultura de datos abiertos y promueva la colaboración entre instituciones, investigadores y la sociedad civil. En este sentido, se sugiere establecer alianzas estratégicas con

## 7. Casos de éxito FAIR en Chile

Para iniciar esta sección, se enumeran algunas iniciativas de gobernanza a nivel nacional y local. Luego, se detallan casos de éxito específicos en Chile.

### Iniciativas de gobernanza a nivel nacional

- Política de acceso abierto a la información científica y a datos de investigación financiados con fondos públicos de la [\[6\]](https://s3.amazonaws.com/documentos.anid.cl/estudios/Politica\_acceso\_a\_informacion\_cientifica\_2022.pdf);
- Plan de Gestión de Datos, Agencia Nacional de Investigación y Desarrollo ANID (2023) [\[15\]](https://www.cincel.cl/documentos/PGD\_20220506.pdf);  
- Directrices de Metadatos y Mecanismos de Interoperabilidad; Agencia Nacional de Investigación y Desarrollo ANID & Comité Técnico Asesor de la Red de Apoyo a la Infraestructura Nacional de Acceso (INA) (2024) [\[16\]](https://acceso-abierto.anid.cl/wp-content/uploads/sites/4/2024/05/Metadatos\_para\_la\_Interoperabilidad\_de\_los\_Repositorios\_2024.pdf).

### Iniciativas de gobernanza a nivel regional

- LA Referencia apoyo a las estrategias nacionales de Ciencia Abierta en América Latina y España (LA Referencia, s. f.) [\[27\]](https://www.lareferencia.info/es/).

### Iniciativas de gobernanza a nivel local

- Política de Ciencia Abierta de la Universidad Central de Chile. Universidad Central de Chile (2023) [\[17\]](http://doi.org/10.5281/ZENODO.10204585);  
- Declaración de interoperabilidad de metadatos Repositorio Institucional Universidad Central de Chile (2024) [\[18\]](http://doi.org/10.5281/ZENODO.10523136);
- Plantilla del Plan de Gestión de Datos de la Universidad Central de Chile (2023) [\[19\]](http://doi.org/10.5281/ZENODO.10067320);
- Plan de Gestión de Datos Universidad Católica de la Santísima Concepción (2023) [\[20\]](https://cienciaabierta.ucsc.cl/wp-content/uploads/sites/157/2023/11/Formato-Plan-de-Gestion-de-Datos-UCSC.docx);
- Política Institucional de Ciencia Abierta de la Universidad Católica de la Santísima Concepción (2023) [\[21\]](https://cienciaabierta.ucsc.cl/wp-content/uploads/sites/157/2023/08/D.R.\_108\_2023\_PROMULGA\_ACUERDO\_DEL\_HCS\_QUE\_APRUEBA\_POLITICA\_DE\_CIENCIA\_ABIERTA\_DE\_LA\_UCSC-2.pdf);
- Política de Ciencia Abierta de la Universidad del Desarrollo (2023) [\[22\]](https://www.udd.cl/wp-content/uploads/2022/08/dr-nro144-23-politica-ciencia-abierta-udd-timbrado.pdf).

### Evaluación de repositorios nacionales y plan de gestión de datos

El proyecto InES Ciencia Abierta de la Universidad Central de Chile, financiado por ANID generó una serie de documentos que permiten sentar las bases para el inicio de la gestión de datos abiertos de investigación. En primer lugar, se promulgó una Política de Ciencia Abierta que establece los ámbitos de acción, promoción y apoyo a la comunidad para comenzar a reconocer e integrar prácticas de ciencia abierta, incluido el fomento de los principios FAIR para los datos de investigación. La política establece que es necesario completar un plan de gestión de datos para toda investigación realizada en la universidad, así como depositar los datos de investigación en el nuevo Repositorio Institucional. 

Además, se hizo pública la Declaración de interoperabilidad de metadatos del Repositorio Institucional de la universidad, para permitir que otros repositorios puedan extraer datos, una práctica poco habitual según el estudio realizado por Hartley y Abedrapo [\[23\]](https://doi.org/10.5281/ZENODO.10557407).

### Disponibilización de datos científicos de estaciones de investigación

La Red de Centros y Estaciones Regionales de la Universidad Católica ([RCER](https://www.uc.cl/unidades-academicas/red-de-centros-y-estaciones-regionales-rcer-uc/)) busca apoyar la investigación interdisciplinaria de investigadores/as de la universidad a través de una red de centros y estaciones donde se desarrollan actividades de investigación, docencia de pre y postgrado y la interacción con los ecosistemas más relevantes del país. El proyecto liderado por la Iniciativa de Ciencia de Datos de la Universidad Católica (UC) tiene como objetivo principal poner a disposición datos para apoyar el desarrollo científico y maximizar el aprovechamiento de la información para generar más conocimiento e impacto. La iniciativa busca hacer accesibles datos relevantes, fomentando la investigación interdisciplinaria y potenciando soluciones a problemas locales y globales. Hacer que los datos estén disponibles es crucial para impulsar el desarrollo científico, ya que permite a investigadores y académicos explorar nuevas áreas de conocimiento, validar estudios previos y desarrollar innovaciones que pueden tener un impacto significativo en diversas disciplinas. Además, facilita la colaboración y el intercambio de información entre investigadores, lo que puede conducir a descubrimientos más rápidos y eficientes. Publicar datos de manera abierta promueve la transparencia en la investigación y permite la reproducibilidad de los estudios, fortaleciendo la confianza en los resultados científicos.

El proyecto enfrenta varios desafíos, como la gobernanza de datos, que implica implementar políticas claras para garantizar la calidad, seguridad y privacidad de los datos, estableciendo normativas sobre quiénes pueden acceder a los datos y bajo qué condiciones. También se abordan cuestiones éticas y de responsabilidad, asegurando que los datos se gestionan de manera ética, protegiendo la privacidad de los individuos y respetando las normas legales y éticas. Otro desafío es promover la interoperabilidad, facilitando que los datos sean fácilmente compartidos y utilizados entre diferentes sistemas y plataformas mediante el uso de estándares comunes.

Este esfuerzo se conecta estratégicamente con la apertura de una oficina de GO FAIR en Chile, una iniciativa global que promueve la implementación de los principios FAIR en la gestión de datos científicos. La oficina de GO FAIR en Chile ayudará a fortalecer la infraestructura de datos en el país, promoviendo mejores prácticas en la gestión de datos y facilitando la colaboración internacional.

### Construyendo las bases de la ciencia abierta en la Pontificia Universidad Católica de Chile

En el año 2021 la Universidad Católica de Chile, se adjudicó la ejecución del proyecto *"Construyendo las bases de la ciencia abierta en la Pontificia Universidad Católica de Chile”*, financiado por ANID. Este proyecto tuvo por objetivo instalar y/o fortalecer capacidades en materia de gestión abierta de publicaciones y datos científicos en la UC. En concreto, se buscó desarrollar un ecosistema institucional de ciencia abierta, que consideraba los modelos de operación, la participación de las personas, la publicación de los productos de la investigación, la gestión de los datos y la instalación de una infraestructura tecnológica estandarizada, abierta, independiente e interoperable con servicios y aplicaciones de acuerdo a las políticas de acceso abierto de ANID y estándares internacionales.

El proyecto abordó cuatro pilares: Gobernanza y políticas, Infraestructura y Servicios, Entrenamiento y Capacitación y Difusión y Redes. Entre los documentos generados, podemos mencionar:

- Lineamientos sobre las políticas de interoperabilidad entre sistemas y proyectos,
- Lineamientos para la difusión y formación continua en el ámbito de la Ciencia Abierta,
- Lineamientos para la aplicación de licencias Creative Commons a los resultados de investigación y finalmente los Lineamientos sobre Política de Preservación Digital de la UC [\[24\]](https://doi.org/10.7764/InESCA.UC.l06).

## 8. Estrategia integrada para la implementación de FAIR

Este capítulo presenta una estrategia operativa que transforma los componentes identificados en el documento en acciones concretas para alcanzar una política de datos FAIR robusta.

### Gobernanza y Coordinación

Se propone la creación de una Red Nacional de Implementación FAIR (GO FAIR) que integre al Ministerio de Ciencia, Tecnología, Conocimiento e Innovación, la Agencia Nacional de Investigación y Desarrollo (ANID), universidades, centros de investigación, empresas, startups de datos y representantes de la sociedad civil. Esta red facilitará la coordinación interinstitucional y la colaboración en la toma de decisiones estratégicas. Además, se establece la Oficina GO FAIR como eje central para articular y ejecutar la estrategia.  

### Infraestructura y Estándares

Desarrollar una infraestructura de datos que permita la interoperabilidad entre repositorios actuales, mediante la adopción de identificadores persistentes (DOI, ORCID, etc.) y metadatos estandarizados según los principios FAIR. Esto creará la base técnica para integrar los distintos componentes y asegurar un flujo de datos eficiente y accesible.  

### Capacitación y Desarrollo de Capacidades

Implementar un programa nacional de formación en ciencia abierta y datos FAIR, que ofrezca cursos y talleres sobre estándares, gestión de datos, interoperabilidad y ética de datos. Esta iniciativa fortalecerá las competencias digitales en universidades y organizaciones, impulsando la cultura de datos FAIR.  

### Marco Normativo, Financiamiento y Evaluación

Ajustar el marco regulatorio vigente, alineándolo con las leyes de protección de datos y demás normativas pertinentes. Establecer fondos concursables y promover alianzas público-privadas para garantizar la sostenibilidad de la infraestructura. Finalmente, diseñar un sistema de monitoreo y evaluación que permita medir el impacto y realizar ajustes dinámicos a la estrategia.

Esta propuesta integral busca ensamblar los componentes identificados, generando el salto cualitativo necesario para la implementación exitosa de la política de datos FAIR en Chile.

## 9. Bibliografía

\[1\] M. D. Wilkinson *et al.*, "The FAIR Guiding Principles for scientific data management and stewardship”, *Sci. Data*, vol. 3, no 1, p. 160018, mar. 2016, doi: [10.1038/sdata.2016.18](https://www.nature.com/articles/sdata201618).

\[2\] I. Pan, L. R. Mason, y O. K. Matar, "Data-centric Engineering: integrating simulation, machine learning and statistics. Challenges and opportunities”, *Chem. Eng. Sci.*, vol. 249, p. 117271, 2022. [10.1016/j.ces.2021.117271](https://doi.org/10.1016/j.ces.2021.117271).

\[3\] R. González-Sendino, E. Serrano, y J. Bajo, "Mitigating bias in artificial intelligence: Fair data generation via causal models for transparent and explainable decision-making”, *Future Gener. Comput. Syst.*, vol. 155, pp. 384–401, jun. 2024, doi: [10.1016/j.future.2024.02.023](https://www.sciencedirect.com/science/article/pii/S0167739X24000694).

\[4\] Biblioteca Nacional del Congreso, "Decreto 20 Aprueba Política Nacional de Inteligencia Artificial”, www.bcn.cl/leychile. Accedido: 31 de mayo de 2024\. \[En línea\]. Disponible en: [https://www.bcn.cl/leychile/navegar?i=1169399\&f=2021-12-03](https://www.bcn.cl/leychile/navegar?i=1169399&f=2021-12-03).

\[5\] Transformación Pública y Prodigio Lab, "Portal \- Conocimiento Público”, Conocimiento Público. Accedido: 31 de mayo de 2024\. \[En línea\]. Disponible en: [https://www.conocimientopublico.cl/](https://www.conocimientopublico.cl).

\[6\] Agencia Nacional de Investigación y Desarrollo (ANID), "Política de acceso abierto a la información científica y a datos de investigación financiados con fondos públicos de la ANID”. Gobierno de Chile, 2022\. Accedido: 21 de junio de 2023\. \[En línea\]. Disponible en: [https://s3.amazonaws.com/documentos.anid.cl/estudios/Politica\_acceso\_a\_informacion\_cientifica\_2022.pdf](https://s3.amazonaws.com/documentos.anid.cl/estudios/Politica\_acceso\_a\_informacion\_cientifica\_2022.pdf)

\[7\] Research Data Alliance FAIR Data Maturity Model Working Group, "FAIR Data Maturity Model: specification and guidelines”, 2020, doi: [10.15497/RDA00050](https://dx.doi.org/10.15497/RDA00050).

\[8\] Ministerio de Ciencia, Tecnología, Conocimiento e Innovación de Chile, "Política Nacional de Ciencia, Tecnología, Conocimiento e Innovación”. 2020\. Accedido: 17 de mayo de 2024\. \[En línea\]. Disponible en: [https://minciencia.gob.cl/politicactci/documentos/Politica-Nacional-CTCi\_Chile-2020.pdf](https://minciencia.gob.cl/politicactci/documentos/Politica-Nacional-CTCi\_Chile-2020.pdf)

\[9\] Ministerio de Ciencia, Tecnología, Ciencia e Innovación; Ministerio de Economía, Fomento y Turismo; Ministerio de Educación, "Proyecto de Ley: Dicta normas sobre transferencia de tecnología y conocimiento”. 4 de enero de 2024\. Accedido: 17 de mayo de 2024\. \[En línea\]. Disponible en: [https://www.camara.cl/legislacion/ProyectosDeLey/tramitacion.aspx?prmID=17258\&prmBOLETIN=16686-19](https://www.camara.cl/legislacion/ProyectosDeLey/tramitacion.aspx?prmID=17258\&prmBOLETIN=16686-19)  

\[10\] Gobierno de Chile, "Desafíos Públicos: MinCiencia y Corfo lanzan el primer programa de innovación abierta que vincula ciencia y tecnología \- Gob.cl”, Gobierno de Chile. Accedido: 17 de mayo de 2024\. \[En línea\]. Disponible en: [https://www.gob.cl/noticias/desafios-publicos-minciencia-y-corfo-lanzan-el-primer-programa-de-innovacion-abierta-que-vincula-ciencia-y-tecnologia/](https://www.gob.cl/noticias/desafios-publicos-minciencia-y-corfo-lanzan-el-primer-programa-de-innovacion-abierta-que-vincula-ciencia-y-tecnologia/)

\[11\] Gobierno de Chile, "Ministerios de Defensa y Ciencia firman convenio para fomentar la investigación y la innovación en ciencia y tecnología \- Gob.cl”, Gobierno de Chile. Accedido: 17 de mayo de 2024\. \[En línea\]. Disponible en: [https://www.gob.cl/noticias/ministerios-de-defensa-y-ciencia-firman-convenio-para-fomentar-la-investigacion-y-la-innovacion-en-ciencia-y-tecnologia/](https://www.gob.cl/noticias/ministerios-de-defensa-y-ciencia-firman-convenio-para-fomentar-la-investigacion-y-la-innovacion-en-ciencia-y-tecnologia/)  

\[12\] Ministerio de Ciencia, Tecnología, Conocimiento e Innovación, "Plan de Acción de la Política Nacional de Ciencia, Tecnología, Conocimiento e Innovación”. 2020\. \[En línea\]. Disponible en: [https://minciencia.gob.cl/politicactci/documentos/Politica-Nacional-CTCI\_Plan\_Accion\_Chile\_2020.pdf](https://minciencia.gob.cl/politicactci/documentos/Politica-Nacional-CTCI\_Plan\_Accion\_Chile\_2020.pdf)

\[13\] Laboratorio de Gobierno, ["Permitido innovar: ¿Cómo podemos desarrollar proyectos de ciencia de datos para innovar en el sector público?”](https://www.lab.gob.cl/permitido-innovar) 2018.

\[14\] Ministerio de Ciencia, Tecnología, Conocimiento e Innovación, "Encuesta Nacional de Percepción Social de la Ciencia, Tecnología, Conocimiento e Innovación (CTCI) 2022”. 2022\. Accedido: 17 de mayo de 2024\. \[En línea\]. Disponible en: [https://observa.minciencia.gob.cl/encuesta/encuesta-nacional-de-percepcion-social-de-la-ctci](https://observa.minciencia.gob.cl/encuesta/encuesta-nacional-de-percepcion-social-de-la-ctci)

\[15\] Agencia Nacional de Investigación y Desarrollo ANID, "Plan de Gestión de Datos ANID v1”. mayo de 2022\. Accedido: 14 de mayo de 2024\. \[En línea\]. Disponible en: [https://www.cincel.cl/documentos/PGD\_20220506.pdf](https://www.cincel.cl/documentos/PGD\_20220506.pdf)

\[16\] Agencia Nacional de Investigación y Desarrollo ANID y Comité Técnico Asesor de la Red de Apoyo a la Infraestructura Nacional de Acceso (INA), "Directrices de Metadatos y Mecanismos de Interoperabilidad”. 2024\. Accedido: 22 de mayo de 2024\. \[En línea\]. Disponible en: [https://acceso-abierto.anid.cl/wp-content/uploads/sites/4/2024/05/Metadatos\_para\_la\_Interoperabilidad\_de\_los\_Repositorios\_2024.pdf](https://acceso-abierto.anid.cl/wp-content/uploads/sites/4/2024/05/Metadatos\_para\_la\_Interoperabilidad\_de\_los\_Repositorios\_2024.pdf)

\[17\] Universidad Central de Chile, "Política de Ciencia Abierta de la Universidad Central de Chile”, nov. 2023, doi: [10.5281/ZENODO.10204585](http://doi.org/10.5281/ZENODO.10204585).

\[18\] Universidad Central de Chile, "Declaración de interoperabilidad de metadatos Repositorio Institucional Universidad Central de Chile”, ene. 2024, doi: [10.5281/ZENODO.10523136](http://doi.org/10.5281/ZENODO.10523136)  

\[19\] R. Hartley y I. Abedrapo Rosen, "Plantilla del Plan de Gestión de Datos de la Universidad Central de Chile”, nov. 2023, doi: [10.5281/ZENODO.10067320](http://doi.org/10.5281/ZENODO.10067320)  

\[20\] Dirección de Investigación, Universidad Católica de la Santísima Concepción, "Plan de Gestión de Datos (PGD) Universidad Católica de la Santísima Concepción”. agosto de 2023\. Accedido: 14 de mayo de 2024\. \[En línea\]. Disponible en: [https://cienciaabierta.ucsc.cl/wp-content/uploads/sites/157/2023/11/Formato-Plan-de-Gestion-de-Datos-UCSC.docx](https://cienciaabierta.ucsc.cl/wp-content/uploads/sites/157/2023/11/Formato-Plan-de-Gestion-de-Datos-UCSC.docx).

\[21\] Universidad Católica de la Santísima Concepción, "Política Institucional de Ciencia Abierta de la Universidad Católica de la Santísima Concepción”. 15 de junio de 2023\. \[En línea\]. Disponible en: [https://cienciaabierta.ucsc.cl/wp-content/uploads/sites/157/2023/08/D.R.\_108\_2023\_PROMULGA\_ACUERDO\_DEL\_HCS\_QUE\_APRUEBA\_POLITICA\_DE\_CIENCIA\_ABIERTA\_DE\_LA\_UCSC-2.pdf](https://cienciaabierta.ucsc.cl/wp-content/uploads/sites/157/2023/08/D.R.\_108\_2023\_PROMULGA\_ACUERDO\_DEL\_HCS\_QUE\_APRUEBA\_POLITICA\_DE\_CIENCIA\_ABIERTA\_DE\_LA\_UCSC-2.pdf).

\[22\] Universidad del Desarrollo, "Política de Ciencia Abierta de la Universidad del Desarrollo”. 4 de diciembre de 2023\. \[En línea\]. Disponible en: [https://www.udd.cl/wp-content/uploads/2022/08/dr-nro144-23-politica-ciencia-abierta-udd-timbrado.pdf](https://www.udd.cl/wp-content/uploads/2022/08/dr-nro144-23-politica-ciencia-abierta-udd-timbrado.pdf).

\[23\] R. Hartley y I. Abedrapo Rosen, "Repositorios y Universidades Chilenas 2023”, 23 de enero de 2024\. doi: [10.5281/ZENODO.10557407](https://doi.org/10.5281/ZENODO.10557407).

\[24\] Pontificia Universidad Católica de Chile. *Lineamientos para Política de Preservación digital de la UC*. Accedido el 6 de julio de 2024. doi: [10.7764/InESCA.UC.l06](https://doi.org/10.7764/InESCA.UC.l06).

\[25\]   Ministerio de Ciencia, Tecnología, Conocimiento e Innovación, “Plan Nacional de Data Centers”. 2024\. Accedido: 03 de marzo de 2025\. \[En línea\]. Disponible en: [https://minciencia.gob.cl/uploads/filer\_public/95/6b/956b8c9f-d937-4b4d-8f6c-a871495a52ff/plan\_nacional\_de\_data\_centers\_pdata.pdf](https://minciencia.gob.cl/uploads/filer_public/95/6b/956b8c9f-d937-4b4d-8f6c-a871495a52ff/plan_nacional_de_data_centers_pdata.pdf)

\[26\]   Agencia Nacional de Investigación y Desarrollo (ANID). (s. f.). InES Ciencia Abierta. Recuperado 3 de febrero de 2025, de [https://acceso-abierto.anid.cl/componentes/inescienciaabierta/](https://acceso-abierto.anid.cl/componentes/inescienciaabierta/)

\[27\]   LA Referencia. (s. f.). LA Referencia. Recuperado 3 de febrero de 2025, de https://www.lareferencia.info/es/

Licencia: [Creative Commons Atribución-NoComercial 4.0 Internacional (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
