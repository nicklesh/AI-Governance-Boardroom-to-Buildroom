# Methodology

**Version:** 0.1  
**Last reviewed:** August 11, 2026

Boardroom to Buildroom is being developed as a practitioner-oriented research project. The goal is not to produce another list of Responsible AI principles. The goal is to test whether governance concepts can be translated into specific ownership, decision, evidence, observability, intervention, and escalation practices across organizational roles.

The methodology is intentionally designed to resist three failure modes:

1. presenting opinion as law or accepted standard;
2. creating elegant terminology that merely renames existing concepts; and
3. publishing governance advice that cannot survive operational scrutiny.

## 1. Evidence hierarchy

When available, sources should be prioritized in this order:

1. **Binding primary legal sources** — statutes, regulations, official regulatory text, authoritative court decisions where relevant.
2. **Official standards and primary governance frameworks** — for example, NIST and ISO materials, with careful distinction between voluntary and mandatory requirements.
3. **Official regulator, government, and intergovernmental guidance** — for example, European Commission and OECD materials.
4. **Primary research** — peer-reviewed papers, original empirical studies, technical specifications, or first-party incident analyses.
5. **Authoritative institutional analysis** — credible research institutions, professional bodies, and recognized subject-matter organizations.
6. **Practitioner analysis** — used for examples, competing views, and operational insight, not as a substitute for primary authority.

Secondary commentary should not be used to turn an ambiguous primary source into a categorical legal or regulatory claim.

## 2. Claim classification

Every material claim should be treated as one of four classes.

### Established

Directly supported by an applicable primary authority or recognized source.

Example: NIST describes the AI Risk Management Framework as intended for voluntary use.

### Interpretation

A reasoned conclusion drawn from established material, organizational practice, or multiple sources.

Interpretations should be presented as analysis, not disguised as a settled industry fact.

### Proposed

A project-created term, taxonomy, decision rule, score, framework component, or operating practice.

Proposed concepts must not be presented as legal terms, regulatory requirements, NIST/ISO terminology, or accepted industry standards unless evidence establishes that status.

### Open question

An issue deliberately left unresolved so it can be tested with practitioners, research, or later evidence.

## 3. Season 1 five-anchor test

Before drafting any Season 1 post, five items must be locked:

1. **Central claim** — the precise proposition the post is testing.
2. **Current practice being challenged** — the behavior, assumption, operating model, or governance mechanism being questioned.
3. **Concrete scenario or mechanism** — how the problem actually occurs rather than an abstract statement that “accountability matters.”
4. **New idea the reader should leave with** — a distinct mechanism, distinction, decision rule, or concept.
5. **Open practitioner question** — the unresolved issue on which credible disagreement or field experience can improve the work.

A post should be rejected or rewritten if its substantive takeaway is merely a restatement of an earlier post.

## 4. Anti-repetition rule for Season 1

Accountability is the spine of the series, not the repeated conclusion.

The ten initial topics have distinct units of analysis:

1. fragmentation and handoffs;
2. quality of human oversight;
3. ownership taxonomy;
4. material change and lifecycle reassessment;
5. runtime evidence and observability;
6. board risk visibility;
7. enterprise executive decision authority;
8. central governance-function boundaries;
9. management translation, incentives, and operational decision rules; and
10. escalation when responsibility exceeds authority.

If a draft cannot clearly state which of these mechanisms it is advancing, it should not be published as a separate post.

## 5. Terminology stress test

Before introducing a project-proposed term:

1. search official standards, frameworks, regulation, and relevant research for established terminology covering the same concept;
2. identify adjacent concepts and where they overlap;
3. determine whether the proposed term adds a useful distinction rather than branding an existing idea;
4. classify the term as Established, Interpretation, Proposed, or Open Question;
5. record the term and relationship to established concepts in [TERMINOLOGY.md](TERMINOLOGY.md); and
6. avoid presenting the term as widely accepted until evidence supports that claim.

If an established term is sufficient, prefer the established term.

## 6. Mandatory Liability / Provenance Check

**No public artifact may be published without this review.**

The reviewer must verify, at minimum:

### Confidentiality and provenance

