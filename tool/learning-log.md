# Tool Learning Log

## Tool: **Foundation framework**

---

## learning log 1

### 3/16/26:
* Read over the documentation for [base typography](http://get.foundation/sites/docs/typography-base.html) within foundation framework
    * I was able to learn most of the fundamentals such as paragraph tags, headers which all were the same compared to normal design making. But what stood out to me was how there was a settings file that was implemented that made it so that you could change specific text, headings, font-family etc...
    * I also tried testing out the base typography and organization within a website(the link unfortunately does not work because it was done in my IDE)
    * I wonder, how could javascript be used for typography? how would the code actually look like?

### 3/20/26:

* looked into the controls documentation into the [button lesson](https://get.foundation/sites/docs/button.html)
    * Decided to watch a video on the topic within the documentation.
        * Buttons in foundation framework seemed to have worked in different ways.
            1. using anchor tags to link buttons to different sites
            2. using the ``<button>`` tag to perform an action within the page(NOTE: javascript is required in order to work)
        * You can also implement different coloring styles to the buttons created which can be in multiple types
            1. the ``button primary`` class will keep the button at its primary color/blue EX:
            2. the `` button secondary`` class will keep the button as a secondary color/black
            3. the `` button success`` class will set the button to green
            4. the `` button alert`` class will set the button to red
            5. the `` button warning`` class will set the button to yellow
        * you can also change the sizings and implement disabled or hollow buttons
            1. For sizings you can implement specific classes to change the size of a button. There are ``tiny`` ``small`` ``large`` ``expanded`` and ``small expanded`` classes that can make buttons really big or really long/expanded
            2. For hollow buttons you can change the transparency of the box by just adding the ``hollow`` class
            3. For disabled buttons you just need to type ``disabled`` outside of the quotations and in front of the ``href="#"`` to disable clicking.
        * the last important pieces of information were **clear styles** and **dropdown arrows**.
            1. Clear styles are used to add a clear button type to your website. All you need to do is include a ``clear`` class.
            2. Dropdown arrows are used to keep information organized. All you need to include is a ``dropdown`` class.

        * A question I have is how could the dropdown class be used in an actual website because it seems useful but its diffucult to find a way for its use.

        * my next steps would be to try implementing these concepts into jsbin to have a better understanding of these button classes and how to use them.

## learning log 2

### 3/23/26

* Looked into the **media documentation** for the [badge lesson](https://get.foundation/sites/docs/badge.html)
    * looked into the basics section of the badge lesson.
        * Badges looked really simple to use because it only required the use of ``<span>`` tags and the creation of a class namned ``.badge``.
        * Heres a code snippet to how it looks like:
          ``<span class="badge">1</span>``
        * you can also bind two elements together with the ``.badge`` class by implementing a unique id to both the badge and the other element to bind the two elements together.
        * **Colors** can also be added to badges
            * All you need to do is similarly to that of the button icons which is providing different classes that will change the color of the icons(primary, seconary, success etc...)
        * Icons can also be implemented with badges
            * all thats needed is to include a seperate class nested in a ``<i>`` tag and include one of the three classes implemented into your code
                EX:
                * ``"fi-share"`` will create a share icon automatically
                * ``"fi-check"`` will create a checkmark
                * ``"fi-wrench"`` will create a wrench icon.
    * What im going to try now is to create an example website using jsbin and try to look in more to the media section when I have the time tomorrow.

### 3/24/26
* looked into the **sass documentation** for the [formating lesson](https://get.foundation/sites/docs/sass-functions.html)
    * Sass functions as a type of css specifically used to alter/change colors, units, selectors etc...
        * A nice feature of foundation framework is that sass is automatically implemented through a specific folder placement in ``scss/util``
            * To import different colors and other parts you just need to include ``@import`` and include the utility you want to alter
                EX:
                ``@import `util/util`;``
            * to include different colors so that it goes to your actual website you just need to include ``@include`` which will create the output of the change made to your website. This is also called a **Mixin**
                here are some examples:
                ``@include flex;`` --> will include the ``display: flex`` to a given element.
                ``@include flex-align($x, $y);`` --> adds horizontal and verticle alignment within a flex container
                    * this rule still applies for colors and measurement with the only difference is the given parameter is inside a parentheses and a function implemented by foundation framework will be used basically acting as a boolean line of code.
                        EX:
                        color-contrast($color1, $color2) --> will check contrast between different colors

    * A question that I have is how can the implementation of sass/scss change the color and measurement implementation to css and html?

    * If I had more time, I shouldve tried this in js bin to get a better understanding of this concept because this is really new to me.

### 3/27/26

* looked into the **navigation section** in foundation framework
    * I first looked into the menu lesson to see how it works
        * menus in foundation framework funtion alot better then regular html with the only downside is that multiple ``<li>`` tags are needed which can make the process very tedious
            1. to do this create a ``<ul>`` tag with the given class of ``menu``
            2. then create a ``<li>`` tag that nests a ``<a>`` tag
            3. finally, include a href that will link to any sections of your website and youve done it!
        * There are also different forms of alignment that can change how the given nav bars are aligned
            1. placing ``align-center`` in the ``menu`` class will align all items in the navbar at the center
            2. placing ``align-right`` in the ``menu`` class will align all items in the navber to the right
            3. placing ``align-left`` in the ``menu`` class will align all items in the navbar to the left
            4. placing ``simple`` in the ``menu`` class will align all items in their regular state
            (theres alot more styles that can be implemented [check here to learn more](https://get.foundation/sites/docs/menu.html))

* unfortunately many of the other lessons within the **navigation section** often required javascript but the rest were mainly available
    * I then decided to head to the [top bar](https://get.foundation/sites/docs/top-bar.html) lesson
        * top bars function as containers that are apart of the navigation bar. Its specifically used as more of a design feature that surrounds the navbar with a background color and can include more content such as search bars, icons,  etc...
            1. to first create the top bar create a ``<div>`` tag with the class of ``top-bar`` which will set the foundation for the implementation of other sections of the navbar
            2. Then, you can create a ``top-bar-left`` inside of a ``<div>`` which can be used to surround specific elements within the navigation bar(menus,anchor tags, alignment etc...) and place them on the left side of the navbar
            3. finally, with the inclusion of a ``top-bar-right`` inside of another ``<div>`` you can organize elements in the navbar within the right of the navbar
            EX:

            ```
            <div class="top-bar">
                <div class="top-bar-left">
                    <ul class="dropdown menu" data-dropdown-menu>
                        <li class="menu-text">Site Title</li>
                        <li>
                          <a href="#">One</a>
                          <ul class="menu vertical">
                            <li><a href="#">One</a></li>
                            <li><a href="#">Two</a></li>
                            <li><a href="#">Three</a></li>
                        </ul>
                    </li>
                    <li><a href="#">Two</a></li>
                    <li><a href="#">Three</a></li>
                    </ul>
                </div>
                <div class="top-bar-right">
                <ul class="menu">
                    <li><input type="search" placeholder="Search"></li> --> these lines of code are meant to show how to create a searchbar
                    <li><button type="button" class="button">Search</button></li> --> these lines of code are meant to show how to create a searchbar
                </ul>
                </div>
            </div>
            ```
            (it may seem intimidating because of the countless amounts of divs and ul tags however the organization can make it easier)

        * A question that I have is why is javascript required in almost all navigation components?

        * Next time, if I have the time then I should try and create a jsbin example and try to finish up the navigation section if possible

## learning log 3

### 4/9/26

* I then decided to read the documentation on utilities and read over the [flexbox-utilities](https://get.foundation/sites/docs/flexbox-utilities.html) lesson
    * flexbox utilities function similarly to bootstrap acting as a way to sort elements in rows by using ``cell`` classes instead of ``col`` classes.
        * these ``cell`` classes are used to create different sections of a container that can split into different parts.
            * you can customize these cells by including the breakpoint/what size will create the seperate gutters EX: small medium large etc... and by including numbers from 4-12 depending on how many cells there are.
    * there are also different forms of alginment which can consist of **horizontal-alignment,** **vertical-alignment,** and **central-alignment**
        * NOTE: its very important that you include a seperate div with the inclusion of the classes ``grid-x`` and ``padding-x`` to allow for horizontal placement of elements.
            * I then decided to test out these components in [jsbin](https://jsbin.com/?html,output)
                * a question I have about these componenets is that why are the classes grid-x and padding-x included? What is their purpose and why is it so important? 






