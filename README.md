[![pages-build-deployment](https://github.com/janpreet/kado-presentation/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/janpreet/kado-presentation/actions/workflows/pages/pages-build-deployment)
# Kado Presentation

This repository contains a presentation showcasing the **Kado Infrastructure Automation Solution**, an orchestration platform designed to unify infrastructure management through modular configuration. This project highlights core functionalities, architectural decisions, workflow examples, and technical trade-offs involved in Kado’s design.

## Project Overview

Kado is a modular infrastructure automation tool that integrates with various infrastructure-as-code (IaC) tools, such as **Ansible**, **Terraform**, and **Terragrunt**, along with policy enforcement through **OPA** (Open Policy Agent) and secret management via **Keybase**. The solution was built with the goal of simplifying and unifying infrastructure deployments, enhancing configuration consistency, security, and operational efficiency.

## Key Objectives

- **Configuration Consistency**: Provide a single source of truth for configurations, reducing drift across environments.
- **Security Compliance**: Integrate robust policy enforcement and secure secrets management.
- **Reliability and Efficiency**: Streamline workflows to improve deployment reliability and performance.
- **Cross-tool Orchestration**: Seamlessly connect with various IaC tools under one system.
- **Policy Enforcement**: Ensure infrastructure changes align with security policies and organizational standards.

## Presentation Structure

This presentation is divided into five slides, each highlighting a different aspect of the Kado solution:

1. **Introduction to Kado**: Overview of Kado’s core objectives and challenges addressed.
2. **Technical Architecture**: Key architectural decisions and modular bead system design.
3. **Workflow Example**: Step-by-step sequence demonstrating Kado’s configuration and policy validation process.
4. **Technical Trade-offs**: Considerations in design decisions, such as custom formats and integration approaches.
5. **Future Roadmap and State Diagram**: An overview of the current status, roadmap, and state diagram of the Kado solution.

## Technologies Used

- **Frontend**: HTML, CSS, and [Mermaid](https://mermaid-js.github.io/mermaid/#/) for visualizing architecture diagrams.
- **Kado's Primary Languages and Tools**: Go, Ansible, Terraform, Terragrunt, OPA, Keybase.

## Key Diagrams

The presentation includes Mermaid diagrams to illustrate various aspects of the Kado solution:
- **Core Architecture**: Displays the relationship between configuration, security layers, and execution tools.
- **Workflow Sequence**: Step-by-step flow from configuration loading to policy validation and execution.
- **Class Diagram**: Showcases the primary classes in Kado, like `Bead`, `Config`, `PolicyEngine`, and `Executor`.
- **State Diagram**: Visual representation of the Kado processing lifecycle, including success and failure paths.

## Viewing the Presentation

You can view the presentation directly by navigating through the slides using the "Previous" and "Next" buttons on each slide. Each slide includes key visuals and highlights to guide the narrative around Kado’s design and implementation.