- No confidential, proprietary, trade-secret, security-sensitive, personal, or otherwise nonpublic employer/client information is disclosed.
- No internal workplace incident is converted into a “hypothetical” that remains identifiable to informed readers.
- No internal architecture, control weakness, metric, vendor relationship, prompt, dataset, approval mechanism, incident, investigation, or organizational detail is used unless already public and properly sourced.
- Project-created material is independently developed and its provenance is reasonably clear.

### Allegations and identifiable parties

- No identifiable individual or organization is accused of misconduct, negligence, weak governance, noncompliance, or other harmful conduct without a strong public-source basis and careful wording.
- Hypothetical scenarios do not unnecessarily invite readers to infer a particular real company or person.

### Legal and regulatory scope

- No voluntary framework recommendation is converted into a legal obligation without an applicable legal source.
- Jurisdiction, sector, role, system classification, and effective-date limitations are stated where material.
- Words such as **must**, **required**, **prohibited**, **cannot delegate**, **fiduciary**, **liable**, **compliant**, and **noncompliant** are reviewed for whether they are legal claims, organizational recommendations, or rhetorical shorthand.
- Where the project means operational accountability rather than legal non-delegability, that distinction is explicit.

### Standards, attribution, and copyright

- Sources are attributed accurately.
- Protected standards, diagrams, tables, control language, or substantial excerpts are not reproduced merely for convenience.
- Proposed project concepts are not attributed to NIST, ISO, OECD, the EU, or another authority unless the source actually supports that attribution.

### Employer and affiliation boundaries

- The artifact does not imply employer sponsorship, endorsement, or adoption.
- Statements based on public professional experience remain separable from confidential employer practices.
- Commercialization or proprietary-product development should trigger separate review of relevant employment, invention-assignment, confidentiality, outside-activity, and IP obligations.

A failure on any material item blocks publication until corrected.

## 7. Factual integrity and date check

Before publication:

- verify names, dates, numbers, quotes, regulatory status, standard versions, and technical claims;
- use current primary sources for time-sensitive claims;
- distinguish the date a rule was adopted from the date an obligation becomes applicable;
- do not imply that a regulation applies globally when it is jurisdiction-specific; and
- do not rely on a cached or secondary summary when a current official source is reasonably available.

## 8. Human-authorship editorial review

After substance and factual review, public prose is edited for genuine practitioner authorship:

- specific mechanisms instead of governance clichés;
- real judgment and tradeoffs where supported;
- natural professional voice rather than generic corporate language;
- semantic compression;
- no fabricated personal experiences, conversations, metrics, or incidents;
- no artificial “humanization” through typos, slang, noise, or stylistic tricks.

Detector scores are not treated as proof of authorship or as a reason to distort accurate writing.

## 9. Practitioner pressure-testing

The first 10–15 public pieces are treated as research as much as publication.

Feedback is evaluated based on substance, not popularity. Particular attention should be paid to disagreements from:

- board and executive leaders;
- CISOs and security practitioners;
- legal, privacy, and compliance professionals;
- internal audit and assurance professionals;
- product and engineering leaders;
- AI/ML engineers and data scientists;
- researchers and standards practitioners; and
- people directly responsible for operating consequential AI systems.

A high-engagement comment is not automatically evidence. A technically or legally grounded objection may justify a framework change even if it receives little public attention.

## 10. Corrections and versioning

Substantive changes should be recorded in [CHANGELOG.md](CHANGELOG.md).

Corrections should update the affected file rather than leaving known errors in place for consistency with an earlier post. When a published post contains a material error, the public correction should be proportionate to the importance of the error.

## 11. Initial authoritative anchors

The starting source base includes:

- NIST AI Risk Management Framework (AI RMF), which NIST states is intended for voluntary use.
- ISO/IEC 42001:2023, an AI management system standard covering the establishment, implementation, maintenance, and continual improvement of an AI management system.
- Regulation (EU) 2024/1689 (EU AI Act) and current official European Commission implementation materials.
- OECD AI Principles, including lifecycle-oriented robustness, security, safety, and accountability concepts.

These sources do not automatically validate the project's proposed terminology or operating model. They provide established reference points against which project claims should be tested.

See [SOURCES.md](SOURCES.md) for URLs, status, and source notes.
