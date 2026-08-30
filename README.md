# Heavy lift cloud agents

This is a Grok Bot skill. I use Grok Bot as the chief of staff. CloudAgent and Grok Build do the work.

Three meters. Grok Bot weekly is this chat, management only. Cursor CloudAgent is monthly Ultra — product/repo work that lands as a PR. Grok Build is grok.com account, grok CLI on the Grok Bot computer, headless grok -p, no PR, does not burn weekly.

Stay in Grok Bot for one cheap read, one short draft, one calendar check, one send I already approved, or a decision only I can make. Looking at a finished cloud-agent PR and doing the merge I already asked for counts too. Each of those is one call.

Launch if you need a deck, a PDF, a repo change, tests, a scrape, research, a writeup, a database, or a second tool call to produce something. Branch/PR or a file in a connected repo goes to Cursor CloudAgent. Token-heavy work that needs this computer and no PR goes to Grok Build (grok -p). If it isn't one of those small stay-here jobs, leave this chat. Don't wait for me to say it.

Eric's six (https://x.com/ericzakariasson/status/2092281851822113131):

1. Event trigger over cron
2. Notify when stalled
3. Connectors > browser
4. Tight skills that still steer
5. No coding in Grok Bot chat — cloud agent / grok build CLI
6. Delete one-shot watches

What he linked:

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

Comments — @elisymlabs https://x.com/elisymlabs/status/2092293584187686981

7. Batch similar tasks instead of triggering separately. If five things need the same check, bundle them into one run rather than five.
8. Review your bot list weekly and kill zombies. Bots built for a one-time need often keep running quietly.

Different skills per bot — @DiogoSnows https://x.com/DiogoSnows/status/2092282097549336821

He asked. Keep it. Different skills per bot. One bot, its own skills. Do not load every skill into this chief-of-staff chat.

HOME + small map, not a dumped folder — @ryanthawks https://x.com/ryanthawks/status/2092412555662692846

This chat needs a HOME file and a small map (`graph.json` / MOC). That is the semantic layer. Dumping a folder into chat is not a knowledge graph.

Browser steps poison context — @likzdrop https://x.com/likzdrop/status/2092284047292604772 (deepens Eric #3)

Deepens Eric #3. Does not replace it. Browser steps poison context. Screenshots and DOM dumps eat budget the bot then reasons around. A connector returns a few hundred tokens of structured truth.

Grok Bot drives. Coding loops live in Cursor cloud — @McKlayneMarsh https://x.com/McKlayneMarsh/status/2092471767096869372 (deepens Eric #5)

Deepens Eric #5. Grok Bot drives and steers. Coding loops live in Cursor cloud. That is how you optimize Grok Bot usage.

Live rules stay in [SKILL.md](SKILL.md). Give that file to Grok Bot. CloudAgent needs a GitHub repo already connected to Cursor. Grok Build is the no-PR local path: grok -p.
