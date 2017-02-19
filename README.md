# P6 Visualization-using-dimple.js-and-D3

### Summary :

In this project I chose Titanic Dataset for visualization .Though the actual number of passengers was more than 2000 but in this dataset
I worked with 892 datapoints. During analysis I found that the survival chance of female was significantly higher than male .Also the 
children were rescued wih higher priority than elders . When analysed the passenger class I found that the survival chance of first class 
passenger was the highest and that of third class was the lowest .So we can say female, Children ad Rich survived better which is clearly 
shown in my final plot.

### Design :

The information on survival and sex looked most interesting to me .So I chose bar plot for an effective visualisation .I took Sex on x-axis
ans survival information on Y-axis .Secondly I chose Age . For better information I categrised the passengers into 3 age groups and showed 
the visualization accordingly .My first visualisation can be seen [here](http://htmlpreview.github.io/?https://github.com/kamal11k/Visualization-using-dimple.js-and-D3/blob/master/index.html)

Then after few feedbacks I changed these things :

I added two buttons .One for counting the total numbers and one for representing that value in percentage .I also added one more variable
i.e Passenger class into visualization .Changed the transition time to give a better feel of animation . Changed colors of the bars .Added
comment lines where ever necessary .Added a headline .My final visualization can be seen [here](http://htmlpreview.github.io/?https://github.com/kamal11k/Visualization-using-dimple.js-and-D3/blob/master/index2.html)

### Feedbacks :

@georgeliu1998

Here're my thoughts:
* Since you used "survival rate" as the title, it's better to use actual rates for the y axes
* I am not good with colors - for me the color orange seems to be very close to red which is normally associated with risk, alert etc., therefore maybe it'll be more intuitive to use it with not survived?
* A short explanation can help communicate and reinforce your findings


@devFarmaan1d

* I notice that the survival rate of female is higher .
* No questions.
* The relationship was between sex and survival rate , Age group and Survival rate .
* I liked your color preference as you stuck with the default ones and your clear visualizations .
* You used count for survival rate . Percentage could have also been applied which gives better visualization for survival rate .

@Abhas

* I noticed female,rich and child have higher survival rate .
* I agree with @george . Rather I would say you can show both count and percentage for better understanding .One additional feedback :)
  you can comment your html file .
  
### Resources :
* http://dimplejs.org/
* https://github.com/d3/d3/wiki
* https://stackoverflow.com
