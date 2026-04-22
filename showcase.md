---
title: "Showcase"
description: "Featured Compositions by ICM S26 Students"
featured_image: ""
---

# Showcase
Here you can listen to some of the creative projects that students in our class have composed! Some projects also include composer’s notes and source files so you can read about their vision or see how they accomplished their creative goals.

## [Project 7 : Computer Music Composition ](/projects/7)

### [Concert](/concert/)

<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
It’s been our pleasure to meet so many of you, and we’re truly amazed by the music you’ve created.
Enjoy the concert, and good luck on your finals!
</i></div>

<br>
<br>

## [Project 6 : Physical Models and Patterns ](/projects/6)

### Salina Mu
<audio controls="" src="./static/showcase/s_mu_p6.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
My goal for this piece was to create battle music for animated characters. I used nested pattern generators for the 'build' at the start of the piece to transpose the pulse with each repetition.
</i></div>

---

### Kai Okorodudu
<audio controls="" src="./static/showcase/k_okorodudu_p6.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
The idea for this one was to have each instrument play at a different division of time. The low notes play once every transposition, where the mid-freq and high-freq instruments play at a 4:1 ratio. Every so often, the ensemble transposes like in the warmup, to add variety.
</i></div>

---

### Victor Norton
<audio controls="" src="./static/showcase/v_norton_p6.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
I already had chords and a repeating melody in mind that I had come up with recently, 
so the challenging part was incorporating random patterns without compromising my 
musical goal. I first made the bass part of the song jump up and down octaves by a 
random pattern similar to the offset from F6(), with the offset lasting for 2 notes 
instead of 20. Then I used make heap to make a simple repeating melody with a 
vibraphone sound. Finally, I used make-heap() and a very small ioi to make the shimmery 
chords with the sax synth that you hear in the second part of the song. 

Ultimately there are 4 voices, mandolin playing the repeating cycle, wg-uniform-bar for
the bass, modal-bar( mode = quote(vibraphone)) for the melody, and sax for the chords.
</i></div>

---

### Justin Wang
<audio controls="" src="./static/showcase/j_wang_p6.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
Intention
*********
This piece is a DIY Choose-Your-Own-Adventure composition meant to be completed by both you and the computer!

While the computer generates the score algorithmically using a variety of pattern generators and nested patterns, you, as the user, are in control of the hyperparameters! For example, you get to choose whether the bassline is plucked or bowed, whether the melody line should be played by a saxophone, clarinet or vibraphone and how long the overall piece should be.

More detailed instructions can be found within the code. Happy composing! :-)


Motivation
**********
Given that algorithmic composition is allowing the computer to determine certain aspects of a piece, I decided to take this one step further and let the user decide the other aspects of my piece. Heavily influenced by the structure (and not the style) of pop-punk bands from the early 2000's, my composition includes a backing drum track, a bassline and a melody. However, this doesn't come without its own set of challenges. Given that there are three independent and simultaneous voices, the likelihood of dissonance occurring is (relatively) high. Therefore, I decided to compose this piece in a major pentatonic scale, where (dissonant) collisions are less likely to occur. This allows for a more balanced algorithmic design that still manages to sound pleasant to the ear, no matter how many times you generate a new score. Furthermore, the pentatonic scale is one of my favorite scales as it (usually) produces uplifting melodies, which are further emphasized in my piece by the lighthearted bassline and backing drum.

The melody is created using a pattern generator while the backing rhythm and bassline are both generated from nested patterns. Delays are added at the start of the piece to emphasize the arrival of each individual voice. Multiple helper functions were created to aid with generating patterns using various different instruments. Given that the intention of my piece is so that the user can participate in its composition, the pattern generators were carefully crafted to ensure that repeated runs of the code would continually generate pleasant results.
</i></div>

<br>
<br>


## [Project 5 : Sampling and Spectral Processing ](/projects/5)

### Yuxin Miao
<audio controls="" src="./static/showcase/y_miao_p5.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
In my piece, I've mainly used two spectral processing functions that I've wrote that acts as a low/high pass for the magnitude of the frames. These magnitude low/high pass functions will only include frames with a magnitude that's within the pass. Since the source sounds that I've used are all mostly orchestral sounds, I aimed to make the composition sound orchestral as well, with a bit of dark/mysterious atmosphere to it. The composition is made entirely of the outputs of different spectral processing runs when edits done in FL Studio.
</i></div>

---

### Victor Norton
<audio controls="" src="./static/showcase/v_norton_p5.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
I first made some arpeggios (my favorite musical pattern) using the mysampler function.
Then I recorded some vocals over it, orginially planning on vocoding them to the melody.
Instead I realized that it was taking a long time to process and probably wouldn't 
sound good anyways, so I recorded some shorter rap bars and vocoded them to some 
background singing. By vocode I mean spectral cross synthesis from example 4. The song
has the original singing at first and only really has the spectral synthesis at the end. 
</i></div>

---

