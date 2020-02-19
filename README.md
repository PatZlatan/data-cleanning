# data-cleanning
Coding class
Group 1:
Cleaning data

It is a process of making your data set homogen, compact and usable for data analysis.
Why? To remove all the incoherent data
What? Can be missing data, not well reported data, insufficient data 
When? Before data analysis 
How? Using some codes :
“Name of cleaned data <-dataset[complete.cases(dataset),]”
“Name of cleaned data<-na.omit(dataset)”

Use the function 
		Is.na(Dataset)
To check your data set before cleaning. It will give an overview of data missing
Because missing values are coded as “Na”, to analyse data without removing missing values, you can give a value to all the Na as 99, by “Dataset[dataset == 99]
