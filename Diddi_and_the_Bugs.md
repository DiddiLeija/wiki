# Diddi and the Bugs (videogame)

_Last updated: December 9th, 2022._

**Diddi and the Bugs** is the name of the first videogame from the _Diddi Games Collection_, a collection
of games about [Diddi](Diddi).

## Product info

| Category | Information |
|---|---|
| Full name | Diddi and the Bugs |
| Author | Diego Ramirez |
| First release date | 25 November 2021 (first **former** release); 03 January 2022 (first **stable** release) |
| Latest stable version | 3.0.1 |
| Download page | ["Diddi and the bugs" at itch.io](https://diddileija.itch.io/diddi-and-the-bugs) |

## Plot

_Sourced from the project's [README](https://github.com/DiddiLeija/diddi-and-the-bugs/blob/main/README.md#introduction)._

> The Earth is under invasion. A fleet of giant bugs, bacteria, and viruses are
> outside of the planet.
>
> In the meantime, Diddi was developing a secret spacecraft. When his frineds told him of
> the invasion, he decided to visit the brilliant Dr. Chuck (a scientist, and also
> an old friend of Diddi). The doctor gave him the **L1-F3** experimental serum, that kills anything
> alive. That should destroy those bugs...
>
> To ensure that those bugs will be destroyed, Diddi modified his spacecraft to convert it into a
> starfighter that energizes the serum and shoot it. Then, he named the starfighter **Willpower**.
> Suddendly, the Willpower goes outside of the planet, to start the fight...

## Gameplay

The game starts with [Diddi](Diddi) riding his [new starfighter, the "Willpower"](Willpower). The goal
is to destroy 200 bugs (which invaded the Earth's atmosphere). If those bugs are destroyed, the game ends.

As a secondary goal, the users are challenged to get the highest score as possible. To do so, they have to
destroy some "space trash" that spawns with the bugs. Also, since the 2.x releases, there's a giant bug known
as "The Monster" (which is not counted with the 200 bugs), that can give an important amount of extra points.

## Development story

### Early development - Submission to GameOff

Initially, the game started as a project for [GameOff 2021](https://itch.io/jam/game-off-2021).

> That's a nice story to tell.
>
> I have a friend \[...\].
> I was chatting with \[her\], while I was stuck with the GameOff theme ("bug").
> 
> And she came with a fresh idea from a non-exhausted mind: a doctor with a starship that kills "bugs".
> At first, I thought it was too bare, but then noticed it was a great idea.
>
> Also, that idea matched with a story I planned in the past (see the 3rth answer).
> So everything connected, and then I started to develop my game!
> 
> ~ @DiddiLeija (quoted from a post in [DiddiLeija's Discord Server](https://discord.gg/DfrHxT9ENy))

<!--

Legacy quote (let's keep it for its sentimental value)...

> When the jam's theme was exposed ("BUG"), I was a bit confused. I just took my computer, and created
> a weird draft, but I dropped it fastly. Then, a few days later, I was chatting
> with a girl that's a great friend of mine, and told her about my plans to join the GameOff. I showed her
> the theme, and then she replied: "I'm thinking about a doctor who uses a laser to destroy viruses or something
> like that". Then, I said "Something like a space-themed shooter with bugs?". "Yes", she replied. After that, the idea was born.
>
> To be honest, the whole _Diddi and the Bugs_ game would not be possible without my friend's fresh idea.
> It was something spontaneous, and then it became something real.
>
> ~ @DiddiLeija

-->

At November 1st, 2021, when the jam started, the design part of the game started. The first idea was to use
[Pygame](https://pygame.org), and actually the game started with Pygame stuff. But then, the game switched
to [Pyxel](https://github.com/kitao/pyxel), that modeled the retro style of the final game.

At November 25, 2021, the first functional shot of the game was ready. A few days later, the first distribution
of **Diddi and the bugs** was ready at [itch.io](https://diddileija.itch.io/diddi-and-the-bugs). It didn't have
any tags or anything, it was just a Python file and a resource file (the game was later packaged and distributed
for specific environments).

After the jam ended, the game ranked 278th from 526 submissions. Not an extraordinary position, though.

> After 2 months of working, coding, rating and fixing, the end of the event has just come.
> Today, they published the results (see [here](https://itch.io/jam/game-off-2021/results)). I know, my game
> is not on the first pages (he he)… It ranked 278th. Only 7 people rated. But I don’t feel bad – there were
> 530 entries on the jam :p
>
> ~ @DiddiLeija ([see original post](https://diddileija.github.io/diary/2022-01-03))

### 1.x series

After that, the first "stable" release (1.0.0) was published. It was only an unmodified version of the game,
exactly the same than the jam's version.

Then, Ramirez started to look for inputs, and followed by new contributors, he polished the game and removed
some issues in two other minor releases, 1.1.0 and 1.2.0.

### 2.x series

Later, Ramirez started the 2.x major series. The 2.0.0 release made several changes, and officially
deprecated the 1.x series, to start a new series of Diddi and The Bugs.

One of the main changes was the addition of a "messages bar", a small space below the screen to show notifications. It became
the first bridge between the user and [Diddi](Diddi) (before this release, he was only mentioned as the spaceship's pilot). Now
the users could receive small messages and alerts from the pilot, but also from "the system" (to notificate higher changes).
This update also included improved features, and also some new "easter eggs", like a hard-to-find creature and secret messages.

Another 2.x release, named 2.0.1, updated dependencies and improved the community stuff.

### 3.x series

A new series (3.x) added a brand-new look to the game, with some appearance features.

The 3.0.0 release added stars to the game, enforcing the space theme. They have random speed and position, so they provide a more
natural aspect. This idea was proposed and developed at Ramirez's Discord server, before its introduction to the codebase.
Another major feature is the main menu, that welcomes the users instead of starting the game directly. The available options are
1\) starting the game and 2) a credits sequence. This credits sequence only provides a link to a list of credits, available at GitHub.
This feat was also proposed on Discord.

A few months later, bugfix version 3.0.1 made a slight change that finally enabled web support, using Pyxel's WASM support. The main
fix that achieved this goal was found accidentally, during the development of the [Abandon the ship!](Abandon_the_Ship) game, and
was implemented a few weeks after the end of that development.

### Future

The current plan is to keep maintaining the 3.x series.
