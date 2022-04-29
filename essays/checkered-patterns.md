---
layout: essay
type: essay
title: Checkered Patterns
# All dates must be YYYY-MM-DD format!
date: 2022-04-27
labels:
  - Design Patterns
  - Software Engineering
  - Learning
---
## More Than a Million Moves
<img class="ui medium right floated rounded image" src="../images/chess.jpg">
There are an average of 10<sup>120</sup> possible games of chess, according to [Hercules Chess](https://herculeschess.com/how-many-chess-games-are-possible/). This is greater than the number of atoms in the observable universe. This was calculated as on average, in any given turn, there are 30 legal moves you could make. With so many possible moves in so many possible games, how do you know what's a good move or not?

Back when I was in Chess Club, and each club meeting would begin with an introduction and explanation of a chess move. The Scotch Opening, Dutch Defense, Queen's Gambit, and so on. Our club advisor would go into the history of each move, what each move was, and how to counter it. If I'm being honest, I had no real interest in learning about these moves. I just enjoyed playing chess off-the-cuff, and didn't really see the point in learning about chess openings from 50 years ago. When I played against a new opponent, it wasn't as if our game was going to follow one of those old games to a tee, so what was the point in learning about those moves?

## Recognize and (Meteor) React
While it's impossible to even think of trying to memorize all possible chess games and moves, being able to recognize a select few can prove advantageous. Recognizing moves that your opponent is using can give you insight into what they might do next and how to properly counter and win.

<img class="ui medium left floated rounded image" src="../images/sinkface.jpeg">
Humans are pattern-recognition machines. It's why we see faces in inanimate objects. Whenever we see or experience something new, our minds immediately compare it to similar situations we've been in in the past so we know how to react.

When coding a structure, we may come across a problem we have to solve or a feature that we wish to implement, and feel swamped with all of the possibile ways to solve it. We don't need to reinvent the wheel each time. Instead, we can turn to design patterns. Design patterns provides us with a template solution to use for other similar problems. Knowing various design patterns can guide us when structuring our code. It won't provide you with all of the exact code to write, but like recognizing openings in chess, it can provide insight for what to do. 

One such design pattern is the Observer Design Pattern. In our project, we had a version of the Observer Design Pattern where we used Meteor's "reactivity" to adapt to reactive data. When constructing the page where users can search through recipes, we wanted the user to be able to select certain tags that they wanted their recipe to follow, such as being vegan or being able to be made under 10 minutes. While we could create a default static collection of tags, we would run into problems whenever that collection got updated. Some users may not have the full array of available tags. Using the following line of code, we were able to get the names of all of the tags in the collection. 

```const allTags = _.pluck(Tags.collection.find().fetch(), 'name');```

This ```.find()``` ensures that this line of code will be rerun each time the collection is edited, so the most recent collection of tags will be fetched. This ensures that users will have consistent access to all available tags. 

Patterns are everywhere in the world: in chess, in art, in the human mind. We can use these patterns to our advantage and 