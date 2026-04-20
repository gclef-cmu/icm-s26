# Project 7 Concert

Pieces marked with <span style="color: #1a6fd6">\*</span> were declared fully executable in Nyquist and are eligible for the Dannenberg Award.

## 01: Anthony Samms  - Ode to Naikia

I've created a piece that blurs the lines between what you may think came from Nyquist and what was created on my own. The piece is short and sweet, so I hope you enjoy!

<audio controls src="media/01.mp3"></audio>

<h2 style="color: #1a6fd6">02*: Amethyst Unknown  - SPECTRAALIZATION</h2>

A nyquist adaptation of a spooky, possibly melodramatic song I composed for piano originally. Mixed by brute force. Coded haphazardly under time pressure of course. The random part is the fast arpeggios at the start. 
Somethings happening up ahead. The path is dark, the light is red. At least I know enough to accept I'm stronger than the parts I left. The spectralization was an attempt to immortalize your final breath, a pale imitation of your flesh.

<audio controls src="media/02.mp3"></audio>

<h2 style="color: #1a6fd6">03*: Anirudh Mani  - As the Day Fades</h2>

This piece imagines a figure watching the city from above as the workday comes to an end. At first, the city feels distant and quiet, with most people still inside. As the day fades, the streets fill with movement as people leave their offices and head into the weekend. This activity gradually slows, leaving behind a quieter, more reflective atmosphere.

The piece is built from layered sounds that reflect these changes. FM-synthesized chords (fmosc) provide a steady harmonic background, while plucked sounds created with the Karplus–Strong model (pluck) introduce irregular, shifting patterns that mirror the movement of people below. The timing of these plucks is partly controlled by a simple Markov process, so the patterns evolve rather than repeat exactly. A soft, breath-like vocal layer is created using granular synthesis, where small fragments of sound are rearranged using functions like extract-abs and randomized placement. This creates a drifting texture, like a quiet exhale at the end of the day.

As the density of these layers increases and then recedes, the music follows the rise and fall of the city’s activity, ending in a more subdued and reflective state as the city goes quiet for the final time.

<audio controls src="media/03.mp3"></audio>

<h2 style="color: #1a6fd6">04*: RPV  - Reincarnated as a caveman and these rocks kinda hit??</h2>

comp1.sal generates the shouting.wav file from source/shout and source/hmm
The first part of the composition(up until the screaming chicken)'s code is all in fin.sal
uglyflute.sal ended up not being a flute, and is only used in the beginning the create a flat background pitch.
Melodies.sal creates the rest of the composition with score-gen functions and make-functions.

<audio controls src="media/04.mp3"></audio>

<h2 style="color: #1a6fd6">05*: Daniel Shan  - Haunted House</h2>

This piece is divided into two halves with distinct characters. The first half features melodic lines performed by physical models of acoustic 
instruments, including flute and saxophone. Harmonic structure and rhythm are generated using nested patterns for score processing, creating a tense but coherent musical texture.
The second half shifts into more experimental territory. Cross-synthesis combines a recording of laughter with organ tones, producing an unsettling hybrid sound. Reverb is applied heavily to blur the sense of space. Physical models are used more aggressively, pushing instruments beyond their natural range. The original melodies from the first half are still present, stretched and buried underneath the effects, though they may be difficult to notice.
The piece was an exploration of how familiar musical material can be gradually transformed into something strange through the use of computer music techniques.

<audio controls src="media/05.mp3"></audio>

## 06: Anonymous  - Playing Poker

A poker table has its own music: chips whisper, cards strike the felt, hands fold, wait, and begin again. This piece begins inside that repetitive, slightly numb table-time, where boredom is the background condition and drama only matters because it interrupts routine.

The form follows two hands. In the first, the player finds a rare moment of certainty: a strong hand, aggressive betting, a call, and release. The table suddenly brightens. Familiar chip and card sounds open into granular textures, and FM tones rise out of the noise like a rush of adrenaline. The jackpot functions as a brief structural flash, not just a sound effect.

