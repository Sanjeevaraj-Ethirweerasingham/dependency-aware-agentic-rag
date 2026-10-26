# Dependency-Aware Selective Revision in Agentic RAG

## Overview
This MSc research project investigates how Agentic Retrieval-Augmented Generation (RAG) systems can recover when new evidence contradicts an earlier assumption.

The proposed approach aims to identify which parts of the reasoning process are affected by an error and revise those parts while preserving independent work that remains valid.

## Research Question
Can dependency-aware selective revision improve answer accuracy and reduce unnecessary retrieval and reasoning in Agentic RAG when new evidence invalidates an intermediate assumption?

## Planned Approach
- Track dependencies between evidence requirements.
- Detect contradictions in newly retrieved evidence.
- Revise affected requirements while preserving valid independent work.
- Compare the approach with standard Agentic RAG and full-restart recovery.

## Datasets
- [HotpotQA](https://hotpotqa.github.io/)
- [2WikiMultiHopQA](https://github.com/Alab-NII/2wikimultihop)

## Project Status
**Work in progress.** Implementation and experiments will be developed as the research progresses.
