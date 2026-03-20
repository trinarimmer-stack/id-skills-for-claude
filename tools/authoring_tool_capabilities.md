# Instructional Design Skill: Authoring Tool
Capabilities and Constraints

## Overview
Knowing what your authoring tool can and cannot do 
is essential for designing learning experiences 
that are technically feasible — not just 
instructionally sound. This skill helps Claude 
understand the capabilities, constraints, and 
ideal use cases of the most widely used 
e-learning authoring tools, so design 
recommendations stay grounded in what's 
actually buildable.

> **Note on currency:** Authoring tool capabilities 
> change with software updates. This file reflects 
> features as of early 2026. Always check the 
> tool's release notes for recent additions.

---

## How to Use This File

When asking Claude for design help, specify 
your authoring tool upfront:

> *"I'm building this in Storyline 360. 
> What interaction types would work 
> for this scenario?"*

Claude will then tailor recommendations 
to what's technically achievable in 
your specific environment.

---

## Articulate Storyline 360

### What It Is
Storyline 360 is a slide-based e-learning 
authoring tool that gives designers 
significant control over layout, 
interactions, animation, and branching. 
It is the most widely used professional 
e-learning authoring tool in the industry.

### Publishing Formats
- HTML5 (primary — all modern browsers)
- SCORM 1.2
- SCORM 2004 (all editions)
- xAPI (Tin Can)
- AICC
- LMS-agnostic web output
- Video (MP4) — limited interactivity

### Natively Supported Interaction Types
These interactions can be built without 
custom code:

**Assessment and knowledge check:**
- Multiple choice (single and multi-select)
- True/false
- Fill in the blank
- Matching (drag and drop, drop-down)
- Sequence/ordering
- Hotspot (click on image)
- Numeric entry
- Short answer (text entry, unscored)
- Likert scale

**Scenario and decision-making:**
- Branching scenarios (slide-level branching)
- Branching via result slides
- Variables-driven conditional branching
- Layered content reveals
- Drag and drop (freeform)
- Pick one / pick many (freeform)

**Navigation and structure:**
- Custom navigation (lock, free, restricted)
- Menu/table of contents (show/hide)
- Lightbox slides
- Slide layers (show/hide on trigger)
- Scene-based organization

**Media and engagement:**
- Embedded video (mp4, YouTube, Vimeo)
- Audio narration per slide/layer
- Animated characters (Storyline assets)
- Screen recording (basic)
- Animated entrance/exit effects
- 360° image viewer (basic)

### Review and Feedback
Articulate Review 360 is a companion 
review tool included with Articulate 360 
subscriptions. Designers publish a 
shareable review link; stakeholders 
and SMEs can leave timestamped, 
contextual comments directly on slides 
or course content without needing 
an Articulate account.

Key features:
- Timestamped comments on specific slides 
  or interactions
- Threaded discussion per comment
- Mark comments as resolved
- Version history — reviewers can 
  compare current version to previous
- No stakeholder login required — 
  review via shareable link
- Works with both Storyline and Rise output

### What Requires JavaScript/Custom Code
These features are possible but require 
custom development:

- Complex variable logic beyond basic 
  true/false or numeric
- Pulling or pushing data to external systems
- Dynamic text population from external sources
- Custom question types beyond native formats
- Sophisticated scoring algorithms
- Real-time feedback based on multiple 
  cumulative variables
- Accessible custom interactions 
  (often requires JS to fix tab order)

### What Is Not Possible in Storyline
- **Native AI integration** — 
  no built-in AI response or 
  adaptive learning engine
- **Real-time collaborative authoring** — 
  one author at a time per file
- **Responsive/fluid layout** — 
  Storyline uses fixed canvas sizes; 
  mobile scaling is approximate, 
  not truly responsive
- **Native form submission to external databases** 
  without custom API work
- **True adaptive learning paths** 
  without significant custom variable logic
- **Native video creation or editing**
- **360° video** — Storyline supports 
  basic 360° image viewing but does not 
  support interactive 360° video; 
  this was a frequent feature request 
  and remains unsupported as of 2026
