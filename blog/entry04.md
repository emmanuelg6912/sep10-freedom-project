# Tinkering with a new app called Foundation Framework 
##### 3/13/26

### Context 

This is currently my fourth blog entry on the topic of animal conservation and developing possible inventions that could be made. Last time I brainstormed and researched what inventions would help in the process of animal conservation. Now I'm using those ideas to develop it into a functional website. In this blog entry I will go over the app that I ended up choosing to work on my project, why I chose it, its uses, and my takeaways on the app. 

### Content 

I decided to choose **foundation framework** because its idea was very interesting. The idea that there could be an app that lets you customize websites from every device sounds like a really good idea. Another reason why I chose it is because the commands and code are easy and intuitive to use which can allow for easy creation of websites without requiring so much effort. 

#### 1. Typography within foundation framework 

* One thing that really stood out to me about the foundation framework was its easy to learn and intuitive typography within websites. At times the code and elements within html remained the same however the typography did change at times. Sometimes the text would automatically change based on the heading given. So, if there was a ``<h1>`` then the text would be automatically resized to be bigger. However, if an ``<h4>`` tag was implemented then the text would shrink and the font would be smaller.

* Another thing that stood out to me was the implementation of ``<a>``/anchor tags and href elements within text. I noticed that when an anchor tag linked to another website was placed within the text the sentence that was inside of the anchor tag became a clickable link and would send you to the specific website. 
  
*  I also noticed that there were element specific commands given to headings within the foundation framework. This was shown in the foundation document where a ``<small>`` tag was added to a specific word and when shown in the website the color would change to a secondary color and the selected word would change its font size and layout as a whole. This can be useful with customization and to hide maybe unimportant text
  
*  The last thing I noticed was being able to change the text size and positioning. Although text size can regularly be changed manually by including a ``font-size`` css attribute within your code. **However**The use of the ``rem-calc()`` function can be used to position a text to your own liking and can be used to zoom in text which can be useful if implemented as an accessibility feature.

#### 2. The x and y grid within foundation framework 

_This concept has a lot of different types of grid systems which can be confusing to understand. So, I will only go over a few that stood out to me_

* What was very surprising to me was its similarities to other apps that I used to use. One app in particular that basically shared the same grid system was the app called bootstrap which is designed to help in making grid systems more intuitive,  easy to use while automatically implementing classes (and adding new ones) that make making websites more easier. Both apps shared the same grid system with a 12/12 grid system which is a lot more simpler in creating different grid patterns. However, foundation framework uses **x and y** classes that can be used to change the margin and padding of the grid system.

* Another thing that surprised me was how you could also implement margin and padding classes to the x and y grids created. For example by creating a grid margin-x will space out a column within its x axis by connecting both columns together and placing another column within them while padding-x will connect both columns together but will interact with each other instead of forming another column inside. This rule also applies to padding-y and margin-y classes instead it applies it to the y axis 
  
* A part that I really liked about this section was that you could also change the size of the columns and automatically change their column length. By using the ``.shrink`` class foundation will change its size to how much space it needs. You can also use the ``.auto`` class which will take up the remaining space needed and can be really helpful when wanting to take up the maximum space of columns. 

#### 3. Containers within foundation framework

_Containers within the foundation framework are actually pretty easy to use with the only problem being that js is required to toggle some elements.

* One thing that interested me was how different the accordion classes worked compared to regular website creation. The accordion classes were placed in ``<ul>`` and ``<li>`` tags which confused me at first but it actually is pretty useful especially when trying to organize your code
  
* There was also this newly implemented feature called **callout cards** which although seemed difficult to make, was actually a lot more simpler. How it works is that by adding a ``.callout``class within a ``div`` you can create a callout card and include elements within the ``div``. This easy customization allows for creation of multiple callout cards without it taking so much effort. 
  
* The card class also shares similarities with callout cards with the only difference being there are **multiple ``divs``** that need to be   used. One div including the ``.card`` class and a style class being able to customize the width of the card,  the other div being the ``.card-divider`` class which is used to include the header, and the last div being the ``.card-section`` class used to include the           description of the specific content made. 


### Research 

_Most of the research I had done was on the documentation. The following is the links  to the following framework documents:_

#### Typography 

* This document goes over the main parts that are included with text such as spacing, size of text, and the implementation of new elements and classes used to help in typography organization and positioning of text. 

(Here's the link to the document)[https://get.foundation/sites/docs/typography-base.html]

#### xy grid 

 * This document mainly goes over the newest addition within the foundation framework which is the xy grid. This grid is specifically designed     to allow for greater customization with changing graphing of specific elements within html and using x and y elements to change the         margin and padding of websites.

(Here's the link to the document)[https://get.foundation/sites/docs/xy-grid.html]

#### Containers 

* This document mainly goes over the use of different types of containers such as accordions, callout cards, etc... and are used to store text and information to keep websites organized and customizable to your choice. 

(Here's the link to the document)[https://get.foundation/sites/docs/accordion.html]
   
### Skills 

The skills I've been trying to develop now in this project are **creativity**, **growth mindset** and **how to learn** 

1. Creativity is the skill that I'm trying to develop right now. I definitely should take the time to tinker with everything within the website and try to use the ideas that I've learned from the foundation framework into a website that tests out all these concepts. When I have the time I should definitely try creating a website using all the concept ive learned from the foundation framework to gain a better understanding of how these concepts work.
   
2. Having a growth mindset is the skill that I'm trying to develop through this part of my freedom project. I'm definitely going to run into problems in the future with creating websites with foundation framework so getting the support from other people and trying some things will help in persevering through the challenges I faced
   
3. The last skill that I'm trying to develop right now is how to learn. Sometimes the foundation framework app may update which may require me to learn some new concepts and see any changes made on my own in order to catch up on any updates made. 

[Previous](entry03.md) | [Next](entry05.md)



[Home](../README.md)
