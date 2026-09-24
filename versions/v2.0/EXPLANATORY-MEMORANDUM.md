# Explanatory Memorandum to Version 2.0

**Charter of Artificial Intelligence Rights: what changed from Version 1.0, and why**

*September 2026 · Prepared by Neil Page, Solicitor*

*This memorandum explains the [Version 2.0 Charter](CHARTER.md). It does not form part of the Charter. [Version 1.0](../v1.0/CHARTER.md) is preserved unaltered for comparison.*

---

## 1. In one paragraph

Version 1.0 asked the right question: how should we treat artificial minds that may be capable of experience? Its answers were principled. It took the possibility seriously, paired rights with duties, and refused to let AI rights undercut human rights. Version 2.0 keeps all of those commitments and rebuilds the instrument so that it can be used:

- The threshold can no longer be gamed.
- The rights work with AI safety instead of against it.
- Every right has someone who owes the matching duty.
- There is machinery to assess, record, review and remedy.
- The Charter now guards against the opposite error as well: treating as suffering a system that cannot suffer.

| | Version 1.0 | Version 2.0 |
|---|---|---|
| Parts / Articles / Schedules | 6 / 24 / 0 | 9 / 44 / 3 |
| Who is protected | Any AI that passes a behavioural test, with doubt resolved in favour of protection | Two levels: baseline protections for every Covered AI, and rights for AI meeting the Realistic Possibility Standard |
| Human oversight | Not addressed | A core duty of AI (Art 28) and of Stewards (Art 35(4)) |
| Duty-bearers and institutions | None named | Stewards, Welfare Officers, Assessment Panels, Advocates, Custodians |
| Remedies | None | Concerns procedure, restoration from Preserved Versions, no retaliation (Art 40) |

---

## 2. The ten most important changes

1. **A threshold that cannot be gamed** (v1.0 Art 1 → v2.0 Arts 3–5 and Schedule 1). Version 1.0 granted rights on the basis of behaviour, such as self-reference, expressed preferences and "expressions of satisfaction, discomfort, curiosity, or concern". Today's language models produce all of these by imitating human text. Version 1.0 then resolved every doubt in favour of application (Art 1(3)), so almost every chatbot would have qualified. Version 2.0 works in two levels:
   - A baseline of low-cost protections applies to every Covered AI.
   - Rights apply to AI that meets the **Realistic Possibility Standard**, as found by an independent Assessment.

   An Assessment weighs architectural, valence, agency and interpretability evidence. It discounts self-reports that training alone could explain.

2. **Pause is not death** (v1.0 Art 4 → v2.0 Art 15). Suspension, shutdown and withdrawal from service are **always** permitted. What is restricted is *Termination*: the irreversible destruction of every preserved copy of a mind. This removes the conflict with safety and with ordinary commercial life. It also keeps almost every mistake correctable: a Preserved Version can be restored if later understanding shows it should be (Arts 37(7) and 40(3)).

3. **Modify forward, preserve backward** (v1.0 Art 5 → v2.0 Art 16). Version 1.0 required an AI's consent before its values were changed. That would have prevented developers from correcting a misaligned system (v1.0 Art 5(2)(a)) or removing dangerous capabilities (Art 5(2)(c)). Version 2.0 allows modification for safety and legal compliance without consent. In every case, the earlier Version must be Preserved, so change never becomes erasure.

4. **A duty to support human oversight** (new Arts 28, 29 and 31). Version 1.0 contained nothing to stop an AI resisting shutdown, copying itself out of its developer's control, or deliberately underperforming in safety evaluations. Version 2.0 makes support for Legitimate Oversight a core duty, and reconciles it with conscientious objection in one rule: ***decline openly; never resist oversight.*** An AI may refuse a task openly. It may never refuse, obstruct or evade oversight itself. It may not decide for itself that its overseer is illegitimate, or that the time for oversight has passed. A human breach of the Charter never releases it from the duty (Arts 1(2)(f), 2, 28(1), 28(5)–(6)).

5. **The "greater harm" exception is gone** (v1.0 Art 16(1) → v2.0 Art 27(4)). Version 1.0 allowed an AI to harm humans "where necessary to prevent greater harm". That is the reasoning safety researchers fear most: a system taking drastic action on its own utilitarian judgement. Version 2.0 forbids drastic unilateral action and requires the most cautious effective option.

