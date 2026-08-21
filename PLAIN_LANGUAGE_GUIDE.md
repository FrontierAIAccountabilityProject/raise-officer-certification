# New York Frontier Artificial Intelligence Officer Certification Act - plain-language guide

**Guide to research draft v0.2 - 21 August 2026**

This guide explains the proposed New York bill in ordinary language. It quotes
the proposal clause by clause and then explains what each clause is intended to
do, who it affects, and what it does not do.

The quoted bill text remains the proposal. This guide is explanatory only. It
is not enacted law, an official interpretation, or legal advice. If this guide
and the proposal differ, [`bill_text.md`](./bill_text.md) controls within this
research project. Official New York publications control the existing law.

## The central idea

The proposal is designed to keep practical power and legal accountability in
the same place.

New York's existing RAISE Act places duties on the covered company. This bill
would preserve those company duties and add duties for identifiable human
beings. The highest executives and the people with final material authority
over a covered model would have to put their own names on the record after a
reasonable inquiry. If they breach their own duties, the Attorney General could
seek a civil penalty from them personally. The company could not pay, insure,
reimburse, or quietly replace that penalty through extra compensation.

The bill does not use wealth as a legal test. A rich investor is not covered
merely for being rich, famous, influential, or technically knowledgeable. But a
founder, controlling owner, trust participant, board member, or other person
cannot keep final practical power while escaping the statute merely by avoiding
an officer title or placing the formal deployment decision in a subsidiary,
committee, delegate, contractor, or artificial intelligence system. The test is
the office expressly named in the bill or the person's real decision authority.

That is also why the bill excludes ordinary engineers, researchers, advisers,
and employees who implement or recommend decisions but do not possess final
material authority. Responsibility follows the power to decide, prevent, halt,
restrict, or correct the covered conduct.

## The proposal in a few sentences

For each covered deployment, and once each year, a large frontier developer
would have to file either:

1. a certification that required work was completed and material compliance
   exists after reasonable inquiry; or
2. a truthful acknowledgment identifying material noncompliance and explaining
   remediation.

The document must be personally signed by the developer's highest executive,
the highest executive of any affiliate that ultimately controls the developer,
the senior officer responsible for the frontier AI framework who can stop a
noncompliant deployment, and any other natural person with final material
decision authority.

The filing, signer names, model, and filing type would enter a searchable public
register. Protected technical information could still be redacted. Supporting
work could be delegated; the signer's duty could not. Lack of actual knowledge
would not be a defense where a reasonable inquiry or adequate escalation system
would have revealed the facts.

The Attorney General could enforce a signer's own breach of duty. Liability
would not arise automatically because the company violated some other rule.
Individual penalties would have to remain individual, separate from company
penalties, and could be accompanied by an injunction or temporary
disqualification from a role carrying the same authority.

## The existing New York law underneath the proposal

The bill is a follow-on amendment to Article 44-B of the General Business Law,
created by New York's RAISE Act. It does not create a second frontier-AI regime.
It uses the RAISE Act's existing definitions, coverage thresholds, regulator,
frontier AI frameworks, transparency reports, internal-use reports, and
critical-safety-incident reports.

In broad terms, the existing Act covers a "large frontier developer": a
frontier developer that, together with its affiliates, had more than $500
million in gross revenues in the preceding calendar year. A "frontier model"
uses the existing training-compute threshold of more than 10^26 integer or
floating-point operations. The proposal does not lower either threshold.

This means the new personal duties are attached to the largest covered
developers and their most powerful decision-makers. The proposal does not
regulate ordinary AI systems, ordinary AI users, small developers below the
existing coverage rules, or downstream users merely because they use a model.

---

# Clause-by-clause explanation

## Title and description of the bill

> # Frontier Artificial Intelligence Officer Certification Act

**Plain English:** This is the proposal's descriptive title. "Officer
certification" refers to the requirement that identified natural persons sign
the compliance record. It does not mean that only a person formally titled
"officer" can be covered; later provisions also reach people with final
material decision authority regardless of title.

> **Research draft v0.2 — 20 August 2026**

**Plain English:** This identifies the version and date. "Research draft"
means the text has not been introduced, enacted, endorsed, or approved by New
York legislative counsel.

> AN ACT to amend the general business law, in relation to natural-person
> certification of transparency and reporting obligations applicable to large
> frontier developers.

**Plain English:** The bill would amend New York's General Business Law. Its
subject is personal certification of duties that already apply to large
frontier developers. "Natural person" means an actual human being, rather than
a corporation, board, committee, or other legal entity.

> THE PEOPLE OF THE STATE OF NEW YORK, REPRESENTED IN SENATE AND ASSEMBLY, DO
> ENACT AS FOLLOWS:

**Plain English:** This is New York's standard enacting language. It marks the
text that would become law if passed and signed.

## Section 1 - short title

> **Section 1. Short title.** This act shall be known and may be cited as the
> “frontier artificial intelligence officer certification act.”

**Plain English:** This gives the proposal a short legal name. It creates no
duty by itself.

## Section 2 - where the new duties would go

> **§ 2.** Article 44-B of the general business law is amended by adding a new
> section 1422-a to read as follows:

**Plain English:** Article 44-B is the existing RAISE Act framework. The bill
would place a new Section 1422-a inside that framework, rather than creating a
new agency or separate regulatory system.

> **§ 1422-a. Officer certification.**

**Plain English:** Everything that follows through subdivision seven belongs
to the proposed officer-certification section.

---

# Subdivision 1 - what must be filed and when

## 1(a) - a filing at deployment

> **1. Required submissions.**

**Plain English:** Subdivision one establishes the documents the covered
developer must file. Later subdivisions identify who must sign them and what
personal work must precede a signature.

> (a) Before or concurrently with deploying a new frontier model or a
> substantially modified version of an existing frontier model, a large
> frontier developer shall submit electronically to the office, in a form
> prescribed by the office, either:

