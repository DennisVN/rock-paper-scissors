# Rock paper scissors lizard Spock 🧱🧻✂️🦎🖖

Welcome to my first Rock Paper Scissors Lizard Spock game. I saw many seasons of The Big Bang Theory, <br> but i obviously missed the one where Sheldon invented this version of the classic. <br>
Site deployed here : https://dennisvn.github.io/rock-paper-scissors/
<br>
# UI Screenshot
![Screenshot](https://github.com/DennisVN/rock-paper-scissors/blob/master/images/screenshot.png)

## How it works
- Click an emoji to challenge the AI.
- After the click you see your result:
    - Win , Lose , Draw, Message
    - Overview of your choice vs ComChoice 
    - Above you find the score_div for you vs AI
    - Fancy CSS & JS effects on hover and click (see below)

## How the code works 
- HTML features : 
    - Header for simple title, looks clean. 
    - Main container :
        - Score container : to display the score (auto updated with innerHTML)
        - Buttons : buttons with ID's and onclick functions to use later in JS declarations. (linked as strings)
        - Challenge : hidden when inactive. Get's displayed after you click a button. This div contains : 
            - your choice and the computer's choice. 
            - you win / lose / draw message. (fades with CSS & JS)
        - Script tag for Javascript. 
<br>

- CSS features :
  - Hover effect on buttons 
  - button turns green when you hover over them 
  - When you win the round you get the .green layout effect (JS), if you lose    
    the .red (JS), with a draw it's the .grey layout (JS).
    - in human language : the button turns green, red, or grey depending on win.
  
- JS features :
    - Array choices contains the words linked to button ID's of emojis
    - Math.floor(Math.random() * 5); to generate the RNG. Declared in the project as i.
    - Automated AI RNG with the variable ComChoice=[]
        - RNG will generate a number from 1-5. each of them beeing an emoji/word.
    - Score function has score_div declared to update the InnerHTML of the "scoreboard". (very basic scoreboard in this project.)
    - if else statements use : 
        - if () LUNCHBREAK BRB WIP
### WIP
- Add mediaQueries for full responsiveness 
- Add scoreboard
- Keep track of scores on leaderboard
- Implement game rounds or 50 max score.
- Add Next Round Button
- Add better graphics and music ;) ! 