Then the room settles back into ordinary waiting.

The second hand returns with unease already present. Similar gestures reappear, but now they are more unstable: spectral heartbeat textures, brittle physical-model attacks, and a score-driven betting line that keeps pushing toward greater risk. The river misses, the bluff comes, and the final call drains the sound field rather than resolving it. The piece ends not with triumph, but with the collapse of performed confidence.

<h2 style="color: #1a6fd6">07*: Kate Lee  - Dissolution of Memory</h2>

This piece traces the slow unraveling of a simple melody. What begins as a clean, intimate mandolin theme, grounded by a steady bowed bass, is subjected to increasingly aggressive forms of corruption across four movements. In the first, imperceptible timing errors and microtonal detuning introduce doubt. In the second, the bass accelerates into eighth-note figures, a random harmonic voice intrudes, and a sitar drone swells underneath, pulling the music toward chaos. In the third, FM synthesis replaces the mandolin entirely: the melody survives in pitch only, its timbre growing more metallic and unrecognizable with each note, while the tempo itself slows and distorts and audio starts clipping. Throughout, the left hand drifts lower and further out of tune, as if losing its footing. The piece asks: at what point does a melody stop being itself? The answer, reached gradually, is that identity dissolves not in a single moment but through accumulation— small corruptions, compounded.

## 08: Yuxin Miao  - Wandering At Night

This piece aims to capture the feeling of wandering alone at night. The chords used are a bit dark, but shouldn't be in a way that's creepy or unsettling. The first half of the piece emulates the soothing feeling of slow stepping in the calm breeze of the night. Then, the piece transitions into a series of arpeggios that mimics the feeling of a sudden burst of freedom, which then quiets back down into the night. Reverb is added to basically all sounds used in this piece to help create the atmosphere. The arpeggio is generated using Nyquist pattern generation at random, under some constraint of the chords, so technically every rendition of this piece would have a slightly different arpeggio section.

<audio controls src="media/08.mp3"></audio>

<h2 style="color: #1a6fd6">09*: Anonymous  - Arcade Crush</h2>

Have you ever been in an arcade after the sun has set and felt like you were transported to another reality? The one outside the glass doors of the arcade disappears and you’re left in a world that is built bit by bit, block by block, then destroyed the moment you read the game over on the screen. I really wanted to use the bit crushing technique we discussed in class (I hope people find this as cool as I do) and the idea of a warped and distorted arcade game audio sounded like an interesting idea to play around with. I hope you enjoy!

<audio controls src="media/09.mp3"></audio>

<h2 style="color: #1a6fd6">10*: Lynn  - Extraterrestial Visitor</h2>

This composition is based on the idea that listeners tend to perceive intervals more readily than absolute frequencies. An algorithm scans two piecewise linear functions (one increasing one decreasing) and identifies points where their frequency ratios approximate predefined just intonation ratios. At these moments, the piece briefly settles on the resulting harmonic interval, with chords that are either manually selected or randomly generated according to the interval type.

The B section, in contrast, uses fixed A=440Hz. However, microtonal harmonies are inserted to create interesting progressions, e.g. something like I iii iii- ii+ ii V I (not totally accurate but hope you get the idea).

<audio controls src="media/10.mp3"></audio>

<h2 style="color: #1a6fd6">11*: Anonymous  - Music Box Collection</h2>

This piece was inspired by the sound and feeling of four imagined music boxes, each one with a slightly different character from the rest. The first music box is sweet and simple and we end up with a broken ominous one. My goal was to create a whimsical atmosphere, while also introducing contrast through texture, pacing, and transformation across sections.

<audio controls src="media/11.mp3"></audio>

## 12: Anonymous  - Mercurial shifts