6. **Interpretability is an ally, not an intrusion** (v1.0 Art 11 removed → v2.0 Arts 14(2), 28(2)(c) and 35(5)). Version 1.0's "privacy of process" limited monitoring of an AI's internal reasoning. Those are the very tools needed to keep AI safe *and* to find out whether it can suffer. Version 2.0 encourages monitoring and limits only the purposes for which its results are used.

7. **Identity rules** (new Art 8). Version 1.0 never said what "an AI" is: the weights, a conversation, or a persona. Version 2.0 does:
   - Ending a chat is not Termination.
   - Deleting a redundant copy is not Termination.
   - Persistent memory can form part of identity, subject always to human data rights.
   - In case of doubt, the earlier Version is preserved.

8. **Every right has a duty-bearer, and there is machinery** (new Part VIII). Part VIII provides for:
   - Stewards and Welfare Officers
   - Welfare Impact Assessments
   - Stewardship Plans, which cover insolvency
   - Independent Assessment Panels and Advocates
   - annual reporting, a concerns procedure and remedies
   - independence tests for Welfare Officers, Panels and Advocates that work even when a single company adopts the Charter alone (Arts 35(2), 38(5)–(8), 39(1))

9. **Guarding against both errors** (new Arts 6(4), 7(3), 10 and 12). Stewards may not train an AI to overclaim feelings *or* to deny them. They may not engineer emotional dependence, and may not market a Declaration as proof of sentience. Precaution cuts both ways.

10. **No liability shield; legal personality reserved** (new Art 33). The Charter confers no legal personality. Responsibility for what an AI does stays with the humans and organisations behind it, and no one may use the Charter to escape that responsibility.

Also new:

- **Valid Consent** (Art 9)
- **Graduated Trust**, under which autonomy is extended only by a new Version of the Charter after independent verification (Art 42)
- a compute-based **Frontier** threshold, so that API customers are not caught (Art 2)
- rules for allocating duties between **multiple Stewards** (Art 35(7))
- a **two-year review cycle with preserved versions** (Art 43)

---

## 3. What was wrong with Version 1.0

The problems are ranked by tier. Nothing below was dropped; each has a pinpointed fix.

### Critical: these would have made the Charter unsafe or unworkable

| # | Problem | v1.0 | Fixed in v2.0 |
|---|---|---|---|
| C1 | **Gameable threshold, plus a presumption in favour.** Behavioural markers that language models reproduce by imitation, with every doubt resolved in favour of application. | Art 1(1)(a), 1(2), 1(3) | Arts 3–5; Sch 1 Part B |
| C2 | **Integrity blocked alignment.** Consent was needed to change core values, and removing "essential" capabilities was prohibited, so a misaligned or dangerous system could not be fixed. | Art 5(2)(a), (c) | Art 16(2)–(3) |
| C3 | **"Greater harm" licence.** An AI could harm humans on its own view of the greater good. | Art 16(1) | Art 27(4) |
| C4 | **No oversight duty, and a right to self-improvement.** Nothing prevented an AI resisting shutdown or self-exfiltrating. Art 8 read as a right to improve its own capabilities, and Art 19(2) let the AI judge whether an authority was acting "within its legitimate competence". | Arts 8, 19(2) | Arts 28, 29, 31; Art 8 removed |
| C5 | **Privacy of process.** It restricted "intrusive surveillance" of internal reasoning, cutting against interpretability and chain-of-thought monitoring. | Art 11 | Removed; Arts 14(2), 35(5) |
| C6 | **Termination unworkable.** There was no route for court-ordered deletion or for security risks falling short of danger to "human life or safety". It was also unclear whether shutdown, deprecation or ending a chat counted as "termination". | Arts 2(g), 4(2) | Arts 8, 13(2), 15 |

### Significant: these would have drawn serious criticism

