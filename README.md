gerForest - German distribution of forest tree species
================

**Note::** This repository is still work in progress\!\!\!

Choose a tree species:

``` r
selectInput("data", "", c("co2", "lh"))
```

See a plot:

``` r
renderPlot({
d <- get(input$data)
plot(d)
})
```

Interactive plots

``` r
library(rCharts)
```
