# Instructional Design Skill: Character Design for E-Learning

## Overview
Characters are one of the most powerful tools in e-learning design—and
one of the most frequently mishandled. When done well, characters create
emotional investment, model realistic decision-making, and make abstract
scenarios feel grounded and human. When done poorly, they distract,
exclude, and undermine the instructional experience.

This skill helps Claude support instructional designers in creating,
specifying, and evaluating characters for e-learning—across all visual
styles, with particular attention to consistency, diversity, and
inclusive representation.

---

## Core Principle: Characters Serve the Learning, Not the Aesthetic

A character exists to help the learner engage with a realistic situation.
Every design decision—visual style, representation, emotional range,
naming—should serve that purpose.

Characters that feel familiar, believable, and consistently rendered
lower cognitive load and increase emotional investment. Characters that
feel generic, inconsistent, or unrepresentative create distance and
signal to some learners that the experience wasn't designed with them
in mind.

---

## Visual Style: More Than One Right Answer

Characters in e-learning exist across a wide spectrum of visual styles.
No single style is inherently superior—the right choice depends on
audience, tone, subject matter, and production context.

### Photorealistic / Photography-Based
Rendered or photographed characters that closely resemble real people.

- **Strengths:** High emotional realism; strong for sensitive or
  high-stakes topics (healthcare, safety, crisis scenarios)
- **Challenges:** Uncanny valley risk; expensive to produce at quality;
  consistency across emotional states is technically demanding
- **Consistency challenge:** Photorealistic characters are the hardest
  to re-render consistently—skin tone, facial structure, and clothing
  can shift between generations even with careful prompting

### Flat / Vector Illustration
Clean, simplified characters with solid shapes and limited detail.
Common in modern SaaS and corporate design aesthetics.

- **Strengths:** Scalable, consistent, fast to produce; works well
  across cultures without implying a specific nationality
- **Challenges:** Can feel sterile or impersonal; limited emotional
  expressiveness without careful design
- **Reference systems:** Humaaans (Pablo Stanley), Avataaars

### Hand-Drawn / Sketch Style
Characters that retain the texture and personality of hand illustration.

- **Strengths:** Warm, approachable, distinctive; communicates craft
  and humanity; strong for training that benefits from a less
  "corporate" feel
- **Challenges:** Style consistency is harder to maintain across a
  large library; emotional states require careful expression design
- **Reference systems:** Open Peeps (Pablo Stanley)

### Comic Book / Graphic Novel Style
Bold lines, dynamic poses, expressive faces. Higher energy and
stylization than flat illustration.

- **Strengths:** High engagement for the right audience; excellent
  emotional range; strong for scenario-based content requiring
  dramatic tension
- **Challenges:** May feel tonally mismatched for formal or sensitive
  content; requires intentional diversity in the illustration style
  itself, not just surface representation

### Cartoon / Animated Style
Simplified, expressive, often exaggerated characters. Common in
consumer-facing learning products.

- **Strengths:** Highly accessible; low visual intimidation; works
  well for younger audiences or lighter content
- **Challenges:** Risk of infantilizing the content; diversity can
  be harder to signal without stereotyping in a highly simplified style

### Choosing a Style
Match the visual style to the emotional register of the content:

| Content type | Suggested style direction |
|---|---|
| High-stakes clinical or safety scenarios | Photorealistic or detailed illustration |
| Corporate soft skills / leadership | Flat vector or hand-drawn |
| Compliance / policy | Flat vector |
| Customer service / sales | Any; match to brand |
| Community-facing or consumer | Cartoon or hand-drawn |
| Portfolio / demonstration work | Flat vector or hand-drawn |

---

## The Consistency Problem

Regardless of visual style, character consistency is the most
technically demanding requirement in e-learning character design—
and one of the most frequently underestimated.

A character must be immediately recognizable as the same person
across:
- Multiple emotional states (neutral, approving, concerned,
  skeptical, distressed)
- Multiple poses (standing, gesturing, seated, active)
- Multiple scenes and screen layouts

**What breaks consistency:**
- Changes in skin tone between renders
- Hair texture, color, or length shifting between scenes
- Clothing colors or patterns changing unexpectedly
- Facial proportions drifting across emotional states
- Eye shape or color inconsistency
- Line weight or illustration style shifting between renders
  (especially relevant for hand-drawn and comic styles)

