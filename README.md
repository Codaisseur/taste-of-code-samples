![Taste of Code](http://cd.sseu.re/2016_01_15_23_30_42_etxia.jpg)

Welcome the first ever Taste of Code.
===================================

- hosted and sponsored by TomTom
- introduction to codaisseur. train developers and teach skill for people to apply in their job + why we do this
- Uitleggen dat we van alles maar een 'taste geven' en alleen uitleggen wat we doen.
- The whole day will be a interactive excercise where we show you a bit of theory and after that immidiately let you apply this theory. If things go too fast, please slow me down by asking questions.
- Our starters will be HTML and CSS. They will prepare you for the main course, Javascript!
- All presentations and exercises will be in English but most teachers and coaches speak Dutch aswell.
- If you have question. first ask the person to your right or left. if you cannot figure it out together you can always ask one of the coaches
- Can everyone get out their laptops if you haven't already and join our SLACK. Slack will be the main means of sharing links and stuff today


HTML
===================================

We will start off with HTML. HTML is the language of the web. Any website you ever vistited was made with html. HTML started off as a pure text based document format. With each new version of HTML, it was adapted to the new requirements of the web.

What does a html document look like?
```html

<!DOCTYPE html>
<html>
<head></head>
<body></body>
</html>

```
You can see the hierarchy clearly in this example. This document format is called XML. HTML is a sub-format of XML.

HTML is made of tags and text
TERM: `TAG`
what is a tag. Always close tags

Tags have a certain style by default. Look at paragraph and Header for example.

Exercise 01
---
> Everyone open up your laptops and lets write the base of the html document we will be using today.

> Write small HTML document with H1 and P

There are many other tags available but today we will mostly use the DIV (Document division).

CSS
===================================

It is nice that text has a certain style by default. but sometimes you want something more. For example you want to give a color to the text.

The way we will show you how CSS works is with a inline STYLE tag. There are other ways but we will not discuss those today.

So for example you want the background of your page to be green!
To do this you need to write a CSS selector. You can select a tag by its name. in this example that will be `<body>`.

Let us all do this together. We make a css selector for body and add the green property to it.


Let us select the HTML TAG
And now we change the setting for background color to green

Exercise 02
---
> Use selector to change the color of the html page to green and the text color to white

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

Exercise 03
---
> Lets apply the warning class to the h1

There are many more things we can change.

Exercise 03
---
> border & radius

Now let us make a balloon!
A balloon will exist of a container tag, a bubble and a string

-To make a balloon we will use the DIV tag. With CSS we can make a balloon. Let us start with the bubble. It has to be round, and has a color. We can do this by setting a width and height and setting a background color and radius.

You can pick any color for your balloon. The easiest way to do this is by its english name. (You can also pick a color with a value. !explain hexidecimal?!)

Exercise 04
---
> circle and color

> make it oval

Now lets add a line for the balloon.

Exercise 04
---
> balloon string

Are there any questions?

Now it is time for lunch.


Javascript
===================================

We will now get to the main course of our taste of code.

So lets get to code. We will teach you what code is by javascript.
What is javascript? Is a programming language that runs in the browser. It is run as plain text.

Let us start with doing something simple in javascript!
Everyone open the developer console in Chrome `View > Developer > Javascript console`

Exercise
---
> Run something easy in the Chrome development console like 1 + 1

Simple calculations are not really what programming is about but it is a nice introduction to the console.

What programming is all about is variables, functions, conditions, loops, methods and objects.

You have to understand, if you use a programming language, you are telling the machine or program what to do.

In this case we are going to tell the browser what it should do. But in other cases it could be your computer, phone or refrigerator.

This is called declarative programming.

So let's have to browser do something

Exercise
---
> close the window with window.close();

What we did here is we used the window `object` and called the close `method` on it.

---
> TODO explain object and method a bit.

---

Now let us use javascript to copy the balloon.

We can do this with normal javascript, but javascript is a old language and not so nice.

So we choose to use jQuery for this. jQuery is specifically created to make it easy to work with HTML and javascript.

---
> TODO explain a bit more what jquery is and what librarians are

---

Let us add Jquery to the page and test if it works.

Exercise 05
---
> Add jquery to the page and test if `$` gives something back.

With jquery we can easily select our balloon and duplicate it.

Exercise 06
---
> Select the balloon and call `clone()` on it.

Selecting is nice, but sometimes you want to use it at a later time. To do this you can work with a variable. A variable is a combination of a name and a value


Exercise 07
---
>  Show you can also use variable for the `window` object and the `window.close()` function and for the result of `1 + 1`

>  Make a variable called balloon

> Copy the balloon and add it to the document


We can also do this multiple times. This is called a loop. A loop looks like this:

```javascript
for(var i=0; i<10; i++){
}
```

Everything that is inside the brackets with run 10 times.

A loop can have different shapes but this is its most common one.
The keyword for is used to note the start of the loop. Then a counter is created that is increased every time the loop runs. and every time it is run there is a check to see if it should stop already.


Exercise 08
---
> Duplicate the balloon in a loop

One of the nice things about javascript is that you can react to certain events in the browser. These events will generally come from something the user does.

We can for example tell the browser to do something when a balloon is clicked

Exercise 09
---
> Add click event to balloon

> Make the balloon disappear

Right now all the balloons are drawn from top to bottom. This is not so nice. So let us do some advanced positioning

Right now our document is in the standard layout mode. But we can tell the browser we want to position our elements ourselves.

We can do this by adding the `position: absolute` property to our balloon

Exercise 10
---
> Add css for position absolute

> Change position in the loop to draw all balloons on a line

Off course to make it a game we need to keep the score. Let's make a counter to keep score of all balloons that were clicked

Exercise 11
---

>  Show a counter for each disappeared balloon


Welcome to the end of our Javascript afternoon program. We have some additional exercises lined up for you


Dessert
===================================

Extra Repetition

> Style the counter with CSS

> Make the loop run 15 times instead of 10

> Use something else instead of balloons



Extra Enhancement

> Change the color of a balloon

> Change the color of all balloons

> Add animation

> Show counter in the center of the screen after all balloons are offscreen

> Add Sound

> Advanced animation


Extra general

> Put it online at bitballoon
