# Instructional Design Skill: UI Control Design for E-Learning

## Overview
Interactive controls—buttons, toggles, sliders, drag zones,
selectors—are the primary interface between a learner and an
e-learning experience. When controls are well-designed, learners
know intuitively what they do, how to use them, and what to expect.
When controls are poorly designed, learners spend cognitive energy
on the interface instead of the content.

This skill file addresses a specific and recurring failure mode
in AI-assisted e-learning design: **additive redundancy**—the
tendency to layer labels, icons, and indicators *on top of*
controls rather than letting the control itself carry the meaning.
The result is cluttered, oversized, off-proportion UI that creates
friction instead of clarity.

Use this file when:
- Designing or reviewing interactive controls in Rise, Storyline,
  or any web-based learning environment
- Prompting AI to generate or refine UI mockups
- Evaluating whether a control is pulling its weight—or just
  adding weight

---

## Core Principle: The Control Is the Communication

A well-designed interactive control doesn't need a separate
element to explain what it does. It communicates its purpose,
state, and affordance through its own visual properties—shape,
color, motion, proportion, and position.

**The test:** Remove every label and supplementary indicator
from the control. Does it still communicate what it does and
what state it's in?

If yes: the design is doing its job.
If no: the design is relying on explanation rather than
embodying clarity.

This principle doesn't mean labels are always wrong. It means
labels should add precision, not carry meaning the control
itself should already be communicating.

---

## The Additive Redundancy Problem

AI tools default to additive redundancy when designing UI
controls. The pattern looks like this:

1. A functional but generic control is generated (a gray
   rounded rectangle toggle, a neutral slider)
2. Meaning is added *on top of* the control through
   supplementary elements: colored dots, icon overlays,
   text labels, directional arrows
3. The result is a control that is larger than it needs to
   be, visually cluttered, and often out of proportion with
   the surrounding interface

**Why AI defaults to this pattern:**
Additive redundancy is the path of least resistance. It
requires no synthesis—just addition. Each element solves
one communication problem in isolation without considering
whether the control itself could solve all of them at once.

**The design thinking AI often skips:**
*How can this control embody its meaning rather than
annotate it?*

---

## The Principle in Practice: Control Types

### Toggles
**The additive redundancy version:**
A gray rounded rectangle toggle with colored dots, icons,
or text labels placed *over* or *beside* it to indicate
the two states.

**The integrated version:**
The toggle itself shifts in color, texture, or tone as
it moves between states. The visual change *is* the
communication. No supplementary indicators needed.

**Example:**
A toggle for switching between a warm and cool color
palette shifts from amber tones (warm state) to blue-gray
tones (cool state) as the user slides it. The control
communicates the palette *and* acts as the mechanism for
selecting it. One element. No redundancy.

**Design questions to ask:**
- What are the two states, and how are they meaningfully
  different?
- How can the visual properties of the toggle itself
  (color, texture, shape weight) signal that difference?
- What supplementary elements can be removed once the
  toggle carries its own meaning?

---

### Sliders
**The additive redundancy version:**
A neutral slider with separate labels at each end, a
separate indicator showing the current value, and
possibly an icon to explain what the slider controls.

**The integrated version:**
The slider track itself changes as the handle moves—
shifting color, filling progressively, or changing
texture—so the position of the handle and the state of
the track together communicate the current value and
direction of change.

**Design questions to ask:**
- What does movement along this slider *mean*? Can the
  visual properties of the track communicate that meaning
  as the handle moves?
- Is the current value label necessary, or does the
  position of the handle already communicate it clearly
  enough?

---

### Buttons
**The additive redundancy version:**
A button with a label, an icon, a tooltip, and a border—
all communicating the same thing.

**The integrated version:**
Shape, color, and label work together to communicate
purpose. Hover and active states communicate interactivity
and response. The button's visual weight in the layout
communicates its relative importance.

**Design questions to ask:**
- Does this button's visual weight match its importance
  in the interface hierarchy?
- Is every element on this button (icon, label, border,
  tooltip) adding distinct meaning—or are some of them
  just hedging against unclear design?
- Does the hover state clearly signal that this is
  interactive without requiring a cursor change alone
  to communicate it?

---

### Drag-and-Drop Zones
**The additive redundancy version:**
A neutral drop zone with a dashed border, a label
("Drop here"), and an icon—all explaining what the
zone does.

**The integrated version:**
The zone responds visually as the draggable element
approaches—changing color, enlarging slightly, or
highlighting—so the interaction itself communicates
affordance in the moment it's needed.

