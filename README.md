# A quick introduction into ggplot2, with ioslides produced from Rmarkdown

## Looking at the slides

To just look at the slides, just clone this repository...
```
git clone https://github.com/dlaehnemann/ggplot2_Intro
```
...and open `ggplot2_Intro.html` from the respective directory in any (contemporary) web browser.

## Changing the slides

### 1. Edit the Rmarkdown file `ggplot2_Intro.Rmd`

Links for how to do this:
* [Main Rmarkdown documentation](http://rmarkdown.rstudio.com/)
* [Rmarkdown cheat sheet](https://www.rstudio.com/wp-content/uploads/2016/03/rmarkdown-cheatsheet-2.0.pdf)
* [ioslides with Rmarkdown intro](http://rmarkdown.rstudio.com/ioslides_presentation_format.html)

### 2. Recompile `ggplot2_Intro.html` using `R`:
```
install.packages("rmarkdown")
install.packages("knitr")
library("rmarkdown")
library("knitr")
render("ggplot2_Intro.Rmd")
```
