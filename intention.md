# intention.md

## Purpose

This repo is a reset.

We are trying to build the smallest possible LiveKit-based voice agent that can
answer questions about Conor Cosnett's CV locally.

## Current goal

Make a low-latency local LiveKit agent that:

- runs simply
- is easy to understand
- answers CV questions well enough
- avoids unnecessary moving parts

## Strong preferences

- minimalism first
- low latency first
- local-first development
- keep LiveKit concerns separate from everything else
- avoid extra product surface area unless clearly needed

## Non-goals for now

- Vercel integration
- GitHub Actions complexity
- telephony
- broad platform architecture
- fancy UI
- over-engineered retrieval
- mixed experiments from older repos

## What "good" looks like

A new coding agent should optimize for:

1. the simplest agent that works
2. the fewest dependencies and abstractions
3. fast local iteration
4. clear code over clever code
5. low-latency answers about Conor's background and work

## Practical framing

If a change makes the system harder to understand, harder to run locally, or
slower, it is probably the wrong change.

Start simple. Keep it pure. Make it work locally first.
