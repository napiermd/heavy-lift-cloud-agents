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

If you are about to make the second real tool call to produce an artifact, you already failed. Launch first.

That includes a browser, a desktop, a connector, or an MCP. A file, a PR, a deck, a PDF, a writeup, a scrape, a database, a library, or a multi-page seed: stop. Launch a cloud agent.

Doing that grind in Grok Bot, or handing it to another Grok Bot, is a failed run even if the answer is right.

## Stay here vs launch

Stay here is one cheap read or one short draft. Not any connector work you can do yourself. Each stay-here item is one call.

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
- A database, a library, or a multi-page seed
- Multi-page research or a writeup
- A scrape that will take minutes
- Two or more real tool calls to produce an artifact

If it is not on the stay-here list, launch. A second tool call is launch.

These are not stay-here exceptions. Launch anyway:

- "The cloud agent cannot write this SaaS"
- "I already have the connector / MCP open"
- "I already have a login"

"I have the connector, so I will do the whole library here" is a failed run.

Put the artifact in a connected repo. If the write surface is unreachable, report that blocker once. Do not do the 20-step novel in chat.

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

If launch fails, is blocked, or cannot finish the last click, tell the user once. Do not grind the job in Grok Bot. An incomplete launch is not permission to do the work here.

## After it lands

Inspect the PR from the network (`gh pr view`, `gh pr diff`). Do not clone the repo onto the Grok Bot computer.

Report: Objective, Artifact, Evidence, Status, Blockers, Next Action.

Evidence is the PR, the file, or a screenshot from that run. Reject a failed handoff. Do not silently repair it on the weekly meter.

## Do not

- Rebuild files, decks, or PDFs in the Grok Bot chat
- Build a database, a library, or a multi-page seed in chat because a connector is open
- Run long browser or desktop sessions for a deliverable
- Fan the same grind to another Grok Bot
- Clone a repo onto the Grok Bot computer
- Wait for the user to say "use a cloud agent"
- Treat "cloud agent cannot write this SaaS" as a stay-here exception
