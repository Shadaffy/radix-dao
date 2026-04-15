# Glossary of Governance Terms

This glossary defines the key terms used across the Radix DAO governance framework. For exact parameter values (quorum percentages, time durations, signing thresholds), see the [DAO Parameters Registry](Parameters/DAO-Parameters-Registry.md). For the overall system structure, see [Supporting Materials / governance-body-intro.md](Supporting-Materials/governance-body-intro.md).

---

## A

**Activation Roadmap**
The step-by-step operational guide for forming Radix DLT DAO LLC and transitioning from Founding Transferor stewardship to DAO governance. Covers four phases: pre-registration preparation, post-registration entity setup, asset transfer, and treasury configuration. Specifies which actor performs each step, what the action is, and the governance vote threshold where applicable. The practical companion document to the Transition Governance Framework.
→ See: [Transition/Activation-Roadmap.md](Transition/Activation-Roadmap.md)

**Accountability Council (RAC)**
The DAO's oversight body, composed of 3–5 elected members serving 6-month terms. The RAC is a *guardian of process*, not a decision-making authority — it ensures governance procedures are followed correctly, verifies that execution matches approved proposals, reviews veto challenges, and manages emergency actions under strict constraints. During Phase 1, the RAC also holds limited transitional authority to support operational bootstrapping. All RAC actions are subject to community challenge and retrospective review.
→ See: [Charter §8](Charter/charter.md), [Transition Governance Framework §4–6](Transition/Transition-Governance-Framework.md), [Emergency & Safeguards Policy §5](Governance-Processes/Core/Emergency-and-Safeguards-Policy.md)

**Approval Threshold**
The minimum percentage of YES votes (among all votes cast) required for a proposal to pass. This is separate from quorum — a proposal must meet *both* quorum and its approval threshold. Thresholds vary by proposal type: Constitutional proposals require ≥66% YES; Governance Process proposals ≥60%; Treasury/Budget, Executable, and Signaling proposals ≥50%.
→ See: [DAO Parameters Registry §3.3](Parameters/DAO-Parameters-Registry.md), [Proposal & Voting Framework §6.4](Governance-Processes/Core/Proposal-and-Voting-Framework.md)

**Authorized Signers**
A pool of 5 individuals responsible for executing treasury and legal actions approved by the DAO. They operate as a multisig — standard actions require 3-of-5 approvals; high-risk actions require 4-of-5. Authorized Signers have no discretionary authority: they execute approved decisions faithfully and may refuse only on procedural, legal, or security grounds. They serve 6-month terms. In the Operating Agreement's terminology, Authorized Signers are Delegates holding the Treasury Signing (§5.3(a)) and Legal Signatory (§5.3(c)) Delegated Functions — see **Delegate (Operational)**.
→ See: [Authorized-Signers-Rules.md](Governance-Processes/Roles/Authorized-Signers-Rules.md), [Operating Agreement §5.3](Legal/Formation/Operating-Agreement.md), [DAO Parameters Registry §6A](Parameters/DAO-Parameters-Registry.md)

---

## C

**Charter**
The highest document in the governance framework. It defines the DAO's purpose, core principles, authority structure, and permanent guarantees (including the non-distribution principle and asset lock). All other governance documents derive their legitimacy from the Charter. Amendments require a Constitutional proposal with ≥66% approval and ≥10% quorum.
→ See: [Charter/charter.md](Charter/charter.md)

**Code of Conduct**
The behavioural standards binding on all DAO participants. It defines six obligations: acting in good faith, respect and constructive engagement, transparency and disclosure, protection of DAO resources, appropriate confidentiality, and data security. Violations are handled through defined enforcement mechanisms.
→ See: [Governance-Processes/Core/Code-of-Conduct.md](Governance-Processes/Core/Code-of-Conduct.md)

**Conflict of Interest**
A situation where a covered person's personal, financial, or professional interests could improperly influence — or reasonably appear to influence — their exercise of DAO authority. Types include financial interests, organizational affiliations, personal relationships, and simultaneous role conflicts. Covered persons (RAC members, Authorized Signers, Working Group Stewards) must disclose conflicts and recuse themselves from affected decisions. Token holders voting in ordinary capacity are encouraged but not required to disclose.
→ See: [Governance-Processes/Roles/Conflict-of-Interest-Policy.md](Governance-Processes/Roles/Conflict-of-Interest-Policy.md)

