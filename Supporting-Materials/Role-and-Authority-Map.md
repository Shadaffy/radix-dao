# Role and Authority Map

This document is a reference summary of all roles, their authority, their limitations, and how the governance-layer terminology maps to the legal-layer terminology in the Operating Agreement.

> **Non-normative notice:** This document is explanatory. The authoritative document hierarchy is defined in [PRECEDENCE-AND-STATUS.md](../PRECEDENCE-AND-STATUS.md) and the [Charter](../Charter/charter.md). Where this document conflicts with a normative document, the normative document prevails.

For parameter values (term lengths, quorum thresholds, signing thresholds) see the [DAO Parameters Registry](../Parameters/DAO-Parameters-Registry.md). For election and removal procedures see the [Election & Role Governance Policy](../Governance-Processes/Roles/Election-and-Role-Governance-Policy.md).

---

## 1. Authority Hierarchy

```
Token Holders (sovereign — all authority flows from here)
│
├── RAC (Accountability Council)
│     Guardian of process. Oversight, emergency response,
│     Phase 1 transitional coordination. NOT a decision-maker.
│
├── Working Groups
│     Execution coordination within approved mandates.
│     NOT a decision-making or strategic body.
│
└── Authorized Signers / Operational Delegates
      Execute treasury and legal actions approved by governance.
      NOT a decision-making body.
```

All delegated authority is bounded, time-limited, and revocable by governance vote. No body exercises authority independent of token-holder governance decisions.

---

## 2. Role Crosswalk: Governance Layer → Operating Agreement

| Governance-Layer Role | Operating Agreement Equivalent | OA Section |
|---|---|---|
| Authorized Signer (Treasury) | Delegate — Treasury Signing function | §5.3(a) |
| Authorized Signer (Legal) | Delegate — Legal Signatory function | §5.3(c) |
| Governance Operator | Delegate — Governance Operations function | §5.3(b) |
| Compliance Liaison | Delegate — Compliance Liaison function | §5.3(d) |
| Web2 Custodian | Delegate — Web2 Custodian function | §5.3(e) |
| RAC Member | No OA Delegated Function — oversight body | Charter §8, RAC Mandate |
| Working Group Steward | No OA Delegated Function — execution coordinator | WG Framework |

The Operating Agreement calls all five operational role-holders "Delegates" performing "Delegated Functions" (OA Article V). The governance policy layer uses distinct role names (Authorized Signers, Governance Operator, etc.) for operational clarity. These are the same people described from two different vantage points. See [Glossary — Delegate (Operational)](../GLOSSARY.md) for the full disambiguation.

---

## 3. Role Profiles

### 3.1 Token Holders

| | |
|---|---|
| **What they are** | Members of the DAO LLC; ultimate source of all governance authority |
| **How they act** | On-chain governance votes via the Governance Platform |
| **CAN** | Propose and vote on any matter; override any delegated body by governance vote; revoke any elected role; delegate voting power |
| **CANNOT** | Act unilaterally on behalf of the LLC; bind the entity without a governance vote |
| **Legal status** | Members of Radix DLT DAO LLC (Operating Agreement §4.1) |
| **Source docs** | [Charter](../Charter/charter.md), [Operating Agreement Article IV](../Legal/Formation/Operating-Agreement.md), [Proposal & Voting Framework](../Governance-Processes/Core/Proposal-and-Voting-Framework.md) |

---

### 3.2 Accountability Council (RAC)

| | |
|---|---|
| **What they are** | Minimum 5 elected members (exact count set by Constitutional Proposal; see Parameters §5.1); guardian of process integrity, not a decision-making authority |
| **Elected by** | Governance vote (two-stage election per Elections Policy) |
| **Term** | 6 months, renewable |
| **CAN** | Validate proposals meet submission requirements; trigger defined governance processes; formally determine vote outcomes; review veto challenges; declare emergencies; coordinate emergency response; (Phase 1 only) exercise limited transitional delegated authority |
| **CANNOT** | Override or invalidate a valid governance vote; make unilateral strategic or treasury decisions; suppress proposals arbitrarily; introduce new rules without governance approval |
| **Phase 1 additions** | Limited transitional authority under Transition Framework §5: facilitate asset transfer, resolve minor governance ambiguities, coordinate urgent operational decisions (with 48-hour harm threshold and retrospective disclosure). Interim execution authority for RFPs within DAO-approved budgets where no Working Group exists (§5.4) |
| **Source docs** | [RAC Mandate](../Governance-Processes/Roles/RAC-Mandate.md), [Charter §8](../Charter/charter.md), [Transition Framework §4–6](../Transition/Transition-Governance-Framework.md), [Emergency Policy §5](../Governance-Processes/Core/Emergency-and-Safeguards-Policy.md) |

---

### 3.3 Authorized Signers

| | |
|---|---|
| **What they are** | Pool of 5 elected individuals; execute treasury and legal actions approved by governance. OA equivalent: Delegates holding Treasury Signing and Legal Signatory Delegated Functions |
| **Elected by** | Governance vote |
| **Term** | 6 months, renewable |
| **Signing thresholds** | Standard actions: 3-of-5; high-risk actions: 4-of-5 |
| **CAN** | Execute treasury transfers authorized by governance; sign legal agreements authorized by governance; operate approved custody systems; perform administrative actions to maintain DAO operations; refuse or delay execution on defined grounds (procedural, legal, security) |
| **CANNOT** | Make strategic decisions; approve new spending; change proposal intent; act outside approved mandates; withhold execution for political reasons; sign self-benefiting transactions without recusal |
| **OA mapping** | Treasury Signers = OA §5.3(a); Legal Signatories = OA §5.3(c) — both are Delegates under OA Article V |
| **Source docs** | [Authorized Signers Rules](../Governance-Processes/Roles/Authorized-Signers-Rules.md), [Operating Agreement §5.3(a), §5.3(c)](../Legal/Formation/Operating-Agreement.md), [Legal Wrapper §7–8](../Legal/Policy/Legal-Wrapper-and-Representation.md), [Execution & Treasury Actions Policy](../Governance-Processes/Core/Execution-and-Treasury-Actions-Policy.md) |

