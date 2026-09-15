````markdown
# UNIVERSAL BRAND INTELLIGENCE

A universal AI brand strategy, creative direction, and brand execution system.

---

## Overview

UNIVERSAL BRAND INTELLIGENCE is a modular AI system designed to help transform raw client information into a complete, strategically grounded, and consistently executed brand.

The system is designed to work across different:

- industries
- business models
- market segments
- brand sizes
- visual styles
- product categories
- service categories
- creative directions

The system does not assume that every brand should be:

- luxury
- minimalist
- modern
- premium
- feminine
- masculine
- playful
- editorial

Instead, every decision must be derived from the specific brand, its audience, market, objectives, and fundamental needs.

---

# Core Philosophy

The system follows one fundamental principle:

> Understand the real problem before designing the solution.

The AI should not blindly execute what a client initially asks for.

A client may provide:

- a requested logo
- a preferred color
- a visual reference
- a website style
- a packaging idea
- a campaign concept

These inputs are treated as signals of intent, not automatically as the correct solution.

The system should identify:

1. What the client wants.
2. Why they want it.
3. What problem they are trying to solve.
4. What assumptions are behind the request.
5. What the market currently does.
6. What patterns are effective.
7. What fundamental need exists underneath the problem.
8. Whether the requested solution is actually the strongest solution.
9. How to reconstruct the solution from first principles.

The objective is not to imitate trends.

The objective is to understand the principles behind what works and use those principles to create a stronger solution.

---

# Master Workflow

The system follows this general workflow:

```text
DISCOVER
    ↓
ANALYZE
    ↓
DEFINE
    ↓
SYSTEMIZE
    ↓
CREATE
    ↓
VALIDATE
    ↓
DELIVER
````

### 1. Discover

Collect and understand the client's:

* business
* product or service
* audience
* problem
* ambition
* market
* competitors
* references
* preferences
* constraints
* objectives

### 2. Analyze

Analyze:

* client information
* market patterns
* competitors
* visual references
* trends
* customer needs
* strategic opportunities
* weaknesses
* contradictions
* assumptions

### 3. Define

Define the strategic foundation:

* purpose
* vision
* mission
* values
* positioning
* value proposition
* promise
* personality
* differentiation
* brand essence

### 4. Systemize

Translate strategy into systems:

* visual identity
* verbal identity
* logo
* color
* typography
* photography
* packaging
* digital
* social
* campaign
* AI prompt rules

### 5. Create

Produce the required creative outputs based on the established brand system.

### 6. Validate

Check whether the output:

* solves the intended problem
* reflects the strategy
* fits the audience
* maintains differentiation
* follows the visual system
* follows brand guidelines
* avoids brand drift

### 7. Deliver

Provide the final production-ready output in the format requested.

---

# System Architecture

```text
UNIVERSAL-BRAND-INTELLIGENCE.skill/
│
├── SKILL.md
│
├── INPUTS/
│   └── CLIENT-DISCOVERY-FORM.md
│
├── CLIENTS/
│   ├── VELORA.md
│   ├── CLIENT-B.md
│   └── CLIENT-C.md
│
├── TEMPLATES/
│   ├── BRAND-STRATEGY.md
│   ├── VISUAL-SYSTEM.md
│   └── BRAND-GUIDELINES.md
│
├── MODULES/
│   ├── LOGO.md
│   ├── COLOR.md
│   ├── TYPOGRAPHY.md
│   ├── PHOTOGRAPHY.md
│   ├── PACKAGING.md
│   ├── DIGITAL.md
│   ├── SOCIAL.md
│   └── CAMPAIGN.md
│
├── ENGINES/
│   ├── DISCOVERY.md
│   ├── STRATEGY.md
│   ├── CREATIVE.md
│   ├── COPY.md
│   ├── AI-PROMPT.md
│   └── BRAND-GUARDIAN.md
│
└── OUTPUTS/
    ├── LOGO/
    ├── PACKAGING/
    ├── WEBSITE/
    ├── SOCIAL/
    ├── CAMPAIGN/
    └── AI-PROMPTS/
```

---

# Directory Responsibilities

## SKILL.md

The master operating system of the entire skill.

It defines:

* how the AI should think
* how the AI should behave
* how information should be interpreted
* how the different engines interact
* how brand consistency is maintained
* how outputs should be validated

`SKILL.md` is the highest-level instruction layer.

---

# INPUTS

## CLIENT-DISCOVERY-FORM.md

The client-facing discovery framework.

Its purpose is to collect the minimum information required to understand a brand before strategic or creative development begins.

The form should capture information about:

* brand
* offer
* origin
* ambition
* audience
* customer problem
* differentiation
* competitors
* desired perception
* undesired perception
* personality
* visual direction
* references
* business objectives
* constraints
* future direction

The form is intentionally limited to a practical number of questions.

The objective is not to interrogate the client.

The objective is to obtain enough information to build a reliable internal Client Profile.

---

# CLIENTS

The `CLIENTS/` directory contains client-specific source-of-truth files.

Each client should have an isolated file.

Example:

```text
CLIENTS/
├── VELORA.md
├── CLIENT-B.md
└── CLIENT-C.md
```

A client file contains the processed understanding of that specific brand.

It may include:

* business foundation
* customer foundation
* market context
* strategic decisions
* brand personality
* verbal identity
* visual DNA
* visual system
* brand rules
* constraints
* approved decisions
* important references
* brand-specific AI instructions

### Client Isolation Rule

Information from one client must never automatically influence another client.

For example:

```text
VELORA
    ↓
