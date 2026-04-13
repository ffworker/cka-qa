# cka-qa

Theory and recall workspace for CKA preparation.

## Purpose

Use this repo for:
- quizzes
- repetition
- weak-topic tracking
- precise definitions
- mental models
- progress tracking

Do not use this repo for hands-on labs or noisy manifest experiments.

## Connected repo

This repo writes handoff data to:
- `cka-shared/handoff.json` via the git submodule

## Core commands in chat

- `Status`
- `Quiz <topic>`
- `Repeat`
- `Update <topic>`

## Source of learning truth

This repo is the source of truth for:
- weak topics
- improving topics
- stable topics
- unstable concepts
- practical recommendations

## Workflow in the larger system

1. theory work happens here
2. results are written into `cka-shared/handoff.json`
3. `cka-lab` reads those results and builds practical work from them
4. practical findings come back through `practicalFeedback`

If theory changes but the shared handoff is not updated, the lab will drift.

## AI agents

Any future AI agent working in this repo must read:
- `AI-WORKFLOW.md`
- `AGENTS.md`
- `cka-shared/handoff.json`
