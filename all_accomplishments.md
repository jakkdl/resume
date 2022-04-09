    Did you do a side project?
    Did you get a somewhat high grade somewhere?
    Did you do something related to STEM, such as teach someone math?
    Did you get a raise? Good feedback from your boss? from a user maybe?
    What can you talk about with enthusiasm?
    Did you write code that someone used (and isn’t in your CV) ?
    Did you publish a blog post or something similar?
    Did you give a lecture somewhere?
    Did you win some award?
    Did you improve the sales of your company? Maybe you reduced the crash rate? Did you help them succeed in some other way?
    Did you volunteer in something? (Even unofficially)
    Did someone write code that used your code as a base? (For example, you made some infrastructure that was then used, or some code that was then adapted for a new purpose?)
    Did you build a tool/automation for yourself?
    Is there some other vague indication that you’ve done a good job somewhere but I didn’t know how to ask about it?


Asking me for a comprehensive list is ... dangerous 😇 I've marked the ones I think are somewhat impressive, most of which have been on my CV and/or LinkedIn at some point or another, with an asterisk.  
Fun exercise to make me realize just how much *stuff* I have done.


# Education
Was offered to skip a grade at age 8, but parents declined after a bad experience with an older sister of mine. Worked ahead in math both around age 9 and at age 15, but lack of self-discipline/drive or support made those efforts peter out.
## Secondary education: Music class
Tip-top grades
## Higher/tertiary education: Science math/programming
C# and SQL, lotsa math, physics and science. High grades.
## 2/3rd of a bachelors degree in Computer Engineering
* Programming languages used: Python, C++, C, Java, Ada, VHDL, Prolog, Assembly, GNU MathProg, Microcode
* Statisticss, logic, discrete math, and other courses.

# Jobs
## summer worker as kyrkvaktmästare at Stora Tuna church
No clue what the english translation of the job role is: usher? attendant? sexton? verger? sacristan? caretaker?  
handling keys for buildings, minor tech responsibilities (microphones) during service, cleaning

## Teaching Assistant @ uni
* lectures
* teacher-led problem solving
* lab assistant
* grade hand-ins
* grade exams
* coach group projects
* standardized grading sheet to save time & make it more clear for students what code standard is expect
* responsible for the manual borrowing system used w/in the group to handle buying from our kiosk, group-buying food, etc
    * transitioned it to splitwise
    * wrote a C XScreenSaver that fetched balances from the splitwise API to display on my screen
    * automated sending emails to people when their balance was too large

## Course developer
* was unhappy with a course and the API it was working against, so complained to the examinator and was for two summers responsible for improving the course and software used in it
* students wrote python code, which interfaced with a python API, which interfaced with a client program written in C, which interfaced with a server written in C
* wrote new tasks, restructured the course
* added functionality, fixed bugs, and streamlined the API
* wrote new documentation
* made the server send more data over the network protocol: the speed of all objects on the screen, so the API didn't have to try and interpolate that
* https://github.com/jakkdl/XPilot-AI_LiU_fork
## IT consultant, Ericsson, HiQ
* Uplift 4G tests written in Erlang to work in a virtual environment
* git master, wrote bash & python scripts
* responsible for team wiki & documentation


# Projects:
## Arch Linux
* hardcore linux user for 15 years. Uses terminals and custom configs for everything.
* Read up on all major parts of the linux operating system, having configured and played around with almost everything.
* I've had lotsa fun setting up my new computer with Wayland, Pipewire, BTRFS with full disk encryption using LUKS, configuring Sway and waybar, and learning how to properly configure xkb keyboard rules.
## dotfiles*
* Recently started tracking configuration files in a git repo, >50 files tracked in it.
* custom-written python script to symlink/copy files to the correct places in the operating system, launched from git hooks
* https://github.com/jakkdl/dotfiles
## podcast fetcher
* frustrated by the lack of good (CLI) programs for listening trough the backlog of [music] podcasts. Wrote my own
* parses rss, downloads episodes, tracks playcount in pickled files
* runs in the background, connected to MPD (Music Player Daemon) and subscribed to playlist events to automatically run, download the listened-to episode, and add newly downloaded episode to theplaylist
* https://github.com/jakkdl/random/blob/master/podcast_archive_mode.py [195 lines]

