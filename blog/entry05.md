# Entry 5: finished learning about foundation framework
##### 4/20/26

### Context
I am currently a student at SEP10 which is meant to give students knowledge on the fundamentals of computer science which currently consists of html, css, and more. This entry will be about how I fully learned how to use my coding tool for my upcoming creation of the freedom project website, what examples I had, and the most important concepts that could be used with my coding tool and how they function overall.


### Content
The most important skills that were most important out of foundation framework were  **menus**,
**motion-ui**, **flexbox-utilities**, **typography**, and **media components**.


1. the **motion-ui** components were the most interesting out of all the other skills that I've learned because of how easy it is to use even though its a really complex concept and how many changes you can make. The motion-ui in regular html would require to create multiple classes in order for elements to be animated. However, all these classes are built into the foundation framework which can prove very useful when trying to customize image animations. **To do this,** you first need to include a **CDN** link that will generate all custom classes created by foundation framework and then you will have access to motion-ui components, which in return can make the use of the motion-ui much more easier.


Here's what the CDN link looks like:


```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/motion-ui@1.2.3/dist/motion-ui.min.css"/>
```
motion-ui works as a sort of custom animation that will change how an image/element is shown within a website. Images that use motion-ui can either **rotate a certain angle,** **fade in or fade out,** and **slide in**. _NOTE: you must include a sass function in your sass file to get built in transitions to work EX: ``@include motion-ui-transitions;``_


2.**flexbox-utilities** serve the purpose of being made to keep elements organized and equally sectioned. Its similar to that of bootstrap where you can include ``container`` and ``col`` classes with the only difference being that there replaced with ``margin-x`` or ``padding-x`` for div classes and ``col`` classes change into ``cell`` classes.
here's an example of how it would work:


```html
<div class="grid-x grid-padding-x">
 <div class="cell small-4">Cell 1</div>
 <div class="cell small-4">Cell 2</div>
 <div class="cell small-4">Cell 3</div>
</div>
```


In this following example, the usual ``container`` class that is usually used is replaced with a ``grid-x`` and ``grid-padding-x`` which are both used to keep all elements inside of a container. The ``cell`` classes are meant to hold content inside of the container(text, divs, etc...). Lastly, the ``small-4`` classes are meant to change the width of a cell with the number 4 giving the cell a width of 4 out of 12 on screens smaller or more.


3. **typography** is the main function of html. It is used to help in creating text, bulleted lists(``<li>``), numbered list(``<ol>``), headings(``<h1>``, ``<h2>``) etc... All these elements play a role in how text is structured within a website. However, the foundation framework adds more to this concept and can allow you to automatically change sizes and implementation of typography. A new element that was created in foundation framework is definition lists which can be used to include definitions which is shown in the form of ``<dt>``, ``<dd>`` being definition info and ``<d1>`` being used to show the display names of the definitions. Two other important new usages of typography with foundation framework are ``<blockquote>``tags which are used to cite or mention specific phrases from important people, and ``.code-block`` classes that change the text inside to code blocks.


4. **Menus** Although they are optional in creating a website, they still serve a good purpose of giving the user easier guidance of information in a website and can make websites more organized overall. Menus can often consist of navbars, links, searchbars icons etc... that can make a website overall more polished. **Navbars** are used to keep links, searchbars and icons in one place without all content being so mixed up.


To create a simple navbar/menu, first create a div with the inclusion of the classes ``top-bar`` and ``stacked-for-medium`` or ``stacked-for-large`` which will stack content together on a screen which can be small or large depending on the class used. Then to include links create a ``<ul>`` class called ``menu`` which will automatically orient content together. Then create an ``<li>`` tag and an anchor tag ``<a>`` inside of an ``href`` element. Finally, repeat this process up to 3-4 times(depending on how your website is structured) and the menu/navbar will work. Here's what the code could look like:


```html
<div class="top-bar stacked-for-medium">
     <ul class="menu">
       <li><a href="#">link one</a></li>
       <li><a href="#">link two</a></li>
       <li><a href="#">link three</a></li>
       <li><a href="#">link four</a></li>
     </ul>
   </div>
```


5. **Buttons**are not such a key factor in building websites but it can help in building forms and also can be used to send the user to different parts of the website or a separate link. buttons can be customized to the users liking through the changing of colors, sizings, and its transparency. To create a button first create a ``<button>`` tag that will set up the button Then include a ``type="button"`` to create a functional button. **however** if the button is used to submit a form then use the ``.submit`` class that will allow for the submitting of a form. Lastly, for including links use an ``<a>`` tag inside of a ``href=""`` to set up the link and include a ``button`` class to link the anchor tag to its specific button and the process should be done.


### Sources


#### motion-ui source:
* (motion-ui document)[https://get.foundation/sites/docs/motion-ui.html]


#### flexbox-utilities source:
* (flexbox-utilities document)[https://get.foundation/sites/docs/flexbox-utilities.html]


#### typography source:
* (typography document)[https://get.foundation/sites/docs/typography-base.html]


#### menus source:
* (menus document)[https://get.foundation/sites/docs/menu.html]


#### buttons source:
* (buttons document)[https://get.foundation/sites/docs/button.html]


### Skills
The skills that I've learned from learning my tool was the importance of **problem decomposition** **debugging** and **how to learn**


* **problem decomposition** was something that I used to struggle with sectioning work into different parts and sections which would make my workflow more slower and organization more messier. However learning foundation framework required me to be able to create schedules/plans that would help me in what steps and research I needed to make on specific days which would help in making learning progress more fluid and easier
* being able to **debug** was very important in learning the foundation framework. I would often run into written errors because I readed a section of the document incorrectly or I was confused on a topic. However, when I would check back on the documentation, I was able to fix some grammar errors within my learning log and I added more information to make specific sections more detailed and polished than before.
* the most important skill that I had to learn was **how to learn** on my own. Sometimes there may be some changes made by the foundation framework and learning on my own on those concepts is sometimes going to be needed in order to gain a better understanding of my tool.


[Previous](entry04.md) | [Next](entry06.md)


[Home](../README.md)
