# Decision-Making and Flow Theory

*Originally posted July 13, 2009*

I'm excited about this week, because this is where we're going to really get into the essence of game design, starting today with decision-making and continuing this Thursday with the nature of fun. These are some of my favorite topics to discuss, because it is the interactivity between players and systems that sets games apart from most other traditional media. This is where the magic of play happens, and as a systems designer, this strikes at the heart of what I deal with when making a game.

## Course Announcements

I understand that with 1400+ people, there will be a wide variance in free time. Some of you are students on holiday and can throw yourselves full-bore into this course with all its challenges. Others of you have day jobs and must focus on providing for yourself and your family first. Some of you are going through transitions of a personal nature, such as moving to a new city or dealing with the death of a loved one. This is all understandable, and expected.

So, I would like to clarify my expectations. My expectation is that each of you give what you can to your education. My hope is that you will take out of this course more than you put in. That is all.

If you have a week where you can do no more than read the blog, then that is what you should do. Obviously you will learn more if you do the challenges, but if you can't, better to do something than to drop everything. This course does not have to be an all-or-nothing venture, and I never intended it to be that way.

If you must prioritize, I would suggest the following:

1.  First, read the blog. This is the cornerstone of everything else in the course, so if you can do nothing else, do this. This includes the readings referenced in the blog from other sources. (If you fall behind, then hopefully you can catch up on the reading later. I will leave this blog online after the course is finished.)

