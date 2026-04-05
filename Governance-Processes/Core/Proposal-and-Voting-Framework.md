# Proposal & Voting Framework

---

## 1. Scope

This document defines:

* How proposals are created, discussed, and approved
* Voting mechanisms and thresholds
* Proposal categories and requirements
* Safeguards such as veto and resubmission rules

---

## 2. Out of Scope

This document does NOT define:

* Treasury management rules (see Treasury Policy)
* Execution authority (see Execution Policy)
* Emergency actions (see Emergency Policy)

---

## 3. Proposal Lifecycle

All proposals follow this lifecycle:

### 3.1 Draft Stage

* Idea introduced publicly (e.g., forum, RadixTalk)
* Open discussion and feedback

---

### 3.2 Formal Submission

* Proposal submitted via governance interface
* Must include required fields (see Section 5)

---

### 3.3 Review Period

* Minimum review period before voting
* Community discussion continues

---

### 3.4 Voting Period

* Token holders vote
* Voting power determined by snapshot

---

### 3.5 Outcome

* Passed → moves to execution
* Failed → cooldown applies

---

## 4. Proposal Categories

### 4.1 Constitutional Proposals

Changes to:

* Charter
* Core governance structure

---

### 4.2 Governance Process Proposals

Changes to:

* Governance rules
* Process documents

Proposals that introduce or modify governance documents, including the Charter, policies, or structural rules, must follow the Governance Maintenance & Upgrade Framework.

This framework defines:

* classification of changes (patch, minor, major)
* required approval thresholds
* consistency and versioning requirements

All governance changes must clearly specify their classification and comply with the defined upgrade process.

---

### 4.3 Treasury & Budget Proposals

* Funding requests
* Budget allocations

---

### 4.4 Executable Proposals

* Technical or operational changes
* On-chain or system execution

---

### 4.5 Signaling Proposals

* Non-binding decisions
* Community sentiment

---

## 5. Proposal Requirements

All proposals must include:

* Title and description
* Category
* Rationale
* Expected outcomes
* Risks and trade-offs
* Budget (if applicable)
* Execution plan (if applicable)

---

## 6. Voting Mechanics

### 6.1 Voting Power

* Voting power is determined at a fixed snapshot
* Snapshot occurs at start of voting period
* Measured in XRD (including defined eligible holdings)

---

### 6.2 Voting Method

* One token = one vote
* Votes: Yes / No / Abstain

---

### 6.3 Quorum

A proposal is valid only if quorum is met.

Quorum thresholds are defined in DAO Parameters and may vary by proposal type.

---

### 6.4 Approval Thresholds

Approval thresholds vary by proposal type:

* Constitutional: supermajority required
* Governance: higher threshold
* Treasury: standard majority
* Signaling: simple majority

Exact thresholds defined in DAO Parameters.

---

## 7. Proposal Conflicts

If two proposals conflict and cannot both be implemented:

* The proposal with the higher YES vote share (as a percentage of total votes cast) prevails
* If the margin between them is less than 5 percentage points, both are invalidated and must be resubmitted as a single proposal with clearly defined alternatives
* If one proposal passed quorum and the other did not, the one that met quorum prevails regardless of vote share

The RAC flags conflicts at the start of the voting period where possible, so the DAO can be aware before voting closes.

---

## 8. Veto Mechanism

### 8.1 Purpose

The veto mechanism exists to:

* Prevent proposals that violate governance rules
* Protect against malicious or invalid proposals

---

### 8.2 Conditions

A veto may only be filed if the proposal:

* Violates the Charter, or
* Violates an existing governance process document

Disagreement with the policy substance of a proposal is not grounds for veto.

---

### 8.3 Who May File

Any token holder may file a veto challenge, provided the minimum participation threshold is met (see DAO Parameters §4).

---

### 8.4 Process

1. A veto challenge must be filed via the governance interface within **48 hours** of the vote closing (see DAO Parameters §4)
2. The filing must cite the specific Charter section or governance rule being violated
3. The RAC reviews the challenge and issues a determination within **48 hours** of filing:
   - If the RAC determines the proposal violates governance rules, the proposal is **halted** pending a corrective resubmission
   - If the RAC determines no violation exists, the proposal **proceeds** to execution
4. The DAO may override any RAC determination via a Governance Process proposal

---

### 8.5 Limitations

* Cannot be used to block proposals based on policy disagreement
* Repeated frivolous filings may result in sanctions per Dispute Resolution Policy
* Cannot be used after the 48-hour window has closed

---

## 9. Cooldowns & Resubmission

### 9.1 Failed Proposals

* Cannot be immediately resubmitted

---

### 9.2 Exception

Resubmission is allowed if:

* Proposal failed due to technical issue
* Minor corrections are made

---

## 10. Proposal Validity

A proposal is invalid if:

* It violates the Charter
* It exceeds DAO authority
* It lacks required information

The RAC may flag invalid proposals but does not decide outcomes.

---

## 11. Transparency

All proposals must:

* Be publicly accessible
* Include sufficient information for decision-making

Exceptions allowed only under defined confidentiality rules.

---

## 12. Execution Handoff

Approved proposals are forwarded to:

* Execution mechanisms (on-chain or off-chain)
* Relevant Working Groups

Execution rules are defined in the Execution Policy.

---

## 13. Governance Parameters

The following are defined separately and may be updated:

* Quorum thresholds
* Voting duration
* Approval thresholds
* Cooldown periods

---

## 14. Amendments

This framework may be updated via governance proposals.
