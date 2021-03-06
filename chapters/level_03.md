# Formal Elements of Games

*Originally posted July 6, 2009*

Today marks the last day that we continue in building a critical vocabulary from which to discuss games; this Thursday we will dive right in to the game design process. Today I want the last pieces to fall into place: we need a way to dissect and analyze a game by discussing its component parts and how they all fit together. This can be useful when discussing other people's games (it would be nice if, for example, more professional game reviews could do this properly), but it is also useful in designing our own games. After all, how can you design a game if you don't know how all the different parts fit together?

## Course Announcements

As usual, there are a few things I'd like to announce and clarify:

-   I'm happy to announce that the [course wiki](http://gamedesignconcepts.pbworks.com/) is now open to the public (read-only access). This wiki is pretty much entirely run by the participants who registered for this course. Among other things, the blog posts here have already been translated into five different languages. I am impressed and humbled at the level of participation going on there, and encourage casual viewers to stop by and check it out.

-   I noticed some confusion on this so I would like to clarify: for readings in the *Challenges* text, you do not have to actually do all of the challenges at the end of the chapter. You certainly can if you want, but most chapters have five long challenges and ten short ones, and I would call that an extreme workload for a class of this pace. Repeat, **you do not have to do all of the challenges** (except where expressly noted on this blog).


## A note on the reading for today

One of the readings for today was Doug Church's *Formal Abstract Design Tools*. I want to mention a few things about this. First, he mentions three aspects of games that are worth putting in our design toolbox:

-   **Player intention** is defined as the ability of the player to devise and carry out their own plans and goals. We will come back to this later on in this course, but for now just realize that it can be important in many games to allow the player to form a plan of action.

-   **Perceivable consequence** is defined in the reading as a clear reaction of the game to the player's actions. Clarity is important here: if the game reacts but you don't know how the game state has changed, then you may have difficulty linking your actions to the consequences of those actions. I'll point out that "perceivable consequence" is known by a more common name: **feedback**.

-   **Story** is the narrative thread of the game. Note that a game can contain two different types of story: the "embedded" story (created by the designer) and the "emergent" story (created by players). Emergent story happens, for example, when you tell your friends about a recent game you played and what happened to you during the play: "I had taken over all of Africa, but I just couldn't keep the Blue player out of Zaire." Embedded story is what we normally think of as the "narrative" of the game: "You are playing a brave knight venturing into the castle of an evil wizard." Doug's point is that *embedded* story competes with intention and consequence — that is, the more the game is "on rails", the less the player can affect the outcome. When Costikyan said in "I Have No Words" that games are not stories, Doug provides what I think is a better way of saying what Costikyan meant.

Here is an example of why player intention and perceivable consequence are important. Consider this situation: you are playing a first-person shooter game. You walk up to a wall that has a switch on it. You flip the switch. Nothing happens. Well, actually something *did* happen, but the game gives you no indication of *what* happened. Maybe a door somewhere else in the level opened. Maybe you just unleashed a bunch of monsters into the area, and you'll run into them as soon as you exit the current room. Maybe there are a series of switches, and they all have to be in *exactly the right pattern* of on and off (or they have to be triggered in the right order) in order to open up the path to the level exit. But you have no way of knowing, and so you feel frustrated that you must now do a thorough search of everywhere you've already been… just to see if the switch did anything.

How could you fix this? Add better feedback. One way would be to provide a map to the player, and show them a location on the map when the switch was pulled. Or, show a brief cut scene that shows a door opening somewhere. I'm sure you can think of other methods as well.

On another subject, Doug also included an interesting note at the end of the article about how he values beta testing, and half of his readers found the first two pages slow, so start at page 3 if you're in that half. This would be an example of **iteration** in the design of this essay, of exactly the sort we talked about.