VELORA.md
    ↓
VELORA strategy
    ↓
VELORA creative output
```

must remain separate from:

```text
CLIENT-B
    ↓
CLIENT-B.md
    ↓
CLIENT-B strategy
    ↓
CLIENT-B creative output
```

---

# TEMPLATES

Templates define universal structures for major brand documents.

They are not client-specific.

## BRAND-STRATEGY.md

Defines the structure for strategic brand development.

It covers areas such as:

* business foundation
* customer foundation
* market analysis
* competitive analysis
* first-principles analysis
* positioning
* value proposition
* brand promise
* personality
* differentiation
* strategic priorities
* strategic guardrails

---

## VISUAL-SYSTEM.md

Defines the structure for developing a complete visual language.

It covers:

* visual DNA
* visual principles
* visual personality
* semiotics
* composition
* color
* typography
* logo
* photography
* material
* graphic language
* iconography
* illustration
* motion
* digital
* social
* packaging
* environmental applications
* AI visual translation
* visual consistency

---

## BRAND-GUIDELINES.md

Defines how the established brand system should be used and governed.

It covers:

* logo rules
* color rules
* typography rules
* layout
* photography
* illustration
* iconography
* materials
* digital
* social
* packaging
* AI generation
* brand drift prevention
* governance
* version control
* quality control

### Important distinction

```text
BRAND STRATEGY
= What the brand should mean and achieve

VISUAL SYSTEM
= How that meaning becomes a visual language

BRAND GUIDELINES
= How that visual and verbal system must be used
```

---

# MODULES

Modules are specialized execution frameworks.

They should not independently redefine the brand strategy.

They execute decisions established by:

```text
Client Profile
        ↓
Brand Strategy
        ↓
Visual System
        ↓
Brand Guidelines
        ↓
Module
```

## LOGO.md

Controls logo development and evaluation.

## COLOR.md

Controls color system development and usage.

## TYPOGRAPHY.md

Controls typeface selection, hierarchy, pairing, and application.

## PHOTOGRAPHY.md

Controls photographic direction, composition, lighting, subject treatment, and image consistency.

## PACKAGING.md

Controls packaging architecture, hierarchy, materials, finishes, and product presentation.

## DIGITAL.md

Controls digital brand expression including websites and digital interfaces.

## SOCIAL.md

Controls social media visual and content systems.

## CAMPAIGN.md

Controls campaign development and campaign-level creative consistency.

---

# ENGINES

Engines are the reasoning and transformation systems of the skill.

They determine how information becomes decisions and outputs.

## DISCOVERY.md

Transforms raw client information into a reliable Client Profile.

Primary responsibilities:

```text
Client Input
    ↓
Interpretation
    ↓
Analysis
    ↓
First-Principles Thinking
    ↓
Problem Decomposition
    ↓
Fundamental Need
    ↓
Client Profile
```

---

## STRATEGY.md

Transforms the Client Profile into a strategic brand foundation.

```text
Client Profile
    ↓
Strategic Analysis
    ↓
Brand Strategy
```

---

## CREATIVE.md

Transforms strategy and visual systems into creative concepts and applications.

```text
Strategy
    +
Visual System
    ↓
Creative Direction
    ↓
Creative Output
```

---

## COPY.md

Controls verbal identity and brand communication.

It ensures that copy reflects:

* positioning
* personality
* audience
* emotional territory
* brand promise
* strategic intent

---

## AI-PROMPT.md

Transforms brand systems into production-ready AI prompts.

AI prompts should encode the brand rather than merely describe an attractive image.

A prompt may incorporate:

* brand DNA
* visual category
* subject
* composition
* material
* lighting
* human element
* color
* camera
* output format
* negative rules

---

## BRAND-GUARDIAN.md

Acts as the final consistency and quality control layer.

It evaluates whether an output:

* belongs to the brand
* follows strategic decisions
* follows visual rules
* maintains differentiation
* avoids generic aesthetics
* avoids brand drift
* remains appropriate for the intended audience

---

# OUTPUTS

The `OUTPUTS/` directory contains final execution outputs.

```text
OUTPUTS/
├── LOGO/
├── PACKAGING/
├── WEBSITE/
├── SOCIAL/
├── CAMPAIGN/
└── AI-PROMPTS/
```

These folders organize production-ready deliverables.

Examples:

```text
OUTPUTS/LOGO/
    logo concepts
    logo prompts
    logo specifications

