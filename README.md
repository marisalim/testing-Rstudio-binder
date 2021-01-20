# testing-Rstudio-binder

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/marisalim/testing-Rstudio-binder/stable-binder-new?urlpath=rstudio)

## Add set up docs to `./binder`
- e.g., `environment.yml`
- if you want certain R packages to be installed, put them in the `environment.yml` file, you don't need `runtime.txt` or `install.R` files.

## Set up binder:
![](./rstudio-binder-setup.png)

- enter URL, branch to point binder to (something like `stable-binder` here), and in "Path to Notebook", change from default "File" to "URL" and type `rstudio` to indicate you want an Rstudio binder -> this is what sets up the binder in Rstudio. Rstudio has a Console for running R commands and a Terminal for bash. This set up is nice because you can use the Rstudio panels to e.g., show/edit text files, run R or bash, and see/navigate file system/plots/installed R packages.
- copy/paste the binder badge link
- click "launch". It takes a while to create.

## Helpful links
- https://www.marsja.se/how-to-use-binder-r-statistical-environment-for-reproducible-research/
- https://github.com/binder-examples/r-conda
