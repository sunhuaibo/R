phangorn
================

### 肿瘤进化树

  - 加载phangorn包

<!-- end list -->

``` r
library(phangorn)
```

  - 读取突变的数据，存给变量df，设置成0,1的格式，1代表突变，0代表不突变

<!-- end list -->

``` r
head(df)
```

    ##                              ZT_C1D0_T ZT_T2D1_T ZT_T3D-1 Germline
    ## chr1_158619694_158619694_T_A         0         0        1        0
    ## chr1_158725494_158725494_T_A         1         1        1        0
    ## chr1_158735727_158735727_A_G         1         1        0        0
    ## chr1_17087589_17087589_A_T           1         0        0        0
    ## chr1_171080088_171080088_G_C         0         1        0        0
    ## chr1_190129924_190129924_C_T         0         1        0        0

``` r
df <- phyDat(t(df), type = "USER", levels = c(1, 0))
dm <- dist.hamming(df)
tree <- NJ(dm)
treeRatchet <- pratchet(df, start=tree, maxit=100,
                        minit=5, k=5, trace=0)
treeRatchet <- acctran(treeRatchet, df)
plot(treeRatchet, type = "unrooted")
```

![](fig/cancer_evolution_files/figure-gfm/unnamed-chunk-5-1.png)<!-- -->
