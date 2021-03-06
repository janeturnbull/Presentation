---
title       : Celsius to Farenheit Converter
subtitle    : 
author      : Jane T
job         : Consulting Company
framework   : io2012       # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides

---
  
## Introduction
  
When traveling outside of the USA, have you ever wondered what the temperature was like outside so you knew what to wear? 

The USA may be the only place on earth that still quotes temperatures in Farenheit, so when in Europe or elswhere, a lot of us have no idea exactly how hot or cold it is when we hear the weather forecast.

---

## The Solution
  
It would be nice to quickly translate those Celsius temperatures to Farenheit so that we exactly know the temperature in order to dress appropriately.

Enter the Celsius to Farenheit converter, the portable use anytime, use anywhere tool that gives you an 
accurate Farentheit temperature when you enter in the Celsius temperature.

---

## How it Works

Pull the app up on your phone or laptop from https://jturnbull.shinyapps.io/project/.   

Enter the Celsius temperate in the textbox and then press the Submit button.

The equivalent Farenheit temperature will be calculated and displayed in the box labelled "Which resulted in a conversion to Farenheit of".

Now you know what to wear outside.

---

## Here is the R code which is run for a Celsius temperature of 0 and 100


```r
temp<-0
farenheit <- (temp*9/5) + 32
farenheit
```

```
## [1] 32
```

```r
temp<-100
farenheit <- (temp*9/5) + 32
farenheit
```

```
## [1] 212
```

---

## My next app with take a Farenheit temperature and convert it to Celsius

Thank you for your support!!


  
