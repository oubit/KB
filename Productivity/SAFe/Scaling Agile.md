# Getting Started

## Business Agility

- Agile Teams: concepto de equipo ágil ya indicado: autonomous, long lived...
- Agile delivery: DevOps
- Enterprise agility: básicamente adoptar SAFe, con sus value stream, ART, solution...
- Lean portfolio management: crear la capa de portfolio
- Agile organization: Desarrollo en el equipo de IT para dar servicio a toda la organización. Se involucra a todos los departamentos: legal, marketing, QA, financiero, seguridad...


## Agile Leaders

- Lead the change: Agile doesn´y grow on its own: leadership, funding, vision and management
- Know the way: where you want to go, your staff, need a guidance
- EMphasize lifelong learning: continuous learning, learning culture (time, formal training, practice...)
- Develop people: servant leaders, no technical leaders, focus on developing teams
- Inspire and align: with mission, northern star
- Minimize constraints: in your team, in the relationship with other teams
- Decentralize decision-making: empower the team. decision bottom-up
- Unlock intrinsic motivation: incentives, compensation, evaluations, agile HRM

## Coaches

Al principio, 1/10 personas deben ser Coach.
Después, 1/20.
Repartir entre externos e internos.

## Core Values

- Alignment
    - Strategic alignment: via Strategic Themes
    - Cadence and rituals: in every level
    - Arquitecture: specific roles
    - Priorization: via Portolio level
        - Epics -> Capabilities -> Features -> User Stories
        - Lean budgets -> Economic Framework
- Built-in quality
    - Periodic demo
    - Rituals: inspect
- Transparency: between levels and teams
- Program execution: via Program level

## Lean-agile mindset

- Respect for people and culture
- Flow
    - Descomposición de épicas hasta user stories
    - Cadencia y syncronización en Team Level
    - Ventajas Kanban:
        - WIP en Kanban en Portfolio, Solution y Program Level.
        - Lotes pequeños
        - Longitud de colas
- Innovation: in every level, bottom-up
- Relentless improvement: métricas

## Scaling principles

1. Take an economic view: vía lean budgets y economic framework
2. Apply systems thinking: los sistemas están interconectados entre ellos y con la organización. No perderlo de vista.
3. Assume variability; preserve options: postergar la toma de decisiones lo más posible, tendrás más información.
4. Build incrementally: with fast and integrated learning cycles
5. Base milestones on objective evaluation of working systems: la clave es hacerlo de manera periódica (demos) sobre sistemas funcionando
6. Kanban principles: visualize and limit the WIP, reduce batch sizes and manage queue lenghts
7. Apply cadence, syncronize with cross-domain planning: PI planning
8. Unlock the intrinsic motivation: 
9. Decentralize decision-making: short-term, frequent, local knowledge

## Team backlog

Requeriment types
- User/Business: funcionalidad para negocio, para el usuario final
- Improvement: mejora proveniente de retrospectiva
- Enabler: requerimiento técnico que no aporta valor al usuario pero es necesario para implementar las de negocio
- NFR (non-functional requeriment): securidad, rendimiento, legal...

## Alignment between teams

PI Plannign genera un Team PIO, objetivos del equipo hasta el próximo incremento.

## Architectural runway

Base para todos los desarrollos.
A nivel de program porque son varios equipos los que comparten una arquitectura.
El System Architect es el PO de la Architectural runway.
Enablers: historias habilitadoras, que permiten construir las de usuario. User Stiry distinto de Enabler story

# Solution

## Intent

La intención proviene de la épica de negocio.
El contexto (la solución) debe basarse en el cliente -> customer centric

Es como un repositorio donde se recogen todas las ideas, no es un backlog.

## Compliance

En vez de hacer fase para chequear con legal, incluirlos en el equipo directamente. Tendrás chequeo en el día a día.

## Spanning Palete

- Metrics: A todos los niveles
- Shared services
    - Legal
    - Expertos
    - -> Definir cómo interactuar con ellos, como conseguir predictibilidad (acuerdos de Kanban)
- CoP (community of practice): integrantes de los distintos equipos con mismos conocimientos
- Roadmaps & milestones: 
    - eventos demo prefijados: cadencia establecida
    - fijos: demos especiales, temas regulatorios...
- Vision: a nivel de portfolio, de solución y de programa
- System team: balance entre ellos y el equipo ágil
- Lean UX: quizás podría ser un shared service

# Portfolio

## Metrics

- Customer satisfaction
    - NPS
    - Surveys
- Partner health
    - Partner and vendor surveys
    - Relationships in the chain
- Productivity
    - Average cycle time
- Employee engagement
    - Turnover
    - Engagement
- Agility
    - Continous improvement
    - Self assessments