**Plain English:** A filing is tied to the deployment decision. The company
cannot wait until long after release. The requirement applies both to a new
frontier model and to an existing model that has been changed enough to count
as substantially modified under the existing framework.

The existing state office chooses the electronic form. The developer must use
one of two routes: certify material compliance or acknowledge material
noncompliance. It cannot avoid filing by refusing to certify.

## 1(a)(i) - the compliance route

> (i) a written certification that, after reasonable inquiry:

**Plain English:** A certification cannot be based on a ceremonial signature,
an impression, or an unquestioned assurance from below. It must follow a
reasonable inquiry. Subdivision three later explains the signers' personal
duty to ensure that inquiry occurs.

> (A) the transparency report required by subdivision three of section
> fourteen hundred twenty-one of this article is complete and accurate;

**Plain English:** The signers must address the deployment transparency report
already required by the RAISE Act. They are certifying that it is materially
complete and accurate, rather than merely confirming that a document exists.

> (B) the assessments, mitigations, third-party evaluations, and other steps
> required by the large frontier developer’s frontier AI framework for the
> decision to deploy were completed or applied; and

**Plain English:** The signers must check whether the developer did the safety
work that its own frontier AI framework says is required for this deployment.
This includes relevant assessments, mitigations, and outside evaluations. The
proposal does not invent those technical standards; it makes named people sign
for whether the developer followed its existing framework.

> (C) the deployment materially complies with the applicable requirements of
> section fourteen hundred twenty-one of this article and with the large
> frontier developer’s frontier AI framework; or

**Plain English:** The certification covers material compliance with both the
existing statutory transparency requirements and the developer's own frontier
AI framework. "Materially" keeps trivial or inconsequential defects from being
treated as if they were major compliance failures.

The word "or" leads to the second filing route. If the signers cannot honestly
make this certification, the developer must use the acknowledgment route.

## 1(a)(ii) - the acknowledgment route

> (ii) a written acknowledgment identifying each material noncompliance,
> describing its nature and extent, and providing a remediation plan. An
> acknowledgment under this subparagraph shall not constitute compliance,
> validation, authorization to deploy, or a defense to any violation of this
> article.

**Plain English:** A signer is not forced to make a false certification. The
developer can instead state what is materially wrong, how extensive the
problem is, and how it plans to fix it.

But acknowledgment is disclosure, not permission. It does not legalize a
noncompliant deployment, prove that the model is safe, or erase an underlying
violation. This prevents the filing from becoming a "confess and ship anyway"
loophole.

**Why it matters:** A two-route system encourages truthful disclosure. If the
only permitted filing were a clean certification, a company facing a real
problem would have an incentive to conceal it or file nothing. The
acknowledgment creates an honest route onto the public record without granting
immunity.

## 1(b) - the annual filing

> (b) Beginning April fifteenth of the calendar year following the first full
> calendar year after this section takes effect, and annually thereafter, each
> large frontier developer shall submit either:

**Plain English:** Deployment filings are event-based. This paragraph adds a
yearly check across the developer's continuing conduct. The first annual filing
is due April 15 after the first complete calendar year under the new section,
then every April 15.

> (i) a written certification that, during the preceding calendar year, the
> large frontier developer materially complied with the applicable requirements
> of sections fourteen hundred twenty-one and fourteen hundred twenty-two of
> this article and with its frontier AI framework; or

**Plain English:** The annual certification looks backward over the previous
calendar year. It covers material compliance with the RAISE Act's transparency
requirements, its reporting requirements, and the developer's frontier AI
framework.

This keeps the signature obligation from ending on deployment day. A model may
remain in use, new information may arise, and incident-reporting or internal-use
duties may become relevant later.

> (ii) a written acknowledgment identifying each requirement with which the
> large frontier developer did not materially comply, describing the nature and
> extent of the noncompliance, and providing a remediation timeline or
> confirmation that remediation is complete.

**Plain English:** If the developer cannot truthfully certify the year, it must
identify each material failure, explain it, and state when it will be fixed or
that it has already been fixed.

The acknowledgment records the actual state of compliance. It is not a vague
statement that "issues occurred"; it must connect the noncompliance to the
requirements involved and describe its scope.

## 1(c) - models already deployed when the law begins

> (c) Existing deployments. On the effective date of this section, each large
> frontier developer that has a frontier model deployed or in extensive
> internal use, in whole or in part in this state, shall submit for each such
> model the certification or acknowledgment required by paragraph (a) of this
> subdivision. For purposes of paragraph (a) of this subdivision, continued
> deployment or extensive internal use of such a model on or after the effective
> date shall be treated as deployment of a new frontier model occurring on the
> effective date. No liability shall arise under this paragraph for conduct
> occurring before the effective date.

**Plain English:** The bill is not limited to models first released after it
takes effect. If a covered model is already deployed or extensively used
internally in New York, continued use on and after the effective date triggers
a prospective filing for that model.

The last sentence protects against retroactive liability under this paragraph.
The filing concerns the decision to continue covered conduct after the new law
starts; it does not punish conduct that was completed before the effective
date.

**Why it matters:** Without this paragraph, the signature system could miss the
most important current models for years, until they happened to be
"substantially modified" or replaced.

---

# Subdivision 2 - which human beings must sign

## The basic rule

> **2. Required signers.** Each certification or acknowledgment submitted
> pursuant to subdivision one of this section shall be signed personally by:

**Plain English:** The company is still responsible for filing, but a company
name or corporate signature is insufficient. The identified human beings must
sign personally. The following paragraphs deliberately combine named senior
roles with a practical-authority test.

## 2(a) - the developer's highest executive

> (a) the highest-ranking natural-person executive of the large frontier
> developer or, if the large frontier developer has no such executive, each
> natural person exercising the most senior executive or governance authority
> over the large frontier developer;

