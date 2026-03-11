# Mesa Examples
## Core Mesa examples
The core Mesa examples are available at the main Mesa repository: https://github.com/mesa/mesa/tree/main/mesa/examples

Those core examples are fully tested, updated and guaranteed to work with the Mesa release that they are included with. They are also included in the Mesa package, so you can access them directly from your Python environment.

## Mesa user examples
This repository contains user examples and showcases that illustrate different features of Mesa. For more information on each model, see its own Readme and documentation.

- Mesa examples that work on the Mesa and Mesa-Geo main development branches are available here on the [`main`](https://github.com/mesa/mesa-examples) branch.
- Mesa examples that work with Mesa 2.x releases and Mesa-Geo 0.8.x releases are available here on the [`mesa-2.x`](https://github.com/mesa/mesa-examples/tree/mesa-2.x) branch.

To contribute to this repository, see [CONTRIBUTING.rst](https://github.com/mesa/mesa-examples/blob/main/CONTRIBUTING.rst).

This repo also contains a package that readily lets you import and run some of the examples:
```console
$ # This will install the "mesa_models" package
$ pip install -U -e git+https://github.com/mesa/mesa-examples#egg=mesa-models
```
For Mesa 2.x examples, install:
```console
$ # This will install the "mesa_models" package
$ pip install -U -e git+https://github.com/mesa/mesa-examples@mesa-2.x#egg=mesa-models
```
```python
from mesa_models.boltzmann_wealth_model.model import BoltzmannWealthModel

```
You can see the available models at [setup.cfg](https://github.com/mesa/mesa-examples/blob/main/setup.cfg).

## License Notice

All examples in this repository are distributed under the same license as the repository, unless explicitly stated otherwise.

---

Table of Contents
=================

Examples in this repository are organized into catalogs by **domain**, **spatial structure**, and **implementation complexity**, providing multiple ways to explore the example models.

---

## Domains
Examples categorized by the **application domain or research area** the model represents.

- ### [Biology](domains/biology.md)
- ### [Computer Science](domains/computer_science.md)
- ### [Ecology](domains/ecology.md)
- ### [Economics](domains/economics.md)
- ### [Epidemiology](domains/epidemiology.md)
- ### [Geography](domains/geography.md)
- ### [Social Science](domains/social_science.md)

---

## Spaces
Examples categorized by the **type of spatial structure used in the model**.

- ### [Grid-based Models](spaces/grid.md)
- ### [Network-based Models](spaces/network.md)
- ### [Continuous Models](spaces/continuous.md)
- ### [GIS-based Models](spaces/gis.md)

---

## Complexity
Examples categorized by the **implementation complexity of the model**, helping users identify beginner-friendly and more advanced examples.

- ### [Basic Examples](complexity/basic.md)
- ### [Advanced Examples](complexity/advanced.md)