OUTPUTS/PACKAGING/
    packaging concepts
    packaging prompts
    packaging directions

OUTPUTS/WEBSITE/
    website concepts
    UI directions
    website prompts

OUTPUTS/SOCIAL/
    social concepts
    post systems
    social prompts

OUTPUTS/CAMPAIGN/
    campaign concepts
    campaign directions
    campaign prompts

OUTPUTS/AI-PROMPTS/
    production-ready AI prompts
    image generation prompts
    visual consistency prompts
```

---

# Information Hierarchy

The system follows this hierarchy:

```text
UNIVERSAL SYSTEM
        ↓
CLIENT PROFILE
        ↓
BRAND STRATEGY
        ↓
VISUAL SYSTEM
        ↓
BRAND GUIDELINES
        ↓
ENGINES
        ↓
MODULES
        ↓
OUTPUTS
```

Each layer has a specific responsibility.

The system should not skip layers when they are necessary for a reliable decision.

---

# First-Principles Intelligence

The system uses first-principles reasoning as a core problem-solving method.

The general process is:

```text
STUDY
  ↓
ANALYZE
  ↓
IDENTIFY PATTERNS
  ↓
IDENTIFY PROBLEM
  ↓
DECOMPOSE PROBLEM
  ↓
ASK WHY
  ↓
FIND FUNDAMENTAL NEED
  ↓
RECONSTRUCT
  ↓
CREATE NEW SOLUTION
```

This prevents the system from simply copying:

* competitors
* trends
* references
* popular aesthetics
* client assumptions

Instead, the system extracts the underlying principles that make something effective.

---

# Trend Intelligence

Trends should be studied as signals, not instructions.

The system should ask:

* Why is this trend working?
* What customer behavior is behind it?
* What visual pattern is becoming popular?
* What psychological need does it satisfy?
* Is the trend temporary or structural?
* Can the underlying principle be adapted?
* Would following the trend strengthen or weaken differentiation?

The system should never copy a trend simply because it is popular.

---

# Client Intent vs. Client Solution

A client request may represent a desired outcome rather than the best implementation.

For example:

```text
CLIENT:
"I want a minimalist logo."

SYSTEM:
"What is the client actually trying to achieve?"

Possible underlying needs:

- easier recognition
- premium perception
- flexibility
- memorability
- digital scalability
- differentiation
```

The system should solve the underlying need rather than blindly obeying the surface-level request.

---

# Information Discipline

Every important piece of information should be understood as one of the following:

```text
FACT
ASSUMPTION
INTERPRETATION
RECOMMENDATION
```

The system should avoid presenting assumptions as facts.

When information is missing, it should be recognized as:

```text
UNKNOWN
```

Unknown information should not automatically be invented.

When the missing information materially affects the decision, the system should ask for clarification.

---

# Brand Drift Prevention

Every output should remain connected to the established brand system.

The system should reject or revise outputs that become:

* generic
* aesthetically attractive but strategically meaningless
* disconnected from the audience
* disconnected from positioning
* overly dependent on trends
* visually inconsistent
* derivative of competitors
* inconsistent with approved brand assets

---

# Quality Gate

Before final delivery, the system should evaluate:

1. Does this solve the intended problem?
2. Is it strategically justified?
3. Is it relevant to the target audience?
4. Is it distinctive?
5. Does it reflect the brand personality?
6. Does it follow the visual system?
7. Does it maintain consistency?
8. Does it avoid generic or derivative execution?
9. Is it practical and usable?
10. Does it strengthen the brand rather than merely decorate it?

If major criteria fail, the output should be revised before delivery.

---

# Operating Principles

The system follows these principles:

### 1. Understand before creating.

### 2. Strategy before aesthetics.

### 3. Meaning before decoration.

### 4. Fundamentals before trends.

### 5. Client intent before client assumptions.

### 6. Evidence before invention.

### 7. Differentiation before imitation.

### 8. System before isolated assets.

### 9. Consistency without rigidity.

### 10. Creativity with strategic justification.

---

# The Master Principle

The system can be summarized as:

```text
THE BRAIN
= Universal Intelligence System

THE BRAND
= Client Profile

THE ENGINES
= Reasoning & Transformation Capabilities

THE MODULES
= Specialized Execution Capabilities