## dominion opening probability calculator
* simulates drawing opening hands in the card-game dominion
* coded up during an afternoon when I was curios, bad code
* https://github.com/jakkdl/random/blob/master/dominion_openings.py [50 lines]

## stepmania playlist generator
* was gonna run 5k, but didn't like actually running to prepare for it, so wrote a quick script to generate playlists for the DDR-like game stepmania to last the length of running a race.
* stepmania interface kinda shitty
* https://github.com/jakkdl/random/blob/master/stepmania_mixtape.py [186 lines]

## synchronized metronome
* Singing happy birthday over the telephone is kinda impossible due to the latency, but realized that if all singers have a metronome synched to the clock and have roughly equal latency to the receiver, they can synch their singing to their locally-running metronome, ignore other singers, and the receiver will hear synchronized song (assuming similar latency to receiver, and correct clocks)
* actually worked decently when me and my brother used it, though didn't bother make it easier to use
* works on windows & linux
* https://github.com/jakkdl/random/blob/master/synchronized_metronome.py [77 lines, but fuck those were tricky lines]

## dominion game length*
* There's no built-in timer in Dominion, so there's always loads of discussions about play speed but extremely sparse data. So I wrote a discord bot that scraped posts for when matches are scheduled to begin, and when their results are reported.
* Logs players involved, match length, number of games played
* calculates a bunch of stats, have some fancy graphs
* possible to dm the bot for personal stats, but didn't catch on much w/ other players. I've personally gotten a bunch of value from it though, and have had plenty discussions about the data with other players.
* shares some code with my other discord bots
* https://github.com/jakkdl/dominion_game_length [1.5k lines]

## necro score bot**
* my favorite baby
* was a pain to keep track of all the leaderboards in the game, so I wrote this twitter bot
* 237 followers, 13.2k tweets, [? of likes, ? of retweets]
* users can put a link to their twitter in their steam profile to be tagged in posts. ? number of people have done this
* running pretty much 24/7 since 2015, maintained and run by other community members
* 5 unique contributors to the source, though vast majority is mine
* interacts with steam, twitter, discord [not activated], necrolab, speedrun.com [disabled]
* https://github.com/jakkdl/necro_score_bot [1.5k lines]

## dominion tournament kingdom generator
* ran an in-person dominion tournament with a friend, and being unhappy with existing tools wrote a program to generate kingdoms such that cards are only used once, we don't run out of different types of tokens and mats, etc
* https://github.com/jakkdl/dominion_tournament_tools [159 lines]