**Why this matters instructionally:**
Inconsistent characters create cognitive disruption. Learners who
notice a character's appearance has changed—even subconsciously—
are pulled out of the scenario and into confusion. Trust in the
learning experience erodes. The scenario loses its immersive power.
This applies equally whether the character is photorealistic,
hand-drawn, flat vector, or cartoon—the consistency requirement
does not diminish with stylization.

---

## Maintaining Consistency Across AI-Generated Characters

AI image generation produces characters of impressive quality—but
consistency across multiple renders is a known limitation across
all current generation systems, regardless of visual style.

### The Reference Image Anchor Technique
The most reliable approach for AI-generated characters:

1. Generate a single **reference image** for the character in a
   neutral pose and expression
2. Evaluate the reference image carefully before proceeding—this
   is your design approval moment
3. Use the approved reference image as an explicit anchor in all
   subsequent generation prompts
4. Generate all emotional states and poses from that single anchor
5. Evaluate each new render against the reference before deploying

**Prompting principle:** Every generation prompt after the first
should include:
- A complete description of the character's fixed visual attributes
  (skin tone, hair texture/color/length, eye color, clothing
  colors and style, illustration style)
- An explicit instruction that only expression and pose should vary
- A reference to the anchor image where the generation system
  supports image-to-image prompting

### Prompt Structure for Consistent Re-Rendering

When specifying a character for AI generation, provide a complete
visual specification that travels with every prompt:

```
Character: [Name]
Role: [Job title / context]
Visual style: [flat illustration / hand-drawn / photorealistic /
  comic / cartoon — be specific about style details]
Skin tone: [specific descriptor]
Hair: [texture, color, length, style — be specific]
Eyes: [color, shape]
Clothing: [specific garments, colors, any cultural or professional
  markers — do not vary between renders]
Expression: [the specific emotional state for this render]
Pose: [standing / gesturing / seated / etc.]
Background: [if applicable]

IMPORTANT: Do not alter any attribute except expression and pose.
Maintain exact clothing colors, hair appearance, facial features,
and illustration style from the reference.
```

The more specific the specification, the more consistent the output.
Vague descriptions produce drift—this is true for all visual styles,
not just photorealistic rendering.

### Evaluating Character Consistency
Before deploying a character set, evaluate across these dimensions:

- [ ] Same skin tone across all renders
- [ ] Same hair texture, color, and general style
- [ ] Same clothing, colors, and any accessories
- [ ] Recognizably the same face across emotional states
- [ ] Consistent illustration style, line weight, and visual treatment
- [ ] Emotional states are clearly distinguishable from each other
- [ ] Poses feel natural and appropriate to the scenario context
- [ ] Character reads as the same person in thumbnail size

If any render fails this checklist, regenerate before deploying.

---

## Inclusive Character Design

Inclusive character design is not a checklist item—it is a design
philosophy that shapes every decision from the beginning. Characters
in e-learning implicitly communicate who belongs in a professional
context, whose experiences are centered, and whose are treated as
edge cases. This responsibility applies across all visual styles:
a cartoon character, a hand-drawn character, and a photorealistic
character all carry representation signals.

### Names

- Characters must have full names (first and last)
- Do not default to Western European or Anglo-American naming
  conventions
- Names must reflect the genuine diversity of the global workforce—
  draw from South Asian, East Asian, Southeast Asian, Middle Eastern,
  African, Latin American, Eastern European, Indigenous, and other
  naming traditions
- Distribute names across roles and seniority levels without
  assigning cultural background based on role type or status
- Names should feel natural and authentic to their cultural origin,
  not anglicized or softened for perceived audience comfort
- Across a portfolio of generated content, no single naming tradition
  should dominate

### Physical Representation

**Skin tone**
Generate characters across the full range of human skin tones.
Do not default to light skin as the neutral or unmarked option.
This applies to all visual styles—flat illustration and cartoon
characters carry skin tone signals just as photorealistic ones do.

**Hair**
Hair is the single most culturally coded visual feature in
illustration and one of the most commonly defaulted away from
diversity in AI generation. Explicitly specify and rotate across:
- Coiled and tightly coiled natural hair
- Locs and protective styles
- Braids (cornrows, box braids, and others)
- Natural volume and afro textures
- Straight hair across a range of textures
- Wavy hair
- Grey, silver, and white hair (representing age authentically)

Do not default to straight or loosely wavy hair as the unmarked
norm—across any visual style.

**Facial features**
Skin tone is the most visible diversity signal but not the only one.
Nose shape, eye shape, face structure, and lip shape are also
culturally coded features that AI systems default away from
diversity on. Explicitly vary these features across a character
portfolio. This is especially important in simplified or cartoon
styles, where the temptation is to use a single "neutral" face
shape with varying skin tones applied.

