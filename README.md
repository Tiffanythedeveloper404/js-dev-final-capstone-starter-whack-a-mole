# Whack-a-Zombie!

**The Game I Chose to Develop**

For my capstone project, I chose to develop Whack‑a‑Zombie, a creative twist on the classic Whack‑a‑Mole game. Instead of moles, zombies pop out of nine holes, and the player uses a custom magic hammer cursor to whack them before the timer runs out. The game includes a spooky horror theme, a scary Butcherman font, and custom styling to enhance the experience.

<img width="1157" height="881" alt="image" src="https://github.com/user-attachments/assets/e4d162f9-d4b0-44eb-b527-97ee778fc7b1" />











**Plan: Functions, Features, Algorithms, and Coding Choices**

Core Functions
startGame() – initializes score, timer, and begins zombie pop‑ups

countDown() – decreases timer every second and ends game at zero

randomHole() – selects a random hole for the zombie to appear

popUpZombie() – shows zombies at random intervals

hitZombie() – increases score when a zombie is clicked


**Key Features**

9‑hole grid layout

Random zombie appearance

Score tracking

Countdown timer

Start button

Scary font and custom cursor

Zombie graphics replacing moles


**Algorithms & Coding Choices**

Randomization using Math.random() to select holes

Timing logic using setInterval() for countdown and zombie pop‑ups

Event listeners for user clicks

CSS grid for layout consistency

Custom assets (zombie PNG + hammer PNG) for theme enhancement

Class toggling for animations and hit effects


**Implementation Plan**

Build HTML structure for title, score, timer, and grid.

Style the grid using CSS Grid and create hole/mole elements.

Add JavaScript logic for random zombie appearance.

Implement scoring and countdown timer.

Add Start button functionality.

Replace moles with zombie images.

Add scary Butcherman font for theme.

Add custom magic hammer cursor.

Test game functionality and fix layout issues.

Deploy to GitHub Pages.

Complete README and gather screenshots.


**Reflection on Coding Trade‑Offs**

I reduced the size of the scary font to prevent layout overflow.

I resized zombie images to improve loading speed and maintain grid alignment.

I kept animations simple to avoid performance issues.

I chose a lightweight design instead of adding sound effects to keep the project focused on core functionality.


**Justification of Choices, Challenges, and Debugging Moments**

Zombie Theme: I chose zombies to make the game more creative and visually engaging.

Scary Font: Butcherman added a horror vibe but required resizing to prevent layout issues.

Cursor Image: The hammer cursor originally had a white background; I fixed this by exporting a transparent PNG.

Layout Overflow: The large font pushed the grid off‑screen; I adjusted font sizes and grid height.

Broken CSS: A duplicate <head> tag prevented CSS from loading; removing it fixed the issue.

File Paths: Some images didn’t load due to incorrect paths; correcting them resolved the problem.


**AI Tools Used (with Justification)**

I used Windsurf and CodeGPT to assist with:

Debugging CSS layout issues

Fixing cursor transparency

Clarifying JavaScript logic

Troubleshooting grid overflow


**100–150 Word Summary of Project Process**

This project involved building a fully functional browser game using HTML, CSS, and JavaScript. I started by creating the grid layout and basic game logic, including random zombie appearance, scoring, and a countdown timer. After the core functionality worked, I added creative elements such as a zombie theme, scary Butcherman font, and a custom magic hammer cursor. Debugging included fixing layout overflow, correcting image paths, and resolving CSS loading issues. I deployed the game to GitHub Pages and documented the entire process with commit history and Replit screenshots. This project strengthened my understanding of DOM manipulation, event handling, and responsive styling.

**GitHub Commit History & Replit Screenshots**


<img width="992" height="607" alt="image" src="https://github.com/user-attachments/assets/18151bc1-b285-4f32-abaa-33215ab0da7b" />




<img width="802" height="482" alt="image" src="https://github.com/user-attachments/assets/89cefb52-0e18-4845-b8e3-2270922b4bf7" />



<img width="1267" height="592" alt="image" src="https://github.com/user-attachments/assets/6df00916-d95a-40d0-a220-dc96f66a06d3" />





<img width="797" height="483" alt="image" src="https://github.com/user-attachments/assets/6b26f568-4bf8-448c-90ae-8950732471d9" />





<img width="797" height="477" alt="image" src="https://github.com/user-attachments/assets/48a9aa7c-9a9a-445f-b21d-2346da411f4b" />


























