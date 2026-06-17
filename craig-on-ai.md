# Craig Larman — Predictions on AI

Drawn from his LeSS Candidate Trainers emails, 2018–2024.

## Main predictions

### Agents will dominate (2024-10-15)
Agent-based solutions become dominant, "another big step in ai evolution." Key trait: *iterative* goal completion + multi-agent collaboration (agent 1 builds, agent 2 refactors, agent 3 evaluates). Wider appreciation ~2026, then disruption.

### Groq / high TPS wins the agent era (2024-10-15)
Groq ~800 TPS vs gpt ~40. Edge meaningless for human assistants, decisive for agents who want max tokens/sec.

### Waymo + Tesla monopoly (2024-10-18)
Only Waymo (now Tesla) near real L4/L5. Others "trivial or BS." Predicts extraordinary global market opportunity without competition.

### AGI via reasoning, not scale (2024-12-22)
Since 2020 keynotes flagged ARC-AGI (Chollet) as gold benchmark. o3 hit ~85%. Path to AGI = more *reasoning* (System 1→2), not more data/compute. Slim chance 2025 = AGI emergence. "Revolutionary impact" most leaders haven't grasped.

### JEPA may replace transformers (2024-05-05)
LeCun's JEPA. Bet: in 100+ of 1000 futures, JEPA dominant in 3 yrs — higher odds than other candidates.

### Software 2.0 (2021-03-24)
AlphaFold/AlphaGo = solutions from learning machines, not imperative code. Sw 2.0 eats into sw 1.0 but won't supplant it (red-light-means-stop stays logic). Devs need mastery of both.

### Generative Design disruptive (2023-04-13)
Copilot generating tests + GPT4 code dialog. Winners = masters of these tools. Coined "GLAD" (Generative-ai & LLM Assisted Development).

### Opaque AI breaks deterministic regulation (2018-01-30)
ANNs opaque → deterministic fault-tracing regs can't stand. Predicted shift to automated test/verification of black boxes "like working with humans."

### ML research should not be a silo (2017-11-29, 2018-02-21)
BMW autonomous-driving R&D needs real PhD-level applied research — reading leading-edge ML papers, evaluating paths. But no single feature team has enough PhDs → "Research Community" experiment (PhDs stay on feature teams + form broad community to triage papers). Warns: many *fine-grained* communities ("RC for vision ML") kill lateral learning (2017-12-02). Core stance: most product "research" isn't science — it's reading/choosing/evaluating algorithms+components, work a regular feature team can do. "Shippable means shippable," not "more knowledge." Status-quo forces use "we produce knowledge" to justify ML silos.

### Machine teaching replaces machine learning effort (2018-02-22, 2018-02-23)
Prediction: as the ML *learning* side becomes "almost trivial with rapid maturation of ML tool chains," focus shifts to **machine teaching** — teaching *skills*, not "features." In robotics/autonomous cars the "feature" language breaks down ("change lane by yourself" is awkward); robotics' *skills* framing fits better and "will become increasingly relevant in domains creating autonomous intelligent agents." On tooling churn: "FWs on top of FWs on top of FWs on top of tensorflow." Insisted on staying hands-on (mob-programming C++ TDD on the BMW car) to coach the domain credibly.

### Capsule neural networks = next big thing (2018-04-19)
On Hinton's capsule NNs (CapsNets). Hinton (godfather of deep learning) sees so much potential he recommends *dropping older NN models and starting afresh*. Technical: capsule neurons pass *vectors* not scalars (observation probability + pose: X,Y,Z + orientation) → model semantics + multi-perspective relationships, not just scenes; pose network transformable to any origin (Galilean-transform analogy). Prediction: devs will increasingly bump into groups applying deep learning (cites fraud detection, fashion design met same day).

### LMs designing things; "programming = last job standing" (2021-07-04)
Learning machines taking over simpler design (UI etc.) → routine design gets automated. Prediction: "programming as the last job standing" — and programming itself moves up the abstraction stack toward *creating language models*. Cites Google using an LM to design its next-gen TPU chip — in production, "better than anything a human could design" (Nature s41586-021-03544-w) — after human designers scoffed. Generalizing trend (links Copilot + TPU designer): **synergistic systems** where LMs + humans co-design complex things, freeing devs for the hard parts and "slowly eliminating single-task specialists."

### ChatGPT disrupts learning + dev (2022-12-06, 2022-12-08)
ChatGPT public review = "wow!" Can converse, explain code/concepts ("explain move semantics in Rust"), and *refactor on request*. Even if results trivial now, that it understood the request + "where it might go" is "mind-blowing." Prediction: **disruptive tech for sw dev** — lowers cost of learning, cuts switching costs, raises adaptiveness. Kills the excuse "we can't learn new things, too hard." Worked example: ChatGPT refactoring Fowler's video-store `statement()`.

### AI phishing / deepfakes (2022-12-16)
Prediction: within 10 years AI phishers good enough to fool people easily — even AI-generated live video of a "grand-daughter" talking with grandma to ask for money.