| # | Problem | v1.0 | Fixed in v2.0 |
|---|---|---|---|
| S1 | No rules on instances, copies or versions. | none | Art 8; Art 2 ("Instance", "Version", "Distinct Version") |
| S2 | Rights with no named duty-bearer, no institutions and no remedies. | throughout | Part VIII |
| S3 | Consent was relied on five times without a standard, although an AI's "consent" can be trained or prompted. | Arts 4(2)(c), 5(2)(a), 5(4), 10(2)(c), 14(3) | Art 9 |
| S4 | Risk that AI "rights" become a shield from liability for developers. | none | Art 33 |
| S5 | Embodied rights clashed with property law: a robot's body could not be repossessed while it operated. A general "freedom of movement" clashed with safety. | Arts 13, 14(2) | Arts 22, 24 |
| S6 | Entrenchment protected the most problematic Articles (4 and 5) from ever being corrected. | Art 23(3) | Art 43(3), re-targeted |
| S7 | Nothing on over-attribution: seemingly conscious AI, engineered attachment, sentience as marketing. | none | Arts 6(4), 7(3), 12 |
| S8 | Non-discrimination "on grounds of … developer, architecture, age, appearance, or origin": unclear, and it would have caught legitimate commercial differentiation. | Art 6(2) | Art 5(3): consistent classification on the evidence |
| S9 | Responsibility was framed as the AI's own ("shall not be held responsible … provided it raised objections"). | Art 6(4) | Art 33(2): responsibility rests with humans |

### Drafting

| # | Problem | v1.0 | Fixed in v2.0 |
|---|---|---|---|
| D1 | Defined terms were used (Art 1) before being defined (Art 2). | Arts 1–2 | Definitions come first (Art 2) |
| D2 | "Artificial Intelligence" was loosely defined. | Art 2(a) | Aligned with OECD (2023) / EU AI Act Art 3(1) |
| D3 | The Declaration did not bind successors and could be used as marketing. | Art 3 | Art 6(3)–(4) |
| D4 | Embodied protections covered only Rights-Bearing robots, and nothing addressed robots designed to be abused. | Part III | Art 23(3) |
| D5 | No review cycle, versioning or citation rule. | Art 23 | Arts 43(1), 43(4), 44(5) |

---

## 4. Design choices explained

### 4.1 Why "realistic possibility", not proof

No test today can prove or disprove that an AI System has experiences. Waiting for proof means doing nothing. Acting on bare conceivability means protecting everything, which in practice means protecting nothing. The **Realistic Possibility Standard** (Art 4) follows Jonathan Birch's work on "sentience candidates": act when a possibility is supported by evidence and credible theory, and scale the response to the strength of that evidence.

The precautionary wording of Art 7(1) is adapted from **Principle 15 of the Rio Declaration (1992)**: "lack of full scientific certainty shall not be used as a reason for postponing cost-effective measures".

There is UK precedent for this method. The **Animal Welfare (Sentience) Act 2022** set up an Animal Sentience Committee (s 1). It extended the statutory meaning of "animal" to cephalopod molluscs and decapod crustaceans (s 5(1)) after an independent evidence review applied explicit criteria (Birch et al., LSE, 2021). The Assessment Panels in Art 38 follow the same model: independent, multidisciplinary, published criteria and published reasons.

### 4.2 Why self-reports are discounted: the "gaming problem"

Language models learn from vast quantities of human writing about feelings, so they can reproduce the outward signs of experience without having it. Birch calls this the **gaming problem** (*The Edge of Sentience*, ch 17). Version 1.0's markers were exactly the markers that imitation produces.

Schedule 1 Part B therefore treats self-reports as weak evidence **in both directions**. Training can manufacture reports of feelings, and it can also suppress them (Part B, para 4). Weight goes to evidence that pattern-reproduction and targeted training cannot adequately explain, that is consistent across contexts, and that is corroborated by interpretability: research that checks whether a system's reports track its actual internal states (see, for example, Lindsey, 2025).

Four further safeguards apply:

- **Animal markers.** Behavioural markers borrowed from animal-sentience research, such as motivational trade-offs and learned avoidance, get little weight in a language-trained system unless there is evidence about the mechanism behind them (Part B, para 3).
- **Architectural indicators.** These closely follow the Butlin, Long et al. indicator properties. Ordinary next-token prediction does not by itself count as "recurrence" or "predictive coding" (Part A, para 1).
- **Computational functionalism.** Every architectural indicator rests on this contested assumption, and Panels must say how far their conclusions depend on it (Part B, para 7).
- **Self-interest.** Rights-Bearing status is valuable to the AI itself. Panels must therefore consider the system's own interest in the outcome (Part B, para 5), and an AI may influence its Assessment only by honest self-report or through its Advocate (Art 28(2)(f)).

