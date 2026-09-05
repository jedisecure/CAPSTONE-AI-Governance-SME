# A Practical AI Security Baseline for Small and Medium-Sized Businesses Adopting Generative AI

**IT595 Information Technology Capstone — Purdue Global University**

- **Author:** Maria Singh
- **Faculty Advisor:** Dr Ash Luitel
- **Date:** September 1, 2026

---








## Introduction

Generative artificial intelligence (AI) has moved from experimentation
to everyday business operations. Employees can use commercially
available assistants to summarize documents, draft communications,
analyze data, generate code, and support customer interactions. These
capabilities can improve productivity for small and medium-sized
businesses (SMEs), but the same accessibility can create unmanaged
exposure when employees enter sensitive information into unapproved
services, rely on inaccurate output, or connect AI systems to
organizational data and applications without appropriate restrictions.
The proposed project addresses this adoption gap by translating
established cybersecurity and AI risk guidance into a practical
minimum-security baseline that an SME can understand and apply.

The project is guided by the following question: What minimum
cybersecurity and governance controls should an SME implement before
employees use generative AI for business work? The work will align the
National Institute of Standards and Technology (NIST) AI Risk Management
Framework functions of Govern, Map, Measure, and Manage with the NIST
Cybersecurity Framework (CSF) 2.0, ISO/IEC 42001, current OWASP threat
guidance, and Singapore\'s internationally aligned AI governance
resources. NIST emphasizes that AI risk management should be adaptable
to organizational resources and context, which is especially relevant to
SMEs with limited security personnel and budgets (Tabassi, 2023). The
result will be an original, SME-oriented assessment tool and prioritized
implementation roadmap rather than a restatement of any one framework.

## Background of Organization

This proposal is designed for a hypothetical composite organization
rather than a named employer. The representative SME is a professional
services company with 50 to 250 employees, a cloud-first environment, a
small information technology team, and no dedicated AI governance
function. Employees already have access to public or enterprise
generative AI assistants, and managers are exploring a customer chatbot
and a limited workflow agent. This context reflects organizations that
need practical controls but cannot maintain a large governance office, a
continuous red-team program, or a specialized AI security platform.

The organization is assumed to have foundational cybersecurity practices
such as identity management, endpoint protection, backups, and vendor
contracting, although maturity varies. The NIST CSF 2.0 Small Business
Quick-Start Guide recognizes that smaller organizations may have modest
cybersecurity plans and need a practical entry point for prioritizing
risk management activities (Eliot, 2024). The proposed baseline will
therefore build on existing business processes instead of requiring a
separate, enterprise-scale control environment.

## Problem

The central problem is not simply the presence of generative AI; it is
the absence of a repeatable decision process for determining which uses
are acceptable, what data may be shared, what safeguards are required,
and who remains accountable for outcomes. An outright ban may drive
activity into unmonitored channels, while unrestricted use can expose
confidential, personal, regulated, or proprietary information.
Additional risks include prompt injection, sensitive-information
disclosure, insecure output handling, excessive system permissions,
unreliable content, third-party dependency, weak logging, and inadequate
incident response. The OWASP GenAI LLM Top 10 2026 consolidates current
application-security risks and mitigations for systems powered by large
language models, providing a threat lens that complements governance
frameworks (Open Worldwide Application Security Project \[OWASP\],
2026).

SMEs face an implementation challenge because authoritative frameworks
are intentionally broad, while technical threat lists may assume
expertise or resources that smaller organizations lack. A company may
know it should manage AI risk but still lack a concise assessment, a
minimum control set, evidence requirements, and an action sequence.
Government guidance also emphasizes protecting confidentiality,
integrity, and availability of data used to train and operate AI
systems, reinforcing the need to address information throughout its
lifecycle (Cybersecurity and Infrastructure Security Agency \[CISA\],
2025). Without these elements, leadership cannot consistently approve
use cases, compare vendors, establish human-review requirements, or
determine whether residual risk is acceptable.

## Purpose of Project

This capstone project designs and evaluates a practical AI security
baseline for SMEs adopting generative AI assistants, chatbots, and
early-stage agents. The project will synthesize relevant controls from
U.S., international, industry, and Singapore sources, translate them
into plain-language assessment questions, and prioritize safeguards by
risk and implementation effort. The baseline will focus on governance
and accountability, approved use cases, data handling, identity and
access management, vendor due diligence, prompt and content security,
human oversight, output validation, monitoring, and incident response.

