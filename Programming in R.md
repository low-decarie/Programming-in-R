Programming in R
========================================================
author: Etienne Low-Décarie
date: December 6, 2016

Outline
========================================================

- Why programming
- Control structures
  - Loops
  - Conditions
- Functions

Why programming?
========================================================

https://www.youtube.com/user/CodeOrg

- Avoid repetitive computer tasks (ever)
- Literacy: reading code
- Considered top 10 desirable professional skill (Forbes.com)


Preperation
========================================================


```r
#install.packages("traits")
require(traits)

#install.packages("oce")
require(oce)
```




"For" loops
========================================================


```r
for(i in 1:10){
  print(i)
}
```

```
[1] 1
[1] 2
[1] 3
[1] 4
[1] 5
[1] 6
[1] 7
[1] 8
[1] 9
[1] 10
```

"For" loops
========================================================


```r
sentence <- NULL
for(words in c("This","does","not yet appear",
           "to be useful")){
  sentence <- paste(sentence,words)
}
print(sentence)
```

```
[1] " This does not yet appear to be useful"
```


"For" loops
========================================================

Get data for multiple coral species












```
processing file: Programming in R.Rpres
Loading required package: traits
Loading required package: oce
Loading required package: ggplot2
Quitting from lines 71-79 (Programming in R.Rpres) 
Error: could not find function "coral_taxa"
In addition: Warning messages:
1: In library(package, lib.loc = lib.loc, character.only = TRUE, logical.return = TRUE,  :
  there is no package called 'traits'
2: In library(package, lib.loc = lib.loc, character.only = TRUE, logical.return = TRUE,  :
  there is no package called 'oce'
Execution halted
```
