# Video Game Ratings Sales and Genre Analysis

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

The final capstone project for INST414 by Seamus Sullivan.

Link to Dataset Used: [Video Game Sales with Ratings](https://www.kaggle.com/datasets/rush4ratio/video-game-sales-with-ratings)

---

**Project Overview**

This project explores how critic and user review scores relate to global video game sales. Instead of trying to perfectly predict how well a game will sell, the goal of this project is to understand what review scores can and cannot tell us about the commercial success of video games. This project examines the relationship between game sales, critic scores, user scores, and game genres to show how much review performance matters in the gaming market and to explore whether highly reviewed games truly become best-selling titles. This project's research question is: How do critic and user review scores relate to video game sales across different genres?

---

**README Update - Sprint 2 Progress**

In Sprint 2, I cleaned the "Video Game Sales with Ratings" dataset that I am using for my analysis (see link above), explored missing values, and created visualizations as part of exploratory data analysis (EDA) to understand the data. I summarized distributions for my key numeric variables - global sales, critic scores, and user scores - and examined how sales differ across genres. I also identified weak relationships between review scores and sales and created sales tiers (Low, Medium, High) to explore class imbalance. Finally, I ran preliminary Random Forest models to see how critic and user scores relate to global sales. All steps are documented in the Jupyter notebooks, with clear comments and visualizations to make the analysis easy to follow.

---

**README Update - Sprint 3 Progress**

In Sprint 3, I built, trained, and evaluated multiple regression models to predict global video game sales using critic score, user score, and genre. I compared Linear Regression, Random Forest, and Gradient Boosting, and found that Gradient Boosting performed the best, though its overall predictive power remained modest. I also generated a full set of diagnostic visualizations - including residual plots, learning curves, feature importance charts, and model comparison figures - to evaluate each model's performance and identify why errors occur. All Sprint 3 code (including the model instructions) can be found in Sprint_3_Code.ipynb, which is located in the notebooks folder of this repository. The code is organized to match the sections and subsections in the Sprint 3 report. All outputs should already be included in the notebook, but you can rerun the cell to reproduce them if needed.

---

## Project Organization

```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         Video Game Ratings Sales and Genre Analysis and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── Video Game Ratings Sales and Genre Analysis   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes Video Game Ratings Sales and Genre Analysis a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------

