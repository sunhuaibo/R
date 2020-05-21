# R

<https://www.rdocumentation.org>  R包下载排名

<https://bookdown.org/>   R电子书

<http://www.dafont.com/search.php?q=people&page=2> 好玩的字体

<http://www.dafont.com/>   字体网站

<https://www.fonts.com/>   字体网站

<http://www.dafont.com/wm-people-1.font>    wm-people字体



### 绘图

* [**Thr R graph gallery**](http://www.r-graph-gallery.com/all-graphs/) - R美图代码
* [forestplot](https://cran.r-project.org/web/packages/forestplot/vignettes/forestplot.html) - 森林图
* [lolliplot](https://www.bioconductor.org/packages/release/bioc/vignettes/trackViewer/inst/doc/trackViewer.html#lolliplot) 绘制突变的needle图
* [igraph](http://igraph.org/r/) - 绘制network, [igraph示例](http://kateto.net/networks-r-igraph)
* [igraph](http://igraph.org/r/) - network绘图, [教程](https://github.com/kateto/R-Network-Visualization-Workshop)
* [gephi](https://gephi.org/) - 绘制network
* [rCircos](https://cran.r-project.org/web/packages/RCircos/index.html) - R package for circular plots.
* [OmicCircos](http://www.bioconductor.org/packages/release/bioc/html/OmicCircos.html) -  R package for circular plots for omics data.
* [circlize](http://zuguang.de/circlize_book/book/) - R绘制circos图, [学习网站](http://zuguang.de/circlize_book/book/)
* [networkD3](https://cran.r-project.org/web/packages/networkD3/) - 绘制sankey plot
* [network3D](https://christophergandrud.github.io/networkD3/) - 动态network绘制
* [corrplot](https://cran.r-project.org/web/packages/corrplot/vignettes/corrplot-intro.html) - 相关性绘图
* [ComplexHeatmap](https://jokergoo.github.io/ComplexHeatmap-reference/book/) - 绘制heatmap图，以及oncoprint图

### 基于ggplot2的绘图

* [常用扩展包](http://www.ggplot2-exts.org/gallery/) - ggplot2常用扩展包
* [gridextra](https://github.com/baptiste/gridextra/wiki/arranging-ggplot) - 多面板控gridextra、gtable、egg、grid
* [ggpubr](http://www.sthda.com/english/rpkgs/ggpubr/) - 包装的ggplot2函数，可在boxplot上添加显著性标
* [ggalluvial](https://github.com/corybrunson/ggalluvial) - 冲击图(alluvial diagram)
* [ggsignif](https://github.com/const-ae/ggsignif) - ggplot插件，给boxplot添加显著性标注
* [ggcorrplot](https://github.com/kassambara/ggcorrplot) - 基于ggplot绘制相关性图，类似corrplot
* [ggrepel](https://github.com/slowkow/ggrepel) - ggplot插件，解决图形label遮盖问题
* [ggtree](http://www.bioconductor.org/packages/release/bioc/html/ggtree.html) -绘制进化树
* [ggimage](https://github.com/GuangchuangYu/ggimage) - 添加图片
* [ggthemes](https://github.com/jrnold/ggthemes) - 自定义ggplot主题
* [ggthemr](https://github.com/cttobin/ggthemr) - 另一个ggplot主题插件
* [gganimate](https://github.com/dgrtwo/gganimate) - 动态图
* [GGally](https://ggobi.github.io/ggally/#ggally) - ggpairs 绘制pairs图, pairs()函数也可以绘制
* [motifStack](http://bioconductor.org/packages/release/bioc/vignettes/motifStack/inst/doc/motifStack_HTML.html) - 绘制motif图
* [ggseqlogo](https://omarwagih.github.io/ggseqlogo/) - 基于ggplot绘制motif图
* [plotly](https://plot.ly/ggplot2/) - 赋予ggplot2图形的动态表示，增加鼠标事件

### 颜色、字体设定

* [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/index.html) - 颜色设定
* [viridis](https://github.com/sjmgarnier/viridis) - 颜色设定
* [showtext](https://cran.r-project.org/web/packages/showtext/vignettes/introduction.html) - 解决字体问题
* [rPlotter](https://github.com/woobe/rPlotter) - 从图片中提取颜色
* [circlize](https://jokergoo.github.io/circlize_book/book/) - circlize包中的colorRamp2函数可以依据值域设置颜色，并根据提供的值返回颜色

```R
    col_fun = colorRamp2(c(-1, 0, 1), c("green", "white", "red")) 
    col_fun(0.5) # 返回"#FF9E81FF" 
```

### 字符串处理

* [stringr](https://cran.r-project.org/web/packages/stringr/vignettes/stringr.html) - 字符串处理   
* [stringi](http://www.gagolewski.com/software/stringi/) - 字符转处理神器，优于stringr

### 数据清洗、统计分析

* [tidyverse](https://www.tidyverse.org/) - 数据分析套件，包括ggplot2、tidyr、dplyr、readr、purrr等包
* [broom](https://github.com/tidyverse/broom) - 汇总统计分析结果
* [car](https://cran.r-project.org/web/packages/car/index.html) - Scatter plot with ellipses

```R
    library(car) 
    with(Prestige, dataEllipse(income, education, type, id.n=2, pch=15:17,
    labels=rownames(Prestige), xlim=c(0, 25000), center.pch="+",
    group.labels=c("Blue Collar", "Professional", "White Collar"),
    ylim=c(5, 20), level=.95, fill=TRUE, fill.alpha=0.1))
```

* [psych](http://personality-project.org/r/psych/) - 统计分析常用包
* [effects](https://cran.r-project.org/web/packages/effects/index.html) - Effect Displays for Linear, Generalized Linear, and Other Models
* [flexmix](https://cran.r-project.org/web/packages/flexmix/index.html) - 有限混合模型分析

### venn图

* [UpSetR](https://cran.r-project.org/web/packages/UpSetR/vignettes/basic.usage.html)
* [ggupset](https://github.com/const-ae/ggupset)
* [nVennR](https://cran.r-project.org/web/packages/nVennR/vignettes/nVennR.html) - venn图

### 数据挖掘

* [caret](https://github.com/topepo/caret) - Classification And Regression Training)
* [mclust](https://cran.r-project.org/web/packages/mclust/vignettes/mclust.html) - clustering, classification, and density estimation based on finite normal mixture modelling,可根据BIC筛选合适的k值
* [factoextra](http://www.sthda.com/english/wiki/factoextra-r-package-easy-multivariate-data-analyses-and-elegant-visualization) - PCA分析
* [cNMF](https://www.bioconductor.org/packages/devel/bioc/vignettes/CancerSubtypes/inst/doc/CancerSubtypes-vignette.html) - 可根据RNAseq的数据进行样本聚类，分类
* [ConsensusClusterPlus](http://www.bioconductor.org/packages/release/bioc/html/ConsensusClusterPlus.html) - 分析RNAseq，用于聚类
* [cluster](https://cran.r-project.org/web/packages/cluster/index.html) - Cluster Analysis Extended Rousseeuw et al，有pam方法
* [NMF](https://cran.r-project.org/web/packages/NMF/index.html)
* [rstatix](https://rpkgs.datanovia.com/rstatix/index.html) - 辅助数据处理，比如，增强版的t_test()函数
* [philentropy](https://github.com/HajkD/philentropy) - 46种距离算法

### 生存分析

* [survivalROC](https://cran.r-project.org/web/packages/survivalROC/index.html) - 生存数据中的连续变量的通过ROC计算获得最优值
* [survival](https://cran.r-project.org/web/packages/survival/index.html) - 生存分析
* [rms](https://cran.r-project.org/web/packages/rms/index.html) - 绘制nomogram图
* [randomForestSRC](https://kogalur.github.io/randomForestSRC/theory.html) - Random Forests for Survival, Regression, and Classification
* [ranger](https://cran.r-project.org/web/packages/ranger/index.html) - Ensembles of classification, regression, survival and probability prediction trees are supported
* [survminer](https://cran.r-project.org/web/packages/survminer/index.html) - 生存绘图
* [trackViewer](https://bioconductor.org/packages/release/bioc/html/trackViewer.html)


### NGS数据分析

* [maftools](http://bioconductor.org/packages/release/bioc/vignettes/maftools/inst/doc/maftools.html) - 突变数据分析绘图
* [xCell](https://github.com/dviraran/xCell) - xCell is a webtool that performs cell type enrichment analysis from gene expression data for 64 immune and stroma cell types.
* [classInt](https://cran.r-project.org/web/packages/classInt/) - 连续变量分类
* [karyoploteR](https://bernatgel.github.io/karyoploter_tutorial/) - plot customizable linear genomes displaying arbitrary data 绘制任意的线性基因组图
* [dada2](http://www.bioconductor.org/packages/release/bioc/vignettes/dada2/inst/doc/dada2-intro.html) - 16s OTU

### 其他常用

* [magrittr](https://github.com/tidyverse/magrittr) - hadley大神写的-管道操作符
* [optparse](https://github.com/trevorld/r-optparse) - R参数
* [GetoptLong](https://github.com/jokergoo/GetoptLong) - R参数设定
* [log4r](https://github.com/johnmyleswhite/log4r)  - 日志文件
* [futile.logger](https://github.com/zatonovo/futile.logger) - 日志