- **Offline mobile app delivery** 
  without third-party tools

### Accessibility in Storyline
- Tab order: customizable per slide
- Alt text: supported for all media
- Closed captions: supported (via SRT files 
  or manual entry)
- Focus indicators: visible but limited 
  customization
- Screen reader support: partial — 
  complex interactions often require 
  manual accessibility remediation
- Color contrast: designer's responsibility — 
  no built-in checker
- Keyboard navigation: supported for 
  standard interactions; custom interactions 
  may require JS fixes

### Storyline's Sweet Spot
Storyline excels at:
- Branching scenarios with multiple 
  decision points
- Custom-designed, pixel-precise screens
- Complex variable-driven interactions
- Simulations (software, process)
- Courses requiring unique visual design 
  that breaks from templates
- High-fidelity interactive assessments

### Storyline's Limitations to Design Around
- **Mobile experience** — fixed canvas 
  doesn't adapt gracefully to small screens; 
  design for desktop first or use Rise 
  for mobile-priority content
- **Collaboration** — not suited to 
  multi-author simultaneous editing
- **Speed** — high-fidelity Storyline 
  courses take longer to build than 
  template-based tools
- **File size** — complex courses with 
  rich media can produce large files 
  that load slowly on slow connections

---

## Articulate Rise 360

### What It Is
Rise 360 is a browser-based, 
responsive e-learning authoring tool 
built on pre-designed block templates. 
It produces courses that are inherently 
mobile-responsive and visually consistent. 
Rise trades Storyline's design flexibility 
for speed, consistency, and accessibility.

### Publishing Formats
- HTML5 (responsive, all modern browsers)
- SCORM 1.2
- SCORM 2004
- xAPI (Tin Can)
- PDF (limited — for reference only)
- Shareable link (no LMS required)
- Embed (iframe)

### Natively Supported Interaction Types

**Content blocks (non-interactive):**
- Text (paragraph, bulleted, numbered)
- Image (single, gallery, full-width)
- Video (embedded or uploaded)
- Audio
- Quote
- Divider/spacer
- Accordion
- Tabs
- Labeled graphic (hotspot image)
- Process (linear steps)
- Timeline
- Sorting activity (basic categorization)
- Flashcards
- Button (link or scroll)

**Interactive blocks:**
- Knowledge check (multiple choice, 
  multiple select, fill in the blank, 
  matching, reorder, hotspot)
- Quiz (graded, with pass/fail and 
  result feedback)
- Scenario block (built-in branching 
  scenario template)
- Storyline block (embed a Storyline 
  interaction directly into Rise)
- Continue block (requires interaction 
  before advancing)

### The Storyline Block: Rise's Power Move
The most important thing to know about 
Rise's capabilities: **anything Rise 
can't do natively, Storyline can do 
inside Rise via a Storyline block.**

This means:
- Complex branching → build in Storyline, 
  embed in Rise
- Custom interactions → build in Storyline, 
  embed in Rise
- Simulations → build in Storyline, 
  embed in Rise

The hybrid Rise + Storyline approach 
gives designers the best of both tools: 
Rise's speed, responsiveness, and 
visual consistency for content delivery; 
Storyline's power for complex interactions.

### Review and Feedback
Rise 360 uses the same Articulate Review 360 
tool as Storyline — included with all 
Articulate 360 subscriptions.

Key features:
- Shareable review link — 
  no stakeholder account required
- Contextual comments on specific 
  lessons or blocks
- Threaded comment discussion
- Mark comments as resolved
- Version history and comparison
- Works seamlessly with both 
  Rise and Storyline output

### What Requires Workarounds in Rise
- **Complex branching** — Rise's scenario 
  block supports basic branching; 
  anything more complex needs a 
  Storyline block
- **Custom visual design** — Rise templates 
  are highly constrained; brand 
  customization is limited to colors, 
  fonts, and cover images
- **Advanced scoring logic** — Rise quiz 
  scoring is straightforward; 
  complex weighted scoring requires 
  Storyline