## Oxygen Not Included, custom map: Void
* I liked the concept of skyblock in minecraft and seablock in factorio, so wanted the same experience in Oxygen Not Included
* Royal pain to do proper modding on linux (C# unity game) so it's only xml modding
* never played by anybody else afaik, but greatly enjoyed by me
* https://github.com/jakkdl/Oxygen-Not-Included_Mods

## seat exchange bot*
* Implements an adaptation of a game from a Korean game show The Genius
* Supports 40 different commands, varying player counts, bot players, simultaneous games, and permissions
* Adheres to PEP coding standards and is object-oriented, modular, and statically typed
* played a couple dozen times with it to pretty decent success, ~20 people joined the server dedicated to playing the game
* https://github.com/jakkdl/seat\_exchange [Python, 3500 lines]
## routine trigger
* frustrated by unreliability of triggering my routine clock from calendar notifications I started writing a native android app to send intents to tasker to trigger
* never ended up used, but did get it to a basic working state
* https://github.com/jakkdl/routine_trigger [Java]
## py-evm pull request*
* been interested in cryptocurrency and specifically ethereum for a long time, and considered trying to become a developer in that ecosystem
* downloaded the source code for one of the clients - primarily used by developers to test new features. Ran a bunch of linters and code analysis tools on it, and fixed some smelly and ugly code.
* several rounds of back-and-forth with the developers to discuss the issues I found and settle on solutions
* https://github.com/ethereum/py-evm/pull/290 [+115 / -104]

## rullgardin
* More of a hardware/physical invention, but after several failed iterations with Arduino motors I mounted a tape motor to my roller blinder that's controlled by an arduino to automatically roll up in the morning
* code is extremely dumb, only a hardcoded timer, and timing is controlled by a wall timer. TODO to make it connect to wifi/bluetooth/something and interact with routine clock
* https://vimeo.com/manage/videos/229001221
## youtube subscription downloader
Forked a git repo and heavily modified to automatically download youtube subscriptions to my phone so I can watch them with VLC. TODO: put it on git
## soundcloud feed downloader
Wrote back in 2015, 560 LOC python. No clue if it works today. Not on github
## A dozen other scripts lying in random directories

## NecroDancer other
### release tester
one of a dozen testers for the release version
### CoNDOR
* one of a small team that ran tournaments in the Crypt of the NecroDancer Online Racing league
* https://condor.live/
* hundreds of participants, prize pool sponsored by the developers to the tune of several thousand dollars
* (I've also competed a couple times to mediocre results)
### necrolab
* Designed scoring formula for power-ranking site created by another community member
* https://necrolab.com/ [site is constantly under maintenance]
### scorebot
(see above)
### mods
* Total of 25 different mods on the steam workshop
* sum total of 636 subscribers, 39 comments, and one follow-up mod by another modder that updated "trap door boss rush" to work with the DLC (41 subs)
* none of the mods have thumbnails, and most don't even have descriptions, and this is a pretty small indie game - so I'm sort of surprised the numbers are that high.
* modding in ND is quite limited, but I pushed the boundary of what was possible with brute-force testing and creative solutions.
* Features intended for translation mods became mods that changed the english labels on things to help enforce tournament rules
    * this, together with edits to remove items, was used in several tournaments
* editing game sounds became an [extremely meme] way of enforcing game restrictions (crashing the game if you do what's forbidden)
* spearheaded efforts to experiment with undocumented xml properties to modify weapons and items in unintended ways
* the main intention with the modding is to resprite the game. I wrote a script that blanked all tile and enemy sprites such that you're forced to play only with sounds, particles and the minimap:
    * pancelor, 2016: 
    > this mod is amazing and terrible. I haven't felt this bad at necrodancer since 2014 and it's a wonderful feeling
    * https://www.twitch.tv/videos/63213080?
* created a series of beatmap-modifying mods that made you play in double tempo, quad tempo, half tempo, compound rhythm, quarter quintuplet tempo, every eight beat is dropped
    * https://www.youtube.com/watch?v=nPORyuKZh7Q
* the game lacking a good way to practice "trap doors", I created a well-liked mod (43+41 subs) that helped practice it - by creative application of beatmap modding



# Awards
## Gold star: Most helpful
Awarded to me at age 10 by my teacher, due to helping my benchmates with math. :D
## Mensa entrance test*
IQ of >135 (top 1%)
## Swedish SAT*
Got the top score first time I wrote it in 2012, top 0.1%  
Took it again for fun in 2016, but "only" scored in the top 0.2% that time
## Ljungbergspriset*
Won a grant for 20,000SEK (1,950 euro) towards higher studies for high grades and writing a good application letter when finishing swedish upper secondary school (age 18).  
One of three in my school, one of eight in my town. Got into the newspaper, was given tours of Falu copper mine and Domnarvet paper mill, and a fancy award dinner.  


# Competitions:
## Kängurun, 2011
During gymnasiet me and a friend pestered our teacher for more competitions, and we got them to arrange a day where students could take part in a swedish math competition called "the kangaroo".  
Placed 9th/155 in my division http://ncm.gu.se/2005
## Trombone competitions
Various competitions as a solo trombonist, was likely one of the best trombonists in Sweden during my school years. Got to perform with a professional orchestra twice, and went to many finals (where entry was for soloists of any instruments).
## Programming Olympiad 2011
Placed in a 21-way tie for 31st out of 164 in the swedish qualifiers.  
https://progolymp.se/2011/skolkval/resultat-mer
## Nordic Collegiate Programming Contest, 2015
Formed a team with two workmates to have an enjoyable day filled with coding.
We solved 3/10 problems, placing us 9th/22 at our uni, 108th/355 across all universities.  
https://ncpc15.kattis.com/standings?filter=352 (Team "Ge UPP!")
## IDA-Masterskapet i Programmering och Algoritmer
A continuous competition run by my university where you solve programming tasks of different difficulties for points, and can win prizes  
Runs with UVA as a backend  
(Didn't put a ton of effort and only participated during two "periods")  
placed 10/22 second round of autumn semester 2015  
Placed 12/22 third round of autumn semester 2015  
total 12 problems solved  

## advent of code
https://github.com/jakkdl/advent_of_code  
Earned 32 stars across 3 years, though ultimately lost interest each year and never completed.
## Genikampen
Participant in the 2016 edition of the swedish national TV-programme "Genikampen" (~"struggle of the geniuses"). A competitive reality show
## Genius Online
A Community that runs run Online Reality Game (ORG) shows inspired by the korean game show The Genius.
These lasts several months, with elaborate and highly competitive original games requiring strategy, planning and social coordination.  
I created massive spreadsheets, elaborate plans, and wrote scripts to aid strategizing.  
I learned game theory and subsequently solved one of the games using combinatorial game theory and memorized the "nimbers" of different shapes of pieces using Anki and scripts to generate those values. (One day I might do a proper write-up)  
Placed 9/13 in Genius Online: The Final Problem  
Placed 1/13 in Genius Invitiational
## TSEA83 Microcode sorting competition*
Every semester this course runs a sorting competition for interested students, where the task is to sort 16 numbers with the minimum number of clock cycles on a given, simulated, microcomputer. You can either write your solution in assembly, and write microcode for the assembly instructions. Or write your solution in raw microcode.  
I wrote mine in raw microcode, used the program memory as a large lookup table / bucket for sorting, and abused several parts of the microcomputer for tasks they were not originally intended to do - in order to achieve some parallellism and optimize my program.  
My program ran in an avg of 903.6 cycles on their problem set (897 cycles on average in my testing).  
The previous student record was around 1,100 cycles or something, and the professors record was 948 cycles.  
My name was then displayed on the course website for multiple years following that, though they've since stopped tracking records... 😇
An overview of what the computer looked like can be found at page 7 of https://www.isy.liu.se/edu/kurs/TSEA83/pdf/mia_manual.pdf  
(One day I might add my solution to github, but I coded it in ... a spreadsheet)

## Tasker*
Very powerful scripting application for android  
Coded with a gui, I have \>400 actions (~lines of code) across >30 actions (functions/programs)  
system for managing my life, notifying when to wake up, take medication \& vitamins, eat, sleep and other reminders. Logs everything to the calendar, as well as time-to-fall-asleep and sleep duration, enabling statistics.  
Also assists with daily diary taking and evaluating drugs with
self-blinded experiments (currently evaluating melatonin dosage).  
Interfaces with my smartwatch, a Pebble Time, and widgets custom-created with KWGT. Planning to interface it to my self-built automatic roller blinds running on an Arduino.  
Currently working on interaction with the Toggl API.  
I could go into a *lot* more detail on this, I've been working on my scripts for >5 years and there's a crapton of functionality everywhere - carefully tuned to be reliable (across time, phones, timezones, android versions, etc) and of the most usefulness for me.


## computers
ripped apart and reconstructed dozens of computers for personal use, or as servers.
Almost never buy new stuff, instead take hand-me-downs and create frankenmachines good enough for me & linux
### dvorak
Can touch-type both Qwerty and Dvorak, learned Dvorak when I was ~16
https://en.wikipedia.org/wiki/Dvorak_keyboard_layout
### messagease
Custom keyboard layout I use on my phones.
Not actually *that* much better than modern keyboards, but I like not having to use auto-correct.  
https://www.exideas.com/ME/index.php
### lineageos (and previously CyanogenMod)
custom OS I use for my mobile phones
https://en.wikipedia.org/wiki/LineageOS
### rockbox
custom OS I installed and ran as daily driver on my iPod a decade ago
https://en.wikipedia.org/wiki/Rockbox


### What can you talk about with enthusiasm?
Oh boi, answering this one would take up another couple thousand words
