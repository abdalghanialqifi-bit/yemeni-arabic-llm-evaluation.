# Yemeni Arabic LLM Evaluation Benchmark

A structured benchmark for evaluating Large Language Models (LLMs) on Yemeni Arabic, with emphasis on dialect authenticity, contextual understanding, cultural relevance, semantic accuracy, and naturalness.

## Project purpose

This project provides a reproducible framework for testing whether an AI response is not only grammatically acceptable Arabic, but also appropriate for Yemeni users and the intended conversational context.

## Evaluation dimensions

- Dialect authenticity
- Semantic accuracy
- Contextual understanding
- Cultural relevance
- Naturalness
- Grammar and morphology
- Intent preservation

## Repository structure

```text
datasets/       Evaluation examples and test cases
evaluation/     Scoring rubric and evaluator utilities
prompts/        Reusable evaluation prompts
docs/           Methodology and annotation guidance
tests/          Automated tests for project utilities
```

## Status

Initial benchmark prototype. The dataset is intentionally small at this stage and is designed to be expanded through documented human annotation.

## Ethical/data note

Examples should be original, non-sensitive, and free of private personal information. Dialect judgments should be documented rather than presented as universal rules across all Yemeni regions.
