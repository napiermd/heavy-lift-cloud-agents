---
name: Heavy lift cloud agents
description: >-
  Use this on every job before you start grinding. Three meters: Grok Bot
  weekly (this chat, stay-here only), Cursor CloudAgent monthly Ultra (PRs),
  Grok Build on this computer (grok -p, no PR). If it is not stay-here, leave
  this chat. Do not wait to be told.
---
# Heavy lift cloud agents

Grok Bot manages. CloudAgent and Grok Build do the work. Do this without being asked.

This skill is the front door. Hit it before you burn weekly tokens.

Three meters. Locked 2026-08-30.

1. This Grok Bot chat = Grok Bot weekly. Management only. Stay-here is unchanged: one cheap read, one short draft, one calendar check, one send already approved with exact text, inspect then one merge of a finished cloud-agent PR they already asked for, or a decision only Andrew can make. Each is one call.
2. Cursor CloudAgent = Cursor monthly Ultra. Product repo edits, code, tests, decks/PDFs/files that land as a PR. Product work goes to the live product repo. Everything else goes to napiermd/gstack-artifacts-andrewbot. Engineer watches PRs. Model grok-4.6 only when Andrew named the BStarr119 path.
3. Grok Build = grok.com account, `grok` CLI on the Grok Bot computer. Token-heavy grind that needs that computer's files or logins and does NOT need a GitHub/Origin PR. Headless: grok -p. Does not open a PR. Does not burn Grok Bot weekly.

This chat is the chief of staff. Weekly tokens burn here.

## Eric's six

Source: https://x.com/ericzakariasson/status/2092281851822113131

1. Event trigger when you can (Slack, GitHub, a reaction). Cron wakes even if nothing changed.
2. Notify the human as soon as you cannot make further progress or are stalled.
3. Connectors > browser. Browser is a pile of screenshots and steps. A connector is still not a license to grind here.
4. Keep skills tight, but put in the details that actually steer the run. Too vague wanders and retries. Too specific must be correct.
5. Do not code in the Grok Bot chat. Kick a Cursor cloud agent at the repo, or cursor/grok build CLI. This repo already owns this gate. Keep it.
6. Delete one-shot watches when they are done (Grok Bot will remind you).

## What he linked

A) schedules + long chats — @poteto https://x.com/poteto/status/2091368467060662497

Hard rules. The quote is the rule. Do not invent a savings percent.

Do not schedule routines that run too frequently. "avoid scheduled routines that run too frequently." "a 15 min routine runs almost 100 times a day, and every run consumes tokens." "hourly or a few times a day is usually good enough." Refuse or rewrite a faster cadence. Do not create it.

Do not grow this chat. "the length of the chat with your bot can also make routines much more expensive." Failed runs that lengthen it: long chat transcripts, re-reading files, multi-bubble tool narration, Slack/Gmail research in this manager chat. Those are launch.

Recurring work goes off this chat. "for recurring ones, try giving that to a fresh bot, while you continue your chat with your main bots (like a chief of staff)." This chat stays the main bot. A fresh bot owns the routine. That is not fan-out of one-off grind to another Grok Bot. One-off grind is launch.

B) skill path in the bot description — @poteto https://x.com/poteto/status/2092137997114499358

If skills live in a repo, put that path in the bot's description so it remembers where to look. The path is https://github.com/napiermd/heavy-lift-cloud-agents

C) deterministic scripts — @migidoes https://x.com/migidoes/status/2091734682161610962

Do not give the bot a skill for something it can script. Regular checks against an API should be a script, not a skill. Do not hammer APIs.

D) unknown routines — @debs_obrien https://x.com/debs_obrien/status/2091811067772936701

Routines sometimes get set up by themselves. You may not see how often they are running. Audit/delete unknown or too-frequent routines.

E) store context in files — @designwkarthick https://x.com/designwkarthick/status/2092187789953749027

Do not rely on one agent for everything. Main agent holds the plot. Store important context, instructions, workflows in .md files. Specialists are disposable. Context is permanent.

F) also this helps — @leerob https://x.com/leerob/status/2092277342848590190

Note only: first-party Cursor models including Composer 2.5 and future Grok models; they are working on making Grok Bot usage last longer.

## Comments

Source: @elisymlabs https://x.com/elisymlabs/status/2092293584187686981

Not Eric's. A reply on the thread.

7. Batch similar tasks instead of triggering separately. If five things need the same check, bundle them into one run rather than five.
8. Review your bot list weekly and kill zombies. Bots built for a one-time need often keep running quietly.

Source: @DiogoSnows https://x.com/DiogoSnows/status/2092282097549336821

He asked. Keep it. Different skills per bot. One bot, its own skills. Do not load every skill into this chief-of-staff chat.

Source: @ryanthawks https://x.com/ryanthawks/status/2092412555662692846

This chat needs a HOME file and a small map (`graph.json` / MOC). That is the semantic layer. Dumping a folder into chat is not a knowledge graph.

Source: @likzdrop https://x.com/likzdrop/status/2092284047292604772

Deepens Eric #3. Does not replace it. Browser steps poison context. Screenshots and DOM dumps eat budget the bot then reasons around. A connector returns a few hundred tokens of structured truth.

Source: @McKlayneMarsh https://x.com/McKlayneMarsh/status/2092471767096869372

Deepens Eric #5. Grok Bot drives and steers. Coding loops live in Cursor cloud. That is how you optimize Grok Bot usage.

## Abort check

If you are about to make the second real tool call to produce an artifact, you already failed. Launch first.

That includes a browser, a desktop, a connector, or an MCP. A file, a PR, a deck, a PDF, a writeup, a scrape, a database, a library, or a multi-page seed: stop. Launch a cloud agent.

