# Website OSCRotterdam

Source code of the website of the Open Science Community Rotterdam.

This website is developed using [_R_](https://cran.r-project.org/) and [`blogdown`](https://github.com/rstudio/blogdown). See [this book](https://bookdown.org/yihui/blogdown/) for details on how to create a website with this software.

## Usage
Please only work in the `development`-branch. To publish your last changes online perform the following step:
1. `blogdown::build_site()` in `R` to build the new public folder 
2. `commit` your changes in development folder(!)
3. `push` all changes and resolve all merge conflicts
4. run `deploy.sh`
