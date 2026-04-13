# Radix DAO Governance Structure

The Radix DAO operates using a **layered governance model**, designed to balance decentralization of authority, operational clarity, real-world execution capability, and long-term adaptability.

**This document is the full framework reference.** Not all documents in it are active simultaneously — governance complexity is introduced in deliberate phases. See the Activation Status section below for what is in force right now.

---

## Governance Architecture

![Radix DAO Governance Framework](RadixGovFramework.png)

*The diagram above illustrates the structural relationships between governance bodies — Token Holders, Proposal & Voting System, Execution & Treasury, Working Groups, Legal Entity, Authorized Signers, and the Accountability Council. It represents the architecture of the system, not its current activation status. For what is in force right now, see the Activation Status section below.*

---

## Governance Layers

### Charter (Principles)

The founding document of the DAO. Defines purpose, governance authority, core principles, treasury stewardship, and structural guarantees.

The Charter is the **highest authority** in the framework. All other documents derive their legitimacy from it and must be consistent with it. Changes to the Charter require a Constitutional proposal with supermajority approval.

---

### Governance Processes

Defines how the DAO operates in practice — how proposals are made and approved, how funds are allocated, how roles are assigned and governed, how disputes and emergencies are handled, and how the governance system itself evolves over time.

These documents are modular: each covers a distinct area of governance, can be updated independently (within governance rules), and connects to others through clearly defined references.

---

### Legal and Representation

Defines how the DAO operates in the real world: legal entity structure, asset custody and control, contractual representation, and the relationship to the Radix Foundation during transition.

---

### Execution Layer

Defines how decisions are carried out: Working Groups coordinate execution, contributors deliver work, and Authorized Signers execute treasury and legal actions. Execution authority is deliberately separated from decision-making authority.

---

## Three Distinct Areas of This Repository

This repository contains three distinct components that serve different purposes. Understanding the distinction is essential to navigating the material correctly.

### 1. The Governance Framework

The operational rulebook for the DAO — how decisions are made, resources allocated, roles governed, disputes resolved, and the system itself maintained. This is the ongoing, living system that the DAO operates under indefinitely.

Found in: `Charter/`, `Governance-Processes/`, `Working-Groups/`, `Parameters/`

The Governance Framework is introduced in three activation phases — see the Activation Status section below.

---

### 2. The Legal Entity

**Radix DLT DAO LLC** is a Marshall Islands DAO LLC that provides the DAO with real-world legal standing — the ability to hold assets, sign contracts, engage contributors, and interface with legal systems without individual token holders bearing personal liability.

The `Legal/` folder contains two distinct categories:

- **`Legal/Policy/`** — governance policy documents defining how the DAO uses its legal representation. These are part of the Governance Framework and follow the same activation and amendment rules as all other governance documents.
- **`Legal/Formation/`** — the actual corporate formation documents for Radix DLT DAO LLC. These are legal instruments, not governance policies. They include the Certificate of Formation, Operating Agreement, Beneficial Owner Information Report (BOIR) template, Asset Transfer Agreement, IP Schedule, and Continuity Statement. They are filed with MIDAO (the Marshall Islands DAO registry) and govern the legal entity's existence independently of the governance framework.

Found in: `Legal/`

---

### 3. The Transition

The Radix DAO succeeds the Radix Foundation, which is winding down and transferring its assets to the newly formed DAO. The Transition area documents how that handover works in practice.

- **Transition Governance Framework** — the rules governing Phase 1: what authority the RAC holds during bootstrapping, how Phase 1 ends, and what conditions must be met to progress.
- **Activation Roadmap** — the step-by-step operational guide for forming the legal entity and transitioning from Foundation governance to DAO governance: pre-registration, entity formation, initial governance proposals, asset transfer, and treasury setup.
- **Phase 1 Governance Proposal** — the proposal submitted to the Foundation governance system to formally launch Phase 1.

Found in: `Transition/`

---

## Activation Status

The governance framework is introduced in three phases. This is intentional — launching full operational complexity from day one creates unnecessary friction and denies the community the opportunity to refine policies through real-world use.

### Phase 1 — Minimum Viable Governance (Active at Launch)

These 10 documents are in force and enforceable from the first day of DAO operations. They are the minimum needed to safely receive assets, vote, execute decisions, respond to emergencies, and hold role holders accountable.

