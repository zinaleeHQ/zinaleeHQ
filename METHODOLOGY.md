# Methodology Notes

*Zina Lee, Product Manager*

---

## Where Product Management Ends

Four projects, four sets of boundaries — a constraint matrix, a set of process guardrails, a stakeholder registry, an access-control model — and exactly one person accountable for making sure all four stayed consistent with each other: me. That's the actual edge of what product management covers. A program manager's job is making sure that discipline doesn't live in one person's head, project by project, but holds across every team, every tool, and every person using AI in an organization, whether or not they're thinking about governance at all — including the ones nobody's watching.

Everything below this line is the same instinct, shown at the scale I currently operate at. Read it as evidence for the claim above, not as four unrelated notes on process.

---

## Working Across Multiple AI Tools

The first version of that instinct is small and almost boring: picking the right tool for the job instead of defaulting to whichever one is already open. Vista is the clearest example — v0.dev built the interactive frontend, Claude worked as the system-architecture collaborator on the KPI taxonomy and governance model, Gemini handled deployment support. Three tools, three distinct jobs, none of them interchangeable with the others for the task it was doing.

I'll be direct about something: confident claims about how Claude, GPT, and Gemini each "think differently" age fast in this field, and a paragraph asserting fixed model personalities reads as dated within months. So the actual principle isn't a taxonomy — it's that I choose deliberately and verify regardless of which tool produced the output. That's a small, personal version of the same discipline the opening section of this page is about. At one-person scale, "pick the right tool and check its work" is a habit. At organizational scale, it's a policy someone has to write down and enforce, because habits don't survive being handed to a hundred people who've never met each other face to face.

---

## Why Prompts, Not Agentic Workflows

This is the same boundary-setting instinct again, just applied to architecture instead of tool choice. I didn't build this portfolio around autonomous agents, for two practical reasons.

Agentic systems carry real overhead — orchestration, token cost, complexity — and for most of what these four projects needed, that's more infrastructure than the actual problem calls for. Good tool selection matches the complexity of the solution to the complexity of the problem, not to how impressive the solution sounds.

The second reason is the one that actually matters more: a structured prompt keeps a visible pause point built into the process, in a way an agent optimized to run end-to-end doesn't. Every prompt across all four projects stops before its final phase and waits for a human "yes." That pause is a boundary I set, deliberately, on every single project — which is exactly the kind of decision the opening section says doesn't yet exist at the organizational level. I can guarantee a pause point in a prompt I wrote myself. I can't yet guarantee one exists in every AI-assisted process across an entire org, and neither can most companies right now. That gap is the whole reason program-level governance is a real, unsolved problem and not a solved one wearing a fancier title.

---

## Scope and Application

Every case study here is set in healthcare IT, but none of the frameworks are healthcare-specific — WSJF, DMAIC, stakeholder mapping, and KPI governance all travel cleanly to other regulated, complex environments. Healthcare just happens to have enough public documentation to build something realistic without touching anyone's proprietary data.

Worth naming directly: a fair amount of what's analytical in these projects could be automated further than I did here. That's deliberate. The pause points, the override calls, the access-boundary decisions stay with the PM on purpose, in every project — because that restraint, repeated four times, is the actual evidence behind the opening section's claim. I can point to four instances of choosing not to automate the judgment layer. What I can't yet point to is a mechanism that makes that same restraint the default for people who've never thought about it, which is probably a fair description of most real organizations.

---

## Where This Actually Has to Go Next

The gap in everything above: it's all still one person's discipline, applied project by project. Real governance has to work at every altitude of an organization at once — policy the C-suite signs off on, guardrails that engineers actually build against, and behavior at the level of an admin quietly using a chatbot to track filing, with nobody in the room who has thought about what that means.

I'm not exempt from that last one, for what it's worth. I've used Gemini's Assistant on Google searches for work tasks outside of any sanctioned framework, the same as plenty of people reading this probably do. That's called "shadow AI", and naming my own use of it probably matters more than writing a policy that only describes other people's risk — because *the problem with shadow AI is that everyone doing it thinks of it as harmless*, including the people who'd write the policy against it.

What closing that gap actually requires, eventually, is an acceptable-use policy that names which tools are sanctioned and which aren't, a monitoring layer that catches sensitive data leaving through an unsanctioned tool before it becomes a breach report, and — the part that's hardest to enforce and easiest to skip — training that reaches the admin using Gemini's Assistant, not just the engineers everyone assumes are the actual risk.

That's the layer these four projects don't cover yet, and it's the next thing I want to build.

*[Back to README](./README.md)*
