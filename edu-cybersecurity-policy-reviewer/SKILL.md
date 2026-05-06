---
name: edu-cybersecurity-policy-reviewer
description: >
  Reviews, critiques, and drafts higher education information security (infosec) policies using the
  "Policy by Design" framework developed by Michael Corn (former CISO at UCSD and other R1 institutions).
  Use this skill whenever the user shares a cybersecurity policy, policy draft, policy language, or policy
  section for review — or asks for help writing, structuring, or improving an infosec policy in a higher
  education context. Also trigger when the user asks about: policy governance structures, CISO authority,
  Information Assurance Management Plans (IAMP), security practice registries, decision rights frameworks,
  infosec policy goals, how to balance pace vs. consensus in campus security governance, or how to make
  policy sustainable over time. Even if the user just asks "is this policy good?", "what's missing from
  our policy?", or "why does our policy keep getting updated?" — use this skill.
---

# EDU Cybersecurity Policy Reviewer

A skill for reviewing, critiquing, and drafting higher education information security policies using
the two-part framework from Michael Corn:

- **"Policy by Scar Tissue"** — Philosophical foundation: the tensions inherent in any infosec policy
  and why most policies become brittle over time
- **"Policy by Design"** — Prescriptive architecture: how to build policy that is stable, agile, and
  governance-oriented

Grounded in higher ed institutional realities: shared governance, academic freedom, research
environments, and the tension between risk pace and consensus culture.

---

## Part 1: Understanding Policy Failure — The Tensions Framework

Before reviewing or drafting, internalize *why* infosec policies fail. Corn identifies two master
tensions that every policy must balance:

### Master Tension 1: Stability vs. Change

Good policy should be immutable — but the threat landscape, technologies, and institutional context
change constantly. The resolution: **separate what is stable from what is dynamic**.

- **Stable (belongs in policy):** Principle, authority, governance, responsibility/decision rights
- **Dynamic (belongs in IAMP/security practice registry):** Specific controls, frameworks, tools,
  risk responses

A policy that conflates these two layers will require constant revision and become unreliable.

**The Scar Tissue Failure Mode:** When an incident occurs, leadership hears "if only people did X
this wouldn't have happened" — and the predictable response is to insert that specific control
directly into the policy. Repeat this over five years and you have a policy that is:
- Littered with obsolete or overly specific controls
- A record of past incidents rather than a governance architecture
- Impossible to maintain or reason about holistically

This is "policy by scar tissue." It is the most common way real-world infosec policies become
ineffective. The antidote is routing incident-driven control needs into the IAMP or security
practice registry — not into the policy document itself.

### Master Tension 2: Culture vs. Strategy

Can policy shape organizational culture, or only reflect it? Corn's answer: policy cannot *mandate*
culture, but it can codify *transparent processes* that build the trust necessary for a security
culture to develop.

Key implications:
- **Don't put compliance/sanctions language in policy.** Faculty and researcher sanctions are HR's
  domain. Attempting to enforce policy compliance through the infosec policy itself creates conflict
  with employment contracts and union agreements — and the disruption of sanctioning a faculty
  member often exceeds the harm of non-compliance.
- **Codify process, not outcomes.** Policy can require transparent engagement processes; it cannot
  require people to have a security mindset.
- **Trust requires transparency.** Policy as social contract must be honest about scope, authority,
  and the limits of what it can compel.

### The Political Artifact Reality

Policy is a political artifact as much as a technical one. It codifies "management will" and
acquires political leverage. The first version of a policy establishes the *right* to have a policy
at all — even a weak policy has value as a foundation for a stronger one later.

**Reviewer implication:** Distinguish between a policy that is *accidentally weak* (design failure)
vs. *intentionally lightweight* (political strategy for incremental adoption). Both are worth
flagging, but the remediation differs.

---

## Part 2: Policy Architecture — Policy by Design

### The Core Thesis

> "Effective information security policy avoids codifying elements subject to change — rather, it
> defines and shapes the **governance** of those dynamic elements."

Policy must move from **technical control → structural agility**. It should not enumerate specific
controls (antivirus, password rules) that become obsolete. Instead, it should define *who decides*,
*how they decide*, and *with what authority*.

