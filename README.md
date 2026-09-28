# Sam-xds.github.io
Personal data science portfolio built with Quarto during the UBC Master of Data Science program

## Reproducible environments

### Python

Python dependencies are managed with `uv`.

To restore the Python environment:

```bash
uv sync
```
### R

R dependencies are managed with `renv`.

To restore the R environment, open the project in R and run:

```r
renv::restore()
```

## Reproducibility check

The project was tested from a fresh clone by restoring the Python and R environments and rendering the complete Quarto site successfully.

## Build the site

From the project root, run:

```bash
uv run quarto render
```