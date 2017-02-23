# Udacity-Data-Visualization-Project
Project 6 for Udacity Data Analyst Nanodegree

This project will be a visual data analysis of a set of data regarding the mortality of those aboard the titanic.

#Summary
This visualization is a stacked barchart showing the mortality rates of passengers in the titanic dataset separated by passenger class. The two levels of bars represent the global values of survivors and deaths respectively. Hovering over the bars indicates the exact global values, and also tells the mortality or survival rate.

#Design
When looking at the survival data by passenger class, I felt both the survival percentages and global values were both important. For instance, I wanted a chart that viewers would be able to look at and discern that a) Third class had the lowest survival rate and b) Third class had by far the most passengers.

I felt a stacked bar chart would show this clearly. I used global values to build the bars, so that the relative numbers of passengers were clear, and displayed more specific information regarding percentages via mouseover.

I chose two shades of blue for my stacked bars, since I felt they would provide discernable contrast without clashing (This was in part due to Initial Feedback 1). On mouseover, I highlighted the given bar to orange so that it was clear what was being looked at (This, along with the specific data displayed was a result of Initial Feedback 2).

The third piece of feedback I received concerned the size of my font, and I eventually settled on something larger than before so that the numbers were clearer all viewers.

#Feedback
1 - Initial Sketch Feedback
The first person to view my initial sketch mistook the meaning of the survivor and deceased bars upon first glance. They said a strong color contrast would make it easier to understand.

2 - Initial Sketch Feedback
The second person found the chart easier to understand but noted that they couldn't tell specifics, like totals or percentages. They said knowing this would make them more confident of their understanding.

3 - Later Feedback
One person felt the meaning of the chart was clear but said the numbers were difficult to read because they were so small.

#Resources
My primary resource, aside from the Udacity lesson was bl.ocks.org. I consulted the following pages:

https://bl.ocks.org/alandunning/274bf248fd0f362d64674920e85c1eb7

http://bl.ocks.org/mstanaland/6100713

http://bl.ocks.org/Caged/6476579

http://bl.ocks.org/phoebebright/3061203

Also, the following page was very helpful for ordinal scales:

https://jaketrent.com/post/use-d3-rangebands/
