# Introduction to dataset
As a student, it is important to be aware of how to translate what you learned in school into the real world. One of the necessary translations is understanding how the market quantifies your contribution in the workforce. This is why I have taken an interest in Statistics Canada's dataset on Labour market outcomes for college and university graduates [found here](https://www150.statcan.gc.ca/n1/pub/71-607-x/71-607-x2019031-eng.htm). This specific dataset documents Class of 2012's income both 2 years after graduating and 5 years after graduating. Variables such as field of study and educational qualification played significant roles in affecting income. 

# My goals
While I liked specific aspects of the visualizations, I thought there were also some aspects that could be re-developed to better explore the dataset. My goal here is to critique the current visualization in Statistics Canada, wireframe a solution, and finally test out my solution. 

# Critique of Statistics Canada's current visualization
![Current visualization of data](https://i.ibb.co/mBdsY5Q/Income-original-graph.jpg)

What works well: 
Intuitiveness- The bar graph chosen is a commonly used visualization, and therefore users are able to quickly grasp the content and objective. 

Limit use of colors- I like how there are only 2 colors used, light blue and dark blue. It conveys the contrast income data effectively.

What doesn't work well:
Completeness- Only when I downloaded the dataset did I realize that there is a important variable that was not considered in the visualization: Field of study. Furthermore, the income actually differs quite a lot depending on field of study across the educational qualifications. 

Truthfulness - It would be inaccurate to tell any student with a undergraduate degree that they can expect the median graduate income, if they went and obtained the graduate degree. Field of study is a attribute that is not exhibited, and it heavily impacts the income. The visualization does not depict the variability of income depending on field of study. 

# Wireframe a solution
I am a pen-and-paper kind of thinker, so I decided to wireframe on a piece of paper:
![My wireframes](https://i.ibb.co/QYnPrcy/IMG-0450.jpg)

I showed all 3 options to a friend, and here is the feedback: 
Option 1:
- It doesn't make sense why you are stacking the degree against income. Did you mean to show the proportion of degree within each field of study? 

Option 2: 
- For this graph, it will be interesting to see how the same degree results in different income levels. 
- Do you have a lot of field of studies? Seems complicated with all the bars. 

Option 3: 
- Where is the 5 year outcome? I thought the goal is to compare and contrast 2 year and 5 year here (like you did in the previous option). 
- The dot format is interesting, I can easily focus on the top incomes from different fields of study. 

In the end, I decided to implement Option 2 as my solution, because it had the most comprehensive visualization of all aspects of my dataset. I also wanted to see if the bars will indeed look overcrowded. 

# Solution-building, V.1
My initial solution via Tableau: 
![Version 1](LabourMarket_V1.png)
Feedback from viewer: I like it! You can see how valuable each level of attainment is for each field is. For architecture & engineering, getting a masters degree doesn't help very much. For education it helps a lot! One thing I'd like to see, is the 2 levels overlay one another. So for business administration, if you can stack them, and the difference is in a different color, then the difference is obvious. 

My thoughts: It makes sense that stacking the income of 2 year vs. 5 years will give viewers a better idea of income growth. I decided to tweak the visualization in Tableau:

# Solution-building, V.2

