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

* Looked into the media documentation for the [badge lesson](https://get.foundation/sites/docs/badge.html)
    * looked into the basics section of the badge lesson.
        * Badges looked really simple to use because it only required the use of ``<span>`` tags and the creation of a class namned ``.badge``.
        * Heres a code snippet to how it looks like:
          ``<span class="badge">1</span>``
        * you can also bind two elements together with the ``.badge`` class by implementing a unique id to both the badge and the other element to bind the two elements together.
        * **Colors** can also be added to badges
            * All you need to do is similarly to that of the button icons which is providing different classes that will change the color of the icons(primary, seconary, success etc...)
        * Icons can also be implemented with badges 
---
<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