### The Four-Element Policy Taxonomy

Every sentence in a well-designed infosec policy should fall into one of these four categories.
Any sentence that doesn't is a candidate for removal or demotion to the IAMP layer:

| Element | What It Means |
|---------|--------------|
| **Principle** | The values and goals that guide the institution's approach to infosec |
| **Authority** | Who is designated as the decision maker and what institutional standing they hold |
| **Governance** | How decisions are made, escalated, and reviewed; the structure within which authority operates |
| **Responsibility** | Decision rights — who is accountable for what, and at what level of autonomy |

### The Three-Word Synthesis: Designate, Situate, Empower

| Element | What It Means in Policy |
|---------|------------------------|
| **Designate** | Name a decision maker (e.g., CISO) with explicit authority |
| **Situate** | Place that decision maker within a governance structure with clear escalation paths |
| **Empower** | Grant *ex ante* authority over a defined taxonomy of decisions; allow the CISO to manage a security practice registry without case-by-case approval |

### The Five Goals of Infosec Policy

Evaluate any policy against all five:

| # | Goal | What to Look For |
|---|------|-----------------|
| 1 | **Advance institutional mission** | Does it frame infosec as an *enabler* of teaching, research, and public service? Does it protect the *privacy of thought* underlying academic freedom? |
| 2 | **Effectively reduce risk** | Does it create *programmatic structure* (sustained, coordinated, resourced) vs. ad hoc activities? Policy ≠ program, but policy should compel a program. |
| 3 | **Establish principles of culture** | Does it use language accessible to non-IT stakeholders? Does it build shared vocabulary around risk and responsibility? |
| 4 | **Be self-maturing and self-auditing** | Does it create feedback loops? Does execution produce evidence of execution? Does it build in governance mechanisms that improve over time? |
| 5 | **Be implementable** | Is it "means-tested"? Are roles, resources, and authority realistic for the institution? Does it avoid symbolic policy without operational backing? |

---

## How to Run a Policy Review

### Step 1 — Read the Policy
Identify the type of content being reviewed:
- Full institutional infosec policy
- Single policy section or standard
- Policy draft seeking structural feedback
- Policy language for a specific context (research, CMMC, enterprise, etc.)

### Step 2 — Apply the Five-Goal Scorecard
For each goal, note:
- **Present**: Clear evidence it's addressed
- **Weak**: Implied but not explicit
- **Absent**: No coverage

### Step 3 — Apply the Governance Test
Ask the following diagnostic questions:

**Decision Rights**
- Is a specific decision maker designated (e.g., CISO as institutional officer)?
- Are decision-making rights *ex ante* (proactive authority) vs. *ex post* (reactive approval) distinguished?
- Is there a taxonomy of decisions the CISO can make without governance approval?
- Is there a taxonomy of decisions requiring governance or executive involvement?

**Governance Role Clarity**
- Is governance framed as *contextual intelligence and political cover* (good) vs. *approval queue* (problematic)?
- Does governance have a role in resource advocacy — not just policy approval?

**Pace and Agility**
- Does the policy account for the speed mismatch between threat landscape and consensus governance?
- Can the designated decision maker act within weeks, not months?

**Authority and Accountability**
- Is the CISO's authority commensurate with scope of responsibility?
- Are there mechanisms to hold the decision maker accountable without hobbling their authority?

### Step 4 — Apply the Sustainability Test

These questions address whether the policy is *durable*, not just well-designed on day one:

**Scar Tissue Resistance**
- Is there a clear pathway for incident-driven control changes to flow into the IAMP/practice
  registry *without* touching the policy document itself?
- Does the policy distinguish between what is immutable (four-element taxonomy) vs. dynamic
  (specific controls)?
- Does the policy contain language that looks like it was inserted in response to a specific past
  incident (overly specific, operationally narrow, inconsistent abstraction level with surrounding
  policy)? If so, flag it as likely scar tissue.

**Stability vs. Change Balance**
- Does the policy avoid enumerating specific technologies, vendor names, or control mechanisms
  subject to change?
- Would a change in the threat landscape or available tools require a policy revision? If yes,
  the policy is over-specified.