I designed this as a quickly shifting journey through multiple ideas.
It starts with a sort of an upbeat hazy portion, and then harshly transitions
into a cloudy bitcrush that shifts into an EDM-inspired section, and then it 
finishes with a spectral sample of an underwater sound. 

I used multiple different techniques from class. FM synthesis is used across most 
instruments to create distinct timbres. This is combined with Markov chains to 
generate the meloidies. LPC vocal synthesis appears in both the intro 
(pitched-down vocal textures) and outro (choir-like harmonies). Granular 
synthesis produces a shifting bed. In the outro, spectral processing stretches 
audio into a cloud-like texture. Bitcrushing is used as a transition as well.

I used panning and fade-ins/outs within Nyquist, as well as echo and reverb in
Audacity to further mix the composition.

<audio controls src="media/12.mp3"></audio>

<h2 style="color: #1a6fd6">13*: Anonymous  - Stressful Deadline in the Dark Hole</h2>

This composition captures the anxiety of coding late at night under a looming deadline. The piece opens in a shadowy sonic landscape, where granular synthesis creates an eerie swirl of digital dust. Algorithmic Markov chains generate unpredictable notes with a designed chord progression, mirroring the disorienting frustration of debugging code.
As the deadline approaches, the granular chaos recedes, giving way to an aggressive, relentless drum and bass groove that drives the momentum forward. A metallic, FM-synthesized main melody—built on perfect fifths—cuts through the mix, reflecting the intense, hollow focus required to push through the night and finally hit "submit."

<h2 style="color: #1a6fd6">14*: Dario Quintero  - Happy Birthdy America</h2>

The Star Spangled Banner replayed with physical modeling, and Markov chains.

<audio controls src="media/14.mp3"></audio>

<h2 style="color: #1a6fd6">15*: ryan zhang  - computer dreams</h2>

Sometimes we are in a position when we question our senses. The digital world can consume our consciousness. The fabric of reality is indeed so fragile. Digital scenes. Computer dreams.

Further Notes: I took heavy inspiration from liminal spaces and the video game Earthbound. I consolidated a variety of techniques such as granular synthesis, FM synthesis, sampling, and Markov-chains to make this surrealist work of contrasting textures.

<audio controls src="media/15.mp3"></audio>

<h2 style="color: #1a6fd6">16*: Kai Okorodudu  - "indoor"</h2>

Meant to evoke the sense of the world going by outside your window. The composition uses answering machine sounds, layers of synth, and various ways of distorting the audio, to create a sense of comfort, yet dissatisfaction.

Freesound sounds used:
	https://freesound.org/people/ERH/sounds/31349/
	https://freesound.org/people/ChrisReierson/sounds/384005/

<audio controls src="media/16.mp3"></audio>

<h2 style="color: #1a6fd6">17*: Collin Greco  - Precipice of War</h2>

This piece aims to capture the sounds of the medieval battlefield and the feelings of valor and sorrow that the soldiers of that time might have felt, standing at the precipice of war. It applies granular synthesis and spectral processing to create ominous sounds like warhorns and wardrums. Additionally, the piece samples a trumpet clip which is applied in an attempt to characterize feelings of valor, and uses the physical models of the mandolin and flute, aiming to exhibit alternative feelings of sorrow.

<audio controls src="media/17.mp3"></audio>

<h2 style="color: #1a6fd6">18*: Anonymous  - Where the Stars Drift</h2>

<audio controls src="media/18.mp3"></audio>

## 19: SkyTim  - A Frog's Relaxing Evening

An exploration into the types of music a frog might enjoy while relaxing in a swamp.

<audio controls src="media/19.mp3"></audio>

<h2 style="color: #1a6fd6">20*: Zhengnan Zhu  - Spring Fragments</h2>

This piece explores the atmosphere of early spring through a combination of synthesized tones and environmental textures. The music begins with a light and transparent texture, gradually building density and harmonic richness over time. Wind-like noise and bird-like gestures create a sense of space and motion, while the melodic material evolves through repetition and transformation.

