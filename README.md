# 📊 LLM Evaluation & Benchmarking Framework

## Overview
This project demonstrates a systematic framework for evaluating
LLM prompt strategies using measurable criteria rather than intuition.

The framework compares prompts across:
- Accuracy
- Hallucination rate
- Consistency across runs
- Cost (token efficiency)

## Task Evaluated
Explain cloud computing to a non-technical audience.

## Prompt Strategies Tested
- Baseline prompt
- Constrained prompt
- Structured prompt

## Evaluation Results

| Prompt Strategy | Accuracy | Hallucination | Consistency | Cost |
|----------------|----------|---------------|-------------|------|
| Baseline | Medium | Medium | Low | Low |
| Constrained | High | Low | Medium | Medium |
| Structured | High | Low | High | High |

## Why This Matters
Most people use LLMs without measuring reliability.
This project treats prompt engineering as a trust
and benchmarking problem rather than trial-and-error.