| Document | Location |
|---|---|
| Charter | Charter/ |
| DAO Parameters Registry | Parameters/ |
| Proposal & Voting Framework | Governance-Processes/Core/ |
| Execution & Treasury Actions Policy | Governance-Processes/Core/ |
| Emergency & Safeguards Policy | Governance-Processes/Core/ |
| Authorized Signers Rules | Governance-Processes/Roles/ |
| RAC Mandate | Governance-Processes/Roles/ |
| Conflict of Interest Policy | Governance-Processes/Roles/ |
| Code of Conduct | Governance-Processes/Core/ |
| Legal Wrapper & Representation | Legal/Policy/ |

---

### Phase 2 — Operational Governance (Activity-Triggered)

These documents activate when the DAO begins the relevant activity. They do not need to be enforced from day one — they become required the moment the specific operational need arises.

| Document | Location | Activation Trigger |
|---|---|---|
| Token Delegation Policy | Governance-Processes/Core/ | When governance platform supports delegation |
| Election & Role Governance Policy | Governance-Processes/Roles/ | Before first role term expires and elections are needed |
| Governance Continuity Framework | Governance-Processes/System-Integrity/ | Before first signer or RAC term ends |
| Governance Maintenance & Upgrade Framework | Governance-Processes/System-Integrity/ | Before first governance document amendment is proposed |
| Dispute Resolution & Arbitration Policy | Governance-Processes/System-Integrity/ | Before first formal dispute is escalated to the RAC |
| Open Source & IP Policy | Governance-Processes/Core/ | Before first grant or RFP with deliverables is issued |
| Source Code Stewardship Policy | Governance-Processes/Core/ | Before any code assets are received via asset transfer |
| Treasury Risk & Diversification Policy | Governance-Processes/Core/ | Before first diversification action is proposed |
| Working Group Framework | Governance-Processes/Execution/ | When first Working Groups are proposed by governance vote |
| Working Group Charter Template | Governance-Processes/Execution/ | When first Working Groups are proposed by governance vote |
| Transition Governance Framework | Transition/ | Active from launch (governs the transition period itself) |
| All Working Group Charters | Working-Groups/ | When each respective Working Group is approved by governance |

---

### Phase 3 — Mature Governance (Formal Governance Vote Required)

These policies are published and available now. They are expected to be followed in spirit from launch. They become **formally enforceable** — including under the dispute resolution and sanctions framework — only after a community governance vote approves each one.

The Governance & Legal Working Group is responsible for bringing each policy to a governance vote.

| Document | Location | Activation Trigger |
|---|---|---|
| Transparency & Reporting Policy | Governance-Processes/Core/ | Governance vote (target: Phase 2, month 2) |
| Contributor Compensation Policy | Governance-Processes/Core/ | Governance vote (target: Phase 2, month 3) |
| Grant Program Policy | Governance-Processes/Core/ | Governance vote (target: Phase 2, month 3) |
| Security Disclosure & Bug Bounty Policy | Governance-Processes/Core/ | Governance vote (target: Phase 2, month 4) |
| Ethics Reporting Policy | Governance-Processes/System-Integrity/ | Governance vote (target: Phase 2, month 4) |
| Contributor Onboarding & Offboarding | Governance-Processes/Execution/ | Governance vote (target: Phase 2, month 6) |
| Smart Contract Audit Policy | Governance-Processes/Core/ | Before any governance contract deployment is proposed |

---

## Full Document Index