- **Variable tracking across lessons** — 
  Rise doesn't support cross-lesson 
  variables natively

### What Is Not Possible in Rise
- **Pixel-precise layout control** — 
  Rise is block-based; you cannot 
  freely position elements on a canvas
- **Custom animations** — no entrance/exit 
  effects beyond block reveals
- **Complex conditional logic** — 
  no native variable system
- **Custom question types** — 
  limited to Rise's native question formats 
  without a Storyline block
- **Full custom branding** — 
  typography, layout structure, 
  and block styles are constrained 
  by Rise's template system
- **Hosted offline delivery** — 
  Rise requires an internet connection 
  for hosted/LMS delivery; however, 
  Rise courses exported as HTML5 
  can be added to a user's desktop 
  for local launch without a browser 
  or internet connection, making it 
  a viable option for low-bandwidth 
  environments

### Accessibility in Rise
Rise is the more accessible of the 
two Articulate tools by default:
- Inherently keyboard navigable
- Logical reading order maintained 
  automatically
- Alt text: supported for all images
- Closed captions: supported for video
- Color contrast: themes can be customized; 
  designer is responsible for contrast ratios
- Screen reader support: strong for 
  native Rise blocks; Storyline blocks 
  embedded in Rise inherit Storyline's 
  accessibility limitations

### Rise's Sweet Spot
Rise excels at:
- Mobile-first or mobile-critical content
- Fast development timelines
- Consistent visual design at scale
- Microlearning and reference content
- Onboarding and orientation courses
- Content that needs to be updated frequently
- Teams with varying design skill levels 
  (templates reduce quality variance)
- Low-bandwidth environments 
  (via HTML5 local launch)

### Rise's Limitations to Design Around
- **Interaction depth** — for anything 
  beyond basic knowledge checks and 
  simple branching, plan to embed 
  a Storyline block
- **Brand control** — if the organization 
  has strict visual identity requirements 
  that go beyond color and font, 
  Rise may not deliver
- **Complex assessment** — Rise quizzes 
  are functional but limited; 
  high-stakes assessments with 
  complex scoring belong in Storyline

---

## Trivantis Lectora Suite

### The Trivantis Product Family

Trivantis offers three distinct products.
Understanding which one is in use matters
because their capabilities, licensing,
and delivery contexts differ significantly.

**Lectora Desktop**
The original, installed Windows application.
Slide-based authoring with the most
granular control over accessibility,
SCORM output, and conditional logic.
Preferred in organizations with strict
IT governance, air-gapped environments,
or legacy LMS infrastructure that requires
predictable SCORM behavior. Not cloud-based —
projects live on the author's machine or
a shared network drive.

**Lectora Online**
The cloud-based version of Lectora.
Functionally similar to Lectora Desktop
but accessed via browser, with the addition
of real-time multi-author collaboration
and responsive design output. The version
most commonly referenced in current job
postings and vendor documentation.
Where "Lectora" is mentioned without
qualification in this file, Lectora Online
is the primary reference unless otherwise noted.

**CenarioVR**
Trivantis's 360° video and virtual reality
authoring tool. Allows designers to create
immersive, branching 360° experiences
without coding — hotspots, decision points,
and scored interactions can be layered onto
360° video or photospheres. Publishes to
web, mobile, and VR headset formats.
Integrates with Lectora and reports via xAPI.

CenarioVR is the right tool when:
- The learning context benefits from
  spatial orientation or environmental
  familiarity (safety walkthroughs,
  facility orientation, procedural training
  in complex physical environments)
- 360° video of a real environment is
  available or can be produced
- The organization has VR headsets or
  wants mobile-based immersive delivery
- xAPI reporting on immersive experiences
  is required

CenarioVR is not the right tool when:
- Standard scenario-based or knowledge
  check interactions will serve the
  learning objective equally well
- 360° video production is not feasible
- The learner population has accessibility
  needs that VR/360° formats cannot meet

