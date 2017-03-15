---
title       : ShinyPsych
subtitle    : Programming online experiments using R and Shiny
author      : Nathaniel Phillips
job         : Basel Research Colloquium - March 16, 2017
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## What is Shiny?

- Shiny is a web application framework for R
- From the website: Turn your analyses into interactive web applications. No HTML, CSS, or JavaScript knowledge required.

<img src="images/shinydiagram.png" title="plot of chunk cookmap" alt="plot of chunk cookmap" width="70%" style="display: block; margin: auto;" />

--- .class #id 
## How are Shiny Apps programmed?

asdf

--- .class #id 
## How does Shiny compare to other programs?

| Software| Time to Learn|Cost|Customizability | Best Suited for|
|------:|----:|:-----|:----|:----|:----|
|     UniPark / Qualtrics| Medium |   ?|Low | Questionnaires     |
|     Inquisit|    Medium / Low|? | Medium | Questionnaires, Simple stimuli     |
|     Custom HTML / JavaScript|   High|Free | Very High | Complex studies     |
|     Shiny|    Medium / High|Free* | High | Complex, statistical stimuli     |

--- .class #id 
## Shiny Pros and Cons

### Pros
- You can integrate all of your data management using R code within the experiment.
    - Great for dynamic experiments where stimuli depend on responses.
- Data can be easily exported in exactly the format you want to Dropbox or via email.
    - No need to worry about databases.

### Cons
- Crashing is, unfortunately, somewhat common.
    - No more than 20 simultaneous users.
- I wouldn't trust response time precision less than 500ms
