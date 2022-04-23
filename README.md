# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for the Salesforce x CodePath's Futureforce Tech Launchpad internship program. 

Submitted by: **Anna Adobamen**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/dorian-rose-margin

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/a/d2i0ybZ)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/72890937/164877725-6366d61c-4bd2-466e-a199-72fc73859456.gif)



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://www.w3schools.com/jsref/jsref_random.asp
https://www.w3schools.com/cssref/css_colors.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I ran into a challenge when implementing the guess function; even after coding the function as well as I thought, the game was not functioning as expected.
The first thing I did was to go over the function carefully to make sure that I had done it correctly. This was necessary because the function contained a lot of nested if-else loops so I wanted to be sure that I had not made a mistake.  After that, I made use of the console.log() function to be able to print things to the console to see where I was going wrong. This helped me to follow the train of functions that the game was using. I eventually discovered that I had forgotten to add the *onclick="guess(#)"* to the attributes for all my buttons except the first. After I did this the game ran smoothly.
Another slight issue I ran into was implementing an additional function that would let the pattern be random numbers each time the game was started. I was confused at first, but after following the hint to use *Math.random()*, I found a website which I cited above that helped me understand how the function worked and how to use it in my code.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

This pre-work exercise was a very insightful and fun introduction to web development. 
One thing I noticed was how the *HTML*, *.css* and *javascript* files can get very clustered and confusing. I would like to learn tips that would help keep track of the structure of the html document, the various functions in the *javascript* file as well as what styles are used in the *css* file.
I think the last of those is more difficult because of the inheritance hierarchy of *HTML* elements.
An interesting concept mentioned that could help which I researched more on is the Document Object Model (DOM) which is an interface that shows the logical structure of *HTML* files.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on the project, I would implement some additional features such as setting a time limit for each guess and increasing/decreasing the permitted number of guesses. I would also make the game have 3 levels: Easy, Medium and Difficult.
The features affected by difficulty would be the number of buttons, the similarity of the buttons’ colors and sound, the time the player has for each guess as well as the number of guesses.
A pause button for the game might also not be a bad idea.
I would also modify the *css* document to make the game look more visually appealing.




## Interview Recording URL Link

[My 5-minute Interview Recording](https://dartmouth.zoom.us/rec/share/97fRfMxZjpO6voO2gO9lbELLfXl8WzqOhESQnARlDVAiJbhto7BLXc60SitvDAIu.SykoBsineFS6cOlH)


## License

    Copyright Anna Adobamen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.