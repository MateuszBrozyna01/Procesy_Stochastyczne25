---
title: "Lab_0"
author: "Mateusz Bro�yna"
date: "2025-03-02"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

# 1. Wylosowa� dziesi�� liczb z rozk�ad�w normalnych o �redniej dowolnej i odchyleniu standardowym dowolnym. 

```{R}
x <- rnorm(10)
x
```
# 2. Sprawdzi� co oznaczaj� funkcje: 

```{R}
dnorm(x, mean=0, sd=1, log = FALSE) 
```

# 3. Wysymulowa�: 
