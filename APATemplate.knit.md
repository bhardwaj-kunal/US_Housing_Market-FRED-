---
title             : "Understanding Housing Market Trends and Risks : An Analytical Study"
shorttitle        : "Housing Market Trends and Risks"

author: 
  - name          : "Kunal Bhardwaj"
    affiliation   : "1"
    email         : "kunal5@illinois.edu"
    role: # Contributorship roles (e.g., CRediT, https://credit.niso.org/)
      - "Conceptualization"
      - "Writing - Original Draft Preparation"
      - "Writing - Review & Editing"

affiliation:
  - id            : "1"
    institution   : "UIUC"


authornote: |
  Enter author note here.

abstract: |
  One or two sentences providing a **basic introduction** to the the problem being addressed by this study. 
  One sentence summarizing the main result.
  Two or three sentences explaining what the **main result** reveals in direct comparison to what was thought to be the case previously, or how the  main result adds to previous knowledge.
  One or two sentences to put the results into a more **general context**.
  Two or three sentences to provide a **broader perspective**, readily comprehensible to a scientist in any discipline.
  
  <!-- https://tinyurl.com/ybremelq -->


bibliography      : "r-references.bib"

floatsintext      : no
linenumbers       : yes
draft             : no
mask              : no

figurelist        : no
tablelist         : no
footnotelist      : no

classoption       : "man"
output            : papaja::apa6_pdf
---





# Introduction

A brief introduction/motivation for the problem at hand, relevant details about the data, additional relevant scientific information, and what is to be addressed.

Citation example:

citation within parenthesis [@tsa4]



# Methods

A discussion and justification of the methods you have used to analyze the data and how you went about analyzing the data. Don't forget to describe in some detail how and why the particular model was selected.


Do not include the R code inside the report unless it is absolutely necessary. If you think a code is absolutely important, you can create an additional section at the end of the report (Appendix) and print all the codes there (not the output). In the main report, keep important and relevant results only.

Don't do this


```r
acf1(soi)
```

![ ](APATemplate_files/figure-latex/unnamed-chunk-1-1.pdf) 

```
##  [1]  0.60  0.37  0.21  0.05 -0.11 -0.19 -0.18 -0.10  0.05  0.22  0.36  0.41
## [13]  0.31  0.10 -0.06 -0.17 -0.29 -0.37 -0.32 -0.19 -0.04  0.15  0.31  0.35
## [25]  0.25  0.10 -0.03 -0.16 -0.28 -0.37 -0.32 -0.16 -0.02  0.17  0.33  0.39
## [37]  0.30  0.16  0.00 -0.13 -0.24 -0.27 -0.25 -0.13  0.06  0.21  0.38  0.40
```

Don't do this (unless you really want to print out the values)

![ ](APATemplate_files/figure-latex/unnamed-chunk-2-1.pdf) 

```
##  [1]  0.60  0.37  0.21  0.05 -0.11 -0.19 -0.18 -0.10  0.05  0.22  0.36  0.41
## [13]  0.31  0.10 -0.06 -0.17 -0.29 -0.37 -0.32 -0.19 -0.04  0.15  0.31  0.35
## [25]  0.25  0.10 -0.03 -0.16 -0.28 -0.37 -0.32 -0.16 -0.02  0.17  0.33  0.39
## [37]  0.30  0.16  0.00 -0.13 -0.24 -0.27 -0.25 -0.13  0.06  0.21  0.38  0.40
```

But do this

![ ](APATemplate_files/figure-latex/unnamed-chunk-3-1.pdf) 

## Subsection title

If you want to put any additional subsection, you may use this style.

# Results

A presentation of the results of your analysis. Interpretations should include a discussion of statistical versus practical import of the results.

# Discussion

A synopsis of your findings and any limitations your study may suffer from.

\newpage

# References

::: {#refs custom-style="Bibliography"}
:::

# Appendix (Optional)

Any R codes or less important R outputs that you wanted to keep- can go in here.
