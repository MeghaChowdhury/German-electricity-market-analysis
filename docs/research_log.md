# Research Log

This document records the development of the project, including decisions,
questions, observations, problems and changes in direction.

## 13 September 2026 - Project Setup & Data Collection

### Goal

I started this project to build an end-to-end data analytics portfolio project
using Python, SQL and Power BI while working with real-world energy market data.

### Initial Research Question

How did Germany's electricity market evolve between 2021 and 2025, and how are
changes in generation, electricity demand and renewable penetration associated
with wholesale electricity prices?

This is an initial broad research question and may change as the exploratory
analysis develops.

### Data Source

Data was obtained from the SMARD electricity market platform of the German
Federal Network Agency (Bundesnetzagentur).

Period: 01.01.2021 – 31.12.2025  
Resolution: Hourly

Three datasets were collected:

1. Actual electricity generation by energy source
2. Actual electricity consumption
3. Wholesale electricity prices

### Initial Questions

Before analysing the data, I am interested in exploring:

- How has Germany's electricity generation mix changed since 2021?
- How have wind and solar generation developed?
- What happened to electricity prices during the 2022 energy crisis?
- When and why do negative electricity prices occur?
- How is residual load related to wholesale electricity prices?
- How did electricity demand change during this period?
- Are electricity price movements similar across neighbouring European markets?

### Next Step

The next step is to inspect the raw datasets in Python and understand their
structure, variables, data types, missing values and potential data-quality
issues before performing any cleaning.