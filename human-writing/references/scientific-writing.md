# Scientific Writing: Let the Evidence Carry the Claim

This file covers research papers, abstracts, literature reviews, research and grant proposals, technical reports, and similar academic work. Read it together with `references/reality.md` whenever the work makes claims about real studies, methods, data, people, or prior literature.

Scientific writing is not impersonal writing. Precision, traceable reasoning, and clear limits establish its voice. Do not simulate rigor with dense terminology, passive voice, or inflated significance.

## Scientific Format Overrides

Scientific conventions take priority over the default prose prohibitions when they are required by the venue or improve precision. Use colons in titles, headings, captions, definitions, and citations; use dashes for ranges, compound modifiers, and mathematical notation; and use numbered headings, tables, equations, abbreviations, and reference lists where the field expects them. Do not remove required structure simply to make the text sound more conversational.

The evidence rules remain non-negotiable. Format does not justify invented citations, misleading figures, unsupported causal claims, or inflated impact language.

## Start With the Assignment and Venue

Identify the document type, audience, decision it must support, and governing instructions before drafting. A journal's author guide, conference template, funder's notice, or institutional policy outranks this file.

- For a manuscript, record the target venue, article type, word limit, abstract format, citation style, required reporting guideline, and data or code policy.
- For a proposal, record the funder, notice or call, review criteria, required sections, page limits, eligibility, budget rules, and submission deadline.
- For a report, record the decision-maker, scope, data cutoff date, required level of certainty, and what action the report must enable.

Do not use a generic introduction or a recycled methods section until these constraints are known. A strong paper can fail a venue's format requirement; a strong proposal can fail because it answers a different call.

## First Establish the Evidence Boundary

Before drafting, list what the work can actually support.

- The research question, scope, and intended audience.
- Supplied sources, data, protocols, observations, or results.
- Claims each source or result supports.
- Method details that are known and reproducible.
- Limits, unknowns, and work that remains to be done.

Do not invent citations, quotations, datasets, sample sizes, statistical results, experiments, approvals, collaborators, institutions, or prior findings. A plausible-looking reference is still fabricated. If the user needs citations but has not supplied them and research is available, research first. Otherwise, mark the unsupported claim as a gap or ask up to three focused questions.

Separate observation, interpretation, and recommendation. An observed result states what happened. An interpretation explains what it may mean. A recommendation states what should be tried or decided next. Do not let one sentence quietly become all three.

### Build an Evidence Ledger

Before drafting a section, create a small private ledger. It keeps citations attached to the claims they actually support.

| Claim or decision | Evidence | Exact support | Limitation | Where it appears |
| --- | --- | --- | --- | --- |
| The intervention improved outcome X in population Y | Study or dataset | Result, table, or page | Design, sample, and setting | Results and discussion |
| The proposed method is feasible | Pilot result, prior work, or preliminary data | Method and observed output | What has not been tested | Approach and feasibility |

The entries are prompts, not text to paste into the final document. If the ledger has no evidence cell, make the sentence a research question, a planned test, or an explicit limitation instead of a claim.

### Use the Right Strength of Language

Match verbs to the evidence. "Measured" and "observed" describe a dataset. "Was associated with" describes correlation. "Caused" requires a design that can support causation. "May" marks a bounded interpretation; it does not rescue an unsupported assertion.

For example, do not write, "The intervention reduces readmission." Write, "In this sample, the intervention group had a lower readmission rate than the comparison group." Add the effect estimate, uncertainty, and comparison definition when they are available. Only then explain whether the design supports a causal interpretation.

## Research Papers and Technical Reports

### Start With a Precise Contribution

State the problem, what is already known, the gap this work addresses, and the contribution it makes. Each part needs support. A contribution may be a measurement, comparison, method, implementation, replication, dataset, or negative result. Do not call routine work novel without a real comparison.

Let the paper answer a sequence of questions.

1. What question is being answered, and why does it matter within the stated scope?
2. What was done, with enough detail to understand or reproduce it?
3. What did the evidence show?
4. How far do those results support the conclusion?
5. What remains uncertain or outside scope?

Write methods in the order another researcher would need to understand the work. Name inputs, selection criteria, procedures, measurements, comparison conditions, and analysis choices where known. Do not hide an unclear method behind phrases such as "a rigorous framework" or "a comprehensive evaluation."

