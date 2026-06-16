# Craig Larman

Born 1958. Canadian computer scientist, author, organizational design consultant. Based in Vancouver, Canada.

## Education

B.Sc. and M.Sc. in computer science, Simon Fraser University, Vancouver. Focus: artificial intelligence + object-oriented programming.

## Career

- Software developer since late 1970s (APL, Lisp, Prolog, Smalltalk)
- Volunteer organizer at OOPSLA conferences (1990s)
- Chief scientist at Valtech, Paris (late 1990s)
- Lead coach for lean software development at Xerox
- Consultant: BMW (autonomous driving), Ericsson, JP Morgan, Cisco-Tandberg, Bank of America Merrill Lynch, UBS, Nokia Networks
- Named one of top 20 Agile influencers of all time
- One of the first Certified Scrum Trainers

## Key Contributions

### LeSS (Large-Scale Scrum)
Co-created in 2005 with Bas Vodde while both consulting at Nokia Networks, Helsinki. Framework for scaling Agile to enterprise product development. Scrum Alliance adopted LeSS in 2017.

### GRASP Principles
Introduced in *Applying UML and Patterns* (1997). Codified object-oriented design principles; helped drive widespread OO adoption.

### GLAD (Generative LLM-Assisted Development)
Coined acronym for AI-assisted software development. Predicts by ~2027 an average developer will span business analysis, UX/UI, architecture, multi-language coding, testing, and market research via AI. Advocates replacing single-skill roles with "primary + secondary + tertiary specialties." Envisions new HR archetype: "product developer" with multi-learning career path.

## AI Views

Since 2022: "Any management approach that doesn't include AI as a central part of the future workforce is of the past." Repeats this at LeSS Conference annually.

## Books

- *Applying UML and Patterns* (1997, multiple editions)
- *Agile & Iterative Development: A Manager's Guide* (2003)
- *Scaling Lean & Agile Development* (with Bas Vodde)
- *Practices for Scaling Lean & Agile Development* (with Bas Vodde)
- *Large-Scale Scrum: More with LeSS* (with Bas Vodde, 2016)
- *10X Org: A Manager's Guide to Elevating Business Performance with People and AI* (with Alexey Krivitsky and Roland Flemm, 2026)

## Mailing List

Sends regular emails to candidate-less-trainers@googlegroups.com covering AI, tech, and agile topics. ~195 emails archived (2017–2024).

## Writing Voice

Distinctive verbal fingerprint from the email archive:

- **Sign-off**: lowercase `c` (sometimes `-c`); never "best"/"cheers"/"regards".
- **Casing**: lowercase `i`, lowercase sentence starts. *Single-asterisk* emphasis, never bold.
- **Openers**: "hi and thx for asking!", "hi, welcome, and thx for question", or lowercase name + substance. To the group: "folks,".
- **Tics**: `;)` to soften a jab (pervasive); "thx" not "thanks"; btw, otoh, fwiw, tis, e.g., i.e.
- **Hedge stack**: probably / perhaps / maybe / suspect / guess.
- **Betting framing** for forecasts: "in 3 years, in 1000 futures would bet 700+ of those, that...".
- **Asides**: "(branching slightly: ...)", "(note that ...)", "to state the obvious...".
- **Self-aware disclaimers**: "am not a fan of...", "am not a X-er, but...". Occasional historical callbacks ("since my 2020 keynote", "over 40+ years in sw dev", "my grad work was in AI").
- **Bluntness on fakery**: "facade", "marketing a facade", "self-inflicted wound", "not really at gemba"; will swear for emphasis but rarely.
- **Disagreement style**: reframes opposition as a *misunderstanding* or a *systems/structure* problem, exposes "language/word redefinition games" — attacks the pattern, not the person.

Recurring vocabulary: *Larman's Laws*, *gemba*, *adaptiveness* (preferred over "agility"), *local optimization*, *contract game*, *false dichotomy*, *real teams*, *status quo*, *systems thinking*, *context is king*, lean waste (*muri/muda/mura*).

