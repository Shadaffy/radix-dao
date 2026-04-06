# Radix DAO Transition Governance Framework

## (Phase 1 Activation & RAC Transitional Authority)

> **Related document:** `Radix-DAO-Phase1.md` contains the original proposal and rationale for this framework. In case of conflict, this document is normative.

---

## 1. Purpose

This document defines the **temporary governance activation model and limited transitional authority** required to move from the Radix Foundation to a fully operational, community-governed DAO.

This framework exists to:

* Enable secure transfer of assets and responsibilities
* Establish the DAO as a legally and operationally functional system
* Reduce governance complexity during early-stage operations
* Provide controlled coordination during initialization

---

## 2. Scope & Duration

### 2.1 Temporary Nature

All provisions in this document are:

* **Temporary**
* **Strictly limited in scope**
* **Subject to DAO oversight**
* **Automatically expire after the transition period**

---

### 2.2 Transition Model

The DAO operates under a **phased governance activation model**:

#### Phase 1 — Simplified Activation (0–12 months)

* Core governance system is active in simplified form
* Selected responsibilities are temporarily delegated to the RAC
* Operational systems are established
* Asset transfer is completed

---

#### Phase 2 — Progressive Decentralization (estimated months 12–24)

* Expanded use of full governance framework
* Reduction of RAC delegated responsibilities
* Increased direct DAO control

Entry into Phase 2 requires a **Governance Process proposal** (≥60% approval, ≥7% quorum) confirming that Phase 1 completion criteria (§10) are substantially met.

**Phase 2 Mandate: Reputation System**

The design and implementation of a community reputation system is a required deliverable of Phase 2. The Governance & Legal Working Group, in collaboration with the Product & Protocol Working Group, is responsible for:

1. **Research & Design (within 3 months of Phase 2 entry)** — Publishing a governance proposal that defines the reputation model, covering at minimum:
   * What actions generate reputation (e.g., on-chain votes cast, proposals authored, peer allocation received, contributor milestones completed)
   * How reputation is weighted and whether it decays over time
   * Whether reputation is transferable or soulbound
   * How reputation interacts with voting power (advisory weighting vs. hard caps)
   * Sybil resistance approach (e.g., Gitcoin Passport integration, proof-of-personhood, or role-based gating)

2. **Community Review (30-day comment period)** — The design proposal must be open for community comment for a minimum of 30 days before a formal governance vote

3. **Implementation (within 9 months of Phase 2 entry)** — A live reputation system, approved by governance vote, must be operational before Phase 3 entry is permitted

The reputation system must not replace token-weighted voting without a Constitutional proposal. Its initial role is advisory — surfacing trusted voices and informing delegation decisions — with expanded governance weight only if explicitly approved by the community.

---

#### Phase 3 — Full DAO Governance (estimated from month 24)

* All transitional delegation expires
* Full governance framework is active
* DAO operates entirely under standard rules

Entry into Phase 3 requires a **Governance Process proposal** confirming that all Phase 2 delegation has been replaced by formal governance processes and that no transitional authority remains active.

---

## 3. Governance Activation in Phase 1

During Phase 1, the DAO operates using a **subset of the full governance framework**.

---

### 3.1 Fully Active Components

The following are fully in force from Phase 1 launch:

* Charter (including purpose, non-distribution, asset lock)
* Legal Wrapper & Representation
* Execution & Treasury Actions Policy
* Emergency & Safeguards Policy
* DAO Parameters Registry (simplified values)
* Code of Conduct
* Conflict of Interest Policy
* Token Delegation Policy

---

### 3.2 Active in Simplified Form

The following operate with reduced complexity during Phase 1:

| Framework | Active in Phase 1 | Deferred to Phase 2 |
|---|---|---|
| Proposal & Voting | Constitutional, Treasury, Signaling, and Governance Process proposals | Executable proposals; advanced categorization |
| Working Group Framework | Working Groups established via DAO approval (5 at Phase 1 launch: Strategic Coordination, Governance & Legal, Product & Protocol, Ecosystem Growth, Community & Marketing) | New WGs beyond approved set require a new DAO proposal |
| Authorized Signers Rules | Standard execution and emergency actions | Complex multi-party coordination procedures |
| Dispute Resolution | Level 1–3 escalation; RAC review | Full Level 4 DAO arbitration processes |

---

### 3.3 Delegated / Supported by RAC

The following functions may be supported or facilitated by the RAC:

* Governance interpretation where ambiguity exists
* Operational coordination across working groups
* Resolution of process gaps not yet formalized
* Strategic alignment support during early stages

---

### 3.4 Deferred to Phase 2

The following are defined but not fully enforced:

* advanced proposal categorization
* complex parameter tuning
* full strategic coordination processes
* advanced governance mechanisms

---

### 3.5 Policy Activation Schedule (Year 1)

The following policies have been drafted and published as part of the DAO's founding policy library. During Phase 1, they operate as **guiding principles** — they are publicly available and expected to be followed in spirit, but are not yet formally enforceable under the dispute resolution or sanctions framework.

Each policy must be formally proposed and approved by DAO governance vote before it becomes fully enforceable. The table below sets out the target timeline for each proposal. These targets are governance commitments, not hard deadlines — the community may accelerate or adjust the schedule by governance vote.

| Policy | Phase 1 Status | Target Formal Approval |
|---|---|---|
| Transparency & Reporting Policy | Guiding principles; simplified WG reporting active from launch | Month 2 |
| Contributor Compensation Policy | Guiding principles active | Month 3 |
| Grant Program Policy | Guiding principles active | Month 3 |
| Security Disclosure & Bug Bounty Policy | Guiding principles active | Month 4 |
| Ethics Reporting Policy | Guiding principles active | Month 4 |
| Contributor Onboarding & Offboarding | Guidelines active | Month 6 |
| Smart Contract Audit Policy | Active immediately upon any governance contract deployment being proposed | Before first deployment |

