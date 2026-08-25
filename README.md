# FRAM Software & Tools

### A community-maintained overview of software supporting the Functional Resonance Analysis Method

This repository provides a structured overview of software, applications, and digital tools related to the **Functional Resonance Analysis Method (FRAM)**.

The purpose of this repository is to help researchers, practitioners, educators, students, and developers:

- Discover available FRAM tools
- Understand the purpose of each tool
- Identify which tool may support a particular modelling task
- Find official access, download, documentation, and support routes
- Compare typical workflows and technical requirements
- Connect software with models, learning materials, and publications
- Make current maintenance and development status visible

The tools presented here cover different stages of the FRAM modelling workflow, including:

1. Data acquisition
2. Model creation
3. Model structuring
4. Analysis and interpretation
5. Exploration and simulation
6. Decision support

> This repository is a community catalogue. Unless explicitly stated otherwise, the FRAMily Community does not own, certify, validate, maintain, or provide technical support for the independently developed tools listed here.

---

## Quick Tool Overview

| Tool | Main Purpose | Platform / Technical Basis | Access |
|------|--------------|----------------------------|--------|
| **FMV: FRAM Model Visualiser** | Visual model creation, checking, cycle-by-cycle interpretation, and metadata-based simulation | Progressive Web App; modern browser; Blazor WebAssembly and .NET 8.0 | [Access the FMV Community Edition](https://github.com/functionalresonance/FMV_Community_Edition) |
| **myFRAM** | Systematic, tabular, data-driven preparation and analysis of large FRAM models | Microsoft Excel add-in; VBA; Windows and Mac | [Access myFRAM](https://sites.google.com/uniroma1.it/resilienceperspectives/myfram) |
| **DynaFRAM** | Animation and visualisation of scenario instantiations over a FRAM model | Standalone desktop application; Windows | [Access DynaFRAM](https://www.engr.mun.ca/~d.smith/dynafram.html) |
| **FRAMalyse** | Structured quantitative analysis and evaluation of FRAM model characteristics | Free standalone desktop application; MATLAB App Designer; Windows 10 or later | [Access FRAMalyse](https://www.mec.ed.tum.de/en/lfe/research/sociotechnical-modeling/software-tool-framalyse/?utm_source=chatgpt.com) |
| **FRAMifier** | Browser-based model creation, multi-level abstraction, expressions, and dynamic simulation | HTML, CSS, and JavaScript | [Access FRAMifier on GitHub](https://github.com/pwgbots/framifier) |
| **FRAMLab** | Next-generation platform for dynamic simulation, advanced analytics, and integration | Browser-based open-source research platform; work in progress | [Open the FRAMLab preview](https://fmv.benjaoued.de/) |

---

## Choosing a Tool

The tools serve complementary purposes rather than representing interchangeable versions of the same software.

### Start with FMV if you want to:

- Create and edit a visual FRAM model
- Check model syntax and consistency
- Identify orphan functions or missing aspects
- Interpret a model cycle by cycle
- Add metadata and equations
- Explore scenario instantiations
- Export tables or graphics

### Start with myFRAM if you want to:

- Develop a large model through structured tables
- Work with 50 or more functions
- Check the completeness of couplings
- Generate network metrics or a Resilience Analysis Matrix
- Colour-code model elements by agent, organisation, or process
- Export the completed model to FMV

### Start with DynaFRAM if you want to:

- Animate a scenario over an existing FRAM model
- Communicate an instantiation through video
- Create images at selected times in a scenario
- Explore and communicate work-as-done variability
- Control playback speed and display text during an animation

### Start with FRAMalyse if you want to:

- Analyse structural characteristics quantitatively
- Identify highly connected functions
- Explore critical variability propagation paths
- Calculate and visualise structural complexity indicators
- Compare versions of a FRAM model
- Produce communication-oriented analytical outputs

### Start with FRAMifier if you want to:

- Build a FRAM model in a browser
- Work across several abstraction levels
- Use subfunctions and composite functions
- Add variables and expressions as metadata
- Develop verifiable activation logic
- Observe a dynamic model through a simulation monitor

### Explore FRAMLab if you want to investigate:

- Time-based rather than only cycle-based simulation
- Monte Carlo and sensitivity analysis
- What-if comparison
- Comparison of Work-as-Imagined and Work-as-Done
- Abstraction/Agency and Space-Time/Agency matrices
- Path visualisation beyond direct couplings
- Real-time exchange with other tools, simulators, or Digital Twin applications

FRAMLab is currently described as a work-in-progress research platform.

---

# Tool Catalogue

## 1. FMV: FRAM Model Visualiser

> **From qualitative FRAM models to dynamic, quantitative simulation of emergence.**

### Overview

The **FRAM Model Visualiser (FMV)** is an established visual environment for creating, editing, checking, interpreting, and exploring FRAM models.

The Community Edition is an open and free tool. It runs as a Progressive Web App in a modern browser and can be installed for offline use.

### Primary Uses

FMV supports:

- Visual model creation and editing
- Syntactic and consistency checking
- Detection of orphan functions
- Identification of missing aspects
- Definition of foreground and background functions
- Definition of entry and exit functions
- Cycle-by-cycle interpretation through FMI
- Instantiation of potential couplings into actual couplings
- Metadata-based quantitative simulation
- Conditional activation and branching
- Tabular model views
- Export of tables and images
- Creation and reuse of `.xfmv` project files

### Typical Workflow

Build functions
→ add aspects
→ couple functions through shared names
→ run FMI cycle by cycle
→ add metadata and equations
→ simulate instantiations
→ export results