**Constitutional Proposal**
The highest category of governance proposal, used to amend the Charter or make fundamental changes to the governance structure. Requires the highest participation and approval thresholds: ≥10% quorum and ≥66% YES votes.
→ See: [Proposal & Voting Framework §4.1](Governance-Processes/Core/Proposal-and-Voting-Framework.md), [DAO Parameters Registry §3.2–3.3](Parameters/DAO-Parameters-Registry.md)

**Contributor**
An individual compensated for work performed on behalf of the DAO. Contributor categories include Working Group Stewards (elected), WG Contributors (engaged within a Working Group's budget), and Specialists (contracted for specific expertise).
→ See: [Governance-Processes/Core/Contributor-Compensation-Policy.md](Governance-Processes/Core/Contributor-Compensation-Policy.md)

**Cooldown Period**
A mandatory waiting period before a failed proposal can be resubmitted. Standard cooldown after a failed proposal is 7 days. Minor-fix resubmissions (e.g., technical errors) may bypass the cooldown. The cooldown prevents immediate re-proposals that exhaust community attention.
→ See: [DAO Parameters Registry §3.4](Parameters/DAO-Parameters-Registry.md), [Proposal & Voting Framework §9](Governance-Processes/Core/Proposal-and-Voting-Framework.md)

---

## D

**Delegate (Voting)**
A participant who accepts voting power assigned by one or more token holders and votes in governance on their behalf. Delegates who accept public delegation are expected to vote actively, communicate their rationale, and act in the interest of delegators and the DAO — not for personal gain.
→ See: [Token Delegation Policy §5](Governance-Processes/Core/Token-Delegation-Policy.md)

*Note: "Delegate" is also used in the Operating Agreement (Article V) to refer to elected Members performing Delegated Functions — see **Delegate (Operational)** below.*

**Delegate (Operational)**
A Member elected by Governance Proposal to perform one or more of the five Delegated Functions defined in Operating Agreement §5.3: Treasury Signing, Governance Operations, Legal Signatory, Compliance Liaison, and Web2 Custodian. Operational Delegates are the legal and operational representatives of the LLC for executing DAO-approved decisions. In the governance policy layer, these roles are referred to as Authorized Signers (Treasury Signing and Legal Signatory) and by their functional titles (Governance Operator, Compliance Liaison, Web2 Custodian). All Operational Delegates must complete KYC before assuming their function and hold no authority independent of DAO governance decisions.
→ See: [Operating Agreement Article V](Legal/Formation/Operating-Agreement.md), [Legal Wrapper §8](Legal/Policy/Legal-Wrapper-and-Representation.md), [Role and Authority Map](Supporting-Materials/Role-and-Authority-Map.md)

**Delegator**
A token holder who assigns their voting power to a delegate. Delegators retain the right to revoke or change delegation at any time; the change takes effect at the next snapshot. Delegators can also vote directly on a specific proposal if the governance platform permits.
→ See: [Token Delegation Policy §3, §8](Governance-Processes/Core/Token-Delegation-Policy.md)

**Delegation**
The act of assigning your voting power to another participant (the delegate) to vote on your behalf. Delegation is recorded on-chain and takes effect at the next governance snapshot. A token holder may only delegate to a single delegate at a time (unless the platform supports partial delegation). Delegation does not remove a token holder's right to submit proposals or file veto challenges.
→ See: [Token Delegation Policy](Governance-Processes/Core/Token-Delegation-Policy.md), [Charter §5](Charter/charter.md)

**De Minimis Threshold**
The minimum financial interest below which no conflict of interest disclosure is required. Ordinary XRD holdings do not constitute a conflict; financial interests above this threshold (equity, tokens, debt, employment, or advisory compensation in an entity affected by a DAO decision) must be disclosed. The exact threshold is defined in the DAO Parameters Registry.
→ See: [Conflict of Interest Policy §3.1](Governance-Processes/Roles/Conflict-of-Interest-Policy.md), [DAO Parameters Registry](Parameters/DAO-Parameters-Registry.md)

**Dispute Resolution**
A structured four-level process for resolving disagreements within the DAO, from direct resolution between parties (Level 1) through Working Group mediation (Level 2), RAC review (Level 3), to full DAO arbitration via governance vote (Level 4). Time limits apply at each level.
→ See: [Governance-Processes/System-Integrity/Dispute-Resolution-Arbitration-Policy.md](Governance-Processes/System-Integrity/Dispute-Resolution-Arbitration-Policy.md), [DAO Parameters Registry §6C](Parameters/DAO-Parameters-Registry.md)

---

## E

**Emergency**
A situation requiring immediate action to prevent loss or compromise of treasury assets, exploitation of protocol vulnerabilities, critical failure of network infrastructure, security compromise, or severe disruption to DAO operations. Only the RAC may declare and act on an emergency, subject to elevated approval thresholds (≥2/3 of RAC members, ≥75% approval). Emergency actions expire automatically after a maximum of 7 days and are subject to retrospective community review.
→ See: [Emergency & Safeguards Policy §4–5](Governance-Processes/Core/Emergency-and-Safeguards-Policy.md), [DAO Parameters Registry §5.2, §10](Parameters/DAO-Parameters-Registry.md)

**Executable Proposal**
A proposal category for technical or operational changes, or actions requiring on-chain or system execution. Requires ≥5% quorum and ≥50% YES approval.
→ See: [Proposal & Voting Framework §4.4](Governance-Processes/Core/Proposal-and-Voting-Framework.md)

**Execution Authority**
The power to carry out governance-approved decisions. Execution authority is deliberately separated from decision-making authority: token holders decide; Working Groups coordinate; Authorized Signers execute treasury and legal actions. No single body controls both decision and execution.
→ See: [Governance-Processes/Core/Execution-and-Treasury-Actions-Policy.md](Governance-Processes/Core/Execution-and-Treasury-Actions-Policy.md), [Charter §4.3](Charter/charter.md)

---

## F

**Formation Documents**
The corporate legal instruments that establish and govern Radix DLT DAO LLC as a legal entity under Marshall Islands law. Distinct from governance policy documents: Formation Documents are filed with MIDAO (the Marshall Islands business registry) and are legal instruments rather than governance policies. They are maintained in the repository for transparency. The Formation Documents are: Certificate of Formation, Operating Agreement, BOIR Template, Asset Transfer Agreement, IP Schedule, and Continuity Statement.
→ See: [Legal/Formation/](Legal/Formation/)

**Fidelity**
The principle that execution must match the approved proposal exactly — Authorized Signers and Working Groups may not change the intent, scope, or terms of an approved decision when carrying it out. Deviations require a new governance proposal.
→ See: [Governance-Processes/Core/Execution-and-Treasury-Actions-Policy.md](Governance-Processes/Core/Execution-and-Treasury-Actions-Policy.md)

---

## G

**Governance Process Proposal**
A proposal category used to create, modify, or repeal governance policy documents and procedural rules. Requires ≥7% quorum and ≥60% YES approval. Also the mechanism used to transition between governance phases (Phase 1 → Phase 2, Phase 2 → Phase 3).
→ See: [Proposal & Voting Framework §4.2](Governance-Processes/Core/Proposal-and-Voting-Framework.md)

**Grant**
Funding awarded to external parties for projects that benefit the Radix ecosystem. Grants are categorised by size and urgency: Micro (fast, small, approved by Working Group Stewards without a DAO vote), Standard (requires governance vote), Strategic (large, requires extended review and governance vote), and Emergency (rapid response, requires ratification after the fact). Exact thresholds are defined in the Parameters Registry.
→ See: [Governance-Processes/Core/Grant-Program-Policy.md](Governance-Processes/Core/Grant-Program-Policy.md)

---

## L

**Legal Entity**
Radix DLT DAO LLC — a Marshall Islands DAO LLC that provides the Radix DAO with real-world legal personhood. Enables the DAO to hold assets, sign contracts, engage contributors, and interface with legal and financial systems without individual token holders bearing personal liability. Governed by its Operating Agreement, which subjects the entity to DAO token-holder governance. The legal entity is the executor of governance decisions in the real world, not a parallel authority. It is registered with MIDAO (the Marshall Islands DAO registry).
→ See: [Legal/Policy/Legal-Wrapper-and-Representation.md](Legal/Policy/Legal-Wrapper-and-Representation.md), [Legal/Formation/](Legal/Formation/)

**LSU (Liquid Staking Units)**
Tokens received by XRD holders who stake their XRD with a validator on the Radix network. LSU represents the holder's staked position and accrues staking rewards over time. For governance purposes, LSU is recognised as eligible voting power from Phase 1: at each voting snapshot, the LSU balance is converted to its XRD equivalent using the LSU redemption rate at that moment, and the resulting XRD-equivalent amount is counted as voting power. Holding LSU rather than liquid XRD does not reduce a holder's ability to participate in governance.
→ See: [Proposal & Voting Framework §6.1](Governance-Processes/Core/Proposal-and-Voting-Framework.md), [DAO Parameters Registry §3.2, §8](Parameters/DAO-Parameters-Registry.md)

---

## M

**Material Financial Interest**
Equity, tokens, debt, employment, or advisory compensation held in an entity that is above the *de minimis* threshold defined in the DAO Parameters Registry. Holding a material financial interest in an entity seeking DAO funding or benefiting from a DAO decision triggers a mandatory conflict of interest disclosure and may require recusal.
→ See: [Conflict of Interest Policy §3.1](Governance-Processes/Roles/Conflict-of-Interest-Policy.md)

**Member**
Any person or entity that holds governance tokens. A person or entity becomes a Member upon acquiring governance tokens (Operating Agreement §4.1). The terms "token holder" and "member" are used interchangeably across governance documents. Members have no economic ownership interest in the Company's assets. Membership terminates when a Member holds no voting assets and has no active votes on the governance smart contract.
→ See: [Operating Agreement §4.1–4.4](Legal/Formation/Operating-Agreement.md), [Legal Wrapper §2A](Legal/Policy/Legal-Wrapper-and-Representation.md)

**Multisig (Multi-Signature)**
A security mechanism requiring multiple approvals before a treasury or legal action can be executed. The DAO uses a 5-signer pool: standard treasury actions require 3-of-5 Authorized Signer approvals; high-risk actions require 4-of-5. This prevents any single individual from unilaterally moving DAO funds.
→ See: [DAO Parameters Registry §6.2, §6A](Parameters/DAO-Parameters-Registry.md), [Governance-Processes/Roles/Authorized-Signers-Rules.md](Governance-Processes/Roles/Authorized-Signers-Rules.md)

---

## N

**Non-Distribution Principle**
The foundational commitment that DAO assets exist to advance the Radix ecosystem — not to enrich its members. No distributions may be made to token holders or members except as reasonable compensation for genuine services rendered or reimbursement of legitimate expenses. This principle applies to asset wind-down as well: should the DAO dissolve, its remaining assets must be transferred to an entity with substantially similar objectives.
→ See: [Charter §10–11](Charter/charter.md), [Legal/Policy/Legal-Wrapper-and-Representation.md](Legal/Policy/Legal-Wrapper-and-Representation.md)

---

## P

**Phase 1**
The first 12 months of DAO operations, also called the Transition phase. Core governance is active, but some features are simplified and the RAC holds limited delegated authority to support operational bootstrapping. Tier 2 policies operate as guiding principles during this phase rather than fully enforceable rules. Phase 1 ends upon a successful Governance Process proposal confirming that Phase 1 completion criteria have been met.
→ See: [Transition Governance Framework §2.2](Transition/Transition-Governance-Framework.md)

**Phase 2**
Estimated months 12–24. Expanded use of the full governance framework, reduction of RAC delegated responsibilities, and increased direct DAO control. Entered via a Governance Process proposal (≥60% approval, ≥7% quorum).
→ See: [Transition Governance Framework §2.2](Transition/Transition-Governance-Framework.md)

**Phase 3**
Estimated from month 24 onward. All transitional delegation expires; the DAO operates entirely under standard rules with no RAC transitional authority. Entered via a Governance Process proposal confirming all Phase 2 delegation has been replaced by formal governance processes.
→ See: [Transition Governance Framework §2.2](Transition/Transition-Governance-Framework.md)

**Proposal**
A formal submission to the DAO requesting a decision. All proposals must include a title, category, rationale, expected outcomes, risks and trade-offs, and (where applicable) a budget and execution plan. Proposals follow a lifecycle: draft → formal submission → review period → voting period → outcome.
→ See: [Proposal & Voting Framework §3, §5](Governance-Processes/Core/Proposal-and-Voting-Framework.md)

**Public Delegate Registry**
A voluntary registry maintained by the Governance & Legal Working Group where delegates may publish their governance philosophy, priorities, conflict of interest disclosures, and contact information. Registration is voluntary — unregistered delegates may still accept delegation — but registered delegates signal a higher accountability commitment.
→ See: [Token Delegation Policy §6.1](Governance-Processes/Core/Token-Delegation-Policy.md)

---

## Q

**Quorum**
The minimum participation required for a vote to be valid, expressed as a percentage of eligible voting power (liquid XRD plus LSU converted to XRD-equivalent at the voting snapshot). If quorum is not met, the proposal fails regardless of the YES/NO split. Quorum thresholds vary by proposal type: Constitutional (10%), Governance Process (7%), Treasury/Budget and Executable (5%), Signaling (3%). If a proposal type repeatedly fails to reach quorum (3 consecutive failures), a reduced quorum threshold and extended voting period may apply per the Governance Continuity Framework.
→ See: [DAO Parameters Registry §3.2](Parameters/DAO-Parameters-Registry.md), [Proposal & Voting Framework §6.3](Governance-Processes/Core/Proposal-and-Voting-Framework.md)

---

## R

**RAC** → See *Accountability Council (RAC)*

**Recusal**
The act of withdrawing from a governance decision due to a conflict of interest. Covered persons (RAC members, Authorized Signers, Working Group Stewards) are required to recuse from votes, deliberations, and negotiations where they have a material conflict. Recusals must be recorded in meeting minutes or governance forum threads, stating the person, the nature of the conflict, and the decision from which they withdrew.
→ See: [Conflict of Interest Policy §5](Governance-Processes/Roles/Conflict-of-Interest-Policy.md)

---

## S

**Signaling Proposal**
A non-binding proposal that gauges community sentiment or preference. The outcome does not create a governance obligation, but provides a public record of community views. Requires ≥3% quorum and ≥50% YES approval.
→ See: [Proposal & Voting Framework §4.5](Governance-Processes/Core/Proposal-and-Voting-Framework.md)

**Snapshot**
A fixed point in time at which voting power is calculated for a specific vote. The snapshot is taken at the start of each voting period. Voting power captured at the snapshot includes liquid XRD holdings and LSU holdings converted to their XRD equivalent at that moment. Any delegation changes, token transfers, or staking actions made *after* the snapshot do not affect the vote in progress — they take effect from the next snapshot.
→ See: [Proposal & Voting Framework §6.1](Governance-Processes/Core/Proposal-and-Voting-Framework.md), [Token Delegation Policy §3.3](Governance-Processes/Core/Token-Delegation-Policy.md)

**Steward**
An elected leader of a Working Group, serving a 6-month term. Each Working Group has 2–3 Stewards. Stewards coordinate execution within the WG's approved mandate and budget, manage workstreams and contributors, and report progress to the DAO. They may not override governance decisions or create new financial obligations beyond approved budgets.
→ See: [Governance-Processes/Execution/Working-Group-Framework.md](Governance-Processes/Execution/Working-Group-Framework.md), [DAO Parameters Registry §7](Parameters/DAO-Parameters-Registry.md)

---

## T

**Tier 1**
Documents and policies that are fully active and enforceable from the first day of Phase 1 launch. Includes the Charter, Proposal & Voting Framework, Execution & Treasury Actions Policy, Emergency & Safeguards Policy, Legal Wrapper, DAO Parameters Registry, Code of Conduct, Conflict of Interest Policy, and Token Delegation Policy.
→ See: [readme.md](readme.md), [Supporting-Materials/governance-body-intro.md](Supporting-Materials/governance-body-intro.md)

**Tier 2**
Documents that are published and available at launch, and expected to be followed in spirit, but that become formally enforceable only after a community governance vote. Each Tier 2 policy has a target approval date within the first year of operations. During Phase 1, Working Groups and contributors are expected to adopt them operationally ahead of formal approval.
→ See: [Transition Governance Framework §3.5](Transition/Transition-Governance-Framework.md), [readme.md](readme.md)

**Tier 3**
Documents that activate the moment they become relevant, regardless of phase. Currently limited to the Smart Contract Audit Policy, which becomes active before any governance contract deployment is proposed.
→ See: [readme.md](readme.md)

**Token Holder Sovereignty**
The foundational principle that ultimate decision-making authority rests with the community of XRD token holders. All governance power flows from and returns to the community. Delegated authority (to the RAC, Working Groups, or Authorized Signers) is a matter of operational necessity and does not transfer sovereignty — token holders can always override any decision through governance.
→ See: [Charter §3.1, §4.1](Charter/charter.md)

**Treasury & Budget Proposal**
A proposal category for funding requests and budget allocations from the DAO treasury. Requires ≥5% quorum and ≥50% YES approval.
→ See: [Proposal & Voting Framework §4.3](Governance-Processes/Core/Proposal-and-Voting-Framework.md)

---

## V

**Veto**
A challenge mechanism that allows any token holder (meeting minimum participation threshold) to challenge a passed proposal within 48 hours of the vote closing, on the grounds that it violates the Charter or an existing governance rule. The RAC reviews and issues a determination within 48 hours. If a violation is found, the proposal is halted pending correction; if not, it proceeds. Disagreement with the *content* of a policy is not grounds for veto. The DAO can override any RAC determination via a Governance Process proposal.
→ See: [Proposal & Voting Framework §8](Governance-Processes/Core/Proposal-and-Voting-Framework.md), [DAO Parameters Registry §4](Parameters/DAO-Parameters-Registry.md)

---

## W

**Whistleblower Protection**
Protections for individuals who report governance integrity violations, misconduct, or ethics breaches in good faith. Designed to prevent retaliation against reporters acting in the DAO's interest.
→ See: [Governance-Processes/System-Integrity/Ethics-Reporting-Policy.md](Governance-Processes/System-Integrity/Ethics-Reporting-Policy.md)

**Working Group (WG)**
An execution body that coordinates contributors within a DAO-approved mandate and budget. Working Groups are led by 2–3 elected Stewards serving 6-month terms. They manage workstreams, engage contributors, report progress to the DAO, and operate within the scope and budget approved by governance. Five Working Groups launched at Phase 1: Strategic Coordination, Governance & Legal, Product & Protocol, Ecosystem Growth, and Community & Marketing. Working Groups cannot define DAO strategy, override governance decisions, or spend beyond approved budgets.
→ See: [Governance-Processes/Execution/Working-Group-Framework.md](Governance-Processes/Execution/Working-Group-Framework.md), [Charter §4.2](Charter/charter.md)

---

## Role Index

This table maps governance-layer role names to Operating Agreement Delegated Functions and key authority documents. For full role profiles including what each role can and cannot do, see the [Role and Authority Map](Supporting-Materials/Role-and-Authority-Map.md).

| Governance-Layer Role | OA Delegated Function | Key Authority Documents |
|---|---|---|
| RAC Member | None — oversight body, not a Delegated Function | [RAC Mandate](Governance-Processes/Roles/RAC-Mandate.md), [Charter §8](Charter/charter.md), [Transition Framework §4–6](Transition/Transition-Governance-Framework.md) |
| Authorized Signer (Treasury) | Treasury Signing — OA §5.3(a) | [Authorized Signers Rules](Governance-Processes/Roles/Authorized-Signers-Rules.md), [Execution & Treasury Actions Policy](Governance-Processes/Core/Execution-and-Treasury-Actions-Policy.md) |
| Authorized Signer (Legal) | Legal Signatory — OA §5.3(c) | [Authorized Signers Rules](Governance-Processes/Roles/Authorized-Signers-Rules.md), [Legal Wrapper §7–8](Legal/Policy/Legal-Wrapper-and-Representation.md) |
| Governance Operator | Governance Operations — OA §5.3(b) | [Proposal & Voting Framework](Governance-Processes/Core/Proposal-and-Voting-Framework.md), [Operating Agreement §6.1](Legal/Formation/Operating-Agreement.md) |
| Compliance Liaison | Compliance Liaison — OA §5.3(d) | [Operating Agreement §8](Legal/Formation/Operating-Agreement.md), [Legal Wrapper §7A](Legal/Policy/Legal-Wrapper-and-Representation.md) |
| Web2 Custodian | Web2 Custodian — OA §5.3(e) | [Operating Agreement §5.3(e)](Legal/Formation/Operating-Agreement.md) |
| Working Group Steward | None — execution coordination role | [Working Group Framework](Governance-Processes/Execution/Working-Group-Framework.md), [Election & Role Governance Policy](Governance-Processes/Roles/Election-and-Role-Governance-Policy.md) |

**Authority boundaries (summary):**

* **Token holders** — sovereign decision-making authority via on-chain governance
* **RAC** — process oversight, emergency response, Phase 1 transitional coordination only; no independent strategic authority
* **Authorized Signers** — execute approved treasury and legal actions only; no discretionary authority
* **Governance Operator** — administers the governance platform per approved procedures; cannot modify, suppress, or delay eligible proposals
* **Compliance Liaison** — entity compliance, KYC, BOIR filing; no strategic or treasury authority
* **Web2 Custodian** — manages Web2 assets per approved procedures; cannot transfer domain ownership without a Governance Proposal
* **Working Group Stewards** — execution coordination within approved mandates and budgets; no strategic authority