The project resolves the identified problem by giving decision makers a
lightweight method to move from vague concern to documented action. It
will not attempt to certify legal compliance, test a particular
commercial model, or replace a full penetration test. Instead, it
establishes minimum conditions for use, identifies gaps that require
treatment, and creates a roadmap an SME can execute in stages. The NIST
Generative AI Profile supports this approach by extending the AI RMF
with actions for generative-AI-specific risks while maintaining a
voluntary, risk-based structure (Autio et al., 2024).

## Overview of the Proposed Project

The project will use an applied design-and-evaluation method. First, the
project will review current authoritative guidance and map it into a
consolidated control taxonomy. Second, it will convert the taxonomy into
an assessment instrument with evidence prompts, maturity ratings,
decision gates, and remediation priorities. Third, will test the draft
against three representative use cases: an employee productivity
assistant, a customer-facing chatbot, and an agent with limited access
to business tools. Finally, it will incorporate findings into a refined
toolkit and an executive-ready 90-day roadmap.

Frameworks will have distinct roles rather than be treated as
interchangeable. NIST will provide the overarching risk-management
structure; ISO/IEC 42001 will provide the formal international
management-system anchor; OWASP will provide the cybersecurity threat
lens; and the AI Verify Testing Framework and Infocomm Media Development
Authority (IMDA) model frameworks will provide practical process checks,
evidence expectations, and implementation considerations. AI Verify is
mapped to NIST, the Hiroshima Process, and ISO/IEC 42001, but it is a
voluntary, internationally aligned testing framework rather than a
certifiable international standard (AI Verify Foundation, 2025). This
distinction prevents the project from overstating any source\'s
authority while still benefiting from Singapore\'s operational approach.

Singapore\'s Model AI Governance Framework for Generative AI contributes
nine dimensions for building a trusted AI ecosystem, while IMDA\'s newer
Agentic AI framework extends the governance discussion to systems that
can plan and act with greater autonomy. Together, these resources
strengthen the project\'s treatment of accountability, human oversight,
testing, transparency, security, and responsibility across the AI life
cycle (AI Verify Foundation & Infocomm Media Development Authority,
2024; Infocomm Media Development Authority, 2026).

The primary deliverables will be (a) a concise AI acceptable-use and
governance baseline, (b) an SME self-assessment worksheet, (c) a control
crosswalk showing traceability to source frameworks, (d) a use-case
risk-rating method, (e) a prioritized remediation roadmap, and (f) the
final capstone report. The light-weight screening assessment is expected
to use approximately 12 to 15 questions across eight control domains and
a four-level scoring scale from 0 (not established) to 3 (defined and
evidenced). Critical decision gates will override the numeric score when
proposed use involves prohibited data, unbounded permissions, or
high-impact decisions without accountable human review.

## Stakeholders

The project is intentionally cross-functional because information
technology alone cannot manage AI risk. For a real SME implementation,
the executive sponsor would approve risk tolerance and resources; the
project lead or cybersecurity advisor would develop and maintain the
baseline; information technology would provide technical evidence and
implement controls; legal or privacy personnel would interpret
contractual and regulatory obligations; business process owners would
define intended use and acceptable performance; human resources would
support workforce policy and training; procurement would evaluate
providers; and end users would test clarity and usability. Customers and
data subjects are indirect stakeholders because poor safeguards could
affect their information or services.

Executive sponsor: approves scope, risk tolerance, policy ownership, and
remediation funding.

> Capstone researcher/project lead: performs research, develops
> artifacts, manages schedule, and documents limitations.
>
> IT and security representatives: validate feasibility, identity
> controls, logging, and incident-response integration.
>
> Business and data owners: classify information, identify use-case
> value, and accept or reject residual risk.
>
> Legal, privacy, procurement, and HR representatives: review
> obligations, provider terms, workforce rules, and training needs.
>
> Pilot users or expert reviewers: assess whether questions and
> recommendations are clear, efficient, and actionable.

## High-Level Costs Associated with Project

The estimate below treats labor as an imputed planning cost so that the
proposal reflects the resources a real SME might require. If the work is
completed entirely as a student capstone working with local non-profit
organizations, using existing university and open-source resources, most
labor is non-cash, and the incremental expense may be limited to
optional collaboration or testing tools. Estimates are rounded and will
be refined after Milestone 1.

**Table 1**

