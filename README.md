# Pre-work - *Memory Game*

**Musical Memory** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Nandana Suresh**

Time spent: **3** hours spent in total

Link to project: (https://glitch.com/edit/#!/speckled-zircon-net)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://media.giphy.com/media/F5fD8PXPrlpOCBRmxJ/giphy.gif)
![](https://media.giphy.com/media/FPusqyBru7snlzvLtV/giphy.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
   - https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
   - https://www.w3schools.com/jsref/jsref_push.asp
   
2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
   
   While creating this submission, I mainly encountered challenges within making sure that the syntax of my
   code was correct, especially in terms of JavaScript, as my experience with that langauge is quite limited. 
   For example, when I was editing the code so that the computer would randomly generate a solution pattern, 
   I ran into some trouble with the syntax for a for loop (which I used to populate the pattern array). I 
   quickly figured out, though, that though my implementation of it was mostly correct, the code was throwing
   errors due to the fact that I mistakenly defined the first expression in its parentheses as "int i = 0".
   Though this is the way that one would start a for loop in other languages, such as C++ and Java, JavaScript
   uses the "var" keyword instead when initializing variables. Thus, I changed that section of the code to
   "var i = 0", which ultimately worked in the way I expected it to. Furthermore, I wasn't so sure about what
   built-in functions JavaScript has in terms of processing and manipulating arrays. For challenges like these,
   I mainly overcame them by taking a few moments to carefully read through JavaScript's documentation, as well
   as other websites that are designed to teach people the basics of this language. In this way, I was able to
   resolve any syntactic problems I was running into, as well as learn more about how JavaScript works as a whole. 
  
  
3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
   
   Through this pre-work assignment, I was able to build a functional memory game, which utilizes sounds and
   colors to help users remember a particular pattern. This game is single-player, though, so I'm particularly
   interested in the work that would go behind implementing a multiplayer version of this game. For example,
   if I wanted to create a version of this game in which two players could connect to the same game and play it
   in a more competitive fashion, how could that be translated into code in terms of web development? I do know
   that in this instance, one would have to separately implement the frontend and backend portions of the game, 
   so what kinds of technologies are frequently used for this?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

   If I had a few more hours to work on this project, I would add more difficulty levels, each of which would
   contain different numbers of buttons which one can press, as well as patterns of different lengths. For 
   example, an "easy" difficulty might include three buttons, with a solution pattern that is six tones long. 
   Furthermore, a "medium" difficulty might include four buttons, with a solution pattern that is eight tones
   long, while a "hard" difficulty might include five buttons, with a solution pattern that is ten tones long. 
   Additionally, I would create another game mode in which the user can play, which is more geared towards
   learning how to play a particular song on an instrument such as the piano. In this game mode, I would include
   twelve buttons, one for each of the pitches represented by the chromatic scale. Each of these buttons would
   be labelled with the name of the musical note they correspond with (C, D#, G, etc.). Then, I would create a
   solution pattern that would play a simple, yet well-known song (such as "Mary Had a Little Lamb") on the
   buttons, essentially teaching the user how to play the song.
   


## License

    Copyright Nandana Suresh

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
