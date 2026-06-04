# Hey there, I'm Hasan

I got my first real look at AI from the receiving end of it. I worked a call-center job at TELUS, in customer service, watching AI get pushed onto customers who didn't want it — automated answers, redirects, menus that led nowhere. The technology was genuinely capable. It was just aimed at the wrong target: cut headcount, deflect calls, treat support as a cost instead of a job worth doing well.

That experience shaped how I think about this stuff. The promise everyone sells is "replace the human." What I saw was that doing so makes the product worse and the customer angrier — you lose the judgment and context that made the work valuable in the first place. The version of AI I believe in is the opposite: a force-multiplier that makes one person able to do more and do it better, not a cheaper way to remove them.

So that's what I build. Local voice and wake-word models, ONNX deployment, tooling around AI agents; concrete things that ship and earn their keep, rather than another demo riding on the promise of replacing people.

- `wakeword-forge`: local wake-word training -> ONNX export
- `okay-hermes-repcnn-onnx`: compact "Okay Hermes" wake-word model
- `okay-hermes-voice`: always-on local voice daemon for Hermes Agent
- `tier-1-2-3-skill-system`: when to use instructions, scripts, or ML
- `recursive-agent-improvement`: repeated agent failure -> specialist tool
- `hermes-linux-ricing`: desktop changes with audit/apply/rollback
