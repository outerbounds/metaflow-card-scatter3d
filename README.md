
# 3D Scatter plot - a Metaflow card

![](https://raw.githubusercontent.com/outerbounds/dynamic-card-examples/main/images/rtcard-scatterflow.gif)

This repository contains [a Metaflow card template](https://docs.metaflow.org/metaflow/visualizing-results/)
for visualizing interactive 3d scatter plots. Besides being
a useful card by itself, you can use this repository as a reference for your own custom card templates.

[See Metaflow documentation for details](https://docs.metaflow.org/metaflow/visualizing-results/advanced-shareable-cards-with-card-templates#developing-a-dynamic-card-template)

## Usage
```
pip install metaflow-card-scatter3d
```
After this, you can add `@card(type='scatter3d')` in your steps.
[See this example flow](https://github.com/outerbounds/dynamic-card-examples/tree/main/custom-card) for reference.
