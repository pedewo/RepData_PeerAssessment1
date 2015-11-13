# Reproducible Research: Peer Assessment 1


## Loading and preprocessing the data

```r
setwd("C:/Users/pedew_000/RepData_PeerAssessment1/")
Activity_Monitoring <- read.csv(unz("activity.zip","activity.csv"), header = TRUE, sep =",",
                                colClasses = c("numeric", "character", "numeric"))
head(Activity_Monitoring)
```

```
##   steps       date interval
## 1    NA 2012-10-01        0
## 2    NA 2012-10-01        5
## 3    NA 2012-10-01       10
## 4    NA 2012-10-01       15
## 5    NA 2012-10-01       20
## 6    NA 2012-10-01       25
```

```r
names(Activity_Monitoring)
```

```
## [1] "steps"    "date"     "interval"
```
## What is mean total number of steps taken per day?

## What is the average daily activity pattern?

## Imputing missing values

## Are there differences in activity patterns between weekdays and weekends?

