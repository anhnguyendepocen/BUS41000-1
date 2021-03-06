# Shiny Apps for BUS41000

A collection of shiny applications for teaching.
Many of them are modifications of applications I found online.

The easiest way to see demonstrations of these applications
is to follow the demo links below.

Alternatively, you can run the applications from your own computer.
If you choose this option, you will need to install some R packages first.
The shiny apps here rely on a number of external resources.
In order to install all packages needed for the shiny applications --- and
the course --- run the following command in R:

	source('https://raw.githubusercontent.com/mlakolar/BUS41000/master/BUS41000.packages.R')

Once you have the required packages installed, run the following code
to, for example, see the demo of `simpleHistogram` application:

	shiny::runGitHub('mlakolar/BUS41000',
					subdir = 'shinyApps/simpleHistogram',  
					launch.browser = T)

In order to run other applications, try

	shiny::runGitHub('mlakolar/BUS41000',
					subdir = 'shinyApps/<nameOfApplication>',  
					launch.browser = T)

where `<nameOfApplication>` should be substituted by one of the names below.


* [Lecture 01](#lecture-01)
  * [simpleHistogram](#simplehistogram)
  * [wikiPageViews](#wikipageviews)
  * [bivariateCorrelation](#bivariatecorrelation)
  * [correlationGame](#correlationgame)

* [Lecture 02](#lecture-02)
  * [twoAssetPortfolio](#twoassetportfolio)
  * [studentHeightWeight](#studentheightweight)

* [Lecture 04](#lecture-04)
	* [RV_distributions](#rv_distributions)
	* [DistributionCalculator](#distributioncalculator)

* [Lecture 06](#lecture-06)
	* CLT proportions
	* Confidence intervals

## Lecture 01

### simpleHistogram

Illustration of the effect of number of bins on the appearance of a histogram.  
DEMO: [link](https://mlakolar.shinyapps.io/simpleHistogram/)


### wikiPageViews

Wikipedia Page Views Statistics. Plots Wikipedia article traffic statistics.    
DEMO: [link](https://mlakolar.shinyapps.io/wikiPageViews/)


### bivariateCorrelation

Scatter plot of two variables. Explore how does the sample correlation affect
the plot.   
DEMO: [link](https://mlakolar.shinyapps.io/bivariateCorrelation/)

## correlationGame

Guess the correlation between two variables. Taken from [https://github.com/ShinyEd/ShinyEd](https://github.com/ShinyEd/ShinyEd).  
DEMO: [link](https://mlakolar.shinyapps.io/correlationGame/)


## Lecture 02

### studentHeightWeight

Height and weight of schoolchildren    
DEMO: [link](https://mlakolar.shinyapps.io/studentHeightWeight/)

### twoAssetPortfolio

Illustrating effect of correlation on the returns of a portfolio.   
DEMO: [link](https://mlakolar.shinyapps.io/twoAssetPortfolio/)


## Lecture 04

### RV_distributions

Draws random numbers from a probability distribution.
Plots a histogram of the sample together with a probability density function.      
DEMO: [link](https://mlakolar.shinyapps.io/RV_distributions/)

### DistributionCalculator

Illustrates concept of PDF and CDF.  
DEMO: [link](https://mlakolar.shinyapps.io/distributionCalculator/)

## Lecture 06

### CLT proportions

DEMO: [link](https://mlakolar.shinyapps.io/CLT_prop/)

### Confidence intervals

DEMO: [link](http://faraway.neu.edu:8080/cinterval/)

