# How to Use This Library

This guide walks you through exactly how 
to load skill files into Claude and 
get genuinely useful instructional 
design support — with real examples 
of what good output looks like.

---

## The Core Idea

Claude is a capable thinking partner 
for instructional designers — but only 
if it has the right context. Out of the box, 
Claude knows a lot about a lot of things. 
These skill files give it something more specific: 
the frameworks, vocabulary, standards, and 
judgment that working instructional designers use.

Loading a skill file is like briefing 
a talented collaborator before a project. 
The better the brief, the better the work.

---

## Step 1: Choose Your Skill File(s)

Start with the skill most relevant 
to your current task.

**Working on a new project brief?**
→ `foundations/needs_analysis_performance_consulting.md`

**Writing a branching scenario?**
→ `design_practice/scenario_based_learning.md`

**Reviewing a storyboard?**
→ `craft_and_quality/quality_assurance_testing_for_elearning.md`

**Not sure? Start with one file.**
You can always add more in the same conversation.

See `COMBINATIONS.md` for suggested 
multi-file pairings for common project types.

---

## ⚠️ One Important Note Before You Start
**For regular one-off chats:** Do not upload `.md` files 
as attachments — this will produce an error. 
Use the paste method (Option A) instead.

**For Claude Projects:** Uploading `.md` files works 
correctly and is the recommended approach (Option B). 
Project Knowledge is a different mechanism 
from chat attachments.

The methods below all work correctly. 
Pick the one that fits your setup.

---

## Step 2: Load the File into Claude

### Option A: Paste into Claude.ai (browser)
1. Open a new conversation at claude.ai
2. Open the skill file on GitHub
3. Click **Raw** to see the plain text
4. Select all → Copy
5. Before pasting, add a framing line:
   *"I'm going to share some background context 
   about instructional design. Please read it 
   and use it to inform your responses 
   for the rest of this conversation."*
6. Paste the skill file content after the framing line
7. Add your request and send

### Option B: Claude Projects (recommended for Claude Pro users)
This is the cleanest, most persistent setup. 
Claude Projects lets you upload skill files directly 
as Project Knowledge — no pasting required, 
and they're available in every conversation 
in that project.

> **Important distinction:** The warning elsewhere 
> in this guide about not uploading `.md` files 
> applies to *regular one-off chats only*. 
> Claude Projects handles `.md` file uploads 
> correctly — this is the right place to use them.

**Setup (one time):**
1. Go to claude.ai and click **Projects** 
   in the left sidebar
2. Create a new project — 
   *"ID Work"* or whatever fits your workflow
3. Download the skill files you want from GitHub 
   (or the whole repo as a ZIP — 
   click **Code → Download ZIP**)
4. Inside your project, click **Add content** 
   → **Upload files**
5. Upload the `.md` files you want — 
   Claude will index them as Project Knowledge
6. In **Project Instructions**, add this activating prompt:

   > *"You have access to instructional design 
   > skill files in your Project Knowledge. 
   > Reference them when relevant to my requests."*

7. That's it — every conversation in this project 
   has full access to your skill files

**Which files to add:** You don't need all of them. 
Start with the skills you reach for most. 
See `COMBINATIONS.md` for suggestions by project type.

**Want even more control?** For skills you use 
on every project, paste the file content directly 
into **Project Instructions** (the system prompt). 
This makes Claude reference those skills proactively 
rather than only when asked.

### Option C: API / Custom Tools
If you're using Claude via API or 
a tool like OpenClaw:
- Add skill file contents to the 
  system prompt for persistent context
- Or paste into the conversation 
  as needed per session

### Option D: Copy a Single Section
You don't need the whole file. 
If you just need Claude to understand 
Bloom's Taxonomy or the COM-B model, 
copy that section only.

---

## Step 3: Make Your Request

After loading the skill file, 
state your request clearly and specifically.

**Less useful:**
> *"Help me with my course."*

**More useful:**
> *"I'm designing a 30-minute e-learning 
> module on handling customer complaints 
> for frontline retail staff with 
> no prior training. The business goal 
> is reducing escalations by 15%. 
> Help me write three scenario-based 
> practice activities that require 
> genuine judgment, not just recall."*

The more context you give, 
the more useful Claude's output.

---

## Real Examples

### Example 1: Needs Analysis Support

**Skill loaded:**
`foundations/needs_analysis_performance_consulting.md`

