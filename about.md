---
title: "About"
description: ""
featured_image: ""
omit_header_text: true
menu:
  main:
    weight: 2
---

# About _Intro to Computer Music_

Have you ever wondered what is actually happening on your computer when you press play to listen to a song? Or how the audio effects in your favorite audio editing software were programmed? Or how machine learning and language models can be used to generate music? If so, this course is for you!

Welcome to _Intro to Computer Music_. Here you will learn the fundamentals of representing and processing musical information with a computer. This course is both technical and creative—think of it as the musical equivalent to a course on computer graphics. Lectures will teach computer music concepts at a high level using both programming examples and the underlying mathematics. Projects will involve programming in a domain-specific music programming language called Nyquist (developed by Roger Dannenberg here at CMU!). Some projects will be open-ended and ask you to define and accomplish creative goals. In a final project, students will demonstrate their mastery of tools and techniques through a complete musical composition played for your peers. We love to see students embrace their creative sides for these projects, though we emphasize that grading will be based on technical correctness and ambition, as opposed to qualitative evaluation of creative accomplishments.

## Prerequisites

The only course prerequisite is that you have taken _some_ introductory programming course (e.g. 15-112), or have the permission of the instructor. Below we also list a few additional informal prerequisites for the course:

**Requirements**. Some **basic programming abilities** are required. If you can write simple programs in any language (e.g., Java or Python), you should be able to follow the course and learn Nyquist. Additionally, you will need a **laptop** running macOS, Windows, or Linux.

**Recommended**. A solid understanding of calculus and trigonometry is recommended to follow the underlying mathematics behind computer music, especially for the units around spectral processing. A basic understanding of probability would be helpful for some units related to machine learning or algorithmic composition.

**Not required**. This course does _not_ assume that students have any formal musical training. You do not need to know how to read music. You also do not need to know signal processing (you will learn some basic signal processing in this course).

## Course content

_Computer music_ refers to a rather broad set of topics. This course focuses in particular on using computers to create and manipulate sound. Topics that will be covered:

- What is sound?
- How do computers represent sound?
- Sound synthesis techniques
- Basics of music generation
- Sound manipulation techniques
- Exposure to notable computer music composers and compositions

You may notice that the topics that will be covered have to do with music as an audio signal. The course will teach how to manipulate audio signals to achieve musical goals. The topics not emphasized tend to deal with music as "events" such as notes, phrases, and other structures, which can be analyzed, generated, and manipulated by computer. We will address these other topics briefly. Also not taught are techniques for real-time interactive systems (we hope to offer more courses covering these topics in the future).

## Who is this for?

This course is open to a wide range of students. It is a Computer Science course, but most of the content is orthogonal to programming or traditional computer science. If you are a great computer science student or even a great programmer, you will be able to use your special skills in this class to your advantage.

On the other hand, if you are a musician with intro-level programming skills, you can get by without writing a lot of difficult programs. Your musical knowledge and intuitions will also be of great value. However, this course does have technical content. You will need to learn and apply basic concepts of sampling theory, frequency, amplitude, spectral content, modulation, and so on. These subjects will not be taught at the level of rigor we would expect to see in an ECE course on signals and systems, but they are technical nonetheless. We expect that the CS and ECE students will learn from the Music students, and vice-versa.

## About the Instructor

[**Chris Donahue**](https://chrisdonahue.com) (Assistant Professor in CSD) is the instructor for this course. Chris is a researcher focusing on developing and responsiblying deploy generative AI for music and creativity, with the goal of unlocking and augmenting human creative potential. His work involves (1) improving machine learning methods for controllable generative modeling for music, audio, and other sequential data, and (2) deploying real-world interactive systems that allow a broader audience—inclusive of non-musicians—to harness generative music AI through intuitive controls. He focuses in particular on research with direct real-world application. For example, his work on [Piano Genie](https://magenta.tensorflow.org/pianogenie) was used in a live performance by [The Flaming Lips](https://magenta.tensorflow.org/fruitgenie), and his work on [Dance Dance Convolution](https://www.theverge.com/2017/3/24/15047328/dance-dance-revolution-ai-neural-network-choreography) powers [Beat Sage](https://beatsage.com), a live service used by thousands of users a day to create multimodal music game content. He currently works part time as a research scientist at [Google Magenta](https://magenta.tensorflow.org/).

### Other instructors

[**Tom Cortina**](https://www.cs.cmu.edu/~tcortina/) (Teaching Professor in CSD, SCS Associate Dean) will be involved as a **guest lecturer** for ICM this semester. Tom has been teaching computer science for over 34 years, including versions of computer music courses at his two prior universities, Stony Brook University and Polytechnic University (now the NYU Tandon School of Engineering). Tom and Chris co-taught 15-322 for the past two years, so many elements of the current version of the course are attributed to Tom.

[**Roger B. Dannenberg**](https://www.cs.cmu.edu/~rbd/) (Professor Emeritus in CSD) is the **original designer of this course and of Nyquist**, and may respond to your questions on Piazza from time to time. Roger is an internationally known researcher, composer, and performer specializing in Computer Music. His invention of computer accompaniment led to the creation of the SmartMusic product used by thousands of music students every day. His work on real-time techniques and software synthesis have influenced the design of many systems in use today. Dr. Dannenberg designed the programming language Nyquist, the scripting language of Audacity, a popular audio editor he also designed with his student Dominic Mazzoni. Dr. Dannenberg is currently working on music understanding by computer and advanced programming techniques for interactive music. He serves as Chief Science Officer of Music Prodigy, an award-winning music education start-up. As a performer, Dannenberg plays trumpet in the Edgewood Symphony and various jazz groups in Pittsburgh, including Capgun Quartet. As a composer, Dannenberg has written works for computer, trumpet, and chamber groups, including commissions by the Wats:On? Festival, U3, and the Pittsburgh New Music Ensemble. He has also performed his compositions in Havana, Mexico City, Paris, Pisa, and Curitiba, Brazil, as well as across the United States.

## Organization

The general plan starts with an examination of sound. What is it, how to we describe it and measure it, and how to we store it on a computer? There are some simple but profound answers, and anyone working with sound on computers needs to know them.

We will immediately begin to learn and use Nyquist. Nyquist is probably the most powerful programming language for audio manipulation, sound synthesis, and computer music composition. Nyquist was designed and implemented by Roger Dannenberg and his students, and has been in use for well over a decade. It now runs under Windows, the Macintosh, and Linux, so you will be able to use it on your favorite machine (and it is also free).

Nyquist will be used to experiment with what we learn in class. For example, if we learn about FM Synthesis, rather than listening to examples or playing with an FM synthesizer, we’ll program an FM Synthesizer in Nyquist (maybe 10 lines of code) and use it to make music. We’ll spend most of our time learning about different techniques, always exploring three aspects:

- **Theory**: What’s going on with the musical signal? How does it work? How can we determine what it will sound like?
- **Programming**: How do we express the process as a program? What are the possibilities for control and expression?
- **Aesthetics**: How do I make music with it?

As the semester moves on, everyone will be expected to create music. We don’t expect masterpieces, nor do we require a musical background. We will require an appreciation for artistic intentions and a serious effort to create something interesting. Often, the students with the least musical baggage produce the best work. We hope everyone will hear music differently after this course. The main homework assignments require music compositions that demonstrate your mastery of technical material from the course.

The culmination of the creative side of the class is a composition and public performance. Students will integrate what they have learned, produce an original composition, and present their work in a public concert.
