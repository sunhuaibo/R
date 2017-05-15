# R

#### 收集包

* [showtext](https://cran.r-project.org/web/packages/showtext/vignettes/introduction.html) - 解决字体问题      
* [corrplot](https://cran.r-project.org/web/packages/corrplot/vignettes/corrplot-intro.html) - 相关性绘图       
* [stringr](https://cran.r-project.org/web/packages/stringr/vignettes/stringr.html) - 字符串处理        
* [broom](https://github.com/tidyverse/broom) - 汇总统计分析结果    
* [cat](https://cran.r-project.org/web/packages/car/index.html) - Scatter plot with ellipses
    library(car) 
    with(Prestige, dataEllipse(income, education, type, id.n=2, pch=15:17,
    labels=rownames(Prestige), xlim=c(0, 25000), center.pch="+",
    group.labels=c("Blue Collar", "Professional", "White Collar"),
    ylim=c(5, 20), level=.95, fill=TRUE, fill.alpha=0.1))
