# Arm Telemetry – DITA Structured Content Demo

This repository is a self-directed technical writing project exploring how
structured authoring and content reuse could be applied to processor telemetry
documentation.

The project uses publicly available Arm telemetry documentation as a technical
domain for practising DITA, Git-based documentation workflows, and reusable
technical content.

## Project goals

The repository demonstrates:

- structured technical authoring using DITA XML
- concept and reference topic types
- topic organisation using a DITA map
- reusable content using `conref`
- reusable terminology and links using `keyref`
- Git/GitHub-based documentation management
- technical research and information modelling for an unfamiliar engineering domain

## Technical domain

The sample content explores processor telemetry concepts including:

- Performance Monitoring Unit (PMU) counters
- telemetry metrics
- the Arm Telemetry Solution
- the Topdown performance-analysis methodology
- relationships between architectural concepts and implementation-specific metrics

The objective is not to reproduce Arm documentation, but to demonstrate how
complex technical information can be analysed, structured, and presented as
modular documentation.

## Repository structure

```text
concepts/      Conceptual explanations of telemetry topics
tasks/         Procedural content
reference/     Metric and technical reference information
reusable/      Reusable DITA content
telemetry.ditamap
