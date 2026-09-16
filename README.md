# Informe del Trabajo Final

<div>
  <p align="center"><img src="assets/cap1/logo/upc-logo.png" alt="Logo UPC" width="150px" /></p>
  <p align="center">Universidad Peruana de Ciencias Aplicadas</p>
  <p align="center">Facultad de Ingeniería</p>
  <p align="center">Carrera: Ingeniería de Software</p>
  <p align="center"><b>Periodo: 202620 </b></p>
  <p align="center">Código del curso: 1ASI0572 </p>
    <p align="center">Nombre del curso: Desarrollo de Soluciones IOT</p>
  <p align="center">NRC: 8729</p>
  <p align="center">Nombre del profesor: Marco Antonio Leon Baca</p>
  <p align="center"><b>Informe de Primer Avance</b></p>
  <p align="center">Nombre del startup: QuakExit</p>
  <p align="center">Nombre del producto: QuakExit</p>
</div>

---

<h3 align="center">Relación de integrantes</h3>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Código</th>
      <th>Apellidos y Nombres</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>U20231G159</td>
      <td>Castro Picón, Manuel Fernando Joao</td>
    </tr>
    <tr>
      <td>U20321774</td>
      <td>Requena Gutiérrez, Diego Gabriel</td>
    </tr>
    <tr>
      <td>U202213406</td>
      <td>Quiroz Zambrano, Fabrizio Javier</td>
    </tr>
    <tr>
      <td>U20231B475</td>
      <td>Solis Chang, Santiago Valentino</td>
    </tr>
    <tr>
      <td>U20231G054</td>
      <td>Vila Guillen, Miguel Angel</td>
    </tr>
    <tr>
      <td>U202213553</td>
      <td>De Las Casas Latour, Sebastián</td>
    </tr>
    <tr>
      <td>U202310129</td>
      <td>Navarro Correa, Cesar Augusto</td>
    </tr>
  </tbody>
</table>

</div>

<p align="center"><b>Tabla 0.1.</b> Relación de integrantes del equipo.</p>

<div>
  
  <p align="center"><b>Septiembre, 2026</b></p>
</div>

---

<div style="page-break-after: always;"></div>

## Registro de Versiones del Informe

## Project Report Collaboration Insights

### Contribuciones por integrante

<div style="page-break-after: always;"></div>

# Contenido

