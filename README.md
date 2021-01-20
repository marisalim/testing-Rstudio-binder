# testing-Rstudio-binder

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/marisalim/testing-Rstudio-binder/stable-binder?urlpath=rstudio)

## Add set up docs to `./binder`
- you need to have an installation of R (`install.R`) - here is where to specify packages you want installed.
- `runtime.txt` specifies the version of R to install
- you can have an `environment.yml` file in here for conda environments, but don't put any r packages in the `dependencies:` section as it will conflict with the other set up files. Add packages you want installed in the `install.R` file. 

## Set up binder:
![](./rstudio-binder-setup.png)

- enter URL, branch to point binder to (`stable-binder` here), and in "Path to Notebook", change from default "File" to "URL" and type `rstudio` to indicate you want an Rstudio binder
- copy/paste the binder badge link
- click "launch". It takes a while to create.

## Helpful links
- https://www.marsja.se/how-to-use-binder-r-statistical-environment-for-reproducible-research/
- https://github.com/binder-examples/r-conda
