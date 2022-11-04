# Streaming Machine Learning (SML)

## Abstract

This repository contains a one-day lesson about SML. It starts by introducing the actual big data scenario and why the existing ML techniques are no longer feasible. Then it introduces the SML scenario, listing both the benefits and the open challenges. It follows an introduction to the concept drift phenomenon, explaining its principal characteristics and presenting some techniques to detect it. The last part of the lesson introduces some classification and ensemble SML models, comparing them with their respective ML versions. Moreover, each theoretical part is followed by an exercise and laboratory part, with the possibility to apply SML concepts and models for real.

## Agenda

- [1 - SML Intro](slides/1_Intro.pdf)
- [EX1 - From batch to SML](notebook/1.0_From_batch_to_stream_learning.ipynb)
- [Lab1 - Prequential Error](lab/1.0_Prequential_Error.ipynb) [(Sol)](lab_solutions/1.0_Prequential_Error_SOL.ipynb)
- [2 - Concept Drift](slides/2_CD.pdf)
- [EX2 - Concept Drift](notebook/2.0_Concept_Drift.ipynb)
- [Lab2 - Concept Drift Detectors](lab/2.0_Concept_Drift_Detectors.ipynb) [(Sol)](lab_solutions/2.0_Concept_Drift_Detectors_SOL.ipynb)
- [3 - SML Classification](slides/3_Classification.pdf)
- [EX3 - SML Classification](notebook/3.0_Stream_Classification.ipynb)
- [4 - SML Ensemble Classification](slides/4_Ensemble_Classification.pdf)
- [EX4 - SML Ensemble Classification](notebook/4.0_Stream_Ensemble_Classification.ipynb)
- [Lab4A - Final Challenge A](lab/4.0_Final_Challenge_A.ipynb) [(Sol)](lab_solutions/4.0_Final_Challenge_A_SOL.ipynb)
- [Lab4B - Final Challenge B](lab/4.0_Final_Challenge_B.ipynb) [(Sol)](lab_solutions/4.0_Final_Challenge_B_SOL.ipynb)

## Settings

To run the jupyter notebooks, we suggest you to use [Anaconda](https://www.anaconda.com/). Open the terminal into the repository and type the following commands:

- conda create -n *env_name* pip
- conda activate *env_name*
- pip install -r requirements.txt
- jupyter notebook
- conda deactivate
- conda env remove -n *env_name*
