# Presentation template based on Jupyter Notebook
Template for generating a `Reveal.js` presentation from a Jupyter notebook (using `nbconvert`) and serving it using GitHub Pages. This example presentation can be viewed [here](https://cicwi.github.io/PresentationJupyterNB/Presentation.html).

## Usage

1. Fork this repository
2. Get [`nbconvert`](https://nbconvert.readthedocs.io/en/latest/install.html) and [`ghp-import`](https://pypi.org/project/ghp-import/).
3. Modify `Presentation.ipynb`. Tip: In Jupyter, you can change slide types (slide, subslide, fragment, skip, notes) by choosing `View -> Right Sidebar -> Show Notebook Tools -> Common Tools`. In Jupyter Lab, it is `View -> Appearance -> Show Right Sidebar (Ctrl+J)`. In VS Code, this menu is in the right bottom corner of the slide.
4. Run `make` to convert the notebook to slides and push the result to the `gh-pages` branch of your repository. The slides are then accessible from `<username>.github.io/<reponame>/Presentation.html`.
