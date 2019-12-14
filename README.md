# Example Empirical Paper

This is a barebones example of how to write an empirical paper for [ECON 480 - Econometrics](https://metricsf19.classes.ryansafner.com) using the data from Stock and Watson 2007 on how class size affects test scores.

This project contains just three important files in the main directory:

- `paper.Rmd`: the main file for writing the paper in markdown, including all associated code, figures, and tables
- `paper.pdf`: knitted result of `paper.Rmd`
- `caschool.dta`: the raw data to be used

This is one method of organizing files, and performing *all* tasks (writing text; importing, wrangling, and analyzing data; creating tables and plots) in a single file - `paper.Rmd`.

To see another method of organization and separation of tasks across multiple files and folders, see my [Workflow](https://github.com/ryansafner/workflow) repository for an example.

# Opening On Your Computer/RStudio

Download this whole repository by clicking the **green button (Clone or Download)** and then downloading as a `.zip` file, which your computer can then unzip. You can look at this whole project in R Studio (with all included files) by opening the `.Rproj` file. Otherwise, you can open individual files individually.

# Compiling to a PDF

If you wish to compile the `.Rmd` to a pdf, you will need a LaTeX distribution, which you can download (fairly large) for [Windows](https://miktex.org/) or [Mac](http://www.tug.org/mactex/). Alternatively (and easiest), you can install a distribution *inside* R, with the following code:

```{r}
install.packages("tinytex")
tinytex::install_tinytex()
```

# Using References

See the `references.bib` file for an example `.bib` file. See more my [1.6 Slides](https://metricsf19.classes.ryansafner.com/slides/06-slides#37) for more.

# Using LaTeX Math

All math is rendered using LaTeX code between two dollar signs, e.g. `$\hat{\beta_1}$` becomes $\hat{\beta_1}$. An excellent guide can be found [here](https://en.wikibooks.org/wiki/LaTeX/Mathematics).