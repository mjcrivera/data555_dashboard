*DATA 555: Final Dashboard and GitHub pages deployment*

# Frontline Community Health Worker (FLCHW) Digital Readiness in Katsina State, Nigeria
by Monica Rivera
on April 27, 2025

## Overview
This repository contains the replication code and data for the **Frontline Community Health Worker (FLCHW) Digital Readiness** study. The project analyzes digital access, Information and Communications Technology (ICT) proficiency, and readiness among health workers to inform targeted capacity-building strategies.

The final dashboard provides an interactive ICT proficiency radar chart, workforce characteristic summaries, and a bivariate analysis of factors associated with digital readiness using Fisher’s exact test.

### Contents of the Report 
* **Workforce ICT Proficiency:** A radar chart visualizing skill gaps in software installation, web search, and document editing.
* **Table 1:** Summary statistics of demographics and digital access.
* **Digital Readiness Figure:** A stacked bar chart showing readiness levels by education.
* **Table 2:** Bivariate analysis of factors (Age, Sex, Education) associated with digital readiness.

## Project Impact and Importance

This dashboard identifies critical gaps in digital literacy and infrastructure among FLCHWs in Katsina State, providing a data-driven roadmap for targeted investment in mobile health technologies. By pinpointing specific skill deficiencies, stakeholders can optimize training resources to ensure the workforce is prepared for the digital transformation of community health delivery.

---

## Repository Setup
- Fork and clone the repository: `https://github.com/mjcrivera/data555_dashboard`.
- Navigate to the project directory in your terminal: `cd final`.

---

## Generating the Dashboard
- Since this is a Shiny-based flexdashboard, the process will generate a link.

---

## Code description

`data.csv`
- The primary dataset containing survey responses from Katsina State health workers.

`final_project.Rmd`
- The main file that integrates R code, Shiny reactivity, and Markdown to create the interactive dashboard.

`code.R`
- Stored in the `code` folder.
- Performs data cleaning, factor leveling for education/experience, and calculates the "Digital Readiness" composite score.
- Contains helper functions for generating summary tables and performing Fisher’s Exact Tests.

`final.Rproj`
- RStudio project file to manage the local session and library paths.