Arifs Mehtijevs - Research into live coding and description of TidalCycles project
AUD821: Algorithmic Sound Structure and Composition

Introduction
The aim of the project was to do a research of a phenomena of live coding in music and to create a music composition using one of the live coding environments. My paper explores different music code-based software options. Such computer programs are developed to allow music composers to create music in an alternative way using a programming language. There is also a possibility to utilize these programs to perform music live on stage by creating lines of code on the fly. This approach, in turn, transforms a music composer into a music programmer. Live coding environments are also very accessible as the vast majority of them are free to get.

General overview
“Live coding is inclusive and accessible to all. Many live coding environments can be downloaded and used for free, with documentation and examples to get you started and friendly on-line communities to help when you get problems. Popular live coding software includes ChucK,  Cyril, extempore, fluxus, impromptu, overtone and supercollider. Environments designed for fast exploration of musical pattern include ixi lang and TidalCycles. Sonic Pi is designed for teaching both music and computer science in classrooms, as well as performing in algoraves. There are also impressively capable web-based live coding environments like gibber and livecodelab. Live patching is live coding with graph-based languages such as the venerable pure-data. It’s also possible to livecode with a gamepad, e.g. with the robot oriented Al-Jazari.” (TOPLAP website n.d.)
There are many live coding programs. Each program comes with its own programming language and learning curve. Of course, there are also different sound capabilities with each software.  Live coding programs like Max MSP and Pure Data introduce “dataflow programming” or, in other words, “patching” approach. This is an alternative live coding way of connecting various pre-designed objects to create a sound output. It is also possible to create your own objects in Max MSP but in order to do that it is imperative to have a basic understanding of the Java language. Max MSP is part of the Ableton Live package, whereas Pure Data software is free and open source. The more traditional music coding programs are Supercollider, TidalCycles, Foxdot and Sonic Pi. With these programs the music composition is achieved by writing lines of code using letters, symbols and digits. 
One of the barriers with programming languages is a steep learning curve. Majority of music composers, for example, do not have coding experience. So, the question is – what are the main prerequisites on a way to learn how to code successfully? According to Victor (2012):

•	Programming is a way of thinking, not a rote skill. Learning about "for" loops is not learning to program, any more than learning about pencils is learning to draw.
•	People understand what they can see. If a programmer cannot see what a program is doing, she can't understand it.
Thus, the goals of a programming system should be:
•	to support and encourage powerful ways of thinking
•	to enable programmers to see and understand the execution of their programs

Algorave
Algorave is a term for live concert where music programmers perform on stage in front of the audience. Musicians compose music live using live coding software. There is a screen on stage where the audience can see the full code of the music piece being played. The term “Algorave” was invented by Alex McLean and Nick Collins in 2011. Since 2011 algoraves are becoming more and more popular and are taking place worldwide. 
“Algorave is made from “sounds wholly or predominantly characterised by the emission of a succession of repetitive conditionals”. These days just about all electronic music is made using software, but with artificial barriers between the people creating the software algorithms and the people making the music. Using systems built for creating algorithmic music and visuals, such as IXI Lang, puredata, Max/MSP, SuperCollider, Extempore, Fluxus, TidalCycles, Gibber, Sonic Pi, FoxDot and Cyril these barriers are broken down, and musicians are able to compose and work live with their music as algorithms. This has good and bad sides, but a different approach leads to interesting places.” (Algorave website n.d.)
One of the prominent live coders from the UK is an artist Joanne Armitage. Joanne performs at algoraves all across the globe and is also a lecturer in digital media at The University of Leeds. 
This is how Kretowicz (2017) describes Joanne’s live performance:

