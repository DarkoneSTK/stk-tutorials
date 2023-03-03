---
title:  SuperTuxKart
subtitle: Tips & Tricks
release: v0.1 03/03/2023
author: by darkone, v0.1
documentclass: book
---

---

\setupcombinedlist[content][list={chapter,section},alternative=c]
\placecontent

---

Here are some advices to optimize your performances and your game with SuperTuxKart. These informations, coming from my experience, are not necessarily exhaustive but may help you to progress. Go to the [official STK website](https://supertuxkart.net/) to discover the game before starting this tutorial.

To improve this document, you can contact me ([darkone-stk@gmail.com](mailto:darkone-stk@gmail.com)) or propose an issue / request in the [github repository](https://github.com/DarkoneSTK/stk-tutorials).

# Improve your time

You will be told that **practice and experience are the key**. This is true. However, the best players follow some important rules.

## Basic rules for effective driving

- **Take the shortest path[^path].** Between the inside and outside of a turn, the difference in distance and time is significant. When multiplied by all the turns, it makes a BIG difference. So it is always important to cut as short as possible. However, there are a few reasons to deviate from the rule:
  - Swerving to get a nitro (especially a big one).
  - Swerving to get a throttle.
  - Manoeuvre to protect yourself from an opponent.
  - Completing a skid.
- **Mastering the art of skidding.** There is a small (yellow) and a large (red) skid. As soon as the desired colour appears, you must release the key as soon as possible, then start skidding again (prolonging the skid is useless).
  - The ideal is to **make as many skids as possible**, up to red if possible, while keeping the shortest path. Anticipation is something you acquire with experience.
  - When stopped, **two yellow skids** are more effective than one red to accelerate to the optimum speed, except with nitro (one yellow will be sufficient) or if the geometry of the track requires another strategy.
- **Knowing and mastering shortcuts.** They allow you to reduce the length of the track even more. The difficulty of the shortcut must be balanced against its gain... for a record, you will take more risks than for a race with competitors. See _"Knowing where the checkpoints are"_ a little further on to find out how to find the shortcuts. And to train, nothing better than the USC tracks of the excellent [mimiz tracks](https://stk.kimden.online/records/mimiz.html).
- **Catch as much nitro as possible.** Nitros are very important to move faster and catch up. If there is a choice, prefer nitros to gifts, unless you are last and the probability of getting zippers is high.
- **Use nitro at the right moment.** I.e. when it is still possible to accelerate. So when you are not going fast or when you are slowing down (listen to the noise of the engine). A good reflex is to use the nitro during a red skid (to maintain the speed of the kart) and not to use the nitro during a red skid.
- **Use zipper[^zipper] at the right time.** It is a shame to cancel the zipper effect prematurely with a sharp turn or an obstacle. It is better to choose a straight line or an easy part of the track to take advantage of the zipper.

[^path]: The "path" is the actual track of the kart.
[^zipper]: Acceleration option (yellow arrow) obtained in a gift.

## Knowing the tracks

- **Knowing where the "checkpoints[^checkpoint]" are.** This allows you to find shortcuts and to know at what point you can cut certain turns, to optimize the path. You can make checkpoints visible by setting `artist_debug_mode` to `true` in `config.xml`.
- **Choose the right kart for the track.** For record setting, a heavy kart is almost always the right choice. But for classic races it's better to have more maneuverable karts on twisty and complicated tracks.

[^checkpoint]: Checkpoints are the set of areas that must be passed to complete a lap. If there are few checkpoints, it is possible to find shortcuts between them to optimize your path.

## Other important parameters

- **Have a good hardware configuration.** A good gamer keyboard (with a very fast response time), a powerful computer with an impressive graphics card, as well as a fibre internet connection and a fast wired network (for online play) are all assets to avoid being limited by the hardware. You can however play with a lesser configuration (I personally have an old desktop laptop with a 4G connection) but it is sometimes a bit frustrating to lose because of hardware slowdowns.
- **Minimise visual effects.** Visual effects consume a lot of CPU/GPU. To optimize response times (especially on a computer with limited hardware), keep the visual effects options to a minimum (or close to it).
- **Free up resources.** Close CPU and RAM consuming software. But also everything that consumes network and internet (video streaming, etc.). The famous "lag" is often due to network disturbances.

## Less important tips

- **Turning off the music** (or lowering the volume) allows you to concentrate better on the game and to hear the important sounds (but you should leave the sound effects on!).

# Interacting with others

- **Break away from the crowd at all costs.** At the beginning of the race, you are caught up in the "crowd" of karts with a great chance of being pushed, blown up or braked. The ideal is to quickly get away from the crowd without being blown up, which is easier with a light kart despite its limited speed afterwards. Once you are ahead of everyone else, the way is clear.
- **Avoid being behind another kart (normal mode).** When there are presents everywhere and many karts, being right behind another kart carries a high risk of being slowed down by a cake, a ball, a chewing gum, a fag, etc.
- **Take advantage of the suction effect (time trial).** In "time trial" mode, however, you can take advantage of the suction effect of other karts by getting in behind them. This is particularly noticeable on racetracks where two good players going at roughly the same speed often yo-yo between 1st and 2nd.
- **Prefer a manageable kart if it is crowded.** A light kart will have the advantage of being able to get around better and to restart faster in case of untimely stops. When there are a lot of people, this is a real advantage, as there is more chance of being slowed down by other people's gifts.
- **Alternative: start last and take gift-zippers.** This is a risky technique, but it can pay off, as the gifts of the last ones are likely to have zippers that allow you to quickly catch up with and pass your competitors.
- **Use gum protection at the right time.** This protection can be activated just before the arrival of a basketball, a new gift or when passing a competitor... it is important to activate it when the probability of it being useful is high.
- **Practice aiming with the balls.** It's not easy (and I admit it's not my strong point) but being able to aim well with the balls is an asset. The competitor's kart must be just in front and if it is far away, don't turn too much (or anticipate its movement).

# Reflexes to have

When you are a beginner, you may not know some important tips that should become reflexes.

## Basic tips

- **Use the start zipper.** At the start, there are three beats "Ready!", "Set!", "Go!". Pressing the throttle at the beginning of "Set!" allows you to have a zipper at the start.
- **Remove a bomb.** The gum and the faggot allow you to remove a bomb. But it is also possible to touch a competitor to pass on the bomb.
- **Remove a parachute.** To do this you have to loot (brake hard) and then restart. In most cases this is more beneficial than continuing to accelerate.
- **Use the traction line.** When there is a competitor not too far ahead, the traction line allows you to hook onto him to accelerate and often overtake him.
- **Send a cake at the right time.** Cakes work when the competitor is relatively close and his speed is not too different from yours.
- **Leave the basketball to the chaser.** When you are in first place with a fairly close chaser and a basketball is coming, slow down and let yourself be passed to avoid the ball.

## Advanced tips

- **Don't look at your kart.** Even if it is beautiful. Instead, look at the circuit and everything that is happening in front of the kart! This will optimize the race by anticipating the turns and obstacles (especially the gums) much better.
- **Remove a bomb by launching a "rescue" at the right moment.** In absolute terms, you won't lose more time by doing this, but if you're about to explode, you might as well do it before an acceleration as just after.
- **Skidding + turning without acceleration.** Temporarily letting go of the throttle and then skidding allows you to better initiate a sharp turn. A good reflex to have to optimise the path travelled by avoiding ending up on the outside of the bend, or even in the ravine.
- **Optimise the path thanks to the chewing gum bubble.** It allows you to pass over the bananas without suffering their fate. Do not hesitate to pass over the banana on the inside of a bend to shorten the path.

# Mistakes to avoid

- **Getting hit.** Fags slow down a lot and for a long time. It is important to stay away from anyone who pulls one out. It is possible to anticipate the appearance of fags by looking at the list of opponents on the left.
- **Confusing balls and gifts.** On some circuits, you can confuse the balls with the presents. Beware of the sound of a ball and know where the gifts are.
- **Spoil a nitro during acceleration.** Using a nitro right after a zipper, throttle or big skid is not effective. As we have seen, nitro has more effect when the kart slows down.
- **Insist on skids.** Doing a huge 30-second skid is useless. As soon as the light turns red, the gain is maximal, so you should release the skid button as soon as possible.

# Training

- **Race online with (a little) stronger than you.** Even though it is frustrating to lose, you make better progress with competitors of the same level or a little stronger. With beginners, be nice and advise them on this document ;). A much stronger competitor will quickly outrun you and won't teach you much until you have his reflexes.
- **Race offline with 19 bots.** Offline race bots are better than online bots, although with experience they will quickly become easy competitors to beat. To practice driving in a crowd, choose a very short circuit with lots of prizes and as many competitors as possible.
- **Study the records and challenges on youtube.** Many passionate players publish their races and records on the net. Watching and analysing them is very beneficial for learning.
- **Participate in competitions, grand prizes and other events.** A good entry point for this is [the website made by kimden](https://stk.kimden.online) which offers meetings and compiles records of the "Francfurt" circuits.
- **Download record files from discord.** In the same way, one can download record files and practice playing against these records.
- **Download a lot of tracks.** Practising on a lot of different tracks allows you to diversify and improve your game.
- **Know how to take the nitro between the two bananas.** Often there is a big nitro between two bananas. This requires a little deviation to catch it without slowing down too much.

# Exploiting side effects (or not)

- **Missing checkpoints.** On some tracks, it is possible to optimise time by turning around to pass all the checkpoints more quickly. In my opinion, this is more of a design error (or a possibility intended by the designer, but it is rare) than a possibility of cheating, because if it were, any shortcut would also be cheating.

# Advanced configuration

- **Minimise visual effects.** Go to the game configuration and set the visual effects as low as possible, except FPS if possible. There are other settings in the configuration files, for example to change viewing angles, which can be useful to optimize gameplay.
- **Compile an optimised binary.** For those compiling the game, refer to the online documentation to optimise the binary for your hardware configuration.