**What "guiding principles" means in practice:** a policy in this status is published, visible, and expected to be followed. However, enforcement via the dispute resolution or sanctions framework requires formal governance approval first. Working Groups and role-holders are encouraged to adopt these policies operationally ahead of formal approval.

The Governance & Legal Working Group is responsible for bringing each policy to a governance vote on or before the target date and for tracking progress against this schedule in its regular reporting.

---

## 4. Role of the Accountability Council (RAC)

During Phase 1, the RAC acts as a **transitional coordination and integrity layer**, not a governing authority.

The RAC:

* ensures governance processes function correctly
* supports operational continuity
* facilitates the transition to decentralized governance

The RAC acts **on behalf of the DAO**, and remains accountable to it.

---

## 5. Transitional Delegated Authority

During Phase 1, the RAC is granted **limited delegated authority** strictly for operational continuity.

---

### 5.1 Permitted Actions

The RAC may:

* Facilitate asset transfer and custody setup
* Support operational bootstrapping (infrastructure, tooling, services)
* Resolve minor governance ambiguities
* Coordinate urgent operational decisions where a delay of more than 48 hours would cause material harm to the DAO, subject to documented justification and retrospective disclosure. **"Material harm"** means: loss of or credible risk to treasury assets; inability to execute a DAO-approved proposal within its required timeframe; or failure of critical operational infrastructure with no other recovery path available within the governance timeline
* Assist in establishing initial working groups

---

### 5.2 Emergency Authority (Transitional Scope)

During Phase 1, the RAC may exercise emergency powers as defined in the Emergency Policy, including:

* rapid response to security threats
* temporary suspension of unsafe operations
* protection of treasury assets

All such actions must:

* be minimal and necessary
* be documented
* be disclosed
* be subject to retrospective DAO review

---

### 5.3 RAC Decision Quorum (Transitional Actions)

All non-emergency transitional actions under §5.1 require a simple majority of RAC members (more than half of seated members). Decisions must be recorded and disclosed in accordance with §8.

---

## 6. Explicit Limitations

Even during Phase 1, the RAC:

* **may not override DAO-approved proposals**
* **may not define or impose strategy independently**
* **may not allocate treasury funds outside approved mandates**
* **may not create or modify governance structures without DAO approval**

All authority remains ultimately with the DAO.

---

### 6.1 Conflict of Interest

RAC members with a personal, financial, or organizational conflict of interest in a transitional decision must:

* disclose the conflict prior to the decision
* recuse themselves from the relevant vote

Conflict of interest rules are defined in full in the **RAC Mandate**.

---

### 6.2 Community Challenge Mechanism

Any RAC transitional action under §5.1 may be challenged by the community by filing a **Governance Process proposal** within **14 days** of the action being disclosed.

If the proposal passes, the DAO's decision supersedes the RAC action. The RAC must comply with the outcome.

---

## 7. Relationship to Execution

Execution during Phase 1 follows standard governance structure:

* Working Groups coordinate execution
* Authorized Signers execute treasury and legal actions
* RAC verifies compliance and supports continuity

The RAC does not directly control treasury execution.

---

## 8. Transparency Requirements

During the transition:

* All RAC actions must be publicly reported to the DAO governance forum within **72 hours** of the action being taken
* Each report must include: action taken, justification, members who voted, and outcome
* Asset transfers must be transparently documented with transaction references
* Delegated actions must include justification
* Exceptions and emergency actions must be disclosed with retrospective review scheduled within 7 days

---

## 9. Progressive Reduction of Delegation

RAC delegated authority must:

* **decrease over time**
* be replaced by formal governance processes
* be reviewed **quarterly** — the RAC publishes a delegation status report, and the community has a 14-day period to raise concerns via governance proposal

Each phase transition must include:

* explicit reduction of RAC responsibilities
* increased reliance on DAO voting

---

## 10. Completion Criteria

Phase 1 is considered complete when all of the following minimum conditions are met:

**Asset Transfer**

* Asset transfer from the Radix Foundation is complete, verified, and publicly disclosed

**Governance Track Record**

* At least 3 full governance proposal cycles (draft → vote → execution) have completed without RAC intervention
* No active emergency action or unresolved veto challenge exists at the time of the Phase 2 proposal

**Working Groups**

* All 5 Phase 1 Working Groups have operated independently for at least 60 consecutive days, producing required biweekly reports

**Policy Activation**

* The following Tier 2 policies have been formally activated by governance vote:
  * Transparency & Reporting Policy
  * Contributor Compensation Policy
  * Grant Program Policy

**Participation**

* At least 2 Treasury or Governance Process proposals have met quorum without the reduced-quorum fallback (Governance Continuity §4.3)

**Reporting**

* At least one full quarterly financial transparency report has been published per the Transparency & Reporting Policy

---

Entry into Phase 2 is confirmed when a **Governance Process proposal** (≥60% approval, ≥7% quorum) affirms that the above conditions are met. The proposal must include a checklist attestation prepared by the RAC and reviewed by the Governance & Legal Working Group.

---

## 11. Expiry

After Phase 1 (12 months):

* All transitional delegated authority expires
* Any extension must be explicitly approved by a **Governance Process proposal** (≥60% approval, ≥7% quorum) submitted no later than 30 days before expiry

---

## 12. Relationship to the Charter

This document:

* Does **not modify the Charter**
* Exists solely to enable transition

In case of conflict:

* The Charter prevails for all permanent governance
* This framework applies only during Phase 1

---

## 13. Guiding Principle

> This framework exists to **enable the safe activation of decentralization**,
> not to concentrate or delay it.