**Culture vs. Strategy Honesty**
- Does the policy attempt to mandate cultural norms that cannot realistically be enforced?
- Does it contain compliance/sanctions language that belongs in HR policy or institutional
  procedures instead?
- Does it rely on process transparency (notice, appeal, governance engagement) rather than
  attempting to grant or restrict substantive individual rights?

**Regulated Environment Scope Discipline**
- Does the policy attempt to subsume CMMC, HIPAA, PCI, or other heavily regulated environment
  requirements? If so, flag as scope overreach — those environments should be governed by
  their own regulatory frameworks, not mapped into the institutional infosec policy.

### Step 5 — Check for Anti-Patterns

| Anti-Pattern | Signal | Better Approach |
|---|---|---|
| **Policy by scar tissue** | Controls that are suspiciously specific, operationally narrow, or inconsistent in abstraction level with surrounding policy; history of frequent point updates | Route incident-driven needs to IAMP/security practice registry; policy should require that governance *respond* to incidents, not specify how |
| **Control enumeration** | Lists specific technologies (e.g., "all systems must use antivirus X") | Reference a *security practice registry* the CISO maintains |
| **Written for cyber pros** | Heavy use of technical terms without definitions | Plain language accessible to faculty, staff, non-IT leaders |
| **No resource mandate** | Policy implies practices but doesn't compel funding/staffing | Governance committee chartered to advocate for resources |
| **Governance as checkpoint** | Every security decision routes through committee | Distinguish approval-free vs. escalation-required decisions |
| **Mission disconnect** | Policy reads as purely technical | Frame infosec as enabling academic freedom + research integrity |
| **No IAMP requirement** | No living program documentation required | Mandate an Information Assurance Management Plan |
| **One-size mission** | Treats enterprise IT = research IT = regulated IT | Explicitly address multi-mission campus complexity |
| **Reactive authority only** | CISO acts only after incidents | Delegate *ex ante* authority for defined control classes |
| **Sanctions in policy** | Disciplinary consequences for non-compliance defined in the infosec policy | Defer to HR and institutional procedures; acknowledge sanctions exist without defining them |
| **Regulated environment absorption** | Policy incorporates CMMC, HIPAA, PCI requirements | Explicitly carve out regulated environments: their governing regulations *are* their policy |
| **Intentionally toothless** | Policy is lightweight by design to secure adoption | Acceptable as v1 strategy only if there is governance commitment to revisit; document the intent |
| **Privacy/surveillance silence** | Policy deploys EDR, behavioral analytics, or similar tools without acknowledging privacy implications | Codify process rights (notice, appeal timeframes) for defined classes of information; distinguish incident-response access from investigative access |

### Step 6 — Produce the Review Output

```
## Policy Review: [Policy Name / Section]

### Overall Assessment
[1-3 sentence verdict: governance-oriented vs. control-oriented, agile vs. rigid, sustainable vs. brittle]

### Five-Goal Scorecard
[Table or narrative by each of the five goals]

### Governance Diagnostic
[Decision rights / authority / pace analysis]

### Sustainability Diagnostic
[Scar tissue indicators / stability-change balance / culture-strategy honesty / scope discipline]

### Anti-Patterns Found
[List what's present with specific policy language citations]

### Strengths
[What the policy does well, with specific language citations]

### Priority Recommendations
[Ranked list: High / Medium / Low — with specific suggested language where possible]

### Suggested Rewrite (optional)
[If requested or clearly helpful, offer revised language for flagged sections]
```

---

## How to Draft or Improve a Policy

When drafting from scratch or significantly revising:

### Architecture Principles

**What policy SHOULD define (the four elements only):**
- **Principle:** Infosec as enabler of mission; academic freedom as a value infosec protects
- **Authority:** Designated decision maker (CISO) and their institutional standing
- **Governance:** Structure and role (intelligence, advocacy, NOT approval queue); escalation paths
- **Responsibility:** Decision taxonomy (CISO-autonomous vs. governance-required); mandate for IAMP;
  security practice registry concept; multi-mission acknowledgment

**What policy SHOULD NOT define:**
- Specific technical controls (passwords, MFA methods, specific tools)
- Vendor names or specific frameworks by name — reference them in the IAMP, not the policy
- Operational procedures (those belong in standards/procedures layer)
- Compliance/sanctions (defer to HR and institutional procedures)
- Regulated-environment control mappings (CMMC, HIPAA, PCI govern themselves)