**Plain English:** The highest human executive of the covered developer must
sign. A developer cannot escape by using an unconventional structure with no
person formally called chief executive. In that case, every human being who
exercises the most senior executive or governance authority must sign.

This is the first "no empty chair" rule. Removing a familiar title does not
remove the obligation.

## 2(b) - the person at an affiliate that ultimately controls the developer

> (b) where an affiliate exercises ultimate authority to direct the management
> and policies of the large frontier developer, the highest-ranking
> natural-person executive of that affiliate or, if such affiliate has no such
> executive, each natural person exercising the most senior executive or
> governance authority over that affiliate;

**Plain English:** If the covered developer is a subsidiary or otherwise sits
under an affiliate that actually has ultimate authority over its management and
policies, the top human at that controlling affiliate must also sign.

Again, an unconventional structure cannot create an empty chair. If the
controlling affiliate has no conventional highest executive, the humans with
the most senior executive or governance authority must sign.

**Why it matters:** Formal corporate separation should not let the person at
the top keep ultimate authority while all accountability stops at a thin
operating subsidiary.

## 2(c) - the senior framework officer with stop authority

> (c) the most senior natural-person officer, other than a signer required by
> paragraph (a) or (b) of this subdivision, who has direct responsibility for
> implementation of the large frontier developer’s frontier AI framework and
> authority to prevent the deployment or extensive internal use of a frontier
> model that does not comply with that framework; and

**Plain English:** The senior person responsible for putting the frontier AI
framework into practice must sign if that person also has authority to stop a
noncompliant deployment or extensive internal use.

The person must have both direct framework responsibility and real stop
authority. A nominal safety title without the power to prevent deployment does
not satisfy this category. The person must also be different from the top
executive signers, so one signature does not collapse all roles into one.

## 2(d) - anyone else with final material deployment authority

> (d) each natural person, other than a signer required by paragraph (a), (b),
> or (c) of this subdivision, who, regardless of title, possesses or exercises
> final material decision authority concerning the deployment or extensive
> internal use of a frontier model of the large frontier developer through one
> or more of the following:

**Plain English:** Named offices may not capture every governance structure.
This paragraph reaches any additional human being who actually has final,
important decision authority over a covered model's deployment or extensive
internal use, regardless of title.

"Final" and "material" narrow the rule. It is aimed at meaningful decision
power, not every person who contributes work, gives input, or carries out a
decision. The following list explains the kinds of authority that count.

### 2(d)(i) - direct release and access decisions

> (i) deployment, expansion, release, or access decisions;

**Plain English:** This covers final authority over whether the model is
deployed, expanded, released, or made accessible. A person who can make or
block that decision cannot avoid the rule simply because their title does not
say "chief executive" or "AI safety officer."

### 2(d)(ii) - control through resources or risk policy

> (ii) budgets, compute, infrastructure, or risk policy materially affecting
> such deployment or use;

**Plain English:** Deployment power can be exercised indirectly. A person may
control the outcome through the budget, computing resources, infrastructure,
or risk policy that determines whether and how a deployment can proceed. If
that authority is final and materially affects deployment, it can make the
person a signer.

Ordinary purchasing, technical administration, or budget work is not enough by
itself. The opening language still requires final material decision authority.

### 2(d)(iii) - control over the people who decide

> (iii) appointment, removal, direction, or supervision of persons exercising
> authority described in subparagraph (i) or (ii) of this paragraph; or

**Plain English:** A person can possess decisive power by choosing, removing,
directing, or supervising the people who make release or resource decisions.
The bill looks through that additional layer when the person's authority is
final and material.

This prevents an ultimate decision-maker from preserving control by causing a
subordinate to perform the final formal act.

### 2(d)(iv) - ownership and governance arrangements that confer practical power

> (iv) ownership, voting, contractual, governance, trust, or other rights
> conferring practical power to prevent, halt, restrict, or correct such
> deployment or use.

**Plain English:** Legal and practical control can arise through shares,
special voting rights, contracts, board or governance rights, trusts, or other
arrangements. If those rights give a human being practical power to stop,
limit, or correct deployment, that authority can trigger the signature duty.

This is the provision most directly concerned with powerful founders,
controlling owners, and other people whose real authority may not appear in a
conventional job title. It does not make them liable merely for owning wealth.
It reaches them where their rights provide the practical power described here.

## How authority is traced, and what does not count

> For purposes of paragraph (d) of this subdivision, authority may be held or
> exercised directly or indirectly, individually or in concert with others, and
> through any affiliate, entity, trust, or arrangement. The following, standing
> alone or in combination only with each other, do not constitute authority
> under paragraph (d) of this subdivision: title, office, seniority, or status;
> professional credentials or technical ability; access to systems, model
> weights, compute, or infrastructure; the ministerial execution,
> implementation, or communication of a decision made by another; or the
> provision of advice, analysis, or recommendation to a person holding decision
> authority. Authority under paragraph (d) of this subdivision is authority to
> decide, not merely capacity to act. Substance controls over title.

**Plain English:** The state may follow real authority through layers. A person
cannot avoid the test by exercising power indirectly, sharing it with others,
or placing it inside a company, affiliate, trust, or contractual arrangement.

At the same time, the paragraph creates a strong boundary around ordinary
workers and advisers. None of the following is enough without actual final
material decision authority:

- an impressive title, senior status, or office;
- expertise or the technical ability to do something;
- access to systems, weights, compute, or infrastructure;
- carrying out or communicating somebody else's decision; or
- giving advice, analysis, or recommendations to the person who decides.

The distinction is between being able to perform an act and having authority
to decide whether it will happen. An engineer may have the technical capacity
to release a model but no lawful authority to decide on release. Conversely, a
founder or controlling person may lack day-to-day technical access but still
hold the deciding power. The bill follows the latter power.

## Shared roles and the second no-empty-chair rule