**Design questions to ask:**
- Does the drop zone communicate its purpose before
  the learner starts dragging, or does it communicate
  it *during* the interaction when it's most relevant?
- What visual response would make a learner feel
  confident they're about to drop in the right place?

---

### Progress Indicators
**The additive redundancy version:**
A progress bar with a percentage label, a step counter,
and section titles all displayed simultaneously.

**The integrated version:**
A progress indicator whose visual weight, proportion, and
movement feel calibrated to the actual effort involved—
not just the number of steps completed.

**Design questions to ask:**
- Does the progress indicator feel proportional to the
  effort the learner has invested?
- Are step numbers and percentage labels adding useful
  precision, or are they creating anxiety about how much
  remains?

---

## Proportion and Scale

One of the most common failures in AI-generated UI is
proportion. Controls are frequently generated at a scale
that made sense in isolation but is wrong in context—
too large relative to surrounding text, too heavy for the
visual weight of the screen, or too prominent relative to
their importance in the interaction.

**The proportion test:**
Place the control in context—surrounded by the actual
content it will accompany. Does its size feel calibrated
to its role? Or does it dominate space it shouldn't own?

**Common proportion failures:**
- Toggles that are sized like primary navigation elements
  when they're controlling a minor preference
- Buttons that are larger than headlines
- Sliders that span the full width of a screen when
  they're adjusting a secondary setting
- Drop zones that consume more visual space than the
  content they're meant to receive

**The fix:**
Size controls relative to their importance in the
interaction hierarchy—not relative to how they look
in isolation.

---

## Prompting AI for Better Control Design

When using AI to generate or refine UI controls, generic
prompts produce generic (additive, oversized) results.
More specific prompts produce more integrated designs.

**Weak prompt:**
"Design a toggle for switching between warm and cool
color palettes."

**Stronger prompt:**
"Design a compact toggle that shifts between warm amber
tones and cool blue-gray tones as the user slides it.
The toggle itself should signal the two palette states
through its own color properties—no additional icons or
labels needed. Scale it to feel like a secondary control,
not a primary navigation element."

**Key elements of a stronger prompt:**
- Specify the *meaning* the control needs to communicate,
  not just its function
- Specify how the control's own visual properties should
  carry that meaning
- Specify scale relative to its role in the interface
- Explicitly exclude redundant supplementary elements
  ("no additional icons or labels")
- Describe the desired state change visually

---

## Reviewing AI-Generated Controls: A Quick Checklist

Before accepting an AI-generated UI control, ask:

☐ **Does the control communicate its purpose without
   supplementary labels or icons?**
   If not, can those elements be removed by making the
   control itself more expressive?

☐ **Is the scale proportional to the control's role
   in the interface?**
   Secondary controls should feel secondary. Primary
   actions should feel primary.

☐ **Does the control's visual change between states
   clearly signal the state it's in?**
   A user should never have to read a label to know
   whether a toggle is on or off.

☐ **Has additive redundancy been introduced?**
   Count the number of elements communicating the same
   thing. Eliminate the redundant ones by making the
   remaining elements do more work.

☐ **Does the control feel like it belongs to the same
   design system as the surrounding interface?**
   A control generated in isolation rarely inherits the
   visual weight, color palette, or typographic scale
   of the surrounding UI without explicit prompting.

---

## Patterns Worth Examining

- **The annotated toggle** — a toggle whose states are
  communicated by labels and icons rather than by the
  toggle's own visual properties; the result is a toggle
  that needs explaining
- **The oversized secondary control** — a preference
  or filter control sized like a primary action; dominates
  space it shouldn't own
- **The neutral slider** — a slider with no visual
  feedback along its track; position of the handle is
  the only communication, which is rarely enough
- **The over-labeled button** — icon + label + tooltip +
  border, all communicating the same affordance; remove
  three of the four
- **The static drop zone** — a drop target that doesn't
  respond visually until after the drop; learners lose
  confidence mid-interaction
- **The isolated control** — a control designed without
  reference to surrounding UI; correct in isolation,
  wrong in context

---

## References & Further Reading
- *The Design of Everyday Things* — Don Norman (affordance,
  signifiers, and feedback as core design principles)
- *Don't Make Me Think* — Steve Krug (cognitive load and
  intuitive interface design)
- *Designing Interactions* — Bill Moggridge (how interaction
  design thinking developed)
- Nielsen Norman Group on toggle design —
  nngroup.com/articles/toggle-switch-guidelines
- Nielsen Norman Group on affordances —
  nngroup.com/articles/affordance-signifiers
- Inclusive Components by Heydon Pickering —
  inclusive-components.design (accessible, semantic
  interactive component design)
