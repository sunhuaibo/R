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
* [ggthemes](https://github.com/jrnold/ggthemes) - 自定义ggplot主题
* [ggthemr](https://github.com/cttobin/ggthemr) - 另一个ggplot主题插件
* [gganimate](https://github.com/dgrtwo/gganimate) - 动态图
* [magrittr](https://github.com/tidyverse/magrittr) - hadley大神写的-管道操作符
* [psych](http://personality-project.org/r/psych/) - 统计分析常用包
* [karyoploteR](https://bernatgel.github.io/karyoploter_tutorial/) - plot customizable linear genomes displaying arbitrary data 绘制任意的线性基因组图
* [**Thr R graph gallery**](http://www.r-graph-gallery.com/all-graphs/) - R美图代码
* [ggrepel](https://github.com/slowkow/ggrepel) - ggplot插件，解决图形label遮盖问题