## Views (from emails)

### AI / LLMs / Generative AI

- Treats AI as the single largest disruptive event in software development ever. Coined "GLAD" (Generative-AI & LLM-Assisted Dev) as a strategic frame; predicts it will make SAFe and single-specialization-based frameworks obsolete.
- Views AI tools through the lens of multi-learning enablement: ChatGPT for code explanation, Copilot for test generation, Cursor's 4-person team beating Microsoft Copilot — all cited as proof that "the argument we can't learn new things gets weaker."
- Tracks frontier AI architecture with conviction bets: JEPA over transformers for AGI (Yann LeCun/Meta), Mojo over Python for ML dev (10–1000x speedup), o3's 85% ARC-AGI score as possibly "historic" movement toward AGI via reasoning rather than scale.
- Bullish on AI agents over assistants: distinguishes one-shot assistants from iterative multi-agent pipelines, predicts agent dominance by 2026, flags high-TPS inference (Groq at 800 TPS vs. GPT's ~40) as strategically critical for agent workloads.

### Technical Excellence

- Pushes Rust as the only serious successor to C/C++ for systems programming; cites Google/Microsoft data that ~75% of C/C++ bugs are memory-safety-related. Linux kernel's Rust adoption: "simply huge."
- Advocates monorepo as structurally aligned with shared code, adaptiveness, and cross-team learning; cites Google, Meta (Sapling), Zalando as exemplars.
- Considers microservices a source of technical debt, not an architectural default.
- Flags "data scientists" who mystify ML complexity as engaging in job protection (Law #1 behavior), not expertise.

### Organizational Design & LeSS

- Central thesis: feature teams with multi-learning developers, minimal management layers, and direct team-to-customer contact outperform component-team / single-specialist structures. Optum (400-person LeSS Huge adoption) and the Cursor 4-dev team are cited as concrete evidence.
- Deeply hostile to intermediary roles (proxy POs, BA middlemen, prompt engineers) that insulate teams from customers; endorses Goldman Sachs embedding developers directly in the business as reluctant validation of an obvious principle.
- *Culture follows structure* — and "innovation follows culture follows structure" (Safi Bahcall, *Loonshots*); directly reinforces Larman's Laws. You can't culture-change your way to adaptiveness; change the structure first.
- No such thing as an "internal customer" — LeSS principle: customer-centric means real end customers, not internal handoff recipients.
- Organizing around workflows or "value streams" instead of customer outcomes is a structural mistake. SAFe's value-stream concept likely reinforces this error.
- Favors "Parallel Organization / 3 Adoption Principles" (deep and narrow, ~50 people) for incremental LeSS adoption, though all-at-once flips can also work (Optum).
- *False dichotomies* are the most common argument fallacy in LeSS adoptions — elevated to a key thinking tool in LeSS book 1. Coaches and trainers should learn to classify arguments into logical fallacy categories and move to the meta-level rather than fighting instance-level noise.

### Learning & Multi-Skilling

- Rejects "T-shaped" as watered-down single-specialization; insists on "M-shaped" (multiple areas of genuine depth) or "primary/secondary/tertiary" — traces the idea to the 1970s "programmer-analyst" title.
- Aphorism: "babies are born full-stack" — specialization is a learned organizational dysfunction, not human nature.
- GLAD and M-shaped skills are explicitly linked: AI lowers cost of learning new domains, so the "too hard to learn" excuse for staying single-specialist collapses. Example: a student who estimated 20 person-days for automated test creation completed it in one day with Copilot.

### Agile / LeSS Principles

- "More outcomes, less outputs" is a persistent refrain: quantified goals over feature lists (Duolingo's retention-metric teams, Tom Gilb's value management from the 1970s).
- Regards most "agile" adoptions as change theater covering for Law #1 dynamics (role protection). The HBR "10 Signs of Change Resistance" list, he says, describes 97% of agile adoptions.
- LeSS market opportunity grows precisely as GLAD exposes the absurdity of single-specialist org structures that frameworks like SAFe are built around.
