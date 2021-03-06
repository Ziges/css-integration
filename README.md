# css-integration
[View interfaces](https://ziges.github.io/css-integration/)

## The challenge
For this exercise we are challenged to consolidate our CSS knowledge by building two full CSS integrations in the form of interfaces. 
This is an exercise in precision and accuracy where we are demanded to re-create two views pixel-perfectly.

### Interface 1 
In the first integration exercise I used the css flexbox properties to make a card layout using a main container and nesting the boxes within.
To make the boxes responsive for smaller screens I used media queries.
Important takeaways: to equally size the images make one of the width or height properties 'auto'. Also it is important to use a logical width 
for the boxes so that the space is maximised without going over borders. To ensure this, add margins and padding to the main container and boxes. 

### Interface 2
In the second integration exercise I used box-standard css to style the container div with 3 nested elements: 2 div's and a footer. 
It was very tricky to achieve the exact pixel perfect layouts as required. I got very close, except for the HR line which in a < tr > tag I was unable to draw 
the entire line without splits. 

With hindsight, it may have been a better idea to work with a CSS utility framework like Tailwind.


### Interface 3
The third integration exercise looked simple at first, yet it was anything but. For this challenge I sed the main image in a container div element 
floated to the left, that way I could simply add my content to the right of the image. This worked but with hindsight I may have been better off using the flexbox display 
structure, with 2 columns, which would have save me time and allowed me to add a border around the content which unfortunately now isn't possible or all my content disperses over the page. 

All that said, it's all about learning and choosing the right tactics from the get-go in order to save time. 


