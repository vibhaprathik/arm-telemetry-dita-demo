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
reference/     Metric and technical reference information
reusable/      Reusable DITA content
telemetry.ditamap
```
## DITA features demonstrated

This project contains practical examples of several DITA structured-authoring techniques:

- **Concept topics** – processor telemetry and Topdown analysis are documented as standalone concept topics.
- **Reference content** – telemetry metric information is modelled as a DITA reference topic.
- **Content reuse with `conref`** – reusable PMU and metric definitions are maintained in a shared topic and reused by other topics.
- **Indirect linking with `keyref`** – topic relationships use keys defined in the DITA map rather than hard-coded file references.
- **DITA map** – `telemetry.ditamap` defines the information structure and topic relationships.
- **Docs-as-code workflow** – source content is maintained as XML in Git and developed through incremental commits.

## Project scope

This is an independent learning and technical-writing portfolio project. It uses publicly available Arm documentation as the technical domain for practising structured authoring and content reuse.

It is not official Arm documentation and does not contain confidential or proprietary Arm information.
