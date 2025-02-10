---
title: Descriptive Statistics, Quant for Qual Researchers
tags: [ "UX research", "UXR tools", "quantitative research", "mixed methods" ]
date: 2025-02-09
description: My working list of quant resoruces for qual researchers.
---

_This article follows my series [Quant for Qual Researchers, a work in progress](https://www.zoracabrera.com/blog/quant-for-qual-researchers-a-work-in-progress/), which I started for qual researchers who want to upscale their toolbox but don't know where to start._

Descriptive statistics, as their name suggests, provide us a way to describe or summarize the characteristics of a data set. This type of statistics can be divided into 3 main types:

- [Central tendency](#central-tendency)
- [Variability](#variability)
- [Frequency Distribution](#frequency-distribution)

<span id="central-tendency"></span>
## Central Tendecy 
Central tendency refers to the number in the middle of the data set, in other words, the average. There are 3 different type of averages. Why are there 3 different types of averages? Well, because each has it's pros and cons.  The table below summarizes the key differences.

| Measure of Central Tendency | Definition| Merits | Problems|
|--------|---------------|---------------|---------------|
| Mean | This is the central tendency measure most of us use. It is calculated by taking the sum of all numbers in a data set, and dividing it by the count of all numbers in a set. | Easy to calculate. Works best when the numbers are similar/not spread too far appart.| May result in a number that is not part of a list. Often it results in a decimal, which doesn't always makes sense. There's no such thing as a 0.5 person. |
| Median | This refers to the number in the middle of the list of numbers. | Results in true, representable numbers. Good if there are extremes within a list. | It's easily altered by the change of a mid point (for example, if you add one number to the start or end). It an also be time consuming to calculate.|
| Mode | This refers to the number that is repeated the most within a set of numbers. | Good for when a pattern is not spread evenly, in other words, when a certain value repeats more frequently or when the  majority of the numbers are above or below the mean. | It can be altered easily by a single number change. Can result in more than one number as the central tenency. |

<span id="variability"></span>
## Variability
Because there are problems with all types of central tendency measures, we often want to pair them with a measure of variability and a measure of distribution. Variability measures specifically refer to how far apart from the mid point and from each other. There's a few different ways to describe variability; the most common are:

| Variability Measure | Definition | Common use cases |    
|--------|---------------|---------------|
| Range | The difference between the first number and the second number.| This is the easiest way to calculate variability, and therefore used commonly. However, it can be miss leading if there are outliers, such as a list like: 1,2,3,4, 100 |
| Interquartile range | The different between the number in the 25th percentile, and the number in the 75th percentile. | This is commonly used for creating a [boxplot](https://www.scribbr.com/statistics/interquartile-range/), which visually represents variability. The bigger the box (and thus bigger the interquartile) the wider the variability. Boxplots, also help show weather numbers are distributed more towards the right or left of the median. |
|Standard Deviation | The average distance from the mean | Although not the easiest to calculate, standard deviation is commonly use because it is a better indicator not just of how spread out values, but also how unevenly spread out they are. A higher standard deviation means numbers are more spread apart from the mean, and more unevenly spread apart. |
| Variance | The average of squared distances from the mean | Variance is important for common statistical tests. |

<span id="frequency-distribution"></span>
## Frequency Distribution
Frequency distribution describes how often a score or a value is observed within a data set. There are four types of frequency distributions.

| Frequency Distribution Type| Definition|
|--------|---------------|
| Ungrouped| The number of observations of each value.  For example, how many black cats in a group of cats of different colors.|
| Grouped | This is used for grouping quantitative data, and describes the number of times a number within an interval is observed. For example how many people within a group are between 20 and 22 years old. |
| Relative Frequency | This is used for comparing frequencies. It describes the proportion of the occurrence. For example, if there 4 black cats, in a group of 20 cats, then the relative frequency is 0.2.|
| Cumulative frequency | This is used to understand how often an observation falls bellow a specific value. This can be used for quantitative data or ordinal data. For example, say we are ranking the expertise of a group for a given activity. They can be ranked as Beginner, Intermediate, or Advanced (a type of ordinal data). There are 5 beginners, 2 intermediate, and 1 advanced, The cumulative frequency is 5 people are below intermediate level, and 7 (5+2) people are below advanced level. |

## Additional Resources
If you'd like to dig more into descriptive statistics, I recommend checking out [Descriptive Statistics | Definitions, Types, Examples](https://www.scribbr.com/statistics/descriptive-statistics/) by [Pritha Bhandari](https://www.scribbr.com/author/pritha/ "All articles by Pritha Bhandari").