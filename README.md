---
title: "ReadMe"
author: "Vitaly Briker"
date: "June 6, 2018"
output: html_document
---

## MSDS 6306 Doing Data Science HomeWork Unit4

This is repository contain home work for unit 4, questions 1 and 2.

Qustion 1:

1. FiveThirtyEight Data (30 points): Navigate on GitHub to
https://github.com/rudeboybert/fivethirtyeight and read README.md. Seriously, it will
include every command you need. Test out some commands on R.
a. Install the fivethirtyeight package.
b. In the listing of Data sets in package ‘fivethirtyeight,’ assign the eighteenth data set to
an object ‘df.’
c. Use a more detailed list of the data sets to write out the URL in a comment to the
related news story.
d. Using R command(s), give the dimensions and column names of this data frame.

Qustion 2:

2. Data Summary (30 points): Use your newly assigned data frame for Question 2.
a. Write an R command that gives you the column names of the data frame. Right after
that, write one that counts the number of columns but not rows. Hint: The number
should match one of your numbers in Question 1d for dimensions.
b. Generate a count of each unique major_category in the data frame. I recommend using
libraries to help. I have demonstrated one briefly in live-session. To be clear, this
should look like a matrix or data frame containing the major_category and the
frequency it occurs in the dataset. Assign it to major_count.
c. To make things easier to read, enter par(las=2) before your plot to make the text
perpendicular to the axis. Make a barplot of major_count. Make sure to label the title
with something informative (check the vignette if you need), label the x and y axis, and
make it any color other than grey. Assign the major_category labels to their respective
bar. Flip the barplot horizontally so that bars extend to the right, not upward. All of
these options can be done in a single pass of barplot(). Note: It’s okay if it’s wider than
the preview pane.
d. Write the fivethirtyeight data to a csv file. Make sure that it does not have row labels.

## Reference

The source data for homework has been downloaded from package "fivethirtyeight",

"An R package that provides access to the code and data sets published by FiveThirtyEight https://github.com/fivethirtyeight/data. Note that while we received guidance from editors at 538, this package is not officially published by 538".



## Contact Information
vbriker@mail.smu.edu
