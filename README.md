# LLM Evaluation & LLM-as-a-Judge Framework

A hands-on engineering project focused on Large Language Model (LLM) evaluation methodologies, prompt benchmarking, and the implementation of an automated evaluation pipeline.

## Overview
This repository contains a complete pipeline designed to evaluate LLM performance on structured e-commerce product data. The project explores the core trade-offs between manual human evaluation and automated LLM-as-a-judge evaluation frameworks.

## Key Features
- **Data Generation:** Generated high-quality product descriptions from raw e-commerce metadata (name, attributes, material, warranty) using Nebius Token Factory models.
- **Evaluation Rubric:** Defined a strict scoring rubric to assess model outputs systematically.
- **Human vs. Auto Evaluation:** Conducted manual evaluation iterations to improve prompt alignment, followed by building an automated **LLM-as-a-judge** system.
- **Analysis:** Compared human-graded benchmarks against automated metrics to evaluate the reliability and alignment of the judge model.

## Tech Stack & Tools
- **Infrastructure:** Nebius Cloud Core Services
- **Development:** Jupyter Notebooks (`.ipynb`), Python
- **Models:** Nebius Token Factory LLM API