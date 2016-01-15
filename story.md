
- Please open up your laptop because today will all about learning to code. You learn code by doing it. for 10,000 hours atleast. Today will be a interactive day with mixed excersises and theory.
- what will today be all about
- hosted and sponsored by TomTom
-
- introduction to codaisseur. train developers and teach skill for people to apply in their job
- Uitleggen dat we van alles maar een 'taste geven' en alleen uitleggen wat we doen.


Welcome the first ever Tast of Code.
===================================

----
The whole day will be a interactive excercise where we show you a bit of theory and after that immidiately let you apply this theory. If things go too fast, please slow me down by asking questions.
Our starters will be HTML and CSS. They will prepare you for the main course, Javascript!
----

----
All presentations and exercises will be in English but most teachers and coaches speak Dutch aswell.
----

----
If you have question. first ask the person to your right or left. if you cannot figure it out together you can always ask one of the coaches
----

----
Can everyone get out their laptops if you haven't already and join our SLACK. Slack will be the main means of sharing links and stuff today
----



HTML
===================================

We will start off with HTML. HTML is the language of the web. Any website you ever vistited was made with html. HTML started off as a pure text based document format. With each new version of HTML, it was adapted to the new requirements of the web.

What does a html document look like?
<html>
<head></head>
<body></body>
</html>

You can see the hirarchy clearly in this example. This document format is called XML. HTML is a subformat of XML.

HTML is made of tags and text
TERM: TAG
what is a tag. Always close tags

Tags have a certain style by default. Look at paragraph and Header for example.
Infact everyone open up your laptops and lets write the base of the html document we will be using today.

- Write small HTML document with H1 and P

There are many other tags available but today we will mostly use the DIV (Document division).

CSS
===================================

It is nice that text has a certain style by default. but sometimes you want something more. For example you want to give a color to the text.

The way we will show you how CSS works is with a inline STYLE tag. There are other ways but we will not discuss those today.

So for example you want the background of your page to be green!
To do this you need to write a CSS selector. You can select a tag by its name. in this example that will be BODY.

Let us all do this together. We make a css selector for body and add the green property to it.


Let us select the HTML TAG
And now we change the setting for background color to green

> Use selector to change the color of the html page

How would we select the Header(`<h1>`)? We will do this by creating a css class. A css class can contain certain properties that can be applied to multiple elements.

Lets assume we want to be able to display a warning text. A warning text is underlined and is red.

To apply the warning text to our existing document we need to write it inline. This is done inside a `<style>` tag. A css class looks like this: `.class{}` and properties always look like this: `property: value;`

If we make a warning class it would look like this:

```css

.warning{
	color: red;
	text-decoration: underline;
}
```

If you want to apply a certain CSS class to a html tag, you have to assign it in the tag like `class='warning'`.

- Lets apply the warning class to the h1

There are many more things we can change.

- Show border, radius

Now let us make a balloon!
A balloon will exist of a container tag, a bubble and a string

-To make a balloon we will use the DIV tag. With clever CSS we can make a balloon. Let us start with the bubble. It has to be round, and has a color. We can do this by setting a width and height and setting a background color and radius.

You can pick any color for your balloon. The easiest way to do this is by its english name. (You can also pick a color with a value. !explain hexidecimal?!)

Now lets add a line for the balloon.

- DONE with balloon

Are there any questions?

Now it is time for lunch.


Javascript
===================================

We will now get to the main course. The taste of code. As you maybe already feel, you need a lot of skills to do something with code. In itself it is not so usefull. That is why we started with HTML and CSS.

So lets get to code. We will teach you what code is by javascript.
What is javascript? Is a programming language that runs in the browser. It is run as plain text.

Let us start with doing something simple in javascript!

- Run something easy in the Chrome development console like 1 + 1

Simple calculations are not really what programming is about but it is a nice introduction to the console.

What programming is all about is methods and variables. You have to understand, if you use a programming language, you are telling the host what to do. In this case it is the browser but in other cases it could be your computer, phone or refrigirator. This is always important to keep in mind.

So let's have to browser do something

- close the window with window.close();

What we want to do is copy the balloon. To do this we can select it, just like with CSS.

We can do this with normal javascript, but javascript is a old language and not so nice. So we choose to use jQuery for this. jQuery is specifically created to make it easy to work with HTML and javascript.

Let us add Jquery to the page and test if it works.

- Add jquery to the page and test if $ gives something back.

With jquery we can easily select our balloon and duplicate it.

- Select the balloon and call clone on it.

Selecting is nice, but somethimes you want to use it at a later time. To do this you can work with a variable. A varriable is a combination of a name and a value
TERM: VAR, ;, Assignment

- Make a variable called balloon
- Show you can also use variable for the window object and the window.close() function

- Copy the balloon and add it to the document
TODO: TERM function, method, object

We can also do this multiple times. This is called a loop. A loop looks like this:

```javascript
for(var i=0; i<10; i++){
}
```

TERM loop
>> explain a bit about logic and true and false (i<10 , i!==10, )

TERM: logic
Everything that is inside the brackets with run 10 times.

- Duplicate the balloon in a loop

------------------------------------------------------------HAPPY IF WE GET THIS FAR



- Add a click event in the loop to make the balloon dissapear
- position the balloon somewhere on the screen => TODO: Tell about position absolute and top, left positioning first.
- Show a counter for each dissapeared balloon





----
Now for the desert we have several additional exerisices

- Animation
- Style the shit out of the counter
- Make the same but with images (of balloons or anything)
- Make sure baloons arent spawned off screen
- API for scorekeeping (AJAX)?
- Put it online
