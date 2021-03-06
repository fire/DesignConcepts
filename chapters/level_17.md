# User Interfaces

*Originally posted August 24, 2009*

If you have made it to this point, your game is hopefully coming along nicely and you are approaching the final stages of design. You may still have temptations to mess around with the mechanics, especially given the short time period allotted for the Design Project, but at this point I want you to settle on something that is at least "good enough" so that you can experience the later stages of design.

Once your mechanics are complete and the game is playable, balanced, and meets your design goals, the last thing to do is figure out how to construct the final version. This is not simply a matter of drawing up some art for your cards and board and sending it off to the printer. There are some considerations to be made concerning the user interface of your game, and those considerations are what we will talk about today.

## Readings / Viewings

Read the following:

-   *Challenges for Game Designers*, Chapter 16 (Creating a User Interface)

-   [*Cooperation and Engagement*](http://www.youtube.com/watch?v=cdTVcFo2EQw), a Google tech talk by game designer Matt Leacock. This video actually ties together a lot of the concepts we've talked about in this course, from difficulty levels and flow states to the iterative process to game narrative, and it should serve to solidify those concepts using the concrete example of *Pandemic*, one of the best-selling hobby games of last year. But what I really want you to pay attention to is how Matt presents his iterative work on the design of the game components themselves, such as how he determined the shape, orientation and color of the cards. The actual talk is only 30 minutes long, although there are an extra 20 minutes at the end from audience Q&A.


## What is a User Interface?

Normally, we think of the term **user interface** (or **UI**) as it applies to software applications. This term refers to the parts of the software that interact directly with a human. It covers things like what options are available to the user at any given time, how those options are presented on the computer screen, as well as the physical interactions (mouse/keyboard, game pad, etc.). In general, with video games, the UI is divided into two parts: the **input** (that is, how the player gives commands to the game) and **output** (how the game communicates the results of those actions and other aspects of the game state to the player).

What if you're making a non-digital game? Is there a UI? Of course there is – and if anything, it is more important to get it right, since you don't have a computer automatically enforcing the game rules. If the players don't understand the rules of a non-digital game, the only recourse is often to stop playing. As the game's designer, the last thing you want is for your brilliant mechanics and carefully-crafted play experience to be ruined because of an interface issue.

In non-digital games, the UI is the game components themselves, since they are both how you interact with the game (through manipulating the game bits) and receive feedback (by viewing the game state). So what we are really talking about today is designing your final components.

## User Interface Design

What makes one UI better than another? We generally talk of two things:

-   Ease-of-use. If you already know what you want to do, how fast and easy is it to perform your desired task correctly?

-   Ease-of-learning. If you are new to the game, how easy is it to figure out what you are allowed to do and what information is available to you?


In practice, there is often a tradeoff between these two. For example, on computers, the presence of special "hotkeys" (Shift/Alt/Ctrl/Cmd key combinations and the like) saves time by making it fast and easy to perform common tasks like saving a file or switching between applications. But if these are the *only* way to perform that task (as is the case with some older word processors that lacked menus), it makes the applications difficult to learn for the first time.

In board games, you often see this tradeoff with how information is presented. Charts, tables, keywords, special symbols and icons – all of these make it much easier for an experienced player to get a quick summary of the game state, but they can be confusing and intimidating to the novice player who does not know what these things mean. The alternative, writing everything out in longhand, makes it much easier for a new player to see immediately what everything does… but it also makes the game take longer for players who already know the rules and do not need them repeated in full on every card.

Sometimes you can include both. Modern software applications include hotkeys *and* menu items, and some even have a "beginner" mode that hides advanced functionality to keep the menus simple, making the software much easier to learn. Card games like *Magic: the Gathering* include keywords, but then explain those keywords in parentheses for players who do not know what the keyword means.

Magic: The Gathering Cards
![Magic Cards](images/level_17_magic_cards.jpg)

Look at all the mechanics in your game, and what players must do in order to follow them. Are there any cases where your wording could be clearer for first-time players? Are there situations where experienced players of your game feel like they are doing excessive book-keeping or note-taking, or performing multiple automatic steps, where it would be possible to streamline the experience?

## The Two Models of Usability

In usability for computer applications, there are two related concepts: the **user model** and the **program model**. The user model is how the user (i.e. the player) thinks that things should work. The program model is how the software *actually* works. (In non-digital games, you can think of the "program model" as the actual rules of the game as intended by the designer, and the user model is what the players *think* the rules are.)

Here's the thing. **The program model is always right.** If the user model and program model match one another, there is no problem. If the two are different, the player is going to do something, they'll expect one thing to happen, but another thing happens instead. With computer games, this leads to frustration, and reviewers will say the game has "poor play control" (often without fully understanding why).

In board games, if the player model and the "program" model are different, the players will just play the game incorrectly. Sometimes, this means the players will have a suboptimal experience, because some aspects of the game will feel unbalanced. Other times, the players will have a perfectly good time, but when they later play the game with *other* players who are playing the game the "right" way there will be rules arguments.

## Changing the User Model

It is common to see a user/program model mismatch during playtesting. Here is what it looks like: with every playtest group, the players always do one particular thing *wrong* the first time around. This suggests an ease-of-learning problem.

A more serious case is an ease-of-use problem with the UI of your game. It looks like this: one or more players accidentally do something wrong in the rules. You point it out to them, and they correct their behavior. But then they forget, and they *do it wrong again* on the next turn. And the next. And the next. And your players apologize to you for continuing to get it wrong, and they feel like idiots.

In cases like this, it would be ideal to change the user model. That is, you'd like to change your players' expectations or actions in order to match the "correct" model of the game itself. Unfortunately, in practice, this is effectively impossible to do. People are creatures of habit. We build up elaborate mental models of the world around us, and we rely on those models greatly. Changing a model is a slow process that requires great effort on the part of a person, and most people are not going to put that kind of effort into your game.

To illustrate this in my classroom courses, I tell the story of the design of a fighter jet. Once upon a time, the military was noticing that one particular type of aircraft had a much higher-than-average number of accidental pilot ejections (that is, the pilot's ejection seat was activated when the pilot did not intend for that to happen). Given the cost of military aircraft, it gets very expensive when something like this happens, so they had a lot of engineers study the problem to figure out why the seat was ejecting, but no mechanical or electrical problems could be identified. Eventually, someone got the bright idea to look at the aircraft that the accidentally-ejected pilots had trained on. It turned out that in all cases, they had trained on an aircraft where the positions of the throttle and the ejection seat controls were reversed! So, when the pilots got in this new aircraft, they had already formed a mental model of where all the controls were, and no amount of training on the new aircraft could change it.

## Identifying the User Model

Okay, so we can't change the user model. That means if you find a mismatch between the user model and the game, you should change the game's interface so that it either conforms to the user model, or change the interface so that it is different enough that it triggers a *different* user model. But how do you know what the user model is in the first place?

Thankfully, this is pretty easy to do. The easiest way is to ask. Find people who play games similar to the one you're making. Set up a situation for them, and ask them how they think the game would work (or how they would accomplish some task, or whatever you're trying to figure out) if they had to guess. Once you ask a few people, a clear consensus will emerge pretty quickly.

Another pretty easy way to identify the user model is to playtest. Watch when people are playing the game, and make note when they do something wrong.

Lastly, if your game's model is nontrivial, it is probably wrong. Other things being equal, people will assume simplicity.

## Whose Responsibility Is It, Anyway?

You might wonder, in some cases, if usability issues are really your problem as the game designer. After all, if you create a good game and you give a complete and correct set of rules, isn't it the responsibility of the players to actually, you know, *read the rules and follow them*? If they play your game wrong, how is that *your* fault? Some people are just stupid or careless, and certainly the brilliant designer should not be held accountable for these people. Right?

Well, first off, it may not be the player's fault. They might have been taught by someone else. They might be in a distracting environment, so they can't give the rules their undivided attention. They might not *have* the rules; maybe they purchased the game second-hand and the rules were missing. The language the rules were written in might not be their first language. There are any number of reasons why a perfectly intelligent and rational person might have difficulty. So, don't just write these people off as not worth your time.

Second, most usability failures *feel* like a mistake on the part of the user (player), but they are *actually* a UI issue that could be fixed. Consider: if your game were easier to use, it wouldn't *let* the players make mistakes. As the designer, take responsibility for the usability of your game, and you will find that players are learning it faster, making fewer mistakes, and generally having a better time.

## Building a Good UI

Now that we know how to identify a bad UI, how do you design a good one? In general, a good UI does two things:

-   It does what the user thinks it will do; and

-   It gives the user feedback so they *know* what it did.

If the game doesn't do what the player thinks it will, that is a problem with the user model not matching the game model, as we've already discussed. But there is one other aspect to designing the UI: giving the player immediate feedback so that they know what they did is correct (and, in the unlikely event that they did something wrong, they will immediately *see* that it is wrong and understand why).

Here is another way of looking at what a good UI does:

-   Make it easy to do things correctly; and

-   Make it hard to do things the wrong way.

Here's an example: suppose you have a board game with several kinds of tokens. Maybe you have one set of markers that keeps track of player score, using a scoring track around the edge of the board. Maybe the game board has a map divided into provinces, and players have military units that are placed in the provinces. Maybe there's also a global market with goods for purchase and sale, and a separate track for each trade good that lists its current price.

It would be easy to get all these different game bits confused. But what if each token was a different size and shape, and each space on the board matched the shape of the token that was used there? All of a sudden, it becomes a lot easier to figure out that the small square tokens must go on the small squares of the scoring track, the star-shaped goods markers go on the star shapes of the trade good price tracks, and so on.

How will the players remember how to adjust the trade good values on each track? A rules summary printed on the board right next to the tracks makes it easy to remember. What about how combat is resolved? Unit strengths, stats and abilities can be printed on the military units themselves, and the remaining rules can either be summarized on the board or on a quick-reference card or other player aid given to each player at the start of the game.

As you go about designing the UI, here is a process you can follow:

-   First, make a list of tasks that players need to accomplish in the game. Make it easy to do those tasks.

-   Second, pay special attention to the most *common* tasks, the ones that players are doing over and over. Difficulty and complexity of a task should be in proportion to how rarely it is used.

-   Iterate through playtesting.

## Use of Color

Color is a great way to convey information to players if done well. It is efficient: color takes up no additional space on a game component, because the component is already there; all you're doing is coloring it. Here are a few quick-and-dirty tips for thinking about color use in your game:

-   The colors that normal human eyes detect most easily are red and green, followed by blue. These colors will tend to stand out more… which can be good for drawing attention, but bad for eye strain if you use fully-saturated bright colors.

-   Don't rely on color alone; a nontrivial portion of your audience has some degree of colorblindness. Vary the intensity of colors as well (so that if, for example, photographed with a black-and-white camera, you would still see a difference), and use different shapes in addition to different colors. By having things differentiated in multiple ways (different shape, different color, etc.) it makes it *really obvious* that those things are distinct from each other.

-   Use color consistently. If you use one color for several things in a game, those things should be related. Some board games I've played, for example, have (say) five different resources, and each one has a color; but each player *also* has a color, and some player colors and resource colors are the same, even though there is no relationship between the green player and green resources. This kind of thing can confuse players who might think that a particular resource is owned by their opponent when it isn't.

## More UI Design Tips

In no particular order:

-   Automate or eliminate tasks that don't involve interesting decisions, if possible. Every click or keypress in a video game, or die-roll or card flip in a board game, should involve the player doing something that is interesting to them. If the player first has to do a bunch of upkeep tasks just to have the privilege of making interesting decisions later, see what you can do to streamline the boring stuff.

-   Use visual metaphors. They make it obvious what something represents. If your players control a bunch of pieces that represent people, using people-shaped pawns is clearer than using wooden cubes. Compare the pawn images below. Each has a very different effect on how the player views it.

Different Pawn Representations
![Wood Pawns](images/level_17_wood_pawns.jpg)

-   Likewise, if you use icons in the game to represent certain abilities, choose icons that look like the concept they're representing (if you can).

-   Be consistent with similar games. In an RPG, red hearts probably mean life or hit points, while blue drops probably represent mana or magic power. Why? Because that's how everyone else does it, and your players will assume by default that you do it that way too.

-   **Don't** just say "well, this is confusing, so we'll explain it in the manual." Remember, your players may not have the manual and they may not read it. Try to make your UI intuitive enough that your game doesn't even *need* a manual.

## Lessons Learned

Giving your game a good UI is a skill that is separate from core systems design, but it is an important skill to learn. Keep in mind that, as with most things in this course, UI design is a huge field and we are only going to cover the very basics. There are entire courses (and even college majors) devoted specifically to UI, not to mention hundreds of books, and I encourage you to seek out these resources after this course is over.

## Further Reading

There are many great books on UI design. If this topic interests you, I would recommend Donald Norman's *Design of Everyday Things*, which gets into the details of how the design of something as simple as a door or a stove can go horribly wrong… with lessons that can be applied directly to games, both digital and non. Also, for ways to show game data to players in efficient and innovative ways, I would recommend any of Edward Tufte's books: *The Visual Display of Quantitative Information*, *Envisioning Information*, and *Visual Explanations*.

If you are primarily interested in video games, there are so many great sources on computer UI that it would be hard to list them all here. If you have any personal favorites, leave as a comment on this blog post, or post on Twitter using \#GDCU.

## Homeplay

The ongoing homeplay from a week ago was to arrange for a blindtest session, which should be completed on or before this Thursday (August 27). Continue working on this if you have not completed it already.

Your other task, also before this Thursday, is to critically analyze your game **with respect to user interface**. Think about your playtests so far, and what rules your players have had trouble with. What kinds of components or player aids would make it easier for them to remember?

Come up with a **user interface plan** for the final version of your game. This plan should involve the following:

-   A complete list of all game components that will be included in the final game.

-   For each component, a detailed description of what you are planning to use. If you have, say, "one pawn to represent each player", how many pawns are included? What colors will they be? What shapes? Will they be made of metal, plastic, wood, or something else?

-   If there are cards, describe a sample card. What information will be displayed on each card? Will the card be oriented as "portrait" or "landscape"? How will the information be laid out – where on the card will each item go? How will it be displayed – what colors, shapes, and keywords do you plan to use (if any)? If there are several *kinds* of cards, do this for each.

-   If there is a board, describe the layout of the board. As with cards, consider what information will be displayed on the board, how it is laid out, and how it is displayed.

-   If there are other components, give similar information to that listed here.

This list is mainly for your own reference, and the purpose is to make it as easy as possible for you to assemble your final game (which you will be doing this next week). The list also serves as a sanity check: do you have access to all the components you need? If you do not own some of them, think about how and where you plan to create or purchase them.

**Post your UI plan to the forums** no later than this Thursday (August 27), noon GMT.

By next Monday (August 31), **read and respond to at least three other posts at the same level as you**, giving preference to those that have not had any responses. By reading, it may give you some ideas to use on your own project. You may also be able to share some ideas you already have with others, helping them to improve their projects.