In results, lead with the finding and give the evidence beside it. Tables and figures need a point: explain the comparison, scale, and exception that matter. Do not repeat every number in prose. A result that does not differ from a baseline or lacks statistical support still belongs in the record when it changes the interpretation.

In discussion, distinguish what the results show from why they may have occurred. Compare with prior work accurately, without turning correlation into cause or one setting into a universal rule. Put limitations near the claim they limit rather than burying them in a final disclaimer.

Write the abstract last. It should state the question, approach, key result, and bounded conclusion. It should not introduce claims, citations, or implications absent from the paper.

### Abstract Template

Use the venue's required structure. When none is specified, write four compact parts.

1. **Context and question:** What problem is being addressed, in which system or population, and what gap remains?
2. **Approach:** What data, materials, method, or analysis was used?
3. **Key finding:** What is the primary result, including the relevant comparison and uncertainty when available?
4. **Bounded conclusion:** What does the result support, and what does it not establish?

Do not write "This study is the first to" unless the literature search supports that claim. Do not write "significantly improved" unless the statistical test, threshold, and comparison are known. A result that is preliminary, exploratory, or limited to one dataset should say so in the abstract.

### A Practical Manuscript Workflow

1. Write a one-sentence question with the population or system, intervention or exposure, comparison, outcome, and scope where applicable.
2. Build the evidence ledger and list every table, figure, or artifact the manuscript needs.
3. Draft methods and results from the actual record before writing interpretation.
4. Write the discussion around the findings, their limits, and the relevant prior work.
5. Write the introduction and abstract last, then reconcile every claim with the completed body.

For empirical work, report the data source, inclusion and exclusion criteria, preprocessing, model or measurement choices, comparison conditions, evaluation metric, and uncertainty. For qualitative work, report recruitment, setting, data collection, analytic approach, researcher position where relevant, and how interpretations were developed. For computational work, record software versions, parameters, hardware where material, random seeds where applicable, and access to code, data, or a reason they cannot be shared.

### Methods and Results Templates

**Methods.** Start with the study design or system. Then give data or materials, selection criteria, procedure, primary outcome or metric, comparison, and analysis plan in the order a reader would reproduce the work. Mark any deviation from a preregistered or planned method, and explain its effect on interpretation.

**Results.** Start each subsection with the finding, then report the evidence. For example: "The model's calibration error was lower on the held-out test set than the baseline's [insert estimate and uncertainty]. This comparison applies to [defined dataset and evaluation protocol]." Do not write the placeholders as final prose; replace them with confirmed values or omit the claim.

**Discussion.** For each finding, state what the evidence directly shows, the most plausible interpretation, the key alternative explanation, and the limit on generalization. One limitation paragraph at the end cannot repair overconfident claims throughout the paper.

### Tables, Figures, and Equations

Every visual element needs a job. A table supports comparison, a figure reveals a pattern or distribution, and an equation defines a relationship that prose cannot state precisely.

- Give each item a self-contained caption: what is shown, units, group or baseline, sample or data scope, and any important uncertainty marker.
- Refer to each item in the text for its finding, not merely to announce that it exists.
- Never alter axes, color scales, exclusions, or image processing in a way that changes the apparent result without disclosure.
- Keep source data, code, and transformation steps traceable to the reported output.

## Embedded Reporting and Proposal Examples

### Systematic Reviews

PRISMA 2020 is a real, peer-reviewed reporting guideline for systematic reviews. Its checklist, abstract checklist, and flow diagrams all serve one purpose: let readers see why the review was done, what the authors did, and what they found.

Embed these reporting details in the review itself.

- State the question, eligibility criteria, information sources, and the date each source was searched.
- Preserve the complete search strategy for every database, register, and website used.
- Explain how records and full reports were screened, how many reviewers participated, and whether they worked independently or used automation.
- Account for included studies, excluded reports that appear eligible, and the reason for each exclusion.
- Describe how studies were grouped, how results were synthesized, how heterogeneity was explored, and which sensitivity analyses were performed.
- Report the certainty or confidence in the body of evidence when the review method calls for it.

Apply the principle beyond health research. A literature review should let a reader determine what was sought, what was included, what was excluded, and how the included work shaped the conclusion. Do not label a narrative reading list a systematic review unless it used an explicit, reproducible process.

### NIH Proposal Hierarchy

NIH application guidance uses a clear order of authority: NIH Guide notices control first, the specific funding opportunity controls second, and general application instructions control third. Apply the same rule to every funder. The call, its current notices, and its required forms outrank any reusable proposal template.

