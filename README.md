[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched2026-JW163)](https://api.reuse.software/info/github.com/SAP-samples/teched2026-JW163)

# JW163 | From SAP Fiori elements to agent to Joule Work: The full stack, hands-on

## Description

This repository contains the material for the SAP TechEd 2026 session **JW163 - From SAP Fiori elements to agent to Joule Work: The full stack, hands-on**.

## Overview

In this session you build an SAP Fiori app with SAP Fiori elements and AI tooling, see how an agent can use an OData service to surface business data, and watch how the SAP Compositional Design System turns your data into enterprise UI at runtime in Joule Work.

The idea behind the session: to show you how the custom SAP Fiori apps and OData services that you have already built contribute to the Joule Work experience. In other words, they are an important asset, rather than becoming legacy code that needs to be replaced. They are machine-readable business knowledge that an AI can reuse. The OData service, its annotations, and its actions describe what the data means, how it connects, and what a user can do with it. When an AI reuses that description, it produces best-fitting results and output that looks familiar to users who already know the app. You experience this across three parts.

## The three parts

- **Part 1 - Build a custom SAP Fiori app.** Using SAP Business Application Studio and its AI tooling, you generate a working SAP Fiori elements application from an image. This gives you a custom app and an OData service: the business knowledge the later parts build on.

- **Part 2 - From app to agent.** Using SAP Joule Studio, you see how an OData service can be used by an agent to surface business data, and get a hands-on feel for how that works, using the SFlight scenario available in SAP Joule Studio.

- **Part 3 - Compositional Design System.** You get a labs preview of the SAP Compositional Design System tool, to see how AI assembles enterprise UI from your data at runtime, and how that same rendering powers the experience in Joule Work.

By the end you will have built a custom Fiori app with AI tooling, seen how an OData service can be used by an agent, and seen how the SAP Compositional Design System renders that data into enterprise UI. The apps you already invest in make your Joule Work experience better, not obsolete.

## Requirements

The requirements to follow the exercises in this repository are provided at the start of each part. In general you need a modern browser and the pre-provisioned workshop accounts handed out during the session. No local installation is required.

## Exercises

- **Part 1 - Build a custom SAP Fiori app**
    - [Exercise 1.0 - Set up your AI development environment](exercises/ex1/ex1.0/)
    - [Exercise 1.1 - Create a CAP project and SAP Fiori app from an image](exercises/ex1/ex1.1/)
    - [Exercise 1.2 - Enable automatic data loading in List Report](exercises/ex1/ex1.2/)
    - [Exercise 1.3 - Add destination column to List Report table](exercises/ex1/ex1.3/)
    - [Exercise 1.4 - Add an analytical column chart to the List Report](exercises/ex1/ex1.4/)

- **Part 2 - From app to agent**
    - [Exercise 2 - Build an Agent with Joule Studio](exercises/ex2/)

- **Part 3 - Compositional Design System**
    - [Exercise 3.0 - Getting Started](exercises/ex3/3.0-getting-started/)
    - [Exercise 3.1 - Understand the Concepts](exercises/ex3/3.1-concepts/)
    - [Exercise 3.2 - Author and Generate](exercises/ex3/3.2-author/)
    - [Exercise 3.3 - Explore on Your Own](exercises/ex3/3.3-explore/)

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## Contributing

Please read the [CONTRIBUTING.md](./CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct

Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## License

Copyright (c) 2026 SAP SE or an SAP affiliate company and teched2026-JW163 contributors. Please see our [LICENSE](LICENSE) for copyright and license information. Detailed information including third-party components and their licensing/copyright information is available [via the REUSE tool](https://api.reuse.software/info/github.com/SAP-samples/teched2026-JW163).
