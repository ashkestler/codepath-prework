# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Ashley Kestler

Time spent: 4 hours spent in total

Link to project: https://glitch.com/edit/#!/hissing-holy-scapula

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
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
<img src="/gifs/projectgif1.gif" width="700"/> /
<img src="/gifs/projectgif2.gif" width="700"/> /
<img src="/gifs/projectgif3.gif" width="700"/> 

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. <br>
https://www.w3schools.com/

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) <br>
This was my first project using JavaScript, so that was a little challenging but also fun! I had some trouble with keeping the buttons properly aligned when inserting the images into the buttons. When I inserted the images into the buttons, they moved around and jumped out of alignment. I attempted to research the issue but couldn't come up with any helpful resources for this particular problem. I overcame it by specifying the height of the images in the CSS file; I tried different height dimensions until I found a size that did not affect the placement of the buttons but still looked visually appealing. I also made sure to set all images to be the same height so that they would look uniform. There was also a minor challenge in figuring out how to make the images only appear when the button is clicked or lit. After researching different CSS properties, I found the best way to accomplish this was to create CSS rules which set the opacity of the image to 0 by default, and set the opacity to 1 when the corresponding button is active or lit.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) <br>
I would love to continue learning more about JavaScript, as I really enjoyed it and found the functionality it offered to be exciting. I have questions about how to use multiple different JavaScript functions in the "onclick" attribute and how that might be implemented. I'd like to learn about animating elements and text. I also have questions about APIs and how to make web development projects using APIs. I would like to know how to make a loading image for a website. I have some basic knowledge about Bootstrap and how to use that to make a website mobile-friendly, but I would like to learn more about that as well to be sure that everything I make can be dynamically resized in order to be easily viewed on all different devices. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) <br>
I would add more functions in order to simplify the "guess" function in the game. I would add an "isCorrect" function to contain the code for checking whether a guess is correct or not, rather than putting that code in the "guess" function. I would then call the "isCorrect" function from within the "guess" function. I would also research more about and add more of the optional features into the game, such as implementing more complex tones for the buttons and adding a timer. The timer in particular was a feature which I wanted to implement but didn't have the time to do enough research on. 



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/28e2e3b7a056470681de69d83fa25b15)


## License

    Copyright Ashley Kestler

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
