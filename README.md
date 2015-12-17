This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

In his paper **"Automobiles on Steroids: Product Attribute Trade-Offs and Technological Progress in the Automobile Sector"**  Christopher R. Knittel (2012) estimates the technological progress since 1980 and the trade-offs faced when choosing between different attributes such as weight, fuel economy or engine power characteristics.
In this interactive offline R Tutorial, we are going to gradually reproduce their study and discuss it. 


## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
if (!require(devtools))
  install.packages("devtools")
source_gist("gist.github.com/skranz/fad6062e5462c9d0efe4")
install.rtutor(update.github=TRUE)
  
install_github("MariusBreitmayer/AttributeTradeOffs")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorAttributeTradeOffs)

# Adapt your working directory to an existing folder
setwd("C:/insertdirectoryHERE")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorAttributeTradeOffs",
       load.sav=TRUE, sample.solution=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
