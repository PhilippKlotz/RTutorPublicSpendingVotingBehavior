# RTutorPublicSpendingVotingBehavior
This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor).

The problem set "Public Spending and Voting Behavior - An Interactive Analysis with R" takes the user on a journey through the economic paper 
"Stimulating the Vote: ARRA Road Spending and Vote Share" by Emiliano Huet-Vaughn (2019). The economic findings along with the according analytic steps, as well as explanations of the economic theory behind it and useful R commands are covered in an interactive way.
The original paper can be found on https://www.aeaweb.org/articles?id=10.1257/pol.20170151

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("PhilippKlotz/RTutorPublicSpendingVotingBehavior")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorPublicSpendingVotingBehavior)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorPublicSpendingVotingBehavior")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorPublicSpendingVotingBehavior",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
