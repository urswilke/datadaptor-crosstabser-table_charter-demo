This is the demo-repo to show how the combination of the packages
[datadaptor](https://gitlab.com/urswilke/datadaptor), 
[crosstabser](https://gitlab.com/urswilke/crosstabser) & 
[table_charter](https://gitlab.com/urswilke/table_charter)
can be used to calculate crosstabs from labelled data.
The table_charter app in the bottom of the website can be automatically rebuilt based on the generated table data.

The website is built from the [quarto qmd file](datadaptor-crosstabser-table_charter-demo.qmd) in this repo 
and will be rebuilt after changing the qmd file, rendering it, and then pushing the changes to main.
The site relies on the [quarto live](https://r-wasm.github.io/quarto-live/) extension.