*Preliminary Budgetary Estimate*

  -----------------------------------------------------------------------
  **Cost element**                 **Basis**              **Estimate**
  -------------------------------- ---------------------- ---------------
  Research and framework crosswalk 30 hours x \$65        \$1,950

  Baseline and assessment design   35 hours x \$65        \$2,275

  Prototype development and        30 hours x \$65        \$1,950
  documentation                                           

  Scenario testing and revision    20 hours x \$65        \$1,300

  Project management and final     15 hours x \$65        \$975
  report                                                  

  Optional tools and secure file   Allowance              \$250
  storage                                                 

  Independent SME/security review  Allowance              \$750

  Contingency                      Approximately 10%      \$945

  Total estimated value            130 labor hours plus   \$10,395
                                   allowances             
  -----------------------------------------------------------------------

## Expected Outcomes of the Project

The expected outcome is a usable minimum AI assurance-readiness baseline
that helps an SME identify and prioritize AI-related cybersecurity and
governance gaps without requiring it to implement every provision of a
large framework. The baseline will use plain language and provide
traceability between each readiness domain and selected authoritative
guidance. It will distinguish actions to address before implementation
from improvements that may be introduced progressively as the AI use
case and associated risks become more complex.

The project will produce the following outcomes:

A structured profile of each participating SME's selected AI use case,
including its business purpose, users, data, vendor involvement, system
access, level of autonomy, potential impact, and accountable owner.

A lightweight screening instrument containing 12 questions across eight
AI assurance-readiness domains. Each question will include examples of
acceptable evidence and use a 0-to-3 evidence-based readiness scale.

A readiness profile that identifies controls that are not addressed,
recognized but not yet developed, partially implemented, or supported by
documented evidence. The profile is intended to identify gaps and guide
improvement, not provide certification or a formal determination of
compliance.

A set of priority risk and escalation indicators for use cases involving
sensitive data, privileged system access, consequential decisions,
autonomous actions, inadequate human oversight, or unsupported vendor
practices.

A practical decision guide advisers can use to help SMEs understand
their readiness gaps and identify appropriate next steps. These may
include strengthening safeguards, obtaining vendor evidence, assigning
accountability, improving documentation, or preparing for specialist
assessment and future formal assurance.

A framework crosswalk connecting the 12 screening questions to relevant
principles and controls from the NIST AI Risk Management Framework, NIST
Generative AI Profile, NIST Cybersecurity Framework 2.0, ISO/IEC 42001,
OWASP guidance, AI Verify, and applicable IMDA AI governance frameworks.
The crosswalk will demonstrate alignment and traceability but will not
claim complete compliance with any framework or standard.

A phased improvement roadmap organized into immediate, 30-day, 60-day,
and 90-day actions. Recommendations will be prioritized according to
risk reduction, effort, cost, ownership, and dependencies.

Pilot findings from approximately five to eight SMEs and feedback from
selected Singapore AI Association advisers concerning the questions'
clarity, relevance, completion effort, ability to identify readiness
gaps, and usefulness in supporting adviser-SME conversations.

A final report documenting the research method, pilot findings,
identified limitations, recommended revisions, and requirements for
future larger-scale testing and validation.

## Benefits of the Proposed Project

The principal benefit is proportional governance: the organization can
enable valuable AI uses while concentrating scarce resources on the
conditions most likely to cause harm. A repeatable intake and assessment
process should reduce inconsistent approvals, improve visibility into
shadow AI, and provide employees with clearer boundaries for acceptable
data and tasks. The baseline can also strengthen procurement by
requiring evidence of data retention, model training, access control,
security testing, and incident notification before approving a vendor.

The project also creates management benefits. Executives receive a
concise view of residual risk and priority decisions; technical teams
receive specific control objectives; and business owners retain
accountability for the context in which output is used. Because the
baseline is modular, an SME can begin with employee assistants and
extend the same structure to chatbots or agents. NIST CSF 2.0 provides a
common language for communicating cybersecurity outcomes across
organizations of different sizes (Pascoe et al., 2024), while ISO/IEC
42001 supplies a recognized management-system structure for
organizations that later require greater governance maturity or
independent certification (International Organization for
Standardization \[ISO\], 2023). The IMDA frameworks add a practical
Asia-Pacific perspective without limiting the resulting baseline to
Singapore.

## Risks to Project Completion and Proposed Mitigations

**Table 2**