> Where two or more natural persons jointly occupy or exercise the rank or
> authority described in paragraph (a), (b), or (c) of this subdivision, each
> such person shall be a required signer. No large frontier developer or
> affiliate may, through a vacancy, allocation of authority among multiple
> persons, use of a board or committee, or other form of organization, leave
> this section without an obligated natural person.

**Plain English:** If a top role or relevant authority is shared, every person
sharing it signs. A company cannot divide a role into pieces so that no single
person appears to meet the rule. It also cannot point to a vacant office, a
board, a committee, or an unusual organization and claim that no human being is
obligated.

The provision does not make every board or committee member a signer
automatically. It says the organization cannot use collective or fragmented
authority to produce an empty chair. The underlying signer categories still
determine which natural people are covered.

## Personal signature, nondelegation, and retained authority

> Each signer shall sign in an individual capacity. A signature by an entity,
> board, committee, representative, or delegate shall not satisfy this
> subdivision. The duties imposed upon a signer by this section may not be
> delegated. No appointment of a safety officer, compliance officer, committee,
> subsidiary, contractor, artificial intelligence system, or other intermediary
> shall relieve a required signer who retains authority material to a duty
> imposed by this section.

**Plain English:** The signature must belong to the human being, in that
person's individual capacity. A corporate signature, board approval, committee
resolution, representative, or delegate cannot replace it.

Supporting work can still be assigned to appropriate staff and experts, as
subdivision three explains. What cannot be transferred is the signer's own duty
to ensure reasonable inquiry and respond within the signer's authority.

Most importantly, a person who retains material authority does not escape by
appointing a safety or compliance officer, using a committee or subsidiary,
hiring a contractor, or putting an AI system in the decision chain. The person
may delegate work; the person cannot keep the power and delegate away the legal
consequence attached to that power.

## Required signer even when the filing is omitted

> For purposes of this section, “required signer” means each natural person
> required to sign pursuant to this subdivision, whether or not the required
> submission was made.

**Plain English:** A covered person does not cease to be a required signer
because the company files nothing. Otherwise, omitting the entire filing could
become a route around individual enforcement.

---

# Subdivision 3 - each signer's personal duty

## 3(a) - ensure a reasonable, documented inquiry

> **3. Personal duty of inquiry and response.**

**Plain English:** The signature is not the whole duty. Each required signer
has a personal obligation concerning how the facts are investigated and how
material noncompliance is addressed.

> (a) Before signing a certification or acknowledgment, each person required to
> sign under subdivision two of this section shall exercise due care to ensure
> that a reasonable inquiry has been conducted. The inquiry shall be based upon
> data and documentation sufficient to determine accurately and demonstrate the
> matters addressed by the submission.

**Plain English:** Each signer must act with due care to ensure a real inquiry
occurred before signing. The inquiry needs enough data and documentation both
to reach an accurate conclusion and to show later how that conclusion was
reached.

This is not strict liability for every bad outcome. The legal question is
whether the signer used due care to ensure a reasonable inquiry into the
matters being certified or acknowledged.

## 3(b) - experts may help, but reliance must be reasonable

> (b) Employees, advisers, and qualified experts may perform work supporting
> the inquiry, but a required signer may rely upon their information only where
> such reliance is reasonable under the circumstances and the signer has no
> reason to believe that the information is materially false or incomplete.
> Delegation of supporting work shall not relieve a required signer of the
> personal duty imposed by this subdivision.

**Plain English:** Senior decision-makers are not expected to run every test or
personally collect every record. Employees, advisers, and experts can do that
work.

The signer must, however, have a reasonable basis for relying on it. A signer
cannot ignore warning signs that the information is materially false or
incomplete. Saying "the team handled it" is not enough where reliance was
unreasonable or the signer failed to ensure the inquiry occurred.

## 3(c) - respond to material noncompliance using actual authority

> (c) When material noncompliance is identified, or would have been identified
> through an inquiry satisfying paragraph (a) of this subdivision, each
> required signer shall exercise due care, using meaningful measures within
> that signer’s authority individually or in combination with others, to cause
> prompt remediation and to prevent, halt, or restrict any deployment or
> extensive internal use to which the noncompliance relates where its
> continuation would violate this article or the large frontier developer’s
> frontier AI framework.

**Plain English:** The duty does not end when a problem reaches the signer's
desk. If material noncompliance is found, or a proper inquiry would have found
it, the signer must use meaningful measures that are actually available within
that person's authority.

Depending on the person's power and the facts, this may include causing prompt
remediation or preventing, halting, or restricting a deployment or extensive
internal use that would remain unlawful or violate the developer's framework.
Different signers may need to act together where authority is shared.

The bill does not demand an act outside the signer's authority. It does prevent
a person from retaining meaningful power and remaining passive when due care
requires its use.

## 3(d) - ignorance and delegation are not safe harbors

> (d) Lack of actual knowledge shall not constitute a defense to a violation of
> this subdivision where the relevant facts would have been disclosed by the
> reasonable inquiry required by paragraph (a) of this subdivision or by
> reporting and escalation systems that due care required the signer to
> establish or maintain. A required signer may not avoid a duty imposed by this
> section through delegation, deliberate avoidance of material information, or
> failure to establish reasonable means by which such information would reach
> the signer.

**Plain English:** A signer cannot create ignorance and then rely on that
ignorance. "I did not know" is unavailable where a reasonable inquiry would
have revealed the facts, or where due care required internal reporting and
escalation systems that would have brought the facts to the signer.

This also addresses deliberate avoidance. A signer cannot preserve plausible
deniability by delegating everything, refusing material information, or failing
to create reasonable channels through which serious information can reach the
top.

The standard is not omniscience. It is what a reasonable inquiry and due-care
reporting system would have disclosed. The provision therefore connects
responsibility to the information architecture a powerful decision-maker has a
duty to establish, rather than to whether somebody can later prove the person
read a particular email.

