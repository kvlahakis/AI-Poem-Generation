# Stylized Sequence Generation with Structured Constraints

This repository accompanies the project:

**"Stylized Sequence Generation with Structured Constraints: Utilizing HMMs and LSTMs to Recreate Shakespearean Poetry"**

We explore the use of probabilistic and neural sequence models for stylized language generation under hard structural constraints. Specifically, we examine the tradeoffs between Hidden Markov Models (HMMs) and Long Short-Term Memory (LSTM) networks in generating Shakespearean sonnets and haikus.

---

## Full Report

For detailed methodology, analysis, and poem samples, read the full report here:  
[Poem_Generation.pdf](Poem Generation.pdf)

---

## Project Overview

We implemented and evaluated:
- A **Hidden Markov Model (HMM)** with phoneme-based rhyme enforcement and syllable-aware decoding
- A **Character-level LSTM** trained on Shakespeare’s 154 sonnets, with sampling controlled via temperature

We show:
- HMMs excel at enforcing poetic constraints (rhyme, syllable count)
- LSTMs offer higher fluency and stylistic diversity
- A phonetic rhyme matcher using the CMU Pronouncing Dictionary improves rhyme quality significantly

---

## Credits
Kieran Vlahakis, Noor Ibrahim, Anirudh Gajula, Sujay Champati

Supervised by Prof. Yisong Yue

---

