# Entry 5: finished learning about foundation framework
##### 4/20/26

### context
I am currently a student at SEP10 which is meant to give students knowledge on the fundamentals of computure science which currently consists of html, css, and more. This entry will be about how I fully learned how to use my coding tool for my upcoming creation of the freedom project website, what examples I had, and the most important concepts that could be used with my coding tool and how they function overall.

### content
The most important skills that were most important out of foundation framework were  **menus**,
**motion-ui**, **flexbox-utilities**, **typography**, and **media componenents**.

1. the **motion-ui** components were the most interesting out of all the other skills that Ive learned because of how easy it is to use even though its a really complex concept and how many changes you can make. The motion-ui in regular html would require to create multiple classes in order for elements to be animated. However, all these classes are built into foundation framework which can prove very useful when trying to customize image animations. **To do this,** you first need to include a **CDN** link that will generate all custom classes created by foundation framework and then you will have acsess to motion-ui components, which in return can make the use of the motion-ui much more easier.

Heres what the CDN link looks like:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/motion-ui@1.2.3/dist/motion-ui.min.css"/>
```
motion-ui works as a sort of custom animation that will change how an image/element is shown within a website. Images that use motion-ui can either **rotate a certain angle,** **fade in or fade out,** and **slide in**. _NOTE: you must include a sass function in your sass file to get built in transitions to work EX: ``@include motion-ui-transitions;``_

2.**flexbox-utilities** serve the purpose of being made to keep elements organized and equally sectioned. Its similar to that of bootstrap where you can include ``container`` and ``col`` classes with the only difference being that there replaced with ``margin-x`` or ``padding-x`` for div classes and ``col`` classes change into ``cell`` classes.
heres an example of how it would work:

```html
<div class="grid-x grid-padding-x">
  <div class="cell small-4">Cell 1</div>
  <div class="cell small-4">Cell 2</div>
  <div class="cell small-4">Cell 3</div>
</div>
```

In this following example, the usual ``container`` class that is usually used is replaced with a ``grid-x`` and ``grid-padding-x`` which are both used to keep all elements inside of a container. The ``cell`` classes are meant to hold content inside of the container(text, divs, etc...). Lastly, the ``small-4`` classes are meant to change the width of a cell with the number 4 giving the cell a width of 4 out of 12 on screens smaller or more.

3. **typography** is the main function of html. It is used to help in creating text, bulleted lists(``<li>``), numbered list(``<ol>``), headings(``<h1>``, ``<h2>``) etc... all these elements play a role in how text is structured within a website. However, foundation framwork adds more to this concept and can allow you to automatically change sizes and impelementation of typography. A new element that was created in foundation framework is definition lists whcih can be used to include definitions which is shown in the form of ``<dt>``, ``<dd>`` being defininiation info and ``<d1>`` being used to show the display names of the definitions. Two other important new usages of typography with foundation framwork are ``<blockquote>``tags which are used to cite or mention specific phrases from important people, and ``.code-block`` classes that change the text inside to code blocks.

4. **Menus** although are optional in creating a website still serve a good purpose of giving the user easier guidance of information in a website and can make websites more organized overall. Menus can often consist of navbars, links, seachbars icons etc... that can make a website overall more polished. **Navbars** are used to keep links, searchbars and icons in one place without all content being so mixed up.

To create a simple navbar/menu, first create a div with the inclusion of the classes ``top-bar`` and ``stacked-for-medium`` or ``stacked-for-large`` which will stack content together on a screen which can be small or large depending on the class used. Then to include links create a ``<ul>`` class called ``menu`` which will automatically orient content together. Then create an ``<li>`` tag and an anchor tag ``<a>`` inside of an ``href`` element. Finally, repeat this process up to 3-4 times(depends on how your website is structured) and the menu/navbar will work. Heres what the code could look like:

```html
<div class="top-bar stacked-for-medium">
      <ul class="menu">
        <li><a href="#">One</a></li>
        <li><a href="#">Two</a></li>
        <li><a href="#">Three</a></li>
        <li><a href="#">Four</a></li>
      </ul>
    </div>
```

5. **Buttons**, arent such as key factor in building websites but it can help in building forms and also can be used to send the user to different parts of the website or a seperate link. buttons can be customized to the users liking through the changing of colors, sizings, and its transparency. To create a button first create a ``<button>`` tag that will set up the botton Then include a ``type="button"`` to create a functional button. **however** if the button is used to submit a form then use the ``.submit`` class that will allow for the submiting of a form. Lastly, for including links use an ``<a>`` tag inside of a ``href=""`` to set up the link and include a ``button`` class to link the anchor tag to its specific button and the process should be done. 

### Sources

### Skills

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