In the back room of a bar in the South London suburb of New Cross, there’s a revolution happening. Or maybe it’s not so much a revolution as a de-volution, a rolling back to the backend of music production, where the possibilities of the encoded information inside computer software is open and endless. An artist with the simple stage name Joanne, is standing on a stage at the Amersham Arms, looking at her laptop and typing, immersed in dry ice and the creative process, as a projection plays behind her. Red, blue, green, yellow, purple text on a black background moves and changes; highlighted orange, and cut-and-pasted, in a flash, disappearing with the rhythm of a cursor. The music it conjures is bouncing out of several well-placed speakers. It ricochets from the corners of the dimmed room as a repetitive dull thud drops, then builds up through a crunching, incessant rhythm. Some of the audience squeals, the floor vibrating with a heavy beat that’s almost organic. This is the look and sound of live-coded electronic music, or the more recently (and craftily) coined music ‘genre’ now known as Algorave.

Such description accounts for quintessential algorave performance.

Summary of a various live coding programs
Supercollider
Supercollider is one of the most well-known live coding environments. It was developed and released in 1996 by James McCartney. Since 2002 Supercollider is a free, open source software which is maintained by a community of live coders. The software is based on C++ language. It consists of three major components: scsynth, sclang, and scide. 
“scsynth, a real-time audio server, forms the core of the platform. It features 400+ unit generators (“UGens”) for analysis, synthesis, and processing. Its granularity allows the fluid combination of many known and unknown audio techniques, moving between additive and subtractive synthesis, FM, granular synthesis, FFT, and physical modeling. You can write your own UGens in C++, and users have already contributed several hundred more to the sc3-plugins repository.
sclang, an interpreted programming language. It is focused on sound, but not limited to any specific domain. sclang controls scsynth via Open Sound Control. You can use it for algorithmic composition and sequencing, finding new sound synthesis methods, connecting your app to external hardware including MIDI controllers, network music, writing GUIs and visual displays, or for your daily programming experiments. It has a stock of user-contributed extensions called Quarks.
scide is an editor for sclang with an integrated help system.” (Supercollider website n.d.)
Apart from working in Supercollider on its own, it is possible to use other programs like TidalCycles and Sonic Pi to use Supercollider sounds. 

TidalCycles
TidalCycles is based on the Haskell programming language and was created by Alex McLean. The software utilizes patterns method of music composing approach. TidalCycles is perfectly designed for musical improvisation and composing. The program is quite accessible for people with music background due to its timing/rhythm concept. 
“Tidal does not make sound itself, but is designed for use with the featureful SuperDirt synth, and can control other synths over Open Sound Control or MIDI. Whether you're using SuperDirt or a synth, every filter and effect can be patterned and manipulated independently with Tidal patterns.” (TidalCycles website n.d.) 
TidalCycles is one of the most commonly used live coding environments used in algorave performances. 

Sonic Pi
Sonic Pi is another, widely used at algoraves, live coding music program. It was developed by Sam Aaron at the University of Cambridge. This software also uses Supercollider engine and it has similar time signature/rhythm-based design. It was originally developed for educational purposes and is based on the Ruby programming language. 
“As an open source environment, Sonic Pi software, toolkits, resources as well as the work of others are available free to all online. Users can define their own sounds, rhythms and tone to create their own music. This can be done as static compositions as well as live performances, and is the first programing system that allows a live loop. This means the user to change the code while it is playing the music and therefore create a continually growing tune. Sonic Pi comes pre-installed with sound loops that can be manipulated by changing the speed, bass levels and repetitions to create your own unique songs.” (Miller, 2017)

Orca
Although not as popular as above-mentioned live coding environments, the software has unique interface and approach to music composition. Orca looks like an old-school roguelike RPG game with minimal ASCII graphics. Labelled as “esoteric programming language” by its creators it is indeed a very accurate description of this environment. However, the method of sending information via “bangs” is quite similar to Max MSP/Pure Data workflow.    


Description of TidalCycles project