For a specific aim, replace a broad promise such as "We will transform clinical decision-making with AI" with a testable commitment: "We will evaluate whether the model improves calibration and error detection on the held-out dataset specified in Aim 1." The second sentence defines the intervention, outcome, and boundary. It still needs a supplied or researched rationale, method, and evaluation plan before it belongs in a proposal.

### NSF Proposal Example

The following requirements are extracted and summarized from NSF's Proposal & Award Policies & Procedures Guide, PAPPG 24-1, Chapter II. NSF rules and program solicitations change, so always verify the current call before submission.

For a standard NSF research proposal, the Project Summary is no more than one page and includes three distinct parts:

1. **Overview**: the proposed activity, its objectives, and the methods to be used.
2. **Intellectual Merit**: how the work can advance knowledge in its field.
3. **Broader Impacts**: how the activity can benefit society or contribute to specific societal outcomes.

The Project Description must clearly state the work, its objectives and significance, its relation to the current state of knowledge, and the general plan of work. It should answer five questions: what will be done, why it matters, how it will be done, how success will be assessed, and what benefits could follow. Unless a solicitation says otherwise, it is limited to 15 pages and must be self-contained; do not rely on URLs for material reviewers need to evaluate the proposal.

NSF requires a separate **Broader Impacts** heading in the Project Description. Do not treat it as a generic claim that the research will help society. Name the activity, audience, delivery mechanism, output, and evidence that will show whether it happened. The Data Management and Sharing Plan is a separate document of up to two pages. It should identify the data, software, samples, or other outputs to be produced; relevant data and metadata standards; access and protection conditions; reuse terms; and preservation or archive arrangements. A statement that no detailed plan is needed requires a clear justification.

**Illustrative NSF Project Summary structure.** This is a model structure, not a real submission or a guarantee of compliance.

> **Overview.** This project will measure how [intervention] affects [outcome] in [defined system]. The team will collect [specified data], compare [condition A] with [condition B], and evaluate [metric] using the analysis plan described in the Project Description.
>
> **Intellectual Merit.** The project tests whether [mechanism or relationship] explains the observed difference between [A] and [B]. It contributes a documented dataset, a reproducible analysis workflow, and evidence about the limits of the method in [scope].
>
> **Broader Impacts.** The team will publish an accessible dataset and teaching module for [identified audience], run [number] workshops with [partner or participant group], and track participation, completion, and reuse. These activities will be adjusted if the stated measures show they are not reaching the intended audience.

This structure works because each paragraph answers a different reviewer question. Replace every bracketed placeholder with information supported by the project plan, preliminary evidence, or confirmed resources. Do not claim that the work will improve education, broaden participation, or change practice until the proposal identifies the activity and a credible way to assess it.

### NSF Compliance Checks

Before drafting for NSF, verify the solicitation and current PAPPG requirements for the proposal type. For a standard research proposal, check the following in addition to the narrative.

- Project Summary includes an overview, Intellectual Merit, and Broader Impacts.
- Project Description uses a separate **Broader Impacts** heading and stays within the applicable page limit.
- References contain bibliographic citations only, not extra narrative that belongs in the Project Description.
- Budget figures, budget justification, personnel effort, facilities, and described work agree with one another.
- Current and pending support, collaborators and other affiliations, and biographical material are accurate, current, complete, and prepared in the required format.
- A Data Management and Sharing Plan addresses outputs, standards, access, reuse, and preservation, or explains why no detailed plan is needed.
- Where applicable, include the required mentoring plan, human-subjects, animal-research, safety, fieldwork, collaboration, or Tribal Nation documentation.

## Literature Reviews

Organize a review around the question or disagreement it clarifies, not a source-by-source parade. Group work by method, finding, context, or unresolved question.

For every cited source, preserve the difference between what it directly found, how the present writer interprets it, and what it cannot establish. Read the original study before making a strong claim about it. A review cannot turn a paper's hypothesis, press coverage, or abstract into a confirmed result.

When sources disagree, identify the relevant difference: population, setting, measure, method, date, or definition. Do not resolve disagreement by choosing the conclusion that makes the narrative cleaner.

### Review Workflow

State the review question and eligibility criteria before reading deeply. Keep the search query, source, date, screening decision, and reason for exclusion. Distinguish a source record from the full report it represents; multiple records may describe the same study.

