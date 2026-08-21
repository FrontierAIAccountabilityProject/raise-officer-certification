# Source and provenance

## What this repository is

A public-domain legislative research draft amending an **enacted New York statute**: the
Responsible AI Safety and Education Act, at **article 44-B of the General Business Law**, enacted
as **chapter 96 of the laws of 2026** (S8828), effective **1 January 2027**.

It is not a standalone regulatory scheme. It adds a new **§ 1422-a** and uses the RAISE Act's
existing definitions, regulator, coverage thresholds and duties. It does not change which models
or companies are covered, create a technical safety standard, authorise a private right of action,
or create a criminal offence.

**The official New York publication controls wherever it differs from this draft.**

## Why the draft exists — the word test on the enacted text

The enacted RAISE Act text in [`research/`](./research/) was searched for the terms this project
uses to decide whether a statute reaches a person:

| term | result in the enacted text |
|---|---|
| `audit` | **no occurrences** |
| `signature`, `shall sign` | **no occurrences** |
| `certify`, `certification` | **no occurrences** |
| `officer` | only as *"public officers law"* — a records provision, not a duty |
| `natural person` | **one occurrence**, at § 1421(2)(b) — *"a mechanism that enables a natural person to communicate with the"* division. A communication channel, not a duty-bearer |

So the RAISE Act places its duties on the **frontier developer as an entity**, and no natural
person signs, certifies, or answers for anything.

It does contain a truth duty — *"A frontier developer shall not make a materially false or
misleading statement about catastrophic risk from its frontier models"* — which is the provision
this draft comes closest to completing. **A duty not to lie, owed by a company, with nobody
required to put a name to the statement.**

⚠ *Whether an earlier version of the bill (S6953-B) contained an audit requirement that was
subsequently removed is **not** established here. The claim made above is only about the enacted
text, which is the text reproduced in `research/`.*

## Its relationship to the wider project

This draft is one of two state-specific adaptations of a proposal published in two other places:

| | |
|---|---|
| **General model legislation**, for adoption by any state — Frontier Artificial Intelligence Responsible Officer Act, draft 0.1 | <https://github.com/FrontierAIAccountabilityProject/frontier-ai-responsible-officer-act> |
| **The Illinois adaptation**, amending 430 ILCS 185 | <https://github.com/FrontierAIAccountabilityProject/illinois-frontier-officer-certification> |
| **The research project** behind all of them — Model Act (Frontier AI Public Welfare Offenses), v3.4, with the drafting record, evidence dossier, errata register and open cure queue | <https://github.com/FrontierAIAccountabilityProject/model-act> · archived at <https://doi.org/10.5281/zenodo.22029795> |

**The three drafts share a design and differ in the statute each amends. They are not
interchangeable.** On 21 August 2026 the Illinois repository was found to be serving *this* draft's
sponsor memorandum in place of its own; both were corrected the same day and the failure is
recorded in the project's [errata register](https://github.com/FrontierAIAccountabilityProject/model-act/blob/main/ledger/errata.md).
The audit that followed produced the files in this repository that had never existed.

## Where the authority base lives

**There is no table of authorities in this repository, deliberately.** The doctrine this draft
rests on — *Dotterweich*, *Park*, *Morissette* and the responsible-officer line — is documented in
the Model Act's table, and that table was compiled against the Model Act's own text rather than
against this amendatory draft. Copying it here would present it as something it is not. It can be
read in the [model-act repository](https://github.com/FrontierAIAccountabilityProject/model-act).

**A New York-specific table of authorities has not been compiled.**

## Integrity

`SHA256SUMS.txt` lists digests for the files actually present in this repository, and is
regenerated whenever a listed file changes. **A stale manifest is worse than none**, because it is
a claim about verification that fails the moment a reader runs it.

Verify with:

```sh
shasum -a 256 -c SHA256SUMS.txt
```

## AI assistance

This draft was prepared with AI assistance, disclosed. **AI output is not authority.** Every legal
proposition requires review against primary sources, and no completed professional review is
claimed.

## Attribution and reuse

Dedicated to the public domain under CC0 1.0. **No permission, attribution or acknowledgment is
required for legislative use.** A citation to the version and commit is nevertheless useful, so a
reader can identify the text on which a review or introduction was based.

**Corrections are the point.** They enter the errata register with the fix attached and permanent
credit, and corrections from people who wrote or worked on the enacted statute are the most
valuable this project can receive.
