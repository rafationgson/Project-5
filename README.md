# Project-5 Exploratory Data Analysis of Video Calls and their Total Bandwidth Usage

The purpose of this analysis is to identify the factors that lead to a higher total bandwidth usage and longer call duration. This dataset includes calls from July 2020 up to September 2020, and it includes information such as the platform used, date, duration, whether the participants turned on their mic, and more.

This is a public dataset from https://www.kaggle.com/dikamsiyoung/conference-call-bandwidth-consumption.

## Project at a glance:
Code used: Python, Pandas, Matplotlib, Seaborn, and Numpy.

## Data Cleaning:
1. Corrected the Platform value of the first row, by removing the unnecessary space.
2. Converted the date column into a datetime format and extracted the day and month.
3. Extracted the hour and AM/PM from the start time column.
4. Added a column for call duration in seconds.

## Data Exploration and Findings:
1. Based on this dataset, majority of the calls use Zoom as the platform. This finding needs more data to verify.
2. Most calls occur on Mondays and Wednesday.
3. The month of August had the highest number of calls.
4. Looking at the number of calls per hour, 9 AM to 12 NN have the highest number of calls.
5. Positive correlation between the duration of calls and the total bandwidth usage.
6. Calls that have participants that turn on their mic, others that share screen, and are classified as group calls have a higher probability of having a longer call duration and more total bandwidth usage.

![Image](https://github.com/rafationgson/Project-5/blob/master/Platform.png)  ![Image](https://github.com/rafationgson/Project-5/blob/master/Calls-Hour.png)

![Image](https://github.com/rafationgson/Project-5/blob/master/Participant.png)  ![Image](https://github.com/rafationgson/Project-5/blob/master/Group.png)



