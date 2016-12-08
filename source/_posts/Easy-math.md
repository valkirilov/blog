title: Easy-math
tags:
  - easy-math
  - math
  - game
  - angular
  - solve
categories:
  - en
  - projects
date: 2016-09-25 13:52:00
---
---

{% asset_img cover.png Easy-math %}

## What Easy-math is?
It's a simple game that challenges your brain and speed of reaction with easy math problems. The game has a few different modes for playing and it allows you to play different levels and difficulties.
 
## What it gives me?
Easy-math is a simple game but can be used for big things, not just for entertainment and fun. This game is training your skills and developing your brain speed and reaction so don't forget to play here a few times a day to keep you in good shape.
 
## What it's not?
Easy-math is not a professional problem solving software. It's just a little game that helps you to develop your brain skills and entertains you.
 
## Wanna play it?
The game is online and you can find it at [http://valkirilov.github.io/easy-math/](http://valkirilov.github.io/easy-math/).
If you are interested about what is behind the UI you can read the whole review.

{% asset_img about.png About %}

# About the idea
This is an idea that was born in a moment of boredom during one of my classes at the university. I wanted to make something that would be addictive with its simplicity and started to work on something small. The main concept of easy-math is to compare two numbers and choose which of them is the bigger one. Therefore, it was the part developed first. I made a generator for simple problems (at the beginning it was generating numbers between 0-10 but later I changed it to be more complicated and generate more difficult problems.

{% asset_img technologies.png Programming %}

# The programming part
Since the project was started during one of my programming classes, I started it from one of my seed projects with AngularJS and Bootsrap. This is my second app with Angular (and first published online) and it was my way to learn some of its basics and practices.

You are already familiar with the idea so I can move directly on the structure. First, I separated the app in a few services. This way the logic of the project can be reused easily. The main parts are QuestionsService and GameFactory which, as you may suggest, are responsible for generating the questions and organizing, running and combining all other services to make the game works. Of course, HighScoreService and DatabaseService which are used for storing the results, fetching and saving them. There are also Timer and Sounds services which complete the list of stuff that is needed to make the game more addictive.

{% asset_img design.png Design %}

# The design part
My wish was to make simple and responsive design which would look good on different devices and, at the same time, would be easy to use. Because of this the "play" screen is really clear and contains only the question - the numbers that you have to compare and three buttons for selecting your choice. According to the game mode a timer or a score bar is at the top of the screen where you can see some more details about your current game.
 
Then I made some images which are used on the page for choosing the game mode to help the user to build a picture about the different game modes.
 
For the home screen, I decided to put the main game screen as an animated component to show what is the main goal of the game. This way, the first thing that visitors of the site see is the game concept and its simplicity. So,  when you start playing the game you have something familiar in front of you and not entirely new interface.

{% asset_img footer.png Future %}

# Future developement
Currently the game has two modes - Classic and Timelimit but everyone can contribute and make the game more various. For an example, there is no limit to new game modes that can be implemented. If you are interested and want to contribute you can contact me.
Have fun

Finally, if you like what you see now you can try it. The game is available online and you can find it at [http://valkirilov.github.io/easy-math/](http://valkirilov.github.io/easy-math/).
Try to beat the High Scores, currently I cannot enter in top 10 of my own game, can you?


---
date: 2016-09-25
author: Valentin Kirilov