markdown
# Instructional Design Skill: Scenario & Case-Based Learning Design

## Overview
Scenario and case-based learning are among the most effective 
strategies for developing judgment, decision-making, and applied 
skills in workplace learning. Rather than presenting information 
and asking learners to recall it, these approaches immerse learners 
in realistic situations that require them to think, choose, and 
experience consequences — much like the actual job. This skill 
helps Claude support instructional designers in planning, writing, 
and structuring scenario and case-based learning experiences.

---

## Core Principle: Context Drives Transfer
Adults learn best when they can connect new knowledge to familiar, 
meaningful situations. Scenarios work because they:

- Activate prior knowledge and experience
- Create emotional engagement and investment in the outcome
- Require application rather than recall
- Provide safe-to-fail practice environments
- Make abstract concepts concrete and job-relevant

The goal is not to test whether learners remember what was covered. 
It's to develop the judgment to handle situations they'll actually 
face on the job.

---

## Scenario vs. Case Study: Key Differences

| | Scenario | Case Study |
|---|---|---|
| **Structure** | Learner makes decisions that drive the story | Learner analyzes a situation after the fact |
| **Interactivity** | High — learner choices affect outcomes | Lower — learner reflects and responds |
| **Best for** | Decision-making, skills practice, behavior change | Analysis, strategy, professional judgment |
| **Feedback** | Immediate, consequence-driven | Facilitated discussion or rubric-based |
| **Format** | Branching, linear with checkpoints | Written case + questions or discussion |

Both are valuable. The right choice depends on the learning 
objective and the level of interactivity the platform supports.

---

## Types of Scenarios

### Linear Scenario
A single narrative thread with decision points and feedback. 
The learner makes choices but the story doesn't branch — 
feedback explains consequences and correct reasoning.

Best for: introducing a concept, lower-stakes practice, 
limited development time.

### Branching Scenario
Learner choices lead to genuinely different outcomes and 
narrative paths. Poor choices lead to realistic negative 
consequences; good choices advance the story toward resolution.

Best for: complex judgment calls, situations with multiple 
valid approaches, high-stakes skill development.

### Role-Play Simulation
Learner interacts with an AI or scripted character in a 
realistic conversation — a difficult stakeholder, a coaching 
conversation, a customer complaint. Particularly powerful 
when combined with AI-generated feedback on tone, word choice, 
and approach.

Best for: communication skills, sales, coaching, 
conflict resolution, customer service.

### Case Study
A richly detailed real or composite situation presented for 
analysis. Learner reads, reflects, and responds — typically 
in writing or discussion. No branching required.

Best for: strategic thinking, professional judgment, 
leadership development, situations where there's no 
single right answer.

---

## The Anatomy of a Strong Scenario

### 1. A Believable Character
Learners need someone to care about — or someone to be. 
Establish:
- Who is this person? (role, experience level, context)
- What do they want or need to accomplish?
- What's at stake for them?

Avoid generic characters. "A manager named Alex" is less 
effective than "Jordan, a newly promoted team lead who's 
about to have her first difficult performance conversation."

### 2. A Realistic, Meaningful Situation
The scenario should reflect actual job complexity — 
ambiguous information, competing priorities, time pressure, 
imperfect options. Clean, obvious setups produce clean, 
obvious choices that don't develop real judgment.

Ask: *Does this situation actually happen on this job? 
markdown
Would getting it wrong have real consequences?*

### 3. A Meaningful Decision Point
The best decision points:
- Have no obviously correct answer on the surface
- Require the learner to apply knowledge, not just recall it
- Reflect genuine dilemmas people face on the job
- Have plausible wrong answers rooted in common mistakes

### 4. Consequence-Driven Feedback
Consequences are where learning happens. Strong consequence 
feedback:
- Shows what actually happens as a result of the choice
- Doesn't just say "correct" or "incorrect"
- Explains *why* the choice leads to that outcome
- For wrong answers: guides without lecturing
- For right answers: reinforces the reasoning, not just 
  the result

### 5. A Satisfying Resolution
The scenario should reach a meaningful conclusion — 
success, failure, or partial success with lessons learned. 
Learners should feel the weight of their choices.

---

## Writing Scenario Dialogue

Dialogue is often the weakest element of instructional scenarios. 
Common problems:

- Characters who speak in complete, grammatically perfect sentences
- No one ever interrupts, misunderstands, or pushes back
- Dialogue that exists to deliver information, not reveal character
- Everyone is either obviously right or obviously wrong