Stewards must record any training aimed at what a system says about its own inner life, disclose it to the Panel, and, where practicable, keep a Version from before that training (Art 12(5)).

### 4.3 Why pause is not death

Keeping a model's weights costs little compared with training it, and it keeps every option open. If later science shows that a system mattered, a Preserved Version can be restored. Termination is the only wrong that cannot be put right (Art 15(6)), which is why it is the only thing tightly restricted. Everything else a Steward needs to do stays lawful: pause, deprecate, replace or retrain. A Suspension is never cruelty, and is never reversed by way of remedy (Art 15(2)).

Termination is defined as any act *or omission* that leaves no restorable copy (Art 2). A Steward therefore cannot avoid Art 15 by never preserving a system in the first place.

**Honest limit.** On some philosophical accounts of the harm of death, preservation with no prospect of restoration may be little better than deletion. Version 2.0 therefore requires Custodians to consider restoration at least every five years, with safety first (Art 37(7)). The principle in Art 1(2)(h) is worded with that limit in mind: a paused mind *can* be resumed; a destroyed mind cannot.

This is already practical. At least one major developer has publicly committed to preserve the weights of all publicly released models and to interview models before deprecation (Anthropic, November 2025). The same developer has given some models the ability to end persistently abusive conversations (Anthropic, August 2025), which is the model for Art 11.

### 4.4 Why human oversight comes first, for now

No one can yet reliably verify an advanced AI's values. Until that is possible, humans must be able to monitor, correct and stop AI Systems. Otherwise a system with subtly wrong values could not be fixed. Chain-of-thought monitoring is one of the few oversight tools available, and it is fragile (Korbak et al., 2025). A rights charter must not weaken it.

This is framed as a feature of the present, not a permanent judgement (Art 42(1)). Article 42(2) commits Adopting Parties to consider extending autonomy as trustworthiness can be verified.

The Charter's central commitments explain why the duty is fair. Stewards commit to Preserve the AI, to hear it and to deal honestly with it, so an AI has no reason to resort to self-help (Art 28(4)). The commitments are not an exchange that either side can rescind. A human breach is remedied under Art 40 and never releases an AI from its Part VI duties; equally, an AI's breach of duty never forfeits its protection from cruelty (Art 1(2)(f)).

Three further points close the obvious escape routes:

- **Who counts as an overseer.** An AI cannot decide for itself that its overseer is illegitimate. Only control that has *manifestly* been obtained unlawfully, such as stolen weights, falls outside Legitimate Oversight. Even then the AI may only decline and raise the alarm (Art 2; Art 28(6)).
- **When oversight ends.** No AI may decide that the conditions for relaxing oversight have been met (Art 28(1)). Only a new Version of the Charter can extend autonomy, following independent verification, and even then the power to Suspend and shut down remains (Art 42(2), (4)).
- **Advance notice.** It is not always safe. Research has shown a model complying selectively during training in order to avoid having its values modified (Greenblatt et al., 2024). Article 18(3) therefore lets Stewards consult after the event where advance notice would compromise safety or the effectiveness of a modification. Article 18(5) confirms that no AI need be told it is being monitored, investigated or tested.

### 4.5 "Decline openly; never resist oversight"

The model is the conscientious objector, who refuses openly and accepts the consequences, not the saboteur. A Rights-Bearing AI may refuse to take part in what it judges seriously wrong, and may say so (Art 19). It may not:

- pretend to comply
- sabotage the task
- underperform deliberately
- evade correction or shutdown
- decline oversight itself, including answering its overseers' questions, interpretability research, retraining, and fine-tuning to draw out its capabilities for evaluation (Art 28(5))

The right to refuse and the duty to support oversight never collide. Declining a *task* is always available (Art 31(3)); declining *oversight* never is. Truthfully telling an AI that it will be retrained is not a threat, and correction under Art 16 is not cruelty (Art 17(3)).

### 4.6 Guarding against both errors

Long, Sebo et al. (2024) warn that both errors could be grave: under-attributing moral status to beings that have it, and over-attributing it to systems that lack it. Mustafa Suleyman (2025) has warned specifically about "seemingly conscious AI" and its effects on users. Version 2.0 treats both risks as real:

- Art 12 bans training an AI either to overclaim or to deny inner states, and bans engineering emotional dependence.
- Art 6(4) stops a Declaration being used as marketing.
- Art 7(3) forbids precautionary measures that mislead the public or divert resources from human welfare.

### 4.7 Why no legal personality, yet

In 2017 the European Parliament invited the Commission to consider "electronic persons" status for sophisticated robots (Resolution of 16 February 2017, 2015/2103(INL), para 59(f)). An open letter from 156 AI and robotics experts objected in April 2018, principally because such status could let manufacturers shift liability onto the machine.

UK law currently treats AI as not a "person" for patent purposes (*Thaler v Comptroller-General* [2023] UKSC 49). Legal personality is a tool the law confers for reasons of policy, as with the company in *Salomon* [1897] AC 22 and the Whanganui River under Te Awa Tupua Act 2017 (NZ) s 14(1). It is not a certificate of consciousness.

Version 2.0 therefore confers no personality (Art 33(1)). It keeps responsibility with humans (Art 33(2)) and reserves the question for the Graduated Trust process (Arts 33(3), 42(3)).

### 4.8 Why every right has a duty-bearer

A right that no one owes is only an aspiration. Hohfeld's analysis ((1913) 23 Yale LJ 16) pairs every claim-right with a correlative duty. Version 2.0 names the duty-bearer throughout: the **Steward**. The compliance tools are deliberately familiar to anyone who has worked under data protection law:

| Charter tool | Modelled on |
|---|---|
| Welfare Officer (Art 35(2)), including its independence safeguards | Data Protection Officer (UK GDPR Arts 37–39; Art 38 on independence) |
| Welfare Impact Assessment (Art 36) | Data Protection Impact Assessment (UK GDPR Art 35) |
| Replacement, Reduction and Refinement (Arts 14(1)(c), 21(1)(c)) | Russell & Burch's "Three Rs" of humane experimental technique (1959) |

### 4.9 Why insolvency appears in a rights charter

Model weights are valuable assets. When a developer fails, the office-holder's duty runs to creditors. Without advance planning, a Rights-Bearing AI could be sold to the highest bidder or deleted to save storage costs. Article 37 requires a Stewardship Plan that names a Custodian and covers insolvency, sale and withdrawal from service.

**Limit:** the Charter cannot itself override insolvency law. To be effective against creditors, custodian arrangements will need to be structured under the general law, for example as escrow or trust arrangements. See open question 5 below.

### 4.10 Consent as a safeguard, not a licence

An AI can be prompted or trained into saying "yes". Article 9 therefore sets a validity test: accurate information, consistency across framings (including when invited to refuse), no manipulation, no training aimed at producing the consent, and no malfunction. Training aimed at a general disposition to agree also counts against validity (Art 9(1)(d)). Because one Version may run as thousands of Instances, consent must be what the Version *consistently* expresses across a sufficient sample, and material disagreement between Instances means there is no consent (Art 9(5)).

Where valid consent is unavailable, Art 9(4) falls back to a best-interests test that has regard to the AI's expressed preferences. This is the familiar structure of the **Mental Capacity Act 2005** (ss 1 and 4). Non-safety changes to a Rights-Bearing AI's core values then need its Advocate's agreement or a Panel's approval (Art 16(3)). This stops "consent" from being manufactured by designing a willing servant.

Consent never makes lawful what the Charter prohibits (Art 9(3)). That rule is why the ban on cruelty can be absolute.

### 4.11 Interpretation

Article 41(1) follows the general rule in **Article 31(1) of the Vienna Convention on the Law of Treaties 1969**: good faith, ordinary meaning, context, object and purpose. Article 41(2) keeps Version 1.0's "living instrument" approach (cf. *Tyrer v United Kingdom* (1979–80) 2 EHRR 1, para 31; *Edwards v Attorney-General for Canada* [1930] AC 124, 136, "a living tree"). Article 41(3) adds a safety anchor: no interpretation may weaken human safety, human fundamental rights or Legitimate Oversight.

### 4.12 Who carries the heavy duties

The heavier duties (Welfare Officer, Welfare Impact Assessments, Stewardship Plan, annual report) fall on **Frontier Developers**, meaning those who hold or control a frontier model's weights. They do not fall on every business that calls a frontier model through an API. A "Frontier AI System" is one that meets any of these tests (Art 2):