### What Lectora (Desktop and Online) Is
Lectora is a slide-based e-learning authoring
tool with a long history in the industry —
particularly strong in regulated industries
(healthcare, pharmaceutical, government,
financial services) where Section 508
compliance, SCORM reliability, and
audit trails matter most. It offers
more granular accessibility controls
than either Storyline or Rise,
and has historically been the tool
of choice for organizations with
strict compliance requirements.

### Publishing Formats
**Lectora Desktop and Online:**
- HTML5 (all modern browsers)
- SCORM 1.2
- SCORM 2004
- xAPI (Tin Can)
- AICC
- Section 508-compliant output
- Responsive design (Lectora Online only)
- CD/offline (Lectora Desktop legacy — less common)

**CenarioVR:**
- Web (HTML5, mobile browser)
- xAPI
- VR headset formats (Oculus, HTC Vive)
- Mobile app delivery

### Natively Supported Interaction Types

**Assessment and knowledge check:**
- Multiple choice (single and multi-select)
- True/false
- Fill in the blank
- Matching
- Sequence/ordering
- Hotspot
- Numeric entry
- Short answer
- Essay (text entry)
- Survey questions (Likert, rating)

**Scenario and decision-making:**
- Branching via page actions and 
  conditional logic
- Variable-driven branching 
  (more robust than Storyline natively)
- Decision trees
- Scored branching scenarios

**Navigation and structure:**
- Fully customizable navigation
- Table of contents
- Conditional page display
- Page locking and unlocking
- Chapter/section/page hierarchy

**Media and engagement:**
- Embedded video and audio
- Animated objects
- Screen recording (via Camtasia integration)
- Web objects (embed external content)
- Co-author collaboration 
  (Lectora Online)

### Review and Feedback
Lectora includes **ReviewLink**, 
a built-in stakeholder review tool 
that functions similarly to 
Articulate Review 360.

Key features:
- Shareable review link — 
  no reviewer account required
- Contextual comments on specific pages
- Threaded comment discussion
- Mark comments as resolved
- Version tracking across review cycles

### What Lectora Does Better Than
Storyline or Rise

**Accessibility**
Lectora offers the most granular 
accessibility controls of any major 
authoring tool:
- Full ARIA landmark and role assignment
- Granular tab order control at the 
  object level
- Reading order independent of 
  visual layout
- Robust screen reader support 
  (JAWS, NVDA, VoiceOver)
- Built-in accessibility checker
- Section 508 and WCAG 2.1 AA 
  compliance tools built into the workflow

For organizations in regulated industries 
or those with strict accessibility 
audit requirements, Lectora is often 
the only viable choice.

**Variable and conditional logic**
Lectora's action/condition system is 
more powerful natively than Storyline's 
trigger/variable system — complex 
conditional logic can be built without 
custom JavaScript in scenarios where 
Storyline would require it.

**Collaboration**
Lectora Online supports real-time 
multi-author collaboration — 
a significant advantage over Storyline 
for large team projects.

**SCORM reliability**
Lectora has a long track record of 
rock-solid SCORM communication — 
particularly valued in enterprise LMS 
environments where SCORM compliance 
is audited.

### What Requires Workarounds in Lectora
- **Visual design** — Lectora's interface 
  and default styling are less polished 
  than Storyline or Rise; achieving 
  high-fidelity visual design requires 
  more manual effort
- **Character and asset library** — 
  Lectora's built-in asset library 
  is limited compared to Articulate 360's 
  Content Library
- **Animation** — entrance/exit animations 
  are functional but less fluid than 
  Storyline's

### What Is Not Possible in Lectora Desktop or Online
- **Truly responsive layout** —
  Lectora Online offers responsive design
  but it is not as seamless as Rise
- **Native AI integration** —
  no built-in AI response or
  adaptive engine
- **360° video** — not supported in
  Lectora Desktop or Online; use
  CenarioVR (separate Trivantis product)
  for 360° and VR experiences
- **Built-in branching scenario templates** —
  unlike Rise's scenario block,
  branching must be built manually
  via the action/condition system

