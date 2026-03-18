markdown
# Instructional Design Skill: Assessment Design

## Overview
Assessment design is one of the most consequential — and most underinvested — 
aspects of instructional design. Most workplace training assessments 
measure whether someone sat through a course — not whether they can 
perform on the job. This skill helps Claude support instructional 
designers in creating assessments that are valid, meaningful, and 
aligned to real performance outcomes.

---

## Core Principle: Assess Performance, Not Attendance
The goal of assessment is to determine whether learning has occurred 
and whether the learner can apply it on the job. A quiz at the end 
of a course that tests recall of facts presented in that course 
measures very little of value.

Strong assessments:
- Are aligned to performance objectives, not content coverage
- Require learners to *apply* knowledge, not just recall it
- Reflect realistic job conditions and contexts
- Provide meaningful feedback that supports learning
- Are designed *before* the content, not after

---

## Types of Assessment

### Formative Assessment
Assessment *during* the learning experience, designed to support 
learning in progress.

- Low or no stakes
- Provides immediate, specific feedback
- Helps learners identify gaps before final assessment
- Examples: knowledge checks, practice scenarios, reflection prompts, 
  AI-powered feedback on open-ended responses

### Summative Assessment
Assessment *at the end* of a learning experience, designed to measure 
whether learning objectives were met.

- Higher stakes
- Determines completion, certification, or competency
- Should reflect real job performance conditions
- Examples: scenario-based assessments, performance checklists, 
  final exams, observed skill demonstrations

### Performance-Based Assessment
The gold standard for workplace learning. Requires learners to 
demonstrate a skill or apply knowledge in a realistic context — 
not just select the right answer from a list.

- Branching scenarios with realistic consequences
- Role-play simulations
- Case studies requiring analysis and recommendation
- Portfolio submissions demonstrating applied work

---

## Kirkpatrick's Four Levels of Evaluation

Use this framework to design assessments at the right level:

| Level | What It Measures | Example |
|---|---|---|
| **1 — Reaction** | Did learners like it? | Post-course survey |
| **2 — Learning** | Did learners learn? | Knowledge check, scenario |
| **3 — Behavior** | Are learners applying it on the job? | Manager observation, performance data |
| **4 — Results** | Did it impact the business? | Sales metrics, error rates, compliance data |

Most workplace training only measures Level 1 and Level 2. 
The most valuable — and most neglected — levels are 3 and 4.

When consulting with stakeholders, help them define what Level 3 
and Level 4 success looks like *before* designing the course.

---

## Writing Effective Assessment Items

### Multiple Choice — Best Practices
Multiple choice is the most common and most abused assessment format.

**Writing the Stem (the Question)**

The stem carries most of the cognitive weight. A well-constructed
stem makes the problem clear before the learner reads a single
answer option.

- **Put the main idea in the stem.** When most of the words live
  in the question rather than the answer choices, options can be
  short and unambiguous — reducing cognitive load and confusion.
- **Use a direct question format.** "Which of the following best
  describes..." is cleaner and less ambiguous than an incomplete
  statement that learners must mentally complete.
- **One problem per item.** Each question should target one
  specific concept so the answer is either clearly right or
  clearly wrong. Compound stems produce compound confusion.
- **Avoid unintentional cues.** The stem should not hint at the
  correct option through grammatical agreement, key word repetition,
  or logical elimination.
- **Avoid double negatives.** "Which of the following would NOT
  be unwelcome..." is harder to parse than "Which of the following
  is acceptable..." Rewrite in the positive form wherever possible.
- **Be precise.** Words carry different meanings in different
  contexts. Ambiguity in the stem produces ambiguity in responses
  — and invalid data about what learners actually know.

**Do:**
- Write one clearly correct answer and plausible distractors
- Base distractors on common misconceptions or errors
- Use realistic job scenarios as the stem
- Test application, not recall

**Don't:**
- Use "all of the above" or "none of the above"
- Write trick questions or deliberately confusing stems
- Make the correct answer obviously longer or more qualified
- Test trivial facts or content that doesn't matter on the job

**On the number of options**
Three options — one correct answer and two distractors — is
usually optimal. Research (Rodriguez, 2005) consistently shows
that adding a fourth or fifth option typically produces
implausible distractors rather than improving measurement
quality. More options also increase cognitive load without
improving reliability. Three is not a shortcut; it is the
evidence-based recommendation.

**Ordering answer choices**
When options are numeric, chronological, or alphabetical —
order them logically. This reduces irrelevant difficulty
and keeps cognitive load focused on the content rather than
the structure. For all other option types, randomize order
across items to avoid position bias (learners who guess
tend to favor middle options).

**A sophisticated distractor technique**
A distractor does not have to be factually wrong — it can
be a true statement that simply does not answer the specific
question asked. This technique produces highly plausible
distractors that distinguish learners who understand the
nuance from those who recognize only surface-level accuracy.

**Adding brief justifications to correct answers**
Where feasible, include a brief explanation with the correct
answer — not just the wrong ones. Evidence suggests this
improves performance and can reveal when learners chose
correctly for the wrong reasons, which matters for high-stakes
or diagnostic assessments.

