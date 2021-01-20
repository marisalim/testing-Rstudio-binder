# testing-Rstudio-binder

with r (version set to 3.6), fastqc, trimmomatic, and salmon installed in binder:
[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/marisalim/testing-Rstudio-binder/stable-binder?urlpath=rstudio)

with latest version of r only:
[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/marisalim/testing-Rstudio-binder/just-r?urlpath=rstudio)

## Add set up docs to `./binder`
- e.g., `environment.yml`
- if you want certain R packages to be installed, put them in the `environment.yml` file, you don't need `runtime.txt` or `install.R` files.
- note that whatever goes in the `environment.yml` was installed when the binder opened, so if you want to demo installations of e.g., fastqc/trimmomatic/salmon with conda, don't include them in the yml file!

## Set up binder:
![](./rstudio-binder-setup.png)

- enter URL, branch to point binder to (something like `stable-binder` here), and in "Path to Notebook", change from default "File" to "URL" and type `rstudio` to indicate you want an Rstudio binder -> this is what sets up the binder in Rstudio. Rstudio has a Console for running R commands and a Terminal for bash. This set up is nice because you can use the Rstudio panels to e.g., show/edit text files, run R or bash, and see/navigate file system/plots/installed R packages.
- copy/paste the binder badge link
- click "launch". It takes a while to create.

## Helpful links
- https://www.marsja.se/how-to-use-binder-r-statistical-environment-for-reproducible-research/
- https://github.com/binder-examples/r-conda
