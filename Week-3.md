Week 3 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

1. What was your impression of the mob programmimg day? Did you notice any pros or cons of this strategy?
Mob programming was good in that there were a lot of minds working together through different problems and suggesting different ideas. So some of the pros were that there were many more minds to be able to fill in the gaps of other people's understanding. Some of the cons were that because there were so many people in the group working on the same problems it could be hard to come to a consensus on which direction to take. Also the more vocal or dominant people were more likely to be influencing the way the program was being written. Another con would be that because there were a lot of people and ideas, there was little time to take a step back and think about the problem and more plugging different options in.

2. What is jQuery and what are the two ways you can add it to your project?

[Your Answer]
jQuery is a way to connect the html of a webpage with javascript to make the page more interactive. You can use jQuery to make something run when you click on something on the webpage.
you can use:
$(this).on("click",function())

You can also use jQuery to add a class to elements.
$(this).addClass("hit");

[Googled Answer]
jQuery is a javascript library that makes it easier to use javascript on your webpage.
jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code.

jQuery also simplifies a lot of the complicated things from JavaScript, like AJAX calls and DOM manipulation.

The jQuery library contains the following features:

HTML/DOM manipulation
CSS manipulation
HTML event methods
Effects and animations
AJAX
Utilities

3. Write an example of the jQuery function used to make sure the webpage has loaded before trying to load any Javascript.
$(document).ready(function()) makes sure that the webpage has loaded first before it tries loading javascript.

4. In a project, what piece do the HTML and CSS form (think MVC roles)? Explain a little bit about this piece or "layer".

//Your Answer
The HTMl and CSS make up the "view" in that they make up most of what the user will see on the webpage. This is the content and the framework of the page, the colors and the design.

//Googled Answer
A view is a (visual) representation of its model. It would ordinarily highlight certain attributes of the model and suppress others. It is thus acting as a presentation filter.

A view is attached to its model (or model part) and gets the data necessary for the presentation from the model by asking questions. It may also update the model by sending appropriate messages. All these questions and messages have to be in the terminology of the model, the view will therefore have to know the semantics of the attributes of the model it represents.

The HTML is the "skeleton" of bedrock content. Text that communicates information to the reader.

The CSS adds visual style to the content. It is the "skin" that we use to flesh out our skeleton and give it a particular look. We can swap in different skins via CSS without altering the original content in any way. They are relatively, but not completely, independent.

5. We learned that JQuery is a javascript library. What do you think a library is? Is it different than a framework? Do 5-10 min of googling to find these answers.

A library is a JavaScript file that contains a bunch of functions, and those functions accomplish some useful task for your webpage.
Some JavaScript libraries allow for easier integration of JavaScript with other web development technologies, such as CSS, PHP, Ruby, and Java. Many libraries include code to detect differences between runtime environments, and remove the need for applications to allow for such inconsistencies.
The key difference between a library and a framework is “Inversion of Control”. When you call a method from a library, you are in control. But with a framework, the control is inverted: the framework calls you

6. What are wireframes? Explain when and why you might use them.

//Your Answer
Wireframes are outlines and plans for the building of a website. You can use wireframes to organize plans for a website.

//Googled Answer
Wireframing is an important step in any screen design process. It primarily allows you to define the information hierarchy of your design, making it easier for you to plan the layout according to how you want your user to process the information

7. What do we call the code layer that makes it possible for the user to interact with the application?

//Your Answer
The controller makes it possible for the user to interact with the application, and example of that would be the jquery that allows the user to interact with the webpage.

//Googled Answer
A controller is the link between a user and the system. It provides the user with input by arranging for relevant views to present themselves in appropriate places on the screen. It provides means for user output by presenting the user with menus or other means of giving commands and data. The controller receives such user output, translates it into the appropriate messages and pass these messages on to one or more of the views.

8. Write two valid JQuery commands that use any two of these: .click(), .append(), .prepend(), .hide(), .show(), .toggle(), .remove()

Might look similar to this example:

$(document).ready(function(){
  $( "p" ).parent( ".highlighted" ).css( "background", "red" );
});

$(document).ready(function(){
  $("div").on("click",function(){
    alert "You have clicked on a thing!"
  });
  $(".container").append($(h2));
});


9. What do we call the code layer responsible for handling and storing the data and logic?

//Your Answer
The "model" is the code layer responsible for handling and storing the data and the logic.

//Googled Answer
The model classes are used to store and manipulate state, typically in a database of some kind.

10. How can you traverse up and down the DOM? Give an example of two commands.

//Your Answer
You can traverse up and down the DOM using the relationship between items. filter() allows you to find specifc things that match criteria that you specify for filter. Parent() will return the direct parent element for something.

//Googled Answer
DOM tree traversal may be accomplished through the use of six basic properties. All properties, except childNodes, contain a reference to another node object. The childNodes property contains a reference to an array of nodes.
### Rails Course Assessment

## Week 3 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What was your impression of the mob programmimg day? Did you notice any pros or cons of this strategy?


#### 2. What is jQuery and what are the two ways you can add it to your project?


[Your Answer]


[Googled Answer]


#### 3. Write an example of the jQuery function used to make sure the webpage has loaded before trying to load any Javascript.


#### 4. In a project, what piece do the HTML and CSS form (think MVC roles)? Explain a little bit about this piece or "layer".

//Your Answer

//Googled Answer


#### 5. We learned that JQuery is a javascript library. What do you think a library is? Is it different than a framework? Do 5-10 min of googling to find these anwers.


#### 6. What are wireframes? Explain when and why you might use them.

//Your Answer

//Googled Answer


#### 7. What do we call the code layer that makes it possible for the user to interact with the application?

//Your Answer

//Googled Answer


#### 8. Write two valid JQuery commands that use any two of these: .click(), .append(), .prepend(), .hide(), .show(), .toggle(), .remove()
Might look similar to this example:

```js
$(document).ready(function(){
  $( "p" ).parent( ".highlighted" ).css( "background", "red" );
});

```

#### 9. What do we call the code layer responsible for handling and storing the data and logic?

//Your Answer

//Googled Answer


#### 10. How can you traverse up and down the DOM? Give an example of two commands.

//Your Answer

//Googled Answer