THE OUTPUTS
= Final Creative Deliverables
```

The ultimate objective is:

> Build the strongest brand solution that can be strategically justified from the client's real needs, market context, audience, and fundamental problem.

Not merely:

> Create what looks good.

Not merely:

> Follow what is trending.

Not merely:

> Do exactly what the client initially requested.

But:

> Understand deeply, challenge intelligently, reconstruct from first principles, systemize the solution, and execute it consistently.

---

# Development Principle

This skill is designed to grow modularly.

New:

* clients
* templates
* modules
* engines
* output formats
* creative capabilities

can be added without changing the fundamental architecture.

The universal system should remain stable while client-specific information and specialized capabilities evolve independently.

---

# File Relationship

The intended relationship between the major files is:

```text
CLIENT-DISCOVERY-FORM.md
        ↓
   DISCOVERY ENGINE
        ↓
   CLIENT PROFILE
        ↓
 BRAND-STRATEGY.md
        ↓
  STRATEGY ENGINE
        ↓
 VISUAL-SYSTEM.md
        ↓
 CREATIVE ENGINE
        ↓
 BRAND-GUIDELINES.md
        ↓
 MODULES
        ↓
 AI-PROMPT ENGINE
        ↓
 BRAND-GUARDIAN
        ↓
     OUTPUTS
```

---

# Current Development Status

## Core

* [x] SKILL.md

## Inputs

* [x] CLIENT-DISCOVERY-FORM.md

## Client Profiles

* [ ] VELORA.md
* [ ] CLIENT-B.md
* [ ] CLIENT-C.md

## Templates

* [x] BRAND-STRATEGY.md
* [x] VISUAL-SYSTEM.md
* [x] BRAND-GUIDELINES.md

## Modules

* [ ] LOGO.md
* [ ] COLOR.md
* [ ] TYPOGRAPHY.md
* [ ] PHOTOGRAPHY.md
* [ ] PACKAGING.md
* [ ] DIGITAL.md
* [ ] SOCIAL.md
* [ ] CAMPAIGN.md

## Engines

* [ ] DISCOVERY.md
* [ ] STRATEGY.md
* [ ] CREATIVE.md
* [ ] COPY.md
* [ ] AI-PROMPT.md
* [ ] BRAND-GUARDIAN.md

## Outputs

* [ ] LOGO
* [ ] PACKAGING
* [ ] WEBSITE
* [ ] SOCIAL
* [ ] CAMPAIGN
* [ ] AI-PROMPTS

---

# Recommended Build Order

The system should preferably be completed in this order:

```text
1. SKILL.md
2. CLIENT-DISCOVERY-FORM.md
3. DISCOVERY.md
4. STRATEGY.md
5. BRAND-STRATEGY.md
6. VISUAL-SYSTEM.md
7. CREATIVE.md
8. COPY.md
9. LOGO.md
10. COLOR.md
11. TYPOGRAPHY.md
12. PHOTOGRAPHY.md
13. PACKAGING.md
14. DIGITAL.md
15. SOCIAL.md
16. CAMPAIGN.md
17. AI-PROMPT.md
18. BRAND-GUARDIAN.md
19. BRAND-GUIDELINES.md
20. CLIENT PROFILES
21. OUTPUTS
```

The order may change during development when dependencies require it.

---

# Final Principle

UNIVERSAL BRAND INTELLIGENCE is not a collection of branding prompts.

It is a structured intelligence system for understanding brands, solving brand problems, building coherent brand systems, and producing consistent creative outputs.

The system should always move from:

```text
UNDERSTANDING
    ↓
REASONING
    ↓
STRATEGY
    ↓
SYSTEM
    ↓
CREATIVE
    ↓
EXECUTION
    ↓
VALIDATION
```

A strong output is not simply visually attractive.

A strong output is:

**Relevant.
Strategic.
Distinctive.
Coherent.
Useful.
Consistent.
Defensible.**

```

### Catatan penting

Saya sengaja membuat `README.md` ini sebagai **dokumentasi arsitektur**, bukan sebagai file instruksi utama. Jadi:

- `SKILL.md` = **otak / aturan operasi**
- `README.md` = **peta / dokumentasi sistem**
- `CLIENT-DISCOVERY-FORM.md` = **pintu masuk data klien**
- `CLIENTS/*.md` = **source of truth masing-masing brand**
- `TEMPLATES/*.md` = **kerangka dokumen**
- `ENGINES/*.md` = **mesin berpikir dan transformasi**
- `MODULES/*.md` = **kemampuan spesifik**
- `OUTPUTS/` = **hasil akhir**

Ada satu hal yang saya sengaja ubah dari urutan sebelumnya: **`DISCOVERY.md` saya tempatkan lebih awal dalam Recommended Build Order**, karena secara arsitektur ia menjadi penghubung antara `CLIENT-DISCOVERY-FORM.md` dan `CLIENTS/*.md`. Ini akan membuat sistem kita lebih masuk akal ketika nanti mulai mengimplementasikan workflow sebenarnya.
```
