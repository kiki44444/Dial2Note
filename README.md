# SMM4H-HEARD 2026 - TASK 4: MEDSYNTH DIALOGUE-TO-NOTE GENERATION
## About the Shared Task

Physicians spend substantial time documenting clinical encounters, contributing to burnout and limiting direct patient care. Automated systems that can reliably map doctor–patient dialogues to structured notes are critical for scalable clinical documentation support.

MedSynth directly addresses this gap with a fully synthetic corpus of doctor–patient dialogues paired with SOAP-format clinical notes, spanning a broad range of diagnoses and clinical presentations. This shared task invites participants to build and evaluate models for Dialogue-to-Note (Dial2Note) generation, using MedSynth as a benchmark resource.

## Task Description

Given a synthetic doctor–patient dialogue, systems must generate the corresponding clinical note in SOAP format (Subjective, Objective, Assessment, Plan).

## Dataset
- Medsynth (https://huggingface.co/datasets/Ahmad0067/MedSynth)
  - Over 10,000 synthetic dialogue–note pairs
  - Coverage of more than 2,000 unique ICD-10 codes
  - Notes provided in standardized SOAP structure
  - Dialogues reflecting realistic primary-care style encounters
  - Generated via a controlled pipeline to ensure privacy (no real patient data)

## Reference
https://www.codabench.org/competitions/14194/