### Regulated Environment Carve-Out Language (Template)

> "The University operates a variety of environments subject to specific federal and industry
> regulations. In such environments, the applicable regulatory framework constitutes the governing
> information security policy for that environment. The University's institutional information
> security policy applies to the extent it is not superseded by those requirements."

### Privacy and Surveillance: Codify Process Rights, Not Substantive Rights

Legal counsel will resist language granting individuals specific privacy rights against
institutional access. The practical approach:

- Define **classes of information** that require elevated process before access (e.g., faculty
  communications, research data)
- Codify **process rights** for those classes: notice requirement, appeal timeframe before access
- Distinguish between **incident-response access** (may require immediacy) vs. **investigative
  access** (process rights apply)
- Acknowledge that surveillance-adjacent tools (EDR, behavioral analytics) exist and that their
  use is governed by the process rights framework — not that they won't be used

### IAMP Requirements to Include

An IAMP (Information Assurance Management Plan) should be mandated in policy with these elements:
- Designated framework(s) the institution aligns to
- Enumeration of active security functions/capabilities
- Roles and responsibilities
- Senior leadership sign-off mechanism
- Review/revision cadence
- Serves as vehicle for resource conversations with executive leadership
- **Is the designated home for incident-driven control additions (not the policy itself)**

### Plain Language Test
Before finalizing any section, ask: *Can a faculty member, HR director, or procurement officer
understand this without a CISO to explain it?* If no, revise.

### Exegesis Reminder
Good practice: recommend the policy team produce a companion *exegesis document* — not an FAQ,
not another policy, but plain-language explanation of author intent and rationale behind each
major provision. This is especially important for process-rights language around privacy and
surveillance, where intent is easily misread.

---

## Higher Education Context Notes

Keep these institutional realities in mind during all reviews and drafts:

- **Shared governance is real**: Faculty senates and governance committees can delay urgent
  decisions by months or years. Policy must anticipate this tension and design around it.
- **Under-resourcing is endemic**: EDU security offices are chronically understaffed. Policy
  that compels structure without mandating resource advocacy is likely to become symbolic.
- **Research environments are distinct**: CMMC, NSF requirements (NSPM-33, Research
  Infrastructure Guide §5.3), CUI handling, and highly regulated research create sub-environments
  with their own risk posture. Do not map these into the institutional policy.
- **Academic freedom is load-bearing**: Pervasive logging, behavioral analytics, and monitoring
  tools have genuine implications for academic freedom. Policy should name this tension explicitly
  and codify process protections rather than avoiding it.
- **CISO authority varies wildly**: Some institutions have CISOs as senior officers with real
  authority; others have them buried in IT org charts. Policy should aim to elevate, not entrench.
- **"Blank stare" problem**: Organizational boundaries (not threat vectors) determine response
  pathways. Policy must name cross-functional coordination explicitly.
- **Faculty sanctions are a third rail**: The business disruption of sanctioning a faculty member
  (courses, time-sensitive research, final exams at risk) often exceeds the harm of non-compliance.
  Policy should not attempt to resolve this tension — acknowledge it and defer to institutional
  procedures.
- **Governance rarely controls budget**: Infosec governance committees typically lack budgetary
  authority. Real resource decisions happen in smaller meetings with CFOs and Provosts. Policy
  should require governance to play an *advocacy* role in resource conversations, not just a
  policy-approval role.

---

## Reference Materials

See `references/corn-framework-quotes.md` for direct source language from Michael Corn's
"Policy by Design" (Part 2) that can be used to ground recommendations in the source framework.

See `references/iamp-elements.md` for a structured breakdown of IAMP components derived from
NSF Research Infrastructure Guide §5.3.

**Source articles (both inform the full framework):**
- "Policy by Scar Tissue" (tensions and failure modes):
  https://michaelcorn.substack.com/p/policy-by-scar-tissue
- "Policy by Design" (prescriptive architecture):
  https://mediaspace.ucsd.edu/media/What%27s+wrong+with+IS-3F+Good+policy+and+security+in+2022+and+beyond/1_5xsa6oo0