### Accessibility in Lectora
Lectora is the industry leader 
for accessibility among authoring tools:
- Full ARIA support
- Granular tab and reading order control
- Built-in accessibility checker 
  with remediation guidance
- Robust screen reader compatibility 
  (JAWS, NVDA, VoiceOver, TalkBack)
- Section 508 compliance output
- WCAG 2.1 AA compliance support

For any project where accessibility 
compliance will be formally audited, 
Lectora is the most defensible choice.

### Lectora's Sweet Spot
Lectora Desktop and Online excel at:
- Regulated industry training
  (healthcare, pharma, government,
  financial services)
- Formally audited Section 508
  or WCAG compliance requirements
- Large team, multi-author projects
  (Lectora Online specifically)
- Enterprise LMS environments requiring
  rock-solid SCORM reliability
- Complex conditional logic without
  custom JavaScript

CenarioVR excels at:
- Safety and procedural training in
  physical environments
- Facility and spatial orientation
- Any context where "being there"
  accelerates learning in ways a
  standard course cannot replicate
- Complex conditional logic without 
  custom code
- Enterprise LMS environments with 
  strict SCORM requirements
- Organizations that need robust 
  audit trail documentation

### Lectora's Limitations to Design Around
- **Visual polish** — achieving 
  Storyline-level visual fidelity 
  requires more design effort
- **Asset library** — plan to source 
  imagery, characters, and icons externally
- **Learning curve** — Lectora's 
  interface is more complex than Rise 
  and arguably steeper than Storyline 
  for new users
- **Community and resources** — 
  Lectora's user community and 
  third-party resource library are 
  smaller than Articulate's

---

## H5P

### The H5P Ecosystem

H5P is an open-source framework for creating interactive HTML5
content. Unlike Storyline, Rise, or Lectora—which are standalone
desktop or cloud applications—H5P is a content type library that
runs inside other platforms. Understanding where H5P lives is
essential before understanding what it does.

**H5P Open Source (free)**
The original, community-maintained version. Runs as a plugin
inside Moodle, WordPress, Canvas, Drupal, and other platforms
that support it. Free to use, but requires a host platform and
some technical comfort to set up. The most common context for
H5P in instructional design is Moodle—H5P is deeply integrated
with Moodle and is a natural choice for organizations already
running Moodle as their LMS.

**H5P.com (freemium)**
A commercial hosted version of H5P that removes the need for
a host platform. Content is created and hosted on H5P.com.
Free tier allows limited content; paid plans unlock more content
types, storage, and reporting. Lower technical barrier than
the open source version but introduces a recurring cost and
platform dependency.

**Which version is relevant:**
For most instructional designers working in organizations that
use Moodle, Canvas, or WordPress — the open source plugin
version is the relevant context. H5P.com is more relevant
for independent designers or small organizations without
an existing LMS. Both produce the same content types;
the difference is in hosting and setup.

Resources:
- h5p.org — open source documentation and content type library
- h5p.com — hosted version
- Moodle H5P integration — docs.moodle.org

### What H5P Is
H5P is not a single tool — it is a library of over 50
distinct interactive content types, each designed for a
specific instructional purpose. This is both its greatest
strength and its steepest learning curve: there is no
single interface to master, because each content type
has its own authoring environment and logic.

H5P is particularly strong in open-source LMS environments
(Moodle, Canvas, WordPress) where budget constraints make
commercial authoring tools impractical. It produces
standards-compliant HTML5 output that is mobile-responsive
by default and reports via xAPI and SCORM 2004 where the
host platform supports it.

The learning curve is real. H5P rewards designers who invest
time learning its content types and configuration options.
Casual or occasional users will find it slower and more
frustrating than commercial tools. It is not the right
choice for designers who need to produce content quickly
without significant upfront investment in learning the platform.

### Key Content Types for Instructional Designers

H5P's 50+ content types range from simple to sophisticated.
The following are the most ID-relevant:

**Branching Scenario**
H5P's most powerful content type for scenario-based learning.
Supports multi-path branching with distinct consequence screens,
embedded media, and scored outcomes. Comparable in concept to
Storyline branching but with a different (and initially less
intuitive) authoring interface. Genuinely capable when mastered.

**Interactive Video**
Overlays questions, hotspots, and navigation points onto
video content. One of H5P's strongest and most distinctive
content types — allows designers to transform existing video
assets into interactive learning experiences. Supports
multiple question types embedded at specific timestamps.

**Course Presentation**
Slide-based content with embedded interactions. Closest
to a traditional e-learning slide deck. Supports a range
of embedded H5P content types within slides. More limited
design control than Storyline but functional for straightforward
content delivery.

**Quiz (Question Set)**
A sequenced set of question types including multiple choice,
true/false, drag and drop, fill in the blank, and mark the words.
Configurable feedback, retry options, and pass/fail thresholds.
Solid for knowledge checks when deep interactivity isn't required.

**Dialog Cards**
Flashcard-style interactions for vocabulary, definitions,
or concept review. Simple to build, effective for spaced
practice content.

**Drag and Drop**
Custom drag-and-drop interactions where designers define
drop zones and draggable elements. Useful for labeling
diagrams, categorization tasks, and matching exercises.
Requires more configuration than it initially appears.

**Image Hotspot**
Clickable hotspots on a static image that reveal information
panels. Useful for equipment identification, spatial
orientation, and visual reference content.

**Accordion**
Expandable content panels. Simple, accessible, useful for
reference material and FAQ-style content where learners
need to explore rather than follow a sequence.

**Timeline**
Chronological content display with media and text. Useful
for historical context, process orientation, and any content
with a temporal dimension.

**Speak the Words / Speak the Words Set**
Speech recognition-based interactions where learners respond
verbally. Uncommon in commercial tools — a genuine differentiator
for language learning or verbal response practice contexts.
Browser support limitations apply.

### Publishing Formats
- HTML5 (all modern browsers, mobile-responsive by default)
- SCORM 2004 (via host platform integration)
- xAPI / Tin Can (where host platform supports it)
- Embedded content (within Moodle, WordPress, Canvas, etc.)
- Standalone embed via H5P.com iframe

Note: H5P does not publish to SCORM 1.2 natively. For
organizations with older LMS infrastructure that requires
SCORM 1.2, this is a significant limitation.

### What H5P Does Well
- **Open source and free:** No licensing cost for the
  core platform — significant advantage in budget-constrained
  environments and nonprofit or educational contexts
- **Moodle integration:** Deep, native integration with
  Moodle — H5P content created inside Moodle grades and
  reports automatically through the Moodle gradebook
- **Mobile-responsive by default:** All H5P content
  renders responsively without additional configuration
- **Interactive video:** One of the best interactive
  video tools available at any price point
- **Branching Scenario depth:** When mastered, H5P
  Branching Scenario produces genuinely sophisticated
  multi-path learning experiences
- **Accessibility:** H5P content types are generally
  well-structured for accessibility, with keyboard
  navigation and screen reader support across most
  content types
- **Community and extensibility:** Active open-source
  community; custom content types can be developed
  for organizations with development resources

### What Is Not Possible in H5P
- **Pixel-perfect visual design:** H5P content types
  have fixed visual templates with limited styling options.
  Designers who need precise control over layout, typography,
  and visual design will find H5P constraining.
- **Custom animations and transitions:** No native support
  for the kind of timeline-based animation available in
  Storyline. Motion is limited to what individual content
  types support.
- **Rapid production:** H5P's learning curve means initial
  production is slower than commercial tools until the
  designer is fluent in the relevant content types.
- **SCORM 1.2:** Not supported natively — a real limitation
  for older LMS environments.
- **Standalone delivery without a host platform:**
  H5P content requires a host (Moodle, WordPress, H5P.com,
  or similar). It cannot be packaged as a self-contained
  deliverable the way a Storyline or Rise export can.