Now, I'm sure this note was partly in jest, but let's take it at face value. There's a slight problem with this fix: you don't see the note until you've already read all of the way through the article, and it's too late to do anything about it. If Doug were to iterate on his design a second time, what would you suggest he do? (I've heard many suggestions from my students in the past.)

## Qualities of Games

It was rightly pointed out in the comments of this blog that on the first day of this course, I contradicted myself: I insisted that a critical vocabulary was important, and then I went on to say that completely defining the word "game" is impossible. Let's reconcile this apparent paradox.

Take a quick look at the definitions listed on the [first day][overview]. Separate out all of the qualities listed from each definition that may apply to games. We see some recurring themes: games have rules, conflict, goals, decision-making, and an uncertain outcome. Games are activities, they are artificial / safe / outside ordinary life, they are voluntary, they contain elements of make-believe / representation / simulation, they are inefficient, they are art, and they are closed systems. Think for a moment about what other things are common to all (or most) games. This provides a starting point for us to identify individual game elements.

I refer to these as "formal elements" again, not because they have anything to do with wearing a suit and tie, but because they are "formal" in the mathematical and scientific sense: something that can be explicitly defined. *Challenges* refers to them as "atoms" — in the sense that these are the smallest parts of a game that can be isolated and studied individually.

## What are atomic elements of games?

This depends on who you ask. I have seen several schemes of classification. Like the definition of "game," none is perfect, but by looking at all of them we can see some emerging themes that can shed light on the kinds of things that we need to create as game designers if we are to make games.

What follows are some parts of games, and some of the things designers may consider when looking at these atoms.

### Players

How many players does the game support? Must it be an exact number (4 players only), or a variable number (2 to 5 players)? Can players enter or leave during play? How does this affect play?

What is the relationship between players: are there teams, or individuals? Can teams be uneven? Here are some example player structures; this is by no means a complete list:

-   Solitaire (1 player vs. the game system). Examples include the card game *Klondike* (sometimes just called "Solitaire") and the video game *Minesweeper*.

-   Head-to-head (1 player vs. 1 player). *Chess* and *Go* are classic examples.

-   "PvE" (multiple players vs. the game system). This is common in MMOs like *World of Warcraft*. Some purely-cooperative board games exist too, such as *Knizia's Lord of the Rings*, *Arkham Horror*, and *Pandemic*.

-   One-against-many (1 player vs. multiple players). The board game *Scotland Yard* is a great example of this; it pits a single player as Mr. X against a team of detectives.

-   Free-for-all (1 player vs. 1 player vs. 1 player vs. …). Perhaps the most common player structure for multi-player games, this can be found everywhere, from board games like *Monopoly* to "multiplayer deathmatch" play in most first-person shooter video games.

-   Separate individuals against the system (1 player vs. a series of other players). The casino game *Blackjack* is an example, where the "House" is playing as a single player against several other players, but those other players are not affecting each other much and do not really help or hinder or play against each other.

-   Team competition (multiple players vs. multiple players [vs. multiple players…]). This is also a common structure, finding its way into most team sports, card games like *Bridge* and *Spades*, team-based online games like "Capture the Flag" modes from first-person shooters, and numerous other games.

-   Predator-Prey. Players form a (real or virtual) circle. Everyone's goal is to attack the player on their left, and defend themselves from the player on their right. The college game *Assassination* and the trading-card game *Vampire: the Eternal Struggle* both use this structure.

-   Five-pointed Star. I first saw this in a five-player *Magic: the Gathering* variant. The goal is to eliminate both of the players who are *not* on either side of you.


### Objectives (Goals)

What is the object of the game? What are the players trying to do? This is often one of the first things you can ask yourself when designing a game, if you're stuck and don't know where to begin. Once you know the objective, many of the other formal elements will seem to define themselves for you. Some common objectives (again, this is not a complete list):

-   Capture/destroy. Eliminate all of your opponent's pieces from the game. *Chess* and *Stratego* are some well-known examples where you must eliminate the opposing forces to win.

-   Territorial control. The focus is not necessarily on destroying the opponent, but on controlling certain areas of the board. *RISK* and *Diplomacy* are examples.

-   Collection. The card game *Rummy* and its variants involve collecting sets of cards to win. *Bohnanza* involves collecting sets of beans. Many platformer video games (such as the *Spyro* series) included levels where you had to collect a certain number of objects scattered throughout the level.

-   Solve. The board game *Clue* (or *Cluedo*, depending on where you live) is an example of a game where the objective is to solve a puzzle. Lesser-known (but more interesting) examples are *Castle of Magic* and *Sleuth*.

-   Chase/race/escape. Generally, anything where you are running towards or away from something; the playground game *Tag* and the video game *Super Mario Bros.* are examples.

-   Spatial alignment. A number of games involve positioning of elements as an objective, including the non-digital games *Tic-Tac-Toe* and *Pente* and the video game *Tetris*.

-   Build. The opposite of "destroy" — your goal is to advance your character(s) or build your resources to a certain point. *The Sims* has strong elements of this; the board game *Settlers of Catan* is an example also.

-   Negation of another goal. Some games end when one player performs an act that is forbiden by the rules, and that player loses. Examples are the physical dexterity games *Twister* and *Jenga*.


### Rules (Mechanics)

As mentioned last week, there are three categories of rules: setup (things you do once at the beginning of the game), progression of play (what happens during the game), and resolution (what conditions cause the game to end, and how is an outcome determined based on the game state).

Some rules are automatic: they are triggered at a certain point in the game without player choices or interaction ("Draw a card at the start of your turn" or "The bonus timer decreases by 100 points every second"). Other rules define the choices or actions that the players can take in the game, and the effects of those actions on the game state.

Let's dig deeper. Salen & Zimmerman's *Rules of Play* classifies three types of rules, which they call operational, constituative, and implied (these are not standard terms in the industry, so the concepts are more important than the terminology in this case). To illustrate, let's consider the rules of *Tic-Tac-Toe*:

-   Players: 2

-   Setup: Draw a 3x3 grid. Choose a player to go first as X. Their opponent is designated O.

-   Progression of play: On your turn, mark an empty square with your symbol. Play then passes to your opponent.

-   Resolution: If you get 3 of your symbol in a row (orthogonally or diagonally), you win. If the board is filled and there is no winner, it is a draw.


These are what *Rules of Play* calls the "operational" rules. Think for a moment: are these the only rules of the game?

At first glance, it seems so. But what if I'm losing and simply refuse to take another turn? The rules do not explicitly give a time limit, so I could "stall" indefinitely to avoid losing and still be operating within the "rules" as they are typically stated. However, in actual play, a reasonable time limit is implied. This is not part of the formal (operational) rules of the game, but it is still part of what *Rules of Play* calls the "implied" rules. The point here is that there is some kind of unwritten social contract that players make when playing a game, and these are understood even when not stated.

Even within the formal rules there are two layers. The 3x3 board and "X" and "O" symbols are specific to the "flavor" of this game, but you could strip them away. By reframing the squares as the numbers 1 through 9 and turning spatial alignment into a mathematical property, you can get *Three-to-Fifteen*. While *Tic-Tac-Toe* and *Three-to-Fifteen* have different implementations and appearances, the underlying abstract rules are the same. We do not normally think in these abstract terms when we think of "rules" but they are still there, under the surface. *Rules of Play* calls these "constituative" rules.

Is it useful to make the distinction between these three types of rules? I think it is important to be aware of them for two reasons:

-   The distinction between "operational" and "constituative" rules helps us understand why one game is fun in relation to other games. The classic arcade game *Gauntlet* has highly similar gameplay to the first-person shooter *DOOM*; the largest difference is the position of the camera. For those of you who play modern board games, a similar statement is that *Puerto Rico* is highly similar to *Race for the Galaxy.* The similarity may not be immediately apparent because the games look so different on the surface, unless you are thinking in terms of game states and rules.

-   Many first-person shooters contain a rule where, when a player is killed, they re-appear ("respawn") in a specific known location. Another player can stand near that location and kill anyone that respawns before they have a chance to react. This is known as "spawn-camping" and can be rather annoying to someone on the receiving end of it. Is spawn-camping part of the game (since it is allowed by the rules)? Is it good strategy, or is it cheating? This depends on who you ask, as it is part of the "implied" rules of the game. When two players are operating under different implied rules, you will eventually get one player accusing the other of cheating (or just "being cheap") while the other player will get defensive and say that they're playing by the rules, and there's no reason for them to handicap themselves when they are playing to win. The lesson here is that it is important for the game designer to define as many of these rules as possible, to avoid rules arguments during play.


### Resources and Resource Management

"Resources" is a broad category, and I use it to mean everything that is under control of a single player. Obviously this includes explicit resources (Wood and Wheat in *Settlers of Catan*, health and mana and currency in *World of Warcraft*), but this can also include other things under player control:

-   Territory in *RISK*

-   Number of questions remaining in *Twenty Questions*

-   Objects that can be picked up in video games (weapons, powerups)

-   Time (either game time, or real time, or both)

-   Known information (as the suspects that you have eliminated in *Clue*)


What kinds of resources do the players control? How are these resources manipulated during play? This is something the game designer must define explicitly.

### Game State

Some "resource-like" things are not owned by a single player, but are still part of the game: unowned properties in *Monopoly*, the common cards in *Texas Hold ‘Em*. Everything in the game together, including the current player resources and everything else that makes up a snapshot of the game at a single point in time is called the *game state*.

In board games, explicitly defining the game state is not always necessary, but it is sometimes useful to think about. After all, what are rules, but the means by which the game is transformed from one game state to another?

In video games, someone must define the game state, because it includes all of the data that the computer must keep track of. Normally this task falls to a programmer, but if the game designer can explicitly define the entire game state it can greatly aid in the understanding of the game by the programming team.

### Information

How much of the game state is visible to each player? Changing the amount of information available to players has a drastic effect on the game, even if all other formal elements are the same. Some examples of information structures in games:

-   A few games offer total information, where all players see the complete game state at all times. *Chess* and *Go* are classic board game examples.

-   Games can include some information that is private to each individual. Think of *Poker* and other card games where each player has a hand of cards that only they can see.

-   One player can have their own privileged information, while other players do not. This is common in one-against-many player structures, like *Scotland Yard*.

-   The game itself can contain information that is hidden from all players. Games like *Clue* and *Sleuth* actually have the victory condition that a player discover this hidden information.

-   These can be combined. Many "real-time strategy" computer games use what is called "fog of war" where certain sections of the map are concealed to any player that does not have a unit in sight range. Some information is therefore hidden from all players. Beyond that, players cannot see each other's screens, so each player is unaware of what information is and isn't available to their opponents.


### Sequencing

In what order do players take their actions? How does play flow from one action to another? Games can work differently depending on the turn structure that is used:

-   Some games are purely turn-based: at any given time it is a single play\-er's "turn" on which they may take action. When they are done, it becomes someone else's turn. Most classic board games and turn-based strategy games work this way.

-   Other games are turn-based, but with simultaneous play (everyone takes their turn at the same time, often by writing down their actions or playing an action card face-down and then simultaneously revealing). The board game *Diplomacy* works like this. There is also an interesting *Chess* variant where players write down their turns simultaneously and then resolve (two pieces entering the same square on the same turn are both captured) that adds tension to the game.

-   Still other games are real-time, where actions are taken as fast as players can take them. Most action-oriented video games fall into this category, but even some non-digital games (such as the card games *Spit* or *Speed*) work this way.

-   There are additional variations. For a turn-based game, what order do players take their turns? Taking turns in clockwise order is common. Taking turns in clockwise order and then skipping the first player (to reduce the first-player advantage) is a modification found in many modern board games. I've also seen games where turn order is randomized for each round of turns, or where players pay other resources in the game for the privilege of going first (or last), or where turn order is determined by player standing (player who is currently winning goes first or last).

-   Turn-based games can be further modified by the addition of an explicit time limit, or other form of time pressure.


### Player Interaction

This is an often-neglected but highly important aspect of games to consider. How do players interact with one another? How can they influence one another? Here are some examples of player interactions

-   Direct conflict ("I attack you")

-   Negotiation ("If you support me to enter the Black Sea, I'll help you get into Cairo next turn")

-   Trading ("I'll give you a Wood in exchange for your Wheat")

-   Information sharing ("I looked at that tile last turn and I'm telling you, if you enter it a trap will go off")


### Theme (Or Narrative, Backstory, or Setting)

These terms do have distinct meanings for people who are professional story writers, but for our purposes they are used interchangeably to mean the parts of the game that do not directly affect gameplay at all.

If it doesn't matter in terms of gameplay, why bother with this at all? There are two main reasons. First, the setting provides an emotional connection to the game. I find it hard to really care about the pawns on my chessboard the way I care about my *Dungeons & Dragons* character. And while this doesn't necessarily make one game "better" than another, it does make it easier for a player to become emotionally invested in the game.

The other reason is that a well-chosen theme can make a game easier to learn and easier to play, because the rules make sense. The piece movement rules in *Chess* have no relation to the theme and must therefore be memorized by someone learning the game. By contrast, the roles in the board game *Puerto Rico* have some relation to their game function: the builder lets you build buildings, the mayor recruits new colonists, the captain ships goods off to the Old World, and so on. It is easy to remember what most actions do in the game, because they have some relation to the theme of the game.

## Games as Systems

I'd like to call two things about these formal elements to your attention.

First, if you change even one formal element, it can make for a *very* different game. Each formal element of a game contributes in a deep way to the player experience. When designing a game, give thought to each of these elements, and make sure that each is a deliberate choice.

Second, note that these elements are interrelated, and changing one can affect others. Rules govern changes in Game State. Information can sometimes become a Resource. Sequencing can lead to different kinds of Player Interaction. Changing the number of Players can affect what kinds of Objectives can be defined. And so on.

Because of the interrelated nature of these parts, you can frame any game as a **system**. (One dictionary definition of the word "system" is: a combination of things or parts that form a complex whole.)

In fact, a single game can contain several systems. *World of Warcraft* has a combat system, a quest system, a guild system, a chat system, and so on…

Another property of systems is that it is hard to fully understand or predict them just by defining them; you gain a far deeper understanding by seeing the system in action. Consider the physical system of projectile motion. I can give you a mathematical equation to define the path of a ball being thrown, and you could even predict its behavior… but the whole thing makes a lot more sense if you see someone actually throwing a ball.

Games are like this, too. You can read the rules and define all the formal elements of a game, but to truly understand a game you need to play it. This is why most people do not immediately see the parallel between *Tic-Tac-Toe* and *Three-to-Fifteen* until they have played them.

## Critical Analysis of Games

What is a critical analysis, and why do we care?

Critical analysis is not just a game review. We are not concerned with how many out of five stars, or any numbers from 0 to 10, or whether or not a game is "fun" (whatever *that* means), or aiding in the consumer decision of whether or not to buy a game.

Critical analysis does not just mean a list of things that are wrong with the game. The word "critical" in this context does not mean "fault-finding" but rather a thorough and unbiased look at the game.

Critical analysis is useful when discussing or comparing games. You can say "I like the card game *Bang!* because it's fun" but that does not help us as designers to learn *why* it is fun. We must look at the parts of games and how they interact in order to understand how each part relates to the play experience.

Critical analysis is also useful when examining our own works in progress. For a game that you're working on, how do you know what to add or remove to make it better?

There are many ways to critically analyze a game, but I offer a three-step process:

1.  Describe the game's formal elements. Do not interpret at this point, simply state what is there.

2.  Describe the results of the formal elements when put in motion. How do the different elements interact? What is the play of the game like? Is it effective?

3.  Try to understand why the designer chose those elements and not others. Why this particular player structure, and why that set of resources? What would have happened if the designer had chosen differently?


Some questions to ask yourself during a critical analysis at various stages:

-   What challenges do the players face? What actions can players take to overcome those challenges?

-   How do players affect each other?

-   Is the game perceived by the players as fair? (Note that it may or may not *actually* be fair. Perception and reality often differ.)

-   Is the game replayable? Are there multiple paths to victory, varied start positions, or optional rules that cause the experience to be different each time?

-   What is the game's intended audience? Is the game appropriate for that audience?

-   What is the "core" of the game — the one thing you do over and over that represents the main "fun" part?


## Lessons Learned

We covered a lot of content today. The main takeaways I offer:

-   Games are systems.

-   Understanding a game is much easier if you have played it.

-   Analyzing a game requires looking at all of the game's working parts, and figuring out how they fit together and how a play experience arises from them.

-   Designing a game requires the creation of all of the game's parts. If you haven't defined the formal elements of your game in some way, then you don't really have a game… you just have the seed of an idea. This is fine, but to make it into a *game* you must actually design it.


## Homeplay

It was brought to my attention that I have been using the word "homeplay" to refer to the reading, and that reading is not play no matter how I dress it up. This criticism is valid; normally in my classroom courses I use "homeplay" to refer to actual game design assignments and not readings, and I mixed the terms up here. I will make an attempt to avoid this confusion in the future, because I believe that trying to treat learning as an inherently Not-Fun activity (as evidenced by the need to use fancy fun-sounding words to describe it) is damaging to our collective long-term well being. As we will see when we get into flow theory, the reality is actually the opposite.

With that said, here is an activity that I hope you will find fun. It is based off of Challenge 2-5 in the *Challenges* text, with some minor changes just to keep you on your toes.

Here's how it works. First, choose your difficulty level based on your previous experience with game design. Skiiers may find this familiar:

![Different Difficulty Symbols](images/level_3_skiing_symbols.pdf)

Here is your challenge:

Most war-themed games have an objective of either territorial control or capture/destroy (as described earlier). For this challenge, you'll be pushing beyond these traditional boundaries. You should design a non-digital game that includes the following:

### Easier

![Green Circle](images/green_circle.pdf)

The theme must relate to **World War I**. The primary objective of players cannot be territorial control, or capture/destroy.

### More Difficult

![Blue Square](images/blue_square.pdf)

You cannot use territorial control or capture/destroy as game dynamics. That is, your game is not allowed to contain the concepts of territory or death in any form.

### Most Difficult

![Black Diamond](images/black_diamond.pdf)

As above, and the players may not engage in direct conflict, only indirect.

### Note

I have created three new areas on the [forums](http://gamedesignconcepts.aceboard.com/) (one for each difficulty level). Post your game rules in the appropriate forum by **Thursday, July 9, noon GMT**. You are encouraged to post earlier if possible.

Then, after you have posted, **read at least two other posts from your difficulty level** and offer a constructive analysis and critique. If you are at blue-square or black-diamond difficulty, **also read at least two other posts from the difficulty level immediately below yours** and offer the benefit of your experience to those who you could mentor. Try to choose posts that have no responses already, so that everyone can get at least some feedback. Also complete this by Thursday, noon GMT.

## A Note About Research…

Note that you may have to do some actual research to complete this project (even if only looking to Wikipedia for inspiration). This is typical of much game design in the field. Many laypersons imagine game designers as these people that just sit and think at their desk all day, then eventually stand up and proclaim, *"I have this Great Idea for a game! Ninjas… and lasers… in space! Go forth and build it, my army of programmer and art lackeys. I shall sit here now until I come up with another Great Idea, while collecting royalties from my last five ideas."* This is not even close to reality. A great deal of design is the details: defining the rules, certainly, but also doing research to make sure that the rules fit the constraints and are appropriate for the project.

## A Note About IP Law…

At this point, some of you may be thinking that by posting your game to the forum, you run the risk that someone will Steal Your Great Idea. How can you protect yourself from the threat of someone taking your basic idea, turning it into a working, sellable game, and leaving you with nothing?

One of the participants of this course, Dan Rosenthal, has kindly [written an article that details the basics of IP (intellectual property) law as it pertains to games](http://gamedesignconcepts.pbworks.com/Legal-Issues-for-Game-Developers). The article admits to being US-centric, but the core idea (which is worth repeating here) should be sound no matter where you are:

Remember, ideas are: not trademarkable, not copyrightable, not trade secretable, and both difficult and prohibitively expensive to patent. You can't protect them anyway, and you shouldn't try — instead you should try to come up with new ones, and start working on the good ones.  Don't freak out when you see things like Game Jams, or this course and think "Ian says I should post my work to the discussion forum, but I came up with a Great Idea™ and I don't want other people to steal it." Ideas are commonplace in games, and the value of your idea is nothing compared to the value of the implementation of that idea, your expertise and hard work in developing it into something that's going to make you real money. But most importantly, our industry is very lateral, very tight-knit, very collaborative. You'll find people sharing their ideas at GDC, doing collaborative projects between studios, or using inspiration from one game's mechanics to improve another. Don't fight it. That's the way things work, and by embracing that open atmosphere, you'll be far better off.