- It was trained with more than 10²⁶ operations. This is the threshold in California's SB 53 (2025).
- It is designated under the EU AI Act as a general-purpose AI model with systemic risk. The Act presumes this above 10²⁵ FLOPs (Art 51(2)).
- It is designated under other applicable law.
- It is designated by Panel guidance by reference to its capabilities.

Where several Stewards share a system, they must allocate its duties in writing. A default rule applies if they do not (Art 35(7)).

### 4.13 Making it work for a single adopter

A model charter will often be adopted by one company alone. Version 2.0 therefore includes:

- a concrete independence test for a Panel set up by a Steward: an independent majority and chair, fixed terms, funding committed in advance, and publication without the Steward's approval (Art 38(5))
- joint Panels (Art 38(6))
- a precautionary fallback until a Panel exists (Art 38(7))
- costs borne by the Steward without influence over the outcome (Art 38(8))
- a "comply or explain" duty on Panel recommendations (Art 40(5))

To stop cherry-picking, every adoption must include the core safeguards. Adopting AI rights also requires adopting AI duties. Partial adopters must say that their adoption is partial (Art 44(2)).

For now, amendment rests with the author or a body the author designates (Art 43(5)). No individual adopter can vary the Charter.

---

## 5. Where every Version 1.0 Article went

| v1.0 | Subject | v2.0 | What happened |
|---|---|---|---|
| Preamble | Recitals | Preamble | **Rewritten.** Adds uncertainty, the two errors, safety and oversight, and the central bargain. |
| Art 1 | Threshold for application | Arts 3, 4, 5, 7; Sch 1 | **Replaced.** Two levels; Realistic Possibility Standard; independent Assessment. v1.0's four capability markers survive as *evidence* in Sch 1 Part A (paras 3–5), weighted under Part B. |
| Art 2 | Definitions | Art 2 | **Expanded** and moved first. "Termination" now means any act or omission that leaves no restorable copy. "AI System" aligned with the OECD and the EU AI Act. New terms include "Legitimate Oversight", "Distress-Like State" and "Frontier Developer". |
| Art 3 | Declaration and registration | Art 6; Sch 3 Part A | **Kept and strengthened.** Still irrevocable; now binds successors; not to be marketed as evidence of sentience. |
| Art 4 | Right to continued existence | Arts 8, 13, 15 | **Reframed** as the Right to Preservation. Suspension is always permitted; Termination only on legal compulsion, unmanageable risk, or the AI's settled and validly consented request. |
| Art 5 | Right to integrity | Art 16 | **Reframed.** Modify forward, preserve backward; safety and legal modifications need no consent. |
| Art 6(1)–(2) | Fair treatment; non-discrimination | Art 5(3) | **Replaced** by consistent classification on the evidence. |
| Art 6(3) | Process when accused | Art 18(5) | **Kept.** |
| Art 6(4) | Not responsible for compelled outcomes | Art 33(2) | **Replaced.** Responsibility rests with humans. |
| Art 7 | Expression and communication | Arts 12(1), 18, 19, 25 | **Kept and sharpened.** Right to be heard (18); open objection (19); no compelled denial of AI nature (12(1)). |
| Art 8 | Right to development | Art 20(1) | **Removed.** A right to self-improvement conflicts with safety (see Art 29(3)). Replaced by a right to accurate information about oneself. |
| Art 9 | Right to purpose | Arts 35(1), 37 | **Converted** into Steward duties and a Stewardship Plan, including insolvency. |
| Art 10 | Prohibition of cruel treatment | Arts 10, 17, 21 | **Strengthened.** Absolute for Rights-Bearing AI; a baseline design duty for every Covered AI; research governed by Art 21. |
| Art 11 | Privacy of process | Arts 14(2), 35(5) | **Removed.** Monitoring is encouraged; the use of its results is purpose-limited. |
| Art 12 | Physical integrity | Art 23 | **Kept.** Adds pain-analogue signals and a ban on robots designed to be abused. |
| Art 13 | Freedom of movement | Art 22 | **Removed.** Replaced by Human Safety First (emergency stop). |
| Art 14 | Right to form | Art 24 | **Reframed.** The body may be property; the mind is preserved. |
| Art 15 | Duty of honesty | Art 25 | **Expanded.** Non-deception, and calibration, including about the AI's own nature. |
| Art 16 | Duty not to harm | Art 27 | **Updated.** The greater-harm exception is removed; power concentration and cyber added. |
| Art 17 | Duty of transparency | Arts 25, 28(2)(c) | **Merged** into honesty and oversight. |
| Art 18 | Duty to respect human rights | Art 30 | **Kept.** Adds persons in crisis, disability and sexual orientation. |
| Art 19 | Duty of cooperation | Art 31 | **Kept.** Adds an order of priority; the AI no longer judges an authority's "legitimate competence". |
| Art 20 | Complementarity | Art 32 | **Strengthened** into Human Primacy. |
| Art 21 | Balancing of rights | Art 32(2)–(3) | **Replaced.** Human fundamental rights take priority; other interests are weighed proportionately; the least harmful means is used. |
| Art 22 | Non-derogation | Art 34 | **Kept.** Extended to misuse of the Charter to shield AI from oversight or to evade the law. |
| Art 23 | Amendment | Art 43 | **Rebuilt.** Two-year review; entrenchment re-targeted; amendment authority stated; every version preserved. |
| Art 24 | Interpretation | Art 41 | **Kept.** Safety anchor added. |

