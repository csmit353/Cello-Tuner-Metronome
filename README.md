## Tags

### v0.1

**The first happy/sad face assignment has to do with displaying two faces forever. The two faces will appear on the led screen on 5000ms intervals.** 
* JS file: [HappySadFace](https://github.com/csmit353/Project-Step-1.git*)

### v0.2

**This assignment took the previous coding and gave it inputs. Instead of the faces appearing forever, the micro bit now displys them after either button "A" or "B" is pressed.**
* JS file: [HappyFace/SadFace](https://github.com/csmit353/Happy-Sad-Face.git*)
  
### v0.3

**Lesson three focused on variables. If you took a game such as rock, paper, scissors, how could you program micro bit to keep track of your score? This code allows you not to do that, but then tell you how many wins each player has and how many times they tied. Using three variables, "PlayerA," "PlayerB," and "Ties," you can then tell the micro bit to display an A, B, or T on the led screen along with a numerical value with the "shownumber" command.**
* JS file: [Scorekeeper](https://github.com/csmit353/ScoreKeeper.git*)

### v0.4

**The next lesson was about coding the micro bit to play rock paper scissors with the user. You can do this by using logic to tell the microbit to pick a random led picture representing rock, paper, or scissors. This coding also includes a score counter for the user that they can display at any time by hitting the "A" button.**
* JS file: [Rock, Paper, Scissors](https://github.com/csmit353/RockPaperScissors-Counter.git*)

### v0.5 

**I was always curious how the "game" section of MakeCode worked. Using loops and game logic, this lesson taught me how to get a sprite to travel across the led screen of the micro bit. It also gave an introduction to the music programming which I focused on for my midterm and final project.** 
* JS file: [Loops Demo](https://github.com/csmit353/Loops-Demos.git*)

### v0.6

**For the mid-term I began exploring the music abilities of micro bit. I have four inputs assigned to four different notes to play. I also tried assigning the same notes to pins in an attempt to create a midi device. I also began exploring tuning ideas during this assignment. 


### v0.7

**This lesson introduced me to animating the leds on mirco bit. It displays a face switching from happy to neutral until you press either button A or B. Once it reads the users input, it displays random led pictures. This assignmnet was a tough one for me, so I will be coming back to this quite a bit.**
* JS file: [Animation](https://github.com/csmit353/Animation.git*)

### v0.8

**Boolean coding is the next focus. This file is a program for the micro bit using a variable for two coin flips and two scores. Different inputs will output random led displays cordinating to a coin flip. The program then adds a point to each "player" to take this from a simple coin flip, to more of a game.**
* JS File:[Double Coin Flip](https://github.com/csmit353/X2-Coin-Flip-.git*)

### v0.9

**This is such a helpful way to understand binary code better. This program allows you to input any binary code and then check to see the decimal equivilent whenever you want. I struggle with understanding binary and will definetly be using this.**
* JS File: [Binary Transmogrifier](https://github.com/csmit353/Binary-Transmogrifier.git*)

### v0.10

**Lesson 10 showed how to code morse code and marco polo. It works by sending radio signals via button inputs that a second micro bit will receive. The user can also see what is coming in, "marco," "polo," or either morse code signal, on the led screen.**
* JS File: [Morse Code/Marco Polo](https://github.com/csmit353/Marco-Polo-Morse-Code.git*)

### v0.11

**Program micro bit to play headband charades (a.k.a. Heads Up) with this code. Give the micro bit a list of words to display and have it display a random one on the led screen using "array" code. I really like how you can use tilt inputs to mimic the smartphone app.**
* JS File: [Heads Up](https://github.com/csmit353/Heads-Up.git*)

### v.012
**This program is described in length below. This is a cello tuner and metronome. It plays the desired tone to tune a cello and plays two different tempos to get you in time to read an allegro or adagio music score.**
* JS File: [Cello Tuner/Metronome](https://github.com/csmit353/Cello-Tuner-Metronome-Code-File.git*)

# Midterm/Final Project

#### Goal

**Music is a passion of mine, therefore, I decided to turn my Micro Bit into a cello tuner and metronome.**

#### Design process For Cello Tuner and Metronome

**I chose a cello for the instrument because it is what I know how to play. It is cello specific because the tones played and displayed are A, D, G, C; the open strings on a cello from high to low. I contemplated for a while on what inputs I wanted to cause the tone for each note. Did I want one button to play all four? Or have buttons A and B play two each? I ended up settling with four seperate inputs for each note, because it was easiest to repeat one note if that string was severely out of tune on the cello. I also struggled with getting the letter to display on the led's while the tone was playing, instead of the tone playing and then the led disply or vise versa. I solved this issue with the "basic.clearscreen" command placement. I originally had it after the led display which caused the issue. I noticed when I was looking on the microbit website and other resources that coding microbits to be tuners is common compared to other ideas. So I wanted to take it one step further and make it a metronome using bpm command option. I wanted to give myself some variety and allow for 120 bpm, which is the lower end bpm standard for most Allegro peices of music, and 72 bpm, which is the most common bpm for an Arpegio peice. Finally, in order to hear all the tones, an external speaker will need to be connected. I can do so by connecting allegator wires to the "GND" and "0" terminals on the micro bit to a speaker or pair of headphones.**

#### JS Constructs & objects

**This project includes some basic commands such as, "showled," "shownumber," "clearscreen," "onstart," and "showstring." It heavily relied on using the microbit inputs that are included in the device like the buttons, tilt, and facing options. I also used "playtone" commands to program the tuner portion. To set the metronome bpms I used the "setTempo" commands under the same category. I wanted to implement loops into the project too so I coupled that with the play tones to hear the note longer and save the user from having to perform the inputs over and over again.**

# Final Project JS Link: [Cello Tuner/Metronome](https://github.com/csmit353/Cello-Tuner-Metronome-Code-File.git)


