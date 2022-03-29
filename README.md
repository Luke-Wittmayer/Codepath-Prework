# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Luke Wittmayer**

Time spent: **4** hours spent in total

Link to project: https://glitch.com/edit/#!/irradiated-ringed-hunter

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Winning
![Success](https://user-images.githubusercontent.com/92394723/160332714-6a1edd5c-796c-4618-a591-17b4f46be0e7.gif)
Losing
![Failure](https://user-images.githubusercontent.com/92394723/160332745-8300a349-a1c4-4faf-a875-05367881a7af.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

To understand how to generate random numbers: https://www.w3schools.com/js/js_random.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

The two largest challenges I ran into were actually rather small and had easy solutions but I simply overlooked them while looking for what I thought would be more complicated errors. The first was trying to add tones to the 5th and 6th buttons. For some reason I kept getting a parser error when I entered in their tone frequency and I couldn’t understand why despite checking everything. It required me to look more closely at my code to notice a simple syntax error. I had forgotten to place the commas on the new entries. 

The second challenge I ran into was how to speed up the play back every turn. This was solved by considering all the pieces that went into determining the length of the playback. I figured out that the constant clueHoldTime. I needed to shorten this, which would decrease the time the clue spent on each color, and thus speed up the playback. By changing this constant to a variable and that is reset on start up and decreased every turn I was able to accomplish the goal. This was not a challenge of overcoming and unknown error but simply considering for a time on how I could implement it in the first place.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

It’s difficult to think of questions based on what I know for now. After working on the prework and completing its objective, I would like to know how it all functions on more complex applications. Regarding the ‘frontend’ and ‘backend’ of any web application, how does a website store data and then access that data upon user interaction? How can websites access separate apps within themselves like playing videos or games? It seems to me these questions would involve some very complex code but these are the things at the forefront of my mind. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I kept working on this project for a few more hours I would try to learn how to implement the remaining optional features. At the moment I don’t know how to add pictures or custom sounds to a application like this and I am unsure of where to find the information to learn this. With enough time I am sure I could figure it out however. Otherwise any other time I spent would be to simply fine tune the project as a whole. This includes looking to see if the code could be cleaned up, if its runtime could be optimized, ect.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://ucf.zoom.us/rec/share/6rhccjFjsL5f2BWWV0zhZI3QEf4VZEDTndoUNF9E0rNlDk-8CZ65x3MgztLtLUcH.fahgvJ0wuSiTOsMn?startTime=1648590611000 (Passcode: gjXH13e#))


## License

    Copyright Luke Wittmayer

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
