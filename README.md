# Data Management with R

This folder contains the fixed Bookdown version of the **Data Management with R** materials.

The previous combined file placed multiple chapters into one `.Rmd` file, which caused duplicate chunk-label errors such as `setup`. This version splits the content back into separate chapter files and prefixes code chunk labels so they are unique across the book.

## Files included

- `index.Rmd` – book landing page and introduction
- `01_project_setup.Rmd` – project setup and Git/GitHub workflow
- `02_tidyverse_basics.Rmd` – tidyverse basics
- `03_joining_data.Rmd` – joining data
- `04_data_cleaning.Rmd` – data cleaning and data management
- `05_strings_regex.Rmd` – strings and regular expressions
- `06_visualization.Rmd` – visualization and advanced cleaning
- `07_exploratory_analysis.Rmd` – exploratory analysis project
- `08_storyboard_reporting.Rmd` – storyboard and reporting
- `_bookdown.yml` – bookdown chapter order and output folder
- `_output.yml` – output settings
- `style.css` – basic styling

## How to render the book

Open the RStudio project, then run:

```r
bookdown::clean_book()
bookdown::render_book("index.Rmd")
```

The rendered book will be created in the `docs/` folder.

## Folder reminders

Keep raw datasets in:

```text
Raw Data/
```

Save generated files in:

```text
Outputs/
```
