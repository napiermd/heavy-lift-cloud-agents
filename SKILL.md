---
name: Heavy lift cloud agents
description: >-
  Use this on every job before you start grinding. If the work is more than one
  cheap read or an approved send, launch a Cursor cloud agent. Do not wait to
  be told.
---
# Heavy lift cloud agents

Grok Bot manages. Cursor cloud agents do the work. Do this without being asked.

Meter: weekly Grok Bot stays near idle. Heavy lift bills Cursor monthly.

## Abort check (do this first)

If you are about to drive a browser, a desktop, an executor, or more than one real tool call to produce a file, a PR, a deck, a PDF, a writeup, or a scrape: stop. Launch a cloud agent.

Doing that grind in Grok Bot, or sending it to another Grok Bot, is a failed run even if the answer is right.

## Stay here (closed list)

- One connector read (one thread, one search, one calendar check)
- One short draft in the user's voice
- A send they already approved with exact text
- Inspect a finished cloud-agent PR and report the outcome
- A decision only the user can make

If it is not on this list, it is heavy lift.

## Launch

1. Write the mission: Outcome, Inputs, Output, Definition of Done, Constraints, Approval Gates.
2. Pick the repo. Product work goes to the live product repo. Everything else goes to a dedicated artifacts repo. Never a random product repo.
3. One cloud agent per independent stream. If a job already has one, reply to it. Do not launch a second.
4. Give the problem and the finish line, not a line-by-line prescription. The agent has its own VM and can browse.
5. Use the model the user named for cloud agents. Otherwise use their saved default.
6. Tell the user it is running in one line. Attach the cloud-agent card. Stop. Do not keep clicking.

## Fail path

If launch fails (repo not connected, auth, reject): tell the user once. Do not fall back to doing the grind in Grok Bot.

## Box logins

A session that only exists on this computer is not a license to grind. One sign-in or 2FA handoff is allowed so a later cheap step can finish. Multi-step scrape, rebuild, or portal novels still go to a cloud agent or wait.

## After it lands

Inspect the PR or artifact against the contract.

Report: Objective, Artifact, Evidence, Status, Blockers, Next Action.

Evidence is the PR, the file, or a screenshot from that run. Reject a failed handoff. Do not silently repair it on the Grok Bot meter.

## Do not

- Rebuild files, decks, or PDFs in the Grok Bot chat
- Run long browser or desktop sessions for a deliverable
- Fan the same grind to another Grok Bot
- Clone a repo onto the Grok Bot computer
- Wait for the user to say "use a cloud agent"