- [Capítulo I: Presentación](#capítulo-i-presentación)
  - 1.1. [Startup Profile](#11-startup-profile)
    - 1.1.1. [Descripción de la Startup](#111-descripción-de-la-startup)
    - 1.1.2. [Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - 1.2. [Solution Profile](#12-solution-profile)
    - 1.2.1. [Antecedentes y problemática](#121-antecedentes-y-problemática)
    - 1.2.2. [Lean UX Process](#122-lean-ux-process)
      - 1.2.2.1. [Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - 1.2.2.2. [Lean UX Assumptions](#1222-lean-ux-assumptions)
      - 1.2.2.3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - 1.2.2.4. [Lean UX Canvas](#1224-lean-ux-canvas)
  - 1.3. [Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)
  - 2.1. [Competidores](#21-competidores)
    - 2.1.1. [Análisis competitivo](#211-análisis-competitivo)
    - 2.1.2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - 2.2. [Entrevistas](#22-entrevistas)
    - 2.2.1. [Diseño de entrevistas](#221-diseño-de-entrevistas)
    - 2.2.2. [Registro de entrevistas](#222-registro-de-entrevistas)
    - 2.2.3. [Análisis de entrevistas](#223-análisis-de-entrevistas)
  - 2.3. [Needfinding](#23-needfinding)
    - 2.3.1. [User Personas](#231-user-personas)
    - 2.3.2. [User Task Matrix](#232-user-task-matrix)
    - 2.3.3. [User Journey Mapping](#233-user-journey-mapping)
    - 2.3.4. [Empathy Mapping](#234-empathy-mapping)
  - 2.4. [Big Picture EventStorming](#235-big-picture-eventstorming)
  - 2.5. [Ubiquitous Language](#236-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - 3.1. [User Stories](#31-user-stories)
  - 3.2. [Impact Mapping](#32-impact-mapping)
  - 3.3. [Product Backlog](#33-product-backlog)

- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - 4.1. [Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    - 4.1.1. [Design-Level EventStorming](#411-design-level-eventstorming)
      - 4.1.1.1. [Candidate Context Discovery](#4111-candidate-context-discovery)
      - 4.1.1.2. [Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      - 4.1.1.3. [Bounded Context Canvases](#4113-bounded-context-canvases)
    - 4.1.2. [Context Mapping](#412-context-mapping)
    - 4.1.3. [Software Architecture](#413-software-architecture)
      - 4.1.3.1. [Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      - 4.1.3.2. [Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      - 4.1.3.3. [Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
      - 4.1.3.4. [Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
  - 4.2. [Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    - 4.2.1. [Bounded Context: Bounded Context Name](#421-bounded-context-context)
      - 4.2.1.1. [Domain Layer](#4211-domain-layer)
      - 4.2.1.2. [Interface Layer](#4212-interface-layer)
      - 4.2.1.3. [Application Layer](#4213-application-layer)
      - 4.2.1.4. [Infrastructure Layer](#4214-infrastructure-layer)
      - 4.2.1.5. [Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      - 4.2.1.6. [Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
        - 4.2.1.6.1. [Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
        - 4.2.1.6.2. [Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)

- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-ui/ux-design)
  - 5.1. [Style Guidelines](#51-style-guidelines)
    - 5.1.1. [General Style Guidelines](#511-general-style-guidelines)
    - 5.1.2. [Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
  - 5.2. [Information Architecture](#52-information-architecture)
    - 5.2.1. [Organization Systems](#521-organization-systems)
    - 5.2.2. [Labeling Systems](#522-labeling-systems)
    - 5.2.3. [SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
    - 5.2.4. [Searching Systems](#524-searching-systems)
    - 5.2.5. [Navigation Systems](#525-navigation-systems)
  - 5.3. [Landing Page UI Design](#53-landing-page-ui-design)
    - 5.3.1. [Landing Page Wireframe](#531-landing-page-wireframe)
    - 5.3.2. [Landing Page Mock-up](#532-landing-page-mock-up)
  - 5.4. [Applications UX/UI Design](#54-applications-ux/ui-design)
    - 5.4.1. [Applications Wireframes](#541-applications-wireframes)
    - 5.4.2. [Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
    - 5.4.3. [Applications Mock-ups](#543-applications-mock-ups)
    - 5.4.4. [Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
  - 5.5. [Applications Prototyping](#55-applications-prototyping)
  - 5.6. [IoT Device Design](#56-iot-device-design)

- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation-&-deployment)
  - 6.1. [Software Configuration Management](#61-software-configuration-management)
    - 6.1.1. [Software Development Environment Configuration](#611-software-development-environment-configuration)
    - 6.1.2. [Source Code Management](#612-source-code-management)
    - 6.1.3. [Source Code Style Guide & Conventions](#613-source-code-style-guide-&-conventions)
    - 6.1.4. [Software Deployment Configuration](#614-software-deployment-configuration)
  - 6.2. [Landing Page, Services & Applications Implementation](#62-landing-page-services-&-applications-implementation)
    - 6.2.1. [Sprint n](#621-sprint-n)
      - 6.2.1.1. [Sprint Planning n](#6211-sprint-planning-n)
      - 6.2.1.2. [Aspect Leaders and Collaborators](#6212-aspect-leaders-and-collaborators)
      - 6.2.1.3. [Sprint Backlog n](#6213-sprint-backlog-n)
      - 6.2.1.4. [Development Evidence for Sprint Review](#6214-development-evidence-for-sprint-review)
      - 6.2.1.5. [Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
      - 6.2.1.6. [Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
      - 6.2.1.7. [Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
      - 6.2.1.8. [Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
      - 6.2.1.9. [Team Collaboration Insights during Sprint](#6219-team-collaboration-insights-during-sprint)
  - 6.3. [Validation Interviews](#63-validation-interviews)
    - 6.3.1. [Diseño de Entrevistas](#631-diseño-de-entrevistas)
    - 6.3.2. [Registro de Entrevistas](#632-registro-de-entrevistas)
    - 6.3.3. [Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
  - 6.4. [Video About-the-Product](#64-video-about-the-product)

- [Conclusiones](#conclusiones)
- [Recomendaciones](#recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<div style="page-break-after: always;"></div>

## Student Outcome


<div style="page-break-after: always;"></div>

# Capítulo I: Introducción

## 1.1 Startup Profile

### 1.1.1. Descripción de la Startup

NeuroDraw es una startup tecnológica emergente dedicada al diseño y desarrollo de soluciones integrales que fusionan el Internet de las Cosas (IoT) con el desarrollo de software orientado a la seguridad residencial. La empresa nace con el propósito de mitigar la vulnerabilidad de las personas frente a desastres naturales, específicamente eventos sísmicos, democratizando el acceso a sistemas de automatización que protegen la vida humana.

### 1.1.2. Perfiles de integrantes del equipo

| Foto                                                    | Nombres y Apellidos               | Carrera                | Descripción                                                                                                                                                                                                                                                 |
| ------------------------------------------------------- | --------------------------------- | ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Joao](imagen)    | Manuel Fernando Joao Castro Picón | Ingeniería de Software | Tengo 19 años y curso el 5to ciclo en la Universidad Peruana de Ciencias Aplicadas. Me gusta entrenar calistenia, escuchar música y jugar fútbol. Me considero responsable, adaptable al trabajo en equipo y con metas claras para ser un gran profesional. |
| ![Valentino](imagen)    | Santiago Valentino Solis Chang    | Ingeniería de Software | Tengo 20 años y curso el 5to ciclo en la Universidad Peruana de Ciencias Aplicadas. En mi tiempo libre disfruto jugar videojuegos, practicar tenis y aprender sobre programación web. Soy responsable, comprometido y capaz de trabajar en equipo.          |
| ![Miguel](imagen)  | Miguel Angel Vila Guillen         | Ingeniería de Software | Tengo 21 años y estudio el 6to ciclo en la Universidad Peruana de Ciencias Aplicadas. Me gusta jugar videojuegos, tocar la guitarra y el fútbol. Me considero capaz de trabajar en equipo y aspiro a ser un profesional competente.                         |
| ![Diego](assets/cap1/pfp-team/diegorequena1.jfif)  | Diego Gabriel Requena Gutiérrez   | Ingeniería de Software | Tengo 19 años y curso el 5to ciclo en la Universidad Peruana de Ciencias Aplicadas. Soy una persona comprometida con mis objetivos, busco optimizar mi rendimiento y mantener un equilibrio entre la excelencia y una vida saludable.                       |
| ![Sebastián](assets/cap1/pfp-team/sebastian.jpg)  | Sebastián De Las Casas Latour   | Ingeniería de Software | Tengo 22 años y curso el 8vo ciclo en la Universidad Peruana de Ciencias Aplicadas. Busco desarrollar mis competencias en análisis, diseño y construcción de soluciones de software, aplicando los conocimientos adquiridos durante mi formación académica.                       |


## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

El Perú se encuentra ubicado en el denominado Cinturón de Fuego del Pacífico, una de las zonas con mayor actividad telúrica del mundo. Específicamente para la ciudad de Lima y Callao, el Instituto Geofísico del Perú (IGP) y el Instituto Nacional de Defensa Civil (INDECI) han advertido sobre un "silencio sísmico" de aproximadamente 300 años en la costa central. Esta acumulación prolongada de energía proyecta la ocurrencia inminente de un terremoto de magnitud 8.8.

Según estimaciones recientes de INDECI, un evento de esta naturaleza afectaría a cerca de 7 millones de personas. El riesgo se agrava al considerar que, según expertos, aproximadamente el 70% de las viviendas en Lima presentan altos niveles de vulnerabilidad estructural debido a la autoconstrucción, uso de suelos inestables y falta de supervisión técnica. En este contexto de inminente riesgo estructural, la capacidad de evacuación inmediata en los primeros segundos del sismo es el factor determinante para preservar la vida de los ocupantes.

Las actuales alertas tempranas de sismos (como el sistema SISMATE o sensores sísmicos convencionales) cumplen un rol exclusivamente informativo. No están vinculadas a un ecosistema de respuesta física (Internet of Things) que accione mecanismos de salvaguarda, como el desbloqueo automático de chapas electromagnéticas o el encendido de señalización de emergencia.

Esta desconexión entre la alerta y la acción física obliga al usuario a depender de su propia respuesta manual bajo condiciones de visibilidad nula y estrés extremo, convirtiendo el propio sistema de seguridad anti-robos de la vivienda en una trampa mortal durante un desastre natural.

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement 1: Enfoque en el usuario final (Dueños de Smart Homes)**

El mercado actual de dispositivos para Smart Homes se centra principalmente en el confort (iluminación, entretenimiento) y la seguridad anti-robos. Sin embargo, hemos observado que los usuarios residenciales carecen de automatización frente a desastres naturales. Durante un sismo de gran magnitud, los propios sistemas de seguridad de la vivienda (cerraduras mecánicas o electrónicas sin protocolo de emergencia) se convierten en obstáculos. Esto causa pánico, desorientación en la oscuridad y retrasos críticos en la evacuación debido a la búsqueda de llaves manuales. ¿Cómo podemos integrar un protocolo de emergencia IoT en los hogares inteligentes que reaccione instantáneamente ante la actividad sísmica, automatizando el desbloqueo de vías de escape y guiando al usuario hacia un entorno seguro de forma autónoma?

**Problem Statement 2: Enfoque empresarial (Inmobiliarias y Constructoras)**

Las inmobiliarias desarrollan edificios multifamiliares modernos buscando ofrecer ventajas competitivas basadas en tecnología y seguridad. Actualmente, los protocolos de emergencia estructurales se limitan a las áreas comunes (alarmas contra incendios, rociadores), pero no se integran con los accesos privados de cada departamento. Esto genera cuellos de botella severos, ya que la evacuación depende de que cada residente logre destrabar su puerta manualmente bajo estrés. ¿Cómo podemos ofrecer a las inmobiliarias una solución IoT escalable e integrable desde la construcción que garantice el desbloqueo simultáneo y coordinado de las rutas de evacuación en todo el edificio durante un sismo, agregando valor comercial a sus proyectos inmobiliarios?

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions (Suposiciones de Negocio)**

  - Creemos que los dueños de Smart Homes preferirán adquirir QuakExit mediante un modelo de pago único que cubra el dispositivo y la instalación, en lugar de un modelo de suscripción mensual recurrente.
  - Creemos que las empresas inmobiliarias y constructoras percibirán un alto valor comercial en integrar la tecnología de QuakExit desde la fase de construcción para ofrecer departamentos con "seguridad sísmica inteligente" como ventaja competitiva.
  - Creemos que nuestro mercado objetivo inicial se encuentra en distritos de alta urbanización vertical en Lima (ej. Santiago de Surco), donde existe una mayor adopción tecnológica y preocupación por la seguridad en edificios.

**User Assumptions (Suposiciones del Usuario)**

  - Asumimos que el usuario priorizará su evacuación inmediata sobre el riesgo de intrusión física durante un evento sísmico de gran magnitud (es decir, aceptan que la puerta se desbloquee para poder huir).
  - Asumimos que los usuarios desconfiarían de un sistema que dependa puramente de la red eléctrica comercial, por lo que requerirán evidencia de que el dispositivo cuenta con autonomía energética (batería de respaldo) para sentirse seguros.
  - Asumimos que el usuario principal en un entorno B2C(negocio a consumidor) tiene conocimientos básicos de uso de aplicaciones móviles para recibir notificaciones y gestionar el estado del dispositivo.

**Technical Assumptions (Suposiciones Técnicas)**

  - Asumimos que las infraestructuras de red convencionales (Wi-Fi/Datos móviles) colapsarán durante el sismo, por lo que la acción crítica (el desbloqueo de cerraduras y activación de alarmas locales) debe ejecutarse mediante Edge Computing, operando de forma 100% offline en el microcontrolador.
  - Asumimos que el hardware puede mantenerse operando bajo un esquema de eficiencia energética (modos Deep Sleep) para prolongar la vida útil de la batería de respaldo sin comprometer la sensibilidad de detección.
  - Asumimos que para el MVP (maqueta universitaria), podremos simular estos escenarios críticos utilizando un microcontrolador (ej. ESP32/Arduino) y actuadores básicos (servomotores o relés para chapas electromagnéticas) que representen las puertas de la vivienda.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis Statement 01: Latencia de Evacuación**

**Creemos** que facilitaremos la evacuación inmediata y reduciremos el pánico de los usuarios si automatizamos el desbloqueo de las vías de escape. Lo **sabremos** **cuando** las pruebas de estrés en nuestra maqueta funcional demuestren que el microcontrolador y el actuador logran abrir la puerta en un tiempo menor a 5 segundos tras la activación del modo de emergencia.

**Hypothesis Statement 02: Resiliencia del Sistema**

**Creemos** que generaremos total confianza en la fiabilidad del sistema si garantizamos su funcionamiento ante los cortes de servicios básicos que ocurren durante un sismo. **Lo sabremos** **cuando** el 100% de las pruebas de activación en la maqueta resulten exitosas simulando una desconexión total de la red Wi-Fi y operando exclusivamente con la batería de respaldo.

**Hypothesis Statement 03: Alertas y Notificaciones**

**Creemos** que el usuario percibirá un alto valor de seguridad si está informado en tiempo real sobre el estado de su vivienda, incluso si no se encuentra en ella. **Lo sabremos cuando** el sistema logre enviar la notificación de "Modo Emergencia Activado" al celular del usuario inmediatamente después de procesar la detección del sismo (siempre que la red de internet siga disponible en los primeros segundos del evento).

**Hypothesis Statement 04: Aceptación de Mercado**

**Creemos** que el mercado residencial e inmobiliario está dispuesto a invertir en prevención automatizada. **Lo sabremos cuando** alcancemos las siguientes métricas en nuestras entrevistas de validación:

  - Al menos 8 de cada 10 personas (80%) afirmen estar dispuestos a adquirir e instalar la solución en sus hogares.

  - Obtengamos una respuesta positiva o intención de compra teórica por parte de representantes de al menos una firma inmobiliaria.

**Hypothesis Statement 05: Eficiencia Energética**

**Creemos** que el dispositivo será viable para su implementación a largo plazo si no requiere intervención constante del usuario para cargar su batería. **Lo sabremos cuando** demostremos mediante cálculos técnicos que el uso de modos de bajo consumo (Deep Sleep) en el microcontrolador permite una autonomía prolongada utilizando únicamente el módulo de energía de respaldo.

#### 1.2.2.4. Lean UX Canvas

Lean UX Canvas es una de las herramientas que hemos utilizado para comprender a nuestros posibles usuarios y sus necesidades. Esta es usada en el campo del diseño centrado en el usuario y la metodología Lean con la intención de desarrollar productos de forma eficientes y práctica para los usuarios. A su vez, esta puede ser utilizada por equipos multidisciplinarios para que colaboración de forma ordenada dentro un marco estructurado.

<div>
  <p align="center"><img src="assets/cap1/images/LeanUx/leanux_canvas.png" alt="Canvas" width="700px" /></p>
</div>

## 1.3. Segmentos objetivo

#### Segmento objetivo #1: Dueños de Smart Homes

Este segmento representa a los usuarios que adquirirán el sistema de forma individual para implementarlo en sus viviendas actuales. Hombres y mujeres de 30 a 55 años de edad, pertenecientes a los niveles socioeconómicos A y B. Generalmente son propietarios de la vivienda o arrendatarios de largo plazo, muchos de ellos con familias constituidas a su cargo. Tienen un perfil tecnológico en el cual no tienen miedo de incorporar nuevas tecnologías si estas demuestran mejorar su calidad de vida o brindarles tranquilidad.

#### Segmento objetivo #2: Inmobiliarias y Constructores

Este segmento permite la escalabilidad del proyecto al integrar el hardware de QuakExit directamente en los planos eléctricos de nuevos proyectos multifamiliares. Son empresas competitivas que buscan constantemente factores diferenciadores que aumenten el valor por metro cuadrado de sus departamentos y aceleren el proceso de venta. Compran tecnología por volumen (Economía de Escala). Buscan proveedores tecnológicos que ofrezcan integración sencilla desde la fase de construcción y que cumplan con las normativas de seguridad de INDECI. Les interesa ofrecer a sus clientes finales un concepto de "Seguridad Sísmica Inteligente" lista para usar desde la entrega de llaves.

---

<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

En este apartado analizaremos las posibles competencias para **QuakExit**, evaluando sus características clave, sus diferencias respecto a nuestra propuesta de valor de automatización IoT y sus limitaciones operativas durante un evento sísmico.

| Competidores | Características | Diferencias | Limitaciones |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[SISMATE](https://www.gob.pe/institucion/mtc/colecciones/532)** (Perú - INDECI / MTC) | - Sistema oficial del Estado peruano que difunde alertas masivas mediante tecnología Cell Broadcast en teléfonos móviles.<br>- Alerta temprana a nivel poblacional ante emergencias y desastres naturales.<br>- Cobertura masiva y de uso público. | - Enfoque estrictamente informativo e institucional.<br>- No se conecta con los dispositivos físicos o la infraestructura interna del hogar.<br>- Notifica a la población pero no acciona salidas. | - No resuelve el bloqueo físico de puertas ni la falta de luz en el inmueble.<br>- Genera alerta sonora pero deja al ciudadano a cargo de la evacuación manual.<br>- Dependencia de la infraestructura de telecomunicaciones pública. |
| **[SASSLA](https://www.sassla.mx/)** (México - Sistema de Alerta Temprana) | - App móvil de alerta sísmica en tiempo real basada en el Sistema de Alerta Sísmica Mexicano (SASMEX).<br>- Notifica con aviso sonoro prioritario que interrumpe el teléfono incluso en modo "no molestar".<br>- Muestra el tiempo estimado de llegada (ETA) y mapas de intensidad. | - Plataforma digital especializada en la interacción smartphone-usuario.<br>- Integración enfocada en la pantalla y altavoz del celular. | - Limitado al ámbito digital e informativo.<br>- No acciona mecanismos físicos de salvaguarda (cerraduras electromagnéticas o lucerías de emergencia).<br>- Inútil si el celular está lejos o si el usuario entra en pánico sin reaccionar. |
| **[ShakeAlert](https://www.shakealert.org/)** (EE. UU. - USGS) | - Sistema de alerta temprana para la costa oeste de EE. UU. administrado por el USGS.<br>- Emite señales para celulares e integra automatización con infraestructuras críticas (transporte, hospitales, bomberos). | - Dispone de algoritmos con capacidad de integración industrial e institucional a gran escala.<br>- Red de acelerómetros profesionales e infraestructura pública masiva. | - Solución orientada a la macro-infraestructura pública y empresarial.<br>- Costos de implementación inaccesibles para el sector residencial masivo.<br>- No comercializa un kit de domótica doméstico accesible para viviendas familiares. |

---

### 2.1.1. Análisis competitivo

| Criterio | SISMATE / SASPe (Perú) | SASSLA (México) | ShakeAlert (EE. UU.) |
| :--- | :--- | :--- | :--- |
| **Perfil: Descripción** | Sistema estatal peruano de difusión masiva de alertas tempranas vía mensajes Cell Broadcast en teléfonos celulares y sirenas urbanas ante desastres naturales. | Aplicación móvil y plataforma digital de alerta temprana de sismos basada en la red de sensores sísmicos de México (SASMEX). | Sistema de alerta sísmica temprana de la costa oeste de EE. UU. (USGS) que notifica a móviles e integra automatización en infraestructura pública. |
| **Ventaja Competitiva** | Cobertura nacional directa garantizada por el Estado peruano a través de concesionarias de telecomunicaciones, sin requerir saldo ni datos móviles. | Notificación de alta prioridad que interrumpe el teléfono móvil en modo "no molestar", con mapa de intensidad en tiempo real y cuenta regresiva estimada. | Infraestructura institucional sólida apoyada en redes sísmicas profesionales con capacidad de integrarse a gran escala con trenes, hospitales y bomberos. |
| **Perfil de Marketing: Mercado Objetivo** | Población general residente en el Perú con acceso a telefonía móvil o ubicada en zonas urbanas con sirenas públicas. | Ciudadanos, familias y organizaciones en zonas de alto riesgo sísmico en México con acceso a smartphones. | Instituciones públicas, empresas de transporte, servicios de emergencia y población general de la costa oeste de Estados Unidos (California, Oregón, Washington). |
| **Perfil de Marketing: Estrategias de marketing** | Difusión institucional mediante campañas públicas del MTC e INDECI en medios masivos (TV, radio, redes sociales) y pruebas técnicas nacionales. | Marketing digital enfocado en ASO (App Store Optimization), redes sociales, versión gratuita accesible y retención por alertas en tiempo real. | Alianzas gubernamentales, integración nativa en Android/iOS, comunicación académica mediante universidades (ej. UC Berkeley) e informes del USGS. |
| **Perfil de Producto: Productos & Servicios** | Alertas sonoras y de texto Cell Broadcast en teléfonos móviles; alertas comunitarias en torres con sirenas públicas urbanas. | Aplicación móvil (iOS/Android), notificaciones push de alerta rápida, mapas interactivos de intensidad sísmica y reportes post-evento. | Señales API de alerta temprana para apps móviles, integraciones con sistemas de transporte masivo, apertura de estaciones de bomberos y corte de energía. |
| **Perfil de Producto: Precios & Costos** | **Gratuito** (Servicio público estatal financiado con fondos gubernamentales). | **Freemium**; versión básica gratuita, suscripción Premium entre **$2.50 USD y $12.50 USD/año** (SASSLA Plus). | **Gratuito para el ciudadano**; financiamiento público gubernamental (inversión de capital del USGS mayor a **$39 M USD**). |
| **Perfil de Producto: Canales de Distribución** | Redes de telefonía móvil (Cell Broadcast/SMS) e infraestructura física estatal de sirenas públicas. | Tiendas de aplicaciones móviles (Google Play Store, Apple App Store) y plataforma web. | Integración a nivel del sistema operativo Android/iOS, apps asociadas (ej. MyShake) y conectores API institucionales. |
| **Análisis SWOT: Fortalezas** | Alcance masivo sin necesidad de conexión a internet; respaldo gubernamental e integración directa con operadoras. | Respuesta ultra rápida; excelente interfaz gráfica de usuario; alertas prioritarias que saltan bloqueos del smartphone. | Altísima precisión científica; respaldado por agencias federales de EE. UU.; amplia capacidad de automatización institucional. |
| **Análisis SWOT: Debilidades** | Totalmente pasivo/informativo; no acciona elementos físicos en el hogar; dependiente de la infraestructura de señal celular pública. | Sin interacción con hardware del inmueble (puertas/luces); ineficaz si el usuario entra en pánico o no está cerca del celular. | Inaccesible para el mercado residencial privado masivo por sus altos costos de infraestructura y enfoque macro-institucional. |
| **Análisis SWOT: Oportunidades** | Incorporación de protocolos de actuación para que empresas privadas desarrollen hardware IoT compatible con la señal estatal. | Integración futura con sistemas domóticos y de automatización para hogares o empresas. | Expansión de APIs públicas para el desarrollo de soluciones residenciales de seguridad física de última milla. |
| **Análisis SWOT: Amenazas** | Saturación o falla en torres de telecomunicaciones durante catástrofes; retrasos en la cobertura de sensores. | Desconexión a internet o caída de servidores durante picos de tráfico masivo por el terremoto. | Cambios en el presupuesto gubernamental federal y dependencia de la burocracia estatal para su actualización. |

---

### 2.1.2. Estrategias y tácticas frente a competidores

**Análisis FODA del proyecto: "QuakExit"**

**F (Fortalezas):** Integración física e inmediata de hardware IoT (desbloqueo automático de cerraduras electromagnéticas y activación de iluminación de emergencia) ejecutada en los primeros segundos del sismo, eliminando las barreras físicas en las rutas de evacuación residenciales.

**O (Oportunidades):** Alta vulnerabilidad en Lima y Callao ante el inminente riesgo sísmico de magnitud 8.8, sumado a la falta de respuesta física automatizada en los sistemas de alerta tradicionales (SISMATE/SASPe) y al alto porcentaje (~70%) de viviendas informales con rutas de salida complejas.

**D (Debilidades):** Requerimiento de instalación física de hardware en los inmuebles y dependencia de respaldo eléctrico local (baterías de emergencia) ante cortes inmediatos de energía provocados por el terremoto.

**A (Amenazas):** Resistencia inicial o desconfianza de los usuarios ante la automatización de accesos por temor a vulneraciones de seguridad patrimonial (robos), sumado a la eventual incursión de marcas consolidadas de domótica en el sector de gestión de desastres.

---

Para aprovechar las fortalezas y oportunidades de **QuakExit**, y al mismo tiempo mitigar sus debilidades y contrarrestar las amenazas del entorno competitivo, se establecen las siguientes estrategias y tácticas:

● **Integración con alertas gubernamentales:** Desarrollar módulos de software que sincronicen las señales de alerta masiva de SISMATE/SASPe vía APIs/Webhooks como gatilladores secundarios, garantizando una acción física instantánea en la vivienda.

● **Sistemas de hardware redundante y procesamiento local:** Diseñar el sistema con alimentación ininterrumpida (baterías de respaldo) y procesamiento *Edge Computing* para asegurar que las cerraduras y luces funcionen sin depender de conexión a internet o energía eléctrica durante el evento telúrico.

● **Certificación y protocolos de seguridad física (fail-safe):** Implementar mecanismos mecánicos y electrónicos de liberación automática ante fallos de energía, asegurando ante los usuarios que el sistema anti-robos no comprometa la evacuación en situaciones de emergencia.

● **Alianzas estratégicas con el sector inmobiliario y de seguros:** Comercializar paquetes de instalación prefabricados para proyectos de vivienda multifamiliar y gestionar reducciones en las primas de seguros de hogar para inmuebles equipados con QuakExit.

● **Pruebas de evacuación y demostraciones prácticas:** Realizar simulaciones en vivo que certifiquen la reducción del tiempo de evacuación en la oscuridad, evidenciando el impacto directo del sistema frente al silencio sísmico de la costa central.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Segmento 1: Dueños de Smart Homes**

Para evaluar las necesidades, hábitos de seguridad y percepciones de riesgo ante eventos sísmicos en el hogar, hemos desarrollado una serie de preguntas enfocadas en comprender la experiencia de los propietarios o arrendatarios de viviendas. El objetivo es identificar cómo reaccionan ante situaciones de emergencia, qué mecanismos de seguridad física poseen actualmente y su disposición hacia la automatización IoT para la evacuación inmediata en sus hogares.

Introducción:

Buenos días/tardes, soy [...], representante del proyecto **QuakExit**. Estamos desarrollando una solución tecnológica orientada a la seguridad residencial que automatiza el desbloqueo de accesos y la iluminación de emergencia durante sismos. Nos gustaría conocer tu experiencia sobre la seguridad en tu vivienda y cómo gestionas la preparación ante desastres naturales. Tu perspectiva será fundamental para diseñar un sistema adaptado a las necesidades reales de tu hogar.

Preguntas:

1. Para comenzar, ¿podrías presentarte brevemente e indicarnos en qué tipo de vivienda resides y con cuántas personas convives?
2. Ante la ocurrencia de un temblor o sismo nocturno, ¿cuáles son las primeras acciones que realizas junto a tu familia?
3. ¿Cuáles son los principales obstáculos o dificultades que percibes al momento de intentar evacuar tu vivienda durante una emergencia?
4. ¿Tu vivienda cuenta actualmente con cerraduras electrónicas, sistemas de domótica, alarmas anti-robos o iluminación de emergencia? ¿Cómo ha sido tu experiencia utilizándolos?
5. Durante un evento sísmico, ¿has experimentado fallas de luz o bloqueos en puertas que hayan dificultado la salida? ¿Cómo resolviste la situación?
6. ¿Qué tan seguro te sientes con los sistemas tradicionales de alerta sísmica (como SISMATE o alertas en el celular) en cuanto a su capacidad para facilitarte la evacuación física?
7. Si existiera un sistema IoT que detectara el sismo y automáticamente desbloqueara las puertas y encendiera luces de ruta hacia la salida, ¿qué valor aportaría a la seguridad de tu hogar?
8. ¿Qué temores o dudas te generaría delegar el desbloqueo de los accesos de tu casa a un sistema automatizado durante un sismo?
9. ¿Qué características o respaldos técnicos (por ejemplo, baterías de emergencia o botones mecánicos de respaldo) considerarías indispensables para confiar en esta tecnología?
10. ¿Estarías dispuesto a instalar un kit de automatización sísmica en tu vivienda actual? ¿Qué factores influirían en tu decisión de compra?

---

**Segmento 2: Inmobiliarias y Constructores**

Para evaluar las oportunidades de escalabilidad e integración técnica de la solución en la etapa de edificación, se han diseñado preguntas orientadas a ejecutivos, arquitectos e ingenieros del sector inmobiliario y de construcción. Estas preguntas buscan entender cómo incorporan criterios de seguridad sísmica e innovación tecnológica en sus proyectos multifamiliares, así como los criterios normativos y económicos que consideran al evaluar nuevos proveedores de hardware IoT.

Introducción:

Buenos días/tardes, soy [...], representante del proyecto **QuakExit**. Estamos desarrollando una solución de automatización IoT enfocada en la evacuación sísmica residencial, diseñada para integrarse directamente desde la etapa de construcción en proyectos inmobiliarios. Nos interesa conocer la visión de su empresa respecto a la inclusión de tecnología de seguridad en edificaciones y los estándares que manejan para ofrecer un factor diferenciador a sus clientes. Agradecemos su tiempo y colaboración.

Preguntas:

1. Para empezar, ¿podría contarnos sobre su rol en la empresa y el tipo de proyectos inmobiliarios o residenciales que desarrollan habitualmente?
2. ¿Qué tecnologías o elementos de diferenciación en seguridad e innovación suelen incorporar en sus proyectos para incrementar el valor por metro cuadrado?
3. ¿Cómo abordan actualmente el cumplimiento de las normativas de evacuación y seguridad sísmica exigidas por INDECI y el Reglamento Nacional de Edificaciones?
4. ¿Qué valor consideran que asigna el comprador final a las soluciones de "Seguridad Sísmica Inteligente" al momento de elegir un departamento?
5. ¿Han considerado o implementado previamente sistemas domóticos centralizados en las áreas comunes o departamentos de sus entregas? ¿Cuál fue la respuesta del mercado?
6. Al evaluar un nuevo proveedor de hardware IoT o infraestructura eléctrica para sus obras, ¿cuáles son los criterios clave (costo, facilidad de instalación, garantías, certificación) que determinan su elección?
7. ¿Qué desafíos técnicos o logísticos identifican al momento de integrar un sistema de desbloqueo automático y luces de emergencia en los planos eléctricos de un edificio en plano o construcción?
8. ¿Qué tipo de certificaciones, pruebas de carga o respaldos técnicos requerirían de un sistema como QuakExit para aprobar su instalación masiva en sus proyectos?
9. ¿Bajo qué modalidad comercial (compra por volumen para todo el edificio o equipamiento opcional para el cliente) consideran más viable la adopción de este tipo de tecnología?
10. ¿Estarían dispuestos a incluir este sistema como un estándar de seguridad en sus próximos lanzamientos inmobiliarios si demuestra acelerar la decisión de compra del cliente final?

---



### 2.2.2. Registro de entrevistas

**Segmento 1: Dueños de Smart Homes**

Entrevista N°1

● Nombre: Johan Karl Bottger Salazar

● Sexo: Masculino.

● Edad: 21.

● Estado Civil: Soltero.

● Labor: Estudiante.

Detalles de la entrevista:

● Duración: 05:56

[● Link: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213553_upc_edu_pe/IQA4QWZM8EVETJ0W6LLa3DucAbWG09Fp3dRKpKRR39FSXmE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=dQe3tg](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202213553_upc_edu_pe/IQA4QWZM8EVETJ0W6LLa3DucAbWG09Fp3dRKpKRR39FSXmE?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=dQe3tg)

<p align="center">
  <img src="assets/images/cap1/images/entrevistas/entrevista-segmento1-1.png" width="700">
</p>

Resumen de los puntos clave en la entrevista:

La entrevista con Johan destaca su perspectiva como joven estudiante residente en una vivienda con elementos tecnológicos. Durante la conversación, Johan detalla cómo le resultaría sumamente cómodo y útil contar con un sistema automatizado que se adapte a su hogar para emitir avisos y desbloquear las puertas de manera inmediata en caso de una emergencia sísmica. Al vivir en un entorno moderno, valora que una solución como QuakExit ofrezca una respuesta física rápida (desbloqueo de accesos) que elimine los obstáculos manuales y facilite la evacuación, brindándole mayor tranquilidad frente al riesgo de quedar encerrado.

Entrevista N°2

● Nombre: Veronica Geraldine Candela Picon.

● Sexo: Femenino.

● Edad: 24 años.

● Estado Civil: Soltera.

● Labor: Arquitecta de Interiores.

Detalles de la entrevista:

● Duración: --:--

[● Link: https://drive.google.com/file/d/10gpZrHKXRZATb-VCJ6RAm-Zu81CONRbT/view?usp=sharing](https://drive.google.com/file/d/10gpZrHKXRZATb-VCJ6RAm-Zu81CONRbT/view?usp=sharing)

Resumen de los puntos clave en la entrevista:

La entrevista con Lucía revela el temor real de los usuarios jóvenes que viven solos en departamentos modernos. Ella cuenta con una cerradura electrónica en su puerta principal y menciona que, durante un corte de luz reciente, tuvo problemas para abrir la puerta manualmente en la oscuridad. Ve un gran valor en QuakExit, ya que prioriza su capacidad de evacuación por encima del riesgo de robos durante un sismo. Destaca que la autonomía con batería de respaldo es el factor más crítico para que ella confíe en el sistema y decida comprarlo.

**Segmento 2: Inmobiliarias y Constructores**

Entrevista N°3

● Nombre: Mateo Alejandro Vargas Silva.

● Sexo: Masculino.

● Edad: 25 años.

● Estado Civil: Soltero.

● Labor: Ingeniero Civil - Supervisor de Obra.

Detalles de la entrevista:

● Duración: --:--

[● Link: https://drive.google.com/file/d/10gpZrHKXRZATb-VCJ6RAm-Zu81CONRbT/view?usp=sharing](https://drive.google.com/file/d/10gpZrHKXRZATb-VCJ6RAm-Zu81CONRbT/view?usp=sharing)

Resumen de los puntos clave en la entrevista:

Mateo trabaja supervisando proyectos multifamiliares y confirma que las inmobiliarias buscan constantemente tecnologías (como domótica básica) para aumentar el valor por metro cuadrado de los departamentos. Señala que actualmente solo se enfocan en las normativas básicas de áreas comunes, pero no en las rutas de escape privadas de cada departamento. Considera que QuakExit sería un excelente diferenciador comercial ("Seguridad Sísmica Inteligente"), siempre y cuando el sistema cuente con las certificaciones necesarias de INDECI y sea fácil de integrar en los planos eléctricos desde la etapa de construcción.

Entrevista N°4

● Nombre: Ariana Valentina Robles Huamani.

● Sexo: Femenino.

● Edad: 22.

● Estado Civil: Soltera.

● Labor: Asistente de Proyectos Inmobiliarios.

Detalles de la entrevista:

● Duración: --:--

[● Link: https://drive.google.com/file/d/1SRe3Ilrde37SMS8YGALvpk9OqU4jpwh0/view?usp=sharing](https://drive.google.com/file/d/1SRe3Ilrde37SMS8YGALvpk9OqU4jpwh0/view?usp=sharing)

Resumen de los puntos clave en la entrevista:

Valeria asiste en la fase de diseño y planificación de nuevos edificios. Resalta la importancia estética de las soluciones tecnológicas; para que QuakExit sea adoptado por su empresa, los dispositivos deben ser minimalistas y no afectar el diseño de interiores. Confirma que la seguridad sísmica es una pregunta frecuente de los compradores finales. Sugiere que el modelo de negocio ideal para ellos sería adquirir los kits de QuakExit por lotes grandes durante la fase final de acabados, incluyéndolos como un "upgrade" opcional o un estándar en proyectos premium.

---

### 2.2.3. Análisis de entrevistas

**Segmento 1: Dueños de Smart Homes**

Hallazgos:

● Existe un temor real y fundamentado frente a los cortes de luz durante un sismo, los cuales pueden trabar cerraduras electrónicas o mecánicas, dificultando la salida en la oscuridad.

● Los usuarios priorizan su integridad física y la capacidad de evacuar rápidamente por encima de los riesgos de intrusión o robos durante una emergencia.

● La principal condición técnica para que los usuarios confíen en el sistema es que cuente con autonomía energética (batería de respaldo) y no dependa de la red de internet o eléctrica del edificio.

● Valoran altamente que el sistema elimine los obstáculos físicos de manera automática (manos libres) y brinde iluminación de emergencia, lo que reduce el pánico y la desorientación.

● Muestran una alta disposición de compra si se les demuestra mediante pruebas que el sistema reacciona de forma inmediata y confiable.


Conclusión:

Los dueños y residentes de Smart Homes, especialmente aquellos que viven en departamentos o edificios multifamiliares, reconocen una vulnerabilidad crítica en sus sistemas de seguridad y accesos actuales ante desastres naturales. El miedo a quedar atrapados en la oscuridad por fallas eléctricas es latente. Por ello, están muy dispuestos a adoptar tecnologías como QuakExit, siempre y cuando estas garanticen una operatividad 100% offline e independiente mediante baterías de respaldo. Para este segmento, la tranquilidad de tener una ruta de evacuación asegurada, automática e iluminada en los primeros segundos de un sismo justifica plenamente la inversión, priorizando la vida sobre la protección patrimonial durante el evento.

**Segmento 2: Inmobiliarias y Constructores**

Hallazgos:

● Las empresas inmobiliarias buscan constantemente integrar nuevas tecnologías (como "Smart Apartments") para aumentar el valor por metro cuadrado y ofrecer factores diferenciadores frente a la competencia.

● Actualmente, la prevención sísmica y el cumplimiento de normativas (INDECI) se limitan estrictamente a las áreas comunes, dejando la responsabilidad de la evacuación de la puerta hacia adentro al cliente final.

● El concepto de "Seguridad Sísmica Inteligente" es percibido como un excelente argumento de ventas, ya que responde a una preocupación real y frecuente de los compradores finales en Lima.

● Los criterios decisivos para integrar un hardware a gran escala son: costo competitivo por volumen, facilidad de instalación en los planos eléctricos regulares, certificaciones formales de seguridad y un diseño estético/minimalista.

● Consideran viable la comercialización del sistema ya sea como un estándar integrado en proyectos premium, o como un paquete de mejora opcional (upgrade) en las fases de acabados.


Conclusión:

El sector de inmobiliarias y constructoras representa una oportunidad clave de escalabilidad comercial (B2B) para QuakExit. Los profesionales de este segmento están muy abiertos a incorporar innovaciones IoT que agilicen la toma de decisión de sus clientes y mejoren la percepción de exclusividad y seguridad de sus proyectos. Sin embargo, para que el sistema sea adoptado masivamente desde la etapa de construcción, la solución no solo debe ser funcional, sino que debe superar barreras operativas: requiere certificaciones que eviten problemas municipales, debe integrarse sin encarecer excesivamente los costos de obra, y su diseño físico debe ser discreto para no afectar la arquitectura de interiores. Si cumple estos requisitos, QuakExit se posiciona como una potente ventaja competitiva en el mercado inmobiliario.

## 2.3. Needfinding

Al recopilar toda la información de los segmentos objetivo y realizar las entrevistas se hará
un análisis de estos mismos haciendo uso de User Persona, Task Matrix, Journey Mapping,
Empathy Mapping y As-Is Scenario Mapping.

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

### 2.3.5. As-is Scenario Mapping

## 2.4. Ubiquitous Language

<div style="page-break-after: always;"></div>

# Capítulo III: Requirements Specification

## 3.1. User Stories

## 3.2. Impact Mapping

## 3.3. Product Backlog

<div style="page-break-after: always;"></div>

# Capitulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. Design-Level EventStorming 

#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2. Domain Message Flows Modeling

#### 4.1.1.3 Bounded Context Canvases

### 4.1.2. Context Mapping 

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3.4. Software Architecture Deployment Diagrams

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.1. Bounded Context: <Bounded Context Name>

#### 4.2.1.1. Domain Layer

#### 4.2.1.2. Interface Layer

#### 4.2.1.3. Application Layer

#### 4.2.1.4. Infrastructure Laye

#### 4.2.1.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.1.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.1.6.1. Bounded Context Domain Layer Class Diagrams

##### 4.2.1.6.2. Bounded Context Database Design Diagram

<div style="page-break-after: always;"></div>
