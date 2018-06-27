

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

##EDA Criteria-
I looked at a few data set and in trying to determine the exploratory data analysis and seeing which data set will allow me the opportunity to provide enough information for my hypothesis. After choosing my data set I looked at what possible tool sets and packages 
I can use in determining my criteria.  I was able to determine that with this current data set I should be able to do some data manipulation, data visualization to do some analysis that can possibly answer my question. Therefore, I found two data sets that I will be utilizing for this project. The dataset are compiled with information of credit card usage, in terms of what the monies are spent on and which gender is utilized the usage of CC frequently. 

1)	Data Exploration
2)	Data analysis 
3)	Data Massage 

##Process Flow: 
The purpose of the flow chart is to show step-by-step flow of the process. 
https://github.com/ASMMOD/Credit-Card-Transactions/files/2139523/process.flow.docx

Git Hub was installed! And it has the following information
about the project has been placed on GitHub: 



o Data set (India and Australia)  



o R-Studio Codes 



o Data project – part 1 (Weka)



o Data project - Part II   (R-Studio) 



o Data project - Part III   (Tableau)




Prerequisites - Installation: Download the following software: 



##R-Studio for Clustering 
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



##Machine Learning for K-means 



KNN 



Tableau 



Weka



software installation download can be found at : https://www.rstudio.com/products/rstudio/download https://machinelearningmastery.com/download-install-weka-machinewww.tableau.com/Tableau/Download



Coding style - generated using RStudio, Tableau and Weka 



Utilized the above application noted.  



Thank you,  Asmita Modi 



