# Domain-specific languages

## aDSL
See: [aDSL](https://github.com/fatvdbergdotus/adsl)

The `adsl` (Agricultural DSL) project is a domain-specific language and accompanying tooling framework for modeling agricultural cyber-physical systems. Based on the concepts presented in the paper *Designing Cyber-Physical Systems with aDSL: A Domain-Specific Language and Tool Support*, the language provides higher-level abstractions for describing system components, interactions, and behaviors in agricultural environments, helping engineers manage the complexity of integrating software, hardware, communication, and physical processes. The repository contains the Xtext grammar, validation and scoping rules, code-generation infrastructure, and example models derived from research papers, demonstrating how DSL-based modeling can improve clarity, maintainability, stakeholder communication, and productivity when designing complex agricultural cyber-physical systems.

## iDSL
See: [iDSL](https://github.com/fatvdbergdotus/idsl)

The `idsl` (Imaging DSL) project is a domain-specific language and toolchain for modeling, simulating, and evaluating the performance of complex medical imaging systems, particularly interventional X-ray (iXR) platforms. The language provides high-level abstractions for defining processes, resources, mappings, scenarios, performance measures, and studies, enabling engineers to analyze latency, resource utilization, concurrency effects, and timing guarantees early in the design process. iDSL models can be automatically transformed into formal analysis models for simulation and model checking, producing artifacts such as latency breakdown charts, cumulative distribution functions (CDFs), resource utilization metrics, and absolute timing bounds. The repository contains the language implementation, grammar, and example models—including a Philips Biplane iXR system and the imaging system used in the author's PhD thesis—demonstrating how domain-specific modeling and automated formal analysis can support architecture evaluation and performance optimization of medical cyber-physical systems.

## QRML
See: [QRML](https://qrml.org/) (external link)

The Quality and Resource Modeling Language (QRML) is a domain-specific language and toolset for modeling, analyzing, and optimizing quality and resource management in complex cyber-physical systems. QRML enables engineers to describe heterogeneous hardware and software components, their configurations, resource consumption and provision, functionality, and quality attributes such as performance, latency, and energy usage within a hierarchical component model. Based on a formal interface-modeling framework, the language supports automated reasoning, constraint solving, multi-objective optimization, configuration exploration, visualization, documentation generation, and the generation of monitoring artifacts, helping designers identify optimal system configurations that satisfy resource, quality, and operational constraints in embedded and cyber-physical systems.

## Getting started
Two manuals:
- Manual [Creating a Domain Specific Language (DSL) with Xtext in Eclipse](http://www.cs.ru.nl/J.Hooman/DSL/Creating_a_Domain_Specific_Language_(DSL)_with_Xtext.pdf).
- [Advanced Xtext Manual on Modularity](http://www.cs.ru.nl/J.Hooman/DSL/AdvancedXtextManual.pdf)
