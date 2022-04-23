# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Youssef Salib**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/omniscient-ritzy-entree?path=index.html%3A1%3A0 

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
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/7cEPYm407F.gif)
![](http://g.recordit.co/zN8vJmGxWX.gif)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
2. 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random 

https://www.freecodecamp.org/news/a-quick-guide-to-styling-buttons-using-css-f64d4f96337f/ 

https://www.w3schools.com/js/js_htmldom.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

Some challenges that I faced were changing the button outlook to be an image. I uploaded the picture to the assets folder ,and embedded the image in an html file. But the image wouldn’t appear at all. I kept searching on youtube and stackoverflow, and tried different solutions ,but nothing was working. I then read the glitch manual on html and found that I was copying the wrong link of the image.I then had to position the image to appear fully in the center using CSS. Thankfully, the problem was resolved and I was able to implement this feature. Another challenge that arose was creating the random order for the pattern. I wanted to generate numbers 1-5 (corresponding with the buttons) randomly and return them in an array. Unfortunately, the game didn't start after. I took a deeper look but all seemed good. I then used console.log to debug the issues and noticed my array wasn’t appending the numbers. I was returning an empty array . The main problem is that  I wasn't initializing my array correctly. After fixing this problem, I was building the 3 strikes feature, and I wanted to alert the user on every strike. But the alert didn’t show the correct number of the strike, instead it was NAN. This was more of a syntax error and I had to wrap the math operation calculating the strike into its own parenthesis. I also tried to incorporate animal voices for each picture, but the sound was the same for each single picture. I looked at the tutorial provided,but couldn’t come to a proper solution. I also didn’t want to exceed the suggested amount by codepath and used the frequencies given to me with some edit


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Quick note: About the video, I was really excited and happy to talk about these topics and mention my experiences. Though,I try to speed up in the video to meet the time requirement of 5 min, so my facial expressions can seem a bit anxious in the video about meeting the time mark :)  I have tried recording multiple times, but my facial expressions were always the same as I try to speed up. 

Some questions regarding my project is how Can I add animal voices to the buttons. I have really tried, but all of the pictures shared the same sound and messed up the game. Some other general questions are how are web pages always updated(e.g News sites)? Does someone manually change them, is there an application that updates it automatically? How do engineers test these web applications? What other technologies are also incorporated with web development other than these 3 languages? How to post a live website and keep it running instead of just hosting them locally? Also, how can we interact with the user and request information from them, and receive insights on what the user does when they're on the website so we can improve the webiste? How can websites intereact with other websites to extract the needed information(ex : movie ticket website)? how's the market for web devlopers, is there a demand for them?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

 Some features I would've implemented are an online server multiplayer mode, where player 1 chooses the pattern and player 2 has to follow it..Also provide worldwide ranking for competitiveness, where you can level up and play with other players around the world.I was also thinking of creating different difficulty levels, where the pattern will be quicker and more buttons are selected at once. If you decide to play on Easy level, you only have 4 buttons , with a short pattern and a comfortable wait time between each click. As levels rise, more buttons will be introduced with longer patterns and shorter wait time. Another feature is with each game win, the player gains a life token and uses them as a "surviving life" to resume the game after the 3 strikes are up.. As I mentioned above , I would have loved to make my game animal based with voices corresponding to each animal. If I were selected for a FutureForce opportunity and after learning the material , I will definitely revisit this project and build more of these features as stated above. This opportunity will be amazing for my growth as a software engineer and a developer.  This program will be an investment in my future in which I am confident that I will accomplish great things and give back to my community.Thank you so much for the consideration and the opportunities Codepath provides.


## Interview Recording URL Link

[My 5-minute Interview Recording](https://berkeley.zoom.us/rec/share/eJj7LRgkv3NCaBrGeqLD_FAkUJ9_IJUFleDaAXcQjZLqZsKjpeWEEsZiQzUFgb5B.ZYRUMF6n1-PlSvPs) 
Quick note: About the video, I was really excited and happy to talk about these topics and mention my experiences. Though,I try to speed up in the video to meet the time requirement of 5 min, so my facial expressions can seem a bit anxious in the video about meeting the time mark :)  I have tried recording multiple times, but my facial expressions were always the same as I try to speed up. 




## License

    Copyright [Youssef Salib]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
