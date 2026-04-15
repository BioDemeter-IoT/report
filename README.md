
<h2 style="text-align: center;"> Universidad Peruana de Ciencias Aplicadas </h2>
<h4 style="text-align: center"> Ingeniería de Software </h4>
<h4 style="text-align: center"> Periodo: 202610 </h4>
<br>
 <p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="upc-logo" width="80px" height="80px"/>
</p>
<h4 style="text-align: center"> Desarrollo de Soluciones IOT </h4>
<h4 style="text-align: center"> Sección: 17756 </h4>
<h4 style="text-align: center"> Docente: David Vera Olivera </h4>
<h3 style="text-align: center;"> Informe de Trabajo Final </h3>
<h4 style="text-align: center"> Startup: BioDemeter </h4>
<h4 style="text-align: center"> Producto: PlantSync </h4>
<h4 style="text-align: center">Integrantes:</h4>
<div style="text-align:center; margin-top: 10px; font-size: 90%; line-height: 1.6;">
   <table style="margin-left: auto; margin-right: auto;">
      <tr>
         <th>Código</th>
         <th>Apellidos y Nombres</th>
      </tr>
      <tr>
         <td>[COMPLETAR]</td>
         <td>[COMPLETAR]</td>
      </tr>
      <tr>
         <td>[COMPLETAR]</td>
         <td>[COMPLETAR]</td>
      </tr>
      <tr>
         <td>[COMPLETAR]</td>
         <td>[COMPLETAR]</td>
      </tr>
      <tr>
         <td>[COMPLETAR]</td>
         <td>[COMPLETAR]</td>
      </tr>
      <tr>
         <td>[COMPLETAR]</td>
         <td>[COMPLETAR]</td>
      </tr>
       <tr>
         <td>[COMPLETAR]</td>
         <td>[COMPLETAR]</td>
      </tr>
       <tr>
         <td>[COMPLETAR]</td>
         <td>[COMPLETAR]</td>
      </tr>
   </table>
</div>
<br>
<h5 style="text-align: center; font-style: italic;"> Abril 2026 </h5>
<hr class="page-break">

# Registro de Versiones del Informe

| Version | Fecha | Autor | Descripción de modificación |
|---------|-------|-------|-----------------------------|
|         |       |       |                             |

<hr class="page-break">

# Project Report Collaboration Insights

<hr class="page-break">

# Contenido

