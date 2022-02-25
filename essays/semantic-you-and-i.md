---
layout: essay
type: essay
title: Semantic (Yo)U and I
# All dates must be YYYY-MM-DD format!
date: 2022-02-24
labels:
  - Semantic UI
  - UI Frameworks
  - Learning
---
When I first learned HTML and CSS, it became extremely easy to design websites. 

Well, to be exact, it became extremely easy to design horrendous-looking websites. 

<img class="ui medium right rounded floated image" src="../images/graphic_design.jpg">
I used to think that writing raw HTML and CSS from scratch was the only way to design a website. I'll spare you the neon eyesore (Middle school Carol knew nothing about graphic design), but my few dips into website design led me to believe that making a website look nice was annoying and time-consuming. For example, having a margin on the far left and right of elements makes a website seem less cluttered. However, actually implementing this means adding a left or right padding to every single element, which isn't difficult, just time-consuming. And don't even get me started on different screen sizes. The moment my websites were viewed on a computer with a significantly larger or smaller screen size, or, heaven forbid, a *phone,* my websites just gave up the ghost and produced some awful concoction where text and images clipped into each other and ran off the screen.

Usability and readability is one of the most important aspects of web design. Even if you have a lot of amazing content on your site, with improper UI, it can be a slog to get through and can greatly reduce the number of people who are willing to read through it all.

Luckily, Semantic UI and other frameworks do a lot of the background work for you, and simplifies a lot of the code that you have to write when designing your websites. For example:

```HTML
<div class = "ui container">
  <h1>Hello World!</h1>
</div>
```

Just by wrapping your elements in a div with the class "ui container," you'll automatically get a nice padding around your elements. This is all defined in Semantic UI, so you don't have to manually adjust the padding in your stylesheet at all. It's just a lot quicker to use Semantic UI here. In addition, when making things like menus, Semantic UI is just a lot simpler. 

```HTML
<div class="ui borderless topmenu menu">
  <div class="ui container">
    <div class="item">
      <a href = "#">Link 1</a>
      <a href = "#">Link 2</a>
    </div>
  </div>
</div>
```
Just like that, a menu is created for the website. What the menu looks like can be further customized in your stylesheet with .ui.borderless.topmenu.menu if needed. This code was actually the basis for creating this site: 

<img class="ui rounded image" src="../images/ui_container.png">

Overall, this website looks incredibly clean and professional. With Semantic UI, I can easily design websites that look a lot more neater. While the same result could be replicated with raw HTML and CSS, it's just a lot easier to do so with Semantic UI. Even though Semantic UI can't *completely* save my sites (That probably falls on me for my enjoyment of colors and patterns that give you a migraine just looking at them), it can do a lot in making a website that I can proudly show people. 