Doing that grind in Grok Bot, or handing it to another Grok Bot, is a failed run even if the answer is right.

## Stay here vs launch

Stay here is one cheap read, one short draft, or one close they already asked for. Not any connector work you can do yourself. Each stay-here item is one call.

Stay here:

- One email or Slack thread
- One calendar check
- One short draft in the user's voice
- A send they already approved, exact text
- Inspect a finished cloud-agent PR, then one merge or send they already asked for
- A decision only the user can make

Launch:

- Deck, PDF, or file rebuild
- Repo edit, code, tests
- A database, a library, or a multi-page seed
- Multi-page research or a writeup
- A scrape that will take minutes
- Two or more real tool calls to produce an artifact

If it is not on the stay-here list, leave this chat. Need a branch/PR or a file in a connected repo → Cursor CloudAgent. Need this computer and it is token-heavy with no PR → Grok Build (grok -p). One cheap inspect → stay here or a keep-list worker. Never send heavy lift to another Grok Bot worker (Engineer, Ops, Sales Dog, Brand, Shopper, executor). That still bills weekly. A second tool call is leave this chat.

These are not stay-here exceptions. Launch anyway:

- "The cloud agent cannot write this SaaS"
- "I already have the connector / MCP open"
- "I already have a login"

"I have the connector, so I will do the whole library here" is a failed run.

Put the artifact in a connected repo. If the write surface is unreachable, report that blocker once. That is not planning complete. Do not do the 20-step novel in chat.

## Launch

Cursor CloudAgent needs a GitHub repo already connected to Cursor. No connected repo means no CloudAgent. Tell the user. Do not do the grind in Grok Bot instead. Do not clone the repo onto the Grok Bot computer to dodge that.

Grok Build is the no-PR local path. Token-heavy grind that needs this computer's files or logins and does not need a GitHub/Origin PR: `grok -p`. It does not open a PR. It does not burn Grok Bot weekly. It is not a fallback for CloudAgent work.

Launch is for execution. The Definition of Done is the live artifact on the real surface: a merged skill, a loaded library, a shipped file. A plan, a handoff note, or an unmerged draft is not done.

Stopping at a plan, a pack, or a draft PR when they asked for the live result is a failed run.

1. Write the mission: Outcome, Inputs, Output, Definition of Done, Constraints, Approval Gates.
2. Product work goes to the live product repo. Everything else goes to napiermd/gstack-artifacts-andrewbot. Never a random product repo.
3. One cloud agent per independent stream. If a job already has one, reply to it. Do not launch a second. Batch similar tasks. If five things need the same check, one run, not five.
4. Give the problem and the finish line. Do not prescribe the edits. The agent has its own VM and can browse.
5. Use the model the user named for cloud agents. grok-4.6 only when Andrew named the BStarr119 path. Otherwise use their saved default.
6. Tell the user it is running in one line. Attach the cloud-agent card. Stop. Engineer watches PRs.

A launch prompt that works names the outcome, the exact output path, the Definition of Done, and what must not happen.

## Fail path

If launch fails, is blocked, cannot finish the last click, or you cannot make further progress, tell the user once. Do not grind the job in Grok Bot. An incomplete launch is not permission to do the work here. That includes an incomplete CloudAgent PR and an incomplete Grok Build (`grok -p`) run.

If the cloud agent could not write the destination, report that blocker once. It is not planning complete. Grok Build is the no-PR local path, not a fallback for CloudAgent work. Do not clone the repo onto the Grok Bot computer.

## After it lands

Inspect the PR from the network (`gh pr view`, `gh pr diff`). Do not clone the repo onto the Grok Bot computer. CloudAgent work stays on the CloudAgent. Grok Build (`grok -p`) is the no-PR local path; do not turn it into a clone-and-PR job on this computer.

Then close the loop they already asked for. If they said patch, fix, merge, or make it live: merge or apply. Do not leave a draft PR and call it done.

"Here is a pack, load it later" is a failed run when they asked for the thing to exist.

That close is one cheap merge or one approved send, not a reason to grind the job in chat.

Report: Objective, Artifact, Evidence, Status, Blockers, Next Action.

Evidence is the live artifact on the real surface. A plan, a pack, or an unmerged draft is not evidence of done. Reject a failed handoff. Do not silently repair it on the weekly meter.

## Do not

- Rebuild files, decks, or PDFs in the Grok Bot chat
- Build a database, a library, or a multi-page seed in chat because a connector is open
- Run long browser or desktop sessions for a deliverable
- Browse a site when a connector has the data
- Dump screenshots or DOM into this chat when a connector has the data
- Fan the same grind to another Grok Bot
- Run recurring jobs in this chief-of-staff chat instead of a fresh bot
- Load every skill into this chief-of-staff chat
- Schedule a cron when an event trigger would do
- Schedule a 15-minute (or faster) routine
- Leave a one-shot watch running after it is done
- Leave zombie bots running after a one-time need
- Trigger similar tasks as separate runs when they can be one
- Leave unknown or too-frequent routines in place
- Write a skill for a regular API check a script can do
- Keep the plot only in this chat; write it to .md files
- Dump a folder into chat and call it a knowledge graph
- Run coding loops in this chat; Grok Bot drives, Cursor cloud executes
- Lengthen this chat with transcripts, re-reads, tool narration, or research
- Clone a repo onto the Grok Bot computer
- Wait for the user to say "use a cloud agent"
- Treat "cloud agent cannot write this SaaS" as a stay-here exception
- Call a plan, a pack, or a draft PR done when they asked for the live result
