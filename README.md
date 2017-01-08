# Make Effective Data Visualization
## Data Analyst Nanodegree - project 6 
### 1.  Summary 

The data visualization shows how the chances of survival for Titanic passengers differed depending on their demographic characteristics. Based on almost 900 records, survival rates split by age range, gender and passenger class are shown. It appears that young females travelling on the first class were most likely to survive the catastrophe. The chances of survival dropped with increasing age, lower passenger class and when a passenger was male.

### 2.  Design
The visualization consists of four different views. The user can change between different views by using radio buttons located in the bottom left corner. With each click, the content of the chart changes, as well as the description and the title of the chart.

The first, introductory view was added after receiving feedback (see Feedback section) that it would be good to have some introduction before showing survival rates split by different characteristics. This view includes a pie chart. As dimple.js does not deal with chart labels natively, these were left off the visualization, however, all relevant info can be seen by hovering mouse over each of the pie chart's slices. Although pie charts are a little bit problematic to work with, the one in this view does not pose any threats to visibility. There are only two categories shown on the pie chart, and the chart itself does not have to be compared to anything else, being a standalone visualization.

Other views are composed of 100% stacked bar charts. The x-axis shows different categories (after receiving feedback, age was split into four buckets), whereas the y-axis contains percentage values. This kind of charts was the best choice for the visualization, as variables on the x-axis are not continuous, and the survivor ratio always sums up to 100% (percentage of survivors + percentage of casualties = 100%). 

Other design choices include the size of the visualization, colors that were used as well as the legend.

*The visualization does not have a fixed size in pixels. Percentage values were used to place different sections of the viz on the webpage. As a result, the visualization will always fit into the browser's window, depending on its size. This functionality was well-received in the feedback.

*The initial color pallette (pale red/pale green), was changed after receiving feedback that it might be problematic for people experiencing color blindness. 

*The legend is always in the same place, relative to the size of the browser's window.
### 3.  Feedback

**The first feedback** that I received was from a fellow Udacity student. It is listed below: 

*"Happy New Year :*

*here is my review for the Titanic Data:*

*1 : I did notice that the three categories you choose have a big impact on the survival. If you are a less than 10 years old, a female and from the 1st class your survival chances were much more than if you are old male from the 3rd class.*

*2 : What we miss from this visualization is an idea of the number of person by category. It would be interesting to know if they were much more older person than younger person.*

*4 : I like the explanation you write for each visualization and how it adapts to the size of the screen.*

*Here is the remarks I'll do:* 

*You use the red and the green and we learned in class that you don't know your audience and you should not use red and green, in regard to color blind people.* 

*In the survival age split visualization, I would not do as much categories.*

*Otherwise I really like your work.""*

*Emmanuelle*

**The second feedback** I received was from my co-employee. He listed three main things that he would like to see differently:

*In the initial version of the visualization, there were no margins for the bottom part of the webpage (one including radio buttons and descriptions), whereas the top part with the chart had them. My colleague noted that margins should be introduced for both parts, so that they are in line with each other

*My colleague also noted that there might be a problem with the color pallette.

*According to my colleague, font sizes for the legend and the tooltips were too small and therefore unreadable. This was changed.


**The final feedback** that I received was from my fiancee. She noted two things specifically:

*There was no introductory view for a storyline that I wanted to tell. In the initial version of the webpage, the first view is automatically survival rate split by age range. In the second version, an introductory view is added.

*The chart titles in the initial version were not clear. They were rephrased in the final version.

### 4. Resources
[Stack Overflow](http://stackoverflow.com)  
[Dimple documentation](http://dimplejs.org)