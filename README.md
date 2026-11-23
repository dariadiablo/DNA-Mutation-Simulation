# DNA Sequence Analysis & Mutation Simulation — Python Portfolio Sample

**Author:** Daria Diablo  
**Context:** Biomedical Science university programming coursework, adapted for an internship portfolio.

## What this project demonstrates

A small, self-contained Python example that:

1. Validates a DNA sequence and checks whether a target subsequence is present.
2. Simulates random mutation events across 1,000 reproduction cycles with a per-base, per-cycle mutation probability of 1/10,000.
3. Repeats the simulation 100 times to estimate how often the target subsequence becomes altered.

The notebook uses the same core mutation approach as my coursework solution, reorganised into a reusable function with clearer explanations and reproducible examples.

## How to run

1. Open `DNA_Mutation_Simulation_Portfolio.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
2. Run all cells from top to bottom using Python 3.
3. No external data files or third-party Python packages are needed; only Python's built-in `random` module is used.

## Data and methodology notes

The original coursework text files were not included with this upload. The notebook therefore uses **synthetic flanking sequences** and a target subsequence shown in my original notebook's saved output, strictly as illustrative inputs. They are not presented as laboratory or clinical data.

Mutation is represented by the character `M` rather than a substitution with another nucleotide; this is a simplified simulation designed to demonstrate programming logic, not a biological prediction. The 100-trial estimate varies with the random seed.

## Skills

Python · loops and conditional logic · functions · string processing · DNA sequence validation · random simulations · reproducibility · basic probability estimation

## Portfolio origin

Adapted from Python programming coursework completed during my BSc Biomedical Science studies at King's College London. This portfolio version removes the assessment instructions, draft attempts and grading material, while preserving the substantive working simulation approach. Please ensure you have permission to distribute any coursework-derived material before publishing or sending it externally.