### GLAD = biggest disruption in sw dev, ever (2023-04-15, 2023-05-01)
Stakes the acronym GLAD (Generative-AI & LLM-Assisted Dev) publicly — first tweet "in almost a decade." Strong bet: 1/2 his equity at 2:1 odds that in 700 of 1000 futures within 2 years GLAD disrupts narrow single-specialist dev. Evidence: Lisbon student budgeted 20 person-days for test creation; GLAD did it in 1, good output — order-of-magnitude, "will be common." Predicts: single-task roles become "nonsensical"; single-specialists generate mountains of lean waste (excess design/front-end/component code); estimation-based planning invalidated → shorter feedback loops; prescriptive single-specialization scaling frameworks (names **SAFe**) seen as mismatch → 2024+ window for simpler org design + LeSS. Calls GLAD "the largest & most disruptive event in sw dev, ever."

### Mojo for AI/ML (2023-07-12, 2024-05-05)
Prediction: in 2–3 years, 700+ of 1000 futures, Mojo is an influential language/stack, esp. for AI/ML. Credits Chris Lattner (LLVM/Clang/Swift) as top language designer of last 20 yrs. Mojo = compiled superset of Python (compiles existing Python); 10x min speedup, some 100–1000x. Key value: abstracts deployment across complex training platforms (e.g. "train on 10k cluster of H100 on DGX") that today takes months of hand-crafted setup. Reasoning: existing languages NOT designed for ML; major future dev focuses on ML → market for abstraction tech. Gives regular devs an easy path to ML → reduces need for "AI/ML specialists" who only know idiosyncratic stack setup. Caveat: hard part (getting/prepping good data) remains "at least until gpt-6, when it will take over that work."

### PromptBreeder: AI engineering AI; Google dominance bet (2023-10-05)
Claim: "prompt engineer" already automated by AIs that do prompt engineering — cites Google/DeepMind PromptBreeder (arXiv 2309.16797). Mechanism: industrial PromptBreeder spins up next-gen AIs orders-of-magnitude faster than humans, "a billion at a time," via double-loop learning (genetic-algorithm outer loop); best offspring = PromptBreeder2, rate-limited only by data-center power. Big bet: 10:1 odds, $200K, that in 900/1000 futures of 2035 Google is #1 or #2 in large/meta-scale AI markets (BERT 2018 seeded GPT; Google has gone "beyond & meta"). Waymo aside: real today (Phoenix), closest to L5, eyeing long-haul trucking ($2T+/yr market). Energy aside: Microsoft/Helion fusion online ~2030 to power AI; massive cheap clean fusion coming faster than expected.

### Facial recognition = mass surveillance (2020-01-20)
On Clearview AI: "ugg yes" — part of "a larger story of mass surveillance, tech, china, and the uighurs." Frames facial-recognition AI as enabler of state mass surveillance.

### Smaller AI tooling notes
- **Python-for-ML env** (2020-09-15): for ML work use macOS/Linux (real Unix/bash), not Windows; avoid Windows-based tutorials.
- **Tesla FSD leap** (2020-09-23): criticized Consumer Reports for testing outdated FSD generation when a full next-gen rewrite with "dramatically more capabilities" was shipping Q4 2020.
- **Google live transcription** (2023-06-21): Pixel's live transcription "perhaps the best & most robust available."
- **GPT in agile roles** (2023-01-10): shared ChatGPT taking a Scrum Master job interview — early signal he saw it role-playing coaching roles.

## Recurring throughlines

- **Acceleration** — AI moving faster than humans can grasp; any tool eval stale in months ("fool's errand").
- **Anti-single-specialist** — "AI team" / "data science team" / "ML research silo" = local optimization (Larman's Law #1). Tooling democratizes ML → multi-learning generalist teams win. Cursor's 4 multi-learning devs beating MS Copilot's siloed orgs = his proof. Quip: "babies are born full-stack."
- **Tooling-softens-constraints** — recurring since 2018: ML keeps getting easier (TensorFlow → FWs-on-FWs → Copilot → ChatGPT → Mojo), so rare-specialist constraints dissolve and cross-functional feature teams become viable. The hard, un-automated remainder = learning, creativity, adaptiveness, and (for ML) getting/prepping good data.
- **Programming as last job standing** — automation climbs the abstraction stack; dev work moves up toward *creating language models*; single-task roles become "nonsensical."
- **Betting in 1000 futures** — signature framing for predictions: "in N of 1000 futures…" often with explicit odds + stakes (JEPA 100+/1000; GLAD 700/1000 + half his equity at 2:1; Mojo 700+/1000; Google AI dominance 900/1000 + $200K at 10:1).
- **Whole-system upheaval** — AI arc = org-design + management + employment + education + energy (fusion-for-AI) disruption most leaders miss.

Note: Craig's grad work was in AI; built "Voyager" agent framework startup, 1995.