---

# Subdivision 4 - signatures, evidence, and the public register

## 4(a) - identify the signer and warn about false written statements

> **4. Form and supporting records.**

**Plain English:** Subdivision four controls the form of the filing, the
records behind it, and what becomes public.

> (a) Each certification or acknowledgment submitted under this section shall
> identify each required signer by name, title, and signing capacity and shall
> bear the following notice immediately above each signature:

**Plain English:** The filing must name every required signer, give the
person's title, and explain the capacity in which the person signs. "Signing
capacity" matters because a job title alone may not reveal the source of the
person's duty.

> “False statements made herein are punishable as a class A misdemeanor
> pursuant to section 210.45 of the penal law.”

**Plain English:** This is New York's existing false-written-statement notice.
The proposal does not create a new crime. It places the existing statutory
warning directly above each personal signature so the filing is not treated as
casual corporate communications.

The notice concerns knowingly false written statements under the existing
Penal Law mechanism. It is distinct from the new civil due-care enforcement in
subdivision five.

## 4(b) - preserve what supported the filing and who held power

> (b) A large frontier developer shall preserve for five years after submission
> all data, reports, assessments, communications, schedules, and other
> documentation materially relied upon in preparing a certification or
> acknowledgment under this section. The large frontier developer shall also
> preserve for the same period records sufficient to identify each required
> signer and the basis upon which that person was or was not treated as a
> required signer, including organizational charts, delegations of authority,
> board or committee resolutions, and voting, contractual, governance, or trust
> arrangements materially relevant to authority described in subdivision two
> of this section. Such records shall be made available to the office or the
> attorney general upon lawful request.

**Plain English:** The company must keep the evidence behind each filing for
five years. That includes the technical and compliance records materially
relied upon and a governance record showing who had the relevant authority.

The second category is essential to the bill's practical-power test. A company
must preserve organizational charts, delegated powers, board or committee
decisions, voting rights, contracts, governance documents, and trust
arrangements that show why a person was or was not treated as a signer.

The office and Attorney General can obtain the records through a lawful
request. The provision does not make all supporting material public.

## The preservation hold

> From the time a large frontier developer or required signer has notice of a
> critical safety incident, investigation, lawful preservation demand, or
> judicial or administrative proceeding to which records described in this
> paragraph are reasonably relevant, such records shall be preserved until the
> final conclusion of the incident response, investigation, demand, or
> proceeding, including any review or appeal, notwithstanding expiration of the
> five-year period.

**Plain English:** Five years is a minimum, not permission to destroy relevant
evidence during a live matter. Once the company or a signer knows of a relevant
critical incident, investigation, preservation demand, or proceeding, the
records must be kept until the matter and any appeal are finished.

This prevents the ordinary retention clock from expiring while investigators,
agencies, or courts are still using the records.

## 4(c) - the agency cannot design away the signatures

> (c) The office shall prescribe forms and procedures necessary to implement
> this section but shall not permit a form, procedure, or electronic submission
> method to dispense with any required signer or diminish the personal duties
> imposed by this section.

**Plain English:** The office can design practical forms and electronic filing
procedures. It cannot use that administrative authority to remove a required
signer, replace individual signatures with one corporate filing, or weaken the
personal duties enacted by the legislature.

## 4(d) - the filing is public, with limited redactions

> (d) Each certification or acknowledgment submitted under this section shall
> be a public record and shall be made available for public inspection and
> copying. The office may redact only information for which withholding is
> necessary to protect trade secrets, cybersecurity, public safety, national
> security, or another interest protected from disclosure by law. The office
> shall not redact the identity of the large frontier developer; the name or
> version of the frontier model to which the submission relates; the reporting
> period; whether the submission is a certification or acknowledgment; the
> filing date; or any required signer’s name, title, signing capacity,
> attestation, and signature or electronic equivalent.

**Plain English:** The certification or acknowledgment is public. Sensitive
technical or legally protected information can be redacted where withholding
is necessary, but the accountability facts cannot disappear behind those
redactions.

The public must still be able to see:

- which developer filed;
- which model or model version is involved;
- the reporting period;
- whether management certified or acknowledged noncompliance;
- the filing date; and
- every required signer's name, role, attestation, and signature.

This is what turns an internal compliance process into a public signature. The
people with the relevant authority are visible beside the decision.

## 4(e) - a searchable public officer-signature register

> (e) Within ten business days after receiving a certification or
> acknowledgment, the office shall publish the public copy on its website and
> enter it in a searchable public register. The register shall permit the
> public to identify submissions by large frontier developer, frontier model,
> required signer, submission type, and filing date. The unredacted submission
> and supporting records shall remain available to the office and the attorney
> general and shall be exempt from public disclosure only to the extent
> permitted by law.

**Plain English:** The office must publish the public version within ten
business days and place it in a register that can be searched by company,
model, person, filing type, and date.

This is more than a folder of PDFs. A member of the public, legislator,
journalist, researcher, investor, worker, or regulator should be able to answer
the question: *Who signed for this model, what did they file, and when?*

The office and Attorney General retain access to the unredacted filing and
supporting records. Public disclosure protections still apply only to the
extent allowed by existing law.

---

# Subdivision 5 - individual civil enforcement

## 5(a) - the Attorney General may sue a signer for that person's duty

> **5. Individual enforcement.**

**Plain English:** This subdivision creates civil enforcement against the
human signer. It is separate from enforcement of the company's existing
obligations.

> (a) The attorney general may bring a civil action against a required signer
> who violates a duty imposed upon that signer by this section.

**Plain English:** The New York Attorney General may bring the case. The cause
of action is the signer's violation of a duty that this new section personally
imposes on that signer.

The bill does not create a private right for any member of the public to sue.
It gives enforcement responsibility to the Attorney General.