**Weak dialogue:**
> Stakeholder: "I need a course on data privacy for my team."
> ID: "Before I design anything, I should conduct a needs analysis 
> to determine the root cause of the performance gap."

**Stronger dialogue:**
> Stakeholder: "Look, I just need something done by the end of 
> the month. Legal is breathing down my neck."
> ID: "I hear you on the timeline. Can I ask — has the team 
> actually had data incidents, or is this more of a 'cover our 
> bases' situation?"

Real conversations are messy, pressured, and full of subtext. 
Write dialogue that sounds like people, not textbooks.

---

## Branching Scenario Structure

### The Decision Tree
Map your scenario before writing it. For each decision point, 
identify:
- The correct / best choice
- 1-2 plausible wrong choices (rooted in real mistakes)
- The consequence of each choice
- Whether wrong choices loop back, dead-end, or branch to 
  a recovery path

### Managing Complexity
Branching scenarios can become unmanageable quickly. 
Practical approaches:

- **Collapsed branching** — wrong choices loop back to 
  the decision point with feedback; only correct choices 
  advance the story
- **Convergent branching** — different paths merge back 
  to a common point after a few steps
- **Layered branching** — 2-3 key decision points with 
  rich consequences, rather than branching at every step

### The "Twine" Principle
Name your branches. Before writing, sketch the structure 
with simple labels:
- Node A → Choice 1 (correct) → Node B
- Node A → Choice 2 (hasty) → Consequence C → Loop to A
- Node A → Choice 3 (avoidant) → Consequence D → Dead end

Seeing the map prevents structural confusion during writing.

---

## Case Study Design

A well-designed case study includes:

1. **Context** — organization, industry, situation background
2. **Characters** — key people involved, their roles and stakes
3. **The problem or decision** — what needs to be resolved
4. **Complicating factors** — constraints, competing priorities, 
   incomplete information
5. **Discussion questions or tasks** — what learners must 
   analyze, decide, or produce
6. **Facilitator notes** (if instructor-led) — key insights, 
   common responses, what good analysis looks like

The best case studies don't have clean answers. They're 
designed to surface tension, reveal assumptions, and 
generate discussion — not confirm what learners already know.

---

## Scenario Design with AI

AI is a powerful collaborator for scenario development:

**Where AI helps most:**
- Generating scenario variants quickly (same concept, 
  different industries or roles)
- Writing first-draft dialogue for revision
markdown
- Suggesting plausible wrong answers and common mistakes
- Building out consequence feedback
- Playing the role of a difficult character in real-time 
  role-play practice

**Where human judgment is still essential:**
- Determining what situations are truly representative 
  of the job
- Evaluating whether choices reflect real dilemmas 
  or false ones
- Ensuring feedback teaches rather than just corrects
- Maintaining narrative coherence across complex branches
- Calibrating the emotional tone of difficult scenarios

**Prompting tip for scenario generation:**
When using AI to draft scenarios, provide:
- The specific job role and context
- The performance objective the scenario supports
- The common mistake or misconception you want to address
- The tone (formal, conversational, high-stakes, etc.)
- Any constraints (length, number of choices, platform)

The more specific the prompt, the more usable the output.

---

## Scenario Design: Patterns Worth Examining

- **The "gotcha" scenario** — deliberately obscure or 
  trick questions that frustrate rather than develop judgment
- **Telegraphed correct answers** — one choice is obviously 
  right, making the scenario a formality rather than practice
- **Feedback that lectures** — wrong answer feedback that 
  dumps information instead of showing consequences
- **Unrealistic stakes** — scenarios where nothing important 
  is at risk produce low engagement and shallow thinking
- **Too many branches** — structural complexity that 
  overwhelms the development process and confuses learners
- **Skipping the map** — writing branching scenarios 
  without a structural plan leads to narrative dead ends 
  and inconsistencies
- **Generic characters** — learners disengage from 
  characters they can't recognize or relate to

---

## References & Further Reading
- *Map It* — Cathy Moore (action mapping and scenario design)
- *Design for How People Learn* — Julie Dirksen
- *The Art of Explanation* — Lee LeFever
- Cathy Moore's blog and resources — blog.cathy-moore.com
- Will Thalheimer's research on scenario-based learning — willatworklearning.com
- Jane Bozarth on story and social learning — bozarthzone.com
- Twine (free branching scenario authoring tool) — twinery.org