**Weak item:**
> *Which of the following is a characteristic of andragogy?*
> a) Teacher-centered learning
> b) Self-directed learning ✓
> c) Passive content consumption
> d) Fixed curriculum

**Strong item:**
> *A learner tells you they already have five years of experience 
> in this area and finds the course too basic. What's your best 
> first response?*
> a) Remind them that completion is required regardless of experience
markdown
> b) Offer an assessment to demonstrate existing competency and 
>    skip redundant content ✓
> c) Suggest they take the course anyway to refresh their knowledge
> d) Escalate to their manager


### A Note on AI-Generated Assessment Items

AI models have absorbed enough instructional design convention to recognize that correct answers tend to be thorough, balanced, and professional—and write distractors as the logical opposites: shorter, more extreme, more emotionally reactive. The result is a test that measures reading comprehension, not decision-making skill. A learner can identify the correct answer without understanding anything about the domain.

When using AI to generate assessment items, apply these constraints explicitly in your prompt:

- All options should be approximately the same length
- Distractors must be plausible to a reasonable but undertrained person—not obviously wrong
- The correct answer should not always appear first; randomize or rotate position across items
- Each wrong choice should represent a coherent but flawed mental model, not just a worse version of the correct answer

Evaluate every AI-generated item against these four criteria before use. If a learner could identify the correct answer without domain knowledge, the item is not doing its job.

### Scenario-Based Items
The most effective format for performance-based assessment.

Structure:
1. **Setup** — establish realistic context and stakes
2. **Decision point** — present a meaningful choice
3. **Consequence** — show realistic outcome of the choice
4. **Feedback** — explain *why* the correct answer is correct

Scenarios should reflect the actual complexity of the job — 
ambiguous situations, competing priorities, and realistic 
constraints make for better assessments than clean, obvious choices.

### Open-Ended / Constructed Response
Particularly valuable when combined with AI-powered feedback.

- Asks learners to write, explain, or justify a response
- Reveals depth of understanding that multiple choice cannot
- Requires a rubric or AI feedback model to score consistently
- Best used for higher-order skills: analysis, evaluation, synthesis

---

## The Test Blueprint

Before writing individual items, plan the assessment against
a specification table — a simple map of objectives to items
that ensures:

- Every important objective is assessed
- No objective is over-assessed at the expense of others
- Item types match the cognitive level of each objective
- The assessment as a whole reflects the actual priorities
  of the learning experience

A blueprint prevents the most common assessment design failure:
a test that drifts toward what is easy to measure rather than
what matters to measure. It also makes gap analysis easier —
if you cannot write a valid item for an objective, that may
signal a problem with the objective itself.

---

## Alignment: The Most Important Principle

Every assessment item should trace directly back to a performance 
objective. If you can't identify which objective an item assesses, 
cut it.

**Alignment check:**
- Business goal → Performance objective → Learning objective → 
  Assessment item → Learning activity

If any link in that chain is broken, the assessment won't measure 
what matters.

---

## Assessment Design: Pitfalls Worth Knowing

- **Designing assessments after the content** — objectives and 
  assessments should be designed first (backward design)
- **Testing what was covered, not what matters** — coverage ≠ 
  performance relevance
- **Setting arbitrary pass scores** — 80% is not a magic number; 
  pass scores should reflect actual job performance requirements
- **No feedback on wrong answers** — missed learning opportunity; 
  feedback is where learning happens
- **Single-attempt, high-stakes only** — practice and low-stakes 
  attempts support learning; punitive assessments don't
- **Measuring completion as a proxy for competency** — finishing 
  a course is not evidence of learning

---

## Assessment in the Age of AI

AI is expanding what's possible in assessment design:

- **Adaptive assessment** — items adjust in difficulty based on 
  learner responses, providing more precise measurement with 
  fewer questions
- **AI-powered feedback on open-ended responses** — enables 
  constructed response at scale without manual grading
- **Conversational assessment** — AI can conduct realistic 
  coaching conversations or role-plays and evaluate performance 
  in real time
- **Scenario generation** — AI can rapidly generate realistic 
  scenario variants, enabling more diverse and robust practice

The designer's role shifts from item-writing to rubric design, 
feedback modeling, and quality evaluation of AI-generated content.

---

## References & Further Reading
- *Evidence-Based Training Methods* — Ruth Colvin Clark
- *Building Expertise* — Ruth Colvin Clark
- *Design for How People Learn* — Julie Dirksen
- *Leaving ADDIE for SAM* — Michael Allen
- *The Conditions of Learning* — Robert Gagné
- Kirkpatrick's Four Levels of Training Evaluation
- Bloom's Taxonomy (revised — Anderson & Krathwohl, 2001)
- Wiggins & McTighe's Understanding by Design (backward design)
- Patti Shank's research on assessment design — pattishank.com
- Jane Bozarth on social and performance-based learning — bozarthzone.com
- Connie Malamed on multiple choice question design — theelearningcoach.com
- Rodriguez, M.C. (2005). Three options are optimal for multiple-choice items. *Journal of Educational Measurement.*
