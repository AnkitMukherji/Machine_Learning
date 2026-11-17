# Mathematics for Machine Learning

Python notebooks exploring the mathematics behind machine learning: linear algebra, optimization, regression, and neural-network gradients.

## Folder guides

- [Mathematics for machine learning notebooks](Mathematics_ML/README.md)

## Notebook guide

All primary material is in [Mathematics_ML/](Mathematics_ML/).

| Theme | Examples |
| --- | --- |
| Linear algebra | [Gram–Schmidt](Mathematics_ML/GramSchmidtProcess.ipynb), [special matrices](Mathematics_ML/IdentifyingSpecialMatrices.ipynb), [PageRank](Mathematics_ML/PageRank.ipynb), [reflections](Mathematics_ML/ReflectingBear.ipynb) |
| Optimization | [Gradient descent](Mathematics_ML/GradientDescentInASandpit.ipynb), [Lagrange multipliers](Mathematics_ML/lagrange_multiplier.ipynb), sandpit exercises |
| Statistical fitting | [Least squares](Mathematics_ML/least_squares_regression.ipynb), [distribution fitting](Mathematics_ML/Fitting_the_distribution_of_heights_data.ipynb) |
| Neural-network calculus | [Backpropagation](Mathematics_ML/Backpropagation.ipynb) |

## Working environment

Inspect [pyproject.toml](Mathematics_ML/pyproject.toml) and [requirements.txt](Mathematics_ML/requirements.txt) within the mathematics directory. Use a compatible Python/Jupyter environment and retain the `readonly/` helpers in their expected relative location.

Run notebooks interactively and examine intermediate calculations. Some material is course-derived, including supplied worksheets/helpers; preserve its attribution and usage terms.

## Relevance to computational biology

These foundations support reasoning about dimensionality reduction, regression, numerical stability, and model fitting in biological analyses. The repository presents mathematical exercises rather than a validated biological prediction system.

Related applied work: [single-cell analysis](https://github.com/AnkitMukherji/single_cell_analysis) · [FRDA exploratory modeling](https://github.com/AnkitMukherji/FRDA_Analysis).
