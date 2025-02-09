# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

**Win-Screen**
![Winning-Screen](https://github.com/robler43/Sound-and-Light/blob/9b3b1ebe0ea79dff4c631a1d3d8724d014ad630c/Screen%20Recording%202025-02-07%20at%2018.24.13.gif)

**Losing-Screen**
![Losing-Screen](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNW1xcDh3c3NkMWRrZWJnbDJhNWFtYW5raTczam4ycGJnemF5YmtoOCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Snq1drSdhNGyD0nGl8/giphy.gif)


Submitted by: Robin Hoesli


## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- Codepath Finalist Task Guide

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
- After completing the final step, which involved setting up the process to check the user's response, I encountered an issue where the game didn't play the pattern as expected. To debug the problem, I used the built-in console in Replit and was able to identify the bug in my code. The issue was related to the declaration of my guessCounter variable. Initially, I had declared it as a const, but since the guessCounter variable is incremented within the guess function, I realized that it couldn't be a const. A "const" declaration prevents reassignment, so I changed it to a "let" to allow the value to be updated. After making this change, the game worked as intended.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
- I want to understand how teams of developers collaborate to work on large projects together. How can multiple developers work on different features, particularly when new updates arrive? What tools and techniques do they use to manage versions and coordinate individual sections of the code?
When dealing with larger codebases, how do developers maintain organization and structure? Is there a particular pattern or architecture, such as Model-View-Controller, that aids in keeping everything manageable? I'm also interested in how various developers approach code splitting, file organization, and modularization to prevent the code from becoming too complex.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
- If I could have a little more time to work on this project, I would prioritize improving the user experience (UX) and user interface (UI) for a more enjoyable and better game. First, I would implement a scoreboard to present the player's current score in real-time during the game. That will enable them to see how they're doing and become more involved.

Second, I would implement animations to make the game nicer and present feedback when in use. For instance, I could animate the pattern display and implement effects when a correct or incorrect button is pressed. That will make the game exciting and interactive.

Third, I would redesign it to make it more fitting for the target group. That could involve altering colors, fonts, and layout to make it nicer and pleasing for the target group, with a simple and pleasing interface.

Lastly, I would modify the program to include a growing game score and a less repetitive experience. Currently, the game takes a specific sequence, but I'd prefer to make the moves random, in order to make the game challenging and exciting to repeat and try again. That will allow the game to become increasingly challenging according to a player's performance and make it less predictable, keeping them interested.

## Video Walkthrough 

Add your screen recordings for specified implemented features here:
[Losing screen recording](https://www.loom.com/share/c6cf160be31f49bc8405f387a3ee5026?sid=a8fe0940-213a-419f-9e6a-2191d3272b9c)

## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/KEEn-_jEPxE)


## License

    Copyright [Robin Hoesli]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