- [Capítulo I: Introducción](#capítulo-i-introducción)
   - [1.1. Startup Profile](#11-startup-profile)
      - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
      - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
   - [1.2. Solution Profile](#12-solution-profile)
      - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
      - [1.2.2. Lean UX Process](#122-lean-ux-process)
         - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
         - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
         - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
         - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
   - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
   - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
   - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
   - [3.1. User Stories](#31-user-stories)
   - [3.2. Impact Mapping](#32-impact-mapping)
   - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
   - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
      - [4.1.1. Design-Level EventStorming](#411-design-level-eventstorming)
         - [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
         - [4.1.1.2. Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
         - [4.1.1.3. Bounded Context Canvases](#4113-bounded-context-canvases)
      - [4.1.2. Context Mapping](#412-context-mapping)
      - [4.1.3. Software Architecture](#413-software-architecture)
         - [4.1.3.1. Software Architecture System Landscape Diagram](#4131-software-architecture-system-landscape-diagram)
         - [4.1.3.2. Software Architecture Context Level Diagrams](#4132-software-architecture-context-level-diagrams)
         - [4.1.3.3. Software Architecture Container Level Diagrams](#4133-software-architecture-container-level-diagrams)
         - [4.1.3.4. Software Architecture Deployment Diagrams](#4134-software-architecture-deployment-diagrams)
   - [4.2. Tactical-Level Domain-Driven Design](#42-tactical-level-domain-driven-design)
      - [4.2.X. Bounded Context: \<Bounded Context Name\>](#42x-bounded-context-bounded-context-name)
         - [4.2.X.1. Domain Layer](#42x1-domain-layer)
         - [4.2.X.2. Interface Layer](#42x2-interface-layer)
         - [4.2.X.3. Application Layer](#42x3-application-layer)
         - [4.2.X.4. Infrastructure Layer](#42x4-infrastructure-layer)
         - [4.2.X.5. Bounded Context Software Architecture Component Level Diagrams](#42x5-bounded-context-software-architecture-component-level-diagrams)
         - [4.2.X.6. Bounded Context Software Architecture Code Level Diagrams](#42x6-bounded-context-software-architecture-code-level-diagrams)
            - [4.2.X.6.1. Bounded Context Domain Layer Class Diagrams](#42x61-bounded-context-domain-layer-class-diagrams)
            - [4.2.X.6.2. Bounded Context Database Design Diagram](#42x62-bounded-context-database-design-diagram)
- [Capítulo V: Solution UI/UX Design](#capítulo-v-solution-uiux-design)
   - [5.1. Style Guidelines](#51-style-guidelines)
      - [5.1.1. General Style Guidelines](#511-general-style-guidelines)
      - [5.1.2. Web, Mobile and IoT Style Guidelines](#512-web-mobile-and-iot-style-guidelines)
   - [5.2. Information Architecture](#52-information-architecture)
      - [5.2.1. Organization Systems](#521-organization-systems)
      - [5.2.2. Labeling Systems](#522-labeling-systems)
      - [5.2.3. SEO Tags and Meta Tags](#523-seo-tags-and-meta-tags)
      - [5.2.4. Searching Systems](#524-searching-systems)
      - [5.2.5. Navigation Systems](#525-navigation-systems)
   - [5.3. Landing Page UI Design](#53-landing-page-ui-design)
      - [5.3.1. Landing Page Wireframe](#531-landing-page-wireframe)
      - [5.3.2. Landing Page Mock-up](#532-landing-page-mock-up)
   - [5.4. Applications UX/UI Design](#54-applications-uxui-design)
      - [5.4.1. Applications Wireframes](#541-applications-wireframes)
      - [5.4.2. Applications Wireflow Diagrams](#542-applications-wireflow-diagrams)
      - [5.4.3. Applications Mock-ups](#543-applications-mock-ups)
      - [5.4.4. Applications User Flow Diagrams](#544-applications-user-flow-diagrams)
   - [5.5. Applications Prototyping](#55-applications-prototyping)
   - [5.6. IoT Device Design](#56-iot-device-design)
- [Capítulo VI: Product Implementation, Validation & Deployment](#capítulo-vi-product-implementation-validation--deployment)
   - [6.1. Software Configuration Management](#61-software-configuration-management)
      - [6.1.1. Software Development Environment Configuration](#611-software-development-environment-configuration)
      - [6.1.2. Source Code Management](#612-source-code-management)
      - [6.1.3. Source Code Style Guide & Conventions](#613-source-code-style-guide--conventions)
      - [6.1.4. Software Deployment Configuration](#614-software-deployment-configuration)
   - [6.2. Landing Page, Services & Applications Implementation](#62-landing-page-services--applications-implementation)
      - [6.2.X. Sprint n](#62x-sprint-n)
         - [6.2.X.1. Sprint Planning n](#62x1-sprint-planning-n)
         - [6.2.X.2. Aspect Leaders and Collaborators](#62x2-aspect-leaders-and-collaborators)
         - [6.2.X.3. Sprint Backlog n](#62x3-sprint-backlog-n)
         - [6.2.X.4. Development Evidence for Sprint Review](#62x4-development-evidence-for-sprint-review)
         - [6.2.X.5. Testing Suite Evidence for Sprint Review](#62x5-testing-suite-evidence-for-sprint-review)
         - [6.2.X.6. Execution Evidence for Sprint Review](#62x6-execution-evidence-for-sprint-review)
         - [6.2.X.7. Services Documentation Evidence for Sprint Review](#62x7-services-documentation-evidence-for-sprint-review)
         - [6.2.X.8. Software Deployment Evidence for Sprint Review](#62x8-software-deployment-evidence-for-sprint-review)
         - [6.2.X.9. Team Collaboration Insights during Sprint](#62x9-team-collaboration-insights-during-sprint)
   - [6.3. Validation Interviews](#63-validation-interviews)
      - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
      - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
      - [6.3.3. Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)
   - [6.4. Video About-the-Product](#64-video-about-the-product)
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<hr class="page-break">

# Student Outcome

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome.

<table>
  <thead>
    <tr>
      <th>Criterio específico</th>
      <th>Acciones realizadas</th>
      <th>Conclusiones</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="5"><strong>[COMPLETAR: Criterio 1]</strong></td>
      <td><strong>[COMPLETAR: Integrante 1]</strong><br><b>TB1:</b></td>
      <td rowspan="5"><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 2]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 3]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 4]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 5]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td rowspan="5"><strong>[COMPLETAR: Criterio 2]</strong></td>
      <td><strong>[COMPLETAR: Integrante 1]</strong><br><b>TB1:</b></td>
      <td rowspan="5"><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 2]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 3]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 4]</strong><br><b>TB1:</b></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Integrante 5]</strong><br><b>TB1:</b></td>
    </tr>
  </tbody>
</table>

<hr class="page-break">

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

<table>
  <thead>
    <tr>
      <th>Perfil</th>
      <th>Foto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>[COMPLETAR: Apellidos, Nombres]</strong><br>[COMPLETAR: descripción]</td>
      <td><img src="assets/images/photos/[COMPLETAR].jpg" alt="[COMPLETAR]" width="200"></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Apellidos, Nombres]</strong><br>[COMPLETAR: descripción]</td>
      <td><img src="assets/images/photos/[COMPLETAR].jpg" alt="[COMPLETAR]" width="200"></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Apellidos, Nombres]</strong><br>[COMPLETAR: descripción]</td>
      <td><img src="assets/images/photos/[COMPLETAR].jpg" alt="[COMPLETAR]" width="200"></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Apellidos, Nombres]</strong><br>[COMPLETAR: descripción]</td>
      <td><img src="assets/images/photos/[COMPLETAR].jpg" alt="[COMPLETAR]" width="200"></td>
    </tr>
    <tr>
      <td><strong>[COMPLETAR: Apellidos, Nombres]</strong><br>[COMPLETAR: descripción]</td>
      <td><img src="assets/images/photos/[COMPLETAR].jpg" alt="[COMPLETAR]" width="200"></td>
    </tr>
  </tbody>
</table>

<hr class="page-break">

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

#### WHAT (Qué)

#### WHEN (Cuándo)

#### WHERE (Dónde)

#### WHO (Quién)

#### WHY (Por qué)

#### HOW (Cómo)

#### HOW MUCH (Cuánto)

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

##### Business Assumptions

##### User Assumptions

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

<hr class="page-break">

## 1.3. Segmentos objetivo

<hr class="page-break">

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="5">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <td colspan="2" align="center"><b>¿Por qué llevar a cabo este análisis?</b></td>
    <td colspan="3">[COMPLETAR]</td>
  </tr>
  <tr>
    <th colspan="2">Nombre</th>
    <th>[Startup]</th>
    <th>[Competidor 1]</th>
    <th>[Competidor 2]</th>
  </tr>
  <tr>
    <td colspan="2" align="center"><b>Logo</b></td>
    <td align="center"><img src="assets/images/logos/[startup]-logo.png" alt="Startup logo" width="100"></td>
    <td align="center"><img src="assets/images/logos/[competidor1].png" alt="[Competidor 1]" width="100"></td>
    <td align="center"><img src="assets/images/logos/[competidor2].png" alt="[Competidor 2]" width="100"></td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td><b>Overview</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td><b>Mercado objetivo</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><b>Estrategias de Marketing</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="3"><b>Perfil de Producto</b></td>
    <td><b>Productos &amp; Servicios</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><b>Precios y Costos</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><b>Canales de distribución</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="4"><b>Análisis SWOT</b></td>
    <td><b>Fortalezas</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><b>Oportunidades</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><b>Debilidades</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td><b>Amenazas</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

<hr class="page-break">

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

<hr class="page-break">

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

<table>
  <thead>
    <tr>
      <th rowspan="2">Tareas</th>
      <th colspan="2">[Segmento 1]</th>
      <th colspan="2">[Segmento 2]</th>
    </tr>
    <tr>
      <th>Frecuencia</th>
      <th>Importancia</th>
      <th>Frecuencia</th>
      <th>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>[COMPLETAR]</td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

<hr class="page-break">

## 2.4. Big Picture EventStorming

## 2.5. Ubiquitous Language

<hr class="page-break">

# Capítulo III: Requirements Specification

## 3.1. User Stories

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-----------------|--------|-------------|-------------------------|---------------------------|
|                 |        |             |                         |                           |

<hr class="page-break">

## 3.2. Impact Mapping

<hr class="page-break">

## 3.3. Product Backlog

| # Orden | User Story ID | Título | Descripción | Story Points |
|---------|---------------|--------|-------------|--------------|
|         |               |        |             |              |

<hr class="page-break">

# Capítulo IV: Solution Software Design

## 4.1. Strategic-Level Domain-Driven Design

### 4.1.1. Design-Level EventStorming

#### 4.1.1.1. Candidate Context Discovery

#### 4.1.1.2. Domain Message Flows Modeling

#### 4.1.1.3. Bounded Context Canvases

### 4.1.2. Context Mapping

### 4.1.3. Software Architecture

#### 4.1.3.1. Software Architecture System Landscape Diagram

#### 4.1.3.2. Software Architecture Context Level Diagrams

#### 4.1.3.3. Software Architecture Container Level Diagrams

#### 4.1.3.4. Software Architecture Deployment Diagrams

<hr class="page-break">

## 4.2. Tactical-Level Domain-Driven Design

### 4.2.X. Bounded Context: \<Bounded Context Name\>

#### 4.2.X.1. Domain Layer

#### 4.2.X.2. Interface Layer

#### 4.2.X.3. Application Layer

#### 4.2.X.4. Infrastructure Layer

#### 4.2.X.5. Bounded Context Software Architecture Component Level Diagrams

#### 4.2.X.6. Bounded Context Software Architecture Code Level Diagrams

##### 4.2.X.6.1. Bounded Context Domain Layer Class Diagrams

##### 4.2.X.6.2. Bounded Context Database Design Diagram

<hr class="page-break">

# Capítulo V: Solution UI/UX Design

## 5.1. Style Guidelines

### 5.1.1. General Style Guidelines

### 5.1.2. Web, Mobile and IoT Style Guidelines

## 5.2. Information Architecture

### 5.2.1. Organization Systems

### 5.2.2. Labeling Systems

### 5.2.3. SEO Tags and Meta Tags

### 5.2.4. Searching Systems

### 5.2.5. Navigation Systems

## 5.3. Landing Page UI Design

### 5.3.1. Landing Page Wireframe

### 5.3.2. Landing Page Mock-up

<hr class="page-break">

## 5.4. Applications UX/UI Design

### 5.4.1. Applications Wireframes

### 5.4.2. Applications Wireflow Diagrams

### 5.4.3. Applications Mock-ups

### 5.4.4. Applications User Flow Diagrams

## 5.5. Applications Prototyping

## 5.6. IoT Device Design

<hr class="page-break">

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management

### 6.1.1. Software Development Environment Configuration

### 6.1.2. Source Code Management

Se utilizó **GitHub** como plataforma de control de versiones y colaboración en equipo.
Los integrantes del equipo y sus nombres de usuario en GitHub son los siguientes:

| Integrantes | Nombre en GitHub |
|-------------|------------------|
|             |                  |
|             |                  |
|             |                  |
|             |                  |
|             |                  |

### 6.1.3. Source Code Style Guide & Conventions

### 6.1.4. Software Deployment Configuration

<hr class="page-break">

## 6.2. Landing Page, Services & Applications Implementation

### 6.2.1. Sprint 1

#### 6.2.1.1. Sprint Planning 1

| Sprint # | Fecha | Hora | Lugar | Preparado por | Asistentes |
|----------|-------|------|-------|---------------|------------|
| Sprint 1 |       |      |       |               |            |

| Sprint Goal & User Stories | |
|----------------------------|-|
| Sprint 1 Goal              |  |
| Sprint 1 Velocity          |  |
| Sum of Story Points        |  |

#### 6.2.1.2. Aspect Leaders and Collaborators

| Team Member | GitHub Username | Aspect | Role |
|-------------|-----------------|--------|------|
|             |                 |        |      |

#### 6.2.1.3. Sprint Backlog 1

| Sprint # | User Story | Work-Item / Task | Descripción | Estimación (horas) | Asignado a | Estado |
|----------|------------|------------------|-------------|-------------------|------------|--------|
| Sprint 1 |            |                  |             |                   |            |        |

#### 6.2.1.4. Development Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 6.2.1.5. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 6.2.1.6. Execution Evidence for Sprint Review

#### 6.2.1.7. Services Documentation Evidence for Sprint Review

| Servicio | Verbo | Endpoint | Parámetros | Response |
|----------|-------|----------|------------|----------|
|          |       |          |            |          |

#### 6.2.1.8. Software Deployment Evidence for Sprint Review

#### 6.2.1.9. Team Collaboration Insights during Sprint

| Integrantes | Tarea asignada |
|-------------|----------------|
|             |                |

<hr class="page-break">

### 6.2.2. Sprint 2

#### 6.2.2.1. Sprint Planning 2

| Sprint # | Fecha | Hora | Lugar | Preparado por | Asistentes |
|----------|-------|------|-------|---------------|------------|
| Sprint 2 |       |      |       |               |            |

| Sprint Goal & User Stories | |
|----------------------------|-|
| Sprint 2 Goal              |  |
| Sprint 2 Velocity          |  |
| Sum of Story Points        |  |

#### 6.2.2.2. Aspect Leaders and Collaborators

| Team Member | GitHub Username | Aspect | Role |
|-------------|-----------------|--------|------|
|             |                 |        |      |

#### 6.2.2.3. Sprint Backlog 2

| Sprint # | User Story | Work-Item / Task | Descripción | Estimación (horas) | Asignado a | Estado |
|----------|------------|------------------|-------------|-------------------|------------|--------|
| Sprint 2 |            |                  |             |                   |            |        |

#### 6.2.2.4. Development Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 6.2.2.5. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 6.2.2.6. Execution Evidence for Sprint Review

#### 6.2.2.7. Services Documentation Evidence for Sprint Review

| Servicio | Verbo | Endpoint | Parámetros | Response |
|----------|-------|----------|------------|----------|
|          |       |          |            |          |

#### 6.2.2.8. Software Deployment Evidence for Sprint Review

#### 6.2.2.9. Team Collaboration Insights during Sprint

| Integrantes | Tarea asignada |
|-------------|----------------|
|             |                |

<hr class="page-break">

### 6.2.3. Sprint 3

#### 6.2.3.1. Sprint Planning 3

| Sprint # | Fecha | Hora | Lugar | Preparado por | Asistentes |
|----------|-------|------|-------|---------------|------------|
| Sprint 3 |       |      |       |               |            |

| Sprint Goal & User Stories | |
|----------------------------|-|
| Sprint 3 Goal              |  |
| Sprint 3 Velocity          |  |
| Sum of Story Points        |  |

#### 6.2.3.2. Aspect Leaders and Collaborators

| Team Member | GitHub Username | Aspect | Role |
|-------------|-----------------|--------|------|
|             |                 |        |      |

#### 6.2.3.3. Sprint Backlog 3

| Sprint # | User Story | Work-Item / Task | Descripción | Estimación (horas) | Asignado a | Estado |
|----------|------------|------------------|-------------|-------------------|------------|--------|
| Sprint 3 |            |                  |             |                   |            |        |

#### 6.2.3.4. Development Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 6.2.3.5. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 6.2.3.6. Execution Evidence for Sprint Review

#### 6.2.3.7. Services Documentation Evidence for Sprint Review

| Servicio | Verbo | Endpoint | Parámetros | Response |
|----------|-------|----------|------------|----------|
|          |       |          |            |          |

#### 6.2.3.8. Software Deployment Evidence for Sprint Review

#### 6.2.3.9. Team Collaboration Insights during Sprint

| Integrantes | Tarea asignada |
|-------------|----------------|
|             |                |

<hr class="page-break">

### 6.2.4. Sprint 4

#### 6.2.4.1. Sprint Planning 4

| Sprint # | Fecha | Hora | Lugar | Preparado por | Asistentes |
|----------|-------|------|-------|---------------|------------|
| Sprint 4 |       |      |       |               |            |

| Sprint Goal & User Stories | |
|----------------------------|-|
| Sprint 4 Goal              |  |
| Sprint 4 Velocity          |  |
| Sum of Story Points        |  |

#### 6.2.4.2. Aspect Leaders and Collaborators

| Team Member | GitHub Username | Aspect | Role |
|-------------|-----------------|--------|------|
|             |                 |        |      |

#### 6.2.4.3. Sprint Backlog 4

| Sprint # | User Story | Work-Item / Task | Descripción | Estimación (horas) | Asignado a | Estado |
|----------|------------|------------------|-------------|-------------------|------------|--------|
| Sprint 4 |            |                  |             |                   |            |        |

#### 6.2.4.4. Development Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 6.2.4.5. Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit ID | Commit Message | Commit Message Body | Committed on (Date) |
|------------|--------|-----------|----------------|---------------------|---------------------|
|            |        |           |                |                     |                     |

#### 6.2.4.6. Execution Evidence for Sprint Review

#### 6.2.4.7. Services Documentation Evidence for Sprint Review

| Servicio | Verbo | Endpoint | Parámetros | Response |
|----------|-------|----------|------------|----------|
|          |       |          |            |          |

#### 6.2.4.8. Software Deployment Evidence for Sprint Review

#### 6.2.4.9. Team Collaboration Insights during Sprint

| Integrantes | Tarea asignada |
|-------------|----------------|
|             |                |

<hr class="page-break">

## 6.3. Validation Interviews

### 6.3.1. Diseño de Entrevistas

### 6.3.2. Registro de Entrevistas

### 6.3.3. Evaluaciones según heurísticas

<hr class="page-break">

## 6.4. Video About-the-Product

<hr class="page-break">

# Conclusiones

## Conclusiones y recomendaciones

## Video About-the-Team

<hr class="page-break">

# Bibliografía

<hr class="page-break">

# Anexos

## Links