*High-Level Project Risks and Mitigation Strategies*

  -----------------------------------------------------------------------------
  **Risk**         **Priority**   **Mitigation strategy**
  ---------------- -------------- ---------------------------------------------
  Scope expansion  High           Limit the baseline to predeployment and early
                                  operational controls for assistants,
                                  chatbots, and limited agents; record
                                  exclusions in the project charter.

  Rapidly changing High           Use versioned source records, perform a
  threats or                      currency check in Milestones 3 and 4, and
  guidance                        separate durable control objectives from
                                  vendor-specific examples.

  Framework        Medium         Apply a minimum-viable-control criterion and
  complexity                      preserve full traceability in a separate
                                  crosswalk rather than placing technical
                                  detail in every user question.

  Limited access   Medium         Use a transparent composite case and three
  to real SME data                defined scenarios; avoid claiming statistical
                                  generalizability from hypothetical
                                  validation.

  Reviewer         Medium         Schedule review during Milestone 2, provide a
  availability                    structured feedback form, and retain an
                                  expert desk-review alternative.

  Assessment bias  High           Require evidence for scores, add critical
  or false                        decision gates, document residual risk, and
  assurance                       state that the tool does not constitute
                                  certification or legal advice.

  Schedule         Medium         Time-box research, maintain weekly completion
  slippage                        criteria, and defer optional formatting or
                                  secondary mappings before reducing core
                                  validation work.
  -----------------------------------------------------------------------------

## Milestone 1: Initiation, Research, and Requirements (Units 2/3)

**Objective.** Establish a controlled project scope and an evidence base
from which the SME baseline can be designed.

# Detailed work breakdown

**Confirm scope and success measures:** Define the representative SME,
covered AI use cases, exclusions, research question, deliverable
boundaries, and completion criteria. Establish a change log so new ideas
do not silently expand the project.

**Conduct targeted literature and standards review:** Review the NIST AI
RMF, NIST Generative AI Profile, NIST CSF 2.0 and small-business
guidance, ISO/IEC 42001, OWASP GenAI LLM Top 10 2026, the AI Verify
Testing Framework, IMDA\'s Model AI Governance Frameworks for Generative
and Agentic AI, and selected government data-security guidance. Record
each source\'s authority, purpose, audience, control implications,
publication date, and limitations.

> **Develop the use-case and threat inventory:** Describe data flows,
> users, providers, integrations, decisions, and potential harms for an
> employee assistant, customer chatbot, and limited workflow agent.
> Identify threat events including sensitive-data disclosure, prompt
> injection, insecure output use, excessive agency, compromised
> dependencies, and loss of auditability.
>
> **Create the initial control taxonomy:** Group candidate safeguards
> into eight domains and remove duplication. Assign each framework a
> defined role and map each proposed control to a business risk and at
> least one authoritative source. Maintain a separate crosswalk so
> international alignment does not make the SME-facing questionnaire
> longer or more technical.
>
> **Approve requirements baseline:** Prioritize requirements as
> mandatory, recommended, or deferred. Confirm that the project can be
> completed within the remaining units and update the budget and
> schedule assumptions.

### Deliverables and completion evidence

> Project charter containing scope, assumptions, exclusions, research
> question, and change-control approach.
>
> Annotated evidence matrix and APA reference inventory.
>
> Three use-case descriptions with data-flow and threat assumptions.
>
> Draft eight-domain control taxonomy and preliminary framework
> crosswalk.

**Acceptance criteria.** Every proposed control has a stated risk
rationale and source; the three use cases are sufficiently detailed for
later testing; scope can be completed within Units 4 through 9.

**Dependencies.** Access to current source publications and timely
instructor feedback on scope.

## Milestone 2: Baseline and Assessment Prototype (Units 4/5)

**Objective.** Translate the research into an SME-friendly baseline,
scoring method, and evidence-based assessment prototype.

### Detailed work breakdown

> **Define minimum control statements:** Write concise outcomes for
> governance ownership, acceptable use, data handling, identity and
> access, third-party risk, prompt and content security, human
> oversight, monitoring, and incident response. Separate universal
> controls from controls triggered by higher-risk use cases and compare
> management-system expectations with AI Verify and IMDA implementation
> guidance.
>
> **Design assessment questions and evidence prompts:** Convert each
> control outcome into a plain-language question. Use AI Verify\'s
> evidence-oriented process checks to strengthen examples of acceptable
> evidence, such as an approved-use register, data classification rule,
> configured single sign-on, vendor contract term, test record, audit
> log, human-oversight record, or response playbook.
>
> **Build the scoring and decision model:** Define levels 0 through 3,
> calculate domain and overall results, and specify how missing evidence
> affects a rating. Add critical gates that prevent a favorable average
> score from hiding prohibited data use, privileged access without least
> privilege, or high-impact automation without human authorization.
>
> **Create the prototype toolkit:** Develop the assessment worksheet,
> use-case intake form, control crosswalk, findings summary, and draft
> 90-day roadmap. Include instructions, ownership fields, priority,
> estimated effort, and residual-risk notes.
>
> **Perform structured design review:** Use a checklist to review
> traceability, duplicate questions, readability, scoring consistency,
> and feasibility. Obtain feedback from an instructor, cybersecurity
> practitioner, or SME advisor when available and log each accepted or
> rejected change.

