---
title       : Approximations to Integrals
subtitle    : Visualizing the area under a non-negative function
author      : Jesse MB
job         : Data Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

<!-- Limit image width and height -->
<style type='text/css'>
img {
    max-height: 400px;
    max-width: 964px;
}
</style>

<!-- Center image on slide -->
<script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.7.min.js"></script>
<script type='text/javascript'>
$(function() {
    $("p:has(img)").addClass('centered');
});
</script>

## Definite Integral as Area

The definite integral of a non-negative function $f(x)$ from $x=a$ to $x=b$ is 
the area between the $x$-axis and the function.



For example, the area indicated in the function below shows
$\int_{0}^{10}x^2dx$.

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 


--- .class #id 

## Toys!

Since students understand things better when they can get their hands on the material
and play with it, we've made a simple app to help visualize approximating the "area under
the curve" with rectangles.

![height](assets/img/screenshot.png)

--- 

## Different Functions

Students can choose between an increasing and a decreasing function.

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

---

## Different Sums

Students can choose between left-hand and right-hand sums.

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png) 

---

## Different Numbers of Rectangles

Students can see how, as the number of rectangles increases, 
the area covered by the rectangles gets closer to the desired area under the curve.

![plot of chunk unnamed-chunk-4](assets/fig/unnamed-chunk-4-1.png) 
