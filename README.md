
## Multi-Persona AI Writing Assistant

A research prototype exploring how multiple AI personas can collaborate to provide structured writing feedback for learners.


## Open in Google Colab  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ijaycyndy/Multi-Persona-AI-Writing-Assistant/blob/main/multi_persona_writing_assistant.ipynb)

Student Essay
      ↓
Multiple AI Personas (Critic, Explainer, Planner, Supporter)
      ↓
Orchestration Logic
      ↓
Consolidated Feedback Output

## How to Run This Notebook

1. Click **Open in Google Colab** above.
2. Go to **Runtime → Run all**.
3. Add your own OpenAI API key when prompted (the notebook will not expose your key).
4. The notebook will:
   - generate feedback from multiple AI personas  
   - combine their responses  
   - save all results into a small dataset for analysis


## Overview

Most writing assistants use a single AI system. This project explores how feedback quality changes when multiple AI personas — each with a different role — work together.
The prototype simulates a small-scale, research-style experiment aligned with the AI for Education.

Personas Implemented

Critic – highlights weaknesses and unclear reasoning

Explainer – rewrites ideas in clearer language

Supporter – gives encouragement and identifies strengths

Planner – suggests improved structure and idea flow

Combined – integrates the feedback of all personas

## What the Notebook Demonstrates

✔ Running feedback sessions for each persona
✔ Simulating a multi-persona orchestration loop
✔ Evaluating feedback along simple dimensions (clarity, structure, argument strength)
✔ Creating a small dataset of persona outputs for analysis

Files in This Repository

multi_persona_ai_writing_assistant.ipynb – Full Colab notebook

feedback_results.csv – Saved feedback results for 2 sample essays

README.md – Project description

How to Use:

Open the notebook in Google Colab

Add your OpenAI API key

Run the cells to generate persona-level and combined feedback

Export results and analyse patterns

Example Output (Simplified)

Each essay receives 5 feedback outputs:

critic_feedback

explainer_feedback

supporter_feedback

planner_feedback

combined_feedback

This allows comparison of:

tone differences

structure differences

improvement suggestions

which persona is most useful for which type of learner

## Why This Project Matters

This project demonstrates:

basic multi-agent collaboration

persona-based prompting

structured educational feedback

early-stage learning analytics

your ability to design research-style experiments