### Anthony Samms
<audio controls="" src="./static/showcase/a_samms_p5.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
I created a beat with the main sample created with spectral processing. I created a synth, exported it, and then cross synthesized it with an opera sample I found online to create a unique overlay. I then added a small drum loop and a bass to accompany with some other flourishes. It took a lot of time to put the sample in a usable state, as I had to chop and retune certain notes of the original sample for it to not sound out of place when the spectral processing effect was used.
</i></div>

---

### Ryan Zhang
<audio controls="" src="./static/showcase/r_zhang_p5.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
So for my composition I just used the inputs used for the cross-synthesis (a Tibetan chant and a Tibetan prayer recitation) and the sampling exercise. I then used the output instrument from those exercises, and created new various sounds (spectral inversion, glitched effect through removing frequencies). Using the produced sounds I manipulated further with effects such as delay reverb and chopping up the samples to create this experimental Tibetan-inspired soundscape.
</i></div>

<br>
<br>

## [Project 4 : Granular Synthesis](/projects/4)

### Vishwajeet Avinashilingam
<audio controls="" src="./static/showcase/v_avinashilingam_p4.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
The general idea was to make something that was ambient, but with the granular sounds providing for an interesting texture. Hence, I used very slow pitch and amplitude sweeps to create textures, imported them into my DAW, added a slight bit of reverb, and had a simple progression going underneath it with a sine sub and simple pads. I was listening to some slow deep melodic house on a rainy day, and it inspired me to make something ambient and chill!
</i></div>

---

### Yuxin Miao
<audio controls="" src="./static/showcase/y_miao_p4.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
I’ve varied the amplitude and pitch by letting the make-granulate-score function keep track of the percentage of the score it has currently generated, and then scaling the velocity and speed of the file-grain function by this percentage to create sounds that are increasing in amplitude and increasing in pitch. The sounds generated by proj4comp.sal are then imported into FL Studio, where the more nuanced pitch changes and audio mixing are done.

The goal of my composition is to create a suspenseful piece that conveys the feeling of being a diver stuck deep underground, with the diving suit starting to fail, and the diving helmet starting to crack. The overall atmosphere is designed with the horror experience of playing a game like Subnautica in mind. 

The source sounds used are 
	Dystopian Tension Siren by MursilProduction
	Nasty Knife Stab 2 by Aris621
	breakwater small waves wind river Maas Bokhoven 752 pm 2500611_1026 by klankbeeld
</i></div>

---

### Kai Okorodudu
<audio controls="" src="./static/showcase/k_okorodudu_p4.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
I vary the amplitude with envelopes, and wih a velocity parameter I added to both instruments. The pitch is also a parameter, and it's further modulated by an LFO on the vibrato instrument. For the granular instrument, I guessed which pitch the wind chimes were already at, and used a simple formula to convert an inputted pitch parameter to the amount to alter the original sample by.

I added vibrato as an extra effect on my oscillator instrument. I also kept the randomness as a parameter for the grain instrument.

When I found the wind chimes sample, I decided to try to build everything around that. I went with pretty minimal instrumentation to keep it focused on the chimes, and because I wanted the whole thing to feel pretty comfy to listen to. At the end I overlay several wind chime instances at once for a more dramatic finish.

Here's the wind chime sample: https://freesound.org/people/acclivity/sounds/30606/
</i></div> 

---

### Anthony Samms
<audio controls="" src="./static/showcase/a_samms_p4.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
origin sound from https://freesound.org/people/gettinsomegamesounds/sounds/847481/


I tried to use granular synthesis to create stems for a beat. I ran the code I wrote in the sal file to get various samples; one using sine tones, one using the sample I picked and one using the default sample that was provided. I then cut up the output samples again, and repitched + added reverb and a sine wave bass in audacity to create something musically viable.
</i></div> 

---

### Ryan Zhang
<audio controls="" src="./static/showcase/r_zhang_p4.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
I varied the amplitude by multiplying my snare and hihat sounds by a pwl envelope to shape the amplitude. I varied pitch first by tweaking the ioi parameter until I reached the note C, then I loaded the sound to a DAW and created an instrument from this middle C sound.

I added delay and reverb on the synths, and reverb on the drums in the DAW. I also EQed the instruments.

For the composition, I wanted to see if I could make something from this one sample I downloaded of a German guy talking. I created drum sounds and two synth sounds from it all using granular synthesis and then from there I made a basic house beat and overlaid some jazz fusion on the synths. 

Source Audio: german.aiff
Sounds generated in Nyquist: kick.wav, snare.wav, hihat.wav, synth1.wav, synth2.wav
These sounds were then manipulated in a separate DAW
</i></div> 

<br>
<br>

## [Project 3 : FM Synthesis, Spectral Centroid](/projects/3)

### Vishwajeet Avinashilingam
<audio controls="" src="./static/showcase/v_avinashilingam_p3.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
With this, since it was FM - I wanted to go the weird neuro/dnb direction. Kept it simple, with different subsections having minor variations. I used no other sounds - all sounds you hear were designed from the original FM sample - a lot of sound design - filtering, compression etc.
</i></div>