- Time-to-market
    - Release frequency
- Quality
    - Data defects
    - Defects

## Budgeting/Funding

Lean Governance - dynamic budgeting

# Program Increment

## ART in an Agile Organization

- Team of Teams: entre 50 y 125 personas
- Synchronization: cadencia, PI...
- Supporting processes
- Supporting roles: product management, System Architect, Release Train Engineer, Business owners
- Part of value stream

## Architecture

- Design emerges, architecture is a collaboration
- The bigger the system, the longer the runway 
    - Todos los equipos deben dedicar tiempo a enablers, cerca del 20%.
    - Puede haber equipos dedicados al 100% a producir enablers.
    - Los enablers deben seguir cumpliendo el ocupar un solo PI.
- Build the simplest architecture than can possibly work
- When in doubt, code or model it out
    - Hace referencia al Intent, que es donde está toda la documentación del sistema.
    - Hacer modelos que permitan avanzar y validar resultados. Estos modelos deben estar en el intent.
- They build it; They test it
- There's no monopoly on innovation
    - Las ideas provienen de todos los equipos
    - El arquitecto gestiona y prioriza
- Architectural flow
    - La sideas pueden venir de cualquier sitio.
    - Si caben en el PI y tienen sentido, el equipo es autosuficiente.
    - Si no, ascender para priorizar.

## Risks

Estados de los riesgos:
- Resolved: se ha resuelto solo
- Owned: asumido por el equipo, no para su resolución, si no para minimizarlo. Por ejemplo, dependencia con otro equipo.
- Accepted: permanece, se acepta como un hecho con el que hay que convivir
- Mitigated: se ha corregido vía acciones.

Descomponer y crear nuevos items para mitigarlos, que pueden ser a nivel de solución, programa o equipo.

## DevOps

- Increase frequency and quality of deployments
- Improve innovation and risk-taking
- Faster time to market
- Reduce severity and frequency of release failures
- Improme mean time of recovery

- Culture: of shared responsability
- Automate: everything
- Lean-flow: accelerates delivery. Visualize and limit WIP, reduce batch sizes and limit queue lenghts.
- Measure: everything
- Recovery: enables low-risk releases

## Continuous Pipeline

### Continuous deployment

- Decouple deployment from release
    - Deployment es un término técnico, desplegar (e integrar) en algún entorno.
    - Release es ofrecer nuevas funcionalidades al cliente (ya sea interno o externo).
    - Interesante la idea feature toggles. Se despliega en PROD pero no habilitado por defecto.

# Solution

Model-based
- Equilibrio entre diseño y ejecución
- Validar diseños que agilicen el desarrollo y consugan entregar valor más rápido

Set-based
- Preserve options
- Al no estar definido todo al principio, se mantienen opciones abiertas hasta que queda patente cual es la mejor/única opción.

## Splitting capabilities

Rules
- Equal effort
- You can delete part of it
- Limit dependencies as much as possible

Tecnics
- CRUD Operations: based on operations create, update, delete, read
- Workflow: identify steps in the process and implement them incrementally
- Business rules: reglas internas (ej. tipos de DNIs aceptados, qué hacer en casos de error...) 
- Data variation: mismo comportamiento pero diferenteconjunto de datps (p.e. idioma)
- Spikes: basado en investigaciones que haya que hacer
- Data entry: based on the way data is entered in the system
- Use case: happy flow and alternate flows.
- Simple/complex: implementar el core (simple) y después añadir extras (complex).
- Major effort: más simple vs más complejo
- Defer quality: critical functionality first

## Pre-PI

Se presentan las capabilities por parte del Solution Manager y el Solution Architect
Se descomponen en Feature por parte de los Product Manager y System Architect de todos los equipos ART

## Roles

Lo mismo que en Program.
- Solution Manager: hablar con Customer y gestión de Intent.
- Solution Architect: architectural runway
- Solution Train Engineer: gestión de rituales...

# Team

## Kanban

Es bueno para shared teams, como System o DevOps, no tanto para el desarrollo. Seguramente por que es más difícil sincronizarse y adquirir una cadencia fija.

# Advanced

## Identify Value Steams

1.- Make sure workshop participants have fundamental knowledge of LEAN and Agile (at sacle)
2.- Define outcomes of the workshop
3.- Define granularity of the value stream steps
4.- Don't hint or propose the outcome up-front
5.- Don't expect to be comprehensive

# Advanced

## Aquisition

Considerar al proveedor en sí mismo un Value Stream, y siguiendo el economic framework, el budget será dinámico en función del valor entregado.
Para ello, se deben tener las métricas validadas por ambas partes para medir el desempeño y vincular a ellas el budget.
Qué se hace con el presupuesto se determina en las I&A sessions al final del PI.