2.  If you have some extra time after that, but not enough to do everything, please provide feedback and peer review to your fellow participants on the [forums](http://gamedesignconcepts.aceboard.com/), in the Project Postings section. I think the people that take the time to do the challenge and post it deserve to have feedback, and time constraints prevent me from giving it myself, so this must be participant-driven and grass-roots in nature. As a courtesy to others, do this if you possibly can.

3.  If you have all the time you need, do the challenge and post it.


## Mini-Challenge Results

Here are a small selection of the answers to the mini-challenge from last time (propose a concept for an art game):

-   A game where players have a secret goal and try to guess other players' goals, as a metaphor for growing up gay.

-   A game similar to The Sims, except it becomes harder to perform functions as time progresses, to get across the feeling of being afflicted with Alzheimer's.

-   A first-person shooter where players are only shown a single line showing the player's line-of-sight, showing the view of a 2D hero in a Flatland world.

-   A sorcery-themed game where the effects of spells are designed during play.


## Readings

Read the following:

-   *Challenges for Game Designers*, Chapters 5 and 6 (Chance / Strategic Skill)

-   *A Theory of Fun for Game Design*, Chapters 1, 2 and 3 (Why Write This Book / How the Brain Works / What Games Are)… if you chose to acquire this book. In an earlier comment, someone suggested only reading the cartoons on each page first, then going back and reading the text afterward.

-   [Building a Princess Saving App](http://lostgarden.com/Mixing_Games_and_Applications.pdf) (PDF), by Dan Cook. This article is actually written for an audience of interaction designers to explain what productivity applications can learn from games. In the process, though, it also happens to touch on some core concepts of game design and the nature of "fun" which is exactly what we're talking about today.


## Decisions

As Costikyan pointed out in *I Have No Words*, we often use the buzzword "interactivity" when describing games when we actually mean "decision-making." Decisions are, in essence, what players *do* in a game. Remove all decisions and you have a movie or some other linear activity, not a game. As pointed out in *Challenges*, there are two important exceptions, games which have no decisions at all: some children's games and some gambling games. For gambling games, it makes sense that a lack of decisions is tolerable. The "fun" of the game comes from the thrill of possibly winning or losing large sums of money; remove that aspect and most gambling games that lack decisions suddenly lose their charm. At home when playing only for chips, you're going to play games like *Blackjack* or *Poker* that have real decisions in them; you are probably not going to play *Craps* or a slot machine without money being involved.

You might wonder, what is it about children's games that allow them to be completely devoid of decisions? We'll get to that in a bit.

Other than those two exceptions, most games have some manner of making decisions, and it is here that a game can be made more or less interesting. Sid Meier has been quoted as saying that a good game is a series of interesting decisions (or something like that), and there is some truth there. But what makes a decision "interesting"? *Battleship* is a game that has plenty of decisions but is not particularly interesting for most adults; why not? What makes the decisions in *Settlers of Catan* more interesting than *Monopoly*? Most importantly, how can you design your own games to have decisions that are actually compelling?

## Things Not To Do

Before describing good kinds of decisions, it is worth explaining some common kinds of **uninteresting** decisions commonly found in games. Note that the terminology here (obvious, meaningless, blind) is my own, and is not "official" game industry jargon. At least not yet.

-   **Meaningless decisions** are perhaps the worst kind: there is a choice to be made, but it has no effect on gameplay. If you can play either of two cards but both cards are identical, that's not really much of a choice.

-   **Obvious decisions** at least have an effect on the game, but there is clearly one right answer, so it's not really much of a choice. Most of the time, the number of dice to roll in the board game *RISK* falls into this category; if you are attacking with 3 or more armies, you have a "decision" of whether to roll 1, 2, or 3 dice… but your odds are better rolling all 3, so it's not much of a decision except in very special cases. A more subtle example would be a game like *Trivial Pursuit*. Each turn you are given a trivia question, and if you know the correct answer it could be said that you have a decision: say the right answer, or not. Except that there's never any reason to *not* say the right answer if you know it. The fun of the game comes from showing off your mastery of trivia, not from making any brilliant strategic maneuvers. This is also, I think, why quiz shows like *Jeopardy!* are more fun to watch than to play.

-   **Blind decisions** have an effect on the game, and the answer is not obvious, but there is now an additional problem: the players do not have sufficient knowledge on which to make the decision, so it is essentially random. Playing *Rock-Paper-Scissors* against a truly random opponent falls into this category; your choice affects the outcome of the game, but you have no way of knowing what to choose.


These kinds of decisions are, by and large, not much fun. They are not particularly interesting. All three represent a waste of a player's time. Meaningless decisions could be eliminated, obvious decisions could be automated, and blind decisions could be randomized without affecting the outcome of the game at all.

In this context, it is suddenly easy to see why so many games are not particularly compelling.

Consider the trivia game that popularized the genre, *Trivial Pursuit*. First you roll a die, and move in any direction, so which location you land on is a decision. Only a few spaces on the board help you towards your victory condition, so if you can land on one of those it is an obvious decision. If you can't, your choice generally amounts to which category you're strongest at, which is again obvious (or blind, to the extent that you don't know what question you would get in each category until after you choose). Once you finish moving, you're asked a trivia question. If you don't know the answer, there is no decision to be made. If you *do* know the answer, there is a decision of whether to say it or not… but there is no reason not to, so again it is an obvious decision.

Or consider the board game *Battleship* which seems to keep coming up in our discussions. Just about every decision made in this game is blind. You are given no information on which to base your decision of what space to fire at. Once you hit an enemy ship you do have *some* information, but you still don't know which direction the ship is oriented (horizontally or vertically) or where its endpoints are, so the decision is more constrained but not any less blind.

Or consider *Tic-Tac-Toe*, which has interesting strategic decisions until you reach the age where you master it and realize the way to always win or draw, at which point the decisions become obvious.

## What Makes Good Decisions?

Now that we know what makes *weak* decisions, the easiest answer is "don't do that!" But we can take it a little further. Generally, *interesting* decisions involve some kind of **tradeoff**. That is, you are giving up one thing in exchange for another. These can take many different forms. Here are a few examples (again I use my own invented terminology here):

-   **Resource trades**. You give one thing up in exchange for another, where both are valuable. Which is *more* valuable? This is a value judgment, and the player's ability to correctly judge or anticipate value is what determines the game's outcome.

-   **Risk versus reward**. One choice is safe. The other choice has a potentially greater payoff, but also a higher risk of failure. Whether you choose safe or dangerous depends partly on how desperate a position you're in, and partly on your analysis of just *how* safe or dangerous it is. The outcome is determined by your choice, plus a little luck… but over a sufficient number of choices, the luck can even out and the more skillful player will generally win. (Corollary: if you want more luck in your game, reduce the total number of decisions.)

-   **Choice of actions**. You have several potential things you can do, but you can't do them all. The player must choose the actions that they feel are the most important at the time.

-   **Short term versus long term**. You can have something right now, or something better later on. The player must balance immediate needs against long-term goals.

-   **Social information**. In games where bluffing, deal-making and backstabbing are allowed, players must choose between playing honestly or dishonestly. Dishonesty may let you come out better on the current deal, but may make other players less likely to deal with you in the future. In the right (or wrong) game, backstabbing your opponents may have very negative real-world consequences.

-   **Dilemmas**. You must give up one of several things. Which one can you most afford to lose?


Notice the common thread here. All of these decisions involve the player judging the value of something, where values are shifting, not always certain, and not obvious.

The next time you play a game that you really like, think about what kinds of decisions you are making. If you have a particular game that you strongly *dis* like, think about the decisions being made there, too. You may find something about yourself, in terms of the kinds of decisions that you enjoy making.

## What About Action Games?

At this point, the video gamers among you are wondering how any of this applies to the latest First-Person Shooter. After all, you're not exactly strategizing about resource management tradeoffs in the middle of a heated battle where bullets and explosions are flying all around you.

The short answer here is that you *are* making interesting decisions in such games, and in fact you are making them at a much faster rate than normal – often several meaningful decisions per second. To compensate for the intense time pressure, the decisions tend to be much simpler: fire or dodge? Aim or move? Duck or jump?

Time limits can, in fact, be used to turn an obvious decision into a meaningful one. Another way I prefer to say this is that **time pressure makes us stupid**. For a more thorough discussion of action games and how skill relates to them, see Chapter 7 (Twitch Skill) in *Challenges for Game Designers*.

## Emotional Decisions

There is one class of decisions that is useful to consider: decisions that have an emotional impact on the player. The decision of whether to save your buddy (while using some of your precious supplies) or leave him behind to die (potentially denying yourself some AI-assisted help later on) in *Far Cry* is a resource decision, but it is also meant to be an emotional one – and certainly, an identical decision made on a real-life battlefield would come down to more than just an analysis of available resources and probabilities. Likewise, the majority of players do not play through a game with moral choices (such as *Knights of the Old Republic* or *Fable*) as pure evil – not because "evil" is a suboptimal strategy, but because even in a fictional simulated world, a lot of people can't stomach the thought of torturing and killing innocent bystanders.

Or consider a common decision made at the start of many board games: what color are you? Color is usually just a way to uniquely identify player tokens on the board, and has no effect on gameplay. However, many people have a favorite color that they always play, and can become quite emotionally attached to "their" color. It can be rather entertaining when two players who "always" play Green, play together for the first time and start arguing over who gets to be Green. If player color has no effect on gameplay, it is a meaningless decision. It *should* therefore be uninteresting, and yet some players paradoxically find it quite meaningful. The reason is that they are emotionally invested in the outcome. This is not to say that you can cover up a bad game by artificially adding emotions; but rather, as a designer, be aware of what decisions your players seem to respond to on an emotional level.

## Flow theory

Let's talk a little bit about this elusive concept of "fun." Games, we are told, are supposed to be fun. The role of a game designer is, in most cases, to take a game and make it fun. I've used the word "fun" a lot in this course without really defining it, and it has understandably made some of you uncomfortable. Notice I usually enclose the word "fun" in quotation marks, on purpose. My reasoning is that "fun" is not a particularly useful word for game designers. We instinctively know what it means, sure, but the word tells us nothing about how to *create* fun. What is fun? Where does it come from? What makes games fun in the first place? We will continue to talk about this on Thursday, but I want to start talking about it now. I'm sure you can agree it has been long enough.

Interesting decisions seem like they might be fun. Is that all there is to it? Not entirely, because it doesn't say anything about *why* these kinds of decisions are fun. Or why *uninteresting* decisions are still fun for children. For this, we turn to Raph Koster.

What a lot of Koster's *Theory of Fun* boils down to is this: **the fun of games comes from skill mastery**. This is a pretty radical statement, because it equates "fun" with "learning"… and at least when I was growing up, we were all accustomed to regard "learning" with "school" which was about as *not* fun as you could get. So it deserves a little explanation.

*Theory of Fun* draws heavily on the work of psychologist Mihaly Csikszentmihalyi (pronounced just like it's spelled, in case you're wondering), who studied what he called the mental state of "flow" (we sometimes call it being "in the flow" or "in the zone"). This is a state of extreme focus of attention, where you tune out everything except the task you're concentrating on, you become highly productive, and your brain gives you a shot of neurochemicals that is pleasurable – being in a flow state is literally a natural high.

Csikszentmihalyi identified three requirements for a flow state to exist:

-   You must be performing a **challenging activity** that requires **skill**.

-   The activity must provide **clear goals** and **feedback**.

-   The outcome is **uncertain** but can be **influenced** by your actions. (Csikszentmihalyi calls this the "paradox of control": you are in control of your actions which gives you indirect control over the outcome, but you do not have *direct* control over the outcome.)


If you think about it, these requirements make sense. Why would your brain need to enter a flow state to begin with, blocking out all extraneous stimuli and hyper-focusing your attention on one activity? It would only do this if it needs to in order to succeed at the task. What conditions would there have to be for a flow state to make the difference between success and failure? See above – you'd need to be able to influence the activity through your skill towards a known goal.

Csikszentmihalyi also gave five effects of being in a flow state:

-   A merging of action and awareness: spontaneous, automatic action/re\-ac\-tion. In other words, you go on autopilot, doing things without thinking about them. (In fact, your brain is moving faster than the speed of thought – think of a time when you played a game like *Tetris* and got into a flow state, and then at some point it occurred to you that you were doing really well, and then you wondered how you could keep up with the blocks falling so fast, and as soon as you started to think about it the blocks *were* moving too fast and you lost. Or maybe that's just me.)

-   Concentration on immediate tasks: complete focus, without any mind-wandering. You are not thinking about long-term tradeoffs or other tasks; your mind is in the here-and-now, because it *has* to be.

-   Loss of awareness of self, loss of ego. When you are in a flow state, you become one with your surroundings (in a Zen way, I suppose).

-   There is a distorted sense of time. Strangely, this can go both ways. In some cases, such as my *Tetris* example, time can seem to slow down and things seem to happen in slow motion. (Actually, what is happening is that your brain is acting so efficiently that it is working *faster*; everything else is still going at the same speed, but you are seeing things from your own point of reference.) Other times, time can seem to speed up; a common example is sitting down to play a game for "just five minutes"… and then six hours later, suddenly becoming aware that you burned away your whole evening.

-   The experience of the activity is an end in itself; it is done for its own sake and not for an external reward. Again, this feeds into the whole "here-and-now" thing, as you are not in a mental state where you can think that far ahead.


I find it ironic, when a typical kid is in their "not now, I'm playing a game" mental state, the parent complains that they are "zoned out." In fact, the gamer is in a flow state, and they are "zoned *in* " to the game.

## Flow States in Games

Simplifying this a bit, we know that to be in a flow state, an activity must be **challenging**. If it is too easy, then the brain has no reason to waste extraneous mental cycles, as a positive outcome is already assured. If it is too difficult, the brain *still* has no reason to try hard, because it knows it's just going to fail anyway. The goal is to hit that sweet spot where the player can succeed… but only if they try hard. You'll often see a graph that looks like this, to demonstrate:

![Challenge Versus Skill in Flow States][]
[Challenge Versus Skill in Flow States]: level_7_czikszentmihalyi.jpg height=200px

All this says is that if you have a high skill level and are given an easy task, you're bored; if you have a low skill level and are given a difficult task, you're frustrated; but if the challenge level of an activity is comparable to your current skill level… flow state! And this is good for games, because this is where a lot of the fun of games comes from.

Note that "flow" and "fun" are not synonyms, although they are related. You can be in a flow state without playing a game (and in fact without having fun). For example, an office worker might get into a flow state while filling out a series of forms. They may be operating at the edge of their ability in filling out the forms as efficiently as possible, but there may not be any real learning going on, and the process may not be fun, merely meditative. (Thanks to Raph for clarifying this for me.)

## One Slight Problem

When you are faced with a challenging task, you get better at it. It's fun because you are *learning*, remember? So, most people start out with an activity (like a game) with a low skill level, and if the game provides easy tasks, then so far so good. But what happens when the player gains some competency? If they keep getting the same easy tasks, the game becomes boring. This is essentially what happens in *Tic-Tac-Toe* when a child makes the transition to understanding the strategy of the game.

By the way, we can now answer our earlier question: why can children's games get away with a lack of meaningful decision-making? The answer is that young children are still learning valuable skills from these games: how to roll a die, move a token on a board, spin a spinner, take turns, read and follow rules, determine when the game ends and who wins, and so on. These skills are not instinctive and must be taught and learned through repeated play. When the child masters these skills, that is about the time when decision-less games stop holding any lasting appeal.

Ideally, as a game designer, you would like your game to have slightly more lasting playability than *Tic-Tac-Toe*. What can you do? Games offer a number of solutions. Among them:

-   Increasing difficulty as the game progresses (we sometimes call this the "pacing" of a game). As the player gets better, they get access to more difficult levels or areas in a game. This is common with level-based video games.

-   Difficulty levels or handicaps, where better players can choose to face more difficult challenges.

-   Dynamic difficulty adjustment ("DDA"), a special kind of negative feedback loop where the game adjusts its difficulty during play based on the performance of the player.

-   Human opponents as opposition. Sure, you can get better at the game… but if your opponent is also getting better, the game can still remain challenging if it has sufficient depth. (This can fail if the skill levels of different players fall out of synch with one another. I like to play games with my wife, and we usually both start out at about the same skill level with any new game that really fascinates us both… but then sometimes, one of us will play the game a lot and become so much better than the other, that the game is effectively ruined for us. It is no longer a challenge.)

-   Player-created expert challenges, such as new levels made by players using level-creation tools.

-   Multiple layers of understanding (the whole "minute to learn, lifetime to master" thing that so many strategy games strive for). You can learn *Chess* in minutes, as there are only six different pieces… but then once you master that, you start to learn about which pieces are the most powerful and useful in different situations, and then you start to see the relationship between pieces, time, and area control, and then you can study book openings and famous games, and so on down the rabbit hole.

-   Jenova Chen's [*flOw*](http://www.jenovachen.com/flowingames/implementations/flowing/core.html) provides a novel solution to this: allow the player to change the difficulty level while playing based on their actions. Are you bored? Dive down a few levels and the action will pick up pretty fast. Are you overwhelmed? Run back to the earlier, easier levels (or the game will kick you back on its own if needed).


You'll notice that when we read in a review that a game has "replayability" or "many hours of gameplay" what we are often *really* saying is that the game is particularly good at keeping us in the flow state by adjusting its difficulty level to continue to challenge us as we get better.

## Why Games?

You might wonder, if flow states are so pleasurable and they are where this elusive and mysterious "fun" comes from, why do we design games to do this and not some other medium? Why not design *productive* tasks to induce flow states, for example, so that maybe we could get a few million people working on discovering a cure for cancer instead of playing *World of Warcraft*? Why not design college classes to induce flow states, so that a student could learn a typical 50-hour class in a week (the same way they might play through a 50-hour RPG on their *PlayStation*) instead of having that same class take an entire 10 or 15 weeks?

Games just happen to be naturally good at putting players in a flow state, so it is much easier to design a fun game than a fun course in Calculus. As Koster points out in *A Theory of Fun*, the brain is a great pattern-matching machine, and it is the finding and understanding of patterns that is what is happening when our brain is in a flow state. I think games bring this out really well because you have three levels of patterns: feeling the Aesthetics, discerning the Dynamics, and finally mastering the Mechanics (in the MDA sense). Since every game has these three layers of patterns, games are three times as interesting as most other activities.

## "Edutainment" Games

You might think that, if games are so great at teaching and if learning is so darned pleasurable, that educational games would be more fun than anything. In reality, of course, "Edutainment" is a dirty word that we only mention when forced, as the vast majority of games that bill themselves as "fun… *and* educational!" are actually neither. What's going on here?

Many "Edutainment" games work like this: first you've got this game, and you play it, and it's maybe kind of fun. And then the game stops, and tries to give you some kind of gross, icky, disgusting *learning*. And as a reward for doing the learning, you get to play the game again. Gameplay is framed as a *reward* for the *inherently unpleasurable* task of learning something. We have a name for this: **chocolate-covered broccoli**.

I think this design contains an error of thinking, and this infects the design of such games at a fundamental level, invalidating the whole premise. The error is the separation of "learning" and "fun" because, as you now know, these are not separate concepts but rather identical (or at least strongly related). The assumption that learning is not fun and that fun cannot be inherently educational undermines the entire game… and incidentally, also reinforces the extremely damaging notion that education is a chore and not a pleasure.

It would be wonderful if we could stop teaching that "learning is not fun" lesson to our children. It would certainly make my life a lot easier as a teacher, if I did not have to first convince my students that they should be intrinsically motivated to do well in my classes.

What if you want to design a game that has the primary purpose of teaching, then? That is a subject that deserves a course of its own. My short answer: start by isolating the inherently fun aspects of learning the skills you want to teach, and then use those as your core mechanics. By integrating the learning and the gameplay (rather than keeping them as separate concepts or activities), you take a large step towards something truly worthy of the "fun, and educational" label.

## A Note for Teachers

If you've accepted everything in this lesson so far, you might see a parallel with teaching. If learning is inherently fun, think about what you can do to draw that out of your subject.

-   How many interesting decisions do your students make? I once saw a statistic that the average college student raises their hand in class once every ten weeks – that's three meaningful decisions per year! Can you do better? Consider giving a choice of assignments (with built-in tradeoffs: for example, an easy-but-boring homework or a difficult-but-interesting one). Ask lots of questions in class that get students involved. Have class discussions or debates.

-   Are too many of your students bored or overwhelmed, because your class is at a difficulty that is too low or too high? Games have this problem too, and often solve it through including multiple difficulty levels; consider having a tiered grading system where remedial students should be able to pass if they can at least put in the work to grasp the basics, while offering advanced students extra work that is more interesting. Offer the course content in layers, first going over the very basics in a "For Dummies" way that everyone can get, then add the main details that are really important, and finally give some advanced applications that only some students might understand, but that are interesting enough that students will at least have some incentive to reach a bit.

-   The most fun games are designed in a player-centric manner, concentrating first on providing a quality experience. You can tell a game where the designer made a game that *they* wanted to play, because it sold a total of five copies to the designer, the designer's close friends, and the designer's mom. You can also tell a game where the designer started with content rather than gameplay; these are the games that have deep, involving stories and incredible layers of content, but no one sees them because the gameplay is boring and people stop playing after five minutes. What would your class be like if you start your lesson plans by thinking of the student experience, rather than designing a class that *you* find interesting (your students might not share your research interests), or designing a class based around content (which is probably not engaging until *you* bring it to life)?


## Lessons Learned

Decisions are the core of what a game is. When critically analyzing a game (yours or someone else's), pay attention to what decisions the players are making, how meaningful those decisions are, and *why*. The more you understand about what makes some decisions more compelling than others, the better a game designer you are likely to be.

Games are unnaturally good at teaching new skills to players. (Whether those skills are *useful* or not, varies from game to game.) Learning a new skill – by being given a challenge that forces you to try hard and increase your skill level – is one of the prerequisites for putting players in a flow state. Flow states are an intensely pleasurable state for the brain to be in, and a lot of the feeling of "fun" that comes from playing games comes from being in the flow.

There it is! Mystery solved! You now know everything there is to know about where "fun" comes from and how to create it. Okay, not really. But this is a start, and we will probe a bit deeper into the nature of "fun" this Thursday.

## Feedback

If you have time, before beginning the Homeplay below, please take the time to offer **constructive feedback** to at least three other posts from the art games from Level 6 (posted on the [forum](http://gamedesignconcepts.aceboard.com/)). If you posted a game yourself, offer feedback to other posts in the same category as you posted yours. If you were unable to post a game last time, then choose whichever of the four topics most interests you (see the bottom of [Level 6](http://gamedesignconcepts.wordpress.com/2009/07/16/level-6-games-and-art/) for details).

Try to complete your feedback on or before Thursday, July 23, noon GMT.

## Homeplay

This time around, let's practice our ability to provide meaningful decision-making to players. We are going to make a mod of a game. (This homeplay is adapted from Challenge 6-1 in the *Challenges* text.)

Here are the basic rules for the children's card game *War*:

-   Players: 2

-   Materials: one standard 52-card deck of playing cards (with Jokers removed)

-   Setup: Shuffle the deck of cards and deal out half to each player. Players take their cards in a single face-down stack.

-   Progression of Play: Simultaneously, players flip over the top card of their deck. If the cards are of unequal rank (number), the higher rank wins the "battle" and that player takes both cards and sets them aside in a discard pile (Aces are high, then King, Queen, Jack, then 10 down to 2). When a player runs out of cards in their deck, they take their discard pile and turn it over to form a new deck.

-   Wars: If players flip over cards that are equal rank, it starts a "war." Players each deal three cards face-down, then flip up a new card face-up, and the higher rank of the new face-up card wins all face-down and face-up cards. This process is repeated if the new face-up cards are the same rank, continuing with additional "wars" until eventually one player wins.

-   Resolution: The game ends when one player runs out of cards, *or* when one player must play cards for a "war" but they do not have enough cards remaining in their deck and discard pile. That player loses the game, and their opponent wins.

This game has no decisions whatsoever. The game mechanically plays itself, and the players merely act as tools to play out the game to its pre-determined conclusion.

Change the rules so that the game outcome is determined primarily by **skill**, and that the game now has **interesting, meaningful decisions**.

Post in the forum that most closely resembles your skill and experience level as a designer.

### Beginner

![Green Circle](images/green_circle.pdf)

Beginner, little or no experience prior to taking this course.

### Intermediate

![Blue Square](images/blue_square.pdf)

Intermediate, some coursework or exposure to game design but little or no professional experience.

### Advanced

![Black Diamond](images/black_diamond.pdf)

Advanced, at least some professional experience as a published game designer.

### Post

Make your post on or before Thursday, July 23, noon GMT. Then, **offer constructive feedback** to at least two other posts in the same forum, *and* at least three posts in one forum "below" yours if you posted in Blue Square or Black Diamond.

## Mini-Challenge

Add a rule that gives interesting decisions to *Trivial Pursuit* that can be expressed in 135 characters or less. Post it to Twitter with the \#GDCU tag. One rule change per person, please! Tweet before July 23, noon GMT.

## Parting Shot

If you're still curious, the name "Csikszentmihalyi" is pronounced "Chick-sent-me-high". Seriously, I'm not making this up. It's not exact, but it's about as close as you can get with an English-language transliteration.

