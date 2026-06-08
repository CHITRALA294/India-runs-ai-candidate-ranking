# Redrob Intelligent Candidate Ranking

## Overview

This project was developed for the Redrob Intelligent Candidate Discovery & Ranking Challenge.

The goal is to identify and rank the most relevant candidates for a Senior AI Engineer role by combining multiple candidate signals instead of relying solely on keyword matching.

## Problem Statement

Traditional candidate matching systems often rank profiles based on keyword overlap, leading to false positives.

This solution focuses on understanding candidate relevance through:

* Experience alignment
* AI/ML skill relevance
* Job title relevance
* Behavioral hiring signals
* Recruiter engagement indicators

## Solution Approach

A hybrid scoring engine was developed to evaluate candidates using multiple dimensions:

### Experience Score

Candidates with 5–9 years of experience receive the highest score.

### Skill Relevance Score

Priority is given to candidates with skills related to:

* NLP
* LLM Fine-Tuning
* Milvus
* Pinecone
* Weaviate
* Qdrant
* FAISS

### Title Relevance Score

Candidates with titles such as:

* AI Engineer
* ML Engineer
* Recommendation Systems Engineer
* Applied ML Engineer
* AI Specialist

receive additional relevance weight.

### Behavioral Signals

The system incorporates:

* Open-to-work status
* Recruiter response rate
* GitHub activity score

## Results

The ranking model successfully reduced false positives such as:

* Marketing Manager
* HR Manager
* Sales Executive

and prioritized highly relevant AI and ML candidates.

## Technologies Used

* Python
* Pandas
* JSONL Processing
* Rule-Based Ranking Engine
* Google Colab

## Repository Structure

```text
submission.csv
redrob_candidate_ranking.ipynb
README.md
```

## Future Improvements

* Semantic candidate-job matching
* Embedding-based retrieval
* Learning-to-rank models
* Explainable AI ranking framework
* Candidate behavioral scoring enhancements
