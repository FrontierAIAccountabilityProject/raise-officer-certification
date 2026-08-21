# RAISE Officer Certification Amendment

New York's RAISE Act places transparency, risk-assessment, framework, and incident-reporting
duties on large frontier AI developers. It does not require a natural person controlling a
deployment to sign for the developer's compliance. This public-domain research draft supplies
that missing signature.

The proposal adds a new § 1422-a to Article 44-B of the New York General Business Law. It uses the
RAISE Act's existing definitions, regulator, duties, and coverage thresholds rather than creating
a separate AI regulatory system.

## What the amendment would do

- Require a certification or acknowledgment of material noncompliance before or concurrently
  with deployment of a new or substantially modified frontier model.
- Apply prospectively to covered models already deployed or in extensive internal use when the
  amendment takes effect.
- Require an annual certification or acknowledgment.
- Require personal signatures from the developer's highest executive, the highest executive of
  an ultimately controlling affiliate, the senior officer responsible for the frontier AI
  framework, and any additional natural person with final material decision authority over the
  deployment or extensive internal use.
- Require reasonable inquiry, adequate records, and reporting and escalation systems. Supporting
  work may be delegated; the signer's duty may not.
- Create a searchable public register identifying the developer, model, filing, and required
  signers while permitting lawful redaction of protected technical information.
- Permit civil enforcement against a required signer for failure to exercise due care in that
  person's own duties.
- Require an individual penalty to be paid personally, without corporate indemnification,
  insurance, reimbursement, or compensation designed to offset it.

## Who it reaches

The draft follows practical authority rather than title alone. A person cannot retain final power
through an affiliate, trust, voting arrangement, contract, committee, or unconventional corporate
structure while leaving the statutory signature chair empty.

Title, seniority, technical expertise, access, advice, and ministerial implementation do not by
themselves create signer status. Engineers, advisers, contractors, and ordinary employees who lack
final material decision authority are excluded.

Company and individual enforcement remain separate. A company penalty does not satisfy an
individual penalty, and company noncompliance does not automatically establish personal
liability. The Attorney General must prove that the signer failed to exercise due care in a duty
within that signer's authority.

## What it would not do

The proposal would not change the RAISE Act's model or revenue thresholds, regulate ordinary AI
systems, create a new regulator or technical safety standard, authorize a private right of action,
or create a new criminal offense. Its Penal Law § 210.45 notice uses New York's existing
false-written-statement mechanism.

## What the enacted Act does not contain

Searching the enacted text reproduced in [`research/`](./research/) — chapter 96 of the laws of
2026 — returns **no occurrence of `audit`, `signature`, `shall sign`, `certify` or
`certification`.** *Officer* appears only as "public officers law", a records provision. *Natural
person* appears once, describing a mechanism for someone to communicate with the division, not a
person who owes anything.

The Act does bar a developer from making "a materially false or misleading statement about
catastrophic risk from its frontier models" — **a duty not to lie, owed by a company, with nobody
required to put a name to the statement.** That is the provision this draft completes.

## Read the draft

- [`bill_text.md`](./bill_text.md) / [`bill_text.pdf`](./bill_text.pdf) — complete amendatory text
- [`PLAIN_LANGUAGE_GUIDE.md`](./PLAIN_LANGUAGE_GUIDE.md) — provision-by-provision explanation
- [`SPONSOR_MEMO.md`](./SPONSOR_MEMO.md) — concise legislative handoff
- [`SOURCE_AND_PROVENANCE.md`](./SOURCE_AND_PROVENANCE.md) — what this amends, what the word test
  returned, and where the authority base lives
- [`research/`](./research/) — enacted RAISE Act source material used for the amendment
- [`SHA256SUMS.txt`](./SHA256SUMS.txt) — digests for every file here; verify with
  `shasum -a 256 -c SHA256SUMS.txt`

## Status and contact

Research draft v0.2, 20 August 2026. Not introduced or enacted. Not legal advice. Drafted with AI
assistance disclosed and published for review and correction.

Contact: `FrontierAIAccountabilityProject@proton.me`

Maintained by the **Frontier AI Accountability Project**. Released into the public domain; no
permission, attribution, or acknowledgment is required for legislative use.
