+++
title = "PbtA Cast Dice"
date = 2020-04-01T09:17:06-05:00
draft = false
description = ""
categories = ["Mechanics", "Cast"]
tags = [
  "Everything",
  "TTRPGs",
  "RPGs",
  "Dice",
  "PbtA",
  "Cast",
]
+++

In [Let Us Cast Dice](/posts/let-us-cast-dice/) I draft the Cast dice
mechanic with a lot of properties I want out of one. But it doesn't
work well for games Powered by the Apocalypse because it doesn't
support weak hits

Let's iterate and add change that

<!--more-->

## Design constraints

To keep the nice properties of the first draft we'll give ourselves
some design constraints

To maintain the property of:

* *accessibility*, no specialized dice, d6s only. Minimal
  math, only counting and comparison

* *speed*, single dice roll generally intrepretable without sorting
  the rolled dice

* *narrative Relevance*, keep the [fictional
  positioning](http://lumpley.com/index.php/anyway/thread/689) tools
  of Complexity and Difficulty and if possible, highlight them

* *scalable moves*, don't disrupt the possibility for moves to let
  players scale power in exchange for tougher rolls

Before covering everything in detail, here is a summary the Cast dice
mechanic in PbtA terms (see [Vincent Baker on how PbtA
works](https://lumpley.games/2019/12/30/powered-by-the-apocalypse-part-1)).

Every roll will have a Difficulty and Complexity determined by the
move and the fictional position. You'll have a relevant Ability
score. When you roll for a move build a pool of dice. Add Ability dice
equal to your ability, and Complexity dice equal to the Complexity.
Differentiate them by using a different color dice for each. Once
rolled, the ability dice may be one of three results - Hit,
Complication, or Miss. Rolled Ability dice that are greater or lesser
than each of the rolled Complexity dice are hits. Rolled Ability dice
that equal the highest or lowest of the rolled Complexity dice are
Complications. All other rolled Ability dice are misses.

The move Succeeds if there are enough Hits to match or exceed the
Difficulty. It's Complicated if there are not enough Hits but
the total of Hits and Complications matches or exceeds the
Difficulty. Otherwise it Fails.

## For example

You do the "Heal" move in which you have three ranks of relevant
abilities. The playgroup has determined that the Difficulty is two and
Complexity is four. You might grab three black Ability dice and four red
Complexity dice. You roll the whole handful.

Ability dice of {1, 4, 6} and complexity dice of {2, 4, 5, 5} is a success
because there are two Hits. Because there are two Ability dice (1 and
6) outside the bounds of the Complexity dice (2 and 5) which matches
the Difficulty of two

Ability dice of {2, 4, 6} with the same Complexity dice of {2, 4, 5, 5} is
Complicated because there is only one Hit (6) but adding the one
Complication (2) that matches the lowest of the Complexity dice
matches the Difficulty of two. Ability dice of {2, 5, 5, 5} against these
Complexity dice would also be Complicated because zero hits plus three
Complications exceeds the Difficulty of two

Ability dice of {1, 3, 4} or {3, 4, 5} or {3, 3, 3} all Fail against a
Complexity roll of {2, 4, 5, 5} because in none of these cases are
there enough Hits and Complications to match the Difficulty of two. In
the first case there is a single Hit (1) but nothing more, in the
second a single Complication (5), and in the third all Misses.

This clearly achieves some of the constraints. It's all d6s. Counting
and comparison are the only mathematical operations used and it keeps the
fictional positioning tools of complexity and difficulty.

What about the rest?

## Scalable moves

What I like about the design space of this mechanic is scalable
moves. That's what I want to keep

Here is a move that doesn't scale with ability

> ENDURE PHYSICAL SHOCK
>
> When you've been punched, shot, fall off a high ledge, or otherwise
> are physically hurt *endure physical shock*.
>
> * Difficulty is damage taken (specified by the weapon or GM)
> * Complexity is 1
> * Roll Tough
>
> No matter what the roll is mark exhaustion for each damage
> taken. Whenever exhaustion is marked as part of this move if exhaustion
> is greater than 5 mark a wound, greater than 11 mark a maiming, if
> greater than 17 you die.
>
> You also die if you get 6 wounds or are maimed 3 times without rest
>
> If it gets complicated the GM may choose 1:
>
> * Damage a piece of armor
> * Mark 2 more exhaustion
> * Lose track of an important item
> * etc.
>
> If you fail, the GM may choose 1 from the above, and one from below:
>
> * Destroy a piece of armor
> * Mark 5 more exhaustion
> * Permanently lose an important item
> * etc.

There is plenty of design space in moves like this given the
flexibility in the complications and failures lists, flexibility in
what stats the move asks you to track etc. but it doesn't scale with
the players abilities. As the player gets better at this, it just gets
easier to succeed. If it scaled players would be able to improve the
positive outcome in exchange for risk of failure and as their
abilities improved, they could push it farther and farther.

The version that scales is similar but with a choice

> ENDURE PHYSICAL SHOCK (2.0)
>
> When you've been punched, shot, fall off a high ledge, or otherwise
> are suddenly physically hurt *endure physical shock* and choose how
> much damage to shrug off.
>
> * Difficulty is damage taken (specified by the weapon or GM)
> * Complexity is 1 + the damage you shrug off
> * Roll Tough
>
> No matter what the roll is mark exhaustion for each damage not shrugged
> off. Whenever exhaustion is marked as part of this move if exhaustion
> is greater than 5 mark a wound, greater than 11 mark a maiming,
> greater than 17 you die.
>
> ... (everything else is the same)

In this version the player may press their luck and try for a better
result at the cost of an increased chance of failure. At higher
abilities this will make the characters harder to whittle away at with
small attacks as they can easily shrug them off, though even with a
high ability, there is always a chance of a complication or
failure. This also gives players in a desperate situation a long shot
which can create some very exciting moments and interesting
strategies

## Speed

So how fast is this to run at the table? It's hard to analyze but I
expect that the simplicity of the individual operations needed, and no
addition required will help. I've personally tried a lot of rolls and
it feels easy with a little practice. This absolutely needs putting
through the playtest ringer

## Probabilities

The [probability
curves](https://docs.google.com/spreadsheets/d/1pjkDFmOBqC1BPa6yQG8rjCFE3O9-h0l97jEb1FP2CUs/view)
for this look pretty good on paper but again it needs playtesting to
confirm.

If you are into it, throw some dice around and let me know how it
works out on Twitter [@jessebmiller](https://twitter.com/jessebmiller)
or in the [cast discord server](https://discord.gg/pCQ44h). I promise
I'll respond.

I'd love for designers to use this mechanic in their games and while
mechanics are not covered by Copyright, I'd ask that you attribute the
design to me. "Cast dice mechanic by Jesse B. Miller" or something
like that. If you do please let me know! I'll help spread the word.

*Thanks for reading!*