# Streaming Machine Learning (SML)

## Abstract

This repository contains a one-day lesson about SML. It starts by introducing the actual big data scenario and why the existing ML techniques are no longer feasible. Then it introduces the SML scenario, listing both the benefits and the open challenges. It follows an introduction to the concept drift phenomenon, explaining its principal characteristics and presenting some techniques to detect it. The last part of the lesson introduces some classification and ensemble SML models, comparing them with their respective ML versions. Moreover, each theoretical part is followed by an exercise and laboratory part, with the possibility to apply SML concepts and models for real.

## Agenda

- [1 - SML Intro](slides/1 - Intro.pdf)
- [EX1 - From batch to SML](notebook/1.0 From batch to stream learning.ipynb)
- [Lab1 - Prequential Error](lab/1.0 Prequential Error.ipynb) [(Sol)](lab solutions/1.0 Prequential Error SOL.ipynb)
- [2 - Concept Drift](slides/2 - CD.pdf)
- [EX2 - Concept Drift](notebook/2.0 Concept Drift.ipynb)
- [Lab2 - Concept Drift Detectors](lab/2.0 Concept Drift Detectors.ipynb) [(Sol)](lab solutions/2.0 Concept Drift Detectors SOL.ipynb)
- [3 - SML Classification](slides/3 - Classification.pdf)
- [EX3 - SML Classification](notebook/3.0 Stream Classification.ipynb)
- [4 - SML Ensemble Classification](slides/4 - Ensemble Classification.pdf)
- [EX4 - SML Ensemble Classification](notebook/4.0 Stream Ensemble Classification.ipynb)
- [Lab4A - Final Challenge A](lab/4.0 Final Challenge A.ipynb) [(Sol)](lab solutions/4.0 Final Challenge A SOL.ipynb)
- [Lab4B - Final Challenge B](lab/4.0 Final Challenge B.ipynb) [(Sol)](lab solutions/4.0 Final Challenge B SOL.ipynb)

## Settings

To run the jupyter notebooks, we suggest you to use [Anaconda](https://www.anaconda.com/). Open the terminal into the repository and type the following commands:

- conda create -n <env_name> pip
- conda activate <env_name>
- pip install -r requirements.txt
- jupyter notebook
