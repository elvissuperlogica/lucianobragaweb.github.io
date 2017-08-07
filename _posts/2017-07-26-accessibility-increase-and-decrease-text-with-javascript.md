---
layout: now/index
title:  "Teste!"
date:   2017-08-06 11:01:11 -0300
categories: jekyll update
---
# Accessibility— Increase and decrease text with JavaScript

It’s common see in sites those buttons of Accessibility for Increase or Decrease the font of texts, which facilitates the life of peoples with vision problems. let’s go see how it is done using JavaScript and JQuery.


## Using simple functions of JQuery Library

Before all let’s go need of JQuery library. This is a example of how create buttons of Accessibility for Increase and Decrease the size of text in elements of your site through Javascript language with help of JQuery Library what ever facilites the work for us developers.

## Buttons for Increase and Decrease the size of text

We started creating simple buttons with a onClick() function which will increase or decrease the font size. See how is simple.

```
<button onClick="fonte('a');">+</button>
<button onClick="fonte('d');">-</button>
```
## JavaScript function for change the font size

Let’s go now create the font.js file, that should contain the function which will make all the magic to happen on our site.

<script src="https://gist.github.com/lucianobragaweb/bf28ddd26b922e6d30e37ccbc62d9b5c.js"></script>

Now just add the class .acessibility to the elements that should be affected by the function.

```
<p class="acessibilidade">
     Example of text with .acessibility class.
</p>
```

## Download a example on GitHub.com
For more details check the repository in my GitHub what create with the finality of become simple and ease the implementation of this and other functions of accessibility: https://github.com/lucianobragaweb/acessibilidade

Thanks for read, and sorry my english.