### Deliverables and completion evidence

> Version 1.0 baseline and 25-to-35-question assessment.
>
> Evidence guide and four-level maturity rubric.
>
> Critical decision-gate logic and risk-rating method.
>
> Draft crosswalk, findings summary, and remediation-roadmap templates.
>
> Review log documenting feedback and disposition decisions.

**Acceptance criteria.** All eight domains are represented; questions
are understandable without specialist interpretation; scores require
evidence; critical risks cannot be averaged away; every control remains
traceable to a threat and source.

**Dependencies.** Milestone 1 taxonomy and use-case assumptions must be
stable; at least one qualified review channel should be identified.

## Milestone 3: Scenario Validation and Refinement (Units 6/7)

**Objective.** Evaluate whether the prototype consistently identifies
meaningful gaps and produces actionable recommendations across the three
representative use cases.

### Detailed work breakdown

> **Prepare validation scenarios:** Create consistent fact patterns for
> the employee assistant, customer chatbot, and limited agent, including
> data categories, user roles, integrations, vendor claims, oversight
> steps, and deliberately missing safeguards.
>
> **Run the assessment:** Complete the tool for each scenario, preserve
> evidence and assumptions, record time to completion, and identify
> questions that produce ambiguity, inconsistent ratings, or
> recommendations unrelated to the scenario\'s actual exposure.
>
> **Test decision gates and prioritization:** Verify that sensitive-data
> use, unbounded tool permissions, unsupported vendor practices, and
> consequential automated actions receive appropriate escalation.
> Compare remediation priority against impact, likelihood, dependency,
> effort, and compensating controls.
>
> **Evaluate usability and coverage:** Apply defined measures:
> completion time, percentage of questions requiring clarification,
> control-to-source traceability, number of material scenario risks
> detected, duplicate items, and reviewer agreement with priority
> findings. Compare retained controls against the AI Verify principles
> and relevant IMDA GenAI or Agentic AI dimensions as a coverage check.
> Treat these as design measures rather than proof of external
> effectiveness.
>
> **Revise and regression-test:** Simplify unclear language, merge
> duplication, correct mappings, adjust scoring thresholds, and rerun
> affected scenarios. Maintain a revision history so changes can be
> linked to observed problems.

### Deliverables and completion evidence

> Three completed scenario assessments with evidence and assumptions.
>
> Validation results matrix covering usability, coverage, traceability,
> and prioritization.
>
> Issue and revision log with rationale for each substantive change.
>
> Version 2.0 baseline and toolkit after regression testing.

**Acceptance criteria.** A trained generalist can complete each scenario
in approximately 60 minutes; all critical scenario conditions are
flagged; 100% of retained controls have source traceability; no
unresolved high-severity scoring defect remains.

**Dependencies.** A complete Version 1.0 prototype, stable scenarios,
and reviewer access or a documented desk-review substitute.

**Milestone 4: Finalization, Roadmap, and Capstone Delivery (Units
8/9)**

**Objective.** Convert validated findings into a coherent final toolkit
and academic report that an SME decision maker can use and maintain.

### Detailed work breakdown

