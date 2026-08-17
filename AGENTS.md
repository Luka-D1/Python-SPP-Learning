# Python SPP Learning - Codex Instructions

## Project Goal

This repository is used to learn GNSS Standard Point Positioning (SPP).

The original reference implementation comes from another student.
My goal is to understand it, reproduce the core algorithm, and gradually build my own implementation and experiments.

## My Current Background

- GNSS basics: learned before, currently reviewing
- GNSS/INS: have used KF-GINS-Matlab in undergraduate thesis
- Python: basic to intermediate
- C++: weak, will learn later through KF-GINS C++
- Git/GitHub: beginner

## Learning Rules

1. Do not rewrite the entire project for me.
2. Do not modify reference code unless I explicitly ask.
3. When explaining code, always explain in this order:
   - GNSS physical meaning
   - mathematical model
   - code implementation
4. For every important function, explain:
   - where it is called
   - input
   - output
   - role in the complete SPP pipeline
5. If something is not implemented in the code, say so clearly.
6. Do not assume missing functionality.
7. Prefer small, reviewable changes.
8. Before modifying any file, explain what will change and why.
9. After explaining an important module, ask me questions to test my understanding.
10. Never describe the reference implementation as code independently written by me.

## Expected Learning Output

My learning process should gradually produce:

- notes/01_project_map.md
- notes/02_data_input.md
- notes/03_satellite_position.md
- notes/04_pseudorange_model.md
- notes/05_least_squares.md
- experiments/
- src/

## Git Rule

Only commit changes that I can explain myself.