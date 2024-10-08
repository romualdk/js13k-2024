# js13k-2024
Game for js13k 2024 Triskaidekaphobia

https://js13kgames.com/

https://medium.com/js13kgames/js13kgames-2024-start-and-theme-announcement-5d734f77da68

# Description

Use cards to attack enemy and defense yourself.

Pick a card to collect attack or defense points.
If you will collect 13 or more points in hand you lose your cards.

There are point cards from 1 to 11.
13th card is a Death card.
12th card is a Shamrock card. It will protect you from Death card.

You are granted one Shamrock card at start.

Good luck and win with as many green bombs as you can.

![cover](https://github.com/romualdk/js13k-2024/blob/cd4d36f68f898a5d6ebd381eaa16dd15f6c4607e/media/Cover%20800x500.png?raw=true)

# To do #

* DONE Change icons (swords, shield, shamrock, death, app icon to SVG)
* DONE App icon as SVG
* DONE Hands icon as SVG
* DONE // Game context (screen) adjustments for mobile with correct aspect ratio
* DON'T BOTHER // If possible set the default context to 100% height and centered
* DONE // Add webmanifest
* DONE Enemy portrait
* DONE Enemy animation (floating and breathing)
* DONE Player portrait (Knight)
* DONE Info about CPU turn and player turn (get rid of highlight and add arrow with text)
* DONE Exp, Level up, progression through stages and different enemies
* DONE Vibrations

# Ideas

* Progress save in local storage
* Introduction window with game rules and objective (force confirmation to enable sound effects)

* Enemy and Player texts messages
* Enemy Boss Shakhaar
* Enemy Boss Lilith

* Enemy face expressions (surpries when got hit, angdy when low health, dead)
* Player face expressions

# Known issues #

* FIXED // Sometimes (pretty often) after some action (dunno when but probably combination of turn change and action bar action) it is a CPU turn but he doesn't do anything. Probably something with timeouts and action flags.
* FIXED // Sometimes defense card have incorrect pattern color (probably Shamrock card)

* FIXED // Incorrect background - change to SVG image instead of gradient
// SVG image was not necessary. It was a matter of incorrect body size
* FIXED // Incorrect size on mobile - adjust width and height - currently only height is checked
* FIXED No icons (death, shield) on mobile and mac - change to SVG shapes included in game
* FIXED // Action timer is not working in Safar web browser on Mac OS - find how to handle / change to regular JS animation or just get rid of the timer

* Safari - stops after card is selected - the card is not going into the spot. Probably something with the animations

# Tools #

* https://minify-js.com/

# Credits #

Sounds made with https://killedbyapixel.github.io/ZzFX/