**Prompt:**
> *"A VP of Sales has requested a course 
> on 'pipeline management skills' for 
> their entire sales team. I have a 
> discovery call tomorrow. Generate 
> 10 diagnostic questions I should ask 
> to determine whether training is 
> actually the right solution and, 
> if so, what kind."*

**What Claude will do:**
Generate a set of sharp, performance-focused 
diagnostic questions that probe the 
actual nature of the gap — whether it's 
a can't-do or won't-do problem, 
what's already been tried, what the 
environment supports, and what success 
would actually look like.

Without the skill file, Claude might 
generate generic discovery questions. 
With it, Claude knows to probe for 
root cause, environmental barriers, 
and whether training is even the 
right intervention.

---

### Example 2: Scenario Writing

**Skill loaded:**
`design_practice/scenario_based_learning.md`

**Prompt:**
> *"Write a branching scenario for new 
> people managers who need to practice 
> having a performance conversation 
> with an employee who is consistently 
> missing deadlines. The employee is 
> well-liked, has been at the company 
> for 8 years, and gets defensive 
> when given feedback. Include one 
> decision point with three options: 
> best choice, common mistake, 
> and avoidant response. 
> Write realistic consequences 
> for each."*

**What Claude will do:**
Write a scenario with a believable setup, 
realistic character detail, a meaningful 
decision point, and consequence feedback 
that teaches rather than just corrects — 
grounded in what makes scenarios 
instructionally effective.

---

### Example 3: QA Review

**Skills loaded:**
`craft_and_quality/quality_assurance_testing_for_elearning.md`
`craft_and_quality/accessibility_in_elearning.md`

**Prompt:**
> *"Here is a storyboard excerpt from 
> a course I'm about to hand off 
> to development. Review it against 
> instructional QA criteria and 
> flag the three most important 
> issues I should address before 
> development begins.*
>
> [paste storyboard content]*"

**What Claude will do:**
Apply both functional/instructional 
QA criteria and accessibility standards 
to identify the highest-priority issues — 
not a laundry list of every possible 
problem, but a prioritized assessment 
with specific, actionable recommendations.

---

### Example 4: Pushback Support

**Skills loaded:**
`collaboration_and_strategy/stakeholder_management_performance_consulting.md`
`foundations/needs_analysis_performance_consulting.md`

**Prompt:**
> *"My stakeholder has sent me a 47-slide 
> PowerPoint and asked me to 'turn it 
> into an e-learning course' by Friday. 
> The content is dense, the objectives 
> are unclear, and I don't think a 
> course is even the right solution. 
> Help me draft a response that 
> pushes back diplomatically, 
> asks the right questions, 
> and buys me time to do this properly."*

**What Claude will do:**
Draft a professional, diplomatically 
framed response that acknowledges 
the stakeholder's urgency, asks 
targeted diagnostic questions, 
and reframes the conversation 
toward outcomes rather than output — 
without being adversarial.

---

## Tips for Getting the Best Results

**Be specific about your audience.**
Claude's output improves dramatically 
when it knows who the learner is — 
their role, experience level, 
context, and what they need to DO.

**Share the business goal.**
*"Reduce onboarding time by 30%"* 
produces better design support 
than *"new employee onboarding."*

**Iterate in the same conversation.**
You don't need to reload skill files 
for follow-up requests. 
Keep working in the same session.

**Ask for critique, not just output.**
Some of the most valuable prompts 
are review requests:
> *"Review this learning objective 
> and tell me what's wrong with it."*
> *"What's missing from this scenario?"*
> *"Is this assessment actually testing 
> application or just recall?"*

**Push back on Claude's output.**
If something doesn't feel right, 
say so. Claude can revise, 
reconsider, and improve — 
but only if you engage critically 
with the first draft.

---

## What These Files Won't Do

**They won't replace your expertise.**
Claude with a skill file is a better 
thought partner — not a replacement 
for instructional design judgment. 
You still make the calls.

**They won't guarantee accurate content.**
Claude can generate instructionally 
sound *structures* — but you are 
responsible for the accuracy of 
subject matter content. 
Always have SMEs review for accuracy.

**They won't test your course for you.**
QA still requires human eyes, 
keyboard testing, screen readers, 
and real learners. Claude can help 
you prepare for QA — not replace it.

---

## Contributing Your Own Combinations

Found a prompt that works especially well? 
A combination of files that produces 
great output for a specific project type?

Share it:
- Open a pull request to add it to `COMBINATIONS.md`
- Start a Discussion in the repo

The best prompt library is built 
by working practitioners — 
not imagined in advance.

---

*Questions? Open an Issue 
and tag it `question`.*