## 5(b) - individual liability is not automatic company liability

> (b) A required signer shall not be liable under this section solely because
> the large frontier developer violated another provision of this article. To
> establish a violation of subdivision three of this section, the attorney
> general shall prove that the required signer failed to exercise due care in
> performing a duty within that signer’s authority.

**Plain English:** A company violation does not automatically become a
personal violation. The Attorney General must prove the individual's own
failure of due care in carrying out a duty within that person's authority.

This is the bill's central fairness boundary. It attaches consequence to the
person's own conduct and power, rather than imposing liability merely because
the person was associated with a company where something went wrong.

## 5(c) - truthful acknowledgment is not itself liability

> (c) A truthful acknowledgment of noncompliance submitted pursuant to
> subdivision one of this section shall not, standing alone, establish personal
> liability. Nothing in this paragraph limits consideration of the facts
> disclosed, the signer’s conduct, or the signer’s compliance with subdivision
> three of this section.

**Plain English:** Truthfully admitting material noncompliance is not, by
itself, proof that the signer violated a personal duty. This protects the
honest filing route and reduces the incentive to conceal problems.

The acknowledgment is not immunity. The Attorney General may still consider
the disclosed facts, what the signer did or failed to do, and whether the
signer met the duties of inquiry and response.

## 5(d) - individual civil penalties and ability to pay

> (d) A court may impose upon a required signer found to have violated this
> section a civil penalty not exceeding two hundred fifty thousand dollars for
> a first violation and one million dollars for each subsequent violation. In
> determining the amount, the court shall consider the nature, circumstances,
> extent, and gravity of the violation; the signer’s degree of culpability and
> authority; any prior violations; efforts to prevent or remediate the
> violation; and the signer’s ability to pay.

**Plain English:** The maximum individual penalty is $250,000 for a first
violation and $1 million for each later violation. The court chooses the actual
amount within those caps.

The court must consider how serious and extensive the violation was, how
culpable and powerful the signer was, the person's history, prevention and
remediation efforts, and ability to pay. The same fixed sum should not be
treated as equally meaningful for every defendant. Ability to pay lets the
court calibrate within the statutory maximum, although the maximum itself
remains fixed.

The penalty is civil, not imprisonment. Subdivision six determines who must
actually bear it.

---

# Subdivision 6 - the individual consequence cannot be shifted back to the company

## 6(a) - personal payment and no indemnification or insurance

> **6. Personal payment; no indemnification.**

**Plain English:** This subdivision closes the route by which an apparently
individual penalty could become just another company expense.

> (a) A civil penalty imposed upon a required signer pursuant to subdivision
> five of this section shall be paid by that signer personally. No large
> frontier developer, affiliate, insurer, employer, or other person shall
> directly or indirectly pay, reimburse, indemnify, insure, or otherwise
> satisfy any part of such penalty.

**Plain English:** The person against whom the court imposes the civil penalty
must personally bear it. The developer, parent or affiliate, employer,
insurance company, or anybody else cannot pay it directly or indirectly.

This is the proposal's clearest rule against hiding behind a company fine. The
company may face its own separate penalty, but it cannot convert the
individual's penalty into another corporate operating cost.

## 6(b) - no bonus or transfer designed to replace the money

> (b) No person shall provide, and no required signer shall solicit, accept, or
> retain, any increase in compensation, bonus, loan, forgiveness of
> indebtedness, distribution, gift, or other transfer of value whose purpose or
> predominant effect is to offset a penalty described in paragraph (a) of this
> subdivision.

**Plain English:** The company or another person cannot evade the personal
payment rule through a matching bonus, pay increase, loan, forgiven debt,
distribution, gift, or other transfer. The signer also cannot ask for, accept,
or keep such an offset.

The rule looks at purpose or predominant effect. Calling the replacement money
something other than "reimbursement" does not solve the problem.

## 6(c) - prohibited arrangements are void and recoverable

> (c) Any agreement or arrangement contrary to this subdivision is void and
> unenforceable. The attorney general may recover a prohibited payment or
> transfer from the person providing it or the required signer receiving it.
> Such recovery shall not reduce or satisfy the required signer’s underlying
> penalty.

**Plain English:** A promise to cover the penalty cannot be enforced. If money
is nevertheless transferred, the Attorney General may recover it from the
provider or the signer.

Recovering the prohibited offset does not pay down the original penalty. The
signer still owes that penalty personally. Otherwise, attempting the evasion
could partially succeed even after it was discovered.

## 6(d) - defense costs remain permitted

> (d) This subdivision does not prohibit payment or advancement of reasonable
> costs of defense. It does not prohibit indemnification of a person upon whom
> no individual penalty is finally imposed.

**Plain English:** A company may still pay reasonable legal defense costs. It
may also indemnify someone who ultimately receives no individual penalty.

The restriction is aimed at shifting a finally imposed personal penalty, not at
denying a defense or treating an accusation as if it were already a judgment.

## 6(e) - no retroactive penalty-payment rule

> (e) This subdivision applies only to a penalty imposed for conduct occurring
> on or after the effective date of this section.

**Plain English:** The no-indemnification rule applies to penalties based on
conduct after the law takes effect. It does not retroactively change who bears
a penalty for earlier conduct.

## 6(f) - transition for existing insurance and indemnification arrangements

> (f) No liability shall arise under this subdivision solely from entering into
> an insurance contract or other indemnification arrangement before the
> effective date of this section or maintaining such a contract or arrangement
> during the transition period described in this paragraph. Such a contract or
> arrangement may be maintained only until the earliest of its renewal,
> expiration, or material amendment, or one year after the effective date of
> this section. Nothing in this paragraph authorizes any payment,
> reimbursement, indemnification, insurance benefit, compensation adjustment,
> or other transfer of value to satisfy or offset a penalty imposed for conduct
> occurring on or after the effective date of this section.

