---
title: "Lab_0"
author: "Mateusz Bro¿yna"
date: "2025-03-02"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

# 1. Wylosowaæ dziesiêæ liczb z rozk³adów normalnych o œredniej dowolnej i odchyleniu standardowym dowolnym. 

```{R}
x <- rnorm(10)
x
```
# 2. Sprawdziæ co oznaczaj¹ funkcje: 

```{R}
dnorm(x, mean=0, sd=1, log = FALSE) 
```

# 3. Wysymulowaæ: 
