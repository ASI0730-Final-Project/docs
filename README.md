# <p align="center">Informe de Trabajo Final</p>

## <p align="center">Universidad Peruana de Ciencias Aplicadas</p>

<div align="center">
  <img src="./imgs/upc-logo.png" alt="Logo de UPC" />
</div>

<p align="center">Ingeniería de Software</p>
<p align="center">Aplicaciones Web - 4371</p>
<p align="center"><strong>Docente:</strong> Naldo Reupo-Musayon Gastulo</p>
<p align="center"><strong>Startup:</strong> GigU</p>
<p align="center"><strong>Producto:</strong> GigU</p>

<p align="center"><strong>Team members:</strong></p>

| Nombre                            | Código     |
| --------------------------------- | ---------- |
|  Allcca Guerrero, Irving          | U202213241 |
| Solis Santa Cruz,Giancarlo Rafael | U202318615 |
| Bryan Felix Martinez Ramos        | u202316246 |
| Oblitas Davila, Mariano Moises    | U202310222 |
| Cacho Seminario, Diego Alonso     | U202223990 |
| Seijas Vásquez, Diego Antonio     | U202210167 |
| Yauri Chocce, Renato              | U202317566 |

<p align="center"><strong>Ciclo 2025-01</strong></p>

# Registro de versiones del informe

| Versión | Fecha      | Autor             | Descripción de modificación                                                                                                                                                                                                                                                                                       |
| ------- | ---------- | ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TB2     | 20/06/2025 | GigU | En esta primera entrega se han incluido los capítulos:<br />Capítulo I: Introducción <br />Capítulo II: Requirements Elicitation & Analysis<br />Capítulo III: Requirements Specification<br />Capítulo IV: Product Design<br />Capítulo V: Product Implementation, Validation & Deployment                       |

# Student Outcomes

ABET – EAC - Student Outcome 5: La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.

| Criterio específico | Acciones realizadas | Conclusiones |
| ----- | ----- | ----- |
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | **\<br/\>\<br/\>Liderazgo distribuido TB2:**\- Irving (U202213241) lideró mejoras en lógica y estética del Frontend.- Mariano (U202310222) impulsó el desarrollo base del Backend y coordinó entrevistas de validación.- Diego Seijas (U202210167) lideró la implementación del dominio Pull y la grabación del video.- Diego Cacho (U202223990) lideró el dominio Chat y evaluación de la interfaz. **\<br/\>\<br/\>Coordinación general:**\- Se mantuvieron reuniones frecuentes para seguimiento.- Roles técnicos asignados por dominio (Users, Chat, Gigs, Portfolio, Pull).- Documentación y planificación continua vía GitHub y Discord. | La estrategia de liderazgo compartido continuó siendo efectiva. Cada miembro asumió un rol activo según su dominio técnico, promoviendo autonomía. Se observó una mejora en la autogestión. Se recomienda incluir sesiones breves de retrospectiva al cierre de cada sprint. |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | **\<br/\>\<br/\>Metodología de trabajo en TB2:**\- Redistribución de tareas por dominio técnico.- Pair programming y colaboración en entrevistas.- Diseño y ejecución de entrevistas de validación.- Participación activa en el diseño y testeo del producto.**Aportes individuales destacados:**\- Giancarlo (U202318615) y Bryan (U202316246): diseño y avance en entrevistas.- Renato (U202317566): desarrollo del dominio Portfolio.- Diego Cacho: evaluación heurística y validación visual del Frontend. **\<br/\>\<br/\>Herramientas utilizadas:**\- GitHub, Discord, Figma, y herramientas de grabación de video. | Se fortaleció el entorno colaborativo a través de la división funcional por dominios. La planificación fue más técnica y precisa. La inclusión se mantuvo gracias al uso constante de herramientas de comunicación. A mejorar: seguimiento en tiempo real del progreso mediante herramientas visuales como Gantt o burndown charts. |

### Tabla de Contenidos