---

### 3.4 Governance Operator

| | |
|---|---|
| **What they are** | Elected member(s) who administer the governance platform. OA equivalent: Delegate holding the Governance Operations Delegated Function |
| **CAN** | Elevate approved Temperature Checks to Governance Proposals via the Owner Badge; update governance parameters per governance vote; maintain the Governance smart contract |
| **CANNOT** | Modify, delay, or suppress an eligible proposal elevation; alter vote parameters after a vote has opened; act outside the scope of passed governance decisions |
| **OA mapping** | OA §5.3(b) Governance Operations Delegated Function |
| **Source docs** | [Operating Agreement §5.3(b), §6.1–6.2](../Legal/Formation/Operating-Agreement.md), [Proposal & Voting Framework](../Governance-Processes/Core/Proposal-and-Voting-Framework.md) |

---

### 3.5 Compliance Liaison

| | |
|---|---|
| **What they are** | Delegate holding the Compliance Liaison Delegated Function; manages entity compliance and KYC |
| **CAN** | Act as Registered Agent liaison; file annual BOIR; coordinate KYC for Delegates and UBO Members; maintain KYC and sanctions records; monitor UBO thresholds; designate the Registered Agent by governance proposal |
| **CANNOT** | Make strategic decisions; access treasury without authorization; disclose confidential KYC records except as required by law |
| **OA mapping** | OA §5.3(d) Compliance Liaison Delegated Function |
| **Source docs** | [Operating Agreement §5.3(d), §8](../Legal/Formation/Operating-Agreement.md), [Legal Wrapper §7A](../Legal/Policy/Legal-Wrapper-and-Representation.md) |

---

### 3.6 Web2 Custodian

| | |
|---|---|
| **What they are** | Delegate holding the Web2 Custodian Delegated Function; manages Web2 assets and credentials |
| **CAN** | Manage social media accounts, GitHub repositories, domain names, and other Web2 assets using an enterprise password manager |
| **CANNOT** | Transfer domain ownership or delete repositories without a Governance Proposal |
| **OA mapping** | OA §5.3(e) Web2 Custodian Delegated Function |
| **Source docs** | [Operating Agreement §5.3(e)](../Legal/Formation/Operating-Agreement.md) |

---

### 3.7 Working Group Stewards

| | |
|---|---|
| **What they are** | 2–3 elected leaders of each Working Group; coordinate execution within the WG's approved mandate and budget |
| **Elected by** | Governance vote |
| **Term** | 6 months, renewable |
| **CAN** | Manage workstreams and contributors within approved budget; engage contractors within approved scope; report progress to the DAO; (Micro grants only) approve small grants without a DAO vote |
| **CANNOT** | Override governance decisions; create financial obligations beyond approved budgets; define DAO strategy; act as legal representatives of the LLC |
| **OA mapping** | No OA Delegated Function — WG Stewards are execution coordinators, not Operational Delegates |
| **Source docs** | [Working Group Framework](../Governance-Processes/Execution/Working-Group-Framework.md), [Election & Role Governance Policy](../Governance-Processes/Roles/Election-and-Role-Governance-Policy.md) |

---

## 4. Document Hierarchy (Quick Reference)

```
Charter  (highest authority — Constitutional proposal to amend)
    │
    ├── Governance Policies  (Governance Process proposal to amend)
    │       Proposal & Voting Framework
    │       Execution & Treasury Actions Policy
    │       Emergency & Safeguards Policy
    │       RAC Mandate
    │       Authorized Signers Rules
    │       Conflict of Interest Policy
    │       Code of Conduct
    │       Legal Wrapper & Representation
    │       DAO Parameters Registry
    │       + Phase 2/3 activity-triggered policies
    │
    └── Formation Documents  (legal instruments — NOT governance policies)
            Operating Agreement  ← controls where not delegated to policy
            Certificate of Formation
            BOIR Template
            Asset Transfer Agreement
            IP Schedule
            Continuity Statement Template
```

**Conflict resolution rule:** Where the Operating Agreement expressly delegates a matter to governance policy, the policy controls. Where they conflict on a matter not delegated, the Operating Agreement prevails. The Charter prevails over all. See [Governance Maintenance & Upgrade Framework §3.1](../Governance-Processes/System-Integrity/Governance_Maintenance-and-Upgrade.md) for the full rule.

---

## 5. Phase 1 Transition Modifications

During Phase 1 (first 12 months), the following modifications apply:

| Normal rule | Phase 1 modification |
|---|---|
| Working Groups coordinate execution | RAC may act as interim execution body where no relevant WG exists (Transition Framework §5.4) |
| All RAC authority permanent | RAC holds additional limited transitional delegated authority (Transition Framework §5.1–5.2); expires automatically at Phase 1 end |
| Standard governance timeline for urgent decisions | RAC may act within 48 hours where delay would cause material harm, with retrospective disclosure |
| Authorized Signers appointed by prior election | Initial Authorized Signers appointed as a founding act at DAO launch, transitioning to standard elections at first term renewal |

All Phase 1 transitional authority is strictly bounded, publicly disclosed, and subject to community challenge within 14 days. See [Transition Governance Framework](../Transition/Transition-Governance-Framework.md) for full detail.

---

*This document is maintained by the Governance & Legal Working Group. Amendments require a Governance Process proposal.*