```
Radix-DAO/
│
├── Charter/
│   └── charter.md                                              [Phase 1]
│
├── Governance-Processes/
│   │
│   ├── Core/
│   │   ├── Proposal-and-Voting-Framework.md                   [Phase 1]
│   │   ├── Execution-and-Treasury-Actions-Policy.md           [Phase 1]
│   │   ├── Emergency-and-Safeguards-Policy.md                 [Phase 1]
│   │   ├── Code-of-Conduct.md                                 [Phase 1]
│   │   ├── Token-Delegation-Policy.md                         [Phase 2 — on delegation support]
│   │   ├── OpenSource-and-Intellectual-Property-Policy.md     [Phase 2 — on first grant/RFP]
│   │   ├── Source-Code-Stewardship-Policy.md                  [Phase 2 — before code asset transfer]
│   │   ├── Treasury-Risk-and-Diversification-Policy.md        [Phase 2 — on first diversification]
│   │   ├── Transparency-and-Reporting-Policy.md               [Phase 3 — governance vote, month 2]
│   │   ├── Contributor-Compensation-Policy.md                 [Phase 3 — governance vote, month 3]
│   │   ├── Grant-Program-Policy.md                            [Phase 3 — governance vote, month 3]
│   │   ├── Security-Disclosure-and-Bug-Bounty-Policy.md       [Phase 3 — governance vote, month 4]
│   │   └── Smart-Contract-Audit-Policy.md                     [Phase 3 — on first contract deployment]
│   │
│   ├── System-Integrity/
│   │   ├── Dispute-Resolution-Arbitration-Policy.md           [Phase 2 — on first RAC escalation]
│   │   ├── Governance-Continuity.md                           [Phase 2 — before first term ends]
│   │   ├── Governance_Maintenance-and-Upgrade.md              [Phase 2 — on first doc amendment]
│   │   └── Ethics-Reporting-Policy.md                         [Phase 3 — governance vote, month 4]
│   │
│   ├── Roles/
│   │   ├── RAC-Mandate.md                                     [Phase 1]
│   │   ├── Authorized-Signers-Rules.md                        [Phase 1]
│   │   ├── Conflict-of-Interest-Policy.md                     [Phase 1]
│   │   └── Election-and-Role-Governance-Policy.md             [Phase 2 — before first election]
│   │
│   └── Execution/
│       ├── Working-Group-Framework.md                         [Phase 2 — on first WG proposal]
│       ├── Working-Group-Charter-Template.md                  [Phase 2 — on first WG proposal]
│       ├── Contributor-Onboarding-and-Offboarding.md          [Phase 3 — governance vote, month 6]
│       └── Proposals/
│           ├── PROP-001-Stokenet-Infrastructure-Takeover.md
│           └── PROP-002-Babylon-Gateway-Operator-TrellisTech.md
│
├── Working-Groups/
│   ├── WB-Strategic-Coordination/
│   │   └── Strategic-Coordination-WG-Charter.md
│   ├── WG-Governance-and-Legal/
│   │   └── Governance-and-Legal-WG-Charter.md
│   ├── WG-Product-and-Protocol/
│   │   └── Product-and-Protocol-WG-Charter.md
│   ├── WG-Ecosystem-Growth/
│   │   └── Ecosystem-Growth-WG-Charter.md
│   ├── WG-Community-and-Marketing/
│   │   └── Community-and-Marketing-WG-Charter.md
│   └── Working-Group-IOP-Template.md
│
├── Legal/
│   ├── Policy/
│   │   └── Legal-Wrapper-and-Representation.md
│   └── Formation/
│       ├── Certificate-of-Formation.md
│       ├── Operating-Agreement.md
│       ├── BOIR-Template.md
│       ├── Asset-Transfer-Agreement-Template.md
│       ├── IP-Schedule.md
│       └── Continuity-Statement-Template.md
│
├── Parameters/
│   └── DAO-Parameters-Registry.md
│
├── Transition/
│   ├── Transition-Governance-Framework.md
│   ├── Activation-Roadmap.md
│   └── Phase1-governance-proposal.md
│
└── Supporting-Materials/
    ├── governance-body-intro.md  ← you are here
    └── RadixGovFramework.png
```

---

## Design Principles

This layered, phased structure ensures:

* **Clear separation of authority** — decision-making and execution are distinct
* **No hidden power concentration** — all authority is defined and bounded
* **Operational flexibility** — the DAO can function effectively from day one without being overwhelmed by process
* **Resilience under failure** — continuity mechanisms exist for governance body failures
* **Ability to evolve** — each document is independently updatable within governance rules

---

## Modularity

Each document in this framework is:

* Focused on a single responsibility
* Independently updatable (within governance rules)
* Connected to others through clearly defined cross-references

This enables safer upgrades, easier community contribution, and better long-term maintainability. The full version history of all documents is tracked in [CHANGELOG.md](../CHANGELOG.md).

---

## Guiding Principle

> The governance system is designed to be:
> simple enough to understand, structured enough to operate, and flexible enough to evolve.
