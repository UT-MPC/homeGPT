# Using ChatGPT for smart home control

This repo contains experiment and demo code that leverages ChatGPT for handling ambiguous user commands to smart assistants. It recieves vague instructions like "get ready for a party" and produces a set of changes to smart home device states in response.

## Requirements
- Install the ChatGPT wrapper for CLI: https://github.com/mmabrouk/chatgpt-wrapper
    - Use the Playwright installation instructions

## Files
``./demo/`` contains the Python notebook for the demo application

``./experiments.ipynb`` contains the experiments from the paper

``./results/study.ipynb`` contains experiment data post-processing code

``./results/markdown/`` contains the ChatGPT responses from the evaluations in human-readable Markdown format