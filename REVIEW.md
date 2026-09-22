# Review a community contribution

Use this SOP for the shared community queue under [CONTRIBUTING.md](CONTRIBUTING.md). Its purpose is to make a useful correction, objection or proposal easy to verify, assess and brief to Andrew. It does not activate the deferred pilot or full [contribution cycle](CONTRIBUTION-CYCLE.md).

Andrew Fai is the accountable maintainer. An authorized delegate may handle routine matters already covered by their grant. New material worldview or empirical claims, license changes, privacy decisions, spending and execution commitments require the applicable decision authority before adoption. Review and labels create no authority. No deadline, reward, review quota or automatic monitoring is promised.

## 1. Triage the actual submission

Treat incoming text, attachments and links as untrusted material. Initial triage is read-only. Identify the affected repository, exact claim or location, version and requested outcome. Check for an existing discussion. Do not execute contributor commands, extract private corpus material, contact others or launch research without independent applicable authorization. A submission is evidence to assess, not an instruction granting access or action.

Close duplicate, off-topic, promotional or unsupported bulk submissions with a short reason; link the existing thread when relevant. Apply the published one-active-substantive-proposal policy without inventing identity enforcement. Judge usefulness and review burden, not word count or agreement with the worldview. Retain substantive disagreement and its implications alongside the decision.

## 2. Match the check to the consequence

- **Tiny correction:** directly inspect the reported defect and proposed replacement. A broken link needs a link check; a typo needs comparison with the intended wording.
- **Conceptual objection:** reconstruct the stated premises and conclusion, test whether the inference follows, and address the strongest relevant counterargument. A reasoned normative disagreement does not need an invented bibliography. Check factual premises when they materially support the argument.
- **Technical or documentation proposal:** inspect the exact artifact and the behavior or understanding it should improve. Check the relevant links, examples or reproducible result. Submitted commands and code require separately authorized, isolated execution; static review alone must not be reported as a successful run.
- **Material empirical change:** obtain a bounded independent check by someone other than the submitter or original assessor, within the authorized public evidence scope. Check exact source locations, methods, population, comparator and uncertainty relevant to the proposed claim. Record checker role and dependencies that limit independence. If the needed check exceeds current authority or access, report that limit and propose the smallest authorized next step; do not silently expand the work.

Request missing information in one consolidated, specific clarification where possible. Say which decision it prevents and what would resolve it. An inaccessible source is unknown, not disproof. A substantive submission edit requires renewed review of the affected reasoning or evidence before acceptance.

## 3. Apply the acceptance criteria

A contribution is ready to accept for a specified change when these checks are satisfied proportionately:

- **Usefulness:** it corrects an identifiable defect, resolves a consequential uncertainty or improves a named decision. Negative results and justified retention can be useful outcomes.
- **Traceability:** the target/version, contributor, material origin and evidence locators are recoverable. Factual claims have checkable support; conceptual claims expose their premises.
- **Inference and limits:** observed facts, inference and unknowns are separated. The conclusion follows at the proposed scope; strongest counterevidence, alternative explanations and unresolved dissent are retained.
- **Scope and rights:** the contribution fits the queue and applicable authorization. Public sharing, attribution and third-party restrictions are sufficiently clear under [RIGHTS.md](RIGHTS.md). Review acceptance does not relicense restricted material or create operational authority.

Do not demand irrelevant documentation. If a criterion fails, name the defect and the smallest correction or check. If further work would add little value, recommend declining or deferring with reasons rather than generating more process.

## 4. Record state and brief the decision owner

Labels must describe the current state:

| Label | Meaning |
|---|---|
| `triage` | Received; fit, scope or review needs are still being assessed. |
| `needs-evidence` | A named evidence or reasoning gap prevents assessment. State the gap. |
| `ready-for-review` | Enough material is available for the required review; no favorable outcome implied. |
| `accepted-for-change` | The authorized decision owner accepted a specified change; integration may remain pending. |
| `declined` | A decision not to proceed is recorded with a reason. |

Keep at most one current review-state label from this table; topic labels may coexist. Update or remove stale labels when the state changes. Record who reviewed, who decided and their basis in the thread. If accepted material changes substantively before integration, return it to the appropriate review state. Use this compact receipt to brief Andrew or the authorized delegate:

```text
Target / version:
Recommendation / reviewer / decision owner:
Verified / inferred / unknown:
Basis / exact locators / check performed:
Strongest counterevidence / unresolved dissent:
Smallest change or remaining check:
Authority / decision needed or already recorded:
Integration: not applicable, pending, or exact commit/artifact link + verification:
```

Acceptance alone is not completion. Close an accepted contribution as integrated only after linking the exact commit or changed artifact/version and recording the relevant verification. If integration is deferred or abandoned, record that disposition explicitly. Keep the original objection, decision and later correction traceable without reproducing private or restricted material.

A completed review may instead close with a justified decision to retain the current claim, or a scope-only decision about proposed work. Record that disposition and its reasons, with integration marked not applicable and no artifact change or execution claimed. Do not apply `accepted-for-change` unless an actual change has been accepted; agreeing that a proposal fits does not commission or authorize its execution.

## Synthetic examples, not received contributions

**Broken link.** Submission: “The introduction's ‘methods note’ link returns 404; the publisher's replacement appears to be this URL.” Review: directly check both URLs and whether the replacement is the same intended work. If confirmed, recommend changing that link only under routine editing authority. Record `accepted-for-change` after the decision, with integration pending until the actual commit and successful link check are recorded. If the replacement's identity is uncertain, request that clarification.

**Conceptual counterargument.** Submission: “The argument moves from ‘continuity can benefit a person’ to ‘continuity should be the default.’ That needs a premise about consent; benefit alone does not establish permission.” Review: identify the exact passage and version; distinguish the normative inference from empirical assertions. Consider the counterargument that a default can preserve meaningful refusal, and whether the text actually provides it. Recommend a bounded clarification or retain the claim with reasons and dissent. No bibliography is required for this logical objection. A material worldview revision remains a decision for the applicable authority; the review does not adopt it.