#### [Capítulo I: Introducción](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
  - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
  - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
  - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
  - [1.2.2 Lean UX Process](#122-lean-ux-process)
    - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
    - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

#### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
- [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
  - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
  - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
  - [2.3.1. User Personas](#231-user-personas)
  - [2.3.2. User Task Matrix](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
  - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

#### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

#### [Capítulo IV: Product Design](#capítulo-iv-product-design)
- [4.1. Style Guidelines](#41-style-guidelines)
  - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
  - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
  - [4.2.1. Organization Systems](#421-organization-systems)
  - [4.2.2. Labeling Systems](#422-labeling-systems)
  - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
  - [4.2.4. Searching Systems](#424-searching-systems)
  - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3.  UI Design](#43-landing-page-ui-design)
  - [4.3.1.  Wireframe](#431-landing-page-wireframe)
  - [4.3.2.  Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
  - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
  - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
  - [4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)
  - [4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
  - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
  - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
  - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
  - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
  - [4.8.1. Database Diagram](#481-database-diagram)

#### [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
- [5.1. Software Configuration Management](#51-software-configuration-management)
  - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
  - [5.1.2. Source Code Management](#512-source-code-management)
  - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
  - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. , Services & Applications Implementation](#52-landing-page-services--applications-implementation)
  - [5.2.1. Sprint 1](#521-sprint-1)
    - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
    - [5.2.1.2. Aspect Leaders and Collaboradores](#5212-aspect-leaders-and-collaboradores)
    - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
    - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
    - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
    - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
    - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
    - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
- [5.2.2. Sprint 2](#522-sprint-2)
  - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
  - [5.2.2.2. Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
  - [5.2.2.3. Sprint Backlog 2](#5223-sprint-backlog-2)
  - [5.2.2.4. Development Evidence for Sprint Review 2](#5224-development-evidence-for-sprint-review-2)
  - [5.2.2.5. Execution Evidence for Sprint Review 2](#5225-execution-evidence-for-sprint-review-2)
  - [5.2.2.6. Services Documentation Evidence for Sprint Review 2](#5226-services-documentation-evidence-for-sprint-review-2)
  - [5.2.2.7. Software Deployment Evidence for Sprint Review 2](#5227-software-deployment-evidence-for-sprint-review-2)
  - [5.2.2.8. Team Collaboration Insights during Sprint 2](#5228-team-collaboration-insights-during-sprint-2)
- [5.2.3. Sprint 3](#523-sprint-3)
  - [5.2.3.1. Sprint Planning 3](#5231-sprint-planning-3)
  - [5.2.3.2. Aspect Leaders and Collaborators](#5232-aspect-leaders-and-collaborators)
  - [5.2.3.3. Sprint Backlog 3](#5233-sprint-backlog-3)
  - [5.2.3.4. Development Evidence for Sprint Review 3](#5234-development-evidence-for-sprint-review-3)
  - [5.2.3.5. Execution Evidence for Sprint Review 3](#5235-execution-evidence-for-sprint-review-3)
  - [5.2.3.6. Services Documentation Evidence for Sprint Review 3](#5236-services-documentation-evidence-for-sprint-review-3)
  - [5.2.3.7. Software Deployment Evidence for Sprint Review 3](#5237-software-deployment-evidence-for-sprint-review-3)
  - [5.2.3.8. Team Collaboration Insights during Sprint 3](#5238-team-collaboration-insights-during-sprint-3)
- [5.3. Validation Interviews](#53-validation-interviews)
  - [5.3.1. Diseño de entrevistas](#531-diseño-de-entrevistas)
  - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
  - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
- [5.4. Video About-the-Product](#54-video-about-the-product)


# Capítulo I: Introducción

### **1.1. Startup Profile**

#### **1.1.1. Descripción de la Startup**

Somos GigU, un equipo de estudiantes de la Universidad Peruana de Ciencias Aplicadas comprometidos con la innovación tecnológica y la creación de oportunidades para nuestra comunidad universitaria.

Nuestra misión es ofrecer una plataforma que permita a los estudiantes universitarios ofrecer sus habilidades y conocimientos a través de servicios freelance, generando ingresos adicionales mientras desarrollan experiencia profesional en su campo.

Nuestra visión es convertirnos en la principal plataforma de trabajo freelance para estudiantes en Perú y Latinoamérica, facilitando la conexión entre talento joven y clientes que buscan soluciones creativas y eficientes en múltiples áreas como desarrollo de software, diseño, tutorías, gestión empresarial, entre otros.

Nuestro producto principal es GigU, una plataforma que conecta a estudiantes con clientes interesados en servicios freelance. Los freelancers pueden publicar sus servicios, definir tarifas y cotizar precios de manera inteligente con base en factores como el tiempo estimado de trabajo, la complejidad del servicio y las tarifas del mercado. La plataforma también proporciona comunicación con clientes y procesamiento seguro de pagos.

GigU no solo ayuda a los estudiantes a generar ingresos mientras estudian, sino que también les permite desarrollar habilidades clave como la gestión del tiempo, la negociación, la resolución de problemas y el trato con clientes reales, preparándose así para la vida profesional.

Además, con GigU, los estudiantes tienen una forma flexible, accesible y efectiva de adquirir experiencia laboral y construir una red de clientes y contactos profesionales desde el inicio de su carrera.


#### **1.1.2. Perfiles de integrantes del equipo**

**Tabla 1**  
*Perfil del integrante Mariano Moisés Oblitas Dávila*

| Nombre: Oblitas Dávila, Mariano Moisés  |  <img src="imgIntegrantes/Mariano.png" alt="Mariano" title="Foto de Mariano" width="320"/> |
| :---- | :---- |
| **Código:** U202310222 |  |
| **Carrera:** Ingeniería en software |  |
| **Habilidades:** Estudiante de 18 años de Ingeniería de Software en la UPC. Me caracterizo por mi creatividad, eficacia y capacidad para resolver problemas de manera racional. Apasionado por la programación y el desarrollo de software, busco constantemente innovar y aprender nuevas tecnologías. |  || Nombre: Cacho Seminario, Diego Alonso |   |

| Nombre: Martinez Ramos,Bryan Felix  |  <img src="imgIntegrantes/Foto proyecto.jpg" alt="Bryan" title="Foto de Bryan" /> |
| :---- | :---- |
| **Código:** U202316246 |  |
| **Carrera:** Ingeniería en software |  |
| **Habilidades:** Soy estudiante de la carrera de ingeniería de software de la universidad Peruana de ciencias aplicadas, soy una persona comprometida y responsable, priorizo mucho mis responsabilidades y siempre trato de cumplir mis trabajos en los tiempos establecidos, tengo experiencia en lenguajes de programación como C++ Python y conocimientos muy básicos en solidity que pienso consolidarlos en el futuro proyecto, tengo habilidades en algunos lenguajes de programación como C + +,python y un poco de html. |  |

| Nombre: Cacho Seminario, Diego Alonso  | <img src="imgIntegrantes/DiegoC.png" alt="DiegoC" title="Foto de Diego Cacho" /> |
| :---- | :---- |
| **Código:** U202223990 |  |
| **Carrera:** Ingeniería de Software |  |
| **Habilidades:** Soy estudiante de Ingeniería de Software cursando el 6to ciclo de mi carrera en la UPC y tengo 20 años. Me considero una persona tranquila y diligente, intentó realizar mis tareas y trabajos lo antes posible para evitar contratiempos en un futuro, especialmente si son actividades que consumen mucho tiempo. Como miembro de equipo buscaré ayudar a mis compañeros cuando lo necesiten, realizando además mis entregas lo más temprano posible. Habilidades en C++, C\#, Python, Unity 2D/3D, html/css/js. |  |

| Nombre: Solis Santa Cruz,Giancarlo Rafael                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | <img src="imgIntegrantes/Giancarlo.jpg" alt="Giancarlo" title="Foto de Giancarlo" /> |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------- |
| **Código:** U202318615                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                                                                                      |
| **Carrera:** Ingeniería de Software                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                                                                      |
| **Habilidades:** Soy estudiante de Ingeniería de Software cursando el 5to ciclo de mi carrera en la UPC y tengo 22 años. Soy una persona proactiva e intuitiva. Me gusta abordar mis tareas de manera eficiente, completándolas con anticipación para evitar problemas futuros, especialmente cuando se trata de proyectos largos o complejos. En equipo, me esfuerzo por colaborar y apoyar a mis compañeros en todo lo que pueda, asegurándome de cumplir con mis entregas a tiempo o incluso antes. Tengo experiencia en programación con C + +, Java, Python, así como en el diseño web con html, CSS y JavaScript. |                                                                                      |
| Nombre: Diego Seijas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | <img src="imgIntegrantes/Diego.jpg" alt="Giancarlo" title="Foto de Diego" />         |
| **Código:** U202210167                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |                                                                                      |
| **Carrera:** Ingeniería de Software                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                                                                      |
| **Habilidades:** Soy estudiante de Ingeniería de Software cursando el 7to ciclo de mi carrera en la UPC y tengo 20 años. Soy una persona proactiva. Me gusta abordar mis tareas de manera eficiente,  especialmente cuando se trata de proyectos largos o complejos. En equipo, me esfuerzo por colaborar y apoyar a mis compañeros en todo lo que pueda. Tengo experiencia en programación con C + +, Java, Python, así como en el diseño web con html, CSS y JavaScript.                                                                                                                                              |                                                                                      |
| Nombre: Irving Allcca                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | <img src="imgIntegrantes/irving.jpg" alt="Irving" title="Foto de Irving" />         |
| **Código:** U202213241                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                                                                                      |
| **Carrera:** Ingeniería de Software                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                                                                      |
| **Habilidades:** Soy estudiante de Ingeniería de Software cursando el 5to ciclo de mi carrera en la UPC y tengo 20 años. Soy una persona empática e intuitiva. Me gusta desarrollar los proyectos de manera secuencial y eficiente. En equipo, me esfuerzo por colaborar. Tengo experiencia en programación con C + +, Java, Python, así como en el diseño web con html, CSS y JavaScript.                                                                                |                                                                                      |
| Nombre: Renato Yauri Chocce                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | <img src="imgIntegrantes/renato.jpg" alt="Renato" title="Foto de Renato" />         |
| **Código:** U202317566                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                                                                                      |
| **Carrera:** Ingeniería de Software                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |                                                                                      |
| **Habilidades:** Soy estudiante de Ingeniería de Software cursando el 5to ciclo de mi carrera en la UPC y tengo 21 años. Soy una persona amable y tranquila. Me gusta desarrollar los proyectos de manera minuciosa. En equipo, me esfuerzo por colaborar. Tengo experiencia con C++, Java, JavaScript, html y CSS.                                                                                                                                                     |                                                                                      |

### **1.2. Solution Profile** 

#### **1.2.1. Antecedentes y Problemática**

##### **¿Cuál es el problema?**  
Muchos estudiantes universitarios enfrentan serias dificultades para generar ingresos y adquirir experiencia profesional mientras cursan sus estudios. Esta carencia de oportunidades laborales adecuadas no solo limita su independencia económica, sino también el desarrollo temprano de habilidades prácticas y su inserción competitiva en el mercado laboral. Según datos del Ministerio de Educación del Perú (2020), aproximadamente el 20% de los estudiantes universitarios de entre 17 y 21 años combina estudios y trabajo de manera simultánea, reflejando que una parte importante de la población estudiantil se ve obligada a buscar ingresos mientras completa su formación. Sin embargo, a pesar de contar con talentos y conocimientos valiosos, la mayoría no dispone de una plataforma accesible, segura y adaptada que les permita ofrecer sus servicios de forma organizada y profesional, especialmente bajo la modalidad freelance.

##### **¿Cuándo ocurre el problema?**  
El problema se presenta a lo largo de toda la etapa universitaria, con mayor énfasis a partir del segundo o tercer año de carrera, cuando los estudiantes ya han adquirido capacidades técnicas, académicas o creativas que podrían ser aplicadas en el ámbito laboral. La necesidad de generar ingresos se intensifica en periodos críticos como matrículas, proyectos finales o gastos personales, momentos en los que la presión financiera se convierte en un factor determinante para su permanencia y rendimiento académico.

##### **¿Dónde ocurre el problema?**  
Esta problemática es evidente en el contexto universitario peruano y latinoamericano, especialmente en instituciones donde las políticas de empleabilidad son limitadas o inexistentes, y donde los programas de prácticas preprofesionales o los vínculos con el mercado freelance son insuficientes o inaccesibles. Asimismo, en el entorno digital persiste la falta de una plataforma centralizada y especializada que facilite a los estudiantes la oferta de servicios freelance de manera organizada, validada y segura.

##### **¿A quién afecta el problema?**  
El problema impacta directamente a estudiantes universitarios que buscan generar ingresos, adquirir experiencia laboral temprana y construir un portafolio real antes de egresar. Esta situación también afecta a microempresas, emprendedores y particulares que requieren servicios profesionales accesibles, confiables y de calidad, y que a menudo no logran encontrar talento joven disponible y verificado en su entorno inmediato.

##### **¿Por qué sucede el problema?**  
El problema radica en la falta de plataformas diseñadas específicamente para conectar estudiantes con clientes potenciales, considerando sus limitaciones de tiempo, experiencia y recursos. Las plataformas freelance tradicionales imponen barreras de entrada significativas, como comisiones elevadas, competencia global desproporcionada y escasa validación académica de perfiles, lo que desalienta la participación de estudiantes y perpetúa su informalidad laboral.

##### **¿Cómo sucede el problema?**  
En ausencia de alternativas formales y especializadas, los estudiantes optan por ofrecer sus servicios a través de redes sociales, contactos personales o plataformas genéricas que no garantizan seguridad, visibilidad ni condiciones laborales justas. Esta informalidad expone a los estudiantes a malas prácticas, incumplimientos de pago, sobreexplotación de tiempo y escaso reconocimiento de sus capacidades, lo que frecuentemente deriva en frustración, desmotivación y experiencias laborales negativas.

##### **¿Cuán grande es el impacto de este problema?**  
El impacto es considerable tanto en el plano individual como en el social. En el Perú, el 85.3% de jóvenes menores de 25 años trabaja en condiciones de informalidad, lo que evidencia una fuerte precarización del empleo juvenil y una limitada protección social (INEI, 2023). Además, la tasa de desempleo en jóvenes de 14 a 24 años alcanza el 10.1%, superando al promedio nacional y posicionando a este grupo como uno de los más vulnerables del mercado laboral (INEI, 2023). Esta realidad afecta directamente su desarrollo personal y profesional, retrasa su independencia económica y limita su proyección laboral futura.

##### 

##### 

#### **1.2.2. Lean UX Process**

##### **1.2.2.1. Lean UX Problem Statements**

En el contexto universitario peruano, los estudiantes enfrentan grandes desafíos para insertarse en el mercado laboral mientras cursan sus estudios. La mayoría se enfrenta a condiciones de informalidad o desempleo, lo cual limita su desarrollo profesional desde una etapa temprana.  
 Hemos observado que no existen plataformas efectivas y especializadas que conectan directamente a estudiantes universitarios con oportunidades laborales formales, flexibles y alineadas a sus carreras, lo cual perpetúa la falta de experiencia profesional al egresar.  
 ¿Cómo podemos ayudar a los estudiantes universitarios en el Perú a insertarse en el mercado laboral de forma formal, flexible y segura durante su etapa académica, permitiéndoles desarrollar habilidades prácticas, generar ingresos y mejorar su empleabilidad desde los primeros ciclos?
 
 ##### **1.2.2.2. Lean UX Assumptions**

¿Quién es el usuario?  
 Estudiantes universitarios peruanos, principalmente entre los 17 y 24 años, que buscan generar ingresos y experiencia profesional compatible con sus horarios académicos.

¿Dónde encaja nuestro producto en su vida?  
ConnectED se integra como una herramienta esencial para complementar su formación académica con experiencia laboral real, generar ingresos, y conectarse con profesionales, clientes o mentores, sin sacrificar su rendimiento académico.

¿Qué problemas tiene nuestro producto y cómo se pueden resolver?

* Posible desconfianza hacia la formalidad de las oportunidades.  
   → Solución: verificación de empleadores/clientes y contratos inteligentes.

* Dificultad para encontrar tareas relacionadas a su carrera.  
   → Solución: sistema de categorización inteligente por carreras y habilidades.

* Baja retención o uso esporádico.  
   → Solución: gamificación, badges y recompensas por participación activa.

¿Cómo y cuándo es usado nuestro producto?  
El producto es usado principalmente durante los tiempos libres o entre clases. Los estudiantes lo utilizan para buscar encargos, postular a proyectos freelance, recibir feedback, y conectarse con mentores o empresas pequeñas que necesitan apoyo técnico o creativo.

¿Qué características son importantes?

* Perfiles profesionales con historial académico y de proyectos.

* Oportunidades freelance o part-time verificadas.

* Inteligencia artificial para emparejar tareas con habilidades.

* Retroalimentación entre estudiantes y clientes.

* Panel de seguimiento de experiencia acumulada.

* Integración con LinkedIn y portafolios.

* Sistema de reputación y badges.

* Chat seguro entre clientes y postulantes.

* Acceso a micro cursos gratuitos recomendados según proyectos.

¿Cómo debe verse nuestro producto y cómo comportarse?  
 Debe tener un diseño moderno, amigable y responsivo. Su comportamiento debe ser fluido, con tiempos de carga bajos y navegación clara. La experiencia de usuario debe motivar la interacción constante, con notificaciones relevantes y recomendaciones que generen valor real para el usuario.

##### **1.2.2.2. Lean UX Assumptions**

¿Quién es el usuario?  
 Estudiantes universitarios peruanos, principalmente entre los 17 y 24 años, que buscan generar ingresos y experiencia profesional compatible con sus horarios académicos.

¿Dónde encaja nuestro producto en su vida?  
ConnectED se integra como una herramienta esencial para complementar su formación académica con experiencia laboral real, generar ingresos, y conectarse con profesionales, clientes o mentores, sin sacrificar su rendimiento académico.

¿Qué problemas tiene nuestro producto y cómo se pueden resolver?

* Posible desconfianza hacia la formalidad de las oportunidades.  
   → Solución: verificación de empleadores/clientes y contratos inteligentes.

* Dificultad para encontrar tareas relacionadas a su carrera.  
   → Solución: sistema de categorización inteligente por carreras y habilidades.

* Baja retención o uso esporádico.  
   → Solución: gamificación, badges y recompensas por participación activa.

¿Cómo y cuándo es usado nuestro producto?  
El producto es usado principalmente durante los tiempos libres o entre clases. Los estudiantes lo utilizan para buscar encargos, postular a proyectos freelance, recibir feedback, y conectarse con mentores o empresas pequeñas que necesitan apoyo técnico o creativo.

¿Qué características son importantes?

* Perfiles profesionales con historial académico y de proyectos.

* Oportunidades freelance o part-time verificadas.

* Inteligencia artificial para emparejar tareas con habilidades.

* Retroalimentación entre estudiantes y clientes.

* Panel de seguimiento de experiencia acumulada.

* Integración con LinkedIn y portafolios.

* Sistema de reputación y badges.

* Chat seguro entre clientes y postulantes.

* Acceso a micro cursos gratuitos recomendados según proyectos.

¿Cómo debe verse nuestro producto y cómo comportarse?  
 Debe tener un diseño moderno, amigable y responsivo. Su comportamiento debe ser fluido, con tiempos de carga bajos y navegación clara. La experiencia de usuario debe motivar la interacción constante, con notificaciones relevantes y recomendaciones que generen valor real para el usuario.

##### **1.2.2.3. Lean UX Hypothesis Statements**

* Creemos que al conectar estudiantes universitarios con oportunidades laborales compatibles con sus carreras y horarios, lograremos que desarrollen experiencia profesional antes de egresar.  
   Sabremos que hemos tenido éxito cuando más del 50% de los usuarios activos complete al menos una tarea remunerada en su primer mes.

* Creemos que implementar un sistema de reputación y gamificación aumentará la participación y compromiso con la plataforma.  
   Sabremos que hemos tenido éxito cuando el tiempo promedio de uso semanal supere los 45 minutos por usuario activo.

* Creemos que ofrecer oportunidades relacionadas a sus habilidades y carrera aumentará su satisfacción y fidelización.  
   Sabremos que hemos tenido éxito cuando al menos el 70% de los usuarios califique la relevancia de las recomendaciones como “alta” o “muy alta”.

##### **1.2.2.4. Lean UX Canvas**

<img src="imgs/LeanUX_canvas_Freelance.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

#### 

#### **1.3. Segmentos Objetivo**

- ##### **Estudiantes Universitarios Freelancers**

Estudiantes de cualquier ciclo universitario que buscan ofrecer sus servicios de manera independiente para adquirir experiencia laboral, generar ingresos y construir una red de clientes. Estos estudiantes pueden pertenecer a diversas especialidades como diseño gráfico, programación, marketing digital, redacción, tutorías académicas, entre otros.

Características:

* Buscan oportunidades de trabajo flexible que les permitan combinar sus estudios con el trabajo freelance.

* Necesitan herramientas que los ayuden a promocionar sus habilidades y construir una cartera de clientes.

* Valoran la facilidad de pago y la seguridad en la gestión de contratos.

- ##### **Personas y Emprendimientos  que buscan contratar servicios freelance**

Individuos o empresas que requieren servicios especializados sin la necesidad de contratar empleados a tiempo completo. Esto incluye emprendedores, startups, pequeñas empresas y particulares que buscan soluciones rápidas y accesibles para sus proyectos.

Características:

* Buscan talento accesible y de calidad para tareas específicas.

* Prefieren plataformas que garanticen la seguridad en la contratación y el cumplimiento del trabajo.

* Valoran las recomendaciones y validaciones de otros clientes para elegir freelancers confiables.
  
# Capítulo II: Requirements Elicitation & Analysis

### **2.1. Competidores**

Los competidores que hemos identificado para GigU son las plataformas freelancer, aunque no existen plataformas que estén 100% enfocadas en estudiantes como lo realiza GigU, si presenta productos con mucha similaridad lo que genera una competencia directa.

#### **2.1.1 Análisis Competitivo**

<img src="imgs/Competidores1.png" alt="Competidores1" title="Competidores1"/>

<img src="imgs/Competidores2.png" alt="Competidores2" title="Competidores2"/>

<img src="imgs/Competidores3.png" alt="Competidores3" title="Competidores3"/>

<img src="imgs/Competidores4.png" alt="Competidores4" title="Competidores4"/>

<img src="imgs/Competidores5.png" alt="Competidores5" title="Competidores5"/>

<img src="imgs/Competidores6.png" alt="Competidores6" title="Competidores6"/>

#### **2.1.2 Estrategias y tácticas frente a competidores**

GigU aplicará una estrategia de diferenciación enfocada en el talento universitario, destacando por su enfoque educativo, precios accesibles y alianzas con instituciones académicas. Frente a los grandes competidores del mercado freelance, GigU se posiciona como una alternativa confiable y de propósito social, conectando clientes con estudiantes verificados. Su valor está en ofrecer soluciones personalizadas, soporte en español y una experiencia centrada en el desarrollo profesional de los jóvenes. Aprovechará las debilidades de otras plataformas como su falta de personalización o enfoque regional, mientras mitiga amenazas como la falta de experiencia estudiantil con garantías y filtros de calidad

### **2.2. Entrevistas**

### **2.2.1 Diseño de entrevistas**

**Segmento objetivo: Estudiantes Universitarios Freelancers**

¿Cual es tu nombre completo?

¿Cual es tu edad?

¿En donde vives?

¿Has ofrecido tus servicios como freelancer alguna vez? ¿En qué área?

¿Qué te motivó a ofrecer tus servicios de manera independiente?

¿Dónde sueles buscar oportunidades freelance (redes, plataformas, conocidos, etc.)?

¿Qué dificultades has encontrado al intentar conseguir clientes como estudiante?


¿Qué características debería tener una plataforma ideal para ayudarte a encontrar clientes?

¿Qué métodos usas actualmente para cobrar tus servicios? ¿Has tenido problemas con eso?

¿Cuánto tiempo a la semana podrías dedicarle a trabajos freelance?

¿Crees que sería útil tener una app que te sugiera proyectos freelance según tu perfil y habilidades?

¿Qué tan importante es para ti tener una forma segura y automática de cobrar por tu trabajo freelance?

**Segmento objetivo: Personas y Emprendimientos que buscan contratar servicios freelance** 

¿Cual es tu nombre completo?

¿Cual es tu edad?

¿En donde vives?

¿Alguna vez has contratado a un freelancer para un proyecto? ¿Cómo fue tu experiencia?

¿Qué tipo de tareas sueles tercerizar o te gustaría tercerizar?

¿Qué canales usas actualmente para encontrar freelancers (plataformas, conocidos, redes)?

¿Qué te haría confiar en un estudiante universitario como freelancer?

¿Qué tan importante es para ti poder ver recomendaciones o validaciones de otros clientes?

¿Te gustaría una plataforma que se encargue de gestionar los pagos y acuerdos con el freelancer, o prefieres hacerlo tú directamente con la persona? 

¿Qué haría que descartes a un freelancer incluso si su precio es atractivo?

¿Qué funcionalidades te gustaría ver en una plataforma para contratar freelancers?

¿Qué tan importante es para ti poder negociar el precio antes de contratar un servicio freelance? ¿Preferirías un precio fijo o la opción de llegar a un acuerdo con el freelancer?

¿Qué factores tomas en cuenta al elegir a un freelancer: precio, portafolio, tiempo de entrega, reputación, otro? ¿Cuál de ellos pesa más para ti al decidir?


### **2.2.2 Registro de Entrevistas**

<b><u>Segmento objetivo #1: Estudiantes Universitarios Freelancers</u></b>

Entrevistado N°1: Bruno Sebastián Gamarra Torres

<img src="imgs/Entrevista_Bruno.jpeg" alt="Entrevista_Bruno" title="Entrevista_bruno"/>

* Sexo: Masculino 
* Edad: 23 
* Ubicación en la que vive: Surco 

Acerca de la entrevista:
 
* Instante en el que inicia: 0:03 minutos
* Duración: 3:44

Resumen:

Bruno Sebastián Gamarra Torres, un joven de 23 años que vive en Surco, ofrece servicios de diseño gráfico y edición de video como freelancer desde hace algunos meses, motivado por la necesidad económica y el deseo de ganar experiencia. Consigue clientes principalmente a través de redes sociales como Instagram y TikTok, pero enfrenta dificultades como la falta de confianza de algunos clientes por ser estudiante. Utiliza Yape, Plin y transferencias para cobrar, aunque a veces sufre retrasos en los pagos. Para él, una plataforma ideal debería permitir dejar reseñas reales, tener chat integrado y un sistema de contratos. 

Entrevistado N°2:Werner Lang

<img src="imgs/entrevista2-segmento1.png" alt="" title=""/>

Sexo:Masculino

Edad:20

Ubicación en la que vive:San Isidro

Acerca de la entrevista:

Instante en el que inicia: 3:45 minutos

Duración: 9:57 minutos

Resumen:
Para Werner, ofrecer servicios como freelancer en diseño gráfico y desarrollo web le ha permitido aplicar lo aprendido en la universidad mientras genera ingresos extra. Su motivación principal es ganar experiencia profesional antes de egresar, trabajando en proyectos reales para pequeños negocios.
Aunque ha logrado conseguir clientes a través de conocidos, grupos en redes sociales y plataformas como Workana, considera difícil que lo tomen en serio por ser estudiante. Además, la falta de un portafolio sólido y la poca experiencia en negociaciones le han representado retos al momento de cerrar acuerdos.
Actualmente cobra sus servicios mediante Yape o transferencias bancarias, aunque ha tenido problemas con demoras en los pagos o clientes que buscan renegociar. Puede dedicar entre 8 y 12 horas semanales al trabajo freelance, dependiendo de su carga académica.
Werner considera que una plataforma ideal debería facilitar mostrar habilidades, contar con herramientas para cotizar servicios, asegurar pagos y permitir una comunicación fluida con los clientes. También valora que una app como GigU pueda sugerirle proyectos alineados con su perfil, lo que le ayudaría a aprovechar mejor su tiempo y aumentar su productividad.
 

Entrevistado N°3: Mario André Cacho Seminario

<img src="imgs/Entrevista_Mario.png" alt="Entrevista_Mario" title="Entrevista_mario"/>

* Sexo: Masculino  
* Edad: 21  
* Ubicación en la que vive: Surco

Acerca de la entrevista:

* Instante en el que inicia: 9:57 minutos  
* Duración: 13:10 minutos

Resumen:

Para Mario, ofrecer servicios como freelancer en la creación de videos de marketing para pequeñas empresas le ha permitido impulsar su desarrollo personal y profesional. Le motiva expandir su perspectiva trabajando con distintos tipos de negocios. Sin embargo, encuentra complicado conseguir clientes, ya que considera que ser estudiante limita su contratación por parte de empresas que priorizan la experiencia. Por lo general, encuentra oportunidades a través de redes sociales o contactos cercanos, y recibe sus pagos mediante transferencias bancarias directas. Dedica entre 6 y 8 horas semanales al trabajo freelance, equilibrándolo con sus estudios. Cree que una plataforma ideal debería permitir visibilidad a personas de todos los niveles (estudiantes, aficionados, profesionales) y contar con un sistema que sugiera proyectos según habilidades y experiencia. También valora que exista un historial de trabajos realizados y, sobre todo, un sistema de cobros seguro que proteja su esfuerzo.


<b><u>Segmento objetivo #2: Personas y Emprendimientos que buscan contratar servicios freelance</u></b>
 

Entrevistada N°1: Yulia Estephania Martinez Martinez


<img src="imgs/Entrevista_Yulia.PNG" alt="Entrevista_Yulia" title="Entrevista_Yulia"/>

<img src="imgs/Entrevista_Yulia2.PNG" alt="Cuack cuadros cuenta instagram" title="Entrevista_Yulia"/>


* Sexo: Femenino  
* Edad: 19  
* Ubicación en la que vive: Surco

Acerca de la entrevista:

* Instante en el que inicia: 17:45 minutos
* Duración: 25:30 minutos

Resumen::  
Yulia tiene un emprendimiento llamado *Quack\_cuadros*, donde realiza cuadros personalizados al gusto del cliente.  
No ha contratado freelancers aún, pero está interesada en tercerizar tareas como *marketing digital*, especialmente *reels* para redes sociales, y *diseño web*.

Canales actuales para buscar freelancers:  
Usa principalmente Instagram y contactos personales, aunque reconoce que puede no ser totalmente confiable.

Criterios para confiar en un freelancer:

* Para trabajos creativos: portafolio visual.

* Para otros trabajos: currículum vitae.

* Valora recomendaciones y validaciones de otros clientes.

Prefiere que la plataforma gestione pagos y acuerdos, ya que no se le da bien la negociación ni el manejo monetario.

Motivos para descartar a un freelancer:

* Mala calidad de trabajo.

* Falta de responsabilidad.

* Poca puntualidad en entregas.

Características deseadas en una plataforma freelance:

* Perfiles detallados de los freelancers.

* Herramientas de negociación de precios.

* Opciones para reuniones dentro de la plataforma (sin necesidad de apps externas).

* Chats y acuerdos formales.

Prefiere negociar dentro de un rango, ya que no tiene claridad sobre cuánto valen ciertos trabajos y confía en el criterio del freelancer para establecer precios razonables.

Factores de decisión:  
El portafolio es el factor más determinante, seguido del precio. Un trabajo que la impacte positivamente la hace más flexible al pagar.  

Entrevistado N°2: Fabrizio Morales

<img src="imgs/entrevista3-segmento2.png" alt="Entrevista_Fabrizio" title="Entrevista_Fabrizio"/>

* Sexo: Masculino  
* Edad: 22  
* Ubicación en la que vive: Molina  

**Acerca de la entrevista:**

* Instante en el que inicia: 25:32 minutos
* Duración 31:17 minutos  

## Resumen
Fabrizio Morales es un joven emprendedor que dirige un negocio de venta de vapes. Actualmente contrata freelancers para apoyar en tareas de marketing y ventas, principalmente a través de redes sociales como Facebook y LinkedIn.

## Canales actuales para buscar freelancers
- Utiliza principalmente **Facebook** y **LinkedIn**.
- También recurre a recomendaciones de su círculo cercano.

## Criterios para confiar en un freelancer
- **Trabajos creativos**: Prioriza portafolio visual o ejemplos previos.
- **Otros tipos de tareas**: Revisa el currículum vitae (CV).
- Valora recomendaciones o testimonios de antiguos clientes.
- Prefiere que haya una plataforma que gestione pagos y acuerdos para evitar negociaciones directas.

## Motivos para descartar a un freelancer
- Calidad de trabajo deficiente.
- Falta de responsabilidad.
- Retrasos en las entregas.

## Características deseadas en una plataforma freelance
- Perfiles completos y detallados de freelancers.
- Herramientas de negociación de precios.
- Opciones para realizar reuniones dentro de la plataforma (sin usar apps externas).
- Chats formales con acuerdos visibles.

## Factores de decisión
- El **portafolio visual** es el factor más determinante.
- Si un trabajo lo impacta positivamente, es flexible para pagar un precio mayor al inicialmente previsto.



Link de entrevista https://upcedupe-my.sharepoint.com/personal/u202213241_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202213241%5Fupc%5Fedu%5Fpe%2FDocuments%2FTB1%20web%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E4ae92057%2De207%2D4244%2D981f%2D491f492ea6b5 

#### **2.2.3 Análisis de entrevistas** 

El Segmento 1: Estudiantes Universitarios Freelancers muestra jóvenes motivados principalmente por la necesidad de ganar experiencia y generar ingresos adicionales mientras estudian. Bruno, Werner y Mario coinciden en que conseguir clientes es complicado debido a la falta de confianza de los empleadores hacia estudiantes y a la necesidad de contar con un portafolio sólido. Utilizan redes sociales y plataformas como Workana para buscar oportunidades, y prefieren métodos de pago sencillos como Yape y transferencias, aunque han enfrentado problemas de demoras en pagos. Para ellos, una plataforma ideal debería facilitar contratos, reseñas reales, chats integrados y sugerencias de proyectos alineados a sus habilidades, además de asegurar los pagos. Valoran la visibilidad de su talento más allá de la experiencia previa, dándoles la oportunidad de competir en el mercado freelance.

En el Segmento 2: Personas y Emprendimientos que buscan contratar freelancers, encontramos a Janet, Yulia y Fabrizio, quienes buscan apoyo externo principalmente para tareas de marketing, diseño y ventas. Sus principales preocupaciones son la calidad del trabajo, la responsabilidad del freelancer y la facilidad para gestionar pagos y acuerdos. Prefieren plataformas que ofrezcan perfiles detallados, portafolios visibles, comentarios de otros clientes y herramientas de negociación claras. Aunque Janet tiene más experiencia y prefiere manejar directamente los pagos, Yulia y Fabrizio valoran que la plataforma gestione los acuerdos para evitar problemas. En todos los casos, el portafolio visual y las buenas referencias son los factores decisivos para la contratación, y están dispuestos a pagar más si el resultado los impacta positivamente.

### **2.3. NeedFinding** 

#### **2.3.1 User Persona** 

User Persona del Usuario estudiante Freelancer

<img src="imgs/UserPersona1.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

User Persona del Usuario Persona o emprendimiento

<img src="imgs/UserPersona2.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

#### **2.3.2 User Task Matrix**

En esta se presenta el user task matrix, herramienta centrada en los segmentos objetivos que nos permitirá identificar las tareas y objetivos claves de los usuarios.

| USER TASK  | Julio Bernal |  | Luisa Fuentes |  |
| :---- | ----- | :---- | ----- | :---- |
|  | Frequency | Importance | Frequency | Importance |
| Publicar servicios y mostrar habilidades | Often | High | Sometimes | High |
| Cotizar precios fácilmente según tipo de trabajo | Sometimes | High | Often | High |
| Encontrar oportunidades mediante una app centralizada | Sometimes | High | Often  | Medium |
| Procesar pagos seguros a través de la plataforma | Always  | High | Always | High |
| Mostrar historial de trabajos realizados | Sometimes | Medium | Often | Medium |
| Negociar precios dentro de un rango flexible | Sometimes | Medium | Always | High |
| Establecer acuerdos y comunicación en la plataforma | Often | High | Always | High |

#### **2.3.3 User Journey Mapping**

User Journey estudiante freelance

<img src="imgs/JourneyMapping1.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>


User Journey persona o empresa:

<img src="imgs/JourneyMapping2.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>


#### **2.3.4 Empathy Mapping**

En esta sección se presenta el Empathy Mapping, herramienta para crear un perfil detallado de los user personas y desarrollar una comprensión profunda de su perspectiva y experiencia. Para cada user persona, se incluyen cinco elementos clave: lo que el usuario ve, lo que el usuario escucha, lo que el usuario dice, lo que el usuario hace y lo que el usuario siente. Además, se incluyen los pains y gains identificados en base a las preguntas: ¿Qué le preocupa?

Empathy mapping de estudiante freelance:

<img src="imgs/Empathymap1.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

Empathy mapping de persona o empresa:

<img src="imgs/Empathymap2.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

#### **2.3.5 AS-IS Mapping**

Se realizaron los siguientes cuadros en la herramienta Miro, el link original puede ser observado aquí: 

[LINK AS-IS](https://miro.com/welcomeonboard/SHJEektJMkxMZFNycTN4eVVtVUJ4a0d5VTk2amQ5dGJLWS9UTGU3Nm10aDQ1SmlCUkI2ZjYwZm93NS9nVGo3K1lLdU1EVmV4blFVK0prZHQ5VjRyR1gxNXJHS2xQcGJUQW1JS1Z3eW9pQVZHOUFLRXJNT2Z3OWU2SHJwT2ttOERBd044SHFHaVlWYWk0d3NxeHNmeG9BPT0hdjE=?share_link_id=926791313064)

As-Is Scenario Mapping para Estudiantes Universitarios Freelancers

<img src="imgs/AS-IS1.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

As-Is Scenario Mapping para Personas y Emprendimientos que buscan contratar servicios Freelance

<img src="imgs/AS-IS2.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

### **2.3. Ubiquitous Language.** 

* **Freelancer:** Estudiante que ofrece servicios a través de la plataforma.

* **Cliente:** Persona o emprendimiento que contrata servicios dentro de la plataforma.

* **Servicio:** Habilidad o trabajo ofrecido por un freelancer.

* **Perfil:** Información pública de un freelancer, incluyendo habilidades y experiencia.

* **Proyecto:** Trabajo definido que necesita ser realizado por un freelancer.

* **Solicitud de Proyecto:** Pedido que realiza un cliente para contratar un servicio.

* **Oferta:** Propuesta de precio y condiciones que un freelancer presenta para un proyecto.

* **Acuerdo:** Confirmación del cliente y freelancer sobre las condiciones de un proyecto.

* **Resumen de Servicio:** Descripción formal de lo que se entregará en un proyecto.

* **Entrega:** Resultado final que el freelancer entrega al cliente.

* **Estado del Proyecto:** Etapa actual de un proyecto (pendiente, en progreso, entregado, finalizado).

* **Calificación:** Puntuación que refleja la calidad del servicio entregado.

* **Comentario:** Reseña escrita sobre la experiencia de trabajo en un proyecto.

* **Historial:** Registro de proyectos completados por freelancers y clientes.

* **Notificación:** Mensaje generado por el sistema para informar sobre acciones relevantes.

* **Ámbito:** Categoría profesional que agrupa servicios similares.

* **Método de Pago:** Sistema mediante el cual se realiza la transacción económica.

* **Reputación:** Indicador basado en calificaciones y comentarios de proyectos finalizados.

* **Negociación:** Interacción en la que cliente y freelancer ajustan precio y condiciones.

* **Plataforma:** Espacio digital donde se conectan clientes y freelancers.

**

### **3.1. To-Be Scenario Mapping.** 

Se realizaron los siguientes cuadros en la herramienta Miro, el link original puede ser observado aquí: 

[LINK TO-BE](https://miro.com/app/board/uXjVIFvzuZo=/?share_link_id=785027992176)

* To-Be Scenario Mapping para Estudiantes Universitarios Freelancers
<img src="imgs/TO-BE1.png" alt="To-Be" title="To-BeScenarioMapping"/>

* To-Be Scenario Mapping para Personas y Emprendimientos que buscan contratar servicios Freelance

<img src="imgs/TO-BE2.png" alt="To-Be" title="To-BeScenarioMapping"/>

### **3.2. User Stories.** 


* EPICS

Las epics definidas para el proyecto GigU están orientadas a cubrir las necesidades principales tanto de los estudiantes de la UPC como de los usuarios que buscan contratar servicios freelance. Estas epics abordan funcionalidades esenciales para el funcionamiento de la plataforma, asegurando una experiencia fluida y efectiva desde la publicación de habilidades por parte de los estudiantes hasta la contratación por parte de clientes o emprendimientos. Desde la interfaz de la landing page, donde los usuarios conocen la propuesta de valor de GigU, hasta la gestión técnica del backend, frontend y servicios web, las epics actúan como una guía estructurada que facilita el desarrollo progresivo y coherente del sistema, alineándose con los objetivos académicos y de empleabilidad del proyecto.

| Epic / Story ID | Título | Descripción |
| :---: | ----- | ----- |
| EP01 | Navegación en Landing Page | Como visitante de GigU, deseo poder navegar de forma intuitiva por la landing page para conocer los beneficios de contratar o publicar servicios. |
| EP02 | Autenticación y Registro de Usuarios | Como usuario nuevo, deseo registrarme e iniciar sesión utilizando correo o redes sociales para acceder a mi cuenta de manera rápida y segura. |
| EP03 | Recuperación de Contraseña | Como usuario registrado, deseo recuperar mi contraseña fácilmente para poder acceder nuevamente en caso de olvidarla. |
| EP04 | Visualización de Servicios y Beneficios | Como visitante, deseo conocer los tipos de servicios disponibles y cómo funciona GigU para saber cómo puede ayudarme a contratar o ser contratado. |
| EP05 | Soporte y FAQ | Como visitante, deseo acceder a una sección de preguntas frecuentes y soporte para resolver mis dudas de forma autónoma y rápida. |
| EP06 | Gestión de Perfil Freelance | Como estudiante, deseo crear y editar mi perfil público con información, habilidades y precios para que posibles clientes conozcan mis servicios. |
| EP07 | Publicación y Edición de Servicios | Como estudiante, deseo publicar servicios personalizados con precios, plazos y descripciones claras para atraer clientes interesados. |
| EP08 | Búsqueda y Filtro de Freelancers | Como cliente, deseo buscar freelancers y filtrar por habilidades, precio o disponibilidad para encontrar al más adecuado para mi proyecto. |
| EP09 | Sistema de Contratación Directa | Como cliente, deseo contratar directamente a un freelancer desde su perfil para simplificar el proceso de contratación. |
| EP10 | Gestión de Proyectos y Solicitudes | Como freelancer, deseo gestionar las solicitudes recibidas y proyectos activos para poder organizar mejor mi trabajo y tiempos. |
| EP11 | Calificaciones y Opiniones | Como usuario, deseo dejar y ver calificaciones y comentarios sobre los freelancers para tomar decisiones más informadas. |
| EP12 | Sistema de Mensajería Interna | Como usuario, deseo comunicarme directamente dentro de la plataforma con el otro usuario para coordinar detalles antes o durante un proyecto. |
| EP13 | Cálculo Inteligente de Precio del Servicio | Como usuario, deseo que la plataforma sugiera un precio justo basado en la propuesta del freelancer, la oferta del cliente, el tipo y tamaño del servicio, y la experiencia del freelancer, para facilitar acuerdos equilibrados entre ambas partes. |

* User Stories

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
| :---: | ----- | ----- | ----- | :---: |
| US01 | Navegación Intuitiva en la Landing Page | Como visitante de GigU, deseo que la landing page tenga una barra de navegación clara y accesible para encontrar fácilmente las secciones importantes. | **Escenario 01:** Given que estoy en la landing page, When hago clic en el menú, Then debería ver opciones como “Inicio”, “Buscar Freelancer”, “Publicar Proyecto” y “Sobre Nosotros”. **Escenario 02:** Given que paso el cursor sobre un ítem, When el ítem está activo, Then debería resaltarse. | EP01 |
| US02 | Acceso rápido a funcionalidades clave | Como visitante, deseo acceder desde la landing page a secciones clave como “Publicar proyecto” o “Registrarse” para actuar rápidamente. | **Escenario 01:** Given que estoy en la landing, When hago scroll, Then debería ver botones CTA como “Empieza a contratar” o “Regístrate como freelancer”. **Escenario 02:** Given que estoy en la landing, When hago clic en un botón CTA como “Regístrate como freelancer”, Then debería ser redirigido al formulario de registro. | EP01 |
| US03 | Registro con Correo y Contraseña | Como nuevo usuario, deseo poder registrarme en la plataforma con mi correo y contraseña para acceder a las funcionalidades de GigU. | **Escenario 01:** Given que estoy en la sección de registro, When ingreso un correo válido y contraseña, Then debería registrarme correctamente. **Escenario 02:** Given que intento registrarme con datos inválidos, When presiono “Register”, Then debería recibir un mensaje de error. | EP02 |
| US04 | Iniciar sesión como Freelancer o Cliente | Como usuario registrado, deseo poder iniciar sesión para acceder a mi cuenta y funcionalidades específicas según mi rol. | **Escenario 01:** Given que tengo una cuenta, When ingreso mis credenciales, Then debería entrar como Freelancer o Cliente dependiendo del rol configurado. **Escenario 02**: Given que ingreso credenciales incorrectas, When presiono “Login”, Then debería recibir un mensaje de error indicando acceso denegado. | EP02 |
| US05 | Registro con redes sociales | Como visitante, deseo registrarme con Google para agilizar el proceso de creación de cuenta. | **Escenario 01:** Given que estoy en la vista de registro, When hago clic en “Registrarse con Google”, Then debería autenticarme y crear mi cuenta automáticamente. **Escenario 02**: Given que mi cuenta de Google ya está vinculada, When intento registrarme nuevamente con Google, Then debería mostrar un mensaje indicando que la cuenta ya existe. | EP02 |
| US06 | Solicitar recuperación de contraseña | Como usuario, deseo solicitar la recuperación de mi contraseña para volver a acceder si la olvido. | **Escenario 01:** Given que olvidé mi contraseña, When ingreso mi correo en la sección “Forgot your password”, Then debería recibir un correo con un enlace de recuperación. **Escenario 02**: Given que ingreso un correo no registrado, When presiono “Recuperar contraseña”, Then debería mostrar un mensaje indicando que el correo no existe en el sistema. | EP03 |
| US07 | Restablecer contraseña vía correo | Como usuario, deseo poder restablecer mi contraseña desde un enlace de recuperación enviado a mi correo. | **Escenario 01**: Given que he recibido el correo de recuperación, When hago clic en el enlace, Then debería poder establecer una nueva contraseña válida. **Escenario 02**: Given que ingreso una nueva contraseña que no cumple con los requisitos, When intento guardarla, Then debería mostrarse un mensaje de validación indicando el error. | EP03 |
| US08 | Conocer los beneficios de GigU | Como visitante, deseo conocer los beneficios de usar GigU para saber por qué debería usar esta plataforma. | **Escenario 01:** Given que estoy en la landing, When accedo a “About us”, Then debería ver beneficios como flexibilidad, soporte al talento joven y precios accesibles. **Escenario 02**: Given que veo los beneficios, When hago clic en uno de ellos, Then debería abrirse un pequeño resumen explicativo o una ventana emergente con más información. | EP04 |
| US09 | Diferencias entre roles (freelancer / cliente)	 | Como visitante, deseo saber las diferencias entre registrarme como freelancer o cliente para elegir el rol adecuado. | **Escenario 01**: Given que estoy revisando roles, When veo la sección de “Roles”, Then debería ver descripciones separadas y sus beneficios. **Escenario 02**: Given que estoy revisando la sección de roles, When hago click en “Freelancer” o “Customer”, Then debería desplegarse información adicional sobre el flujo de cada tipo de usuario. | EP04 |
| US10 | Experiencias de otros usuarios | Como visitante, deseo ver testimonios de usuarios anteriores para confiar en la plataforma. | **Escenario 01:** Given que estoy en la sección de experiencias, When visualizo un testimonio, Then debería ver nombre, rol y comentario del usuario. **Escenario 02**: Given que estoy en la sección de experiencias, When hago clic en “Ver más”, Then debería expandirse una lista con testimonios adicionales. | EP04 |
| US11 | Detalles sobre tipos de servicios | Como visitante, deseo conocer los tipos de servicios que puedo contratar o brindar en GigU. | **Escenario 01:** Given que accedo a la sección “Tipos de servicios”, When selecciono uno, Then debería ver una descripción detallada y ejemplos de ese servicio. **Escenario 02**: Given que estoy viendo la descripción de un tipo de servicio, When hago clic en “About This Gig”, Then debería ver casos prácticos de ese tipo de servicio realizado por otros freelancers. | EP04 |
| US12 | Acceso a Preguntas Frecuentes | Como visitante, deseo ver una sección de preguntas frecuentes para resolver mis dudas comunes sin ayuda externa. | **Escenario 01:** Given que estoy en la sección de ayuda, When hago clic en "FAQ", Then debería ver un listado de preguntas comunes con sus respuestas. **Escenario 02**: Given que veo el listado de preguntas, When hago clic en una respuesta, Then debería poder colapsar nuevamente la respuesta para limpiar la vista. | EP05 |
| US13 | Búsqueda dentro de Preguntas Frecuentes | Como usuario, deseo buscar palabras clave en la sección de FAQ para encontrar respuestas más rápido. | **Escenario 01:** Given que estoy en la sección FAQ, When ingreso una palabra en el buscador, Then debería mostrar solo las preguntas relacionadas. **Escenario 02**: Given que la búsqueda no devuelve resultados, When ingreso un término no encontrado, Then debería mostrarse un mensaje que diga “Didn’t found results”. | EP05 |
| US14 | Envío de Ticket de Soporte | Como usuario, deseo enviar un mensaje de soporte si no encuentro mi duda en la FAQ para recibir asistencia personalizada. | **Escenario 01:** Given que no encontré mi respuesta en FAQ, When hago clic en “Send Ticket”, Then debería poder completar un formulario con mi consulta. **Escenario 02**: Given que envío el formulario, When falta un campo obligatorio, Then debería impedir el envío y mostrar un mensaje de error indicando qué falta completar. | EP05 |
| US15 | Creación de Perfil Freelance | Como estudiante, deseo crear mi perfil freelance con mi nombre, carrera y universidad para que los clientes conozcan mi identidad profesional. | **Escenario 01:** Given que soy nuevo en la plataforma, When accedo a "Wanna Sell?", Then debería poder llenar campos como nombre, universidad y carrera. **Escenario 02**: Given que completé el formulario, When presiono “Guardar”, Then debería mostrarse un mensaje de confirmación y redirigirme al perfil creado. | EP06 |
| US16 | Añadir Habilidades y Descripción Personal | Como freelancer, deseo añadir habilidades y una descripción personal a mi perfil para destacar mis fortalezas. | **Escenario 01:** Given que estoy editando mi perfil, When ingreso habilidades y descripción, Then debería guardarse correctamente y verse en mi perfil público. **Escenario 02**: Given que edité mis habilidades, When regreso a mi perfil público, Then debería mostrarse la información actualizada en la sección de habilidades. | EP06 |
| US17 | Establecer Tarifas por Servicio | Como freelancer, deseo establecer mis tarifas por tipo de servicio para que los clientes vean cuánto cobro. | **Escenario 01:** Given que accedo a mi perfil, When ingreso una tarifa para un servicio, Then debería guardarse y mostrarse al público. **Escenario 02**: Given que ingreso un valor fuera del rango permitido, When intento guardar, Then debería mostrarse un mensaje de error de validación. | EP06 |
| US18 | Subir Portafolio de Proyectos | Como freelancer, deseo subir muestras de trabajos anteriores para mostrar mi experiencia a los clientes. | **Escenario 01:** Given que estoy en la sección de portafolio, When subo un archivo o enlace, Then debería verse en mi perfil con título y descripción. **Escenario 02**: Given que subo un archivo no permitido, When intento guardar el portafolio, Then debería mostrarse un mensaje de error indicando el tipo de archivo permitido. | EP06 |
| US19 | Editar y Actualizar Perfil en Cualquier Momento | Como freelancer, deseo poder actualizar mi perfil cuando quiera para mantener mi información al día. | **Escenario 01:** Given que accedo a “Edit Profile”, When modifico algún dato, Then debería guardarse correctamente sin errores. **Escenario 02**: Given que edité mi perfil exitosamente, When regreso a la vista pública, Then debería visualizar los cambios aplicados sin necesidad de recargar. | EP06 |
| US20 | Publicar un Servicio Personalizado | Como freelancer, deseo publicar un servicio con título, descripción y precio para ofrecerlo a potenciales clientes. | **Escenario 01:** Given que soy freelancer, When accedo a “Publish Service”, Then debería poder completar un formulario con título, descripción, categoría y precio. **Escenario 02**: Given que omití un campo obligatorio, When intento guardar el servicio, Then debería mostrarse un mensaje de error indicando qué debe completarse. | EP07 |
| US21 | Establecer Plazos de Entrega | Como freelancer, deseo definir el tiempo de entrega estimado para cada servicio para que el cliente tenga expectativas claras. | **Escenario 01:** Given que estoy publicando un servicio, When selecciono un plazo de entrega, Then debería mostrarse junto al resto de detalles del servicio. **Escenario 02**: Given que seleccioné un plazo, When se muestra públicamente, Then debería incluir el número de días junto a la descripción del servicio. | EP07 |
| US22 | Editar Servicios Publicados | Como freelancer, deseo poder editar los servicios que ya publiqué para corregir errores o actualizar precios y descripciones. | **Escenario 01:** Given que tengo un servicio publicado, When ingreso a "Edit service", Then debería poder modificar campos y guardar los cambios. **Escenario 02**: Given que edité un campo del servicio, When guardo los cambios, Then debería aparecer un mensaje de confirmación y el servicio actualizado debería estar disponible públicamente. | EP07 |
| US23 | Pausar o Eliminar Servicios Publicados | Como freelancer, deseo pausar o eliminar mis servicios si ya no los ofrezco o deseo ocultarlos temporalmente. | **Escenario 01:** Given que tengo servicios publicados, When presiono “Pause Service” o “Eliminate Service”, Then el servicio debería dejar de mostrarse públicamente. **Escenario 02**: Given que pausé un servicio, When regreso al listado de mis servicios, Then debería ver el estado actualizado como "Paused" y poder reactivarlo desde ahí. | EP07 |
| US24 | Añadir Imágenes o Archivos al Servicio | Como freelancer, deseo subir imágenes o archivos de muestra a mis servicios para ayudar al cliente a visualizar mejor lo que ofrezco. | **Escenario 01:** Given que estoy publicando un servicio, When adjunto una imagen o archivo, Then debería visualizarse como parte de la publicación. **Escenario 02**: Given que adjunto varias imágenes, When visualizo el servicio publicado, Then debería poder navegar entre las imágenes en un visor tipo carrusel. | EP07 |
| US25 | Buscar Freelancers por Palabra Clave | Como cliente, deseo buscar freelancers usando palabras clave para encontrar rápidamente quienes ofrecen lo que necesito. | **Escenario 01:** Given que soy cliente, When ingreso una palabra clave en el buscador, Then debería ver freelancers cuyos servicios coincidan con esa palabra. **Escenario 02**: Given que ingreso varias palabras clave, When presiono "Search", Then los resultados deberían mostrar coincidencias que incluyan al menos una de las palabras. | EP08 |
| US26 | Filtrar Freelancers por Habilidad | Como cliente, deseo filtrar freelancers según sus habilidades para encontrar al más apto para mi proyecto. | **Escenario 01:** Given que estoy buscando freelancers, When selecciono una habilidad del filtro, Then solo deberían mostrarse aquellos que la tienen registrada. **Escenario 02**: Given que selecciono varias habilidades, When aplico el filtro, Then debería mostrarse la combinación de freelancers que cumplan con al menos una de ellas. | EP08 |
| US27 | Filtrar por Rango de Precios | Como cliente, deseo establecer un rango de precios para ver freelancers que cobren dentro de mi presupuesto. | **Escenario 01:** Given que establezco un rango de precios, When aplico el filtro, Then debería ver resultados ajustados al presupuesto indicado. **Escenario 02**: Given que no hay freelancers en el rango seleccionado, When aplico el filtro, Then debería mostrarse un mensaje indicando “No se encontraron resultados en este rango de precios”. | EP08 |
| US28 | Filtrar por Nivel de Experiencia | Como cliente, deseo filtrar freelancers según su experiencia (básica, intermedia, avanzada) para elegir el nivel adecuado para mi necesidad. | **Escenario 01:** Given que uso el filtro de experiencia, When selecciono un nivel, Then deberían aparecer freelancers con ese nivel en su perfil. **Escenario 02**: Given que selecciono el nivel "Advanced", When veo los resultados, Then cada freelancer debería mostrar su nivel de experiencia en su tarjeta resumen. | EP08 |
| US29 | Ordenar Resultados por Relevancia o Calificación | Como cliente, deseo ordenar los resultados de búsqueda por calificación o relevancia para facilitar la comparación de perfiles. | **Escenario 01:** Given que busco freelancers, When elijo una opción de ordenamiento, Then la lista debería reordenarse de acuerdo al criterio seleccionado. **Escenario 02**: Given que cambio el criterio de ordenamiento de "Relevance" a "Qualification", When la página se actualiza, Then debería reflejar el nuevo orden y mantener los filtros seleccionados. | EP08 |
| US30 | Contratar desde el Perfil del Freelancer | Como cliente, deseo poder contratar a un freelancer directamente desde su perfil para ahorrar tiempo en el proceso de negociación. | **Escenario 01:** Given que estoy en el perfil de un freelancer, When hago clic en “Hire”, Then debería abrirse un formulario para confirmar la contratación y condiciones. **Escenario 02**: Given que contrato a un freelancer desde su perfil, When confirmo la solicitud, Then debería agregarse un registro en mi historial de contrataciones. | EP09 |
| US31 | Confirmación de Contratación Exitosa | Como cliente, deseo recibir una confirmación visual y por correo al contratar a un freelancer para saber que el proceso fue exitoso. | **Escenario 01:** Given que contrato un freelancer, When confirmo la acción, Then debería ver una notificación en pantalla y recibir un correo con los detalles del proyecto. **Escenario 02**: Given que recibo la confirmación, When reviso mi correo, Then debería encontrar un mensaje con el nombre del freelancer y los términos acordados. | EP09 |
| US32 | Rechazar o Aceptar una Solicitud de Contrato | Como freelancer, deseo tener la opción de aceptar o rechazar una contratación directa para mantener el control sobre mi disponibilidad. | **Escenario 01:** Given que recibo una solicitud de contrato, When reviso los detalles, Then debería poder aceptarla o rechazarla desde mi panel de notificaciones. **Escenario 02**: Given que rechazo una contratación, When el cliente revisa el estado, Then debería ver la notificación con el motivo (si se brindó). | EP09 |
| US33 | Ver Historial de Contrataciones Realizadas | Como cliente, deseo ver un historial de las contrataciones directas realizadas para tener un registro de mis actividades. | **Escenario 01:** Given que he contratado freelancers, When accedo a mi historial, Then debería ver una lista con nombres, fechas y estados de cada contratación. **Escenario 02**: Given que accedo a mi historial, When selecciono una contratación, Then debería poder ver detalles como fecha, nombre del freelancer y monto acordado. | EP09 |
| US34 | Visualizar Proyectos Activos | Como freelancer, deseo ver una lista de mis proyectos activos para organizarme y darles seguimiento. | **Escenario 01:** Given que estoy en mi dashboard, When accedo a “Mis Proyectos”, Then debería ver una lista con el título, cliente, y estado de cada proyecto activo. **Escenario 02**: Given que tengo múltiples proyectos activos, When ingreso al panel, Then debería poder ordenarlos por fecha de inicio o estado del proyecto. | EP10 |
| US35 | Gestionar Solicitudes Recibidas | Como freelancer, deseo revisar y gestionar solicitudes de nuevos proyectos para aceptar solo las que se ajusten a mi disponibilidad. | **Escenario 01:** Given que tengo solicitudes pendientes, When entro al panel de notificaciones, Then debería poder ver detalles y aceptar o rechazar cada una. **Escenario 02**: Given que rechazo una solicitud, When regreso al panel de solicitudes, Then la solicitud rechazada debería mostrarse con un estado “Rechazado” y opción de comentario. | EP10 |
| US36 | Marcar Proyecto como Finalizado | Como freelancer, deseo marcar un proyecto como finalizado para indicar que mi trabajo ha sido completado. | **Escenario 01:** Given que he terminado un proyecto, When entro al detalle del proyecto, Then debería poder marcarlo como “Finalizado”. **Escenario 02**: Given que marco un proyecto como finalizado, When el cliente revisa el proyecto, Then debería aparecer el estado actualizado como “Finalized by the Freelancer”. | EP10 |
| US37 | Seguimiento del Estado del Proyecto | Como cliente, deseo ver el estado de mis proyectos en curso para saber si están en espera, en proceso o finalizados. | **Escenario 01:** Given que contraté un freelancer, When accedo a “My hires”, Then debería ver el estado actualizado de cada proyecto. **Escenario 02**: Given que el proyecto cambia de estado, When ingreso al detalle del mismo, Then debería poder ver un historial con los cambios de estado y fechas correspondientes. | EP10 |
| US38 | Calificar al Freelancer Finalizado el Proyecto | Como cliente, deseo dejar una calificación al freelancer al finalizar el proyecto para compartir mi experiencia con otros usuarios. | **Escenario 01:** Given que finalizó un proyecto, When accedo a la sección de calificación, Then debería poder seleccionar una puntuación del 1 al 5 y escribir un comentario. **Escenario 02**: Given que ya califiqué al freelancer, When reviso el proyecto, Then debería ver el comentario que dejé y la calificación asignada. | EP11 |
| US39 | Ver Calificaciones en Perfil de Freelancer | Como cliente, deseo ver las calificaciones que otros clientes han dejado en el perfil del freelancer para tomar una decisión informada. | **Escenario 01:** Given que visito el perfil de un freelancer, When reviso la sección de reseñas, Then debería ver las calificaciones promedio y comentarios anteriores. **Escenario 02**: Given que estoy viendo las reseñas, When hago clic en una calificación, Then debería poder expandirla para ver el comentario completo si está truncado. | EP11 |
| US40 | Editar Calificación Después de Proyecto | Como cliente, deseo poder editar mi calificación si he cometido un error o si hubo una mejora significativa tras el feedback. | **Escenario 01:** Given que ya dejé una calificación, When hago clic en “Edit Review”, Then debería poder modificar el puntaje y/o comentario. **Escenario 02**: Given que edito una reseña, When la guardo, Then debería aparecer una etiqueta indicando “Review edited” con la nueva fecha. | EP11 |
| US41 | Calificar al Cliente | Como freelancer, deseo calificar al cliente luego de terminar un proyecto para que otros freelancers conozcan su reputación. | **Escenario 01:** Given que terminé un proyecto, When accedo a la sección de calificaciones, Then debería poder puntuar al cliente y dejar un comentario. **Escenario 02**: Given que califico al cliente, When regreso a mi historial de proyectos, Then debería ver un ícono o mensaje indicando que ya he calificado ese proyecto. | EP11 |
| US42 | Enviar Mensaje a Usuario desde Perfil | Como usuario, deseo enviar un mensaje a otro usuario desde su perfil para coordinar antes de contratar o aceptar un proyecto. | **Escenario 01:** Given que estoy en el perfil de un usuario, When hago clic en "Send Message", Then debería abrirse una ventana de chat para iniciar la conversación. **Escenario 02**: Given que inicio una conversación, When el otro usuario responde, Then debería mostrarse una notificación dentro del ícono de mensajes. | EP12 |
| US43 | Ver Historial de Conversaciones | Como usuario, deseo ver el historial de mis conversaciones previas para recordar acuerdos y detalles importantes. | **Escenario 01:** Given que tengo mensajes anteriores, When ingreso a la sección de “Messages”, Then debería ver una lista de chats recientes con sus respectivos nombres y fechas. **Escenario 02**: Given que abro un chat antiguo, When hago scroll hacia arriba, Then debería cargarse el historial completo de mensajes anteriores automáticamente. | EP12 |
| US44 | Notificación de Nuevo Mensaje | Como usuario, deseo recibir una notificación cuando me envíen un nuevo mensaje para no perderme ninguna comunicación importante. | **Escenario 01:** Given que me enviaron un mensaje, When estoy dentro o fuera de la plataforma, Then debería recibir una notificación visual. **Escenario 02**: Given que recibo un mensaje nuevo, When estoy dentro de la conversación, Then el nuevo mensaje debería aparecer automáticamente sin necesidad de recargar. | EP12 |
| US45 | Bloquear o Reportar Usuario desde Chat | Como usuario, deseo poder bloquear o reportar a alguien desde el chat si recibo mensajes inapropiados o spam. | **Escenario 01:** Given que estoy en una conversación, When hago clic en "Report User", Then debería aparecer un formulario con motivo y botón para enviar el reporte. **Escenario 02**: Given que bloqueé a un usuario, When intento enviarle otro mensaje, Then debería recibir una notificación indicando que no puedo interactuar con ese usuario. | EP12 |
| US46 | Sugerencia de Precio Inteligente | Como usuario, deseo recibir una sugerencia automática de precio al momento de negociar, para basarme en un valor justo según experiencia y tipo de servicio. | **Escenario 01:** Given que estoy creando una propuesta, When selecciono tipo de servicio y nivel de experiencia, Then debería mostrarse una sugerencia de precio calculada automáticamente. **Escenario 02**: Given que ya tengo una tarifa sugerida, When modifico el tipo de servicio, Then el sistema debería actualizar automáticamente la sugerencia con el nuevo valor. | EP13 |
| US47 | Ajuste Manual sobre Precio Sugerido | Como usuario, deseo poder modificar manualmente el precio sugerido para adaptarlo a mis propias condiciones. | **Escenario 01:** Given que veo la sugerencia de precio, When edito el campo manualmente, Then debería permitir cambiarlo sin perder la base de cálculo previa. **Escenario 02**: Given que ya ingresé un nuevo valor, When regreso a la sección de precios, Then debería verse el valor manual ingresado como definitivo. | EP13 |
| US48 | Detalle del Cálculo del Precio | Como usuario, deseo ver una explicación breve de cómo se calculó el precio sugerido para tener mayor confianza en su lógica. | **Escenario 01**: Given que recibo una sugerencia de precio, When hago clic en "View Details", Then debería mostrarse un resumen con factores como experiencia, tipo y tamaño del servicio. **Escenario 02**: Given que veo los factores del cálculo, When paso el cursor por cada uno, Then debería mostrarse una breve descripción de cómo influye en el precio. | EP13 |
| US49 | Comparación entre Propuesta y Oferta | Como usuario, deseo comparar mi propuesta con la oferta del otro usuario para llegar más fácilmente a un acuerdo. | **Escenario 01:** Given que ambos usuarios hicieron una propuesta, When estoy en la sección de negociación, Then debería verse una tabla comparativa entre los dos valores. **Escenario 02**: Given que hay una diferencia significativa entre ambas partes, When abro la tabla comparativa, Then debería verse un mensaje sugerente para negociar o ajustar. | EP13 |
| US50 | Historial de Precios de Servicios Similares | Como usuario, deseo ver precios promedios de servicios similares contratados anteriormente para decidir mejor mi tarifa. | **Escenario 01:** Given que estoy creando una propuesta, When hago clic en "See price history", Then debería verse un gráfico o listado con precios de trabajos similares. **Escenario 02**: Given que estoy viendo precios anteriores, When selecciono una categoría distinta, Then debería actualizarse el historial mostrado según la nueva categoría. | EP13 |

### **3.3. Impact Mapping.** 

Se realizaron los siguientes cuadros en la herramienta Miro, el link original puede ser observado aquí: [LINK Impact Mapping](https://miro.com/app/board/uXjVIE5Pk5Q=/?share_link_id=296495865120)

**Impact Map Segmento 1:** Estudiantes Universitarios Freelancers  

El impact map de GigU para los estudiantes universitarios freelancers busca proporcionar un sistema robusto con alta posibilidad de personalización para la expresión creativa y profesional de los freelancers con la posibilidad de subir portafolios completos, publicar diversos tipos de servicios y editar o personalizar los perfiles junto a los servicios del freelancer.  
<img src="imgs/ImpactMap1.png" alt="ImpactMapping" title="ImpactMapping"/>

**Impact Map Segmento 2:** Personas y Emprendimientos que buscan contratar servicios freelance  

El impact map de GigU para las personas y emprendimientos que buscan contratar servicios freelance busca optimizar el proceso del contratado de freelancers por medio de un sistema de búsqueda completo que permite encontrar al freelancer indicado teniendo en cuenta sus servicios disponibles, la media de costos que propone y su nivel de experiencia.  
<img src="imgs/ImpactMap2.png" alt="ImpactMapping" title="ImpactMapping"/>

### **3.4. Product Backlog.** 

Se utilizó la escala Fibonacci para la estimación de los Story Points. En total se tuvieron **197** Story Points.

| \# Orden | Epic / Story ID | Título | Descripción | Story Points (1/2/3/5/8) |
| :---: | :---: | ----- | ----- | :---: |
| 1 | US01 | Navegación Intuitiva en la Landing Page | Como visitante de GigU, deseo que la landing page tenga una barra de navegación clara y accesible para encontrar fácilmente las secciones importantes. | 3 |
| 2 | US02 | Acceso rápido a funcionalidades clave | Como visitante, deseo acceder desde la landing page a secciones clave como “Publicar proyecto” o “Registrarse” para actuar rápidamente. | 3 |
| 3 | US03 | Registro con Correo y Contraseña | Como nuevo usuario, deseo poder registrarme en la plataforma con mi correo y contraseña para acceder a las funcionalidades de GigU. | 3 |
| 4 | US04 | Iniciar sesión como Freelancer o Cliente | Como usuario registrado, deseo poder iniciar sesión para acceder a mi cuenta y funcionalidades específicas según mi rol. | 5 |
| 5 | US05 | Registro con redes sociales | Como visitante, deseo registrarme con Google para agilizar el proceso de creación de cuenta. | 2 |
| 6 | US06 | Solicitar recuperación de contraseña | Como usuario, deseo solicitar la recuperación de mi contraseña para volver a acceder si la olvido. | 2 |
| 7 | US07 | Restablecer contraseña vía correo | Como usuario, deseo poder restablecer mi contraseña desde un enlace de recuperación enviado a mi correo. | 2 |
| 8 | US08 | Conocer los beneficios de GigU | Como visitante, deseo conocer los beneficios de usar GigU para saber por qué debería usar esta plataforma. | 1 |
| 9 | US09 | Diferencias entre roles (freelancer / cliente)	 | Como visitante, deseo saber las diferencias entre registrarme como freelancer o cliente para elegir el rol adecuado. | 8 |
| 10 | US10 | Experiencias de otros usuarios | Como visitante, deseo ver testimonios de usuarios anteriores para confiar en la plataforma. | 5 |
| 11 | US11 | Detalles sobre tipos de servicios | Como visitante, deseo conocer los tipos de servicios que puedo contratar o brindar en GigU. | 5 |
| 12 | US12 | Acceso a Preguntas Frecuentes | Como visitante, deseo ver una sección de preguntas frecuentes para resolver mis dudas comunes sin ayuda externa. | 3 |
| 13 | US13 | Búsqueda dentro de Preguntas Frecuentes | Como usuario, deseo buscar palabras clave en la sección de FAQ para encontrar respuestas más rápido. | 3 |
| 14 | US14 | Envío de Ticket de Soporte | Como usuario, deseo enviar un mensaje de soporte si no encuentro mi duda en la FAQ para recibir asistencia personalizada. | 3 |
| 15 | US15 | Creación de Perfil Freelance | Como estudiante, deseo crear mi perfil freelance con mi nombre, carrera y universidad para que los clientes conozcan mi identidad profesional. | 5 |
| 16 | US16 | Añadir Habilidades y Descripción Personal | Como freelancer, deseo añadir habilidades y una descripción personal a mi perfil para destacar mis fortalezas. | 8 |
| 17 | US17 | Establecer Tarifas por Servicio | Como freelancer, deseo establecer mis tarifas por tipo de servicio para que los clientes vean cuánto cobro. | 8 |
| 18 | US18 | Subir Portafolio de Proyectos | Como freelancer, deseo subir muestras de trabajos anteriores para mostrar mi experiencia a los clientes. | 5 |
| 19 | US19 | Editar y Actualizar Perfil en Cualquier Momento | Como freelancer, deseo poder actualizar mi perfil cuando quiera para mantener mi información al día. | 3 |
| 20 | US20 | Publicar un Servicio Personalizado | Como freelancer, deseo publicar un servicio con título, descripción y precio para ofrecerlo a potenciales clientes. | 5 |
| 21 | US21 | Establecer Plazos de Entrega | Como freelancer, deseo definir el tiempo de entrega estimado para cada servicio para que el cliente tenga expectativas claras. | 5 |
| 22 | US22 | Editar Servicios Publicados | Como freelancer, deseo poder editar los servicios que ya publiqué para corregir errores o actualizar precios y descripciones. | 5 |
| 23 | US23 | Pausar o Eliminar Servicios Publicados | Como freelancer, deseo pausar o eliminar mis servicios si ya no los ofrezco o deseo ocultarlos temporalmente. | 5 |
| 24 | US24 | Añadir Imágenes o Archivos al Servicio | Como freelancer, deseo subir imágenes o archivos de muestra a mis servicios para ayudar al cliente a visualizar mejor lo que ofrezco. | 3 |
| 25 | US25 | Buscar Freelancers por Palabra Clave | Como cliente, deseo buscar freelancers usando palabras clave para encontrar rápidamente quienes ofrecen lo que necesito. | 3 |
| 26 | US26 | Filtrar Freelancers por Habilidad | Como cliente, deseo filtrar freelancers según sus habilidades para encontrar al más apto para mi proyecto. | 3 |
| 27 | US27 | Filtrar por Rango de Precios | Como cliente, deseo establecer un rango de precios para ver freelancers que cobren dentro de mi presupuesto. | 5 |
| 28 | US28 | Filtrar por Nivel de Experiencia | Como cliente, deseo filtrar freelancers según su experiencia (básica, intermedia, avanzada) para elegir el nivel adecuado para mi necesidad. | 5 |
| 29 | US29 | Ordenar Resultados por Relevancia o Calificación | Como cliente, deseo ordenar los resultados de búsqueda por calificación o relevancia para facilitar la comparación de perfiles. | 3 |
| 30 | US30 | Contratar desde el Perfil del Freelancer | Como cliente, deseo poder contratar a un freelancer directamente desde su perfil para ahorrar tiempo en el proceso de negociación. | 5 |
| 31 | US31 | Confirmación de Contratación Exitosa | Como cliente, deseo recibir una confirmación visual y por correo al contratar a un freelancer para saber que el proceso fue exitoso. | 3 |
| 32 | US32 | Rechazar o Aceptar una Solicitud de Contrato | Como freelancer, deseo tener la opción de aceptar o rechazar una contratación directa para mantener el control sobre mi disponibilidad. | 3 |
| 33 | US33 | Ver Historial de Contrataciones Realizadas | Como cliente, deseo ver un historial de las contrataciones directas realizadas para tener un registro de mis actividades. | 2 |
| 34 | US34 | Visualizar Proyectos Activos | Como freelancer, deseo ver una lista de mis proyectos activos para organizarme y darles seguimiento. | 5 |
| 35 | US35 | Gestionar Solicitudes Recibidas | Como freelancer, deseo revisar y gestionar solicitudes de nuevos proyectos para aceptar solo las que se ajusten a mi disponibilidad. | 3 |
| 36 | US36 | Marcar Proyecto como Finalizado | Como freelancer, deseo marcar un proyecto como finalizado para indicar que mi trabajo ha sido completado. | 3 |
| 37 | US37 | Seguimiento del Estado del Proyecto | Como cliente, deseo ver el estado de mis proyectos en curso para saber si están en espera, en proceso o finalizados. | 5 |
| 38 | US38 | Calificar al Freelancer Finalizado el Proyecto | Como cliente, deseo dejar una calificación al freelancer al finalizar el proyecto para compartir mi experiencia con otros usuarios. | 3 |
| 39 | US39 | Ver Calificaciones en Perfil de Freelancer | Como cliente, deseo ver las calificaciones que otros clientes han dejado en el perfil del freelancer para tomar una decisión informada. | 5 |
| 40 | US40 | Editar Calificación Después de Proyecto | Como cliente, deseo poder editar mi calificación si he cometido un error o si hubo una mejora significativa tras el feedback. | 5 |
| 41 | US41 | Calificar al Cliente | Como freelancer, deseo calificar al cliente luego de terminar un proyecto para que otros freelancers conozcan su reputación. | 5 |
| 42 | US42 | Enviar Mensaje a Usuario desde Perfil | Como usuario, deseo enviar un mensaje a otro usuario desde su perfil para coordinar antes de contratar o aceptar un proyecto. | 3 |
| 43 | US43 | Ver Historial de Conversaciones | Como usuario, deseo ver el historial de mis conversaciones previas para recordar acuerdos y detalles importantes. | 2 |
| 44 | US44 | Notificación de Nuevo Mensaje | Como usuario, deseo recibir una notificación cuando me envíen un nuevo mensaje para no perderme ninguna comunicación importante. | 1 |
| 45 | US45 | Bloquear o Reportar Usuario desde Chat | Como usuario, deseo poder bloquear o reportar a alguien desde el chat si recibo mensajes inapropiados o spam. | 2 |
| 46 | US46 | Sugerencia de Precio Inteligente | Como usuario, deseo recibir una sugerencia automática de precio al momento de negociar, para basarme en un valor justo según experiencia y tipo de servicio. | 8 |
| 47 | US47 | Ajuste Manual sobre Precio Sugerido | Como usuario, deseo poder modificar manualmente el precio sugerido para adaptarlo a mis propias condiciones. | 5 |
| 48 | US48 | Detalle del Cálculo del Precio | Como usuario, deseo ver una explicación breve de cómo se calculó el precio sugerido para tener mayor confianza en su lógica. | 5 |
| 49 | US49 | Comparación entre Propuesta y Oferta | Como usuario, deseo comparar mi propuesta con la oferta del otro usuario para llegar más fácilmente a un acuerdo. | 3 |
| 50 | US50 | Historial de Precios de Servicios Similares | Como usuario, deseo ver precios promedios de servicios similares contratados anteriormente para decidir mejor mi tarifa. | 2 |


## **4.1. Style Guidelines**

### **4.1.1. General Style Guidelines**

●      **Tipografía**: Se utiliza la familia tipográfica Inter, con pesos 400, 600 y 800. Es moderna, legible y coherente para interfaces digitales.  
  

●      **Colores principales**:  
  

○      Azul claro: #5acae6 (acentos, íconos)

○      Blanco: #ffffff (fondos)

○      Negro/Gris oscuro: #222 a #333 (textos)

●      **Estilo visual**:  
  

○      Minimalista, limpio y profesional.  
  

○      Íconos Font Awesome estilizados con color coherente.  
  

○      Uso consistente de **espaciado**, **bordes redondeados**, y **botones de acción con fondo azul claro**.  
  

●      **Interactividad**:  
  

○      Botones con efecto hover.  
  

○      Modal animado con fade-in/fade-out.  
  

---

### **4.1.2. Web Style Guidelines**

●      **Responsividad**: Uso de viewport en <meta> para dispositivos móviles.

●      **Componentes**:  
  

○      Botones reutilizables con clase .button.  
  

○      Secciones con títulos destacados (.section-title).  
  

●      **Accesibilidad**:  
  

○      Etiquetas alt en imágenes.

○      Campos input con placeholder y atributos required.  
  

●      **Animaciones suaves**:  
  

○      @keyframes fadeIn / fadeOut aplicadas a modales.

---

## **4.2. Information Architecture**

### **4.2.1. Organization Systems**

●      **Jerárquico**: La información está organizada de mayor a menor importancia:  
  

○      Encabezado (navegación)  
  

○      Hero Section  
  

○      Sección de confianza  
  

○      Sobre Nosotros  
  

○      Servicios  
  

○      Clientes  
  

○      Contacto  
  

●      **Modular y Seccional**: Cada área está contenida en su propio <section> con clases semánticas (about-section, services-section, etc.).  
  

---

### **4.2.2. Labeling Systems**

●      **Menú principal**:  
  

○      Inicio, Nosotros, Servicios, Clientes, Contacto.  
  

●      **Botones de acción**:  
  

○      “Explorar más”, “Ver más”, “Enviar correo”.  
  

●      **Formulario**:  
  

○      Campos etiquetados por placeholder: Nombre, Correo, Contraseña.  
  

### **4.2.3. SEO Tags and Meta Tags**

○      **Meta etiquetas presentes**:  
  
 html  
CopiarEditar  
<meta charset="UTF-8">

○      <meta name="viewport" content="width=device-width, initial-scale=1.0">

○      <title>GigU - Soluciones Web</title>

●       

●      **Mejoras sugeridas**:  
  

○      Añadir <meta name="description"> con descripción clara del negocio.

○      Etiquetas <meta property="og:title">, <og:image>, etc., para redes sociales.  
  

○      Uso de etiquetas semánticas como <section>, <header>, <nav>, <footer> para SEO técnico.

### **4.2.4. Searching Systems**

●      **Actualmente no hay un sistema de búsqueda implementado.  
  
**

○      Recomendación: incluir un input type="search" en el menú o el footer con funcionalidad básica para encontrar contenido en la página o blog.

### **4.2.5. Navigation Systems**

●      **Navegación superior**:  
  

○      Menú fijo con links anclados (#nosotros, #servicios, etc.).  
  

○      Botón de llamada a la acción “Empezar”.  
  

●      **Flujo lógico**:  
  

○      Registro/Login primero → Página principal después.  
  

●      **Internacionalización**:  
  

○      Sitio en español; estructura preparada para multilenguaje si se extiende.  
  

●      **Footer con navegación secundaria**:  
  

○      WhatsApp, Email, Dirección, y redes sociales como Facebook, Instagram y LinkedIn.  
  

●      **Estructura modular:**

○      Cada sección puede contener tarjetas, grids o listas de contenido reutilizable.  
  

#### **4.2.2. Labeling Systems**

●      **Etiquetas claras y estándar:**

○      Menú: Inicio, Sobre Nosotros,Servicios, Contacto.  
  

○      Botones: “Explorar más”, “ver mas ”, “Enviar correo”.”Saber más”  
  

●      **URL Amigables:** /servicios, /contacto, /proyectos/nombre-aplicacion

4.2.3. SEO Tags and Meta Tags

<title>Aplicaciones Web | Soluciones Innovadoras</title>

<meta name="description" content="Desarrollo de aplicaciones web personalizadas para optimizar procesos empresariales y digitales.">

<meta name="keywords" content="Aplicaciones web, desarrollo web, software a medida, soluciones digitales">

<meta property="og:title" content="Aplicaciones Web | Soluciones Digitales">

<meta property="og:description" content="Creamos plataformas web funcionales, escalables y modernas.">

<meta property="og:image" content="url-del-logo-o-imagen.jpg">

<meta property="og:type" content="website">

#### **4.2.4. Searching Systems**

●      **Buscador en la landing page y header.**

●      Filtro por tipo de aplicación o categoría (administrativas, educativas, gestión).  
  

●      Resultados ordenados por coincidencia y fecha.  
  

#### **4.2.5. Navigation Systems**

●      **Menú Fijo (Sticky):** Con accesos a Inicio, Servicios, Contacto.

●      **Navegación Interna (anchor links):** Scroll suave a secciones dentro de una misma página.

●      **Footer completo:** Enlaces rápidos, redes sociales, contacto, política de privacidad.

### **4.3. Landing Page UI Design**



<img src="imgs/Image1.png" alt="LandingPageUIDesign" title="LandingPageUIDesign"/>

<img src="imgs/image2.png" alt="LandingPageUIDesign" title="LandingPageUIDesign"/>

<img src="imgs/image3.png" alt="LandingPageUIDesign" title="LandingPageUIDesign"/>

<img src="imgs/image4.png" alt="LandingPageUIDesign" title="LandingPageUIDesign"/>

#### **4.3.1. Landing Page Wireframe**

<img src="imgWireframe/main.png" alt="Main Page" title="Main Page"/>

### **4.3.2. Landing Page Mock-up**

<img src="imgs/image3.png" alt="LandingPageUIDesign" title="LandingPageUIDesign"/>

 #### **4.4. Web Applications UX/UI Design.**
 #### **4.4.1. Web Applications Wireframes.**
En esta sección se mostrarán los wireframes de nuestra aplicación
<h2 align="center">Página Principal</h2>

<img src="imgWireframe/main.png" alt="Main Page" title="Main Page"/>

---

<h2 align="center">Descripción del Servicio</h2>

<img src="imgWireframe/description-app.png" alt="Service Description" title="Service Description"/>

---

<h2 align="center">Confirmación de Registro como Freelancer</h2>

<img src="imgWireframe/freelance-confirmation.png" alt="Freelance Confirmation" title="Freelance Confirmation"/>

---

<h2 align="center">Perfil del Freelancer</h2>

<img src="imgWireframe/freelance-profile.png" alt="Freelance Profile" title="Freelance Profile"/>

---

<h2 align="center">Verificación de Identidad</h2>

<img src="imgWireframe/freelance-verification.png" alt="Freelance Verification" title="Freelance Verification"/>

---

<h2 align="center">Login</h2>

<img src="imgWireframe/login.png" alt="Login Page" title="Login Page"/>

---

<h2 align="center">Confirmación de Inicio de Sesión</h2>

<img src="imgWireframe/loging-ver.png" alt="Login Confirmation" title="Login Confirmation"/>

---

<h2 align="center">Registro de Usuario</h2>

<img src="imgWireframe/sign-up.png" alt="User Sign Up" title="User Sign Up"/>

---

<h2 align="center">Perfil del Usuario</h2>

<img src="imgWireframe/Profile-user.png" alt="User Profile" title="User Profile"/>

---

<h2 align="center">Pull y Negociación de Servicios</h2>

<img src="imgWireframe/Pull.png" alt="Service Pull" title="Service Pull"/>



 #### **4.4.2. Web Applications Wireflow Diagrams.**
 
# User Goal: Usuario se registra, recupera contraseña y inicia sesión a la aplicación

<img src="imgWireframe/diagram-sign-logout.png" alt="diagram-sign-logout" title="diagram-sign-logout"/>

**Descripción:**  
Cuando el usuario abre la aplicación, se encuentra con el formulario de **registro de cuenta**. Si ya tiene una cuenta, puede optar por la opción **"Iniciar sesión"**. Al hacerlo, deberá ingresar sus credenciales en el formulario de **inicio de sesión**. Si la información es correcta, accederá a la **página principal** de la plataforma.

Si el usuario ha olvidado su contraseña, puede seleccionar la opción **"Recuperar contraseña"**. Esto lo llevará a un formulario donde debe ingresar su **correo electrónico**. Tras enviarlo, recibirá un **enlace de recuperación** en su correo para restablecer su contraseña.

Una vez que el usuario haya restablecido su contraseña o ingresado las credenciales correctas, podrá acceder a la **página principal** de la plataforma.

---

# User Goal: Usuario se inscribe como freelancer y quiere subir alguna oferta

<img src="imgWireframe/diagram-freelancer.png" alt="diagram-freelancer" title="diagram-freelancer"/>

**Descripción:**  
El proceso de registro comienza cuando el usuario accede al formulario de **registro de cuenta**. En este formulario, deberá proporcionar sus datos personales, como **nombre completo**, **correo electrónico** y otros detalles relevantes para completar su perfil en la plataforma.

Durante el proceso de inscripción, el usuario deberá **adjuntar dos documentos**:  
- Una **foto de su DNI**.  
- Una **foto de su carnet universitario**.  

Estos documentos son necesarios para validar la identidad y el estatus académico del freelancer.

Una vez que el formulario se complete y los documentos se hayan subido, el sistema procederá a **validar los datos** y, si todo es correcto, la cuenta será **verificada y aprobada**.

Luego de la validación exitosa, el sistema enviará un **mensaje de bienvenida**, informando al usuario que su cuenta ha sido aprobada y que ahora puede comenzar a ofrecer sus servicios como freelancer.

Después del registro, el usuario será redirigido a la **pantalla principal** del freelancer, donde podrá ver información sobre su cuenta, estadísticas y las herramientas necesarias para comenzar a ofrecer servicios. En esta pantalla, podrá interactuar con los clientes y gestionar las ofertas de servicio.

Si desea comenzar a ofrecer sus servicios, el freelancer puede hacer clic en **"Crear un nuevo GIG"**. Esto lo llevará a un formulario donde deberá completar los campos como el **título del GIG**, la **categoría** y los **search tags**, los cuales ayudarán a los usuarios a encontrar su servicio dentro de la plataforma.

Finalmente, después de completar el formulario de GIG, el freelancer será llevado a una **página de confirmación**, donde podrá revisar todos los detalles antes de publicar el GIG. Si todo es correcto, podrá proceder con la **publicación** del GIG y comenzar a recibir solicitudes o propuestas.

---

# User Goal: Usuario quiere contratar a un freelancer

<img src="imgWireframe/diagram-contact-freelancer.png" alt="diagram-freelancer" title="diagram-freelancer"/>

**Descripción:**  
El proceso comienza cuando el **usuario** decide contratar a un freelancer. El usuario accede a la **publicación** del freelancer, donde puede consultar la información básica sobre los servicios ofrecidos, los **comentarios de otros usuarios** y la **tarifa mínima** del servicio.

Si el usuario está interesado y desea continuar, hace clic en el botón **"Contratar"**, lo que lo llevará a la **calculadora inteligente**.

En esta calculadora, el usuario completará un formulario donde ingresará detalles sobre el **trabajo a realizar**, como **duración** y **funcionalidades requeridas**. Con esta información, el sistema calculará automáticamente una **estimación de costo** para el servicio solicitado.

Una vez recibida la estimación, el usuario puede decidir **aceptar el presupuesto** o negociar el precio con el freelancer. Si acepta la oferta, será redirigido a una página donde podrá interactuar con el freelancer para llegar a un acuerdo final sobre el **precio y las condiciones** del trabajo.

Cuando ambas partes acuerden el precio, el usuario pasará a la **página de pago**, donde podrá realizar el pago correspondiente. El sistema le proporcionará las opciones de pago disponibles, y una vez completado el proceso de pago, el usuario recibirá una **notificación de confirmación** de que el pago fue exitoso y que el trabajo está en proceso.

Finalmente, el usuario será redirigido a su **perfil personal**, donde podrá ver una lista de **órdenes activas**, con detalles sobre el estado de cada una y la opción de interactuar con los freelancers asignados.


 #### **4.4.3. Web Applications Mock-ups.**
<h1 align="center">Wireframes y Mockups del Proyecto</h1>

<h2 align="center">forgot pass</h2>

<img src="imgMockup/forgot-pass.png" alt="forgot-pass" title="forgot-pass"/>

---

<h2 align="center">forgot pop</h2>

<img src="imgMockup/forgot-pop.png" alt="forgot-pop" title="forgot-pop"/>

---

<h2 align="center">freelance verification</h2>

<img src="imgMockup/freelace-verification.png" alt="freelace-verification" title="freelace-verification"/>

---

<h2 align="center">freelance profile</h2>

<img src="imgMockup/freelance-profile.png" alt="freelance-profile" title="freelance-profile"/>

---

<h2 align="center">freelance verificated</h2>

<img src="imgMockup/freelance-verificated.png" alt="freelance-verificated" title="freelance-verificated"/>

---

<h2 align="center">log in</h2>

<img src="imgMockup/login.png" alt="login" title="login"/>

---

<h2 align="center">login verified/h2>

<img src="imgMockup/login-verified.png" alt="login-verified" title="login-verified"/>

---

<h2 align="center">main log out</h2>

<img src="imgMockup/main-logout.png" alt="main-logout" title="main-logout"/>

---

<h2 align="center">posting gig</h2>

<img src="imgMockup/posting-gig.png" alt="posting-gig" title="posting-gig"/>

---

<h2 align="center">profile freelancer ocupacion</h2>

<img src="imgMockup/profile-freelancer-ocupacion.png" alt="profile-freelancer-ocupacion" title="profile-freelancer-ocupacion"/>

---

<h2 align="center">user profile</h2>

<img src="imgMockup/user-profile.png" alt="user-profile" title="user-profile"/>

---

<h2 align="center">user profile main </h2>

<img src="imgMockup/user-profile-main.png" alt="user-profile-main" title="user-profile-main"/>

---

<h2 align="center">pull </h2>

<img src="imgMockup/pull.png" alt="pull" title="pull"/>

---

<h2 align="center">sign up</h2>

<img src="imgMockup/sign-up.png" alt="sign-up" title="sign-up"/>

---

<h2 align="center">startup description</h2>

<img src="imgMockup/startup-description.png" alt="startup-description" title="startup-description"/>

---

<h2 align="center">user payment</h2>

<img src="imgMockup/user-payment.png" alt="user-payment" title="user-payment"/>

 #### **4.4.4. Web Applications User Flow Diagrams.**
 **User Goal:** Usuario se registra, recupera contraseña y inicia sesión a la aplicación con credenciales
 
<img src="imgMockup/wireflow-register.png" alt="wireflow-register" title="wireflow-register"/>

**Description:** Al iniciar la aplicación, el usuario se encuentra en el formulario de registro de cuenta. Si ya tiene una cuenta, puede seleccionar la opción "Iniciar sesión". Si el usuario ya tiene una cuenta, ingresará sus credenciales en el formulario de inicio de sesión. Si las credenciales son correctas, accederá a la página principal de la plataforma.

En caso de que el usuario no recuerde su contraseña, podrá hacer clic en "Recuperar contraseña". Esto lo llevará a un formulario donde ingresará su correo electrónico asociado a la cuenta. Al enviar el formulario, el sistema enviará un enlace de recuperación al correo proporcionado para que el usuario pueda restablecer su contraseña.

Una vez que el usuario ingrese sus credenciales correctas, ya sea después de haber restablecido la contraseña o al haberlas ingresado correctamente en el inicio de sesión, accederá a la página principal de la plataforma.

---


 **User Goal:** Usuario se inscribe como freelancer y quiere subir alguna oferta
<img src="imgMockup/wireflow-register-freelancer.png" alt="wireflow-register" title="wireflow-register"/>

**Description:** El proceso de inscripción comienza cuando el usuario accede al formulario de registro de cuenta. En este formulario, debe ingresar sus datos personales reales, como su nombre completo, correo electrónico, y otros detalles relevantes que ayudarán a completar su perfil en la plataforma.

A continuación, durante la inscripción, el usuario debe adjuntar dos documentos esenciales para la validación de su cuenta. Estos documentos son una foto de su DNI y una foto de su carnet universitario, los cuales son necesarios para verificar la identidad y el estatus académico del freelancer.

Una vez que el formulario se ha completado y los documentos han sido subidos, el sistema procederá a validar la información y los documentos proporcionados por el usuario. Si todo es correcto, la cuenta será verificada y aprobada para que el freelancer pueda continuar con el proceso.

Tras la validación exitosa, el sistema enviará un mensaje de bienvenida, informando al usuario que su cuenta ha sido aprobada y que ahora tiene acceso a la plataforma como freelancer. Desde este momento, podrá comenzar a ofrecer sus servicios y gestionar su perfil.

Luego de completar el registro, el usuario será dirigido a la pantalla principal del freelancer, donde podrá visualizar detalles sobre su cuenta, estadísticas relevantes y las herramientas necesarias para comenzar a ofrecer sus servicios a través de la plataforma. Esta pantalla principal proporciona acceso a todas las funcionalidades para interactuar con los clientes y gestionar las ofertas de servicio.

Si el freelancer desea comenzar a ofrecer sus servicios, podrá hacer clic en la opción "Crear un nuevo GIG", lo que lo llevará a un formulario de creación de GIG. En este formulario, el freelancer deberá proporcionar información clave como el título del GIG, la categoría en la que se encuentra el servicio que ofrece, y los search tags, que ayudarán a los usuarios a encontrar su servicio más fácilmente dentro de la plataforma.

Finalmente, después de completar el formulario de GIG, el freelancer será redirigido a una página de confirmación, donde podrá revisar todos los detalles del GIG antes de proceder con su publicación. Si todo está correcto, podrá publicar el GIG y comenzar a recibir ofertas o solicitudes de los usuarios interesados en sus servicios.

---


 **User Goal:** Usuario quiere contratar a un freelancer
<img src="imgMockup/wireflow-contact-freelancer.png" alt="wireflow-register" title="wireflow-register"/>

**Description:** El proceso comienza cuando el usuario desea contratar a un freelancer. Este accede a la publicación del freelancer, donde puede ver la información básica sobre los servicios ofrecidos, los comentarios de otros usuarios y la tarifa mínima del servicio.

Una vez que el usuario revisa la publicación y decide continuar, puede hacer clic en el botón de "Contratar" para proceder con el siguiente paso del proceso de contratación. Al hacerlo, será redirigido a la calculadora inteligente.

En la calculadora inteligente, el usuario deberá completar un formulario con las características de su trabajo. Este formulario permite ingresar detalles como la duración del proyecto, las funcionalidades requeridas y cualquier otro dato relevante. Una vez que el usuario complete la información, el sistema calculará automáticamente una estimación de costo para el servicio solicitado.

Después de recibir la estimación de precio, el usuario tendrá la opción de aceptar el presupuesto o negociar con el freelancer. Si el usuario acepta el precio, será redirigido a una página de interacción donde podrá comunicarse directamente con el freelancer para llegar a un acuerdo final sobre el precio y las condiciones del trabajo.

Una vez que ambas partes acuerden el precio, el usuario procederá a la página de pago, donde podrá realizar el pago correspondiente por el servicio. El sistema proporcionará las opciones de pago disponibles, y una vez completada la transacción, el usuario recibirá una notificación de confirmación indicando que el pago ha sido exitoso y que el trabajo está en proceso.

Finalmente, el usuario será dirigido a su perfil personal, donde podrá visualizar una lista de las órdenes activas (es decir, los trabajos que ha contratado), incluyendo detalles sobre el estado de cada uno y la posibilidad de interactuar con los freelancers asignados.

### *4.5. Web Applications Prototyping.*  
En esta sección se compartirán los prototipos relacionados a la aplicación web, donde se presentan el alcance de los user goals en ambos segmentos objetivos.

Enlace del Prototipo:[Ver Prototipo](https://www.figma.com/proto/uWjErNes085X9nT1QnwbG4/APPWEB-4371-Figma?node-id=1-4863&p=f&t=AUYuxuxOvdv1Z2d3-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A575)

Enlace del Video de Prototipo:[Ver Video de Prototipo](https://drive.google.com/file/d/198c49nDlMbolfklmcFJzCl5_C-Hjvktt/view?usp=drive_link)

#### **4.6. Domain-Driven Software Architecture.**

Este segmento se describe los diagramas arquitectónicos para la plataforma GigU, una plataforma de servicios freelance para estudiantes universitarios.
---

   ##### **4.6.1. Software Architecture Context Diagram.**

**Objetivo:**  
Mostrar el sistema GigU en su entorno, identificando actores y sistemas externos que interactúan con la plataforma.

 ![DiagramaContexto](imgs/structurizr-102394-SystemContext-001.png)

**Elementos principales:**  
- **Actores:** Estudiante universitario freelance, Cliente.  
- **Sistema:** GigU.  
- **Sistemas externos:** APIs de Factiliza, SendGrid, RENIEC y Google.

**Relaciones:**  
- Los actores usan GigU para ofrecer o contratar servicios freelance.  
- GigU consume servicios externos para validar información y enviar notificaciones.

**Componentes Utilizados**
![DiagramaContexto](imgs/structurizr-102394-SystemContext-001-key.png)

---
   ##### **4.6.2. Software Architecture Container Diagrams.**

**Objetivo:**  
Descomponer el sistema GigU en sus contenedores tecnológicos principales y mostrar sus interacciones.

 ![DiagramaContenedores](imgs/structurizr-102394-Container-001.png)

**Contenedores:**  
- **Landing Page:** Página web estática para presentación y redireccionamiento.  
- **Aplicación Web:** Frontend en Vue.js para interacción de usuarios.  
- **API RESTful:** Backend en ASP.NET Core que maneja la lógica y acceso a datos.  
- **Base de Datos:** MySQL que almacena toda la información del sistema.

**Relaciones:**  
- Los usuarios interactúan con la Landing Page y la Aplicación Web.  
- La Aplicación Web se comunica con el API RESTful para operaciones.  
- El API RESTful accede a la Base de Datos para lectura y escritura.  
- El API también integra servicios externos para validaciones y notificaciones.

**Componentes Utilizados**
 ![DiagramaContenedores](imgs/structurizr-102394-Container-001-key.png)

---

  

   ##### **4.6.3. Software Architecture Components Diagrams**
   **Objetivo:**  
Detallar los componentes internos del API RESTful para definir responsabilidades y dependencias.

   ![DiagramaComponentes](imgs/structurizr-102394-Component-001-001.png)
**Componentes:**  
- Notificaciones  
- Chat  
- Gestión de servicios  
- Contratos  
- Calificaciones y comentarios  
- Calculadora  
- Autenticación y registro  
- Perfiles  
- Shared Kernel

**Relaciones:**  
- Todos los componentes interactúan con la Base de Datos para persistencia.  
- Los componentes *Perfiles* y *Autenticación y registro* consumen servicios externos (Factiliza, RENIEC, Google, SendGrid).  
- La Landing Page y Aplicación Web llaman al componente *Autenticación y registro* para la gestión de usuarios.


  **Componentes Utilizados**
 ![DiagramaContenedores](imgs/structurizr-102394-Component-001-key.png)

 
  
 #### **4.7. Software Object-Oriented Design.**
##### **4.7.1. Class Diagrams.**
   
   <img src="imgs/Class_Diagram.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>


   ##### **4.7.2. Class Dictionary**

   **User**

| Attribute | Type | Description | Constraints |
| :---- | :---- | :---- | :---- |
| id | UUID | Unique identifier | PRIMARY KEY |
| name | String | Full name | NOT NULL |
| email | String | Email address | UNIQUE, NOT NULL |
| password | String | Encrypted password | NOT NULL |
| role | String | User role (client/freelancer) | ENUM('client', 'freelancer') |
| bio | Text | Personal description |  |
| profile\_image\_url | String | Profile picture URL |  |
| reputation\_score | Float | Average rating (0-5) | DEFAULT 0.0 |
| created\_at | DateTime | Account creation timestamp | DEFAULT CURRENT\_TIMESTAMP |
| updated\_at | DateTime | Last profile update | DEFAULT CURRENT\_TIMESTAMP |

**AcademicPortfolio**

| Attribute | Type | Description | Constraints |
| :---- | :---- | :---- | :---- |
| id | UUID | Unique identifier | PRIMARY KEY |
| user\_id | UUID | Associated freelancer | FOREIGN KEY (users.id), UNIQUE |
| university | String | Institution name | NOT NULL |
| career | String | Field of study | NOT NULL |
| semester | Integer | Academic progress level |  |
| cv\_url | String | Resume/CV document link |   |

**Portfolio**

| Attribute | Type | Description | Constraints |
| :---- | :---- | :---- | :---- |
| id | UUID | Unique identifier | PRIMARY KEY |
| user\_id | UUID | Owner | FOREIGN KEY (users.id) |
| title | String | Work title | NOT NULL |
| description | Text | Project details |  |
| file\_url | String | Portfolio item file | NOT NULL |
| created\_at | DateTime | Creation timestamp | DEFAULT CURRENT\_TIMESTAMP |

**Service**

| Attribute | Type | Description | Constraints |
| :---- | :---- | :---- | :---- |
| id | UUID | Unique identifier | PRIMARY KEY |
| user\_id | UUID | Freelancer offering service | FOREIGN KEY (users.id) |
| title | String | Service name | NOT NULL |
| description | Text | Detailed offering | NOT NULL |
| category | String | Main category | NOT NULL |
| subcategory | String | Specialization | NOT NULL |
| base\_price | Float | Minimum price | NOT NULL |
| delivery\_time\_days | Integer | Estimated completion days | NOT NULL |
| price\_by\_calculator | Float | System-suggested price |  |
| is\_active | Boolean | Availability status | DEFAULT TRUE |
| created\_at | DateTime | Listing creation time | DEFAULT CURRENT\_TIMESTAMP |

**PriceCalculator**

| Attribute | Type | Description | Constraints |
| :---- | :---- | :---- | :---- |
| id | UUID | Unique identifier | PRIMARY KEY |
| difficulty | String | Complexity level | ENUM('easy','medium','hard') |
| urgency | String | Time sensitivity | ENUM('low','medium','high') |
| freelancer\_level | String | Experience tier | ENUM('junior','mid','senior') |
| market\_trend | Float | Demand adjustment factor | NOT NULL |
| suggested\_price | Float | Algorithm-calculated price | NOT NULL |

**ServiceNegociation**

| Attribute | Type | Description | Constraints |
| :---- | :---- | :---- | :---- |
| id | UUID | Unique identifier | PRIMARY KEY |
| service\_id | UUID | Negotiated service | FOREIGN KEY (services.id) |
| client\_id | UUID | Client making offer | FOREIGN KEY (users.id) |
| proposed\_price | Float | Alternate price suggestion | NOT NULL |
| status | String | Negotiation state | ENUM('pending','accepted','rejected') |
| created\_at | DateTime | Proposal timestamp | DEFAULT CURRENT\_TIMESTAMP |

**Order**

| Attribute | Type | Description | Constraints |
| :---- | :---- | :---- | :---- |
| id | UUID | Unique identifier | PRIMARY KEY |
| service\_id | UUID | Contracted service | FOREIGN KEY (services.id) |
| client\_id | UUID | Ordering client | FOREIGN KEY (users.id) |
| freelancer\_id | UUID | Service provider | FOREIGN KEY (users.id) |
| final\_price | Float | Agreed payment amount | NOT NULL |
| status | String | Order state | ENUM('created','in\_progress','delivered','completed','cancelled') |
| delivery\_date | Date | Deadline for completion | NOT NULL |
| created\_at | DateTime | Order creation time | DEFAULT CURRENT\_TIMESTAMP |

**Payment**

| Attribute | Type | Description | Constraints |
| :---- | :---- | :---- | :---- |
| id | UUID | Unique identifier | PRIMARY KEY |
| order\_id | UUID | Associated order | FOREIGN KEY (orders.id), UNIQUE |
| amount | Float | Transaction value | NOT NULL |
| payment\_method | String | Payment processor | NOT NULL |
| status | String | Payment state | ENUM('pending','completed','failed','refunded') |
| created\_at | DateTime | Payment timestamp | DEFAULT CURRENT\_TIMESTAMP |

**Review**

| Attribute | Type | Description | Constraints |
| :---- | :---- | :---- | :---- |
| id | UUID | Unique identifier | PRIMARY KEY |
| order\_id | UUID | Reviewed order | FOREIGN KEY (orders.id) |
| reviewer\_id | UUID | User writing review | FOREIGN KEY (users.id) |
| reviewed\_user\_id | UUID | User being rated | FOREIGN KEY (users.id) |
| rating | Integer | Quality score (1-5) | RANGE(1,5) |
| comment | Text | Written feedback |  |
| created\_at | DateTime | Review timestamp | DEFAULT CURRENT\_TIMESTAMP |

**ChatMessage**

| Attribute | Type | Description | Constraints |
| :---- | :---- | :---- | :---- |
| id | UUID | Unique identifier | PRIMARY KEY |
| order\_id | UUID | Context order | FOREIGN KEY (orders.id) |
| sender\_id | UUID | Message author | FOREIGN KEY (users.id) |
| receiver\_id | UUID | Message recipient | FOREIGN KEY (users.id) |
| message | Text | Communication content | NOT NULL |
| file\_url | String | Attached file link |  |
| sent\_at | DateTime | Send timestamp | DEFAULT CURRENT\_TIMESTAMP |

  #### **4.8. Database Design**

   ##### **4.8.1. Database Diagrams.**
   
   <img src="imgs/Database GigU.png" alt="LeanUXCanvas" title="LeanUXCanvas"/>

### **5.1. Software Configuration Management.**

### **5.1.1. Software Development Environment Configuration**

A continuación, se detallan las herramientas de software empleadas durante el desarrollo de nuestro proyecto.

* Gestión de Proyectos

- **WhatsApp**: [LINK WhatsApp](https://www.whatsapp.com)   
  Utilizamos WhatsApp como canal principal de comunicación para coordinar tareas, compartir ideas y brindar soporte entre los miembros del equipo durante todo el proceso de desarrollo.

* Diseño UX/UI del Producto

- **Miro:** [LINK Miro](https://miro.com/es/)     
  Se empleó Miro para la elaboración del Lean UX Canvas y To-Be Scenario Mapping, el cual nos ayudó a visualizar los aspectos estratégicos del diseño centrado en el usuario.  
    
- **Uxpressia:** [LINK Uxpressia](https://uxpressia.com/)    
  Con esta herramienta desarrollamos las User Personas, Mapas de Empatía y Journey Maps, facilitando así el entendimiento profundo de nuestros usuarios.  
    
- **Figma:** [LINK Figma](https://www.figma.com/)     
  Figma fue nuestra herramienta principal para crear wireframes, wireflows, prototipos y maquetas de la landing page y las aplicaciones web.


* Desarrollo de Software

- **Landing Page**:  
  La página principal del proyecto fue desarrollada utilizando tecnologías estándar como HTML5, CSS y JavaScript.

* Pruebas de Software

- **Navegador**:  
  Las pruebas del sitio web y la aplicación se llevaron a cabo mediante las herramientas de desarrollo integradas en los navegadores Google Chrome, Brave, Opera y Edge.

* Entornos de Desarrollo (IDE)

- **Visual Studio Code**: [LINK Visual Studio Code](https://code.visualstudio.com)   
  Visual Studio Code fue nuestro entorno de desarrollo preferido para el frontend debido a su ligereza, amplia disponibilidad de extensiones.

* Despliegue de Software

- **GitHub Pages**: [LINK GitHub Pages](https://pages.github.com/)     
  La landing page fue desplegada a través de GitHub Pages, lo que permitió una publicación automatizada desde el repositorio

* Documentación de Software

- **Google Docs**: [LINK Google Docs](https://docs.google.com/document)    
  Google Docs nos permitió hacer seguimiento de tareas y compartir información relevante entre los integrantes del equipo.  
    
- **GitHub**: [LINK GitHub](https://github.com/)    
  GitHub fue clave para la documentación colaborativa del proyecto, permitiendo la trazabilidad de cambios mediante commits y GitFlow.

### **5.1.2. Source Code Management.**

Para administrar y organizar los cambios realizados en el proyecto, creamos un repositorio en GitHub que centralizó el desarrollo. La estructura fue la siguiente:

* Organización

- **Repositorio en GitHub**: [LINK Repositorio](https://github.com/ASI0730-Final-Project)   
    
- **Landing Page**: [LINK Landing Page](https://github.com/ASI0730-Final-Project/GigU-Landing)   

* Ramas Principales

- **Rama main**:  
  Contiene la versión estable del proyecto, lista para ser puesta en producción.  
    
- **Rama docs/**:  
  Rama destinada a la integración de nuevas funcionalidades antes de ser lanzadas.

### **5.1.3. Source Code Style Guide & Conventions.**

Con el objetivo de mantener la coherencia, legibilidad y calidad del código durante el desarrollo de la landing page y la aplicación web, adoptamos una serie de convenciones específicas para cada tecnología utilizada:

* HTML  
    
- Tipo de Documento: Cada archivo HTML inicia con \<\!DOCTYPE html\> para asegurar su correcta interpretación por los navegadores.  
    
- Etiquetas en Minúsculas: Todas las etiquetas y atributos se escriben en minúscula.
    
- Cierre Correcto de Etiquetas: Nos aseguramos de cerrar todas las etiquetas, incluso las opcionales, para mantener una estructura clara y evitar errores.  
    
- Atributos entre Comillas: Los valores de los atributos siempre están entre comillas dobles.
    
- Imágenes Accesibles: Incluimos los atributos alt, width y height en las imágenes, lo cual mejora tanto la accesibilidad como el diseño adaptable.  
    
- Formato Limpio en Atributos: No se colocan espacios alrededor del signo igual. 
    
- Uso del Elemento \<title\>: No se omite el título de la página, ya que es fundamental para el SEO y la accesibilidad.  
    
- Idioma y Codificación: Se declara el idioma con el atributo lang y se define la codificación.

* CSS

- **Recursos Seguros**: Todos los recursos externos, como fuentes y multimedia, se cargan mediante HTTPS.  
    
- **Nombres en Minúsculas**: Los selectores, propiedades y valores se escriben en minúsculas para mantener un estilo uniforme.  
    
- **Nombres de Clase Descriptivos**: Las clases CSS reflejan su función usando palabras clave separadas por guiones.  
    
- **Propiedades Abreviadas**: Se aplican propiedades abreviadas siempre que sea posible para optimizar el tamaño del código.  
    
- **Orden Alfabético**: Las propiedades CSS dentro de un bloque se ordenan alfabéticamente para facilitar la lectura y mantenimiento.  
    
- **Uso Consistente del Punto y Coma**: Cada línea termina con un punto y coma para evitar errores de interpretación.  
    
- **Espaciado Uniforme**: Se mantiene un espacio después de los dos puntos y dentro de las llaves de los bloques.  
    
- **Comillas en Atributos**: Los valores como fuentes están entre comillas simples.

#### **5.1.4. Software Deployment Configuration.**

**Ilustracion Github Software Deployment Configuration 1**
<img src="imgs/Software Deployment Configuration1.jpg" alt="Software Deployment Configuration1" title="Software Deployment Configuration1"/>

**Ilustracion Github Software Deployment Configuration 2**
<img src="imgs/Software Deployment Configuration2.jpg" alt="Software Deployment Configuration2" title="Software Deployment Configuration2"/>

**Ilustracion Github Software Deployment Configuration 3**
<img src="imgs/Software Deployment Configuration3.jpg" alt="Software Deployment Configuration3" title="Software Deployment Configuration3"/>

**Ilustracion Github Software Deployment Configuration 4**
<img src="imgs/Software Deployment Configuration4.jpg" alt="Software Deployment Configuration4" title="Software Deployment Configuration4"/>

**Ilustracion Github Software Deployment Configuration 5**
<img src="imgs/Software Deployment Configuration5.jpg" alt="Software Deployment Configuration5" title="Software Deployment Configuration5"/>


### **5.2. Landing Page, Services & Applications Implementation.**

#### **5.2.1. Sprint 1**

##### **5.2.1.1. Sprint Planning 1**

## Sprint Details
| **Field**          | **Value**                     |
|--------------------|-------------------------------|
| Sprint Number      | Sprint 1                      |
| Date               | 25 de abril de 2025           |
| Time               | 05:00 PM                      |
| Location           | Modalidad remota              |
| Prepared By        | [Nombre de tu equipo]         |
| Attendees          | Todos los miembros del equipo |

## Sprint Overview
**Previous Sprint Summary:**  
*No hay resúmenes previos (primer sprint).*

**Sprint Goal:**  
Desarrollar y desplegar una landing page funcional que cumpla con todas las historias de usuario para la interacción inicial con clientes.

## Technical Specifications
| **Aspect**         | **Details**                   |
|--------------------|-------------------------------|
| Duration           | 10 - 25 de abril de 2025              |
| Team Capacity      | 120 horas totales             |
| Tech Stack         | HTML5, CSS3, JavaScript, Figma|
| Velocity           | 18                            |
| Total Story Points | 18                            |


##### **5.2.1.2. Aspect Leaders and Collaborators**

##### **5.2.1.3. Sprint Backlog 1**

**Objetivo**: Desarrollar y desplegar una landing page funcional que cumpla con todas las historias de usuario especificadas para la interacción inicial con clientes y presentación del producto.

**Alcance**:
- Implementar barra de navegación responsive
- Crear componentes de llamada a la acción (CTA)
- Desarrollar sección de beneficios del servicio
- Construir tarjetas interactivas de servicios
- Implementar funcionalidad de preguntas frecuentes (FAQ)

**Duración**: 1 al 14 de marzo de 2024  
**Capacidad del equipo**: 120 horas totales  
**Requisitos técnicos**: HTML5, CSS3, JavaScript, diseños en Figma

![alt text](imgs/ImagenGithubGigU.PNG)

### Líderes de Aspecto y Colaboradores
#####
| Team Member (Last Name, First Name) | GitHub Username | Landing page Leader (L) / Collaborator (C) | DocumentationLeader (L) / Collaborator (C) | Epics Leader (L) / Collaborator (C) |
| :---- | :---- | :---- | :---- | :---- |
| Mariano Moises Oblitas Davila | MarianoOblitas | C | L | C |
| Diego Alonso Cacho Seminario | Memesitos | C | C | C |
| Bryan Felix Martinez Ramos | BryanMR1 | C | C | C |
| Renato Yauri Chocce | JavierRog | C | C | C |
| Diego Antonio Seijas Vásquez | NotSeijas |L | C | C |
| Giancarlo Rafael Solis Santa Cruz | LucidVoid10 | C | C | L |
| Irving Washington Allcca Guerrero | Diegosaurio18 | C | C | C |

##### 

### Sprint Backlog 1
| ID Historia de Usuario | Descripción de Tarea | Estado | Asignado a | Horas Estimadas | Horas Reales |
|--------------|------------------|--------|-------------|-----------------|--------------|
| US01 | Implementar barra de navegación responsive | Completado | Seijas Vásquez | 5 | 6 |
| US01 | Diseñar componentes de navegación en Figma | Completado | Seijas Vásquez | 3 | 2.5 |
| US02 | Desarrollar botones CTA principales | Completado | Seijas Vásquez | 4 | 5 |
| US08 | Crear contenido de sección de beneficios | Completado | Oblitas Davila | 2 | 3 |
| US08 | Implementar interfaz de tarjetas de beneficios | Completado | Oblitas Davila | 6 | 7 |
| US11 | Diseñar tarjetas de servicios | Completado | Cacho Seminario | 4 | 5 |
| US11 | Programar interactividad de tarjetas | Completado | Cacho Seminario | 5 | 6 |
| US12 | Investigar y compilar preguntas frecuentes | Completado | Solis Santa Cruz | 3 | 4 |
| US12 | Implementar acordeón de FAQ | Completado | Solis Santa Cruz | 5 | 4 |



##### **5.2.1.4. Development Evidence for Sprint Review**

En el alcance del sprint 1 se ha desarrollado el landing page como primera instancia, por lo que no se evidencia testeo de servicios o interacciones.

##### **5.2.1.5. Execution Evidence for Sprint Review**
Aqui se puede ver la evidencia del sprint.
Video de Landing:[Execution Evidence for Sprint Review](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202210167_upc_edu_pe/EdnyKPia8E9JgiZsrh1oo3gBnjmZByEaVxkEXSIe0pTYLA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=e0sw3A)

##### **5.2.1.6. Services Documentation Evidence for Sprint Review**

En el primer Sprint solamente se ha desarrollado la Landing Page por lo que no se ha hecho uso de servicios web.

##### **5.2.1.7. Software Deployment Evidence for Sprint Review**
Link de la Landing:[Landing Page](https://asi0730-final-project.github.io/GigU-Landing/)

##### **5.2.1.8. Team Collaboration Insights during Sprint**

El equipo desarrolló la landing page por ramas para desarrollar cada user story asignadas de la sprint. Una vez terminado con el desarrollo pasaría por las validaciones para el despliegue de la aplicación. Debido a la disponibilidad de tiempos se delegó la responsabilidad del desarrollo a un integrante con capacidades para realizarlo.Ademas se mostrara el corecto proceso que se realizo en la documentacion por parte del grupo. A continuación se presenta el insight.

*Landing Page*

<img src="imgs/1graphcommit.png" alt="GraphCommit1" title="GraphCommit1"/>

<img src="imgs/1networkcommit.png" alt="NetworkCommit1" title="NetworkCommit1"/>

*READ.ME*

<img src="imgs/2graphcommit.png" alt="GraphCommit2" title="GraphCommit2"/>

<img src="imgs/2networkcommit.png" alt="NetworkCommit2" title="LeanUXCaNetworkCommit2nvas"/>

#### **5.2.2. Sprint 2**

##### 5.2.2.1. Sprint Planning 2\.

 

*  Sprint Details

| Field | Value |
| :---: | :---: |
| Sprint Number | Sprint 2 |
| Date | 10 de Mayo de 2025 |
| Time | 04:30 PM |
| Location | Modalidad remota |
| Prepared By | GigU |
| Attendees | Todos los miembros del equipo |

* Sprint Overview

**Previous Sprint Summary:**  
Para el Sprint 1, buscamos desarrollar y desplegar una landing page funcional que cumpla con todas las historias de usuario especificadas para la interacción inicial con clientes y presentación del producto.

**Sprint Goal:**  
Desarrollar y desplegar el front end de nuestro producto teniendo en cuenta las historias de usuario anteriormente especificadas implementando además el uso de fake APIs.

**Technical Specifications:**

| Aspect | Details |
| :---: | :---: |
| Duration | 26 de Abril \- 14 de Mayo de 2025 |
| Team Capacity | 120 horas totales |
| Tech Stack | Vue, PrimeVue, JavaScript, Figma |
| Velocity | \# |
| Total Story Points | \# |

##### 5.2.2.2. Aspect Leaders and Collaborators.


| Team Member (Last Name, First Name) | GitHub Username | Landing page Leader (L) / Collaborator (C) | DocumentationLeader (L) / Collaborator (C) | Epics Leader (L) / Collaborator (C) |
| :---- | :---- | :---- | :---- | :---- |
| Mariano Moises Oblitas Davila | MarianoOblitas | C | L | C |
| Diego Alonso Cacho Seminario | Memesitos | C | C | L |
| Bryan Felix Martinez Ramos | BryanMR1 | C | C | C |
| Renato Yauri Chocce | JavierRog | C | C | C |
| Diego Antonio Seijas Vásquez | NotSeijas |L | C | C |
| Giancarlo Rafael Solis Santa Cruz | LucidVoid10 | C | C | C |
| Irving Washington Allcca Guerrero | Diegosaurio18 | C | C | C |

 

##### 5.2.2.3. Sprint Backlog 2\.

**Objetivo:** Desarrollar y desplegar el front end de nuestro producto teniendo en cuenta las historias de usuario anteriormente especificadas implementando además el uso de fake APIs.

**Alcance:**

* Implementar un Fake API para el guardado de información  
* Aplicar seguridades básicas  
* Corregir la organización del código y carpetas

**Duración:** 26 de Abril \- 14 de Mayo de 2025

**Capacidad de equipo:** 120 horas totales \- 7 integrantes

**Requisitos técnicos:** Vue, PrimeVue, JavaScript diseños en Figma


| **Task ID** | **User Story** | **Description** | **Assigned To** | **Estimated Hours** | **Status** | **Epic** |
|------------|----------------|-----------------|-----------------|----------------------|------------|----------|
| T01 | US03, US04 | Implement login/register with email/password (Fake API) | Mariano Oblitas | 15 | Completed | EP02 |
| T02 | US05 | Integrate Google OAuth for social login (Fake API) | Giancarlo Solis | 10 | Completed | EP02 |
| T03 | US06, US07 | Password recovery flow (email simulation) | Mariano Oblitas | 12 | Completed | EP03 |
| T04 | US15, US16 | Freelancer profile creation (skills, description, fake API save) | Diego Seijas | 20 | Completed | EP06 |
| T05 | US20, US21 | Service publication form (title, description, pricing) | Renato Yauri | 18 | Completed | EP07 |
| T06 | US25, US26 | Freelancer search/filter UI (mock data) | Bryan Martinez | 15 | Completed | EP08 |
| T07 | US30 | "Hire Freelancer" button (Fake API interaction) | Diego Cacho | 10 | Completed | EP09 |
| T08 | US42 | Chat UI for messaging (no backend, mock data) | Diego Seijas | 10 | Completed | EP12 |
| T09 | - | Code organization: Refactor folder structure (Vue best practices) | Giancarlo Solis | 5 | Completed | - |
| T10 | - | Basic security: Input validation, fake JWT simulation | Giancarlo Solis | 5 | Completed | EP02 |

---

 

##### 5.2.2.4. Development Evidence for Sprint Review 2\.

Se evidencia la funcionalidad por medio del siguiente link: https://drive.google.com/drive/folders/1NrkH2ayB4qU-eCF1u6Z2NhzptuG3ecv8?usp=sharing
 

##### 5.2.2.5. Execution Evidence for Sprint Review 2\.

Se evidencia el avance del segundo Sprint (Front End) por medio del siguiente link: https://drive.google.com/drive/folders/1TL6bSnb1KhhZmNsHx1sYCbuYTvyv_TtS?usp=sharing

 

##### 5.2.2.6. Services Documentation Evidence for Sprint Review 2\.

Aquí se muestra la documentación de los servicios empleados. En esta ocasión, hemos utilizado servicios simulados (fake services) para desarrollar la interfaz frontal, simulando así los servicios finales de nuestro producto.

Servicio de users:

<img src="imgs/user-service.jpeg">

##### 5.2.2.7. Software Deployment Evidence for Sprint Review 2\.

Link de frontend web app: https://gigu-3873a.web.app 

 

##### 5.2.2.8. Team Collaboration Insights during Sprint 2\.
El equipo realizó el front end por ramas con el objetivo de mejorar la organización del código y el desarrollo individual de las historias de usuario. Al finalizar con el sprint, se realizó el despliegue de la aplicación. Se presenta el siguiente insight.

*Landing Page*  
<img src="imgs/GraphCommitSprint2_Landing.png">
 
<img src="imgs/NetworkCommitSprint2_Landing.png">

*READ.ME*  
<img src="imgs/GraphCommitSprint2_doc.png">

<img src="imgs/NetworkCommitSprint2_doc.png">


#### **5.2.3. Sprint 3**
##### 5.2.3.1. Spring Planning 3\.

  * Sprint Details.
    
| Field | Value |
| :---: | :---: |
| Sprint Number | Sprint 3 |
| Date | 10 de Junio de 2025 |
| Time | 04:30 PM |
| Location | Modalidad remota |
| Prepared By | GigU |
| Attendees | Todos los miembros del equipo |

  * Sprint Overview
**Previous Sprint Summary:**  
Para el Sprint 2, buscamos desarrollar y desplegar el frontend de nuestra aplicación teniendo en cuenta las historias de usuario anteriormente especificadas implementando además el uso de fake APIs.

**Sprint Goal:**  
Para el Sprint 3, buscamos realizar el backend de nuestra aplicación realizando diversos endpoints y conectarlos hacia una base de datos.

**Technical Specifications:**

| Aspect | Details |
| :---: | :---: |
| Duration | 14 de Mayo \- 20 de Junio de 2025 |
| Team Capacity | 120 horas totales |
| Tech Stack | Vue, PrimeVue, JavaScript, Figma, Rider, Postman, MySQL Workbench, Swagger |
| Velocity | \# |
| Total Story Points | \# |

##### 5.2.3.2. Aspect Leaders and Collaborators.\.
 

| Team Member (Last Name, First Name) | GitHub Username | Diseño UI/UX Leader (L) / Collaborator (C) | Desarrollo Backend Leader (L) / Collaborator (C) | Control de Calidad Leader (L) / Collaborator (C) | Documentación Leader (L) / Collaborator (C) |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Mariano Moises Oblitas Davila | MarianoOblitas | C | L | C | C |
| Diego Alonso Cacho Seminario | Memesitos | C | C | C | L |
| Bryan Felix Martinez Ramos | BryanMR1 | C | C | C | C |
| Renato Yauri Chocce | JavierRog | C | C | C | C |
| Diego Antonio Seijas Vásquez | NotSeijas | L | C | C | C |
| Giancarlo Rafael Solis Santa Cruz | LucidVoid10 | C | C | L | C |
| Irving Washington Allcca Guerrero | Diegosaurio18 | C | C | C | C |

##### 5.2.3.3. Sprint Backlog 3\.

**Objetivo:** Realizar el backend de nuestra aplicación realizando diversos endpoints y conectarlos hacia una base de datos.

**Alcance:**

* Implementar endpoints que satisfagan el uso de nuestra aplicación  
* Conectar nuestro proyecto con una base de datos en tiempo real  
* Corregir la organización de nuestro proyecto

**Duración:** 14 de Mayo \- 20 de Junio de 2025

**Capacidad de equipo:** 120 horas totales \- 7 integrantes

**Requisitos técnicos:** Vue, PrimeVue, JavaScript, Figma, Rider, Postman, MySQL Workbench, Swagger

| Task ID | User Story | Description | Assigned To | Estimated Hours | Status | Epic |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| T01 | US46 | Sugerencia de Precio Inteligente | Mariano Moises Oblitas Davila | 15 | Completado | EP13 |
| T02 | US42 | Enviar Mensaje a Usuario desde Perfil (Back end) | Diego Alonso Cacho Seminario | 10 | Completado | EP12 |
| T03 | US34 | Visualizar Proyectos Activos | Bryan Felix Martinez Ramos | 12 | Completado | EP10 |
| T04 | US24 | Añadir Imágenes o Archivos al Servicio | Renato Yauri Chocce | 15 | Completado | EP07 |
| T05 | US23 | Pausar o Eliminar Servicios Publicados (Back end) | Diego Antonio Seijas Vásquez | 16 | Completado | EP07 |
| T06 | US11 | Detalles sobre tipos de servicios | Giancarlo Rafael Solis Santa Cruz | 13 | Completado | EP04 |
| T07 | US09 | Diferencias entre roles (freelancer / cliente) (Back end) | Irving Washington Allcca Guerrero | 12 | Completado | EP04 |



##### 5.2.3.4. Development Evidence for Sprint Review 3.\.

Se evidencia la funcionalidad por medio del siguiente link: https://github.com/ASI0730-Final-Project/backend

##### 5.2.3.5.  Execution Evidence for Sprint Review 3.\.

Se evidencia el avance del tercer Sprint (Back End) por medio del siguiente link: https://gigu-appbackend-webapi-dqasbuf8fwe8dvf9.canadacentral-01.azurewebsites.net/swagger/index.html

<img src="imgs/ExecutionEvidenceSprint3-1.png">

<img src="imgs/ExecutionEvidenceSprint3-2.png">

<img src="imgs/ExecutionEvidenceSprint3-3.png">

<img src="imgs/ExecutionEvidenceSprint3-4.png">

##### 5.2.3.6.  Services Documentation Evidence for Sprint Review 3.\.

Aquí se muestra la documentación de el deployment y execution.
![SqlFreeDatabase Creation](imgs/SQLfree.JPG)

![Db Creation In MySQL](<imgs/DB CONECTION.JPG>)

![Creacion de Tablas en SQL](imgs/SQL.JPG)

![Conection string en backend](imgs/CONECCTION.JPG)

![Azure Project view](imgs/AzureProyect.JPG)

![Azure Conection](imgs/AzureConections.JPG)

![Creacion de las acciones en github](imgs/ActionCreatrionYarn.JPG)

![Listener Execution in GitHub](imgs/ListenerImageExecution.JPG)

![AzureServer Execution Swagger](imgs/Execution.JPG)

##### 5.2.3.7.  Software Deployment Evidence for Sprint Review 3.\.

Link de frontend web app: https://gigu-3873a.web.app
Link de

##### 5.2.3.8.  Team Collaboration Insights during Sprint.\.
El equipo realizó el back end actualizando la rama principal. Al finalizar el sprint, se realizó el despliegue de la aplicación. Se presenta ele siguiente insight.

*Front End*  
<img src="imgs/frontend-insight2.png">

*Network graph (Front End)*  
<img src="imgs/networkgraph-2.png">

*Back End*  
<img src="imgs/insight-backend2.png">

*Network graph (Back End)*  
<img src="imgs/networkgraph-2.png">

*README*  
<img src="imgs/readme-insight2.png">

*Network graph (README)*  
<img src="imgs/networkgraph-readme2.png">

### **5.3. Validation Interviews.**
##### **5.3.1. Diseño de entrevistas.**

Con el objetivo de recolectar información de nuestros usuarios se realizaron una serie de entrevistas para verificar el rendimiento de la página web.

**Segmento objetivo #1: Estudiantes Universitarios Freelancers**  

**Preguntas personales:**
  * ¿Cuál es tu nombre?
  * ¿Cuántos años tienes?
  * ¿Qué carrera estás estudiando y en qué ciclo te encuentras?
  * ¿Qué tipo de servicio ofreces como freelancer?
  * ¿Cuánto tiempo llevas como freelancer?

**Preguntas principales:**
  * ¿Nuestra página te pareció atractiva visualmente? ¿Por qué?
  * ¿Crees que el diseño se siente moderno y profesional?
  * ¿Pudiste entender fácilmente de qué trata la página?
  * ¿Hubo algo que te confundió o te hizo dudar?
  * ¿Sientes que la página responde a tus necesidades o intereses?
  * ¿Hay algo que crees que debería agregarse o eliminarse?
  * Como freelancer, ¿usarías la página?

**Segmento objetivo #2: Personas y Emprendimientos que buscan contratar servicios freelance** 

**Preguntas personales:**
  * ¿Cuál es tu nombre?
  * ¿Cuántos años tienes?
  * ¿Cuántos años llevas como emprendedor?
  * ¿A qué se dedica tu empresa?
  * ¿Has contratado alguna vez a algún freelancer?

**Preguntas principales:**
  * ¿Qué opinas del diseño general de la página?
  * ¿La página te inspira confianza para contratar freelancers?
  * ¿La navegación te pareció clara y sencilla?
  * ¿Qué parte de la página te pareció más útil o destacada?
  * ¿Qué mejorarías o cambiarías en la página?
  * ¿Crees que la información presentada es suficiente para tomar una decisión de contratación?
  * ¿La recomendarías a otros emprendedores o personas que necesiten contratar freelancers?

##### **5.3.2. Registro de Entrevistas.**

Video completo con las entrevistas: [video de entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202316246_upc_edu_pe/ES8sterK-ilHpaXHHNZeqWoBC4_yGYa9T_ETHo2f8GiO9Q?e=RvBwOH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

**Segmento objetivo #1: Estudiantes Universitarios Freelancers**  

Entrevistado N°1: Mario André Cacho Seminario

<img src="imgs/Entrevista_Mario2.png">

* Sexo: Masculino  
* Edad: 22  
* Ubicación en la que vive: Surco

Acerca de la entrevista:

* Link: [video de entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202316246_upc_edu_pe/ES8sterK-ilHpaXHHNZeqWoBC4_yGYa9T_ETHo2f8GiO9Q?e=RvBwOH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
* Instante en el que inicia: 0:10  
* Duración: 4:48

Resumen:

Para Mario, la página parece ayudarle en sus proyectos como freelancer, considera que los colores y el diseño es atractivo y moderno y le agrada bastante la posibilidad de calcular el precio en base a la actividad y puntos que se registran en ella. Por último le gustaría ver una personalización un poco más detallada de los servicios que brinda con el objetivo de llamar un poco más la atención de ciertas empresas.


 Entrevistado N°2: Enrique Gonzales

<img src="imgs/entrevista-Enrique.png">

  * Sexo: Masculino
  * Edad: 23
  * Ubicación en la que vive: San Miguel

Acerca de la entrevista:

  * Link:[video de entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202316246_upc_edu_pe/ES8sterK-ilHpaXHHNZeqWoBC4_yGYa9T_ETHo2f8GiO9Q?e=RvBwOH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
  * Instante en el que inicia: 04:49
  * Duración:5:10

 Resumen:

 Para Enrique,mencionó que le gustó la aplicación por la adecuada selección de colores, ya que facilitó su comprensión y entendimiento del funcionamiento. Comentó que, por el momento, no considera necesarias mejoras, pues con lo básico le resulta suficiente para desarrollarse en este campo. Además, destacó que la aplicación le permite ofrecer sus servicios como editor sin inconvenientes, y que la funcionalidad de pagos fue beneficiosa y no presentó ningún problema.



**Segmento objetivo #2: Personas y Emprendimientos que buscan contratar servicios freelance** 

Entrevistado N°1: Ciro Torbisco

<img src="imgs/Ciro_E.png">

  * Sexo: Masculino
  * Edad: 22
  * Ubicación en la que vive: San borga

Acerca de la entrevista:

  * Link:[video de entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202316246_upc_edu_pe/ES8sterK-ilHpaXHHNZeqWoBC4_yGYa9T_ETHo2f8GiO9Q?e=RvBwOH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
  * Instante en el que inicia: 10:00
  * Duración: 6:10 

Resumen: 
Para Ciro la página es una idea muy interesante, además de que puede apoyar mucho más a emprendedores con gran capital que requieran un servicio más profesionalizado, le gusta ya que la aplicación sea directa lo cual le brinda confianza al momento contratar un freelancer. 


Entrevistada N°2: Fabrizio Morales Alarcón

<img src="imgs/Fabrizio_E.png">

  * Sexo: Masculino
  * Edad: 25
  * Ubicación en la que vive: San Borja

Acerca de la entrevista:

  * Link:[video de entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202316246_upc_edu_pe/ES8sterK-ilHpaXHHNZeqWoBC4_yGYa9T_ETHo2f8GiO9Q?e=RvBwOH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
  * Instante en el que inicia: 16:11
  * Duración: 5:35

Resumen: 
Para Fabrizio la página está muy balanceada y dinámica, además de que puede encontrar con facilidad lo que busca lo cual lo hace sentir que es una página profesional y le da confianza para contratar servicios.

Entrevistada N°3: Yulia Estephania Martinez Martinez

<img src="imgs/Yulia_E.png">

  * Sexo: Femenino
  * Edad: 19
  * Ubicación en la que vive: Surco

  * Link:[video de entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202316246_upc_edu_pe/ES8sterK-ilHpaXHHNZeqWoBC4_yGYa9T_ETHo2f8GiO9Q?e=RvBwOH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
  * Instante en el que inicia: 21:47
  * Duración: 6:24


Resumen:
Para Yulia le gusto el diseño ya que se siente intuitiva y fácil de navegar en la página, además de que las funcionalidades como el chat que le permite tener una charla previa con el freelancer le inspira confianza tanto en la página como el freelancer.


##### **5.3.3. Evaluaciones según heurísticas.**
**SITE o APP A EVALUAR:** GIG U

**TAREAS A EVALUAR:**  
El alcance de la siguiente evaluación presenta la revisión de la usabilidad de las presentes tareas:

1. Registro de nuevo usuario  
2. Navegación de usuario  
3. Create Gig (visión freelancer)  
4. My Orders (visión emprendimiento)  
5. Pestaña de gigs disponibles

No están incluidas en esta versión de evaluaciones las siguientes tareas:

1. Métodos de pago  
2. Soporte  
3. Sección de mensajes

**ESCALA DE SEVERIDAD**  
Se presenta una lista de puntuación para la calificación de las tareas.

| Nivel | Descripción |
| ----- | :---- |
| **1** | Problema superficial: puede ser fácilmente superado por el usuario ó ocurre con muy poco frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| **2** | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente reléase |
| **3** | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta. |
| **4** | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento. |

**TABLA RESUMEN**

| \# | Problema | Escala de severidad | Heurística/Principio violada(o) |
| :---: | ----- | :---: | ----- |
| **1** | En la página de registro de usuario, al seleccionar una imagen como foto de perfil usando la opción de “Profile Image” el registro de usuario no se puede completar. | 2 | Information Architecture: Is it usable? |
| **2** | En la página de inicio, el botón de cambiar de idioma se encuentra en una posición muy alejada. | 1 | Aesthetic and minimalist design. |
| **3** | En la vista de freelancer, al seleccionar la categoría y/o subcategoría, el despliegue de opciones solo muestra la opción de “Select a Category” y “Select a Subcategory” respectivamente. | 2 | Information Architecture: Is it usable? |
| **4** | El botón de “My Orders” en la vista del Buyer no cambia de página al ser presionado. | 4 | Information Architecture: Is it usable? |
| **5** | En pestaña de gigs disponibles, al interactuar con una de ellas los botones de la parte superior que tienen el overview, la  descripción, el about the seller, el compare packages, el recommendations y el reviews no funciona correctamente. | 2 | Information Architecture: Is it usable? |

**DESCRIPCIÓN DE PROBLEMAS**

PROBLEMA 1: En la página de registro de usuario, al seleccionar una imagen como foto de perfil usando la opción de “Profile Image” el registro de usuario no se puede completar.

Severidad: 2  
Heurística violada: Information Architecture: Is it usable?

Problema:  
Al ingresar a la página de registro de usuario, cuando se selecciona una imagen de nuestro dispositivo utilizando la opción de “Profile Image” el registro de usuario no se llega a terminar, lo que nos brinda un error de registro fallido.

<img src="imgs/ProblemaHeu1.png" alt="ProblemaHeu1" title="ProblemaHeu1"/>

Recomendación:  
Permitir al usuario colocar una imagen de perfil al registrarse.

PROBLEMA 2: En la página de inicio, el botón de cambiar de idioma se encuentra en una posición muy alejada.

Severidad: 1  
Heurística violada: Aesthetic and minimalist design.

Problema:  
Al ingresar a la aplicación y encontrarnos en la página de inicio, cuando se busca el botón para cambiar de idioma este es difícil de encontrar ya que se encuentra en la parte inferior del final de la página de inicio.

<img src="imgs/ProblemaHeu2.png" alt="ProblemaHeu2" title="ProblemaHeu2"/>

Recomendación:  
Brindar la opción de cambiar de idioma en la parte superior de la pantalla o brindarle la posibilidad al usuario de cambiar el idioma en cualquier momento con un botón que sigue la pantalla a medida que esta sube o baja.

PROBLEMA 3: En la vista de freelancer, al seleccionar la categoría y/o subcategoría, el despliegue de opciones solo muestra la opción de “Select a Category” y “Select a Subcategory” respectivamente.

Severidad: 2  
Heurística violada: Information Architecture: Is it usable?

Problema:  
En la página de crear gig en la vista de freelancer, al seleccionar la categoría y/o subcategoría, el despliegue de opciones solo muestra la opción de “Select a Category” y “Select a Subcategory” respectivamente.

<img src="imgs/ProblemaHeu3.png" alt="ProblemaHeu3" title="ProblemaHeu3"/>

Recomendación:  
Brindar una lista más amplia de categorías disponibles para que el usuario freelancer pueda categorizar correctamente sus “gigs”.

PROBLEMA 4: El botón de “My Orders” en la vista del Buyer no cambia de página al ser presionado.

Severidad: 4  
Heurística violada: Information Architecture: Is it usable?

Problema:  
En la página principal cuando el usuario se encuentra en la vista de “Buyer”, al presionar el botón de  “My Orders”, la página no lleva a otra sección que contenga las órdenes del “Buyer”/

<img src="imgs/ProblemaHeu4.png" alt="ProblemaHeu4" title="ProblemaHeu4"/>

Recomendación:  
Implementar una página que le permita al usuario Buyer poder revisar las órdenes que tiene.

PROBLEMA 5: En pestaña de gigs disponibles, al interactuar con una de ellas los botones de la parte superior que tienen el overview, la  descripción, el about the seller, el compare packages, el recommendations y el reviews no funciona correctamente.

Severidad: 2  
Heurística violada: Information Architecture: Is it usable?

Problema:  
Al estar en la página principal, luego de interactuar con una de las tarjetas que contienen los gigs disponibles, los botones de la parte superior que tienen el overview, la  descripción, el about the seller, el compare packages, el recommendations y el reviews no funciona correctamente.

<img src="imgs/ProblemaHeu5.png" alt="ProblemaHeu5" title="ProblemaHeu5"/>

Recomendación:  
Habilitar estos botones para que muestren la información necesaria o eliminarlos ya que la información ya se encuentra disponible en la sección de overview.


### **5.4. Video About-the-Product.**

El siguiente link corresponde al video promocional que resume nuestro modelo de negocio, los beneficios del producto y sus características.



https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310222_upc_edu_pe/ETWOnCw8v9hJkQClwVU_1MABNC1EgU-niEKYL8Dzh8yzcQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=DO3TRb

## Conclusiones
**- TB1:**
**GigU atiende una necesidad concreta en el entorno universitario y emprendedor**, ofreciendo una solución que permite a los estudiantes monetizar sus habilidades mientras adquieren experiencia profesional en un entorno real. A la vez, brinda a los emprendedores y pequeños empresarios acceso a talento joven, creativo y accesible, que puede cubrir tareas específicas sin los altos costos de una agencia o empleados fijos.


**La propuesta de valor de GigU va más allá de conectar usuarios**, ya que incorpora funcionalidades clave como cotización inteligente, visibilidad mediante portafolios, acuerdos formales y un sistema de pagos seguro. Esto no solo aumenta la confianza entre las partes, sino que también profesionaliza la experiencia freelance desde etapas tempranas, promoviendo relaciones laborales más justas, eficientes y formativas.

**- TP1:**
En la presente entrega nos enfocamos principalmente en mejorar la experiencia de usuario por medio de mejoras respecto al Landing Page y nuevas funciones para esta misma. Pulimos diversos aspectos respecto a la entrega anterior, mejorando además el diseño y organización del documento.

Implementamos el uso de un FakeAPI dentro de nuestra página con el objetivo de guardar la información de los usuarios de una manera más dinámica y funcional.

**- TB2:**
Para esta entrega, mejoramos diversos aspectos de las entregas pasadas teniendo en cuenta las correcciones brindadas en el Landing Page y el Front End, además iniciamos con el proceso del Back End de nuestro proyecto creando diferentes endpoints para satisfacer con las necesidades de nuestros servicios.

## Bibliografia

Empleo informal alcanza más del 85 % de jóvenes peruanos menores de. (2024, January 13). Radio Nacional. https://www.radionacional.gob.pe/noticias/economia/empleo-informal-alcanza-mas-del-85-de-jovenes-peruanos-menores-de-25-anos 

Vista de Jóvenes universitarios que trabajan        | Revista Peruana de Investigación Educativa. (n.d.). https://revistas.siep.org.pe/index.php/RPIE/article/view/388/388#:~:text=En%20el%20Per%C3%BA%2C%20para%20el,Ministerio%20de%20Educaci%C3%B3n%2C%202020a).



## Anexos

*Enlace del Prototipo*
https://www.figma.com/proto/uWjErNes085X9nT1QnwbG4/APPWEB-4371-Figma?node-id=1-4863&p=f&t=AUYuxuxOvdv1Z2d3-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A575

*Enlace del Video de Prototipo*
https://drive.google.com/file/d/198c49nDlMbolfklmcFJzCl5_C-Hjvktt/view?usp=drive_link

*Link Figma*
https://www.figma.com/design/uWjErNes085X9nT1QnwbG4/APPWEB-4371-Figma?node-id=0-1&t=7if5zvdwgHO5HRyS-1

*Link Repositorio Docs Github*
https://github.com/ASI0730-Final-Project/docs

*Link Organizacion Github*
https://github.com/ASI0730-Final-Project

*Link Landing Page*
https://asi0730-final-project.github.io/GigU-Landing/

*Link aplicacion web deployada(Firebase)*
https://gigu-3873a.web.app

*Link aplicacion web deployada-backend(Azure)*
https://gigu-appbackend-webapi-dqasbuf8fwe8dvf9.canadacentral-01.azurewebsites.net/swagger/index.html

*Link respectia de la database*
https://www.freesqldatabase.com/account/

*Link about the product*
https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310222_upc_edu_pe/ETWOnCw8v9hJkQClwVU_1MABNC1EgU-niEKYL8Dzh8yzcQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=DO3TRb
