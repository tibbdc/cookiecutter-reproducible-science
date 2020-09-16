Reproducible Science
====================

A boilerplate for reproducible and transparent science with close resemblances to the philosophy of [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science): *A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.*

Requirements
------------
Install `cookiecutter` command line: `pip install cookiecutter`    

Usage
-----
To start a new science project:

`cookiecutter gh:tibbdc/cookiecutter-reproducible-science`

Project Structure
-----------------

```
.
├── AUTHORS.md
├── LICENSE
├── README.md
├── bin                <- Your compiled model code can be stored here (not tracked by git)
├── config             <- Configuration files, e.g., for doxygen or for your model if needed
├── data
│   ├── external       <- Original Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The prosessed data for analysis, this should be the data which can also be used/archieved for other analysis, such as a model.
│   └── result         <- The result data.
├── docs               <- Documentation
├── notebooks          <- Jupyter notebooks to show the whole workflow, call the code in src directory
├── reports            <- For PPT and a manuscript source, e.g., LaTeX, Markdown, etc., or any project reports
│   └── figures        <- Figures for the manuscript or reports
└── src                <- Source code for this project
    ├── data           <- Scripts for downloading and preprocessing the data (generate data from external to processed)
    ├── external       <- Any external source code, e.g., pull other git projects, or external libraries
    ├── analysis       <- Scripts for analysis (generate result)
    ├── tools          <- Any other helper scripts go here
    └── visualization  <- Scripts for results visualisation and figures generation, e.g., matplotlib related.
```

Check out the latest research project, which successfully applied the `cookiecutter` philosophy: [SEMIC: an efficient surface energy and mass balance model applied to the Greenland ice sheet](https://gitlab.pik-potsdam.de/krapp/semic-project).

License
-------
This project is licensed under the terms of the [BSD License](/LICENSE)
