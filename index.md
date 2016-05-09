---
title       : 'Course Project: Shiny Application and Reproducible Pitch'
subtitle    : Body Mass Index (BMI)
author      : Mathupanee Oonsivilai
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What is BMI?

* BMI, which was first proposed by the Belgian statisfactorytalktician Adolphe Quételet in 1835.  Its popularity derives from its simplicity and the fact that weight and height are easily measured.

* The BMI is a rough attempt to quantify the amount of tissue mass (muscle, fat, and bone) in an individual, and then categorize that person as underweight, normal weight, overweight, or obese based on that value.

* There is some debate about where on the BMI scale the dividing lines between categories should be placed[1] and lately, more debate on it's overall usefulness.

* Commonly accepted BMI ranges are underweight: under 18.5, normal weight: 18.5 to 25, overweight: 25 to 30, obese: over 30.

---

## How to calculate

Is calculated by the formula


$$BMI = (\frac{Weight(kgs)}{Height(m)^2})$$


#### Example

A person 56 kgs and 170 cms would have


```r
weight <- 56
height <- 1.7
BMI <- (56/1.7^2)
BMI
```

```
## [1] 19.37716
```

The BMI may also be determined using a table or chart which displays BMI as a function of mass and height using contour lines or colors for different BMI categories, and may use two different units of measurement.

---

## Body Mass Index Table

![](bmitable.jpg)

---

## Controversy

#### Cons

* Like IQ, the single number for BMI does not tell us all we need to know.

* BMI does not distinguish between fat mass and lean mass (muscle, water, bone, etc).

* Someone who is physically fit can have a high BMI due to having greater than average muscle mass misclassifying some people as obese (BMI of 30 or greater) who are not obese

* Using this criterion actually misses more than half of people with excess body fat.

#### Pros

* In a study assessing attractiveness, females judge men and women with higher BMI as less attractive with BMI being the sole indicator of attractiveness [2]

---

## References

1. Dr Malcolm Kendrick (April 12, 2015). "Why being 'overweight' means you live longer: The way scientists twist the facts"
2.  Dr Sonia Oreffice (April 7, 2016) "Research into the correlation between beauty and body size shows that women are the harshest judges"




