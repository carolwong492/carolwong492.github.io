---
layout: essay
type: essay
title: Frog in the Machine
# All dates must be YYYY-MM-DD format!
date: 2022-02-10
labels:
  - ESLint
  - Coding Standards
  - Learning
---
## Running Smoothly
Coding standards are rules and practices that make the most readable and most efficient code. It helps protect against minor errors and just gives your code a clean feel. Needless to say, when working in a group, they're essential to making sure that others can quickly read your code and edit accordingly. Though they can be a bit boring and annoying to keep track of, coding standards are an essential cog in the machine. Code that doesn't comply to an agreed-upon coding standard will exponentially increase the time team-members spend working, as a large portion of their time will be spent trying to deduce what you wrote. In fact, you might even confuse yourself if you don't follow coding standards, as you might have to spend time looking through messy code for a missing parenthesis or some other minor issue.

<img class="ui medium right floated rounded image" src="../images/frogcomputer.jpg">
By skipping coding standards, you may feel that you save a few extra seconds, not worrying about the readability of the code, and instead, focusing on getting the program to work as quickly as possible. But without that essential cog in the machine, you're left with a plethora of bugs that no amount of frogs could eat up. 

## Grinds My Gears
One time, in my high school Intro to Computer Science class, we were randomly paired up to inspect each other's code for our end-of-quarter project. After we swapped laptops, I gave a cursory glance at their code and tried scrolling down. When the scrollbar didn't appear on the side of the screen, but on the *bottom,* I knew that this was not going to be fun. 

I looked closer to see that yes, this was a horizontal scroll bar with a scroll box smaller than my pinky nail. In fascinated horror, I scrolled to the right and watched as hundreds of characters passed by, all formatted on a singular line. I turned, slack-jawed, and my partner merely shrugged and said they liked having their code on the fewest amount of lines as possible. And I don't know, maybe my partner genuinely coded better like that. Maybe having three hundred &&'s and \|\|'s all on one line was truly how they worked best. But as an outsider, I could hardly parse what each line was supposed to do, much less suggest how to improve the code. 

Imagine working on a project where everyone wrote like that: Each file having only one line composed of thousands of characters. Work would never get done, because we'd be too busy nursing our migraines in the break room. 

After that harrowing experience, I vowed to always maintain the neatest and most readable code that I could. In every new IDE I used, one of the first things I would search up would be the keyboard shortcut to fix my indentation. I would press it every time I finished a couple of lines of code until it just became habit.

## The Green Checkmark
What exactly is defined as being "coding standard" differs from IDE to IDE, or language to language, or even person to person. Luckily, checkstyle tools are made to quicken the process, alerting you right away if you write a line of code that doesn't follow proper coding standard. With ESLint, errors are not only underlined with a red squiggly line, but noted with a red bar on the side of the line of the error *and* the total number of errors is shown in red in the upper right corner. With that many alerts, it's not difficult to easily locate where the coding standard error is. 

As for fixing the error, ESLint provides a description of what the error is, such as how strings should be surrounded with single-quotes instead of double-quotes. If you can't figure out how to fix the error from the description, ESLint also provides the name of the error, so it's simply a matter of searching up the error and finding it in the ESLint documentation. When that is all said and done, seeing that green checkmark in the corner is very gratifying; it's like getting a final seal of approval that your code is good to go. 

Overall, I am the number one supporter of coding standards and I believe that they should be used in practically every situation. They just make things simpler for everyone involved, and make code so much nicer to look at. With cleaner code, we can replace our frogs with cogs and get a smooth-running machine. 