---

### Salina Mu
<audio controls="" src="./static/showcase/s_mu_p3.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
I used my voice to produce sounds for analysis by spectral centroid. Then I used the spectral centroid as the im for a melody I created. The melody was meant to sound like a beginner's piano piece that you would learn when you were a kid.
</i></div>

---

### Victor Norton
<audio controls="" src="./static/showcase/v_norton_p3.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
I first used my fminstr to make a synth melody using create-cycle and ~ to compress 
the sound to a speed I liked. Then I made an audio recording of myself singing over 
the melody, used audacity to try to reduce noise and to align the recording with the 
sound of the melody, then used that voice recording as the input audio for the spectral
centriod. Using the SC as the index of modulation on fminstr as it replays the original
melody results in a shimmery sound that reacts to the singing. Playing them at the same
time on audacity gives a somewhat cool effect, though there seems be some noise and 
weird artifacts. The final composition is the orginial melody playing once followed 
by the modified melody and vocals played simultaneously.
</i></div>

---

### Lynn Ye
<audio controls="" src="./static/showcase/l_ye_p3.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
The composition aims to create a rhythmic vibe with all kinds of strange sound, pushing user into a colorful world of FM synthesis. The call and response in the main melody intends to create a sense of space together with the reverb. 

Most of the instruments use origin/beat.wav for the modulation index. As a result, you can hear the syncopated rhythm characteristic of the beat.wav.
</i></div>

<br>
<br>

## [Project 2 : Envelopes and Scores](/projects/2)

### Isidore Lu
<audio controls="" src="./static/showcase/i_lu_p2.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
I wanted to splice up three different versions of the score played by different sounds I designed to create a light and comical soundtrack to someone clicking and exploring a web page.
</i></div>

---

### Salina Mu
<audio controls="" src="./static/showcase/s_mu_p2.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
I wanted to make a song with many layers and two parts, the second part an octave above the first. Additionally, the first part has a slowed sound underneath that is offset from the sounds above.
</i></div>

---

### Yuyang Shan
<audio controls="" src="./static/showcase/y_shan_p2.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
In this p2comp.wav file, I am trying to keep developing a melody by adding more layers constantly and make the last repetition slower to create a more dramatic effect.
</i></div>

--- 

### Ryan Zhang
<audio controls="" src="./static/showcase/r_zhang_p2.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
I generated the score based on the perfect squares 1, 4, 9, 16, 25. I used the random function to randomly generate the series of notes. Then I generated 3 tracks using 3 different instruments. Then on Audacity I changed the pitches of the clips and spliced the clips to create something interesting. The result was like a randomly generated electronic canon with the melody played at irregular rhythms.
</i></div>

---

### Alex Kirages
<audio controls="" src="./static/showcase/a_kirages_p2.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
The goals of my piece were to follow a musical pattern ending with a happy high note to bring joy to the community.
</i></div>

<br>
<br>


## [Project 1 : Audacity and Crossfading](/projects/1)

### Isadore Lu 
<audio controls="" src="./static/showcase/i_lu_p1.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
I wanted to use a vocal sample for a primarily arppeggiated sequence, drawing inspiration from Laurie Anderson and A.G. Cook.
</i></div>

___
### Simone Lu 
<audio controls="" src="./static/showcase/s_lu_p1.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
This composition was created to build a Chinese-style horror atmosphere using environmental sounds and traditional musical elements. I wanted the listener to feel like they were walking alone through a quiet, rainy street at night.

At the beginning, I tried different sound combinations, but the mood felt too flat. After adjusting the volume and timing of the rain, bell, and ghost whispers, the atmosphere became much more intense. The slow ghost voices gradually turning into faster whispers helped create a growing sense of tension.

I added the pipa sound between the ghost voices to give the piece a more traditional Chinese feeling. The wooden door sound at the end was placed to make the ending feel sudden and unsettling.

This project helped me understand how layering sounds and shaping volume can change the emotional impact of a composition.
</i></div>
___
### Atul Thyvalappil 
<audio controls="" src="./static/showcase/a_thyvalappil_p1.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
This sound transitions between an eerie hiss and a 2-note mode, meant to create suspense and a sense of impending doom (the recurring ticking, and the modulation between quiet and loud tones).
</i></div>

___
### Lynn Ye 
<audio controls="" src="./static/showcase/l_ye_p1.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
A canon-like composition based on one single musical motif, with some harmonic progression and contrast between homophonic and polyphonic textures.

</i></div>

___
### Zhengnan Zhu
<audio controls="" src="./static/showcase/z_zhu_p1.wav"></audio>

**Composer's Notes**
<div style="height:200px;overflow:auto;border:1px solid #000;padding:10px"><i>
A moving soundscape that follows a person reading and circling out important ideas while walking through a city street. All sounds samples and music were recorded on an iPhone.

</i></div>