> **Analyze and synthesize findings:** Summarize what the scenario tests
> reveal about minimum controls, differences among assistants, chatbots,
> and agents, recurring dependencies, and limits of the scoring
> approach. Separate observations from claims that would require field
> research.
>
> **Finalize the prioritized roadmap:** Organize remediation into
> 0-to-30, 31-to-60, and 61-to-90-day phases. Assign a suggested owner,
> expected evidence, effort level, dependency, and risk-reduction
> rationale to each action.
>
> **Complete the toolkit:** Finalize the baseline, assessment,
> instructions, intake form, multi-framework crosswalk, findings
> summary, and executive dashboard. Add version information, review
> cadence, document owner, and triggers for reassessment such as a new
> vendor, new data type, tool-enabled agency, or material revision to
> NIST, ISO, OWASP, AI Verify, or IMDA guidance.
>
> **Write and edit the final report:** Document the problem, method,
> framework synthesis, prototype design, validation results, benefits,
> costs, risks, limitations, and recommendations. Verify that
> paraphrases are original, in-text citations match references, and
> conclusions do not exceed the evidence.
>
> **Perform quality assurance and handoff:** Check artifact
> completeness, calculations, links, accessibility, terminology, and
> formatting. Conduct a final currency review of major sources, create
> an executive presentation outline, and archive the clean final
> versions with a maintenance note.

### Deliverables and completion evidence

> Final SME AI Security Baseline and self-assessment toolkit.
>
> Final control crosswalk and three-phase implementation roadmap.
>
> Executive summary and presentation outline.
>
> Completed IT595 capstone report with APA citations and references.
>
> Maintenance note defining review ownership, frequency, and change
> triggers.

**Acceptance criteria.** All promised artifacts are complete and
internally consistent; citations and references reconcile; high-priority
recommendations have owners and evidence; the final report clearly
states scope, limitations, and expected---not proven---benefits.

**Dependencies.** Completion of Milestone 3 validation, incorporation of
instructor feedback, and sufficient time for final academic and visual
quality review.

## Conclusion

This proposal addresses a timely management problem: SMEs need to gain
value from generative AI without relying on either blanket prohibition
or unmanaged adoption. The proposed capstone will create a minimum,
evidence-based baseline that connects governance, cybersecurity, and
day-to-day business decisions. Its four milestones move deliberately
from scope and research, through prototype design, to scenario
validation and final delivery. The result is expected to give smaller
organizations a defensible starting point for approving use cases,
protecting data, controlling access, reviewing output, evaluating
vendors, monitoring activity, and responding when safeguards fail.

The project is feasible within the IT595 unit structure because it
limits its claim: it will produce and evaluate a practical
decision-support toolkit, not certify compliance or demonstrate
effectiveness across the entire SME population. By documenting
assumptions, source traceability, acceptance criteria, and limitations,
the capstone can contribute an original applied artifact while remaining
academically credible and useful beyond the course.

## References

AI Verify Foundation. (2025). What is AI Verify?
https://aiverifyfoundation.sg/what-is-ai-verify/

AI Verify Foundation & Infocomm Media Development Authority. (2024).
Model AI governance framework for generative AI.
https://aiverifyfoundation.sg/resources/mgf-gen-ai/

Autio, C., Schwartz, R., Dunietz, J., Jain, S., Stanley, M., Tabassi,
E., Hall, P., & Roberts, K. (2024). Artificial intelligence risk
management framework: Generative artificial intelligence profile (NIST
AI 600-1). National Institute of Standards and Technology.
https://doi.org/10.6028/NIST.AI.600-1

Cybersecurity and Infrastructure Security Agency. (2025, May 22). New
best practices guide for securing AI data released.
https://www.cisa.gov/news-events/alerts/2025/05/22/new-best-practices-guide-securing-ai-data-released

Eliot, D. (2024). NIST Cybersecurity Framework 2.0: Small business
quick-start guide (NIST SP 1300). National Institute of Standards and
Technology. https://doi.org/10.6028/NIST.SP.1300

Infocomm Media Development Authority. (2026, January 22). Singapore
launches new model AI governance framework for agentic AI.
https://www.imda.gov.sg/resources/press-releases-factsheets-and-speeches/press-releases/2026/new-model-ai-governance-framework-for-agentic-ai

International Organization for Standardization. (2023). ISO/IEC
42001:2023: Information technology---Artificial
intelligence---Management system. https://www.iso.org/standard/42001

Open Worldwide Application Security Project. (2026, August 3). OWASP
GenAI LLM Top 10 2026.
https://genai.owasp.org/resource/owasp-genai-llm-top-10-2026/

Pascoe, C., Quinn, S., & Scarfone, K. (2024). The NIST Cybersecurity
Framework (CSF) 2.0 (NIST CSWP 29). National Institute of Standards and
Technology. https://doi.org/10.6028/NIST.CSWP.29

Tabassi, E. (2023). Artificial intelligence risk management framework
(AI RMF 1.0) (NIST AI 100-1). National Institute of Standards and
Technology. https://doi.org/10.6028/NIST.AI.100-1
