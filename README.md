# Introduction

This is an assignment from week 2 of [The Reproducible Research][1] course offered by [Coursera][2]. 
This assignment makes use of data from a personal activity monitoring device. This device collects data at 5 minute intervals through out the day. The data consists of two months of data from an anonymous individual collected during the months of October and November, 2012 and include the number of steps taken in 5 minute intervals each day.

This work is done on RStudio for Linux. GitKraken for linux is used as a Git Client. This is written in R markdown and using knitr package a markdown and html file is created.

[1]: https://www.coursera.org/learn/reproducible-research
[2]: https://www.coursera.org


**For Faster Navigation**

1. [PA1_template.Rmd](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.Rmd)

2. [PA1_template.md](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md)

3. [Figures](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/tree/master/PA1_template_files/figure-html)


## Assignment


#### [Loading and preprocessing the data](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#loading-and-preprocessing-the-data)



#### [What is mean total number of steps taken per day?](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#what-is-mean-total-number-of-steps-taken-per-day)

1. [Make a histogram of the total number of steps taken each day.](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#1-creating-a-histogram)

2. [Calculate and report the mean and median total number of steps taken per day.](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#2-mean-and-median-total-number-of-steps-per-day)



#### [What is the average daily activity pattern?](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#what-is-the-average-daily-activity-pattern)

1. [Make a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all days (y-axis).](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#1-making-a-time-series-plot-ie-type--l-of-the-5-minute-interval-x-axis-and-the-average-number-of-steps-taken-averaged-across-all-days-y-axis)

2. [Which 5-minute interval, on average across all the days in the dataset, contains the maximum number of steps?](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#2-finding-the-maximum-number-of-steps-in-the-time-series-plot)


#### [Imputing Missing Values](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#imputing-missing-values)

1. [Calculate and report the total number of missing values in the dataset (i.e. the total number of rows with NAs).](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#1-calculating-the-total-number-of-missing-values)

2. [Devise a strategy for filling in all of the missing values in the dataset. The strategy does not need to be sophisticated. For example, you could use the mean/median for that day, or the mean for that 5-minute interval, etc.](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#2-devising-a-strategy-for-filling-in-all-of-the-missing-values-in-the-dataset)

3. [Create a new dataset that is equal to the original dataset but with the missing data filled in.](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#3-creating-a-new-dataset-equal-to-original-dataset-without-any-missing-value)

4. [Make a histogram of the total number of steps taken each day and Calculate and report the mean and median total number of steps taken per day. Do these values differ from the estimates from the first part of the assignment? What is the impact of imputing missing data on the estimates of the total daily number of steps?](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#4-new-dataset-creating-a-histogram-find-mean--median--comparing-with-original-dataset)



#### [Are there differences in activity patterns between weekdays and weekends?](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#are-there-differences-in-activity-patterns-between-weekdays-and-weekends)

1. [Create a new factor variable in the dataset with two levels -- "weekday" and "weekend" indicating whether a given date is a weekday or weekend day.](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#1-creating-a-new-factor-variable-in-the-dataset-with-two-levels---weekends-and-weekdays)

2. [Make a panel plot containing a time series plot (i.e. type = "l") of the 5-minute interval (x-axis) and the average number of steps taken, averaged across all weekday days or weekend days (y-axis).](https://github.com/ashutoshparajuli/RepData_PeerAssessment1/blob/master/PA1_template.md#2-creating-a-panel-plot-containing-time-series-plot-of-5-min-interval-x-axis-vs-average-number-of-steps-y-axis-averaged-across-all-week)