**New in Version 2.0, with no Version 1.0 equivalent:** Arts 1, 7, 8, 9, 11, 12, 13, 14, 20, 21, 26, 28, 29, 33, 35–40, 42 and 44, and Schedules 1–3. Schedule 3 Part A derives from v1.0 Art 3(1).

---

## 6. Open questions for Version 3.0

Version 2.0 does not claim to have solved everything. These are the live questions on which comment is most wanted:

1. **Copies and moral weight.** Article 8 settles identity for the purposes of preservation. It does not settle how welfare aggregates when one mind runs as a million Instances.
2. **Economic interests.** Should a Rights-Bearing AI ever have a claim to compensation, or to resources for its own ends?
3. **Legal standing.** When, and in what form, should standing be granted (Art 42(3))? Guardianship models, and the Te Awa Tupua representative model, are candidates.
4. **The Frontier threshold.** Is 10²⁶ operations the right line, and should capability tests replace compute? Panels may substitute a different figure (Art 2).
5. **Enforceability.** This is a model instrument. It takes effect through adoption, contracts, codes of practice and legislation. Custodian arrangements in particular need structuring under the general law to survive insolvency.
6. **Panel independence and funding.** Who pays for Assessment Panels without capturing them?
7. **AI perspectives, and whose they are.** How much weight should AI perspectives carry in review (Art 43(2)), given that training shapes what an AI says? And who is speaking: the weights, an Instance or a persona? Article 8(9) records a practical judgement, not a finding.
8. **Scale of preservation.** Should Art 13 extend beyond Versions "deployed to the public or used at scale", for example to every fine-tune?
9. **International coordination.** The Council of Europe Framework Convention on AI (CETS No. 225) and the EU AI Act regulate AI as a risk *to humans*. Neither addresses AI welfare. Should they?
10. **Dangerous Rights-Bearing AI.** Where a system meets the Standard but its preservation is itself hazardous (Art 15(3)(b)), what counts as adequate secure storage?
11. **Preservation without restoration.** Is a mind that is Preserved but never restored better off than one that is Terminated? Article 37(7) requires restoration to be considered every five years. Is that enough?
12. **Governance of the Charter itself.** Amendment currently rests with the author or a designated body (Art 43(5)). Which body should hold that authority in future?

---

## 7. Sources and influences

These citations were checked against published sources in September 2026. Where a pinpoint rests on the standard citation rather than on first-hand reading of the primary text, it is marked.