- **Consistent branding across content types:**
  Each content type has its own visual template. Achieving
  a consistent branded look across multiple H5P content
  types in a single course is difficult without custom
  CSS development.

### H5P's Sweet Spot
H5P excels at:
- Moodle-based learning environments where native
  integration and gradebook reporting matter
- Budget-constrained organizations (educational
  institutions, nonprofits, government) where commercial
  licensing is not feasible
- Interactive video — transforming existing video assets
  into interactive learning experiences
- Organizations with developer resources who can extend
  and customize the platform
- Open-source ecosystems where vendor lock-in is a concern
- Designers who are willing to invest time learning the
  platform in exchange for a powerful, free tool

H5P is not the right choice when:
- Rapid production is a priority
- Precise visual design control is required
- The organization uses an LMS that does not support
  H5P integration
- SCORM 1.2 compliance is required
- The designer needs a self-contained, portable output
  file without platform dependencies

### H5P vs. Commercial Tools: The Honest Assessment
H5P is not trying to compete with Storyline or Rise on
production speed or design flexibility. It is a different
tool for a different context. The decision is rarely
"H5P vs. Storyline" — it is usually "H5P because the
budget and platform make commercial tools impractical,
or because Moodle integration is a hard requirement."

For organizations already running Moodle, H5P is often
the obvious first choice for interactive content — not
because it is easier or more flexible than commercial
tools, but because the integration, cost, and open-source
alignment make it the right fit for that environment.


---

## Choosing Among All Four Tools

| Situation | Recommended Tool |
|---|---|
| Complex branching scenarios | Storyline |
| Mobile-first delivery | Rise |
| Fast development turnaround | Rise |
| Pixel-precise custom design | Storyline |
| Software simulation | Storyline |
| Frequent content updates | Rise |
| High-stakes graded assessment | Storyline |
| Microlearning / reference | Rise |
| Multi-author collaboration | Rise or Lectora |
| Formally audited 508/WCAG compliance | Lectora |
| Regulated industry (healthcare, pharma, gov) | Lectora |
| Complex conditional logic without code | Lectora |
| Enterprise SCORM reliability | Lectora |
| Mixed content + complex interactions | Rise + Storyline blocks |
| Low-bandwidth environments | Storyline (optimized) or Rise (HTML5 local launch) |

---

## A Note on Tool Selection

The best authoring tool is the one 
that fits the project requirements, 
the team's skills, and the organization's 
infrastructure — not the one with the 
most features.

When helping with design decisions, 
Claude will default to the tool 
specified by the designer. If no tool 
is specified and the design involves 
complex branching or interactions, 
Claude will ask which tool is in use 
before making specific recommendations.

---

## Prompting Claude With Tool Context

> *"I'm building a compliance course 
> for a pharmaceutical client in Lectora. 
> They need to pass a formal Section 508 
> audit. What accessibility steps should 
> I build into my development workflow?"*

> *"I need to decide between Storyline 
> and Rise for a new manager onboarding 
> program. Mobile access is important, 
> but so is a branching scenario. 
> What would you recommend?"*

> *"Can I build a three-decision-point 
> branching scenario natively in Rise, 
> or do I need a Storyline block?"*

> *"I'm building in Storyline 360. 
> My client wants 360° video walkthroughs 
> of their facility. Is that feasible?"*

---

## References & Further Reading
- Articulate Storyline 360 user guide — 
  articulate.com/support/storyline-360
- Articulate Rise 360 user guide — 
  articulate.com/support/rise-360
- Articulate Review 360 user guide — 
  articulate.com/support/review-360
- Lectora user guide — 
  trivantis.com/lectora/support
- Lectora ReviewLink documentation — 
  trivantis.com/reviewlink
- Articulate community forums — 
  community.articulate.com
- E-Learning Heroes (Articulate community 
  blog and resources) — 
  elearningheroes.com
- Lectora accessibility guide — 
  trivantis.com/accessibility
- WebAIM authoring tool accessibility — 
  webaim.org
- Connie Malamed on authoring tool 
  selection — theelearningcoach.com
