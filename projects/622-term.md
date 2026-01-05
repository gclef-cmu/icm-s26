---
title: "15-622 Term Project (Grad students only)"
description: ""
---

# 15-622 Term Project (Grad students only)

## Key dates:

**<span style="color:red;">For grad students only, a discussion about this project will be held immediately after exam 1 on Wednesday February 11. (Exam 1 is only 40 minutes).</span>**

**Proposal due Wednesday February 18**. If you need more time, this may be submitted **_no later than February 25_ at 11:59PM** if you need more time, but better to submit early to allow more time to iterate on the proposal with the instructor.

**Interim Report due Wednesday, April 1**.

**In class presentation on Monday April 20 or Wednesday April 22** (you will be assigned to one of these dates).

**Final written project report due Friday April 24 at 11:59PM**

## Overview

Every 15-622 student is required to complete a term project (in addition to the final composition that is also created by 15-322 students). These projects must be completed individually (no teams). This is designed to be much more open-ended than the other class projects and can make use of other technologies you are interested in.

By default, this will involve proposing and executing a **computer music software engineering project**, broadly defined. Within scope would be things like:

1. Building a library of Nyquist utilities and using them to realize an ambitious computer music piece
1. Contribute to a library called [`pyquist`](https://github.com/gclef-cmu/pyquist) which will be used in future iterations of the course
1. Developing audio plugins (VST, AU, etc.) in C/C++
1. Creating interactive web-based music applications in JavaScript
1. Recreating a famous piece of computer music in a modern computer music system
1. Create a set of online computer music learning materials combining technical explanations with interactive demos
1. Extending open source tools we've used in class like Nyquist or Audacity

If you prefer, you may also choose to propose a **computer music research project**. However, research is harder to properly scope to particular time constraints. Accordingly, you would have to work w/ the instructor to ensure that your project has a high likelihood of being achieveable before the end of the semester. Within scope would be things like:

1. Implementing classical techniques from computer music research papers in Python or Faust
1. Deploying a modern music AI technique on synthetic data and measuring generalization to real-world data
1. Training existing models on new datasets and measuring performance

_Students who are primarily composers are not expected to build complex software systems, use JavaScript or C, or write complex digital signal processing code._ Your options include but are not limited to:

1. Porting algorithms from other systems to realize an instrument (not necessarily a traditional one), to create an effect, to implement an automatic composition algorithm, etc.
1. Recreating a famous piece of computer music in a modern computer music system
1. Pursuing a sophisticated approach in your composition project that involves substantial use of advanced computer music techniques, probably resulting in a longer-than-required composition

## A few example project ideas

These were implemented by students in last year's course:

1. Nyquist toolkit for creating Synthwave music
1. VSCode extension for Nyquist development
1. Real-time web-based compressor in the Web Audio API
1. Modeling specific composers using Markov chains
1. Real-time C++ vocoder in JUCE
1. Nyquist toolkit for sonifying chess games
1. Real-time sample delay plugin in JUCE
1. Real-time distortion plugin in JUCE
1. (Research) An [infinite MIDI generation tool](https://arxiv.org/abs/2411.09625v1)

Other project ideas from past years:

1. Implement a convolution reverb as a VST plugin in [JUCE](https://juce.com)
1. Create an interactive sequencer in JavaScript that can play back audio samples
1. Create a guitar tuner application using [Pyin](https://ieeexplore.ieee.org/document/6853678)
1. Program a virtual analog instrument using [Faust](https://faustide.grame.fr)
1. Reverse engineer the time-varying FM synthesis parameters in John Chowning's "Stria"
1. Interactive online computer music learning materials [example](https://chrisdonahue.com/js_audio_examples)
1. Write a VS Code extension for Nyquist with syntax highlighting and sound playback

## A successful past project

This project was done by Chris Yealy and is now part of Nyquist, but we will describe it as if it has not been done: The latest Nyquist IDE (based on a project from a previous class) is great for editing text and displaying sounds (at least short ones), but there is no support for entering functions of time. This project adds a new view to the IDE allowing the user to edit piece-wise linear functions of time. Each function has a name, and multiple functions can be stored in one file. The functions are implemented by defining a Lisp function containing a call to PWL. If the user creates a time function named foo in the IDE, then the user can write foo() in Nyquist code to obtain the function. When the user opens one of these files in the IDE, the IDE parses the code and can then display functions graphically. The user can add, move, and delete breakpoints, change function names, copy functions to a new name, etc. It would be great to be able to display multiple functions in different colors so they can be edited in concert. Also, it should be possible to snap to user-controlled grid lines, zoom in or out, change the vertical axis, etc.

Having convenient direct-manipulation access to functions of time opens up a new way to control synthesis. Complex sounds with several parameters can be made to evolve according to time-varying controls that are edited graphically. These parameters in the editor become a sort of musical score notation.

Some reasons why this project was a good one:

1. It’s Computer Music: there’s computation, and there’s music.
1. It requires some thought about music representation and music processing.
1. It extends Nyquist (or Audacity). Notice that the project is not even a complete stand-alone system, only the extension of one, so the student does less work and leverages what’s already there.
1. The project isn’t too easy, but it’s not impossibly hard.
1. Students will be able to use this in the future.

Your project will probably not have to have all these features, but we hope this gives you a good idea of what we am looking for. Review the list above with respect to your project.

# The Term Projects in Stages

The project has several parts:

## Part 1: Proposal (due <span style="color:red;">Wednesday, February 18, 2026</span> – may be submitted up through Wednesday, February 25, 2026 if you need additional time)

A proposal is required. Your proposal should state clearly:

- the general nature of what you will implement,
- what code, journal articles, etc. you will rely on, port, implement, modify, etc.,
- a significant milestone that you will report/deliver as the interim report (note, due on April 1st, so think about what you can do in about a month)
- a specific list of deliverables for your final project submission
- how will you measure your success? E.g. what functionality will you demonstrate?

All projects must be approved by the instructors, so this really is a proposal. We will usually suggest some changes, and if the project really seems out of line, we’ll let you know early and without penalty. (A clear proposal for a bad project gets a good grade and a request for another submission, a vague proposal for a good project gets a bad grade and an OK to proceed).

**SUBMISSION: Submit your proposal (as a PDF file) by email to chrisdonahue@cmu.edu with the subject “15-622 Proposal”. Please CC tcortina@cs.cmu.edu as well.**

## Part 2: Interim Report (due <span style="color:red;">Wednesday, April 1, 2026</span>)

An interim report is required. Ideally, you will have completed the milestone described in your project proposal. If you fail, you should describe clearly what you have done, what problems you encountered, whether this will affect your ability to finish the project as planned, and any modifications (subject to instructor approval) you feel you should make to the project.

**SUBMISSION: You should submit the report as a PDF file by email to chrisdonahue@cmu.edu. Please cc tcortina@cs.cmu.edu as well.** You may attach a zip file with interim code as long as the TOTAL submission including PDF is less than 1MB. If you have sound results, more code, and other data to substantiate your report, put it somewhere on the web and include a link in your email.

## Part 3A: IN CLASS Presentation (<span style="color:red;">Monday, April 20, 2026</span> and <span style="color:red;">Wednesday, April 22, 2026</span>)

You will present your project to the class. Plan for 10 minutes maximum. This is a very short presentation. You should present your work in three parts. Use slides (preferably PowerPoint) to supplement your talk.

1. Motivate your work. What purpose (outside of your education) is served by your project? What existing problem does your work solve? (1 slide)
2. State your approach and goals. How does your project solve the problem just stated? Be sure to state clearly and with some detail exactly what you did. (1 or 2 slides)
3. What is the state of your project? Tell what is complete and working as well as what would be the next step if you (or someone else) were to continue working. (1 slide)

_If you have sound file examples (recommended):_

- be prepared to play sound files from your computer
- be sure you know how to share audio in Zoom and test this with a friend to make sure the sound levels are reasonable
- be ready to show any interactive demo you may have, though also have sound examples as a backup!

Please rehearse your talk. It is expected to be fairly polished, be precisely timed, and effectively communicate your achievements w/ the undergraduate students.

## Part 3B: The Final Written Project Submission (due <span style="color:red;">Friday, April 24, 2026</span>)

Your goal is to prepare a complete package of software, documentation, example code, and sound examples. For example, if your project were to create a phase vocoder, you would submit the software implementation, document how to apply the vocoder and use all the parameters, provide code examples that apply the vocoder to a test sound, and one or more sounds that illustrate the effect of the vocoder. Another student should be able to use the vocoder given your final submission. **Your submission should reflect what you presented during the week in class. You should not be changing significant portions of your project between the presentation and the written project deadline.**

**SUBMISSION: Put everything in a zip file, submit this zip file to chrisdonahue@cmu.edu and CC tcortina@cs.cmu.edu.**
