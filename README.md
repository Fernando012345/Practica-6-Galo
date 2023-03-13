# Practica 6 Galo
 title: "practica 6 galo"
author: "Fernando López"
date: "13/3/2023"
output:
  html_document:
    df_print: paged
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```




## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

summary(cars)


## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.



###ejercicio 1
Ningun sistema o lenguaje de programación puede crear valores realmente aleatorios, van a ser pseudoaleatorios.
``` [R]
set.seed (1)
rnor m1= rnorm(10)

set.seed (2)
rnorm = rnorm2 (10)
 
rexp1= rexp (5)

###EJERCICIO 2
 Shapiro-Wilk normality test
 
data:  rnorm2
W = 0.9556, p-value = 0.6164

En estadistica hay pruebas paramétrica y pruebas no paramétricas (Valores ordinales). 
shapiro.test (rnorm2)
shapiro.test












