This is the GitHub repository for the [Sample Space](https://sample-space.org) website, based on [quarto](https://quarto.org/).

**NB**: Note the use of the `.Rprofile` file, in which we setup 
```
options(htmlwidgets.dir = "public/site_libs")
```
to prevent the rendering from `Rstudio` to create a `~/site_libs` folder, which unnecessarily clutters the home folder of the system.
