# Instructional Design Skill: Industry-Specific Design Considerations

## Overview
Instructional designers work across industries—and the gap between
generic training design and industry-credible training design is
significant. Every sector has its own terminology, regulatory
environment, professional culture, and relationship to risk that
shapes what good learning design looks like in that context.

LLMs are particularly prone to producing content that sounds
industry-fluent but is subtly or significantly wrong—using
outdated terminology, misrepresenting regulatory requirements,
conflating distinct professional roles, or applying corporate
L&D norms to contexts where they don't belong.

This skill helps Claude support instructional designers in
recognizing the specific design requirements of major industry
verticals, avoiding common LLM failure modes in each, and
knowing when to require expert review before proceeding.

---

## Core Principle: Plausible Is Not Accurate

In industry-specific content, LLMs produce confident, fluent
text that pattern-matches to the surface features of the domain.
This content can pass a generalist review and still be wrong
in ways that matter—clinically, legally, regulatorily, or
professionally.

The designer's responsibility is to know enough about the
industry context to recognize when AI-generated content
requires expert verification—and to build that verification
into the workflow rather than treating it as optional.

---

## Healthcare and Clinical Settings

### What Makes This Vertical Distinct
Healthcare is the highest-stakes vertical for content accuracy.
Terminology errors, scope-of-practice misrepresentations, and
protocol inaccuracies are not just professionally embarrassing—
they can contribute to patient harm. Clinical learning design
must reflect the actual regulatory, ethical, and operational
environment of healthcare delivery.

### LLM Failure Modes
- **Role conflation:** Conflating clinical roles with distinct
  scope of practice—nurse vs. nurse practitioner vs. physician
  assistant vs. attending physician vs. resident. Each has
  specific, legally defined boundaries on what they can do.
- **Outdated terminology:** Clinical language evolves. Terms
  that were standard five years ago may be deprecated, replaced,
  or carry different connotations in current practice.
- **Protocol generalization:** Clinical protocols vary by
  institution, specialty, and jurisdiction. A medication
  administration scenario that reflects one institution's
  protocol may contradict another's.
- **Regulatory simplification:** HIPAA, Joint Commission
  standards, CMS requirements, state licensing boards, and
  specialty-specific accreditation bodies all impose
  overlapping and sometimes conflicting requirements.
  LLMs flatten these into generic "healthcare compliance."
- **Missing the clinical environment:** Scenarios that don't
  reflect the actual pace, pressure, communication patterns,
  and decision-making conditions of clinical work feel
  false to clinicians and fail to prepare them for reality.

### Design Guidance
- Require clinical SME review for all content—not just
  at final review, but from storyboard stage
- Specify the exact clinical role, setting, specialty,
  and institution type in every scenario brief
- Reference the specific regulatory bodies and standards
  that govern the scenario's context
- Use the terminology the clinical audience actually uses—
  not the terminology a generalist would recognize
- Design for the real decision-making conditions:
  time pressure, incomplete information, team dynamics,
  and handoff situations

### Key Regulatory Bodies and Standards
Joint Commission, CMS, HIPAA, state licensing boards,
specialty-specific boards (ABIM, ANCC, etc.), Magnet
Recognition Program, OSHA bloodborne pathogens standard

---

## Financial Services

### What Makes This Vertical Distinct
Financial services is heavily regulated across multiple
dimensions—by product type, institution type, client type,
and jurisdiction. The regulatory landscape is also in
constant flux. Content that was accurate at the time of
design may become non-compliant as regulations change.
The fiduciary dimension of client relationships adds an
ethical layer that generic business training does not address.

### LLM Failure Modes
- **Regulatory conflation:** Blurring distinctions between
  banking (OCC, FDIC, Federal Reserve), securities (FINRA,
  SEC), insurance (state regulators), investment advisory
  (SEC, state), and fintech (evolving, jurisdiction-specific).
  Each has distinct requirements.
- **Jurisdiction errors:** UK (FCA, PRA), EU (ESMA, MiFID II),
  US (SEC, FINRA, CFPB), Australian (ASIC), Canadian (OSFI)
  regulatory environments are not interchangeable.
