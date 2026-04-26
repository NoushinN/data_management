# Data Management with R

This repository contains teaching materials and examples focused on **data management and reproducible analysis using R**. The content emphasizes practical workflows for cleaning, transforming, summarizing, and presenting data in a structured and reproducible way using modern R tools.

The materials are suitable for learners who have basic familiarity with R and want to strengthen their skills in data wrangling, functional programming, and clear analytical communication.

---

## Core topics covered

- **Tidy data principles**
- **Data cleaning and transformation** using the tidyverse
- **Reproducible project structure** with RStudio Projects and relative file paths
- **Functions and iteration** using base R and `purrr`
- **Table and figure creation** for exploratory analysis and reporting
- **Storyboards and dashboards** using R Markdown and flexdashboard

---

## Repository structure

- `Raw Data/`  
  Example input datasets used for demonstrations and practice exercises

- `Outputs/`  
  Cleaned data, intermediate outputs, and analysis results

- `Demo_*.Rmd`  
  Demonstration notebooks illustrating core concepts and workflows

- `Practice_*.Rmd`  
  Hands‑on practice exercises aligned with each topic area

- `Data-Management-Setup-*.Rmd`  
  Guidance on project setup, package use, and reproducible workflows

---

## Learning flow

The materials are designed to be used sequentially:

1. **Introduction to tidy data and the tidyverse**  
   Reading data, selecting variables, filtering rows, and creating summaries

2. **Practice exercises (01 & 02)**  
   Applying data cleaning and transformation techniques

3. **Functions and iteration**  
   Writing reusable functions and using `purrr` for scalable data workflows

4. **Practice exercises (03 & 04)**  
   Reinforcing functional programming concepts

5. **Storyboards and dashboards**  
   Communicating results using plots, tables, and narrative with R Markdown and flexdashboard

---

## Intended use

This repository can be used for:
- Self‑guided learning
- Workshop or classroom instruction
- Reference examples for applied data analysis projects
- Templates for reproducible analytic workflows

All example data included in this repository are **simulated or instructional only**.

---

## Tools and packages used

- `tidyverse`
- `ggplot2`
- `knitr`
- `kableExtra`
- `purrr`
- `here`
- `flexdashboard`

---

## Reproducibility notes

- The project assumes use of **RStudio Projects** for consistent file paths
- Relative paths (e.g., via `here::here()`) are used throughout
- Code is written to be readable, modular, and easy to adapt

---

## Licence

This repository is intended for educational and instructional use. See the `LICENSE` file for details.