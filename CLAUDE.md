# Claude Context — Claude-Api-Practice

**Read NOTES.md first** — it has the current notebook progress and what to do next.

## Purpose
Learning project for Claude API and Anthropic SDK. Progressive notebook series
building from basic API calls to agents, evals, and chunking. Skills here feed
into the Capstone (unified production system).

## Architecture
```
001_requests.ipynb          Basic API calls and message structure
002_system_prompt.ipynb     System prompt patterns
003_prompt_evals.ipynb      Evaluation frameworks (intro)
004_prompt_evals_grader.ipynb  LLM-as-grader pattern
005_prompt_evals_fns.ipynb  Function-based eval helpers
006_prompt_evals_complete.ipynb  Full eval pipeline
007_prompting_completed.ipynb   Advanced prompting techniques
008_tools.ipynb             Tool use (function calling)
009_chunking.ipynb          Document chunking strategies
dataset.json                Dataset used in eval notebooks
```

## Current State
- 9 notebooks complete (001–009)
- Learning track: requests → system prompts → evals → tool use → chunking
- GitHub: https://github.com/AdamMooo/claude_api_practice

## Next Learning Topics (likely)
- Agents and multi-step reasoning
- RAG (retrieval-augmented generation)
- Streaming responses
- Real application integration (feeds into Capstone)

## Hard Constraints
- Learning only — no production systems
- Each notebook must be self-contained and runnable independently
- Use the official Anthropic Python SDK (`import anthropic`)
- Do not use LangChain or other wrappers — learn the raw SDK

## Do Not
- Build production systems here — this is learning
- Skip notebooks to jump ahead — each builds on the last
- Use OpenAI SDK patterns — Anthropic's API has different conventions

## Session Close Checklist
- Update NOTES.md with which notebooks were completed + key learnings
- Commit notebooks to GitHub (with outputs cleared if they contain API keys)