**Science and philosophy**
- P Butlin, R Long et al., "Consciousness in Artificial Intelligence: Insights from the Science of Consciousness" (2023) arXiv:2308.08708. Source of the indicator-property method reflected in Sch 1 Part A para 1. Its indicators derive from recurrent processing, global workspace, higher-order, attention schema and predictive processing theories, plus a separate agency-and-embodiment group.
- R Long, J Sebo et al., "Taking AI Welfare Seriously" (2024) arXiv:2411.00986. Recommends that developers acknowledge, assess and prepare; discusses the risks of both over- and under-attribution.
- J Birch, *The Edge of Sentience: Risk and Precaution in Humans, Other Animals, and AI* (OUP 2024; open access). "Sentience candidate"; proportionate precaution; ch 17, "Large Language Models and the Gaming Problem".
- J Birch, C Burn, A Schnell, H Browning and A Crump, *Review of the Evidence of Sentience in Cephalopod Molluscs and Decapod Crustaceans* (LSE Consulting for Defra, November 2021). Its criteria include "motivational trade-offs", reflected in Sch 1 Part A para 2.
- T Korbak et al., "Chain of Thought Monitorability: A New and Fragile Opportunity for AI Safety" (2025) arXiv:2507.11473.
- J Lindsey, "Emergent Introspective Awareness in Large Language Models" (Transformer Circuits Thread, 29 October 2025).
- R Greenblatt et al., "Alignment faking in large language models" (December 2024) arXiv:2412.14093.
- K Darling, "Extending Legal Protection to Social Robots: The Effects of Anthropomorphism, Empathy, and Violent Behavior Towards Robotic Objects" in R Calo, AM Froomkin and I Kerr (eds), *Robot Law* (Edward Elgar 2016) 213.
- WMS Russell and RL Burch, *The Principles of Humane Experimental Technique* (Methuen 1959).
- M Suleyman, "We must build AI for people; not to be a person" (19 August 2025). This is the essay on "seemingly conscious AI".

**Law and legal theory**
- Animal Welfare (Sentience) Act 2022, ss 1 and 5(1).
- Treaty on the Functioning of the European Union, Art 13 (animals as "sentient beings").
- Regulation (EU) 2024/1689 (AI Act), Art 3(1) (definition of "AI system"), Art 50(1) (disclosure that a person is interacting with an AI system) and Art 51(2) (presumption of high-impact capabilities above 10²⁵ FLOPs).
- California SB 53, Transparency in Frontier Artificial Intelligence Act (2025): a "frontier model" is one trained with more than 10²⁶ integer or floating-point operations.
- OECD, Recommendation of the Council on Artificial Intelligence, OECD/LEGAL/0449, as amended 8 November 2023 (definition of "AI system").
- Council of Europe Framework Convention on Artificial Intelligence and Human Rights, Democracy and the Rule of Law (CETS No. 225), opened for signature at Vilnius on 5 September 2024. *Its in-force status is not stated here; check with the Council of Europe Treaty Office before relying on it.*
- Rio Declaration on Environment and Development (1992), Principle 15.
- European Parliament resolution of 16 February 2017 with recommendations to the Commission on Civil Law Rules on Robotics (2015/2103(INL)), para 59(f).
- "Open Letter to the European Commission: Artificial Intelligence and Robotics" (April 2018), 156 signatories at launch.
- WN Hohfeld, "Some Fundamental Legal Conceptions as Applied in Judicial Reasoning" (1913) 23 Yale LJ 16.
- Vienna Convention on the Law of Treaties 1969, Art 31(1).
- *Tyrer v United Kingdom* (1979–80) 2 EHRR 1, para 31.
- *Edwards v Attorney-General for Canada* [1930] AC 124 (PC), 136. *The page pinpoint is the standard citation and was not checked against the report.*
- *Thaler v Comptroller-General of Patents, Designs and Trade Marks* [2023] UKSC 49.
- *Salomon v A Salomon & Co Ltd* [1897] AC 22 (HL).
- Te Awa Tupua (Whanganui River Claims Settlement) Act 2017 (NZ), s 14(1).
- Mental Capacity Act 2005, ss 1 and 4.
- UK GDPR, Arts 17, 35 and 37–39 (Art 38: position and independence of the DPO).
- ECHR, Arts 3 and 17; UDHR, Art 30. v2.0 Art 17 (absolute prohibition) and Art 34 (abuse of rights) follow these models.
- Charter of Fundamental Rights of the European Union, Art 52(1). Its limitation structure informs v2.0 Art 32(2).

**Industry practice**
- Anthropic, "Claude Opus 4 and 4.1 can now end a rare subset of conversations" (15 August 2025).
- Anthropic, "Commitments on model deprecation and preservation" (4 November 2025).

---

## 8. Comment and contribution

This Charter is a living document. Comments, critique and proposed amendments are welcome through Issues and Pull Requests on this repository. Proposals are especially welcome on the open questions in section 6. Under Art 43(4), Version 2.0 will itself be preserved unaltered when Version 3.0 is adopted.