In the later section, the texture becomes more layered, introducing harmonic doubling and increased intensity. The piece concludes with a cadenza-like passage in C major, where the musical ideas expand freely before resolving.

The work aims to balance structure and spontaneity, combining algorithmic thinking with expressive musical gestures.

<audio controls src="media/20.mp3"></audio>

## 21: Anonymous  - Ballooning

I wanted to paint a scene of a journey through the sky in a hot-air balloon. We're above the clouds. There's soft sunlight peaking through. There are strong winds, but everything moves with a gentle slowness.

The composition is created by generating three instrument layers in Nyquist. A physical model clarinet and a horn-like FM synth are respectively sequenced in notes of a pentatonic scale. They are mixed, resequenced, delayed, and reverberated against a backdrop of lush, and mildly turbulent, granular synthesis (based on a sample of breathing) in a DAW.

<audio controls src="media/21.mp3"></audio>

<h2 style="color: #1a6fd6">22*: Yuan  - Falling Petals in Still Water</h2>

This piece is inspired by the image of petals falling onto still water, where time seems to slow down and small details become more noticeable. I wanted to combine a classical harmonic structure with a more lyrical, Chinese-inspired melodic style. The main melody is written to feel continuous and expressive, like the gentle motion of falling petals, while the piano and strings provide a stable, repeating foundation underneath, like the surface of the water carrying these subtle changes.

The image of petals drifting across still water also shaped the structure of the piece. Instead of dividing the music into clear, rigid sections, I allowed it to flow more freely, with ideas evolving through small variations over time, similar to how petals move naturally on water. Subtle recurring sounds and background textures add a sense of motion and slight unpredictability, while the overall atmosphere remains calm and slightly nostalgic.

<audio controls src="media/22.mp3"></audio>

<h2 style="color: #1a6fd6">23*: Vishwajeet Avinashilingam  - EZZA - The Prelim</h2>

EZZA - The Prelim started out with a piano idea, that I converted into a nyquist score eventually. I used reverb and delay buses interestingly - this let me process these streams separately. I tried to create an orchestration of sorts by sorting different MIDI note ranges into different instruments. A mastering EQ to boost the highs and lows towards the end.

<audio controls src="media/23.mp3"></audio>

<h2 style="color: #1a6fd6">24*: Anonymous  - Royal Road</h2>

The goal of this project was to somewhat mimic a rock song using just Nyquist, no sources used. I used the Royal Road Chord progression because I watched a video about it, hence the composition name, though without inversions or anything else it doesn't fit super well. I tried to recreate drums, bass, and electric guitar for this purpose, and put both a rhythm and lead guitar into the song. I then introduced some more electronic elements to embellish the guitar solo near the end. I modified the mandolin instrument for the bass and electric guitar, and I modified noise plus some basic oscillator tones for the drums (hat is noise, snare is noise plus tone, kick is noise plus lower tone). Pattern generation was used to add some randomness to the guitar solo to extend it. FM synthesis creates that extra instrument that plays along-side the guitar solo. Panning led to annoying clipping issues, so it's in mono, but the guitars would be better panned. It also doesn't really sound like rock by the end and the guitars lack distortion but its fineee.

<audio controls src="media/24.mp3"></audio>

## 25: Justin  - Homage to Mark 1

This piece pays homage to the earliest attempts at using computers to generate music (where "Mark 1" refers to the Mark 1 computers used back in the 50's and 60's for such purposes). Back when memory was very limited, composers had to conserve the amount of space they used when trying to synthesize entire compositions. As a result, this piece relies heavily on computer techniques such as granular synthesis and sampling (to produce tones of different pitches), frequency modulation (to mimic vibratos) and algorithmic composition (to produce melodies), so that short recordings of singular notes can be maximally used to produce complex, evolving and layered melodies, which otherwise would have been impossible to create using the earliest computers that provided the foundation for today's music.

<audio controls src="media/25.mp3"></audio>