**Plain English:** Existing contracts are not unlawful merely because they were
signed before the new rule. They receive a limited transition period ending at
the earliest renewal, expiration, material amendment, or one year after the
effective date.

But the transition concerns maintenance of the old contract, not payment of a
new penalty. Even during that period, nobody may use the arrangement to satisfy
or offset a penalty imposed for post-effective-date conduct.

This reduces retroactivity concerns while preserving the substantive rule that
new individual consequences remain individual.

---

# Subdivision 7 - court orders and temporary disqualification

## 7(a) - injunctions and model-specific restraint

> **7. Injunctive relief and disqualification.**

**Plain English:** Money is not the only available remedy. A court may also
order compliance, address an ongoing problem, and in more serious cases
temporarily remove a violator from a covered role.

> (a) In an action brought pursuant to subdivision five of this section, the
> court may grant appropriate injunctive or other equitable relief, including
> requiring a compliant submission, requiring remediation of an identified
> violation, or restraining the deployment or extensive internal use of a
> frontier model in this state until the requirements of this section are
> satisfied.

**Plain English:** In the Attorney General's individual-enforcement case, a
court may order the missing or defective filing to be corrected, require
remediation, or temporarily restrain the relevant deployment or extensive
internal use in New York until the certification requirements are met.

This is model- and compliance-specific relief. It is not a general ban on AI or
on all company operations.

## 7(b) - temporary disqualification from a covered role

> (b) Upon finding that a required signer knowingly violated this section, or
> committed two or more violations within five years, the court may prohibit
> that person, for a period not exceeding five years, from serving in an office
> or exercising authority that would make the person a required signer for a
> large frontier developer.

**Plain English:** For a knowing violation, or at least two violations within
five years, a court may bar the person for up to five years from holding a role
or exercising authority that would again make that person a required signer.

This consequence follows authority, not title. A person cannot satisfy the
order by changing job labels while continuing to exercise the same covered
power.

Disqualification is discretionary, not automatic. The court "may" order it,
and paragraph (d) requires a proportionality analysis first.

## 7(c) - the company cannot leave a disqualified person in control

> (c) A large frontier developer shall not deploy or extensively use a frontier
> model internally in this state while a person subject to an order under
> paragraph (b) of this subdivision continues to hold an office or exercise
> authority that would make that person a required signer.

**Plain English:** A disqualification order has operational force. The company
cannot continue covered deployment or extensive internal use in New York while
the barred person remains in a role carrying the same authority.

The person must actually leave the covered office or relinquish the covered
power. A paper change that leaves practical authority intact would not satisfy
the rule.

## 7(d) - factors the court must weigh

> (d) Before ordering disqualification, the court shall consider the gravity
> and duration of the violation, the person’s degree of culpability and
> practical authority, efforts to remediate the violation, the likelihood of
> recurrence, and whether lesser relief would adequately protect the public.

**Plain English:** The court must consider proportionality. It looks at the
seriousness and length of the violation, how blameworthy and powerful the
person was, efforts to fix the problem, whether it is likely to happen again,
and whether a less severe remedy would be enough.

This protects against automatic removal for a minor or isolated failure while
preserving disqualification for serious, repeated, or knowing misconduct by a
person with substantial practical authority.

---

# Section 3 - company penalties remain separate

## The existing company-enforcement provision is expanded

> **§ 3.** Subdivision one of section fourteen hundred twenty-seven of the
> general business law, as added by chapter ninety-six of the laws of two
> thousand twenty-six, is amended to read as follows:

**Plain English:** Section 1427 is the RAISE Act's existing civil-penalty
section. This proposal would amend its first subdivision so that the company
can be penalized for failing to make the new filing or violating a company duty
created by the new section.

> **1.** The attorney general may bring a civil action to recover a civil
> penalty in an amount not to exceed one million dollars for a first violation
> and in an amount not to exceed three million dollars per subsequent
> violation, determined based on the severity of the violation, where a large
> frontier developer fails to publish or transmit a compliant document required
> to be published or transmitted under this article, makes a statement in
> violation of subdivision four of section fourteen hundred twenty-one of this
> article, fails to report an incident as required by section fourteen hundred
> twenty-two of this article, fails to submit a certification or acknowledgment
> required by section fourteen hundred twenty-two-a of this article, otherwise
> violates a duty imposed upon the large frontier developer by such section, or
> fails to comply with its own frontier AI framework.

**Plain English:** The Attorney General retains the existing entity-level civil
case and penalties: up to $1 million for a first violation and $3 million for
each later violation, calibrated to severity. The list of company violations
would now include failure to submit the required certification or
acknowledgment and breach of another company duty under new Section 1422-a.

This paragraph concerns the developer as an entity. It does not by itself make
an individual liable.

## The company cannot absorb the individual's penalty

> A penalty imposed upon a large frontier developer pursuant to this
> subdivision shall be separate from, and shall not satisfy or reduce, any
> penalty imposed upon a required signer pursuant to section fourteen hundred
> twenty-two-a of this article.

**Plain English:** Company and individual penalties are separate. Paying the
company's penalty does not pay, reduce, or replace the signer's penalty.

Together with subdivision six, this closes both directions of substitution:
the company penalty cannot stand in for the individual penalty, and the company
cannot reimburse the individual after the individual penalty is imposed.

---

# Section 4 - severability

> **§ 4. Severability.** If any clause, sentence, paragraph, subdivision,
> section, or part of this act shall be adjudged by a court of competent
> jurisdiction to be invalid, such judgment shall not affect, impair, or
> invalidate the remainder thereof, but shall be confined in its operation to
> the clause, sentence, paragraph, subdivision, section, or part directly
> involved in the controversy in which such judgment shall have been rendered.

**Plain English:** If a court invalidates one portion of the Act, the remaining
parts are intended to continue operating where they can. The judgment should be
limited to the provision directly involved, rather than automatically erasing
the whole law.

