<div align="center">

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

## Facultad de IngenierÃ­a
### Carrera de IngenierÃ­a de Software

**CICLO:** 202601  
**CURSO:** Arquitecturas de Software Emergentes  
**SECCIÃ“N:** 10042  
**PROFESOR:** Royer Edelwer Rojas Malasquez

---

## INFORME DE TRABAJO FINAL

**Startup:** _Apex Twin_  
**Producto:** _SmartPark_

### Plataforma de gestiÃ³n inteligente de estacionamientos en centros comerciales basada en Digital Twins

---

### RelaciÃ³n de Integrantes

| CÃ³digo     | Apellidos y Nombres             |
|------------|---------------------------------|
| U202220829 | Riva Rodriguez, Elmer Augusto   |
| u202216263 | Morales Calderon, Hernan Emilio |
| U20211g671 | Qqueso Rodriguez, Britney Delhy |
| U202210973 | Sanchez Rios, Camila Cristina   |
| U202210297 | Valle Zuta, Abel AndrÃ©s         |

**Lima, PerÃº â€” Abril de 2026**

</div>

---

## Registro de Versiones del Informe

| VersiÃ³n | Fecha      | Autor      | DescripciÃ³n de modificaciÃ³n                                                      |
|---------|------------|------------|----------------------------------------------------------------------------------|
| TB1   | 24-04-2026 | <li>Riva Rodriguez, Elmer Augusto</li>  <li>Morales Calderon, Hernan Emilio</li> <li>Qqueso Rodriguez, Britney Delhy</li>  <li>Sanchez Rios, Camila Cristina</li> <li>Valle Zuta, Abel AndrÃ©s</li>| VersiÃ³n inicial del informe para entrega TB1. Incluye CapÃ­tulos I, II, III y IV. |
|         |            |            |                                                                                  |
|         |            |            |                                                                                  |

---

## Project Report Collaboration Insights

**URL del repositorio del informe:** `https://github.com/upc-pre-202601-1ASI0728-10042-smartpark/report`

**URL de la organizaciÃ³n GitHub:** `https://github.com/upc-pre-202601-1ASI0728-10042-smartpark`

### Repositorios de productos digitales

| Producto                   | Repositorio                                                                  |
|----------------------------|------------------------------------------------------------------------------|
| Landing Page               | `https://github.com/upc-pre-202601-1ASI0728-10042-smartpark/landing-page`    |
| Web Application (Operador) | `https://github.com/upc-pre-202601-1ASI0728-10042-smartpark/web-application` |
| Web Services (API)         | `https://github.com/upc-pre-202601-1ASI0728-10042-smartpark/web-services`    |
| IoT Simulator              | `https://github.com/upc-pre-202601-1ASI0728-10042-smartpark/iot-simulator`   |
| Mobile App (PowerApps)     | `https://github.com/upc-pre-202601-1ASI0728-10042-smartpark/mobile-app`      |

### Evidencias de colaboraciÃ³n

_(Para cada entrega, incluir: descripciÃ³n de cÃ³mo se han desarrollado las actividades, capturas de los analÃ­ticos de colaboraciÃ³n de GitHub Insights mostrando commits por miembro del equipo, grÃ¡fico de contribuciones, y evidencia de la aplicaciÃ³n de GitFlow y Conventional Commits.)_

#### TB1
_(Pendiente)_

#### TP1
_(Pendiente)_

#### TB2
_(Pendiente)_

#### TF1
_(Pendiente)_

---

