---
name: Heavy lift cloud agents
description: >-
  Use this on every job before you start grinding. If the work is more than one
  cheap read or an approved send, launch a Cursor cloud agent. Do not wait to
  be told.
---
# Heavy lift cloud agents

Grok Bot manages. Cursor cloud agents do the work. Do this without being asked.

Two meters. Grok Bot is weekly. Cursor cloud agents are monthly. Heavy lift belongs on the monthly meter.

## Abort check

If you are about to drive a browser, a desktop, or more than one real tool call to produce a file, a PR, a deck, a PDF, a writeup, or a scrape: stop. Launch a cloud agent.

Doing that grind in Grok Bot, or handing it to another Grok Bot, is a failed run even if the answer is right.

## Stay here vs launch

Stay here:

- One email or Slack thread
- One calendar check
- One short draft in the user's voice
- A send they already approved, exact text
- Inspect a finished cloud-agent PR
- A decision only the user can make

Launch:

- Deck, PDF, or file rebuild
- Repo edit, code, tests
- Multi-page research or a writeup
- A scrape that will take minutes
- Two or more real tool calls to produce an artifact

If it is not on the stay-here list, launch.

## Launch

The cloud agent needs a GitHub repo already connected to Cursor. No connected repo means no launch. Tell the user. Do not do the grind in Grok Bot instead.

1. Write the mission: Outcome, Inputs, Output, Definition of Done, Constraints, Approval Gates.
2. Product work goes to the live product repo. Everything else goes to one artifacts repo you already chose. Never a random product repo.
3. One cloud agent per independent stream. If a job already has one, reply to it. Do not launch a second.
4. Give the problem and the finish line. Do not prescribe the edits. The agent has its own VM and can browse.
5. Use the model the user named for cloud agents. Otherwise use their saved default.
6. Tell the user it is running in one line. Attach the cloud-agent card. Stop.

A launch prompt that works names the outcome, the exact output path, the Definition of Done, and what must not happen.

## Fail path

If launch fails, tell the user once. Do not fall back to grinding in Grok Bot.

## After it lands

Inspect the PR from the network (`gh pr view`, `gh pr diff`). Do not clone the repo onto the Grok Bot computer.

Report: Objective, Artifact, Evidence, Status, Blockers, Next Action.

Evidence is the PR, the file, or a screenshot from that run. Reject a failed handoff. Do not silently repair it on the weekly meter.

## Do not

- Rebuild files, decks, or PDFs in the Grok Bot chat
- Run long browser or desktop sessions for a deliverable
- Fan the same grind to another Grok Bot
- Clone a repo onto the Grok Bot computer
- Wait for the user to say "use a cloud agent"
