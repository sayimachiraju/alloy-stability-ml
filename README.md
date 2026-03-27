# Alloy Stability Prediction using Materials Project

## Overview
This project investigates whether atomic properties can predict the stability of binary metal alloys.

## Dataset
- Source: Materials Project API
- 1867 binary metal-metal systems
- Stability measured via energy above hull

## Features
- Atomic radius difference
- Electronegativity difference
- Atomic number difference

## Key Finding
Electronegativity difference is a stronger predictor of alloy stability than atomic size mismatch, suggesting that chemical bonding effects dominate over classical Hume-Rothery size rules for this dataset.

## Methods
- Data extraction via mp-api
- Feature engineering using pymatgen
- Random Forest classification model

## Future Work
- Incorporate valence electron concentration
- Separate solid solutions vs intermetallic compounds