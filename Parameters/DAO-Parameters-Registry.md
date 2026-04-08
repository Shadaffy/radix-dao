# DAO Parameters Registry

---

## 1. Purpose

This document defines the **configurable parameters** governing DAO operations.

These parameters:

* Enable flexibility without modifying core governance documents
* Provide clarity on thresholds, durations, and limits
* May be updated via governance proposals

---

## 2. Scope

This registry defines:

* Voting thresholds
* Quorum requirements
* Time durations
* Budget limits
* Emergency thresholds

---

## 3. Governance Parameters

---

### 3.1 Voting Durations

| Parameter               | Value    | Description                           |
| ----------------------- | -------- | ------------------------------------- |
| Draft Discussion Period | 5–7 days | Minimum time for community discussion |
| Review Period           | 2–3 days | Time between submission and voting    |
| Voting Period           | 5–7 days | Duration of voting                    |

---

### 3.2 Quorum Requirements

Quorum is measured as a percentage of eligible voting power. Eligible voting power includes liquid XRD holdings and LSU holdings converted to their XRD equivalent at the time of the voting snapshot.

| Proposal Type      | Quorum                      |
| ------------------ | --------------------------- |
| Constitutional     | 10% of eligible voting power |
| Governance Process | 7%                     |
| Treasury / Budget  | 5%                     |
| Executable         | 5%                     |
| Signaling          | 3%                     |

---

### 3.3 Approval Thresholds

| Proposal Type      | Approval  |
| ------------------ | --------- |
| Constitutional     | ≥ 66% YES |
| Governance Process | ≥ 60% YES |
| Treasury / Budget  | ≥ 50% YES |
| Executable         | ≥ 50% YES |
| Signaling          | ≥ 50% YES |

---

### 3.4 Cooldown Periods

| Scenario               | Cooldown    |
| ---------------------- | ----------- |
| Failed Proposal        | 7 days      |
| Minor Fix Resubmission | No cooldown |
| Major Resubmission     | 7 days      |

---

## 4. Veto Parameters

| Parameter                  | Value              |
| -------------------------- | ------------------ |
| Veto Window                | 48 hours post-vote |
| Minimum Participation      | 3% quorum (XRD and LSU-equivalent combined) |
| Optional Stake Requirement | None               |

---

## 5. RAC Parameters

---

### 5.1 RAC Composition

| Parameter                        | Value                                                                  |
| -------------------------------- | ---------------------------------------------------------------------- |
| Members                          | 3–5 (exact count set by initial governance vote before Phase 1 launch) |
| Term Length                      | 6 months                                                               |
| Routine Decision Quorum          | Simple majority (more than half of seated members)                     |
| Routine Decision Approval        | Simple majority YES                                                    |

---

### 5.2 RAC Emergency Thresholds

| Parameter                 | Value         |
| ------------------------- | ------------- |
| Quorum                    | ≥ 2/3 members |
| Approval Threshold        | ≥ 75%         |
| Emergency Action Duration | Max 7 days    |

---

## 6. Treasury Parameters

---

### 6.1 Budget Limits

| Parameter                | Value                |
| ------------------------ | -------------------- |
| Working Group Budget Cap | Defined per proposal |
| Single Transaction Limit | Set by initial governance vote before Phase 1 launch |
| Emergency Spend Limit    | Set by initial governance vote before Phase 1 launch |

---

### 6.2 Treasury Structure

| Parameter                 | Value       |
| ------------------------- | ----------- |
| Multi-account Requirement | Yes         |
| Multisig Threshold        | See §6A: 3-of-5 standard, 4-of-5 high-risk |
| Audit Requirement         | Recommended |

---

## 6A. Authorized Signers Parameters

| Parameter                       | Value                           | Description                                           |
| ------------------------------- | ------------------------------- | ----------------------------------------------------- |
| Number of Authorized Signers    | 5                               | Total signer pool                                     |
| Minimum Signing Threshold       | 3 of 5                          | Minimum approvals required for standard actions       |
| High-Risk Signing Threshold     | 4 of 5                          | Minimum approvals required for high-risk actions      |
| Signer Term Length              | 6 months                        | Standard appointment term                             |
| Max Execution Window            | 5 business days                 | Time allowed to execute an approved action            |
| Max Acknowledgement Window      | 2 business days                 | Time allowed to acknowledge a valid execution request |
| Emergency Execution Window      | ASAP, within 24 hours           | Required response time during emergencies             |
| Required Availability Standard  | Respond within 48 hours         | Minimum expected responsiveness                       |
| Key Rotation Review Interval    | Every 6 months                  | Frequency of key / access review                      |
| Max Unexcused Inactivity Period | 14 days                         | Inactivity threshold before replacement review        |
| Signer Replacement Window       | 21 days                         | Time to fill a vacant signer seat                     |
| Allowed Unilateral Actions      | None unless explicitly approved | Default rule for signer authority                     |
| Conflict Disclosure Requirement | Mandatory                       | Public or confidential as appropriate                 |
| Signer KYC Requirement          | Required where applicable       | Compliance standard                                   |

