---
layout: post
title:  "Spanish pronunciation training"
one-liner: "TODO"
categories: projects
---
One of my favorite courses at the Master in Human-Computer Interaction was Ken Koedinger's
[E-Learning Design Principles](http://www.learnlab.org/research/wiki/index.php/E-Learning_Design_Principles_and_Methods_2016). 
We studied research-backed best practices to design effective systems for human learning.

I've always been enthusiastic about languages, having learned English at an early age, Swedish and Portuguese later.
I have noted that people who are more confident in their speaking abilities learn quicker, and my hypothesis is that
**when people attain good pronunciation skills early on, they become more engaged in language-learning activities**.
Hence, I made <a target="_blank" href="/docs/spanish-pronunciation-project.pdf">my course project</a> about 
**helping native English speakers without previous pronounce Spanish understandably**. 

Due to the rigor of the course,
only an early [Wizard of Oz prototype](https://en.wikipedia.org/wiki/Wizard_of_Oz_experiment) was completed, but there
were some interesting early findings. 

![Screen showing the translation of the word "flaco".](/img/spanish-pronunciation/spanish-pronunciation-mockups.jpg)


# Instructional Design Principles
I followed guidelines laid out by Mayer and Clark in [their seminal book on the subject](https://www.amazon.com/Learning-Science-Instruction-Guidelines-Multimedia/dp/0470874309).

- The *Multimedia Principle*: include both images and text in learning activities.
- The *Segmenting and Pretraining Principle*: focus on instructing the basic building blocks (e.g. phonemes before words).

# Process

I put together a deck of virtual flash cards with Spanish words, their English translations and a helpful image,
under the assumption that learners would be more engaged if they understood the words they were uttering.

I provided two kinds of pronunciation advice in English: at the phoneme level 
(e.g. *say the letter "a" as you would in "father"*), and at the word level (e.g. *say a-sool for the color "blue"*).
In this very low-fi prototype, the system's pronunciation was voiced by me.

The first user tests showed that:
- People often skip reading the pronunciation advice, and want to interact with the exercise right away.
- People struggle with a few key sounds that do not exist in English [(ɾ and ʎ)](https://en.wikipedia.org/wiki/Help:IPA_for_Spanish).
- Pronunciation advice at the word level can interfere with people's spelling in Spanish later on.

Following these results and feedback from Spanish professors, I decided to make the first activities
teach individual phonemes before moving on to words (validating the *Segmenting and Pretraining* principle
that I had ignored for the sake of engagement). I also removed word-level pronunciation advice.

Second iteration tests showed that students were visibly less engaged by having to learn phonemes rather than words. We need more data 
from a more sophisticated system with real users to conclude if this decrease 
in engagement leads to improved proficiency in the long term
(that is, if the phoneme-learning task has a [desirable difficulty](https://en.wikipedia.org/wiki/Desirable_difficulty)).
I am looking for opportunities to continue the research.