Summarize each included source with its design, setting, participants or data, comparison, outcome, key finding, and major limitation. Synthesis begins only after those units are clear. Do not combine estimates with incompatible outcomes, populations, or definitions merely to produce one number.

### Literature Synthesis Template

Use a claim-evidence-limit sequence rather than one paragraph per source. State the narrow conclusion first. Then compare the relevant studies by population, design, measurement, and result. End by naming the uncertainty that prevents a stronger conclusion. Cite each source beside the fact it supports; a citation cluster at the end of a paragraph does not reveal which source supports which statement.

## Research and Grant Proposals

Open with the problem, the specific gap, and why addressing that gap is worth the proposed effort. The proposal should make clear what will be learned or built, not promise that a desired result will occur.

Each aim needs a question, a concrete output, an approach, and a decision point. An aim such as "explore the impact" is too broad until it says what will be measured, compared, or produced.

Describe the plan in dependency order. State the materials or participants, method, evaluation criteria, timeline, resources, and responsible roles only to the extent they are known. Include the main risk and a credible alternative path. A contingency plan is stronger than certainty language.

Claims of impact should follow from a plausible chain: completing this work produces this evidence or capability, which enables this next decision or use. Do not claim that a proposal will transform a field, solve a social problem, or guarantee adoption without evidence.

### Proposal Workflow

1. Parse the call into mandatory requirements and review criteria.
2. State the problem, gap, and the evidence that the gap exists.
3. Define each aim with an output, method, success criterion, and decision point. For NSF proposals, show how the aim supports Intellectual Merit, Broader Impacts, or both.
4. Show feasibility through prior work, preliminary results, access to resources, or a narrow first milestone.
5. Name risks, alternatives, timeline dependencies, ethics or compliance needs, and responsible roles.
6. Check that the budget, staffing, facilities, data-management plan, references, and required supplementary documents agree with the narrative.

Use conditional language honestly. "If the pilot does not meet the prespecified performance threshold, we will analyze the failure mode and test the alternative method" is a credible contingency. "The pilot will prove feasibility" is an unsupported prediction.

### Revision and Response Letters

When revising after peer review, make a response table with four columns: reviewer point, change made, manuscript location, and reason no change was made when applicable. Quote or paraphrase the reviewer accurately. Thank reviewers briefly, then answer the substance. Do not claim to have performed an analysis, collected data, or changed a manuscript section unless the revised files show it.

For a rejected or unfunded proposal, separate reviewer interpretation from verified requirements. Keep a decision log: comment, evidence in the current draft, planned revision, and whether the revision requires new data, a different method, or a narrower claim. Do not rewrite toward every reviewer preference when it contradicts the funder's call or the evidence.

## Integrity, Authorship, and Sensitive Research

Do not fabricate, selectively omit, manipulate, or suppress results to create a cleaner story. Report deviations from a protocol, missing data, excluded observations, failed experiments, and negative findings when they affect interpretation.

Follow the applicable ethics approval, consent, privacy, security, export-control, animal-research, and conflict-of-interest requirements. Remove identifying information unless its use is authorized. Do not claim approval, consent, registration, data availability, or authorship unless it is true and documented.

AI tools may help with outlining, wording, formatting, and code explanation only within the venue's policy. They cannot validate sources, generate evidence, accept authorship responsibility, or replace expert review. Verify every citation, calculation, and factual claim independently.

## Citation, Style, and Delivery

Use the citation style the venue, funder, or user specifies. Keep a source record while drafting so every citation can be checked. Verify author names, title, publication venue, date, version, page or section, and URL or identifier before delivery.

Use the terminology required by the field, then define specialized terms where readers need it. Prefer direct verbs over nominalizations when the meaning stays precise. Passive voice is useful when the actor is genuinely unknown or irrelevant; do not use it to conceal responsibility.

Before delivery, verify the following.

- Every factual, methodological, and literature claim has support.
- Every citation exists and says what the text attributes to it.
- Numbers, units, sample descriptions, and comparison groups are consistent.
- Conclusions do not exceed the method, data, or stated scope.
- Limitations, conflicts, assumptions, and uncertainty are visible where they affect interpretation.
- Required reporting checklists, declarations, appendices, and data or code statements are complete.
- The document follows the controlling venue, funder, or institutional instructions.
- Scientific-format conventions required by the venue are preserved rather than overridden by general prose rules.