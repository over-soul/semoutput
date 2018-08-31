# semoutput
Package to create nice looking output for CFA and SEM analyses.

## Easy to use

The package contains an R Markdwon template that makes it very easy to run CFA and SEM analyses in R and create nice looking output.

Once you install the package, you will be able to access the RMarkdown template by going to

File -> New File -> R Markdown... -> From Template -> SEM RMarkdown

You simply need to specify the data file location in the YAML header under 

params:

&nbsp;&nbsp;&nbsp;&nbsp; data: "filepath"
  
Then specify the CFA or SEM model using lavaan syntax. 

Lavaan syntax is very intuitive to use and is documented with useful tutorials

http://lavaan.ugent.be/tutorial/index.html

Interact with an [Example Output](http://englelab.gatech.edu/R/Example_semoutput.html)

### Screen Shots

#### Model Fit

![alt text](https://github.com/dr-JT/semoutput/blob/master/Example/ModelFit_CFA.png)

#### CFA Output

![alt text](https://github.com/dr-JT/semoutput/blob/master/Example/Output_CFA.png)

#### SEM Output

![alt text](https://github.com/dr-JT/semoutput/blob/master/Example/Output_SEM.png)


#### Model Diagram

![alt text](https://github.com/dr-JT/semoutput/blob/master/Example/DiagramModel_SEM.png)

#### Correlation Matrix

![alt text](https://github.com/dr-JT/semoutput/blob/master/Example/CorrelationMatrix.png)


## Install

### First you may need to install the devtools package

install.packages("devtools")

### Then install the semoutput package from GitHub

devtools::install_github("dr-JT/semoutput")

## Required Packages

Uses the lavaan package to run CFA and SEM analyses

Uses the semPlot package to display model diagrams

Uses the sjPlot package to print the correlation table
