# Questions

I made this .csv file called pie_chart.csv. I've been trying to make a pie chart for every single sample that is on there, with the other columns being categories that the pie charts display. I currently have this so far:

`#Pie Chart
library(readr)
x <- read_csv("pie_chart.csv")`

`#rename the first column
colnames(x)[colnames(x)=="X1"] <- "Sample"`

I am confused as to how to continue from here. I have tried a for loop but would appreciate any help that is given! Thank you!
