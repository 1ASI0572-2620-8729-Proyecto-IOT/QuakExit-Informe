# Informe del Trabajo Final

<div>
  <p align="center"><img src="assets/images/upc-logo.png" alt="Logo UPC" width="150px" /></p>
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

1. [Capítulo I: Presentación](#capítulo-i-presentación)
  1.1. [Startup Profile](#11-startup-profile)
    1.1.1. [Descripción de la Startup](#111-descripción-de-la-startup)
    1.1.2. [Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  1.2. [Solution Profile](#12-solution-profile)
    1.2.1. [Antecedentes y problemática](#121-antecedentes-y-problemática)
    1.2.2. [Lean UX Process](#122-lean-ux-process)
      1.2.2.1. [Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      1.2.2.2. [Lean UX Assumptions](#1222-lean-ux-assumptions)
      1.2.2.3. [Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      1.2.2.4. [Lean UX Canvas](#1224-lean-ux-canvas)
  1.3. [Segmentos objetivo](#13-segmentos-objetivo)

2. [Capítulo II: Requirements Development and Software Solution Design](#capítulo-ii-requirements-development-and-software-solution-design)
  2.1. [Competidores](#21-competidores)
    2.1.1. [Análisis competitivo](#211-análisis-competitivo)
    2.1.2. [Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  2.2. [Entrevistas](#22-entrevistas)
    2.2.1. [Diseño de entrevistas](#221-diseño-de-entrevistas)
    2.2.2. [Registro de entrevistas](#222-registro-de-entrevistas)
    2.2.3. [Análisis de entrevistas](#223-análisis-de-entrevistas)
  2.3. [Needfinding](#23-needfinding)
    2.3.1. [User Personas](#231-user-personas)
    2.3.2. [User Task Matrix](#232-user-task-matrix)
    2.3.3. [User Journey Mapping](#233-user-journey-mapping)
    2.3.4. [Empathy Mapping](#234-empathy-mapping)
  2.4. [Big Picture EventStorming](#235-big-picture-eventstorming)
  2.5. [Ubiquitous Language](#236-ubiquitous-language)

3. [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  3.1. [User Stories](#31-user-stories)
  3.2. [Impact Mapping](#32-impact-mapping)
  3.3. [Product Backlog](#33-product-backlog)

4. [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  4.1. [Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
    4.1.1. [Design-Level EventStorming](#411-design-level-eventstorming)
      4.1.1.1 [Candidate Context Discovery](#4111-candidate-context-discovery)
      4.1.1.2 [Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
      4.1.1.3 [Bounded Context Canvases](#4113-bounded-context-canvases)
    4.1.2. [Context Mapping](#412-context-mapping)
    4.1.3. [Software Architecture](#413-software-architecture)
      4.1.3.1. [Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
      4.1.3.2. [Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
      4.1.3.3. [Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
      4.1.3.4. [Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
  4.2. [Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
    4.2.1. [Bounded Context: <Bounded Context Name>](#421-bounded-context-context)
      4.2.1.1. [Domain Layer](#4211-domain-layer)
      4.2.1.2. [Interface Layer](#4212-interface-layer)
      4.2.1.3. [Application Layer](#4213-application-layer)
      4.2.1.4. [Infrastructure Layer](#4214-infrastructure-layer)
      4.2.1.5. [Bounded Context Software Architecture Component Level Diagrams](#4215-bounded-context-software-architecture-component-level-diagrams)
      4.2.1.6. [Bounded Context Software Architecture Code Level Diagrams](#4216-bounded-context-software-architecture-code-level-diagrams)
        4.2.1.6.1. [Bounded Context Domain Layer Class Diagrams](#42161-bounded-context-domain-layer-class-diagrams)
        4.2.1.6.2. [Bounded Context Database Design Diagram](#42162-bounded-context-database-design-diagram)
   
5. [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-ui/ux-design)
  5.1. [Style Guidelines](#51-style-guidelines)
    5.1.1. [General Style Guidelines](#511-general-style-guidelines)
    5.1.2. [Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
  5.2. [Information Architecture](#52-information-architecture)
    5.2.1. [Organization Systems](#521-organization-systems)
    5.2.2. [Labeling Systems](#522-labeling-systems)
    5.2.3. [SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
    5.2.4. [Searching Systems](#524-searching-systems)
    5.2.5. [Navigation Systems](#525-navigation-systems)
  5.3. [Landing Page UI Design](#53-landing-page-ui-design)
    5.3.1. [Landing Page Wireframe](#531-landing-page-wireframe)
    5.3.2. [Landing Page Mock-up](#532-landing-page-mock-up)
  5.4. [Applications UX/UI Design](#54-applications-ux/ui-design)
    5.4.1. [Applications Wireframes](#541-applications-wireframes)
    5.4.2. [Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
    5.4.3. [Applications Mock-ups](#543-applications-mock-ups)
    5.4.4. [Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
  5.5. [Applications Prototyping](#55-applications-prototyping)
  5.6. [IoT Device Design](#56-iot-device-design)

6. [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation-&-deployment)
  6.1. [Software Configuration Management](#61-software-configuration-management)
    6.1.1. [Software Development Environment Configuration](#611-software-development-environment-configuration)
    6.1.2. [Source Code Management](#612-source-code-management)
    6.1.3. [Source Code Style Guide & Conventions](#613-source-code-style-guide-&-conventions)
    6.1.4. [Software Deployment Configuration](#614-software-deployment-configuration)
  6.2. [Landing Page, Services & Applications Implementation](#62-landing-page-services-&-applications-implementation)
    6.2.1. [Sprint n](#621-sprint-n)
      6.2.1.1. [Sprint Planning n](#6211-sprint-planning-n)
      6.2.1.2. [Aspect Leaders and Collaborators](#6212-aspect-leaders-and-collaborators)
      6.2.1.3. [Sprint Backlog n](#6213-sprint-backlog-n)
      6.2.1.4. [Development Evidence for Sprint Review](#6214-development-evidence-for-sprint-review)
      6.2.1.5. [Testing Suite Evidence for Sprint Review](#6215-testing-suite-evidence-for-sprint-review)
      6.2.1.6. [Execution Evidence for Sprint Review](#6216-execution-evidence-for-sprint-review)
      6.2.1.7. [Services Documentation Evidence for Sprint Review](#6217-services-documentation-evidence-for-sprint-review)
      6.2.1.8. [Software Deployment Evidence for Sprint Review](#6218-software-deployment-evidence-for-sprint-review)
      6.2.1.9. [Team Collaboration Insights during Sprint](#6219-team-collaboration-insights-during-sprint)
  6.3. [Validation Interviews](#63-validation-interviews)
    6.3.1. [Diseño de Entrevistas](#631-diseño-de-entrevistas)
    6.3.2. [Registro de Entrevistas](#632-registro-de-entrevistas)
    6.3.3. [Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
  6.4. [Video About-the-Product](#64-video-about-the-product)

[Conclusiones](#conclusiones)
[Recomendaciones](#recomendaciones)
[Video About-the-Team](#video-about-the-team)
[Bibliografía](#bibliografía)
[Anexos](#anexos)

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
| ![Diego] (imagen) | Diego Gabriel Requena Gutiérrez   | Ingeniería de Software | Tengo 19 años y curso el 5to ciclo en la Universidad Peruana de Ciencias Aplicadas. Soy una persona comprometida con mis objetivos, busco optimizar mi rendimiento y mantener un equilibrio entre la excelencia y una vida saludable.                       |


## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

#### Segmento objetivo #1:

#### Segmento objetivo #2:

<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.2. Estrategias y tácticas frente a competidores

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Segmento: .**

**Segmento: .**

### 2.2.2. Registro de entrevistas

**Segmento 1: .**

### 2.2.3. Análisis de entrevistas

**Segmento 1: .**

**Segmento 2: .**

## 2.3. Needfinding

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
