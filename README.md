# Targeted Therapeutic Synthesis Engine

A computational drug discovery pipeline that uses biomedical literature data from PubMed and structural seeds from PubChem to generate and mutate small molecules for optimized binding efficiency against therapeutic targets.

## Overview
The goal of this pipeline is to automate the discovery and optimization of drug candidates. The system sources verified molecular data and literature records, establishes structural "seeds," and applies targeted mutation algorithms to modify chemical structures. This process iterates on functional groups to systematically improve the calculated efficiency of the molecules against target receptors.

## Pipeline Architecture
* **Data Ingestion:** Retrieves literature baselines from PubMed and structural compound data from PubChem to establish initial molecular seeds.
* **Structural Mutation:** Automatically applies in-silico chemical mutations to the molecular structures to alter functional groups.
* **Efficiency Optimization:** Evaluates mutated variants through an algorithmic scoring loop, preserving structures that demonstrate increased predicted binding efficiency.
* **Matrix Output:** Compiles finalized molecular data into structured arrays for downstream screening analytics.

## Technical Stack
* **Language:** Python
* **Data & Matrix Handling:** NumPy, Pandas

## Performance & Project Outcome
In baseline testing, the pipeline demonstrated higher calculated binding efficiency and predictive target optimization compared to generative outputs from baseline LLMs like Gemini. However, further refinement is still required to match the structural stability, pharmacokinetic profiles, and targeted efficacy of established, real-world pharmaceuticals currently utilized in clinical settings.