- **Role and license specificity:** Series 7, Series 65,
  Series 66, CFP, CFA, CPA—each license defines what a
  person can do, say, and recommend. Scenarios that ignore
  these distinctions produce incorrect guidance.
- **Suitability vs. fiduciary standard:** The distinction
  between suitability (broker-dealer standard) and fiduciary
  duty (investment adviser standard) is legally significant
  and frequently misrepresented in generic content.
- **Stale regulatory references:** Financial regulations
  change. Content that references specific rules or
  thresholds without version control becomes non-compliant.

### Design Guidance
- Specify the regulatory jurisdiction, institution type,
  and product category in every scenario brief
- Require compliance officer review for all regulatory
  content—legal sign-off is often required before deployment
- Build version control and review triggers into content
  maintenance plans—financial training has a short shelf life
- Scenario language around client recommendations must
  reflect the specific standard (suitability vs. fiduciary)
  that governs the role in the scenario
- Avoid specific figures, rates, or thresholds that will
  change—or flag them for regular review

### Key Regulatory Bodies and Standards
SEC, FINRA, OCC, FDIC, CFPB, Federal Reserve (US);
FCA, PRA (UK); ESMA, EBA (EU); ASIC (Australia);
OSFI (Canada); Basel III/IV, MiFID II, Dodd-Frank,
BSA/AML requirements

---

## Legal and Legal Operations

### What Makes This Vertical Distinct
Legal content is jurisdiction-specific, role-specific, and
often ethically governed in ways that general professional
training is not. The distinction between legal information
and legal advice has professional conduct implications.
Paralegal and legal operations roles have tightly defined
scope that varies by jurisdiction.

### LLM Failure Modes
- **Jurisdiction conflation:** US legal content does not
  translate to UK, Canadian, Australian, or EU contexts.
  Even within the US, state law varies significantly.
- **Role scope errors:** What a paralegal can do is
  defined by jurisdiction and bar association rules.
  Unauthorized practice of law (UPL) is a serious
  professional risk that generic content may inadvertently
  encourage.
- **False certainty:** LLMs present legal standards with
  more certainty than the law typically offers. Legal
  analysis involves judgment, ambiguity, and competing
  interpretations—scenarios should reflect this.
- **Ethics rule specificity:** Professional responsibility
  rules (Model Rules of Professional Conduct in the US)
  vary by state adoption and amendment. Content that
  references ethics rules must reflect the specific
  jurisdiction's version.
- **Privilege and confidentiality nuance:** Attorney-client
  privilege, work product doctrine, and confidentiality
  obligations are frequently oversimplified in generic content.

### Design Guidance
- Specify jurisdiction at the outset of every legal
  scenario brief
- Distinguish clearly between attorney and non-attorney
  roles and their distinct obligations
- Have all legal content reviewed by a licensed attorney
  in the relevant jurisdiction
- Design scenarios that reflect genuine legal ambiguity—
  not clean fact patterns with obvious answers
- Include appropriate disclaimers where content provides
  legal information rather than legal advice

---

## Government and Public Sector

### What Makes This Vertical Distinct
Government and public sector organizations operate under
constraints—legal, political, procedural, and cultural—
that have no direct equivalent in private sector organizations.
Accountability to the public, the role of elected officials,
procurement rules, civil service protections, and union
agreements all shape what decisions look like and how they
are made.

### LLM Failure Modes
- **Private sector norm transfer:** Applying corporate L&D
  norms (agility, customer-centricity, performance culture)
  to government contexts where accountability, due process,
  and public service values are the governing framework
- **Hierarchy and accountability misrepresentation:**
  Government decision-making involves legislative oversight,
  Inspector General functions, audit requirements, and
  political accountability that don't exist in corporate contexts
- **Procurement and contracting ignorance:** Government
  procurement is governed by specific regulations (FAR in
  the US federal context) that create constraints with no
  private sector equivalent
- **Union and civil service context:** Many government
  employees are covered by collective bargaining agreements
  and civil service protections that significantly affect
  how performance management, discipline, and role
  assignments work
