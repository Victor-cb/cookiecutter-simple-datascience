# Cookiecutter Modern Data Science
[Cookiecutter] template for starting a Data Science project.
To install it:
1. pip install cookiecutter
2. cookiecutter https://github.com/Victor-cb/cookiecutter-simple-datascience.git
## Directory structure

This is how your new project will look like:

    ├── .gitignore                <- GitHub's excellent Python .gitignore customized for this project
    ├── LICENSE                   <- Your project's license.
    ├── Pipfile                   <- The Pipfile for reproducing the analysis environment
    ├── README.md                 <- The top-level README for developers using this project.
    │
    ├── data
    │   ├── 0_raw                 <- The original, immutable data dump.
    │   ├── 1_external            <- Data from third party sources.
    │   ├── 2_interim             <- Intermediate data that has been transformed.
    │   └── 3_final               <- The final, canonical data sets for modeling.
    │
    ├── docs                      <- GitHub pages website
    │   ├── data_dictionaries     <- Data dictionaries
    │   └── references            <- Papers, manuals, and all other explanatory materials.
    │
    ├── notebooks                 <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                                the creator's initials, and a short `_` delimited description, e.g.
    │                                `01_cp_exploratory_data_analysis.ipynb`.
    │
    ├── output
    │   ├── features              <- Fitted and serialized features
    │   ├── models                <- Trained and serialized models, model predictions, or model summaries
    |   |   └── mlruns            <- MLflow artifacts 
    │   └── reports               <- Generated analyses as HTML, PDF, LaTeX, etc.
    │       └── figures           <- Generated graphics and figures to be used in reporting
    │
    |
    │
    └── serve                     <- HTTP API for serving predictions
        ├── Dockerfile            <- Dockerfile for HTTP API
        ├── Pipfile               <- The Pipfile for reproducing the serving environment
        ├── app.py                <- The entry point of the HTTP API
        └── tests
            ├── fixtures          <- Where to put example inputs and outputs
            │   ├── input.json    <- Test input data
            │   └── output.json   <- Test output data
            └── test_app.py       <- Integration tests for the HTTP API




[Cookiecutter]: https://github.com/audreyr/cookiecutter
