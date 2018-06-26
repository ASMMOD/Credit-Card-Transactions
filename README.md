

ReadMe: 



By Asmita Modi  



For: Regis University - MSDS -692 Data Science Practicum I  



Project Name: Credit Transaction (India/Australia) 



I will be researching credit card sales in India/ Australia.  The sales transaction will be examined for
Male and Females as to what the cards are being utilized for.  



I will also look at to see which type of credit card has the
most usage.   



Getting Started -Data Science Practicum I (Master Certificate in
Data Science) 



Git Hub was installed! And it has the following information
about the project has been placed on GitHub: 



o Data set (India and Australia)  



o R-Studio Codes 



o Data project – part 1 (Weka)



o Data project - Part II   (R-Studio) 



o Data project - Part III   (Tableau)




Prerequisites - Installation: Download the following software: 



R-Studio for Clustering 
//R-Studio codes 
setwd("C:/Users/guest 1/Desktop")
> data <- read.csv("OnlineRetail_v13_Australia.csv", header = TRUE)
> str(data)



////

> summary(data)

> save.image("C:/Users/guest 1/Desktop/DSP Project Workspace/OnlineRetail_v13_Australia.rdata.RData")
> barplot(prop.table(table(data$Gender)))
> barplot(prop.table(table(data$Quantity)))
> barplot(prop.table(table(data$UnitPrice)))
> barplot(prop.table(table(data$Cost)))

> barplot(prop.table(table(data$Cost)))

> data <- read.csv("OnlineRetail_v13_Australia.csv", header = TRUE)
> str(data)

> summary(data)




> barplot(prop.table(table(data$StkCode)))
> 
> barplot(prop.table(table(data$CardType)))
> barplot(prop.table(table(data$IntChg)))
> barplot(prop.table(table(data$Loss)))
> barplot(prop.table(table(data$Gender)))
> save.image("C:/Users/guest 1/Desktop/DSP Project Workspace/OnlineRetail_v13_Australiav1.rdata.RData")
> 
> 
> 
> 
> data <- read.csv("OnlineRetail_v15_India.csv", header = TRUE)
> str(data)


> data <- read.csv("OnlineRetail_v15_India.csv", header = TRUE)
> str(data)

> barplot(prop.table(table(data$CardType)))
> barplot(prop.table(table(data$IntChg)))
> barplot(prop.table(table(data$Loss)))
> barplot(prop.table(table(data$CustomerID)))
> save.image("C:/Users/guest 1/Desktop/DSP Project Workspace/OnlineRetail_v15_India.rdata.RData")
> 


> data <- read.csv("OnlineRetail_v15_India.csv", header = TRUE)
> str(data)
© 2018 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
API
Training
Shop
Blog
About

/// end 



Machine Learning for K-means 



KNN 



Tableau 



Weka



software installation download can be found at : https://www.rstudio.com/products/rstudio/download https://machinelearningmastery.com/download-install-weka-machinewww.tableau.com/Tableau/Download



Coding style - generated using RStudio, Tableau and Weka 



Utilized the above application noted.  



Thank you,  Asmita Modi 



