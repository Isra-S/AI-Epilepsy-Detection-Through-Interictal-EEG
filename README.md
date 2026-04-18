# AI Epilepsy Detection Through Interictal EEG

This project investigates whether machine learning can detect epilepsy 
from seizure-free (interictal) EEG recordings, periods where the brain 
appears normal and no seizures are occurring. Traditional clinical EEG 
interpretation relies on a specialist visually identifying abnormal 
patterns, a method with known diagnostic limitations. This project 
explores a computational alternative.

The core idea is that even when an EEG looks normal to the human eye, 
subtle patterns in how different brain regions communicate with each 
other; known as functional connectivity; may still carry meaningful 
diagnostic information. By extracting and analysing these hidden 
patterns, a machine learning classifier is trained to distinguish 
epilepsy patients from healthy individuals.

## Pipeline Overview

- **Preprocessing:** Raw EEG signals are filtered and segmented into 
short epochs to capture dynamic brain behaviour
- **Feature Extraction:** Functional connectivity between EEG channel 
pairs is quantified across domains
- **Classification:** A classifier is trained and evaluated with 
performance assessed through accuracy, sensitivity, specificity, etc

## Dataset

Publicly available EEG dataset.

## Goals

To build a reliable, data-driven pipeline that classifies epilepsy from 
interictal EEG with high accuracy.

## Status

🚧 In progress — Final Year Project (2026)
