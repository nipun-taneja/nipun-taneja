
# Nipun Taneja

ML / AI Engineer. Around 8 years building data and machine learning systems in fintech and consumer tech. Currently finishing an MS in Artificial Intelligence, with most of my work now going into evaluation and reliability for LLM and agent systems.

Most of what I build starts from a simple question: does this still hold up on the fiftieth run, not the first one.

## Currently

- MS in Artificial Intelligence, San Francisco State University. Graduating December 2026.
- Building a production-reliability evaluation harness for agentic fraud triage, measuring pass-k consistency and failure modes rather than single-run accuracy.
- Open to mid-level MLE / AI Engineer roles in the US. Open to sponsorship.

## What I work on

| Area | Detail |
|---|---|
| Evaluation engineering | Pass-k consistency, calibration, failure-mode taxonomies, regression harnesses for non-deterministic systems |
| Agents and orchestration | LangGraph multi-agent workflows, escalation policies, tool-use routing |
| Retrieval | Embeddings, RAG pipelines, vector search (Qdrant) |
| Computer vision | Object detection, loss-function design, YOLO-family models |
| Production ML | Feature pipelines, gradient boosting, experiment design at 50M+ user scale |

## Projects

**[Fraud Triage Evaluation Harness](#)** 
An XGBoost risk scorer paired with a LangGraph escalation agent on the IEEE-CIS dataset, evaluated the way a production system actually needs to be: repeated runs, pass-k consistency, and a breakdown of where and why the agent fails.
Python, XGBoost, LangGraph

**[AEIoU: Robust Detection of Amorphous Objects](#)** 
Master's thesis research on IoU-based loss functions for objects with soft boundaries. The result is a reproducible improvement for colorectal polyp detection (lambda = 0.1, +0.013 mAP@50-95, roughly 89% win rate across repeated runs on Kvasir-SEG), along with an honest account of which gains survived a code-path confound and which did not.
PyTorch, Ultralytics YOLO, Kvasir-SEG, CVC-ClinicDB, ISIC


**[ATS Job Discovery Pipeline](#)** 
Pulls live postings directly from Greenhouse, Lever and Ashby endpoints, then scores job-description fit using the Claude API.
Python, Anthropic API, ETL

## Stack

Python, PyTorch, scikit-learn, XGBoost, LangGraph, SQL, Docker, AWS, Qdrant

## Before grad school

| Company | Role | Highlight |
|---|---|---|
| Airtel | Senior Lead Data Analyst | Analytics and growth tooling across Wynk Music, Xstream OTT and Gaming. 3x revenue growth on Xstream; built the trigger behind roughly 10M customer acquisitions |
| SIMPL | Data Science | Risk and behavioral modeling for consumer credit |
| Goldman Sachs | Data Science / ML | ML systems in financial services |
| Barclays | Data Science / ML | Modeling and analytics for banking products |


## Contact

LinkedIn: [https://www.linkedin.com/in/nipun-taneja/](#) 

Email: nipuntaneja93@gmail.com 

Interviewing now. If you work on eval infrastructure, agent reliability, or applied ML in medical imaging, I'd be glad to talk.