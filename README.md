# R

#### 收集包

* [showtext](https://cran.r-project.org/web/packages/showtext/vignettes/introduction.html) - 解决字体问题      
* [corrplot](https://cran.r-project.org/web/packages/corrplot/vignettes/corrplot-intro.html) - 相关性绘图       
* [stringr](https://cran.r-project.org/web/packages/stringr/vignettes/stringr.html) - 字符串处理        
* [broom](https://github.com/tidyverse/broom) - 汇总统计分析结果    
* [car](https://cran.r-project.org/web/packages/car/index.html) - Scatter plot with ellipses
>   
    library(car) 
    with(Prestige, dataEllipse(income, education, type, id.n=2, pch=15:17,
    labels=rownames(Prestige), xlim=c(0, 25000), center.pch="+",
    group.labels=c("Blue Collar", "Professional", "White Collar"),
    ylim=c(5, 20), level=.95, fill=TRUE, fill.alpha=0.1))

* [stringi](http://www.gagolewski.com/software/stringi/) - 字符转处理神器，优于stringr
* [igraph](http://igraph.org/r/) - 绘制network
* [rCircos](https://cran.r-project.org/web/packages/RCircos/index.html) - R package for circular plots.
* [OmicCircos](http://www.bioconductor.org/packages/release/bioc/html/OmicCircos.html) -  R package for circular plots for omics data.
