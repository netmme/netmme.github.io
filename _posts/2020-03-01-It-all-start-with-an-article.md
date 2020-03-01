---
layout: post
title: Tournament arc — It all start with an article [1/.]
---

This story start in my ex-university’s library. There was a clearance sale and
I went to it because books. That’s a reason. On a table, next to a Shakespear
manga’s adaptation and a guide on how to use rootkits, an AI periodical took
center stage. I was a computer science student and AI was a brand new magic and
shiny concept to me at this time. So I bought the book...

![_config.yml]({{ site.baseurl }}/images/config.png)

The book was “Revue d’intelligence artificielle volume 14 : algorithme d’apprentissage et application.” In fact I bought two more books on ant colony algorithms but I never succeeded to pass the second article. Anyway, I came back home with my shiny new book (and some others) and I started to read it. I read it on the bus, at class, at the doctor’s office and I finally finished it. It was realy intersting and one article stood out. This article was about AI and games. As you know I was a found of AI but you may not know that I do love game more than AI. I love video games, card games, board games and both game theory (the youtube channel and the science). That article (drammatic pause) was the beginning of a very long journey…

The article was : “Apprentissage pour l’anticipation de comportements de joueurs humains dans les jeux à information complète et imparfaite : les “Mind-Reading Machines”” by Jean-Daniel Zucker and Christophe Meyer. Or for Shakespear’s people who don’t believe on google translate : “How humans suck at playing unpredictably or randomly.” Here come a realy quick and dirty abstract.

Hum hum…

There is a game calling matching penny. Player A (wich will be Alice) choose between either tails or faces. Player B (let’s call him Bob) have to guess wich side Alice have choose. If he guess right then he get the point. If not, Alice get the point. Here come a game simulation :

“Alice: I secretly choose tails. Bob what do you think I chose ?

Bob: I’m gonna guess heads.

Alice: Well you’re wrong, I get the point. Here we go again, I secretly choose tails agains. Bob ?

Bob: Edges.

Alice: ... Please get help.”

The researchers propose three algorithms to play (and win) at this game.

* The first one is the Shanon mind-reading machine. Basicly the algorithm look if you change or keep your choice after a loss or a win. Obviously there is a little more than that but it’s enough to see the big picture.

* The second one is the Minaisi alorithm. Inspired by an algorithm proposed by Minaisi to win at rock-paper-scissors. This algorithm will remember all choices you made and then find patterns. If the algorithm recognize a past pattern he will guess that your next choices will be the same as the previous time.

* The third case is a brand new algorithm propose by the two researchers, called SAGACE. The exeplanation in the article is basicly just a big picture with arrows and boxes. Honnestly I’m not realy sure how it works so I will remain silent on him for now.

I was excited ! The game was simple, the first two algorithms was also simple and my python 3 (please don’t use python 2 anymore !) was ready to do a messy but quick implementation to test all those ideas. That was the very first stone on a painful road. During my journey to a final implementation of this game, I gathered more and more documentation. One day I said to myself: “Man there is not a lot of documentation about what you are looking for. It could be nice if you keep a trace of all of this.” Obviously I said this to myself way to late to have properly written down all the sources I used but the idea was there. And that’s how I decided to do a series of articles about this project wich started on how to implement a mind-reading machine and is now at a state where I have to find how to solve a combinatorial optimization problem. And it’s not even the end of it…

PS: As you can guess by reading the article name I’m French and as 95% of the french population, I’m bad at english (the other 5% are liars). Those articles will also be a way to improve my writting skills. If you spot a mistake (and I’m sure they’re will be some), don’t burn me alive please and just notify me. I will happily correct it and learn from my mistakes. Have a greatful day :) (or night, I don’t know).