- **Jurisdiction layering:** Federal, state/provincial,
  and municipal government operate under different legal
  frameworks and have different relationships to policy,
  regulation, and public accountability

### Design Guidance
- Specify the level of government (federal, state, municipal),
  the agency type, and the relevant legal framework
- Reflect the actual decision-making constraints of the
  context—including political and procedural constraints
  that have no corporate equivalent
- Design scenarios that reflect public accountability
  as a genuine value and constraint, not just a compliance
  requirement
- Require SME review from people with actual government
  service experience—not just subject matter experts
  from the private sector

---

## Manufacturing and Industrial Safety

### What Makes This Vertical Distinct
Manufacturing and industrial training operates under
specific regulatory safety requirements that are non-
negotiable and highly specific to industry segment,
hazard type, and jurisdiction. Generic safety content
that does not reflect actual standards is not just
unhelpful—it may create false confidence and legal risk.

### LLM Failure Modes
- **Standard generalization:** OSHA standards are
  specific—the general industry standards (29 CFR 1910)
  differ from construction (29 CFR 1926) and maritime.
  State plan states may have additional requirements.
- **Hazard-specific inaccuracy:** Chemical safety,
  electrical safety, confined space, lockout/tagout,
  and fall protection each have specific regulatory
  requirements that generic content frequently misrepresents
- **International standard confusion:** ISO, ANSI, NFPA,
  IEC, and regional standards (EU CE marking, etc.)
  are frequently conflated or misapplied
- **Missing the physical environment:** Scenarios that
  don't reflect the actual physical conditions, equipment,
  and production pressures of industrial work feel false
  to experienced workers and fail to prepare them for reality

### Design Guidance
- Identify the specific OSHA standard(s) and any
  applicable state plan requirements before designing
- Require review by a qualified safety professional
  (CSP, CSHM, or equivalent) for all safety content
- Reflect the actual physical environment and production
  pressures of the specific industry segment
- Design for the real decision-making conditions—
  time pressure, physical constraints, team communication
  under noise and PPE—not an idealized safety scenario

### Key Regulatory Bodies and Standards
OSHA (US), HSE (UK), Safe Work Australia, ISO 45001,
NFPA, ANSI, industry-specific standards (MSHA for
mining, FAA for aviation, etc.)

---

## Education: K-12 and Higher Education

### What Makes This Vertical Distinct
Educational institutions have their own professional
culture, regulatory environment, and relationship to
learning that is distinct from corporate L&D. Terminology,
role structures, accountability frameworks, and the
purpose of learning itself differ significantly from
workplace training contexts.

### LLM Failure Modes
- **Corporate norm transfer:** Applying corporate L&D
  frameworks to educational contexts where pedagogy,
  curriculum standards, and student development—not
  performance outcomes—are the governing framework
- **Regulatory specificity:** FERPA, IDEA, Section 504,
  Title IX, and state-specific education codes create
  a regulatory environment with no corporate equivalent
- **Role and title confusion:** Principal, assistant
  principal, department chair, dean, provost, instructional
  coach—titles and roles vary significantly across
  institution types and district/institution structures
- **Student population sensitivity:** Content involving
  minor students requires specific protections, consent
  frameworks, and trauma-informed design considerations
  that adult-focused corporate training does not

### Design Guidance
- Specify institution type (K-12 district, charter,
  independent school, community college, university),
  grade level or student population, and applicable
  regulatory framework
- Use educational terminology accurately—curriculum,
  pedagogy, assessment, IEP, 504 plan, PLC—not
  corporate L&D equivalents
- Require review by current educators for content
  aimed at teacher or administrator audiences
- Apply trauma-informed and age-appropriate design
  principles for any content that involves students

---

## Nonprofit and Social Services

### What Makes This Vertical Distinct
Nonprofit and social services organizations combine
mission-driven culture with resource constraints,
volunteer/staff complexity, and often trauma-adjacent
work. Training design that ignores these dimensions
produces content that feels tone-deaf to practitioners
who work in this sector.

### LLM Failure Modes
- **Resource assumption:** Assuming technology, budget,
  and time resources that nonprofit organizations
  typically don't have