---

## 6B. Elections & Roles Parameters

| Parameter                           | Value     | Description                              |
| ----------------------------------- | --------- | ---------------------------------------- |
| Standard Term Length                | 6 months  | Default role duration                    |
| Election Voting Duration            | 5-7 days  | Length of election voting                |
| Nomination Period                   | 5-7 days  | Time allowed for candidate submissions   |
| Minimum Participation for Elections | Gov quorum| Quorum requirement                       |
| Removal Vote Threshold              | ≥ 50% YES | Required support to remove a role holder |
| Inactivity Threshold                | 14 days   | Time before inactivity review            |
| Replacement Election Trigger Time   | 7 days    | Time before election must start          |
| Replacement Completion Time         | 21 days   | Max time to fill vacancy                 |
| Max Concurrent Roles per Individual | 2         | Limits role concentration                |
| Conflict Disclosure Requirement     | Mandatory | Required for all roles                   |

---

## 6C. Dispute Resolution Parameters

| Parameter                       |   Value   | Description                          |
| ------------------------------- | --------- | ------------------------------------ |
| Level 1 Resolution Window       | 3–5 days  | Time for direct resolution           |
| Level 2 Mediation Window        | 5–7 days  | WG mediation time                    |
| RAC Review Window               | 5–7 days  | Time for RAC review                  |
| Max Escalation Time             | 21 days   | Total allowed escalation time        |
| Signer Response Time            | 48 hours  | Time to respond to execution request |
| Signer Dispute Escalation Time  | 48 hours  | Time before escalation allowed       |
| Misconduct Review Window        | 7–14 days | Time to review misconduct claims     |
| Governance Escalation Threshold | quorum    | Participation required to escalate   |
| Abuse Threshold                 | Case by case (RAC discretion, subject to DAO review) | Limit on repeated frivolous disputes |

---

## 7. Working Group Parameters

| Parameter           | Value    |
| ------------------- | -------- |
| Stewards per WG     | 2–3      |
| Term Length         | 6 months |
| Reporting Frequency | Biweekly |

---

## 8. Identity & Participation Parameters

| Parameter        | Value        |
| ---------------- | ------------ |
| Voting Basis     | XRD holdings and LSU (converted to XRD-equivalent via snapshot) |
| LSU Inclusion    | Active (Phase 1) — snapshot-based XRD conversion               |
| Delegation       | Allowed (Phase 2, when platform supports delegation) |
| Sybil Resistance | Deferred to Phase 2             |

---

## 9. Execution Parameters

| Parameter                 | Value          |
| ------------------------- | -------------- |
| Execution Delay           | None by default (Phase 1)       |
| High-Risk Execution Delay | 24 hours recommended            |

---

## 9A. Governance Continuity Parameters

| Parameter | Value | Description |
|---|---|---|
| Governance Inactivity Trigger | 3 consecutive quorum failures on the same proposal type | Threshold before reduced quorum activates |
| Reduced Quorum Threshold | 50% of the standard quorum for that proposal type (minimum 1%) | Applies after inactivity trigger is met |
| Extended Voting Period | Double the standard voting duration | Applies alongside reduced quorum during inactivity |
| Reconstitution Deadline | 30 days after failure event | Maximum time to re-establish a failed role or body |

---

## 10. Emergency Parameters

| Parameter           | Value           |
| ------------------- | --------------- |
| Emergency Duration  | Max 7 days      |
| Disclosure Deadline | Within 48 hours |
| Post-Review Window  | 7 days          |

---

## 11. Amendment Rules

This registry may be updated via governance proposals.

Changes are classified as:

* Minor (parameter adjustment)
* Major (structural change)

---

## 12. Versioning

Each update must include:

* Version number
* Change log
* Effective date

---

## 13. Guiding Principle

> Parameters should enable flexibility without compromising
> the integrity and security of governance.