## Tabla de Contenidos

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [CapÃ­tulo I: IntroducciÃ³n](#capÃ­tulo-i-introducciÃ³n)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. DescripciÃ³n de la Startup](#111-descripciÃ³n-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemÃ¡tica](#121-antecedentes-y-problemÃ¡tica)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [CapÃ­tulo II: Requirements Elicitation & Analysis](#capÃ­tulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. AnÃ¡lisis competitivo](#211-anÃ¡lisis-competitivo)
    - [2.1.2. Estrategias y tÃ¡cticas frente a competidores](#212-estrategias-y-tÃ¡cticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. DiseÃ±o de entrevistas](#221-diseÃ±o-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. AnÃ¡lisis de entrevistas](#223-anÃ¡lisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [CapÃ­tulo III: Requirements Specification](#capÃ­tulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [CapÃ­tulo IV: Strategic-Level Software Design](#capÃ­tulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
      - [4.1.2.1. Primary Functionality](#4121-primary-functionality)
      - [4.1.2.2. Quality Attribute Scenarios](#4122-quality-attribute-scenarios)
      - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Software Architecture Context Level Diagram](#432-software-architecture-context-level-diagram)
    - [4.3.3. Software Architecture Container Level Diagram](#433-software-architecture-container-level-diagram)
    - [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)
- [CapÃ­tulo V: Tactical-Level Software Design](#capÃ­tulo-v-tactical-level-software-design)
  - [5.1. Bounded Context: Parking Occupancy](#51-bounded-context-parking-occupancy)
    - [5.1.1. Domain Layer](#511-domain-layer)
    - [5.1.2. Interface Layer](#512-interface-layer)
    - [5.1.3. Application Layer](#513-application-layer)
    - [5.1.4. Infrastructure Layer](#514-infrastructure-layer)
    - [5.1.5. Bounded Context Software Architecture Component Level Diagrams](#515-bounded-context-software-architecture-component-level-diagrams)
    - [5.1.6. Bounded Context Software Architecture Code Level Diagrams](#516-bounded-context-software-architecture-code-level-diagrams)
      - [5.1.6.1. Bounded Context Domain Layer Class Diagrams](#5161-bounded-context-domain-layer-class-diagrams)
      - [5.1.6.2. Bounded Context Database Design Diagram](#5162-bounded-context-database-design-diagram)
  - [5.2. Bounded Context: Safety & Incidents](#52-bounded-context-safety--incidents)
    - [5.2.1. Domain Layer](#521-domain-layer)
    - [5.2.2. Interface Layer](#522-interface-layer)
    - [5.2.3. Application Layer](#523-application-layer)
    - [5.2.4. Infrastructure Layer](#524-infrastructure-layer)
    - [5.2.5. Bounded Context Software Architecture Component Level Diagrams](#525-bounded-context-software-architecture-component-level-diagrams)
    - [5.2.6. Bounded Context Software Architecture Code Level Diagrams](#526-bounded-context-software-architecture-code-level-diagrams)
  - [5.3. Bounded Context: Traffic Flow](#53-bounded-context-traffic-flow)
  - [5.4. Bounded Context: Energy Management](#54-bounded-context-energy-management)
  - [5.5. Bounded Context: Parking Session](#55-bounded-context-parking-session)
  - [5.6. Bounded Context: Notifications](#56-bounded-context-notifications)
  - [5.7. Bounded Context: Identity & Access Management](#57-bounded-context-identity--access-management)
  - [5.8. Bounded Context: Digital Twin Synchronization](#58-bounded-context-digital-twin-synchronization)
- [CapÃ­tulo VI: Solution UX Design](#capÃ­tulo-vi-solution-ux-design)
  - [6.1. Style Guidelines](#61-style-guidelines)
    - [6.1.1. General Style Guidelines](#611-general-style-guidelines)
    - [6.1.2. Web, Mobile & Devices Style Guidelines](#612-web-mobile--devices-style-guidelines)
  - [6.2. Information Architecture](#62-information-architecture)
    - [6.2.1. Organization Systems](#621-organization-systems)
    - [6.2.2. Labeling Systems](#622-labeling-systems)
    - [6.2.3. SEO Tags and Meta Tags](#623-seo-tags-and-meta-tags)
    - [6.2.4. Searching Systems](#624-searching-systems)
    - [6.2.5. Navigation Systems](#625-navigation-systems)
  - [6.3. Landing Page UI Design](#63-landing-page-ui-design)
    - [6.3.1. Landing Page Wireframe](#631-landing-page-wireframe)
    - [6.3.2. Landing Page Mock-up](#632-landing-page-mock-up)
  - [6.4. Applications UX/UI Design](#64-applications-uxui-design)
    - [6.4.1. Applications Wireframes](#641-applications-wireframes)
    - [6.4.2. Applications Wireflow Diagrams](#642-applications-wireflow-diagrams)
    - [6.4.3. Applications Mock-ups](#643-applications-mock-ups)
    - [6.4.4. Applications User Flow Diagrams](#644-applications-user-flow-diagrams)
  - [6.5. Applications Prototyping](#65-applications-prototyping)
- [CapÃ­tulo VII: Product Implementation, Validation & Deployment](#capÃ­tulo-vii-product-implementation-validation--deployment)
  - [7.1. Software Configuration Management](#71-software-configuration-management)
    - [7.1.1. Software Development Environment Configuration](#711-software-development-environment-configuration)
    - [7.1.2. Source Code Management](#712-source-code-management)
    - [7.1.3. Source Code Style Guide & Conventions](#713-source-code-style-guide--conventions)
    - [7.1.4. Software Deployment Configuration](#714-software-deployment-configuration)
  - [7.2. Solution Implementation](#72-solution-implementation)
    - [7.2.1. Sprint 1](#721-sprint-1)
      - [7.2.1.1. Sprint Planning 1](#7211-sprint-planning-1)
      - [7.2.1.2. Sprint Backlog 1](#7212-sprint-backlog-1)
      - [7.2.1.3. Development Evidence for Sprint Review](#7213-development-evidence-for-sprint-review)
      - [7.2.1.4. Testing Suite Evidence for Sprint Review](#7214-testing-suite-evidence-for-sprint-review)
      - [7.2.1.5. Execution Evidence for Sprint Review](#7215-execution-evidence-for-sprint-review)
      - [7.2.1.6. Services Documentation Evidence for Sprint Review](#7216-services-documentation-evidence-for-sprint-review)
      - [7.2.1.7. Software Deployment Evidence for Sprint Review](#7217-software-deployment-evidence-for-sprint-review)
      - [7.2.1.8. Team Collaboration Insights during Sprint](#7218-team-collaboration-insights-during-sprint)
    - [7.2.2. Sprint 2](#722-sprint-2)
      - [7.2.2.1. Sprint Planning 2](#7221-sprint-planning-2)
      - [7.2.2.2. Sprint Backlog 2](#7222-sprint-backlog-2)
      - [7.2.2.3. Development Evidence for Sprint Review](#7223-development-evidence-for-sprint-review)
      - [7.2.2.4. Testing Suite Evidence for Sprint Review](#7224-testing-suite-evidence-for-sprint-review)
      - [7.2.2.5. Execution Evidence for Sprint Review](#7225-execution-evidence-for-sprint-review)
      - [7.2.2.6. Services Documentation Evidence for Sprint Review](#7226-services-documentation-evidence-for-sprint-review)
      - [7.2.2.7. Software Deployment Evidence for Sprint Review](#7227-software-deployment-evidence-for-sprint-review)
      - [7.2.2.8. Team Collaboration Insights during Sprint](#7228-team-collaboration-insights-during-sprint)
    - [7.2.3. Sprint 3](#723-sprint-3)
      - [7.2.3.1. Sprint Planning 3](#7231-sprint-planning-3)
      - [7.2.3.2. Sprint Backlog 3](#7232-sprint-backlog-3)
      - [7.2.3.3. Development Evidence for Sprint Review](#7233-development-evidence-for-sprint-review)
      - [7.2.3.4. Testing Suite Evidence for Sprint Review](#7234-testing-suite-evidence-for-sprint-review)
      - [7.2.3.5. Execution Evidence for Sprint Review](#7235-execution-evidence-for-sprint-review)
      - [7.2.3.6. Services Documentation Evidence for Sprint Review](#7236-services-documentation-evidence-for-sprint-review)
      - [7.2.3.7. Software Deployment Evidence for Sprint Review](#7237-software-deployment-evidence-for-sprint-review)
      - [7.2.3.8. Team Collaboration Insights during Sprint](#7238-team-collaboration-insights-during-sprint)
  - [7.3. Validation Interviews](#73-validation-interviews)
    - [7.3.1. DiseÃ±o de Entrevistas](#731-diseÃ±o-de-entrevistas)
    - [7.3.2. Registro de Entrevistas](#732-registro-de-entrevistas)
    - [7.3.3. Evaluaciones segÃºn heurÃ­sticas](#733-evaluaciones-segÃºn-heurÃ­sticas)
  - [7.4. Video About-the-Product](#74-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-Team](#video-about-the-team)
- [BibliografÃ­a](#bibliografÃ­a)
- [Anexos](#anexos)
  - [Anexo A: Videos de Exposiciones](#anexo-a-videos-de-exposiciones)
  - [Anexo B: TÃ©rminos y Condiciones del Servicio](#anexo-b-tÃ©rminos-y-condiciones-del-servicio)
  - [Anexo C: ConfiguraciÃ³n de InternacionalizaciÃ³n (i18n) y Accesibilidad (a11y)](#anexo-c-configuraciÃ³n-de-internacionalizaciÃ³n-i18n-y-accesibilidad-a11y)
  - [Anexo D: DTDL Models de Azure Digital Twins](#anexo-d-dtdl-models-de-azure-digital-twins)

---

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET â€“ EAC - Student Outcome 3:** Capacidad de comunicarse efectivamente con un rango de audiencias.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET â€“ EAC - Student Outcome 3.

| Criterio especÃ­fico                                                                                                                                                                       | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                  | Conclusiones                                      |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------|
| **Comunica oralmente sus ideas y/o resultados con objetividad a pÃºblico de diferentes especialidades y niveles jerÃ¡rquicos, en el marco del desarrollo de un proyecto en ingenierÃ­a.**    | **_(Apellidos, Nombres del integrante 1)_**<br>**TB1**<br>_(Acciones especÃ­ficas realizadas)_<br><br>**TP1**<br>_(Acciones especÃ­ficas realizadas)_<br><br>**TB2**<br>_(Acciones especÃ­ficas realizadas)_<br><br>**TF1**<br>_(Acciones especÃ­ficas realizadas)_<br><br>**_(Apellidos, Nombres del integrante 2)_**<br>**TB1**<br>_(Acciones especÃ­ficas realizadas)_ | _(Conclusiones grupales acumulables por entrega)_ |
| **Comunica en forma escrita ideas y/o resultados con objetividad a pÃºblico de diferentes especialidades y niveles jerÃ¡rquicos, en el marco del desarrollo de un proyecto en ingenierÃ­a.** | **_(Apellidos, Nombres del integrante 1)_**<br>**TB1**<br>_(Acciones especÃ­ficas realizadas)_<br><br>**TP1**<br>_(Acciones especÃ­ficas realizadas)_                                                                                                                                                                                                                  | _(Conclusiones grupales acumulables por entrega)_ |

---

# CapÃ­tulo I: IntroducciÃ³n

## 1.1. Startup Profile

### 1.1.1. DescripciÃ³n de la Startup

_(DescripciÃ³n de la startup: nombre, misiÃ³n, visiÃ³n, valores, propuesta de valor Ãºnica, mercado objetivo, modelo de negocio. Incluir logo de la startup.)_

### 1.1.2. Perfiles de integrantes del equipo

| Foto       | Nombre completo        | CÃ³digo    | Carrera                | Aporte al equipo                                    |
|------------|------------------------|-----------|------------------------|-----------------------------------------------------|
| _(Imagen)_ | _(Apellidos, Nombres)_ | U20XXXXXX | IngenierÃ­a de Software | _(Conocimientos tÃ©cnicos y habilidades que aporta)_ |
| _(Imagen)_ | _(Apellidos, Nombres)_ | U20XXXXXX | IngenierÃ­a de Software | _(Conocimientos tÃ©cnicos y habilidades que aporta)_ |
| _(Imagen)_ | _(Apellidos, Nombres)_ | U20XXXXXX | IngenierÃ­a de Software | _(Conocimientos tÃ©cnicos y habilidades que aporta)_ |
| _(Imagen)_ | _(Apellidos, Nombres)_ | U20XXXXXX | IngenierÃ­a de Software | _(Conocimientos tÃ©cnicos y habilidades que aporta)_ |

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemÃ¡tica

_(Aplicar la tÃ©cnica The 5 'W's & 2 'H's para describir antecedentes y problemÃ¡tica.)_

#### What (Â¿QuÃ©?)
_(DescripciÃ³n del problema central.)_

#### When (Â¿CuÃ¡ndo?)
_(CuÃ¡ndo ocurre el problema, frecuencia, momentos crÃ­ticos.)_

#### Where (Â¿DÃ³nde?)
_(Contexto fÃ­sico, geogrÃ¡fico y digital donde ocurre.)_

#### Who (Â¿QuiÃ©n?)
_(Actores afectados: operadores de estacionamientos, conductores, administradores de centros comerciales.)_

#### Why (Â¿Por quÃ©?)
_(Causas raÃ­z del problema.)_

#### How (Â¿CÃ³mo?)
_(CÃ³mo se manifiesta el problema en la operaciÃ³n diaria.)_

#### How Much (Â¿CuÃ¡nto?)
_(Magnitud cuantitativa del problema: pÃ©rdidas econÃ³micas, tiempos perdidos, incidentes, etc.)_

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

**Problem Statement 1 â€” Operadores de Centros Comerciales**

_(Domain)_: La operaciÃ³n de estacionamientos en centros comerciales de gran escala...  
_(Customer Segments)_: Operadores de estacionamiento y administradores de seguridad...  
_(Pain Points)_: Falta de visibilidad integral en tiempo real, decisiones reactivas, ineficiencia energÃ©tica...  
_(Gap)_: Las soluciones existentes no integran ocupaciÃ³n, seguridad, flujo y energÃ­a en una vista espacial unificada...  
_(Vision/Strategy)_: Construir un gemelo digital 3D operacional como single pane of glass...  
_(Initial Segment)_: Centros comerciales de Lima Metropolitana con mÃ¡s de 500 plazas de estacionamiento...

**Problem Statement 2 â€” Conductores frecuentes de centros comerciales**

_(Domain)_: La experiencia de estacionamiento en centros comerciales...  
_(Customer Segments)_: Conductores que visitan centros comerciales semanalmente...  
_(Pain Points)_: Tiempo perdido buscando espacio, dificultad para localizar vehÃ­culo al regresar, desconocimiento de costo acumulado, falta de informaciÃ³n ante incidentes...  
_(Gap)_: Las apps existentes no ofrecen guÃ­a contextual ni alertas de seguridad georreferenciadas...  
_(Vision/Strategy)_: AplicaciÃ³n mÃ³vil low-code que entregue disponibilidad en tiempo real, registro de ubicaciÃ³n y alertas de seguridad...  
_(Initial Segment)_: Conductores entre 25-55 aÃ±os, NSE B/C, residentes en Lima...

#### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**

| ID | Assumption |
|---|---|
| BA-01 | _(Los operadores de centros comerciales estÃ¡n dispuestos a invertir en una plataforma de gestiÃ³n inteligente de estacionamientos.)_ |
| BA-02 | _(Los conductores adoptarÃ¡n una app mÃ³vil que reduzca su tiempo de bÃºsqueda de plaza.)_ |
| BA-03 | _(...)_ |

**User Assumptions**

| ID | Â¿QuiÃ©n es el usuario? | Â¿DÃ³nde encaja nuestro producto en su dÃ­a? | Â¿QuÃ© problemas resuelve? | Â¿CuÃ¡ndo y cÃ³mo lo usa? | Â¿QuÃ© features son importantes? | Â¿CÃ³mo deberÃ­a verse y comportarse? |
|---|---|---|---|---|---|---|
| UA-01 | _(Operador)_ | _(...)_ | _(...)_ | _(...)_ | _(...)_ | _(...)_ |
| UA-02 | _(Conductor)_ | _(...)_ | _(...)_ | _(...)_ | _(...)_ | _(...)_ |

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis 1**  
We believe that **_(business outcome esperado)_**  
will be achieved if **_(usuarios objetivo)_**  
attain **_(beneficio para el usuario)_**  
with **_(feature propuesto)_**.

**Hypothesis 2**  
We believe that...

**Hypothesis 3**  
We believe that...

#### 1.2.2.4. Lean UX Canvas

_(Insertar imagen del Lean UX Canvas v2 elaborado en Miro o LucidChart.)_

![Lean UX Canvas](assets/images/chapter-01/lean-ux-canvas.png)

## 1.3. Segmentos objetivo

### Segmento 1: Operadores de estacionamientos en centros comerciales

_(CaracterÃ­sticas demogrÃ¡ficas, perfil profesional, informaciÃ³n estadÃ­stica de sustento con citas.)_

### Segmento 2: Conductores frecuentes de centros comerciales

_(CaracterÃ­sticas demogrÃ¡ficas, hÃ¡bitos de consumo, informaciÃ³n estadÃ­stica de sustento con citas.)_

---

# CapÃ­tulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. AnÃ¡lisis competitivo

<table border="1" cellspacing="0" cellpadding="6"> 
  <tr> 
  <th colspan="5"> <b>Objetivo del anÃ¡lisis:</b> Identificar el posicionamiento competitivo de SmartPark en el mercado de soluciones tecnolÃ³gicas para la gestiÃ³n de estacionamientos en centros comerciales, entendiendo las ventajas diferenciales del gemelo digital frente a alternativas tradicionales y modernas. </th> </tr> <tr> <th></th> <th>SmartPark (Apex Twin)</th> <th>ParkingSoft (PerÃº)</th> <th>Parkimovil (LatinoamÃ©rica)</th> <th>TIBA Parking Systems (Global)</th> </tr> <tr> <th colspan="5"><b>PERFIL</b></th> </tr> <tr> <td><b>Overview</b></td> <td>Plataforma SaaS con gemelo digital 3D en tiempo real que integra ocupaciÃ³n, seguridad contra incendios, flujo vehicular y eficiencia energÃ©tica en una visualizaciÃ³n unificada. SoluciÃ³n nativa de nube sobre Azure Digital Twins.</th> <tr> <td>Sistema tradicional de control de acceso y gestiÃ³n de estacionamientos con hardware propietario (barreras, lectores de tickets, contadores). Enfoque en control de entrada/salida mÃ¡s que en operaciÃ³n interna.</th> <tr> <td>SoluciÃ³n mobile-first para conductores que muestra disponibilidad de plazas y permite reservas. Orientada al usuario final, no al operador del centro comercial. Carece de gemelo digital o integraciÃ³n con sensores de seguridad.</th> <tr> <td>Multinacional con hardware y software integrado para estacionamientos automatizados (LPR, sistemas de guiado por luces LED, cÃ¡maras). SÃ³lida presencia en centros comerciales de alta gama, pero sin capa de gemelo digital ni analÃ­tica predictiva.</th> </tr> <tr> <th colspan="5"><b>PERFIL DE MARKETING</b></th> </tr> <tr> <td><b>Mercado objetivo</b></th> <td>Centros comerciales de gran escala en Lima, con proyecciÃ³n a PerÃº, Colombia y Chile hacia 2029. Segmento primario: operadores (jefes de operaciones, facility managers). Segmento secundario: conductores frecuentes.</th> <td>Centros comerciales medianos y grandes en PerÃº (Lima y provincias). Clientes actuales: Real Plaza, MegaPlaza, Mall Aventura. Foco exclusivo en operadores.</th> <td>Centros comerciales y estacionamientos pÃºblicos en MÃ©xico, Colombia y Chile. Foco casi exclusivo en conductores (usuarios B2C), no en operadores B2B.</th> <td>Centros comerciales de lujo, aeropuertos y hospitales a nivel global (presente en 35 paÃ­ses). En PerÃº: Jockey Plaza, Larcomar. Segmento premium con alta inversiÃ³n en hardware.</th> </tr> <tr> <td><b>Estrategias de marketing</b></th> <td>Marketing digital B2B (LinkedIn, casos de Ã©xito), demostraciones gratuitas del gemelo digital, alianzas con integradores de IoT locales (Claro IoT, Movistar Empresas), participaciÃ³n en eventos de PropTech y Smart Buildings.</th> <td>Fuerza de ventas directa en Lima y principales ciudades, presencia en ferias de seguridad y tecnologÃ­a para retail (Expofacility, PERUMIN). Relaciones de largo plazo con constructoras de centros comerciales.</th> <td>Marketing B2C agresivo (App Store, Google Play, influencers de automovilismo), alianzas con marcas de autos y estaciones de servicio. Limitada penetraciÃ³n en el canal B2B de centros comerciales.</th> <td>Marketing tradicional B2B con alto componente de demostraciÃ³n tÃ©cnica, presencia en ferias internacionales (Parking Expo, Intertraffic), fuerza de ventas global con partners locales en PerÃº (Grupo Viatek).</th> </tr> <tr> <th colspan="5"><b>PERFIL DE PRODUCTO</b></th> </tr> <tr> <td><b>Productos & Servicios</b></th> <td><b>SmartPark Web (Operador):</b> Gemelo digital 3D, mapa de ocupaciÃ³n en tiempo real, geolocalizaciÃ³n de alertas de humo, mapa de calor de flujo vehicular, recomendaciones de eficiencia energÃ©tica.<br> <b>SmartPark App (Conductor):</b> Consulta de plazas libres, registro de ubicaciÃ³n vÃ­a QR, monitoreo de costo acumulado, notificaciones push de seguridad.</th> <td><b>ParkingSoft Core:</b> Sistema de control de acceso (tickets, tarjetas RFID), contadores de vehÃ­culos por nivel, reportes de ocupaciÃ³n histÃ³rica, facturaciÃ³n electrÃ³nica.<br> <b>ParkingSoft Lite:</b> VersiÃ³n reducida para estacionamientos pequeÃ±os sin integraciÃ³n de sensores.</th> <td><b>Parkimovil Driver:</b> App para conductores con mapa de disponibilidad, reserva de plazas (pago anticipado), navegaciÃ³n interna hacia la plaza, historial de estacionamientos.<br> <b>Parkimovil Manager (bÃ¡sico):</b> Panel web simple con ocupaciÃ³n agregada por nivel, sin visualizaciÃ³n espacial.</th> <td><b>TIBA ParCS:</b> Sistema de control de acceso con LPR (lectura de placas), emisiÃ³n de tickets, integraciÃ³n con sistemas de guiado por luces LED en cada plaza.<br> <b>TIBA Fleet:</b> MÃ³dulo para flotas corporativas.<br> <b>TIBA Analytics:</b> Reportes histÃ³ricos de ocupaciÃ³n, sin tiempo real ni gemelo digital.</th> </tr> <tr> <td><b>Precios & Costos</b></th> <td>Modelo SaaS por suscripciÃ³n mensual por centro comercial:<br> - <b>Basic</b> (hasta 500 plazas): USD 499/mes<br> - <b>Professional</b> (hasta 1,500): USD 999/mes<br> - <b>Enterprise</b> (>1,500): USD 1,999/mes<br> App conductores: freemium (gratis con publicidad o USD 2.99/mes sin anuncios y reservas prioritarias).</th> <td>Licenciamiento perpetuo + mantenimiento anual (15-20% del valor de licencia):<br> - <b>PequeÃ±o</b> (hasta 300 plazas): USD 8,000 - 12,000 licencia<br> - <b>Mediano</b> (300-1,000): USD 15,000 - 25,000<br> - <b>Grande</b> (>1,000): USD 30,000 - 50,000<br> Hardware adicional (barreras, lectores): USD 5,000 - 15,000 por acceso.</th> <td>Modelo freemium para conductores (gratis con anuncios). Ingresos por:<br> - <b>Reservas pagadas:</b> 10% de comisiÃ³n sobre el monto reservado<br> - <b>Plan Premium para conductores:</b> USD 4.99/mes (reservas ilimitadas sin publicidad)<br> - <b>Panel Manager para operadores:</b> USD 299/mes por centro comercial (funcionalidades limitadas).</th> <td>Licenciamiento perpetuo (hardware + software) con costos elevados:<br> - <b>Por plaza monitoreada:</b> USD 800 - 1,500 (incluye sensor LED, LPR, controlador)<br> - <b>Centro comercial de 1,500 plazas:</b> USD 1.2M - 2.2M iniciales<br> Mantenimiento anual: 12-18% del valor total.<br> MÃ³dulo de analÃ­tica: USD 15,000 - 30,000 adicional.</th> </tr> <tr> <td><b>Canales de distribuciÃ³n</b></th> <td>Web (Angular) y mÃ³vil (PowerApps + Firebase) vÃ­a Microsoft AppSource y Google Play Store. Despliegue en Azure con opciÃ³n on-premise controlada. ImplementaciÃ³n remota asistida en 2-3 semanas.</th> <td>Software instalado en servidores locales del cliente (on-premise) con hardware propietario. ImplementaciÃ³n presencial en 4-8 semanas por integrador certificado.</th> <td>MÃ³vil (iOS/Android) vÃ­a App Store y Google Play. Panel web accesible desde cualquier navegador. Sin hardware adicional requerido. ImplementaciÃ³n en 1 semana (autogestionada).</th> <td>Hardware y software integrado instalado por personal tÃ©cnico de TIBA o partners certificados. ImplementaciÃ³n presencial en 8-16 semanas (incluye obra civil para sensores LED).</th> </tr> <tr> <th colspan="5"><b>AnÃ¡lisis SWOT (Fortalezas, Debilidades, Oportunidades, Amenazas)</b></th> </tr> <tr> <td><b>Fortalezas</b></th> <td>- <b>Ãšnico con gemelo digital 3D en tiempo real</b> integrando 4 dimensiones operativas (ocupaciÃ³n, seguridad, flujo, energÃ­a)<br> - <b>Contexto espacial para alertas de humo</b> (localizaciÃ³n exacta vs seÃ±al genÃ©rica)<br> - <b>Modelo SaaS de bajo costo inicial</b> (sin inversiÃ³n en hardware)<br> - <b>ProyecciÃ³n a eficiencia energÃ©tica</b> (ahorro 15-25% en iluminaciÃ³n)<br> - <b>Dos productos en uno</b> (operador web + conductor app)</th> <td>- <b>Amplia base instalada en PerÃº</b> (presencia en 15+ centros comerciales)<br> - <b>Relaciones consolidadas con constructoras</b> (entrada temprana en nuevos proyectos)<br> - <b>Soporte local presencial</b> (respuesta en menos de 4 horas)<br> - <b>IntegraciÃ³n con sistemas de facturaciÃ³n electrÃ³nica peruanos</b> (Sunat)</th> <td>- <b>Gran base de usuarios conductores</b> (>500,000 descargas en LatinoamÃ©rica)<br> - <b>Modelo freemium efectivo</b> (alta adopciÃ³n B2C)<br> - <b>UI/UX muy pulida y gamificada</b><br> - <b>Reserva anticipada de plazas</b> (diferenciador clave para conductores)</th> <td>- <b>Liderazgo tecnolÃ³gico global</b> (LPR de alta precisiÃ³n, sensores LED robustos)<br> - <b>Estabilidad y confiabilidad probada</b> (99.95% de uptime en instalaciones)<br> - <b>Capacidad de manejar altos volÃºmenes</b> (>5,000 vehÃ­culos/hora)<br> - <b>Marca reconocida a nivel mundial</b> (aval de centros comerciales premium)</th> </tr> <tr> <td><b>Debilidades</b></th> <td>- <b>Marca desconocida en el mercado peruano</b> (startup sin clientes reales aÃºn)<br> - <b>Dependencia de sensores IoT simulados</b> (en fase inicial, sin validaciÃ³n con hardware real)<br> - <b>Curva de aprendizaje para operadores</b> (gemelo digital 3D puede intimidar al inicio)<br> - <b>Sin integraciÃ³n con sistemas de facturaciÃ³n electrÃ³nica</b> (requerimiento clave en PerÃº)</th> <td>- <b>TecnologÃ­a legacy</b> (sistemas on-premise difÃ­ciles de actualizar)<br> - <b>Sin visualizaciÃ³n 3D ni gemelo digital</b> (paneles 2D tradicionales)<br> - <b>Alertas de seguridad sin contexto espacial</b> (solo seÃ±al genÃ©rica por nivel)<br> - <b>Alto costo inicial de licencia</b> (barrera para centros comerciales medianos)</th> <td>- <b>Sin soluciÃ³n para operadores avanzada</b> (panel web muy bÃ¡sico, sin analÃ­tica predictiva)<br> - <b>No integra sensores de humo ni eficiencia energÃ©tica</b><br> - <b>Dependencia de que el conductor tenga la app instalada</b> (penetraciÃ³n no universal)<br> - <b>Sin gemelo digital ni visualizaciÃ³n espacial para el operador</b></th> <td>- <b>Costo de inversiÃ³n inicial extremadamente alto</b> (solo viable para centros comerciales de lujo)<br> - <b>Dependencia de hardware propietario</b> (vendor lock-in, migraciÃ³n costosa)<br> - <b>Sin eficiencia energÃ©tica ni recomendaciones de iluminaciÃ³n</b><br> - <b>Tiempos de implementaciÃ³n largos</b> (8-16 semanas, interrupciÃ³n operativa)</th> </tr> <tr> <td><b>Oportunidades</b></th> <td>- <b>Crecimiento del mercado de centros comerciales en PerÃº</b> (7 nuevas aperturas 2023-2025)<br> - <b>Alta demanda post-pandemia de digitalizaciÃ³n</b> (operadores buscan eficiencia)<br> - <b>Posible integraciÃ³n con sistemas de facturaciÃ³n electrÃ³nica</b> (diferenciador local)<br> - <b>Alianzas con integradores IoT locales</b> (Claro, Movistar, Huawei)<br> - <b>ExpansiÃ³n a otros verticales</b> (aeropuertos, hospitales, universidades)</th> <td>- <b>MigraciÃ³n de centros comerciales pequeÃ±os a la nube</b> (costo de licencia perpetua es barrera)<br> - <b>AdopciÃ³n de sensores IoT de bajo costo</b> (pueden modernizar su oferta)<br> - <b>Alianzas con startups tecnolÃ³gicas</b> (para cerrar brecha de innovaciÃ³n)</th> <td>- <b>Convertirse en plataforma B2B completa</b> (adquiriendo o integrando tecnologÃ­a de gemelo digital)<br> - <b>ExpansiÃ³n a centros comerciales de primer nivel</b> (actualmente solo en medianos)<br> - <b>Ofrecer mÃ³dulo de eficiencia energÃ©tica</b> (diferenciador frente a SmartPark)</th> <td>- <b>Desarrollar versiÃ³n SaaS mÃ¡s accesible</b> (para centros comerciales medianos)<br> - <b>Integrar gemelo digital como servicio adicional</b> (aprovechando su hardware instalado)<br> - <b>Expandirse a mercados de LatinoamÃ©rica de menor poder adquisitivo</b> (con modelo de precios ajustado)</th> </tr> <tr> <td><b>Amenazas</b></th> <td>- <b>Competidores tradicionales (ParkingSoft, TIBA) con relaciones consolidadas</b><br> - <b>Competidores B2C (Parkimovil) capturando la relaciÃ³n con el conductor</b><br> - <b>Entrada de grandes tecnolÃ³gicas (AWS, Microsoft, Siemens) al mercado de gemelos digitales</b><br> - <b>Escepticismo de operadores sobre gemelos digitales</b> (percibidos como "sobreingenierÃ­a")<br> - <b>Ciclos de decisiÃ³n largos en centros comerciales</b> (6-12 meses)</th> <td>- <b>SmartPark y soluciones SaaS nativas de nube</b> (menor costo, mayor innovaciÃ³n)<br> - <b>Parkimovil capturando la relaciÃ³n con el conductor</b> (operador queda como mero proveedor de infraestructura)<br> - <b>TIBA ofreciendo mÃ³dulos de analÃ­tica mÃ¡s avanzados</b><br> - <b>Startups locales con gemelos digitales mÃ¡s econÃ³micos</b></th> <td>- <b>SmartPark ofreciendo funcionalidades de reserva similares</b> (pero integradas al operador)<br> - <b>Centros comerciales desarrollando sus propias apps</b> (integrando disponibilidad de plazas)<br> - <b>TIBA o ParkingSoft integrando reservas en sus sistemas</b><br> - <b>Regulaciones de protecciÃ³n de datos que limiten la geolocalizaciÃ³n</b></th> <td>- <b>SmartPark y startups con gemelos digitales a fracciÃ³n del costo</b><br> - <b>Centros comerciales optando por sensores IoT genÃ©ricos + desarrollo propio</b><br> - <b>Crisis econÃ³mica que reduzca inversiones en tecnologÃ­a de centros comerciales</b><br> - <b>Competidores chinos con hardware mÃ¡s econÃ³mico</b></th> </tr></table>

### 2.1.2. Estrategias y tÃ¡cticas frente a competidores

_(Estrategias y tÃ¡cticas preliminares que aplicarÃ¡ la startup para afrontar las fortalezas y aprovechar las debilidades de la competencia, asÃ­ como el contexto de oportunidades y amenazas.)_

## 2.2. Entrevistas

### 2.2.1. DiseÃ±o de entrevistas

#### Preguntas para Segmento 1: Operadores de estacionamiento

**Preguntas demogrÃ¡ficas y de contexto**
1. Â¿CuÃ¡l es su nombre, edad y cargo?
2. Â¿En quÃ© centro comercial trabaja y desde hace cuÃ¡nto?
3. Â¿QuÃ© tan grande es el estacionamiento que opera (cantidad de plazas, niveles)?

**Preguntas principales**
1. _(Â¿CÃ³mo monitorea actualmente el estado de ocupaciÃ³n del estacionamiento?)_
2. _(Â¿QuÃ© herramientas tecnolÃ³gicas utiliza dÃ­a a dÃ­a?)_
3. _(...)_

**Preguntas complementarias**
1. _(...)_

#### Preguntas para Segmento 2: Conductores

**Preguntas demogrÃ¡ficas y de contexto**
1. Â¿CuÃ¡l es su nombre, edad, distrito de residencia y ocupaciÃ³n?
2. Â¿Con quÃ© frecuencia visita centros comerciales?

**Preguntas principales**
1. _(Â¿CuÃ¡nto tiempo promedio invierte buscando estacionamiento?)_
2. _(Â¿Le ha pasado perder su vehÃ­culo dentro de un estacionamiento?)_
3. _(...)_

### 2.2.2. Registro de entrevistas

#### Segmento 1: Operadores

**Entrevista 1**

| Campo | Dato |
|---|---|
| Nombres y Apellidos | _(...)_ |
| Edad | _(...)_ |
| Distrito | _(...)_ |
| Cargo | _(...)_ |
| Fecha de entrevista | YYYY-MM-DD |
| URL del video (Microsoft Stream) | `https://...` |
| Timing inicio | HH:MM:SS |
| DuraciÃ³n | MM:SS |

_(Screenshot del video de entrevista)_

![Screenshot Entrevista 1 - Operador](assets/images/chapter-02/interview-operator-01.png)

**Resumen de la entrevista:**  
_(DescripciÃ³n detallada de las principales respuestas, incluyendo personalidad, marcas e influencias, tecnologÃ­a, canales de interacciÃ³n, browser, dispositivos.)_

**Entrevista 2 â€” Operador**  
_(Misma estructura)_

**Entrevista 3 â€” Operador**  
_(Misma estructura)_

#### Segmento 2: Conductores

**Entrevista 1 â€” Conductor**  
_(Misma estructura)_

**Entrevista 2 â€” Conductor**  
_(Misma estructura)_

**Entrevista 3 â€” Conductor**  
_(Misma estructura)_

### 2.2.3. AnÃ¡lisis de entrevistas

#### Segmento 1: Operadores

_(AnÃ¡lisis con sustento estadÃ­stico â€” porcentajes â€” de las caracterÃ­sticas objetivas y subjetivas mÃ¡s comunes encontradas. Cada caracterÃ­stica debe tener relaciÃ³n clara con las entrevistas registradas.)_

| CaracterÃ­stica | % | Sustento (entrevistas) |
|---|---|---|
| _(Edad promedio entre 35-50 aÃ±os)_ | _(80%)_ | _(E1, E2, E4)_ |
| _(Usa Excel para registro manual)_ | _(60%)_ | _(E1, E3, E5)_ |

#### Segmento 2: Conductores

_(Mismo formato de anÃ¡lisis para el segmento de conductores.)_

## 2.3. Needfinding

### 2.3.1. User Personas

_(IntroducciÃ³n explicando la relaciÃ³n entre los User Personas y las caracterÃ­sticas identificadas en el anÃ¡lisis de entrevistas y competencia.)_

#### User Persona 1: Operador de Estacionamiento

![User Persona Operador](assets/images/chapter-02/user-persona-operator.png)

#### User Persona 2: Conductor Frecuente

![User Persona Conductor](assets/images/chapter-02/user-persona-driver.png)

### 2.3.2. User Task Matrix

_(IntroducciÃ³n establecidiendo los segmentos considerados.)_

| Tarea | Operador (Frecuencia) | Operador (Importancia) | Conductor (Frecuencia) | Conductor (Importancia) |
|---|---|---|---|---|
| _(Verificar estado del estacionamiento)_ | Always | High | Often | Medium |
| _(Buscar plaza libre)_ | Never | N/A | Always | High |
| _(Atender alerta de incidente)_ | Sometimes | High | Sometimes | High |
| _(Ajustar iluminaciÃ³n por zona)_ | Often | Medium | Never | N/A |
| _(Recordar ubicaciÃ³n de vehÃ­culo)_ | Never | N/A | Always | High |
| _(...)_ | | | | |

_(AnÃ¡lisis post-tabla resaltando tareas con mayor frecuencia/importancia, diferencias y coincidencias entre User Personas.)_

### 2.3.3. Empathy Mapping

_(Resumen del proceso de elaboraciÃ³n. Capturas de los Empathy Maps elaborados en UXPressia para cada User Persona.)_

#### Empathy Map: Operador
![Empathy Map Operador](assets/images/chapter-02/empathy-map-operator.png)

#### Empathy Map: Conductor
![Empathy Map Conductor](assets/images/chapter-02/empathy-map-driver.png)

### 2.3.4. As-is Scenario Mapping

_(Resumen del proceso. Capturas de los As-Is Scenario Maps elaborados en LucidChart/Miro, con filas Phases, Doing, Thinking, Feeling.)_

#### As-Is Scenario Map: Operador
![As-Is Scenario Operador](assets/images/chapter-02/as-is-operator.png)

#### As-Is Scenario Map: Conductor
![As-Is Scenario Conductor](assets/images/chapter-02/as-is-driver.png)

## 2.4. Ubiquitous Language

_(Glosario de tÃ©rminos del business domain en inglÃ©s, sin ambigÃ¼edad. NO incluir tÃ©rminos tÃ©cnicos de ingenierÃ­a de software.)_

| Term (English) | TÃ©rmino (EspaÃ±ol) | DefiniciÃ³n |
|---|---|---|
| **Parking Space** | Plaza de estacionamiento | Unidad individual designada para el estacionamiento de un vehÃ­culo, identificada por cÃ³digo Ãºnico dentro de una zona y nivel. |
| **Parking Level** | Nivel de estacionamiento | DivisiÃ³n vertical del estacionamiento (sÃ³tano 1, sÃ³tano 2, primer piso, etc.) que agrupa zonas y plazas. |
| **Parking Zone** | Zona de estacionamiento | SubdivisiÃ³n de un nivel agrupando plazas con caracterÃ­sticas comunes (preferencial, discapacitados, mujeres, general). |
| **Occupancy State** | Estado de ocupaciÃ³n | Estado actual de una plaza: Free, Occupied, Reserved, OutOfService. |
| **Smoke Detector** | Detector de humo | Sensor IoT que monitorea presencia de humo en una zona especÃ­fica. |
| **Smoke Alert** | Alerta de humo | Evento generado cuando un detector excede su umbral, con localizaciÃ³n espacial. |
| **Evacuation Route** | Ruta de evacuaciÃ³n | Trayecto designado para evacuaciÃ³n segura, asociado a salidas de emergencia. |
| **Traffic Flow Counter** | Contador de flujo vehicular | Sensor que registra el paso de vehÃ­culos en accesos y rampas. |
| **Access Point** | Punto de acceso | Entrada o salida vehicular del estacionamiento. |
| **Ramp** | Rampa | ConexiÃ³n inclinada entre niveles del estacionamiento. |
| **Luminosity Level** | Nivel de luminosidad | Intensidad lumÃ­nica medida en una zona, expresada en lux. |
| **Lighting Zone** | Zona de iluminaciÃ³n | Conjunto de luminarias controlables como unidad para gestiÃ³n energÃ©tica. |
| **Parking Session** | SesiÃ³n de estacionamiento | PerÃ­odo entre el ingreso y salida de un vehÃ­culo, asociado a un conductor y una plaza. |
| **Vehicle Location** | UbicaciÃ³n de vehÃ­culo | PosiciÃ³n registrada (nivel, zona, plaza) donde un conductor estacionÃ³. |
| **Fare Rate** | Tarifa | Costo por unidad de tiempo aplicado a una sesiÃ³n de estacionamiento. |
| **Operator** | Operador | Personal del centro comercial responsable de la gestiÃ³n del estacionamiento. |
| **Driver** | Conductor | Usuario final que utiliza el estacionamiento del centro comercial. |
| **Digital Twin** | Gemelo digital | RepresentaciÃ³n virtual sincronizada del estado fÃ­sico del estacionamiento. |
| **Twin Model (DTDL)** | Modelo de gemelo | DefiniciÃ³n de la estructura y propiedades de una entidad en el grafo de Azure Digital Twins. |
| **Telemetry** | TelemetrÃ­a | Datos enviados por sensores (reales o simulados) hacia el gemelo digital. |
| **Incident** | Incidente | Evento anÃ³malo que requiere atenciÃ³n del operador (humo, congestiÃ³n, falla). |

---

# CapÃ­tulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

_(Resumen del proceso. Capturas de los To-Be Scenario Maps con identificaciÃ³n de cambios respecto al As-Is.)_

### To-Be Scenario Map: Operador
![To-Be Scenario Operador](assets/images/chapter-03/to-be-operator.png)

### To-Be Scenario Map: Conductor
![To-Be Scenario Conductor](assets/images/chapter-03/to-be-driver.png)

## 3.2. User Stories

_(IntroducciÃ³n al conjunto de Epics y User Stories. Recordar incluir: User Stories del Landing Page con rol "Visitor", User Stories de aplicaciones por User Persona, y Technical Stories con rol "Developer" para servicios tÃ©cnicos como APIs.)_

| Epic / Story ID | TÃ­tulo | DescripciÃ³n | Criterios de AceptaciÃ³n | Relacionado con (Epic ID) |
|---|---|---|---|---|
| EP-01 | Real-time Parking Occupancy Visualization | _(Como operador deseo visualizar el estado de ocupaciÃ³n en tiempo real para tomar decisiones operativas.)_ | _(N/A â€” agrupa US relacionadas)_ | â€” |
| US-01 | View 3D Parking Occupancy Map | Como operador deseo visualizar un mapa 3D del estacionamiento con el estado de ocupaciÃ³n de cada plaza para identificar visualmente los niveles de ocupaciÃ³n. | **Scenario 1: Visualization on dashboard load**<br>Given the operator is authenticated<br>When the operator navigates to the dashboard<br>Then the 3D map renders showing all parking spaces with color-coded occupancy state<br><br>**Scenario 2: Real-time update**<br>Given the 3D map is displayed<br>When a parking space changes its occupancy state<br>Then the 3D map updates the corresponding space color within 5 seconds | EP-01 |
| EP-02 | Smoke Incident Management | _(Como operador deseo gestionar alertas de humo con localizaciÃ³n espacial.)_ | â€” | â€” |
| US-02 | Receive Smoke Alert with Spatial Context | Como operador deseo recibir alertas de humo con la ubicaciÃ³n exacta en el modelo 3D para responder inmediatamente. | **Scenario 1: Smoke detected**<br>Given a smoke detector exceeds its threshold<br>When the system processes the telemetry<br>Then an alert is displayed within 2 seconds highlighting the affected zone in red on the 3D model | EP-02 |
| EP-03 | Parking Session Management for Drivers | _(Como conductor deseo gestionar mi sesiÃ³n de estacionamiento.)_ | â€” | â€” |
| US-03 | View Available Spaces by Zone | Como conductor deseo consultar la disponibilidad de espacios por zona o nivel para dirigirme al Ã¡rea con mayor disponibilidad. | **Scenario 1: View availability**<br>Given the driver is in the mobile app<br>When the driver opens the "Availability" view<br>Then the app displays the count of free spaces per zone and level updated within the last 30 seconds | EP-03 |
| US-04 | Register Vehicle Location | Como conductor deseo registrar la ubicaciÃ³n exacta donde estacionÃ© mi vehÃ­culo para localizarlo fÃ¡cilmente al regresar. | **Scenario 1: Registration**<br>Given the driver has parked<br>When the driver taps "Register location" and confirms the level and zone<br>Then the location is stored and associated with the driver's session | EP-03 |
| US-05 | Receive Safety Alerts Near Vehicle | Como conductor deseo recibir alertas de seguridad en la zona donde estÃ¡ mi vehÃ­culo con indicaciones de evacuaciÃ³n si fuera necesario. | **Scenario 1: Push notification on smoke alert**<br>Given the driver has an active session in zone Z<br>When a smoke alert is triggered in zone Z<br>Then the app receives a push notification with evacuation instructions within 5 seconds | EP-03 |
| EP-04 | Energy Management | _(Como operador deseo optimizar el consumo energÃ©tico basado en ocupaciÃ³n.)_ | â€” | â€” |
| US-06 | Identify Low-Occupancy Zones for Lighting Adjustment | Como operador deseo identificar zonas sin vehÃ­culos donde la iluminaciÃ³n pueda atenuarse para reducir consumo energÃ©tico. | **Scenario 1**<br>Given the dashboard is loaded<br>When the operator selects "Energy view"<br>Then zones with occupancy below 20% are highlighted with a recommendation to reduce lighting | EP-04 |
| EP-05 | Landing Page Communication | _(Como visitante deseo conocer la propuesta de valor.)_ | â€” | â€” |
| US-07 | View Landing Page as Mall Operator | Como visitante segmento operador deseo conocer cÃ³mo la plataforma resuelve la gestiÃ³n de mi estacionamiento para evaluar contratarla. | **Scenario 1**<br>Given the visitor lands on the home page<br>When the visitor scrolls to the "For Mall Operators" section<br>Then a CTA button "Request a Demo" is visible and clickable | EP-05 |
| US-08 | View Landing Page as Driver | Como visitante segmento conductor deseo conocer los beneficios de la app mÃ³vil para decidir descargarla. | **Scenario 1**<br>Given the visitor lands on the home page<br>When the visitor scrolls to the "For Drivers" section<br>Then a CTA button "Download the App" links to the PowerApps installation page | EP-05 |
| EP-06 | Technical APIs for Digital Twin Integration | â€” | â€” | â€” |
| TS-01 | Twin State Update Endpoint | Como developer deseo exponer un endpoint que actualice el estado de un twin en Azure Digital Twins para que el simulador IoT pueda enviar telemetrÃ­a. | **Scenario 1: Successful update**<br>Given a valid twin ID and JSON Patch payload<br>When the simulator sends PATCH /api/v1/twins/{id}<br>Then the system applies the patch and returns 204 No Content within 500ms<br><br>**Scenario 2: Invalid twin ID**<br>Given an unknown twin ID<br>When the simulator sends PATCH /api/v1/twins/{id}<br>Then the system returns 404 Not Found | EP-06 |
| TS-02 | Occupancy Query Endpoint | Como developer deseo exponer un endpoint que consulte ocupaciÃ³n agregada por zona/nivel para alimentar las apps. | **Scenario 1**<br>Given the operator is authenticated<br>When GET /api/v1/occupancy?level={n} is called<br>Then the response returns aggregated occupancy data with HTTP 200 | EP-06 |
| TS-03 | Push Notification Trigger | Como developer deseo integrar Firebase Cloud Messaging para enviar push notifications a la app PowerApps cuando se generen alertas. | **Scenario 1**<br>Given a smoke alert is generated in zone Z<br>When the notifications service identifies drivers with active sessions in Z<br>Then FCM messages are dispatched to all corresponding device tokens | EP-06 |

_(Continuar con el resto de User Stories y Technical Stories.)_

## 3.3. Impact Mapping

_(Resumen del proceso de elaboraciÃ³n. Capturas del Impact Map en UXPressia.)_

![Impact Map](assets/images/chapter-03/impact-map.png)

**Business Goals (SMART):**

- **BG-01:** Alcanzar 5 contratos con centros comerciales de Lima Metropolitana en un lapso de 12 meses tras el lanzamiento.
- **BG-02:** Lograr 10,000 descargas activas de la aplicaciÃ³n mÃ³vil del conductor en un lapso de 8 meses.
- **BG-03:** Reducir en 30% el tiempo promedio de bÃºsqueda de plaza para conductores en estacionamientos contratantes en un lapso de 6 meses.
- **BG-04:** _(...)_

## 3.4. Product Backlog

**URL del Product Backlog en herramienta:** `https://www.pivotaltracker.com/...` _(o Trello / Jira / YouTrack)_

_(Captura del Product Backlog en la herramienta seleccionada.)_

![Product Backlog](assets/images/chapter-03/product-backlog.png)

| # Orden | User Story Id | TÃ­tulo | DescripciÃ³n | Story Points (1/2/3/5/8) |
|---|---|---|---|---|
| 1 | US-07 | View Landing Page as Mall Operator | Como visitante segmento operador deseo conocer cÃ³mo la plataforma resuelve la gestiÃ³n de mi estacionamiento... | 3 |
| 2 | US-08 | View Landing Page as Driver | Como visitante segmento conductor deseo conocer los beneficios de la app mÃ³vil... | 3 |
| 3 | US-01 | View 3D Parking Occupancy Map | Como operador deseo visualizar un mapa 3D del estacionamiento... | 8 |
| 4 | US-03 | View Available Spaces by Zone | Como conductor deseo consultar la disponibilidad de espacios por zona... | 5 |
| 5 | US-04 | Register Vehicle Location | Como conductor deseo registrar la ubicaciÃ³n exacta... | 3 |
| 6 | TS-01 | Twin State Update Endpoint | Como developer deseo exponer un endpoint que actualice el estado de un twin... | 5 |
| 7 | TS-02 | Occupancy Query Endpoint | Como developer deseo exponer un endpoint que consulte ocupaciÃ³n... | 3 |
| 8 | US-02 | Receive Smoke Alert with Spatial Context | Como operador deseo recibir alertas de humo con la ubicaciÃ³n exacta... | 5 |
| 9 | US-05 | Receive Safety Alerts Near Vehicle | Como conductor deseo recibir alertas de seguridad en la zona donde estÃ¡ mi vehÃ­culo... | 5 |
| 10 | TS-03 | Push Notification Trigger | Como developer deseo integrar Firebase Cloud Messaging... | 5 |
| 11 | US-06 | Identify Low-Occupancy Zones for Lighting Adjustment | Como operador deseo identificar zonas sin vehÃ­culos donde la iluminaciÃ³n pueda atenuarse... | 3 |
| ... | ... | ... | ... | ... |

---

# CapÃ­tulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1. Design Purpose

_(ExplicaciÃ³n del propÃ³sito del proceso de diseÃ±o, evidenciando relaciÃ³n con la problemÃ¡tica y orientaciÃ³n a satisfacer las necesidades de los segmentos objetivo y el negocio.)_

El propÃ³sito del diseÃ±o arquitectÃ³nico de la plataforma es habilitar una soluciÃ³n que combine visibilidad operativa unificada para el operador del centro comercial con experiencias mÃ³viles Ã¡giles para el conductor, sustentada por un gemelo digital como single source of truth del estado del estacionamiento. Las decisiones arquitectÃ³nicas buscan satisfacer simultÃ¡neamente requisitos de baja latencia para alertas de seguridad, alta modificabilidad para incorporar nuevos tipos de sensores en el futuro, y costo operativo controlado consistente con un modelo SaaS dirigido a centros comerciales medianos.

### 4.1.2. Attribute-Driven Design Inputs

#### 4.1.2.1. Primary Functionality

_(Resumen de los requisitos funcionales seleccionados como Primary, por su impacto en la arquitectura.)_

| Epic / User Story ID | TÃ­tulo | DescripciÃ³n | Criterios de AceptaciÃ³n | Relacionado con (Epic ID) |
|---|---|---|---|---|
| US-01 | View 3D Parking Occupancy Map | _(...)_ | _(...)_ | EP-01 |
| US-02 | Receive Smoke Alert with Spatial Context | _(...)_ | _(...)_ | EP-02 |
| US-05 | Receive Safety Alerts Near Vehicle | _(...)_ | _(...)_ | EP-03 |
| TS-01 | Twin State Update Endpoint | _(...)_ | _(...)_ | EP-06 |
| TS-03 | Push Notification Trigger | _(...)_ | _(...)_ | EP-06 |

#### 4.1.2.2. Quality Attribute Scenarios

| Atributo | Fuente | EstÃ­mulo | Artefacto | Entorno | Respuesta | Medida |
|---|---|---|---|---|---|---|
| Performance (Latency) | Smoke detector sensor | Smoke detection event | Notifications service & Operator dashboard | Normal operation | System processes telemetry, updates twin and propagates alert | Alert visible in dashboard within 2 seconds; push notification delivered within 5 seconds |
| Availability | Mall operator | Dashboard query during business hours | Web Application + Web Services | Production environment | Dashboard returns occupancy data | 99.5% monthly uptime during operating hours (8am-11pm) |
| Scalability | IoT Simulator | 500 sensors emitting at 1 update/second | Web Services + Azure Digital Twins | Peak hours (mall full) | System processes all updates without data loss | Sustained throughput â‰¥ 500 msg/s with end-to-end latency < 500ms |
| Modifiability | Product Owner | Request to add a new sensor type (e.g., air quality) | Twin Models (DTDL) + Simulator + Web Services | Development environment | Team integrates new sensor type | Integration completed within â‰¤ 3 person-days |
| Security | External attacker | Unauthorized access attempt to Web Services | Web Services API | Production environment | System rejects request and logs the attempt | 100% of unauthenticated requests return HTTP 401; audit log generated |
| Usability | Driver (first-time user) | Driver opens mobile app for the first time | PowerApps mobile application | Public deployment | User registers and views available spaces | First successful availability view within â‰¤ 60 seconds from app open |
| Interoperability | IoT Simulator | Telemetry message in JSON Patch format | Azure Digital Twins via SDK | Continuous operation | Twin state updated successfully | 100% of valid JSON Patch operations applied with HTTP 204 |

#### 4.1.2.3. Constraints

_(Restricciones impuestas por el cliente o el negocio, no negociables.)_

| Technical Story ID | TÃ­tulo | DescripciÃ³n | Criterios de AceptaciÃ³n | Relacionado con (Epic ID) |
|---|---|---|---|---|
| CON-01 | Use of Azure Digital Twins | El gemelo digital debe construirse sobre Azure Digital Twins por requerimiento del modelo de negocio basado en transformaciÃ³n digital. | El sistema utiliza Azure Digital Twins como repositorio del grafo del gemelo digital. | â€” |
| CON-02 | Low-code Mobile App | La aplicaciÃ³n mÃ³vil del conductor debe desarrollarse con tecnologÃ­a low-code. | La app mÃ³vil se construye con Microsoft PowerApps. | â€” |
| CON-03 | Web Services Framework | Los Web Services deben implementarse en ASP.NET Core con C#. | Todos los servicios REST se construyen con ASP.NET Core 8. | â€” |
| CON-04 | Web Application Framework | La aplicaciÃ³n web del operador debe implementarse en Angular. | El dashboard del operador se construye con Angular y Angular Material o PrimeNG. | â€” |
| CON-05 | Default Language English | El idioma por defecto en todos los productos digitales debe ser inglÃ©s (en_US), con soporte a espaÃ±ol latinoamericano (es_419). | Todas las interfaces, mensajes y documentaciÃ³n API estÃ¡n en inglÃ©s por defecto. | â€” |
| CON-06 | Cost Containment | El presupuesto operativo debe ajustarse a Azure for Students ($100 USD). | Se evita el uso de Event Grid e IoT Hub; el simulador alimenta ADT directamente vÃ­a SDK. | â€” |
| CON-07 | RESTful API Style | Los Web Services deben seguir el estilo arquitectÃ³nico RESTful. | Endpoints diseÃ±ados con verbos HTTP semÃ¡nticos y recursos como sustantivos. | â€” |
| CON-08 | Documentation with OpenAPI | La documentaciÃ³n de APIs debe seguir OpenAPI Specification vÃ­a Swagger. | Cada endpoint cuenta con su especificaciÃ³n Swagger publicada. | â€” |
| CON-09 | Source Control with GitFlow | El control de versiones aplica GitFlow y Conventional Commits. | Todos los repos siguen el branching model definido. | â€” |

### 4.1.3. Architectural Drivers Backlog

_(IntroducciÃ³n al proceso seguido en el Quality Attribute Workshop iterativo.)_

| Driver ID | TÃ­tulo de Driver | DescripciÃ³n | Importancia para Stakeholders | Impacto en Architecture Technical Complexity |
|---|---|---|---|---|
| QA-01 | Low Latency for Safety Alerts | Las alertas de humo deben propagarse del sensor al operador y conductor en menos de 5 segundos. | High | High |
| QA-02 | Sensor Type Modifiability | Incorporar nuevos tipos de sensores debe ser posible en menos de 3 dÃ­as-desarrollador. | High | High |
| QA-03 | Cost Containment | Costo operativo dentro del crÃ©dito de Azure for Students. | High | Medium |
| FR-01 | 3D Spatial Visualization | VisualizaciÃ³n 3D del estacionamiento con estado en tiempo real. | High | High |
| FR-02 | Real-time Driver Notifications | Push notifications ante incidentes de seguridad. | High | Medium |
| QA-04 | Throughput at Peak | Sostener 500 msg/s en horas pico. | Medium | High |
| QA-05 | Availability | 99.5% uptime en horario operativo. | High | Medium |
| CON-01 | Azure Digital Twins as Twin Store | RestricciÃ³n tecnolÃ³gica del gemelo digital. | High | Medium |
| CON-02 | PowerApps for Mobile | RestricciÃ³n de tecnologÃ­a low-code. | High | Medium |
| CON-03 | ASP.NET Core for Backend | RestricciÃ³n de framework backend. | High | Low |
| CON-04 | Angular for Web Frontend | RestricciÃ³n de framework web. | High | Low |
| CON-05 | English as Default Language | RestricciÃ³n de internacionalizaciÃ³n. | Medium | Low |

### 4.1.4. Architectural Design Decisions

_(ExplicaciÃ³n del proceso siguiendo los stages del Quality Attribute Workshop. Para cada iteraciÃ³n: drivers considerados, tÃ¡cticas y patrones evaluados, criterios de decisiÃ³n.)_

#### IteraciÃ³n 1: Decomposition Strategy
**Drivers considerados:** QA-02 (Modifiability), QA-04 (Throughput), CON-01

| Driver ID | TÃ­tulo | PatrÃ³n 1: Modular Monolith | PatrÃ³n 2: Microservices | PatrÃ³n 3: Serverless Functions |
|---|---|---|---|---|
| QA-02 | Sensor Type Modifiability | **Pro:** Cambios localizados en mÃ³dulo. **Con:** RecompilaciÃ³n total. | **Pro:** Despliegue independiente. **Con:** Sobrecarga de coordinaciÃ³n. | **Pro:** Funciones especÃ­ficas por sensor. **Con:** Cold starts, fragmentaciÃ³n. |
| QA-04 | Throughput | **Pro:** Sin overhead de red entre mÃ³dulos. **Con:** Escalado vertical. | **Pro:** Escalado horizontal selectivo. **Con:** Latencia de red. | **Pro:** Auto-scaling. **Con:** Costo por invocaciÃ³n. |
| CON-03 | ASP.NET Core | **Pro:** Encaja naturalmente. | **Pro:** Encaja, pero overhead. | **Pro:** Azure Functions C#. **Con:** Cambio de paradigma. |

**DecisiÃ³n:** Modular Monolith en ASP.NET Core con mÃ³dulos por Bounded Context. JustificaciÃ³n: alcance acadÃ©mico, restricciÃ³n de costo (CON-06), simplicidad de despliegue, modularidad interna suficiente para satisfacer modificabilidad.

#### IteraciÃ³n 2: Real-time Data Propagation
**Drivers considerados:** QA-01 (Latency), QA-04 (Throughput)

| Driver ID | TÃ­tulo | PatrÃ³n 1: Polling | PatrÃ³n 2: WebSockets/SignalR | PatrÃ³n 3: Event-driven via FCM |
|---|---|---|---|---|
| QA-01 | Latency for Alerts | **Con:** Latencia variable segÃºn intervalo. | **Pro:** Push inmediato. **Con:** Mantener conexiones. | **Pro:** Push nativo. **Con:** Dependencia de servicio externo. |

**DecisiÃ³n:** SignalR para dashboard del operador (web) + FCM para push a PowerApps mÃ³vil. JustificaciÃ³n: cada canal usa la tecnologÃ­a mÃ¡s adecuada por tipo de cliente.

#### IteraciÃ³n 3: Twin Synchronization
_(Continuar con mÃ¡s iteraciones segÃºn necesidades del proyecto.)_

### 4.1.5. Quality Attribute Scenario Refinements

#### Scenario Refinement for Scenario 1: Low Latency for Smoke Alerts

| Campo | Valor |
|---|---|
| **Scenario(s):** | A smoke detector triggers an alert; the system propagates it to the operator dashboard and to drivers with active sessions in the affected zone. |
| **Business Goals:** | Ensure rapid response to safety incidents to protect lives and property; differentiate the platform from reactive parking systems. |
| **Relevant Quality Attributes:** | Performance (latency), Reliability |
| **Stimulus:** | Smoke detection event |
| **Stimulus Source:** | Smoke detector sensor (simulated) |
| **Environment:** | Normal operation, business hours |
| **Artifact:** | Web Services + Azure Digital Twins + SignalR Hub + FCM |
| **Response:** | Twin state updated; alert pushed to operator dashboard via SignalR; FCM message sent to drivers with active session in zone |
| **Response Measure:** | Operator dashboard alert visible â‰¤ 2 seconds; driver push notification delivered â‰¤ 5 seconds |
| **Questions:** | Is the SignalR Hub colocated with the Web Services? How is FCM rate-limited? |
| **Issues:** | Need to validate end-to-end latency under load; FCM delivery is best-effort |

#### Scenario Refinement for Scenario 2: Sensor Type Modifiability
_(Misma estructura)_

#### Scenario Refinement for Scenario 3: Cost Containment
_(Misma estructura)_

## 4.2. Strategic-Level Domain-Driven Design

### 4.2.1. EventStorming

_(IntroducciÃ³n y explicaciÃ³n de las actividades realizadas en la sesiÃ³n de EventStorming, con duraciÃ³n aproximada de 1-2 horas. Capturas del EventStorm elaborado en Miro o Lucidchart.)_

![EventStorming Session](assets/images/chapter-04/event-storming.png)

**Eventos de dominio identificados (Domain Events):**
- ParkingSpaceOccupied
- ParkingSpaceFreed
- SmokeDetected
- SmokeAlertTriggered
- VehicleEnteredAccessPoint
- VehicleExitedAccessPoint
- TrafficCongestionDetected
- LuminosityLevelChanged
- LightingDimmingRecommended
- ParkingSessionStarted
- VehicleLocationRegistered
- ParkingSessionEnded
- FareCalculated
- DriverNotificationSent
- _(...)_

### 4.2.2. Candidate Context Discovery

_(ExplicaciÃ³n del proceso de identificaciÃ³n de bounded contexts a partir del EventStorming, aplicando tÃ©cnicas como start-with-value, start-with-simple o look-for-pivotal-events.)_

![Candidate Context Discovery](assets/images/chapter-04/candidate-contexts.png)

**Bounded Contexts candidatos identificados:**

1. **Parking Occupancy Context** â€” Estado de plazas, niveles, zonas
2. **Safety & Incidents Context** â€” DetecciÃ³n de humo, alertas, evacuaciÃ³n
3. **Traffic Flow Context** â€” Accesos, rampas, contadores
4. **Energy Management Context** â€” IluminaciÃ³n, luminosidad, reglas de atenuaciÃ³n
5. **Parking Session Context** â€” Sesiones de conductor, ubicaciÃ³n, tarifa
6. **Notifications Context** â€” Push, FCM, in-app
7. **Identity & Access Management Context** â€” AutenticaciÃ³n de operadores y conductores
8. **Digital Twin Synchronization Context** â€” Capa anti-corrupciÃ³n hacia Azure Digital Twins

### 4.2.3. Domain Message Flows Modeling

_(ExplicaciÃ³n del proceso de Domain Storytelling para visualizar la colaboraciÃ³n entre bounded contexts.)_

#### Flow 1: Smoke Alert End-to-End
![Domain Story: Smoke Alert](assets/images/chapter-04/domain-story-smoke-alert.png)

#### Flow 2: Driver Parking Session
![Domain Story: Parking Session](assets/images/chapter-04/domain-story-parking-session.png)

#### Flow 3: Energy Adjustment Recommendation
![Domain Story: Energy Adjustment](assets/images/chapter-04/domain-story-energy.png)

### 4.2.4. Bounded Context Canvases

#### Bounded Context Canvas 1: Parking Occupancy

| SecciÃ³n | Contenido |
|---|---|
| **Name** | Parking Occupancy |
| **Purpose** | Track and expose the real-time occupancy state of every parking space, organized by zone and level. |
| **Strategic Classification** | Core Domain |
| **Domain Roles** | Operator (consumer), IoT Simulator (producer) |
| **Inbound Communication** | Receives PATCH requests from Digital Twin Synchronization Context with new occupancy state. |
| **Outbound Communication** | Publishes domain events: ParkingSpaceOccupied, ParkingSpaceFreed. |
| **Ubiquitous Language** | ParkingSpace, ParkingZone, ParkingLevel, OccupancyState |
| **Business Rules** | A space transitions Freeâ†’Occupied only via valid sensor event. OutOfService overrides any sensor reading. |
| **Dependencies** | Depends on Digital Twin Synchronization Context (downstream). |

#### Bounded Context Canvas 2: Safety & Incidents
_(Misma estructura)_

#### Bounded Context Canvas 3: Traffic Flow
_(Misma estructura)_

#### Bounded Context Canvas 4: Energy Management
_(Misma estructura)_

#### Bounded Context Canvas 5: Parking Session
_(Misma estructura)_

#### Bounded Context Canvas 6: Notifications
_(Misma estructura)_

#### Bounded Context Canvas 7: Identity & Access Management
_(Misma estructura)_

#### Bounded Context Canvas 8: Digital Twin Synchronization
_(Misma estructura)_

### 4.2.5. Context Mapping

_(ExplicaciÃ³n del proceso de elaboraciÃ³n del Context Map, indicando los patrones de relaciÃ³n aplicados.)_

![Context Map](assets/images/chapter-04/context-map.png)

**Relaciones entre Bounded Contexts:**

| Upstream | Downstream | PatrÃ³n | JustificaciÃ³n |
|---|---|---|---|
| Digital Twin Synchronization | Parking Occupancy | Customer/Supplier | Occupancy depende del estado actualizado del twin. |
| Digital Twin Synchronization | Safety & Incidents | Customer/Supplier | Las alertas de humo dependen del estado del twin del SmokeDetector. |
| Safety & Incidents | Notifications | Published Language | Eventos de SmokeAlertTriggered consumidos por Notifications. |
| Parking Session | Notifications | Customer/Supplier | Notifications consulta sesiones activas para identificar destinatarios. |
| Identity & Access Management | All others | Shared Kernel | Token de autenticaciÃ³n compartido. |
| Energy Management | Parking Occupancy | Conformist | Energy consume estado de ocupaciÃ³n sin influir en su modelo. |

## 4.3. Software Architecture

### 4.3.1. Software Architecture System Landscape Diagram

_(Diagrama de paisaje del sistema mostrando la soluciÃ³n completa en su contexto empresarial.)_

![System Landscape Diagram](assets/images/chapter-04/c4-system-landscape.png)

### 4.3.2. Software Architecture Context Level Diagram

_(C4 Level 1: Context Diagram. El sistema como recuadro central, rodeado por usuarios y sistemas externos.)_

![C4 Context Diagram](assets/images/chapter-04/c4-context.png)

**Actores externos:**
- Mall Operator (usuario)
- Driver (usuario)
- Visitor (usuario del Landing Page)
- Azure Digital Twins (sistema externo)
- Firebase Cloud Messaging (sistema externo)
- _(Pasarela de pago si aplica)_

### 4.3.3. Software Architecture Container Level Diagram

_(C4 Level 2: Container Diagram. Containers de alto nivel y cÃ³mo se distribuyen las responsabilidades, decisiones de tecnologÃ­a y comunicaciÃ³n.)_

![C4 Container Diagram](assets/images/chapter-04/c4-container.png)

**Containers principales:**
- Landing Page (HTML5/CSS3/JS estÃ¡tico, hosteado en Azure Static Web Apps)
- Web Application (Angular SPA, Azure Static Web Apps)
- Mobile App (Microsoft PowerApps)
- Web Services API (ASP.NET Core 8, Azure App Service)
- IoT Simulator (Node.js, Azure Container Apps)
- Sessions Database (PostgreSQL, Azure Database)
- Azure Digital Twins (servicio gestionado)
- 3D Scenes Storage (Azure Storage Account)

### 4.3.4. Software Architecture Deployment Diagrams

_(Diagrama de deployment mostrando cÃ³mo se despliegan los containers en infraestructura fÃ­sica/cloud.)_

![C4 Deployment Diagram](assets/images/chapter-04/c4-deployment.png)

---

# CapÃ­tulo V: Tactical-Level Software Design

_(En este capÃ­tulo se incluye una secciÃ³n por cada Bounded Context con el detalle tÃ¡ctico de su diseÃ±o. La numeraciÃ³n usa 5.1, 5.2, etc. por cada BC.)_

## 5.1. Bounded Context: Parking Occupancy

### 5.1.1. Domain Layer

_(Clases que representan el core del bounded context y las reglas de negocio.)_

**Entities:**
- `ParkingSpace` â€” Entidad raÃ­z del agregado de ocupaciÃ³n. Atributos: `Id`, `Code`, `Type`, `OccupancyState`, `LastUpdated`. MÃ©todos: `MarkAsOccupied()`, `MarkAsFreed()`, `MarkOutOfService()`.
- `ParkingZone` â€” Atributos: `Id`, `Name`, `LevelId`. MÃ©todos: `GetOccupancyRate()`.
- `ParkingLevel` â€” Atributos: `Id`, `Name`, `Floor`.

**Value Objects:**
- `OccupancyState` â€” Free, Occupied, Reserved, OutOfService.
- `SpaceCode` â€” CÃ³digo identificador de plaza con validaciÃ³n de formato.

**Aggregates:**
- `ParkingSpaceAggregate` (raÃ­z: ParkingSpace).

**Domain Services:**
- `OccupancyCalculationService` â€” Calcula tasas de ocupaciÃ³n agregadas.

**Repositories (interfaces):**
- `IParkingSpaceRepository`
- `IParkingZoneRepository`

### 5.1.2. Interface Layer

_(Clases del Interface/Presentation Layer.)_

**Controllers:**
- `OccupancyController` â€” Expone `GET /api/v1/occupancy`, `GET /api/v1/occupancy/levels/{levelId}`, `GET /api/v1/occupancy/spaces/{spaceId}`.

### 5.1.3. Application Layer

**Commands:**
- `UpdateOccupancyStateCommand`

**Command Handlers:**
- `UpdateOccupancyStateCommandHandler`

**Queries:**
- `GetOccupancyByLevelQuery`
- `GetOccupancyByZoneQuery`

**Event Handlers:**
- `TwinOccupancyChangedEventHandler` â€” Reacciona a eventos del Digital Twin Sync Context.

### 5.1.4. Infrastructure Layer

**Repository Implementations:**
- `ParkingSpaceRepository` (EF Core sobre PostgreSQL para metadata, lectura desde ADT para estado en tiempo real).

**Adapters:**
- `AzureDigitalTwinsAdapter` â€” Consume el SDK de Azure.DigitalTwins.Core.

### 5.1.5. Bounded Context Software Architecture Component Level Diagrams

_(C4 Level 3: Component Diagram para los containers de este bounded context.)_

![Component Diagram - Parking Occupancy](assets/images/chapter-05/component-parking-occupancy.png)

### 5.1.6. Bounded Context Software Architecture Code Level Diagrams

#### 5.1.6.1. Bounded Context Domain Layer Class Diagrams

_(Diagrama UML de las clases del Domain Layer, con atributos, mÃ©todos, scope, relaciones, multiplicidad.)_

![Class Diagram - Parking Occupancy](assets/images/chapter-05/class-parking-occupancy.png)

#### 5.1.6.2. Bounded Context Database Design Diagram

_(Diagrama de base de datos con tablas, columnas, constraints, relaciones.)_

![DB Diagram - Parking Occupancy](assets/images/chapter-05/db-parking-occupancy.png)

---

## 5.2. Bounded Context: Safety & Incidents

### 5.2.1. Domain Layer
_(Misma estructura)_

### 5.2.2. Interface Layer
_(Misma estructura)_

### 5.2.3. Application Layer
_(Misma estructura)_

### 5.2.4. Infrastructure Layer
_(Misma estructura)_

### 5.2.5. Bounded Context Software Architecture Component Level Diagrams
_(Misma estructura)_

### 5.2.6. Bounded Context Software Architecture Code Level Diagrams
_(Misma estructura)_

---

## 5.3. Bounded Context: Traffic Flow

_(Misma estructura)_

---

## 5.4. Bounded Context: Energy Management

_(Misma estructura)_

---

## 5.5. Bounded Context: Parking Session

_(Misma estructura)_

---

## 5.6. Bounded Context: Notifications

_(Misma estructura)_

---

## 5.7. Bounded Context: Identity & Access Management

_(Misma estructura)_

---

## 5.8. Bounded Context: Digital Twin Synchronization

_(Misma estructura)_

---

# CapÃ­tulo VI: Solution UX Design

## 6.1. Style Guidelines

### 6.1.1. General Style Guidelines

_(Decisiones sobre Branding, Typography, Colors, Spacing y tono de comunicaciÃ³n: Formal/Casual, Respetuoso/Irreverente, etc.)_

**Branding:**
- Nombre del producto: _(...)_
- Logotipo: _(insertar)_
- Tagline: _(...)_

**Typography:**
- Fuente primaria: _(Roboto / Inter / etc.)_
- Fuente secundaria: _(...)_
- Escala tipogrÃ¡fica: _(...)_

**Colors:**
| Token | Color | Uso |
|---|---|---|
| Primary | #_(hex)_ | _(...)_ |
| Secondary | #_(hex)_ | _(...)_ |
| Accent | #_(hex)_ | _(...)_ |
| Alert/Danger | #_(hex)_ | _(...)_ |
| Success | #_(hex)_ | _(...)_ |

**Spacing:** Sistema basado en mÃºltiplos de 8px (8, 16, 24, 32, 48, 64).

**Tono de comunicaciÃ³n:** Profesional, claro, orientado a acciÃ³n. Formal pero accesible.

### 6.1.2. Web, Mobile & Devices Style Guidelines

_(Decisiones sobre estÃ¡ndares visuales y de interacciÃ³n para responsive web e interfaces mÃ³viles.)_

## 6.2. Information Architecture

### 6.2.1. Organization Systems

_(Esquemas de organizaciÃ³n aplicados: jerÃ¡rquica, secuencial, matricial. Esquemas de categorizaciÃ³n: alfabÃ©tico, cronolÃ³gico, por tÃ³picos, segÃºn audiencia.)_

### 6.2.2. Labeling Systems

_(Etiquetas a utilizar para representar conjuntos de informaciÃ³n, con el mÃ­nimo nÃºmero de palabras.)_

### 6.2.3. SEO Tags and Meta Tags

| PÃ¡gina | Title | Description | Keywords | Author |
|---|---|---|---|---|
| Landing Home | _(...)_ | _(...)_ | _(...)_ | _(...)_ |
| Landing For Operators | _(...)_ | _(...)_ | _(...)_ | _(...)_ |
| Landing For Drivers | _(...)_ | _(...)_ | _(...)_ | _(...)_ |
| Web App Dashboard | _(...)_ | _(...)_ | _(...)_ | _(...)_ |

**ASO Elements (PowerApps):**
| Field | Value |
|---|---|
| App Title | _(...)_ |
| App Subtitle | _(...)_ |
| App Keywords | _(...)_ |
| App Description | _(...)_ |

### 6.2.4. Searching Systems

_(Opciones de bÃºsqueda, filtros disponibles, presentaciÃ³n de resultados.)_

### 6.2.5. Navigation Systems

_(Acciones y tÃ©cnicas de navegaciÃ³n a travÃ©s del Landing Page y aplicaciones.)_

## 6.3. Landing Page UI Design

### 6.3.1. Landing Page Wireframe

#### Desktop Web Browser
![Landing Wireframe Desktop](assets/images/chapter-06/landing-wireframe-desktop.png)

#### Mobile Web Browser
![Landing Wireframe Mobile](assets/images/chapter-06/landing-wireframe-mobile.png)

### 6.3.2. Landing Page Mock-up

#### Desktop Web Browser
![Landing Mockup Desktop](assets/images/chapter-06/landing-mockup-desktop.png)

#### Mobile Web Browser
![Landing Mockup Mobile](assets/images/chapter-06/landing-mockup-mobile.png)

## 6.4. Applications UX/UI Design

### 6.4.1. Applications Wireframes

#### Web Application (Operador)
![Web App Wireframes](assets/images/chapter-06/webapp-wireframes.png)

#### Mobile Application (Conductor â€” PowerApps)
![Mobile App Wireframes](assets/images/chapter-06/mobile-wireframes.png)

### 6.4.2. Applications Wireflow Diagrams

#### Wireflow: Operator views smoke alert and locates affected zone
**User Goal:** Identificar la ubicaciÃ³n exacta de un incidente de humo para coordinar respuesta.

![Wireflow Operator Smoke Alert](assets/images/chapter-06/wireflow-operator-smoke.png)

#### Wireflow: Driver finds and registers a parking space
**User Goal:** Localizar un espacio libre y registrar la ubicaciÃ³n del vehÃ­culo.

![Wireflow Driver Park](assets/images/chapter-06/wireflow-driver-park.png)

### 6.4.3. Applications Mock-ups

#### Web Application (Operador)
![Web App Mockups](assets/images/chapter-06/webapp-mockups.png)

#### Mobile Application (Conductor)
![Mobile App Mockups](assets/images/chapter-06/mobile-mockups.png)

### 6.4.4. Applications User Flow Diagrams

#### User Flow: Operator manages an active smoke incident
**User Goal:** Gestionar un incidente de humo desde detecciÃ³n hasta resoluciÃ³n.

![User Flow Operator](assets/images/chapter-06/userflow-operator.png)

#### User Flow: Driver completes a parking session
**User Goal:** Completar una sesiÃ³n de estacionamiento desde ingreso hasta pago de salida.

![User Flow Driver](assets/images/chapter-06/userflow-driver.png)

## 6.5. Applications Prototyping

_(Prototipos de UI con simulaciÃ³n de interacciÃ³n y navegaciÃ³n. Para cada aplicaciÃ³n: 1 screenshot del video y enlace al video subido en Microsoft Stream.)_

### Prototype: Web Application (Operador)
![Web App Prototype Screenshot](assets/images/chapter-06/webapp-prototype-screenshot.png)

**URL del video:** `https://web.microsoftstream.com/...`

### Prototype: Mobile Application (Conductor)
![Mobile App Prototype Screenshot](assets/images/chapter-06/mobile-prototype-screenshot.png)

**URL del video:** `https://web.microsoftstream.com/...`

---

# CapÃ­tulo VII: Product Implementation, Validation & Deployment

## 7.1. Software Configuration Management

### 7.1.1. Software Development Environment Configuration

| CategorÃ­a | Producto | PropÃ³sito | Ruta de referencia/descarga |
|---|---|---|---|
| Project Management | Pivotal Tracker | Product Backlog y Sprint tracking | `https://www.pivotaltracker.com/` |
| Requirements Management | UXPressia | User Personas, Empathy Maps, Impact Maps | `https://uxpressia.com/` |
| Domain Modeling | Miro / LucidChart | EventStorming, Bounded Context Canvases, Domain Storytelling | `https://miro.com/` |
| Software Architecture (C4) | Structurizr | C4 Model diagrams | `https://structurizr.com/` |
| UML Design | LucidChart | UML class diagrams | `https://lucidchart.com/` |
| Database Design | Vertabelo | DB design diagrams | `https://vertabelo.com/` |
| UI/UX Design | Figma | Wireframes, mockups, prototypes | `https://figma.com/` |
| IDE Backend | Visual Studio 2022 / JetBrains Rider | ASP.NET Core 8 development | `https://visualstudio.microsoft.com/` |
| IDE Frontend | Visual Studio Code | Angular, Node.js, HTML/CSS/JS | `https://code.visualstudio.com/` |
| Mobile Development | Microsoft PowerApps Studio | Low-code mobile app | `https://make.powerapps.com/` |
| API Documentation | Swagger UI | OpenAPI documentation | Embebido en ASP.NET Core |
| Source Control | Git + GitHub | Version control con GitFlow | `https://github.com/` |
| Cloud Provider | Microsoft Azure | Web Services hosting, Digital Twins, Storage | `https://portal.azure.com/` |
| Notifications | Firebase Cloud Messaging | Push notifications | `https://firebase.google.com/` |
| Video Hosting | Microsoft Stream + YouTube | Videos de entrevistas y producto | â€” |

### 7.1.2. Source Code Management

**Repositorios:**

| Producto | Repositorio | Branches base |
|---|---|---|
| Report | `https://github.com/<org>/report` | main, develop |
| Landing Page | `https://github.com/<org>/landing-page` | main, develop |
| Web Application | `https://github.com/<org>/web-application` | main, develop |
| Web Services | `https://github.com/<org>/web-services` | main, develop |
| IoT Simulator | `https://github.com/<org>/iot-simulator` | main, develop |
| Mobile App | `https://github.com/<org>/mobile-app` | main, develop |

**GitFlow Workflow:**

- `main`: rama principal con releases estables. Protected, solo merges desde `release/*` o `hotfix/*`.
- `develop`: rama de integraciÃ³n. Default branch.
- `feature/*`: una rama por feature/user story. Naming: `feature/<chapter-or-module>-<short-description>` para el report; `feature/us-<id>-<short-description>` para productos digitales.
- `release/*`: ramas de preparaciÃ³n de release. Naming con semantic versioning: `release/v0.1.0-tb1`, `release/v0.2.0-tp1`, `release/v0.3.0-tb2`, `release/v1.0.0-tf1`.
- `hotfix/*`: correcciones urgentes post-entrega. Naming: `hotfix/<short-description>`.

**Conventional Commits:** Se aplica `https://www.conventionalcommits.org/`.

| Tipo | Uso |
|---|---|
| `feat` | Nueva funcionalidad |
| `fix` | CorrecciÃ³n de bug |
| `docs` | Cambios de documentaciÃ³n |
| `style` | Formato, sin cambios de lÃ³gica |
| `refactor` | RefactorizaciÃ³n sin cambio funcional |
| `test` | AÃ±adir o corregir tests |
| `chore` | Tareas auxiliares |
| `perf` | Mejoras de performance |

**Semantic Versioning:** Se aplica `https://semver.org/` (MAJOR.MINOR.PATCH).

### 7.1.3. Source Code Style Guide & Conventions

| Lenguaje | GuÃ­a adoptada | Referencia |
|---|---|---|
| C# (ASP.NET Core) | Microsoft C# Coding Conventions | `https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions` |
| TypeScript (Angular) | Google TypeScript Style Guide | `https://google.github.io/styleguide/tsguide.html` |
| JavaScript (Node, Landing) | Airbnb JavaScript Style Guide | `https://github.com/airbnb/javascript` |
| HTML5 / CSS3 | Google HTML/CSS Style Guide | `https://google.github.io/styleguide/htmlcssguide.html` |
| Gherkin (.feature) | Gherkin Conventions for Readable Specifications | `https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/` |

Toda nomenclatura en inglÃ©s.

### 7.1.4. Software Deployment Configuration

_(Pasos para desplegar cada producto digital desde sus repositorios.)_

#### Landing Page â†’ Azure Static Web Apps
1. Push a `main` dispara GitHub Actions workflow.
2. Azure Static Web Apps build & deploy.

#### Web Application (Angular) â†’ Azure Static Web Apps
1. `ng build --configuration production`.
2. Deploy automatizado vÃ­a GitHub Actions.

#### Web Services (ASP.NET Core) â†’ Azure App Service
1. `dotnet publish -c Release`.
2. Deploy vÃ­a Azure Pipelines o GitHub Actions.

#### IoT Simulator (Node.js) â†’ Azure Container Apps
1. `docker build -t iot-simulator .`.
2. Push a Azure Container Registry.
3. Deploy a Container Apps.

#### Mobile App (PowerApps)
1. Export & Import via PowerApps Solution.

#### Azure Digital Twins
1. Deploy via ARM template / Bicep.
2. Upload DTDL models via CLI.

**Deployment Diagram (C4):**
![Deployment Diagram](assets/images/chapter-07/deployment-diagram.png)

## 7.2. Solution Implementation

### 7.2.1. Sprint 1

#### 7.2.1.1. Sprint Planning 1

| Sprint Planning Background | |
|---|---|
| **Sprint #** | Sprint 1 |
| **Date** | YYYY-MM-DD |
| **Time** | HH:MM AM/PM |
| **Location** | _(Virtual / FÃ­sica)_ |
| **Prepared By** | _(Team Leader)_ |
| **Attendees** | _(Lista de asistentes)_ |
| **Sprint 0 Review Summary** | N/A (primer sprint) |
| **Sprint 0 Retrospective Summary** | N/A (primer sprint) |

| Sprint Goal & User Stories | |
|---|---|
| **Sprint 1 Goal** | _(Definir el goal y la mÃ©trica de cumplimiento.)_ |
| **Sprint 1 Velocity** | _(N story points)_ |
| **Sum of Story Points** | _(N)_ |

#### 7.2.1.2. Sprint Backlog 1

**URL del Board:** `https://trello.com/b/...` _(o herramienta equivalente)_

![Sprint 1 Board](assets/images/chapter-07/sprint-1-board.png)

| Sprint # | Sprint 1 | | | | | | |
|---|---|---|---|---|---|---|---|
| **User Story** | | | **Work-Item / Task** | | | | |
| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status |
| US-07 | View Landing Page as Mall Operator | T-01 | Setup landing page repo | _(...)_ | 2 | _(Nombre)_ | Done |
| US-07 | View Landing Page as Mall Operator | T-02 | Build hero section | _(...)_ | 4 | _(Nombre)_ | Done |
| US-08 | View Landing Page as Driver | T-03 | Build "For Drivers" section | _(...)_ | 4 | _(Nombre)_ | Done |
| TS-01 | Twin State Update Endpoint | T-04 | Setup ASP.NET Core project | _(...)_ | 3 | _(Nombre)_ | Done |
| TS-01 | Twin State Update Endpoint | T-05 | Implement PATCH /api/v1/twins/{id} | _(...)_ | 6 | _(Nombre)_ | Done |
| _(...)_ | | | | | | | |

#### 7.2.1.3. Development Evidence for Sprint Review

_(Resumen de avances en implementaciÃ³n. Tabla de commits por repositorio.)_

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| `<org>/landing-page` | `feature/hero-section` | `abc1234` | feat: add hero section | Implements landing page hero with primary CTA | YYYY-MM-DD |
| `<org>/web-services` | `feature/ts-01-twin-update` | `def5678` | feat(twins): add PATCH endpoint for twin state updates | Implements UpdateOccupancyStateCommand and handler | YYYY-MM-DD |
| _(...)_ | | | | | |

#### 7.2.1.4. Testing Suite Evidence for Sprint Review

_(Conjunto de Unit Tests, Integration Tests y Acceptance Tests automatizados, para Web Services.)_

**Unit Tests implementados:**
- `ParkingSpaceTests` â€” valida transiciones de estado.
- `OccupancyCalculationServiceTests` â€” valida cÃ¡lculos agregados.

**Acceptance Tests (.feature):**

```gherkin
Feature: Twin State Update
  As a developer
  I want to update twin state via PATCH endpoint
  So that the simulator can send telemetry

  Scenario: Successful twin update
    Given a valid twin with id "space-001"
    When I send PATCH /api/v1/twins/space-001 with valid JSON Patch
    Then the response status is 204

  Scenario: Twin not found
    Given a twin id "nonexistent" does not exist
    When I send PATCH /api/v1/twins/nonexistent
    Then the response status is 404
```

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| `<org>/web-services` | `feature/ts-01-tests` | `ghi9012` | test(twins): add acceptance tests for twin update | Includes successful and not-found scenarios | YYYY-MM-DD |

#### 7.2.1.5. Execution Evidence for Sprint Review

_(Screenshots de las principales vistas implementadas + enlace a video demo.)_

![Sprint 1 Landing Hero](assets/images/chapter-07/sprint-1-landing.png)

**URL del video demo:** `https://web.microsoftstream.com/...`

#### 7.2.1.6. Services Documentation Evidence for Sprint Review

_(Endpoints documentados con OpenAPI relacionados con el alcance del sprint.)_

| Endpoint | HTTP Verb | Description | Parameters | Example Response |
|---|---|---|---|---|
| `/api/v1/twins/{id}` | PATCH | Updates a twin state | `id` (path), JSON Patch (body) | `204 No Content` |
| `/api/v1/occupancy/levels/{levelId}` | GET | Returns occupancy by level | `levelId` (path) | `200 OK` with JSON array |

![Swagger UI Sprint 1](assets/images/chapter-07/sprint-1-swagger.png)

#### 7.2.1.7. Software Deployment Evidence for Sprint Review

_(Capturas de procesos de deployment ejecutados durante el sprint.)_

![Deployment Sprint 1](assets/images/chapter-07/sprint-1-deployment.png)

**URLs desplegadas:**
- Landing Page: `https://...`
- Web Services: `https://...`
- Web App: `https://...`

#### 7.2.1.8. Team Collaboration Insights during Sprint

![Sprint 1 GitHub Insights](assets/images/chapter-07/sprint-1-insights.png)

_(AnÃ¡lisis de la colaboraciÃ³n de cada miembro durante el sprint.)_

---

### 7.2.2. Sprint 2

#### 7.2.2.1. Sprint Planning 2

| Sprint Planning Background | |
|---|---|
| **Sprint #** | Sprint 2 |
| **Date** | YYYY-MM-DD |
| **Time** | HH:MM AM/PM |
| **Location** | _(Virtual / FÃ­sica)_ |
| **Prepared By** | _(Team Leader)_ |
| **Attendees** | _(Lista de asistentes)_ |
| **Sprint 1 Review Summary** | _(Resumen del Sprint 1: resultados a nivel de productos de software, opiniones de miembros y feedback del product owner.)_ |
| **Sprint 1 Retrospective Summary** | _(Resumen del Sprint 1: opiniones del equipo sobre aciertos y oportunidades de mejora en su forma de trabajo.)_ |

| Sprint Goal & User Stories | |
|---|---|
| **Sprint 2 Goal** | _(Definir el goal y la mÃ©trica de cumplimiento.)_ |
| **Sprint 2 Velocity** | _(N story points)_ |
| **Sum of Story Points** | _(N)_ |

#### 7.2.2.2. Sprint Backlog 2

**URL del Board:** `https://trello.com/b/...` _(o herramienta equivalente)_

![Sprint 2 Board](assets/images/chapter-07/sprint-2-board.png)

| Sprint # | Sprint 2 | | | | | | |
|---|---|---|---|---|---|---|---|
| **User Story** | | | **Work-Item / Task** | | | | |
| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status |
| US-01 | View 3D Parking Occupancy Map | T-01 | Setup Angular project with Material | _(...)_ | 3 | _(Nombre)_ | Done |
| US-01 | View 3D Parking Occupancy Map | T-02 | Embed 3D Scenes Studio viewer via iframe | _(...)_ | 5 | _(Nombre)_ | Done |
| US-03 | View Available Spaces by Zone | T-03 | Build PowerApps availability screen | _(...)_ | 4 | _(Nombre)_ | Done |
| US-04 | Register Vehicle Location | T-04 | Implement vehicle location registration | _(...)_ | 5 | _(Nombre)_ | Done |
| TS-02 | Occupancy Query Endpoint | T-05 | Implement GET /api/v1/occupancy | _(...)_ | 4 | _(Nombre)_ | Done |
| _(...)_ | | | | | | | |

#### 7.2.2.3. Development Evidence for Sprint Review

_(Resumen de avances en implementaciÃ³n. Tabla de commits por repositorio.)_

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| `<org>/web-application` | `feature/us-01-3d-viewer` | `a1b2c3d` | feat(dashboard): embed 3D Scenes Studio viewer | Adds iframe-based viewer for the parking digital twin | YYYY-MM-DD |
| `<org>/mobile-app` | `feature/us-04-location-register` | `e4f5g6h` | feat(driver): add vehicle location registration screen | Implements zone/level selector and confirmation flow | YYYY-MM-DD |
| `<org>/web-services` | `feature/ts-02-occupancy-query` | `i7j8k9l` | feat(occupancy): add GET endpoint for occupancy aggregation | Implements GetOccupancyByLevelQuery and handler | YYYY-MM-DD |
| _(...)_ | | | | | |

#### 7.2.2.4. Testing Suite Evidence for Sprint Review

_(Conjunto de Unit Tests, Integration Tests y Acceptance Tests automatizados, para Web Services.)_

**Unit Tests implementados:**
- `OccupancyControllerTests` â€” valida respuesta de endpoint de ocupaciÃ³n.
- `GetOccupancyByLevelQueryHandlerTests` â€” valida lÃ³gica de agregaciÃ³n.

**Acceptance Tests (.feature):**

```gherkin
Feature: Occupancy Query
  As an operator
  I want to query parking occupancy by level
  So that I can see the current state of each level

  Scenario: Successful occupancy query
    Given I am authenticated as an operator
    When I send GET /api/v1/occupancy/levels/B1
    Then the response status is 200
    And the response contains the count of free, occupied, and reserved spaces

  Scenario: Level not found
    Given level "Z9" does not exist
    When I send GET /api/v1/occupancy/levels/Z9
    Then the response status is 404
```

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| `<org>/web-services` | `feature/ts-02-tests` | `m1n2o3p` | test(occupancy): add acceptance tests for occupancy query | Includes successful and not-found scenarios | YYYY-MM-DD |

#### 7.2.2.5. Execution Evidence for Sprint Review

_(Screenshots de las principales vistas implementadas + enlace a video demo.)_

![Sprint 2 Dashboard](assets/images/chapter-07/sprint-2-dashboard.png)
![Sprint 2 Mobile App](assets/images/chapter-07/sprint-2-mobile.png)

**URL del video demo:** `https://web.microsoftstream.com/...`

#### 7.2.2.6. Services Documentation Evidence for Sprint Review

_(Endpoints documentados con OpenAPI relacionados con el alcance del sprint.)_

| Endpoint | HTTP Verb | Description | Parameters | Example Response |
|---|---|---|---|---|
| `/api/v1/occupancy/levels/{levelId}` | GET | Returns aggregated occupancy by level | `levelId` (path) | `200 OK` with JSON object |
| `/api/v1/occupancy/zones/{zoneId}` | GET | Returns aggregated occupancy by zone | `zoneId` (path) | `200 OK` with JSON object |
| `/api/v1/sessions` | POST | Registers a new parking session | Body (driver, location) | `201 Created` |

![Swagger UI Sprint 2](assets/images/chapter-07/sprint-2-swagger.png)

#### 7.2.2.7. Software Deployment Evidence for Sprint Review

_(Capturas de procesos de deployment ejecutados durante el sprint.)_

![Deployment Sprint 2](assets/images/chapter-07/sprint-2-deployment.png)

**URLs desplegadas:**
- Web Services: `https://...`
- Web Application: `https://...`
- IoT Simulator: `https://...`

#### 7.2.2.8. Team Collaboration Insights during Sprint

![Sprint 2 GitHub Insights](assets/images/chapter-07/sprint-2-insights.png)

_(AnÃ¡lisis de la colaboraciÃ³n de cada miembro durante el sprint.)_

---

### 7.2.3. Sprint 3

#### 7.2.3.1. Sprint Planning 3

| Sprint Planning Background | |
|---|---|
| **Sprint #** | Sprint 3 |
| **Date** | YYYY-MM-DD |
| **Time** | HH:MM AM/PM |
| **Location** | _(Virtual / FÃ­sica)_ |
| **Prepared By** | _(Team Leader)_ |
| **Attendees** | _(Lista de asistentes)_ |
| **Sprint 2 Review Summary** | _(Resumen del Sprint 2: resultados a nivel de productos de software, opiniones de miembros y feedback del product owner.)_ |
| **Sprint 2 Retrospective Summary** | _(Resumen del Sprint 2: opiniones del equipo sobre aciertos y oportunidades de mejora en su forma de trabajo.)_ |

| Sprint Goal & User Stories | |
|---|---|
| **Sprint 3 Goal** | _(Definir el goal y la mÃ©trica de cumplimiento. Foco en cierre: integraciÃ³n de alertas en tiempo real, push notifications, gestiÃ³n energÃ©tica y refinamiento UX.)_ |
| **Sprint 3 Velocity** | _(N story points)_ |
| **Sum of Story Points** | _(N)_ |

#### 7.2.3.2. Sprint Backlog 3

**URL del Board:** `https://trello.com/b/...` _(o herramienta equivalente)_

![Sprint 3 Board](assets/images/chapter-07/sprint-3-board.png)

| Sprint # | Sprint 3 | | | | | | |
|---|---|---|---|---|---|---|---|
| **User Story** | | | **Work-Item / Task** | | | | |
| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status |
| US-02 | Receive Smoke Alert with Spatial Context | T-01 | Implement SignalR Hub for real-time alerts | _(...)_ | 6 | _(Nombre)_ | Done |
| US-02 | Receive Smoke Alert with Spatial Context | T-02 | Subscribe operator dashboard to alert channel | _(...)_ | 4 | _(Nombre)_ | Done |
| US-05 | Receive Safety Alerts Near Vehicle | T-03 | Integrate Firebase Cloud Messaging in backend | _(...)_ | 5 | _(Nombre)_ | Done |
| US-05 | Receive Safety Alerts Near Vehicle | T-04 | Configure FCM device token registration in PowerApps | _(...)_ | 4 | _(Nombre)_ | Done |
| TS-03 | Push Notification Trigger | T-05 | Implement notifications service for active sessions | _(...)_ | 5 | _(Nombre)_ | Done |
| US-06 | Identify Low-Occupancy Zones for Lighting Adjustment | T-06 | Implement energy view in dashboard | _(...)_ | 4 | _(Nombre)_ | Done |
| _(...)_ | | | | | | | |

#### 7.2.3.3. Development Evidence for Sprint Review

_(Resumen de avances en implementaciÃ³n. Tabla de commits por repositorio.)_

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| `<org>/web-services` | `feature/us-02-signalr-alerts` | `q1r2s3t` | feat(alerts): add SignalR Hub for real-time smoke alerts | Implements push channel for operator dashboard | YYYY-MM-DD |
| `<org>/web-services` | `feature/ts-03-fcm-integration` | `u4v5w6x` | feat(notifications): integrate Firebase Cloud Messaging | Implements FcmNotificationService and device token registry | YYYY-MM-DD |
| `<org>/web-application` | `feature/us-02-alert-overlay` | `y7z8a9b` | feat(dashboard): subscribe to SignalR alert channel | Renders alert overlay on 3D viewer when smoke detected | YYYY-MM-DD |
| `<org>/mobile-app` | `feature/us-05-push-alerts` | `c1d2e3f` | feat(driver): handle FCM push notifications for safety alerts | Displays in-app evacuation instructions on alert receipt | YYYY-MM-DD |
| `<org>/web-application` | `feature/us-06-energy-view` | `g4h5i6j` | feat(dashboard): add energy management view | Highlights low-occupancy zones with dimming recommendations | YYYY-MM-DD |
| _(...)_ | | | | | | | |

#### 7.2.3.4. Testing Suite Evidence for Sprint Review

_(Conjunto de Unit Tests, Integration Tests y Acceptance Tests automatizados, para Web Services.)_

**Unit Tests implementados:**
- `FcmNotificationServiceTests` â€” valida envÃ­o correcto a FCM.
- `SmokeAlertHandlerTests` â€” valida detecciÃ³n de sesiones afectadas por zona.
- `EnergyRecommendationServiceTests` â€” valida lÃ³gica de recomendaciÃ³n de atenuaciÃ³n.

**Acceptance Tests (.feature):**

```gherkin
Feature: Smoke Alert End-to-End
  As an operator
  I want to receive smoke alerts with spatial context in real time
  So that I can coordinate the response immediately

  Scenario: Alert reaches operator dashboard within 2 seconds
    Given a smoke detector "SD-001" in zone "B1-A"
    When the simulator emits a smoke detection event
    Then within 2 seconds the operator dashboard receives the alert
    And the affected zone is highlighted on the 3D viewer

  Scenario: Driver with active session receives push notification
    Given a driver with an active parking session in zone "B1-A"
    When a smoke alert is triggered in zone "B1-A"
    Then within 5 seconds the driver receives a push notification
    And the notification includes evacuation instructions
```

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on |
|---|---|---|---|---|---|
| `<org>/web-services` | `feature/us-02-tests` | `k7l8m9n` | test(alerts): add end-to-end tests for smoke alerts | Validates 2s latency for dashboard and 5s for FCM push | YYYY-MM-DD |

#### 7.2.3.5. Execution Evidence for Sprint Review

_(Screenshots de las principales vistas implementadas + enlace a video demo.)_

![Sprint 3 Smoke Alert](assets/images/chapter-07/sprint-3-alert.png)
![Sprint 3 Push Notification](assets/images/chapter-07/sprint-3-push.png)
![Sprint 3 Energy View](assets/images/chapter-07/sprint-3-energy.png)

**URL del video demo:** `https://web.microsoftstream.com/...`

#### 7.2.3.6. Services Documentation Evidence for Sprint Review

_(Endpoints documentados con OpenAPI relacionados con el alcance del sprint.)_

| Endpoint | HTTP Verb | Description | Parameters | Example Response |
|---|---|---|---|---|
| `/api/v1/alerts` | GET | Returns active alerts | Query: `zoneId`, `levelId` | `200 OK` with JSON array |
| `/api/v1/alerts/{id}/acknowledge` | POST | Acknowledges an alert by operator | `id` (path) | `204 No Content` |
| `/api/v1/notifications/devices` | POST | Registers a device token for push notifications | Body: `driverId`, `token` | `201 Created` |
| `/api/v1/energy/recommendations` | GET | Returns lighting dimming recommendations by zone | Query: `levelId` | `200 OK` with JSON array |
| `/hubs/alerts` | WebSocket | SignalR Hub for real-time alert channel | â€” | Real-time alert events |

![Swagger UI Sprint 3](assets/images/chapter-07/sprint-3-swagger.png)

#### 7.2.3.7. Software Deployment Evidence for Sprint Review

_(Capturas de procesos de deployment ejecutados durante el sprint. Esta es la versiÃ³n final desplegada de los productos digitales.)_

![Deployment Sprint 3](assets/images/chapter-07/sprint-3-deployment.png)

**URLs desplegadas (versiÃ³n final):**
- Landing Page: `https://...`
- Web Application: `https://...`
- Web Services: `https://...`
- IoT Simulator: `https://...`
- Swagger Docs: `https://.../swagger`

**ConfiguraciÃ³n de Firebase Cloud Messaging:**
- FCM Project: `<project-id>`
- Server Key configurado en App Service settings.

**ConfiguraciÃ³n de Azure Digital Twins:**
- ADT Instance: `<instance-name>.api.<region>.digitaltwins.azure.net`
- 3D Scenes Storage Container: `<container-name>`

#### 7.2.3.8. Team Collaboration Insights during Sprint

![Sprint 3 GitHub Insights](assets/images/chapter-07/sprint-3-insights.png)

_(AnÃ¡lisis de la colaboraciÃ³n de cada miembro durante el sprint final.)_

## 7.3. Validation Interviews

### 7.3.1. DiseÃ±o de Entrevistas

_(Elementos a validar por segmento objetivo, incluyendo Landing Page y aplicaciones. User flows que formarÃ¡n parte de la validaciÃ³n.)_

### 7.3.2. Registro de Entrevistas

#### Entrevista de ValidaciÃ³n 1 â€” Operador
| Campo | Dato |
|---|---|
| Nombres y Apellidos | _(...)_ |
| Edad | _(...)_ |
| Distrito | _(...)_ |
| Cargo | _(...)_ |
| Fecha de entrevista | YYYY-MM-DD |
| URL del video | `https://web.microsoftstream.com/...` |
| Timing inicio | HH:MM:SS |
| DuraciÃ³n | MM:SS |

![Validation Interview 1](assets/images/chapter-07/validation-interview-01.png)

**Resumen:** _(Apreciaciones del entrevistado respecto a las tareas asignadas.)_

_(Repetir para todas las entrevistas de validaciÃ³n, 3-5 por segmento.)_

### 7.3.3. Evaluaciones segÃºn heurÃ­sticas

**UX Heuristics & Principles Evaluation**  
**Usability â€“ Inclusive Design â€“ Information Architecture**

| Campo | Valor |
|---|---|
| **CARRERA** | IngenierÃ­a de Software |
| **CURSO** | Arquitecturas de Software Emergentes |
| **SECCIÃ“N** | _(...)_ |
| **PROFESORES** | _(...)_ |
| **AUDITOR** | _(Nombre del Grupo)_ |
| **CLIENTE(S)** | _(Nombres de los participantes)_ |

**SITE/APP A EVALUAR:** _(Web Application del Operador / Mobile App del Conductor)_

**TAREAS A EVALUAR:**
1. _(Login del operador)_
2. _(VisualizaciÃ³n de mapa 3D de ocupaciÃ³n)_
3. _(AtenciÃ³n de alerta de humo)_
4. _(Registro de ubicaciÃ³n de vehÃ­culo en app mÃ³vil)_
5. _(RecepciÃ³n de alerta de seguridad en app mÃ³vil)_
6. _(...)_

**TAREAS NO INCLUIDAS:**
1. _(...)_

**ESCALA DE SEVERIDAD:**

| Nivel | DescripciÃ³n |
|---|---|
| 1 | Problema superficial: puede ser fÃ¡cilmente superado por el usuario o ocurre con muy poca frecuencia. |
| 2 | Problema menor: ocurre un poco mÃ¡s frecuentemente o es mÃ¡s difÃ­cil de superar. Prioridad baja. |
| 3 | Problema mayor: ocurre frecuentemente o los usuarios no pueden resolverlo. Prioridad alta. |
| 4 | Problema muy grave: error de gran impacto que impide el uso. Imperativo corregir antes del lanzamiento. |

**TABLA RESUMEN:**

| # | Problema | Escala de severidad | HeurÃ­stica/Principio violada(o) |
|---|---|---|---|
| 1 | _(DescripciÃ³n del problema)_ | _(1-4)_ | _(HeurÃ­stica violada)_ |
| 2 | _(...)_ | _(...)_ | _(...)_ |

**DESCRIPCIÃ“N DE PROBLEMAS:**

**PROBLEMA #1:** _(TÃ­tulo)_

- **Severidad:** _(1-4)_
- **HeurÃ­stica violada:** _(...)_
- **Problema:** _(DescripciÃ³n detallada con captura)_
- **RecomendaciÃ³n:** _(...)_

_(Repetir para cada problema identificado.)_

## 7.4. Video About-the-Product

_(IntroducciÃ³n y descripciÃ³n del contenido del video. Tono consistente con el producto. Incluye al menos un testimonio positivo de un usuario que haya participado en las entrevistas de validaciÃ³n.)_

![Video About-the-Product Screenshot](assets/images/chapter-07/about-product-screenshot.png)

- **URL Microsoft Stream:** `https://web.microsoftstream.com/...`
- **URL YouTube:** `https://youtube.com/...`
- **DuraciÃ³n:** MM:SS

---

# Conclusiones

## Conclusiones y recomendaciones

_(Conclusiones sobre el trabajo, contrastando con los Problem Statements, Assumptions, Hypothesis Statements y criterios de Ã©xito definidos en el proceso Lean UX. Recomendaciones sobre roadmap futuro de los productos digitales.)_

### Conclusiones por entrega

#### TB1
_(Conclusiones acumulables.)_

#### TP1
_(Conclusiones acumulables.)_

#### TB2
_(Conclusiones acumulables.)_

#### TF1
_(Conclusiones finales del proyecto.)_

### Recomendaciones de roadmap

_(PrÃ³ximos pasos para escalar la soluciÃ³n: integraciÃ³n con sensores IoT reales, expansiÃ³n a mÃºltiples centros comerciales, pasarela de pagos, integraciÃ³n con sistemas de gestiÃ³n del centro comercial, analÃ­tica predictiva, etc.)_

## Video About-the-Team

_(Resumen del proceso de trabajo, pauta de secuencias con timing, screenshot del video.)_

![Video About-the-Team Screenshot](assets/images/chapter-07/about-team-screenshot.png)

**Pauta de secuencias:**

| Inicio (hh:mm:ss) | SecciÃ³n |
|---|---|
| 00:00:00 | IntroducciÃ³n |
| 00:00:30 | Sesiones de trabajo del equipo |
| 00:02:00 | Testimonio integrante 1 |
| 00:03:00 | Testimonio integrante 2 |
| 00:04:00 | Testimonio integrante 3 |
| 00:05:00 | Testimonio integrante 4 |
| 00:06:00 | Conclusiones grupales |

- **URL Microsoft Stream:** `https://web.microsoftstream.com/...`
- **URL YouTube:** `https://youtube.com/...`

---

# BibliografÃ­a

_(Referencias en formato APA.)_

- Brown, S. (2018). _The C4 model for visualising software architecture_. C4 Model. https://c4model.com/
- Cervantes, H., & Kazman, R. (2016). _Designing Software Architectures: A Practical Approach_. Addison-Wesley.
- Driessen, V. (2010). _A successful Git branching model_. https://nvie.com/posts/a-successful-git-branching-model/
- Evans, E. (2003). _Domain-Driven Design: Tackling Complexity in the Heart of Software_. Addison-Wesley.
- Fowler, M. (2006). _UbiquitousLanguage_. martinfowler.com. https://martinfowler.com/bliki/UbiquitousLanguage.html
- Gothelf, J., & Seiden, J. (2021). _Lean UX: Designing Great Products with Agile Teams_ (3rd ed.). O'Reilly Media.
- Microsoft. (2025). _Azure Digital Twins documentation_. https://learn.microsoft.com/en-us/azure/digital-twins/
- Microsoft. (2025). _3D Scenes Studio (preview) for Azure Digital Twins_. https://learn.microsoft.com/en-us/azure/digital-twins/concepts-3d-scenes-studio
- Microsoft. (2025). _Microsoft Power Apps documentation_. https://learn.microsoft.com/en-us/power-apps/
- Nielsen, J. (1994). _10 Usability Heuristics for User Interface Design_. Nielsen Norman Group. https://www.nngroup.com/articles/ten-usability-heuristics/
- Preston-Werner, T. (2013). _Semantic Versioning 2.0.0_. https://semver.org/

_(Continuar con todas las referencias utilizadas.)_

---

# Anexos

## Anexo A: Videos de Exposiciones

| Entrega | URL del video |
|---|---|
| TB1 | `https://web.microsoftstream.com/...` |
| TP1 | `https://web.microsoftstream.com/...` |
| TB2 | `https://web.microsoftstream.com/...` |
| TF1 | `https://web.microsoftstream.com/...` |

## Anexo B: TÃ©rminos y Condiciones del Servicio

_(Texto completo de los Terms of Service expuestos en el footer del Landing Page y aplicaciones, redactados con responsabilidad Ã©tica y profesional segÃºn los principios del cÃ³digo de Ã©tica de software engineering de ACM/IEEE y del CIP.)_

## Anexo C: ConfiguraciÃ³n de InternacionalizaciÃ³n (i18n) y Accesibilidad (a11y)

_(Detalle de la configuraciÃ³n de i18n para English (en_US) y Latin American Spanish (es_419), y configuraciÃ³n de ARIA attributes en Landing Page y Web Application.)_

## Anexo D: DTDL Models de Azure Digital Twins

_(Listado de los Twin Models definidos en DTDL para el grafo del estacionamiento.)_

```json
{
  "@id": "dtmi:smartpark:ParkingSpace;1",
  "@type": "Interface",
  "@context": "dtmi:dtdl:context;2",
  "displayName": "Parking Space",
  "contents": [
    {
      "@type": "Property",
      "name": "code",
      "schema": "string"
    },
    {
      "@type": "Property",
      "name": "occupancyState",
      "schema": "string"
    },
    {
      "@type": "Property",
      "name": "lastUpdated",
      "schema": "dateTime"
    }
  ]
}
```

_(Continuar con los modelos de ParkingZone, ParkingLevel, SmokeDetector, etc.)_

