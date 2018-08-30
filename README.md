# science-binder

JupyterLab: [![binder badge][binder_badge]][binder_lab]

RStudio: [![binder badge][binder_badge]][binder_studio]

Repo to host analyses notebooks in jupyter

Integrated with binder: Click launch binder above to explore this project and run the code.

Project Organization
--------------------

    .
    ├── AUTHORS.md
    ├── LICENSE
    ├── README.md
    ├── bin
    ├── binder
    │   ├── apt.txt
    │   ├── install.R
    │   ├── postBuild
    │   ├── requirements.txt
    │   └── runtime.txt
    ├── config
    ├── data
    │   ├── external
    │   ├── interim
    │   ├── processed
    │   └── raw
    ├── docs
    ├── notebooks
    ├── reports
    │   └── figures
    └── src
        ├── data
        ├── external
        ├── models
        ├── tools
        └── visualization

<!-- Badges -->
[binder_badge]: https://mybinder.org/badge.svg
[binder_lab]: https://mybinder.org/v2/gh/juanesarango/science-binder/master?urlpath=lab
[binder_studio]: https://mybinder.org/v2/gh/juanesarango/science-binder/master?urlpath=rstudio