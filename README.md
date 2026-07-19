# Automated Statistical Pipeline: ANOVA Inference Engine

## Overview
A reproducible R-based analytical pipeline designed to automate Analysis of Variance (ANOVA) modeling. This repository extracts the core analytical logic from a proprietary biomedical data pipeline to demonstrate programmatic data validation, automated statistical testing, and structured output generation.

## Pipeline Architecture
The engine is designed to minimize manual analytical overhead while enforcing strict statistical rigor:

* **Algorithmic Data Validation:** Enforces strict structural constraints and checks statistical assumptions (e.g., variance homogeneity, normality) prior to model execution.
* **Error Handling & Routing:** Implements robust fallback mechanisms and programmatic routing to handle malformed inputs or violated assumptions without crashing the runtime environment.
* **Standardized Output:** Leverages the `broom` package to transform complex statistical model objects into tidy, machine-readable data frames for downstream consumption.

## Execution

### Tech Stack
* **R:** Core statistical runtime.
* **Tidyverse:** Data manipulation and structural transformations.
* **broom & rstatix:** Model tidying and statistical summary generation.
* **R Markdown:** Pipeline orchestration and report compilation.

### Run the Pipeline
The logic is encapsulated in a reproducible R Markdown document.

1. Download the `Automated_ANOVA.Rmd` source file.
2. Open the file in RStudio or an equivalent R environment.
3. Execute the `Knit` command to compile the source code, run the data validation algorithms, and generate the final structured HTML report.