The whole transcript of the code can be accessed via the github link - https://github.com/rufusld/rufusld/blob/master/tidal_project.tidal
For my practical part of the project I chose TidalCycles as the live coding environment and Atom as a text editor. Coming from the electronic music background, TidalCycles was easier for me to get into due to its pattern-based workflow. 
Patterns are labelled as d1, d2, d3, etc. My tidal project has nine patterns (each pattern for each instrument). They are described below. 
D1 – kick drum (sample)
D2 – snare drum (sample)
D3 – percussions (sample)
D4 – hi-hats (sample)
D5 – synth pad (sample)
D6 – superfork (synthesizer)
D7 – supercomparator (synthesizer)
D8 – superpiano (synthesizer)
D9 – 808 bass (sample)
The idea was to make a Trip Hop composition with applied swing effect drum line similar to 90s flavour. This is achieved by using “swingBy” function on hi-hats.
 
$ swingBy (1/30) 8 will delay every other hi-hat 1/30 towards the next hi-hat.
All drum elements are also bit-crushed with “crush” effect. This is done to replicate old-school drum machine sound.      Digit represents the amount of bit-crushing. 
Each pattern is panned differently to widen up the stereo field of the mix.   The allowed values are from 0 to 1 with 0 being hard left and 1 hard right. 
#gain represents the volume for each sample or note. 
  
In the example above there are 16 hi-hats in the loop and programmed volume values for each hi-hat. 
The reverb is applied for each pattern of the track.  
The #room function controls the reverb effect amount. #Size controls reverb room decay time. It turns a number pattern (ranging from 0 to 1) into a control pattern that controls the room decay time of the reverb effect. The #dry function controls dry/wet amount. 
The #slow function slows down a pattern.  
In this example, the percussion pattern is being played twice as slow. In other words, it repeats once every two cycles. 
On pattern 5 there is a synth pad sample. 
 
The #octer function is an octaver which uses `octer` for octave harmonics, `octersub` for half-frequency harmonics, and `octersubsub` for quarter-frequency harmonics. This effect adds additional harmonics to the pad sample. The #hpf effect is a high pass filter. Everything below 700Hz was filtered out to reserve space for bass and kick drum. #vowel is a formant filter to make things sound like vowels, a pattern of either `a`, `e`, `i`, `o` or `u`.
As this is the live coding project, majority of the parameters will be changed on the go during performance in order to keep it interesting for the listener. 

Conclusion
The live coding approach to music can improve improvisational capabilities and bring unexpected results. Music programming is an ideal environment for finding fresh approach to music composition and/or performance. This is especially true for experimental non-mainstream types of music. I will definitely use TidalCycles environment in my future project. My next step will be researching the method of sending the MIDI information out of TidalCycles into a DAW. I would like to use live coding to control external virtual instruments.  




























Bibliography
Algorave website (n.d.). Algorave about page. [Online] Available from: https://algorave.com/about/ [Access date 20/01/20]
Allieway Audio (2019). ORCA Sequencer Intro (Experimental Livecoding!). [Online] Available from:  https://youtu.be/RaI_TuISSJE [Access date 20/01/20]
Kretowicz, Steph (2017). Artists across the world are redefining what it means to create music with a laptop. [Online] https://mixmag.net/feature/algorave [Access date 20/01/20]
Miller, Sarah (2017). What is Sonic Pi? [Online] Available from: https://www.fdmgroup.com/what-is-sonic-pi-2/ [Access date 20/01/20]
Supercollider website (n.d.). Supercollider main page. [Online] Available from: https://supercollider.github.io/ [Access date 20/01/20]
TidalCycles website (n.d.). TidalCycles welcome page. [Online] Available from: https://tidalcycles.org/index.php/Welcome [Access date 20/01/20]
TOPLAP website (n.d.). Toplap about page. [Online] Available from: https://toplap.org/about/ [Access date 20/01/20]
Victor, Bret (2012). Learnable Programming. [Online] Available from: http://worrydream.com/LearnableProgramming/ [Access date 20/01/20]


Word count - 2149