- **Corporate culture transfer:** Applying corporate
  professionalization norms to sector cultures that
  value mission, relationship, and community differently
- **Volunteer/staff dynamics:** The relationship between
  paid staff and volunteers is complex and distinct—
  motivations, accountability, and training approaches differ
- **Trauma-informed design gaps:** Many social service
  workers and their clients have trauma histories that
  require specific design considerations that generic
  content does not address
- **Funding and compliance complexity:** Grant requirements,
  government contracts, and reporting obligations create
  compliance contexts that are distinct from corporate
  regulatory compliance

### Design Guidance
- Reflect realistic resource constraints in scenario
  design—not idealized conditions
- Apply trauma-informed design principles throughout,
  not just in content about trauma
- Design for mixed volunteer/staff audiences with
  awareness of their different relationships to
  the work and the organization
- Require review by practitioners with current
  direct-service experience

---

## Prompting Guidance for Industry-Specific Content

When using AI to develop content for any of these verticals,
provide the following context explicitly:

```
Industry: [specific sector and sub-sector]
Regulatory jurisdiction: [country/state/region]
Governing standards: [specific regulatory bodies and standards]
Audience role: [specific job title and scope of practice]
Institution type: [specific organization type]
Known terminology: [field-specific terms to use]
Review required: [who must review this content before use]
```

After generation, explicitly ask:
- What assumptions did you make about the regulatory context?
- What terminology choices did you make and why?
- What elements of this content should be verified by
  a domain expert before use?

Treat all AI-generated industry-specific content as a
first draft that requires expert review—not finished content.

---

## The Expert Review Non-Negotiable

For all industry-specific content, expert review is not
optional. The question is not whether to include it—it
is who should provide it and at what stage.

**Review should happen at storyboard stage, not final review.**
Finding a content error after the course is built is
significantly more expensive than finding it before.

**The reviewer must have current, active experience.**
A clinician who left practice five years ago, a financial
advisor who hasn't held a license in three years, or a
lawyer in a different jurisdiction may not catch current
errors. Currency matters.

**The reviewer should be a practitioner, not just a subject expert.**
The most valuable reviewer for workplace training content
is someone who currently does the job the training is
designed for—not just someone who knows the subject matter
academically.

---

## Industry-Specific Design: Patterns Worth Examining

- **Confident ignorance**—AI-generated content that sounds
  fluent in industry terminology but misrepresents the
  regulatory, clinical, or professional reality
- **Generic compliance**—treating all regulatory compliance
  content as structurally equivalent regardless of the
  specific standards, bodies, and consequences involved
- **Role flattening**—conflating distinct professional roles
  with specific, legally defined scope of practice
- **Jurisdiction blindness**—producing content that
  references standards, laws, or practices without
  specifying the jurisdiction they apply to
- **Skipping expert review**—treating industry-specific
  content as complete without review from a current
  practitioner in the specific role, institution type,
  and jurisdiction the training addresses

---

## References & Further Reading

### Healthcare
- Joint Commission standards — jointcommission.org
- CMS conditions of participation — cms.gov
- HIPAA guidance — hhs.gov/hipaa
- Institute for Healthcare Improvement — ihi.org

### Financial Services
- FINRA rules and guidance — finra.org
- SEC regulations — sec.gov
- FCA guidance — fca.org.uk
- CFPB resources — consumerfinance.gov

### Legal
- ABA Model Rules of Professional Conduct — americanbar.org
- State bar association ethics resources

### Government
- OPM training and development guidance — opm.gov
- FAR (Federal Acquisition Regulation) — acquisition.gov

### Manufacturing / Safety
- OSHA standards — osha.gov
- NIOSH resources — cdc.gov/niosh
- NSC (National Safety Council) — nsc.org

### Education
- FERPA guidance — ed.gov/ferpa
- IDEA resources — sites.ed.gov/idea
- Regional education agencies and state education departments

### Cross-Vertical
- *The Cult of Compliance* framing — Cathy Moore on
  compliance training that actually changes behavior
  blog.cathy-moore.com
- Patti Shank on evidence-based content design — pattishank.com