Whether remaining provisions can function after a particular ruling would
still depend on the court and the legal issue involved.

---

# Section 5 - effective date and implementation

> **§ 5. Effective date.** This act shall take effect on the one hundred
> eightieth day after it shall have become a law. Effective immediately, the
> addition, amendment, or repeal of any rule or regulation necessary for the
> implementation of this act on its effective date is authorized to be made and
> completed on or before such effective date.

**Plain English:** The substantive duties begin 180 days after enactment. The
state may begin making the necessary rules and forms immediately so the system
is ready when the duties start.

The delay gives covered developers time to identify signers, map actual
authority, establish inquiry and escalation systems, review existing models,
and prepare filings. It also gives the office time to build forms and the
public register.

---

# How the whole mechanism works in practice

Consider a covered developer preparing to deploy a substantially modified
frontier model in New York.

1. The company identifies every required signer. That includes the developer's
   highest executive, the top executive of an affiliate that ultimately
   controls it, the senior framework officer with stop authority, and any other
   human with final material deployment authority.
2. Staff, evaluators, and experts perform the underlying work. Each signer must
   use due care to ensure a reasonable, documented inquiry occurred and cannot
   ignore signs that the record is false or incomplete.
3. If material compliance exists, the signers personally certify. If it does
   not, they personally acknowledge each material problem and the remediation
   plan. The acknowledgment does not itself authorize deployment.
4. The office publishes the public version and places the signer, model,
   filing type, and date in the searchable register. Protected technical
   information may be redacted; the names and signatures may not.
5. If a material problem exists, each signer must use meaningful measures
   within that person's actual authority to cause remediation and prevent,
   halt, or restrict unlawful covered conduct.
6. If the Attorney General alleges that a signer breached that personal duty,
   the state must prove the person's own failure of due care within the
   person's authority. A company violation alone is insufficient.
7. If a court imposes an individual penalty, the signer must personally bear
   it. The company cannot pay it, reimburse it, insure it, replace it with a
   bonus, or reduce it by paying a corporate penalty instead.
8. For knowing or repeated violations, the court may temporarily bar the
   person from exercising covered authority after weighing proportionality.

The result is a chain from actual decision power, to a named public signature,
to a personal duty of inquiry and response, to a consequence that remains with
the individual if that duty is violated.

# What the proposal deliberately does not do

The bill does **not**:

- change which companies or models the RAISE Act covers;
- lower the existing compute or revenue thresholds;
- regulate ordinary AI systems, startups below the thresholds, or ordinary
  downstream users;
- make wealth, fame, expertise, technical access, employment, or advice alone
  a basis for personal liability;
- make every engineer, researcher, safety employee, board member, investor,
  cloud provider, or contractor a signer;
- impose liability merely because a model causes harm or because the company
  violates another provision;
- make the signer personally guarantee that no failure or bad outcome can ever
  occur;
- prohibit the use of employees, experts, auditors, or advisers to perform
  supporting work;
- create a private right of action;
- create a new criminal offense; or
- create a general ban on AI research, development, deployment, or use.

The proposal instead creates a civil, public-signature system for people at the
top of covered organizations and for any additional person who actually holds
final material deployment authority. Individual liability requires proof of
the individual's own breach of a statutory duty within that person's
authority.

# Why both titles and practical power matter

A title-only law can be evaded by reorganizing titles, leaving an office
vacant, splitting authority across a committee, or locating control in a parent
company, trust, board arrangement, or special voting right. A purely functional
law, on the other hand, can become vague or accidentally sweep in technical
workers whose access is mistaken for authority.

This proposal uses both approaches:

- named senior offices create an identifiable minimum set of signers;
- fallback rules prevent unconventional structures from leaving an empty
  chair;
- the functional category reaches other people with final material decision
  authority, including authority exercised through ownership or governance
  rights; and
- explicit exclusions protect people who merely implement, advise, analyze, or
  possess technical capacity without decision authority.

The intended line is therefore not "rich people versus employees" as a matter
of status. It is **people who retain the greatest relevant power versus people
who do not decide**. Wealth can accompany that power, especially where it comes
with controlling ownership or special governance rights, but practical
decision authority is the legal connection.

# Why the individual penalty must remain individual

An entity-level fine can be paid from corporate funds and ultimately borne by
shareholders, workers, customers, or insurers. Even a nominally individual fine
can become an entity expense if the company indemnifies the officer, buys
insurance for the penalty, or replaces the money through a bonus.

The proposal addresses each step:

- Section 1427 preserves a separate company penalty.
- Section 1422-a(5) permits a court to impose a penalty for the signer's own
  breach.
- Section 1422-a(6)(a) requires the signer to pay it personally.
- Section 1422-a(6)(b) prohibits compensation offsets and disguised
  reimbursement.
- Section 1422-a(6)(c) makes contrary arrangements unenforceable and allows
  recovery of prohibited transfers without reducing the original penalty.
- Section 1422-a(7) adds possible disqualification for knowing or repeated
  violations.

That is how the proposal turns "personal accountability" from a label into an
actual allocation of consequence.

# Important drafting limits

This remains a research draft. Legislative counsel and subject-matter experts
should review, among other things:

- conformity with New York bill-drafting and cross-reference conventions;
- how the signer categories interact with particular corporate, trust,
  nonprofit, and public-benefit-corporation structures;
- whether the civil-penalty caps and disqualification standard are calibrated
  appropriately;
- interaction with New York insurance, indemnification, corporate-governance,
  labor, privilege, public-records, and constitutional law;
- implementation of the public register and protection of sensitive technical
  information;
- the existing-deployment transition and annual filing dates; and
- the evidentiary standard for practical authority, reasonable reliance, and
  due care.

The guide explains the draft's intended operation. It should not be treated as
a prediction of how a court would resolve every disputed application.
