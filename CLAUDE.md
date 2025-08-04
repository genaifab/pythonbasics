# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Python educational repository containing Jupyter notebooks for teaching absolute beginners Python programming. The workshop series covers fundamental programming concepts through interactive notebooks.

## Repository Structure

- `/notebooks/` - Contains sequential Jupyter notebooks teaching Python basics
  - Notebooks 01-09: Core lessons from intro to mini-project
  - `/notebooks/exercises/` - Practice exercises and solutions
    - 10a: Easy exercises (with solutions)
    - 10b: Moderate exercises (with solutions)
    - 10c: Hard exercises
  - `certificate.md`: Completion certificate template
- `main.py` - Simple entry point file
- Python 3.9+ required

## Common Commands

### Running Notebooks
```bash
# Start Jupyter notebook server
jupyter notebook

# Or use Jupyter Lab
jupyter lab
```

### Python Environment
```bash
# Run the main Python file
python main.py

# Install Jupyter if needed
pip install jupyter
```

## Working with Notebooks

When modifying or reviewing notebooks:
- Use `NotebookRead` to read .ipynb files
- Use `NotebookEdit` to modify notebook cells
- Each notebook builds on previous concepts - maintain pedagogical flow
- Notebooks are designed for complete beginners with no programming experience

## Key Educational Principles

The notebooks follow a structured learning path:
1. Introduction and environment setup
2. Core concepts (variables, data types, I/O)
3. Control flow (conditionals, loops)
4. Data structures (lists, dictionaries)
5. Functions and modular code
6. Practical application (quiz app project)
7. Practice exercises with varying difficulty

When modifying educational content, ensure examples remain accessible to absolute beginners and build incrementally on previous lessons.