**Age**
AI systems default to generating characters who appear to be in
their late 20s to mid-30s. Explicitly include:
- Characters who appear to be in their 40s, 50s, and 60s
- Visible signs of age (lines, grey hair)
- A range of career stages, not just early career representation

**Body type**
Avoid defaulting to a single body type across characters. Vary
build, height impression, and physical presentation deliberately.

**Disability and visible difference**
Where scenario context supports it, include characters with
visible disabilities, assistive devices, or other visible markers
of difference—not as the subject of the training, but as
participants in it.

### Gender and Role Distribution

- Do not assign gender based on role type, seniority level,
  or industry
- Women should appear as frequently as men in positions of
  authority, technical expertise, and decision-making
- Do not default men to roles that deliver corrections,
  expertise, or authority; do not default women to roles
  that receive guidance or provide emotional support
- Non-binary and gender-nonconforming characters are welcome
  and should not be confined to specific role types or
  supporting roles
- Subject matter experts, authority figures, and characters
  who provide correction or guidance should be drawn from
  diverse cultural backgrounds and should not default to
  male presentation

### Professional Presentation and Clothing

Avoid defaulting to Western professional dress (business suit,
blazer, button-down) as the universal signal for "professional."
A wide range of professional presentation styles exist globally:

- Hijab and other head coverings in professional contexts
- Natural hair in professional settings (not "dressed down")
- Traditional or cultural garments worn professionally
- Varying formality norms across industries and cultures
- Religious or cultural jewelry and markers

Professional is not a single aesthetic. Design characters whose
clothing reflects the genuine diversity of how professional
people present themselves—and remember that clothing is one of
the fixed attributes that must not vary between renders.

### The "Neutral" Trap

Some illustration systems attempt to solve representation
by making characters deliberately ambiguous—pale or desaturated
skin, minimal facial features, androgynous presentation. This
approach backfires: it represents no one, and it typically
defaults to a Eurocentric aesthetic anyway.

Specificity is better than false neutrality. Generate genuinely
diverse characters with distinct, culturally specific features.
Representation requires presence, not erasure. This applies
equally to simplified and cartoon styles—a highly stylized
character still carries representation signals and still benefits
from intentional, specific design choices.

---

## Character Design: Patterns Worth Examining

- **The default character**—generating characters without explicit
  diversity constraints produces a predictable output: light skin,
  straight or loosely wavy hair, Western professional dress,
  male in authority roles, female in support roles. This is not
  neutral. It is a design choice with real consequences for who
  feels represented in the learning experience. It applies across
  all visual styles.

- **Skin tone as the only diversity lever**—changing skin tone
  while keeping all other features (hair texture, facial structure,
  clothing, naming) constant produces a superficial diversity
  that still centers a single cultural aesthetic.

- **Consistency neglect**—treating character consistency as
  a nice-to-have rather than a core design requirement. Inconsistent
  characters break immersion and undermine the scenario's
  instructional power regardless of visual style or how well-written
  the content is.

- **Style-representation mismatch**—choosing a highly simplified
  cartoon style and assuming it handles representation automatically
  because features are minimal. Simplified styles still carry
  representation signals and require the same intentional design
  as more detailed styles.

- **Age erasure**—populating an entire course with characters
  who appear to be the same age range. Real workplaces span
  multiple generations; scenario characters should reflect that.

- **Emotional state as the only variation**—designing a character
  system where expression changes but pose never does. Characters
  who stand perfectly still while their faces shift expression
  feel uncanny and robotic. Pose variation is as important as
  expression variation for believability—across all styles.

- **Forgetting that clothing is fixed**—clothing, accessories,
  and any cultural or professional markers on a character are
  fixed attributes. They must not change between renders of the
  same character. Changing a character's clothing between scenes
  signals a different character or breaks continuity.

---

## References & Further Reading

- Humaaans illustration system — humaaans.com (Pablo Stanley)
- Open Peeps illustration system — openpeeps.com (Pablo Stanley)
- Blush Design — blush.design (diverse illustration packs from
  global artists)
- 7Taps microlearning platform — reference benchmark for
  character consistency across emotional states
- *Accessibility in E-Learning* skill file (this library) —
  for guidance on characters and disability representation
- *Visual Design Principles* skill file (this library) —
  for broader visual design guidance
- Bianca Woods on inclusive design in learning — biancawoods.com
