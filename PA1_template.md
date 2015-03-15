# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data
First import the data using read.csv(), into a data.frame called **activity**
```{r]
## Read CSV data
activity <- read.csv("rep1/activity.csv")
## Convert activity$date using as.Date
activity$date <- as.Date(activity$date)
```
Data import and preprocessing are now complete.

## What is mean total number of steps taken per day?
First we will split the data.frame into the list **bydate**, then apply mean() to each of its elements

```r
## Split **activity** by date

## Apply *sum()* to every element of **bydate**.
```
rm(datesum)
sum(bydate[[3]])
hist(datesum)
head(datesum)
unlist(datesum)
## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
