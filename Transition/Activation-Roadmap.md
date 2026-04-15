# DAO Activation Roadmap

## Radix DLT DAO LLC — From RAC Election to Fully Operational DAO

> **Assumptions:**
> - RAC members have been elected by the community through the community-deployed Consultation V2 governance system
> - Unless a RAC member notifies intent to withdraw, all elected RAC members carry forward as founding Delegates
> - The Consultation V2 on-chain governance system is already deployed and operational
> - The 10 Phase 1 governance documents are drafted and ready for adoption
>
> **How to read this document:**
> Each step is marked with who acts, what the action is, and (for governance proposals) the required threshold and vote type. Steps must be completed in order within each phase. Steps within the same sub-section may be parallelised where noted.

---

## Phase 0 — Pre-Registration Preparation

These steps do not require a governance vote. The RAC carries them out under its founding transitional authority (Transition Governance Framework §5.1). All actions must be published to the governance forum within 72 hours of completion.

---

### 0.1 Confirm Delegate Roster and Function Assignments

**Actor:** RAC (collectively)

The five Delegated Functions under Operating Agreement §5.3 must be assigned before registration. Each function must have at least one holder. Treasury Signing requires a minimum of three holders (multi-signature requirement).

| Delegated Function | Minimum Holders | Notes |
|---|---|---|
| Treasury Signing (§5.3(a)) | 3 (standard multisig) | Maximum 5 for 3-of-5 config |
| Governance Operations (§5.3(b)) | 1 | Holds Owner Badge / adminBadge |
| Legal Signatory (§5.3(c)) | 1 | Signs formation documents and ATA |
| Compliance Liaison (§5.3(d)) | 1 | Files BOIR; manages KYC records |
| Web2 Custodian (§5.3(e)) | 1 | Controls repositories and domains |

RAC members may hold more than one function. Disclose any dual-function arrangement in the Delegate Roster published to the governance forum.

**Output:** A published Delegate Roster document listing each member's assigned function(s) and their Radix Network wallet address(es).

---

### 0.2 Complete KYC — All Delegates (KYC Tier 1)

**Actor:** Each individual Delegate; coordinated by Compliance Liaison

All Delegates must complete KYC verification through the designated provider (SumSub) **before** assuming any Delegated Function. This is a hard prerequisite — the Operating Agreement, BOIR filing, and MI DAO Act all require it.

- KYC Tier 1 applies to all five function types
- Collect: full legal name, date of birth, nationality, residential address, passport details, associated wallet address(es)
- KYC Tier 2 (UBO/BOIR) also applies to any Delegate holding ≥25% of total eligible voting power

**Output:** Compliance Liaison confirms in writing that all Delegates have passed KYC and holds verified records ready for BOIR filing.

---

### 0.3 Record Consultation V2 Smart Contract Identifiers

**Actor:** Governance Operator

Retrieve and document the three on-ledger identifiers from the Consultation V2 deployment. These are required for the Certificate of Formation and Operating Agreement §1.4.

| Identifier | Description |
|---|---|
| `packageAddress` | Scrypto package identifier |
| `componentAddress` | Instantiated governance component |
| `adminBadgeAddress` | Owner Badge — used to elevate Temperature Checks to Governance Proposals |

**Output:** Confirmed address table, published to governance forum and inserted into Operating Agreement §1.4 before filing.

---

### 0.4 Establish Multi-Signature Treasury Wallet

**Actor:** Treasury Signers (coordinated by RAC)

Set up the multi-signature treasury wallet on the Radix Network:

- **Standard threshold:** 3-of-5 signatures required (per DAO Parameters §6A)
- **High-risk threshold:** 4-of-5 signatures required
- Each Treasury Signer's wallet address must match the KYC-verified address on record

Confirm the wallet address is published before registration, as it is a material detail of the entity's custody structure.

**Output:** Multi-sig wallet address published on governance forum; confirmed in writing by all Treasury Signers.

---

## Phase 0 Governance Proposal — Pre-Registration

This proposal runs through the **community's own Consultation V2 deployment** — the governance system the community operates independently of the Founding Transferor. The DAO entity does not yet legally exist, but the community already governs itself on-chain. This is the founding act that brings the legal entity into existence and gives the governance framework formal legal standing.

---

### GP-PRE-1: DAO Formation and Framework Adoption

**Type:** Combined Constitutional + Formation Authorization
**Threshold:** ≥66% approval / ≥10% quorum (Constitutional standard, as this establishes the Charter and authorizes entity formation)
**Process:** Temperature Check (7 days) → Governance Proposal (14 days)

**This single pre-registration proposal covers:**

1. **Governance Framework Adoption** — Formally adopt the following 10 Phase 1 documents as the founding governance framework of the DAO:
   - Charter
   - DAO Parameters Registry
   - Proposal & Voting Framework
   - Execution & Treasury Actions Policy
   - Emergency & Safeguards Policy
   - Authorized Signers Rules
   - RAC Mandate
   - Conflict of Interest Policy
   - Code of Conduct
   - Legal Wrapper & Representation

2. **Entity Formation Authorization** — Authorize the Legal Signatory to file the Certificate of Formation with MIDAO Directory Services, Inc. on behalf of the founding Members, using the Operating Agreement as filed.

3. **Founding Delegate Ratification** — Ratify the Delegate Roster prepared in step 0.1, confirming which elected RAC members hold which Delegated Functions under the new entity.

4. **Transition Governance Framework Authorization** — Confirm that the Transition Governance Framework is in force from the date of entity formation, granting the RAC its Phase 1 transitional delegated authority.

**Why one proposal:** The community should vote on the entire founding act as a single coherent decision, not as separate questions. Splitting it creates the risk that the framework is adopted without the entity, or the entity is formed without the framework. They are inseparable.

---

## Phase 1 — Entity Registration

**Actor:** Legal Signatory Delegate

Following passage of GP-PRE-1, the Legal Signatory files with MIDAO Directory Services, Inc., Majuro, Republic of the Marshall Islands:

| Filing | Document | Notes |
|---|---|---|
| Certificate of Formation | `Legal/Formation/Certificate-of-Formation.md` | Include Consultation V2 addresses in smart contract field |
| Operating Agreement | `Legal/Formation/Operating-Agreement.md` | Complete §1.4 with confirmed addresses before filing |
| Registered Agent engagement | MIDAO standard form | Pay formation and annual fees |

**Output:** Confirmation of formation from MIDAO. The entity **Radix DLT DAO LLC** now exists as a legal person under Marshall Islands law. Record the formation date and publish it to the governance forum within 72 hours.

---

## Phase 2 — Post-Registration: Activate the Entity

All proposals from this point forward are run through the DAO's **own** governance system (Consultation V2). The entity is now the legal decision-maker. Proposals follow the two-stage process: Temperature Check → Governance Proposal.

---

### GP-1: File Initial BOIR

**Type:** Governance Process
**Threshold:** ≥60% approval / ≥7% quorum
**Urgency:** File within 30 days of formation (DAO Act §712(1))

Authorize the Compliance Liaison to file the initial Beneficial Owner Information Report with MIDAO Directory Services using `Legal/Formation/BOIR-Template.md`. The BOIR lists all current Delegates (all qualify as beneficial members under §702(r) through actual control). Confirm that all Delegates have current, verified KYC before filing.

This proposal may be expedited — if the 30-day window is tight after GP-PRE-1 and registration, the RAC may coordinate the BOIR filing as an administrative act under §5.1 transitional authority and publish it to the governance forum immediately, with retrospective ratification via GP-1.

---

### GP-2: Adopt Operational Policies under OA §12.4

**Type:** Governance Process
**Threshold:** ≥60% approval / ≥7% quorum

Formally adopt the 10 Phase 1 governance documents as subordinate operational policies of Radix DLT DAO LLC under Operating Agreement §12.4. This is the bridge between the community governance framework and the legal entity — it makes the governance documents legally binding on the entity and on Delegates.

The proposal should list each document by name and confirm that it is in force as an operational policy from the date of the vote.

> **Note:** This is the second adoption of these documents — the first was GP-PRE-1 on the community's Consultation V2 before the entity existed. GP-2 re-enacts the adoption under the legal entity's own authority per OA §12.4. The governance tool is the same; what changes is the legal standing that makes the documents formally binding on the entity and its Delegates.

---

### GP-3: Set DAO Parameters §6.1 Treasury Limits

**Type:** Treasury
**Threshold:** ≥60% approval / ≥7% quorum

Set the two currently unresolved values in DAO Parameters §6.1:

- **Single Transaction Limit** — maximum value that Treasury Signers may execute in a single transaction without an additional governance approval step
- **Emergency Spend Limit** — maximum value that may be spent under emergency authority

These values cannot be left blank once the treasury holds assets. The proposal should set initial values and state that they may be revised by a subsequent Treasury proposal.

---

## Phase 3 — Asset Transfer

These steps prepare for and execute the transfer of assets from the Founding Transferor. They must be completed in strict order.

---

### GP-4: Approve Asset Transfer Agreement and IP Schedule

**Type:** Constitutional (this is the most consequential single decision the DAO makes — it defines what it receives and under what terms)
**Threshold:** ≥66% approval / ≥10% quorum

Publish the completed Asset Transfer Agreement (`Legal/Formation/Asset-Transfer-Agreement-Template.md` as filled in with the Founding Transferor) and the completed IP Schedule (`Legal/Formation/IP-Schedule.md`) for community review. The proposal must include:

1. The full text of the Asset Transfer Agreement as it will be signed
2. The completed IP Schedule enumerating every asset being transferred (repositories with commit hashes, license rights, trademarks, patents, documentation)
3. Authorization for the Legal Signatory to execute both documents on behalf of the DAO
4. Activation of the Open Source & IP Policy and Source Code Stewardship Policy (required before any asset with code deliverables is received — Transition Governance Framework §3.2)

**Minimum community review period:** 14 days before the vote opens. The IP Schedule in particular must be publicly visible so that the community can verify the enumerated assets match their understanding of what the DAO is receiving.

---

### Execute Asset Transfer (Non-Governance Actions)

Once GP-4 passes, the following actions are carried out by the Legal Signatory and Compliance Liaison:

| Action | Actor | Document |
|---|---|---|
| Sign Asset Transfer Agreement | Legal Signatory | `Legal/Formation/Asset-Transfer-Agreement-Template.md` |
| Receive completed IP Schedule from Founding Transferor | Compliance Liaison | `Legal/Formation/IP-Schedule.md` |
| Execute Continuity Statement | Legal Signatory + Compliance Liaison | `Legal/Formation/Continuity-Statement-Template.md` |
| File Continuity Statement with Registered Agent | Compliance Liaison | |
| Publish Acceptance Statement to governance forum | Legal Signatory | Within 72 hours of transfer |
| Record provenance in DAO records | Compliance Liaison | Per Operating Agreement §9.3 |
| Updated BOIR (if asset transfer changes reportable information) | Compliance Liaison | Within 30 days of change |

The Acceptance Statement published to the governance forum is the public record that the transfer is complete. It must include: confirmation that the ATA is signed, that the IP Schedule is complete, that the Continuity Statement is executed, the on-chain transaction reference for any token or asset transfer, and confirmation that all conditions precedent in the ATA have been met.

---

## Phase 4 — Working Group Activation

Working Groups are the operational layer of the DAO. Each requires its own governance proposal to establish a Charter and appoint initial Stewards. They should be established in priority order based on operational need.

The Working Group Framework document must be formally activated before any Working Group is established (Transition Governance Framework §3.2). This can be bundled into the first Working Group proposal if not already activated.

**Staggered Term Start — Group A and Group B**

To avoid simultaneous renewal of all Working Group Stewards every 6 months, Working Groups are split into two groups with staggered term start dates:

| Group | Working Groups | Initial Term Start |
|---|---|---|
| Group A | Governance & Legal WG, Protocol & Engineering WG, Ecosystem Growth WG | Month 1 — established at DAO launch per GP-5 through GP-7 |
| Group B | Community & Marketing WG, Infrastructure & Security WG, Market Making & Liquidity WG, Strategic Coordination WG | Month 4 — established approximately 90 days after DAO launch per GP-8 through GP-10 |

This stagger means Group A and Group B renewal windows are offset by ~3 months, ensuring that at most half of all WG Stewards are in a renewal cycle at any one time. This applies to both auto-renewals and any contested elections triggered by a challenge proposal (see Election & Role Governance Policy §9).

---

### GP-5: Activate Working Group Framework + Establish Governance & Legal Working Group

**Type:** Governance Process
**Threshold:** ≥60% approval / ≥7% quorum
**Priority:** Highest — this Working Group governs the DAO's own governance processes

**Working Group Framework activation:** Formally activate the Working Group Framework document per Transition Governance Framework §3.2.

**G&L Working Group Charter:** Define mandate, initial Stewards, and operating scope:
- Governance maintenance and document amendments
- Legal compliance (BOIR, registered agent, sanctions)
- Framework development (drafting Phase 2 and Phase 3 policies on schedule)
- Oversight of the Election & Role Governance Policy activation

This Working Group takes over the RAC's governance coordination functions progressively as it becomes operational.

---

### GP-6: Establish Protocol & Engineering Working Group

**Type:** Governance Process
**Threshold:** ≥60% approval / ≥7% quorum
**Priority:** Critical — covers technical network operations

**P&E Working Group Charter:** Define mandate, initial Stewards, and operating scope:
- Protocol maintenance, development, and upgrade coordination
- Smart contract governance (RFC process, security review, deployment)
- Source code stewardship and repository governance (access control, versioning, security patching per Source Code Stewardship Policy)
- Secure development lifecycle standards
- Smart contract audit coordination prior to any governance contract deployment
- Technical roadmap governance

**Transition action:** Once the P&E Working Group is operational, the RAC's interim execution authority for any technical RFPs or code-related work (Transition Governance Framework §5.4) lapses for that workstream. The Working Group takes over.

This Working Group is the primary interface for ongoing Radix Network protocol work after the Founding Transferor's development team transitions responsibilities.

---

### GP-7: Establish Treasury & Finance Working Group

**Type:** Governance Process
**Threshold:** ≥60% approval / ≥7% quorum
**Priority:** High — required before significant treasury operations begin

**T&F Working Group Charter:** Define mandate, initial Stewards, and operating scope:
- Treasury management and custody oversight
- Financial reporting (quarterly transparency reports)
- Grant program administration (once Grant Program Policy is formally activated)
- Treasury Risk & Diversification Policy activation coordination

This Working Group also takes over the Authorized Signers operational oversight from the RAC.

---

### GP-8: Establish Community & Ecosystem Working Group

**Type:** Governance Process
**Threshold:** ≥60% approval / ≥7% quorum
**Priority:** Medium — supports ecosystem growth but not blocking for network operations

**C&E Working Group Charter:** Define mandate, initial Stewards, and operating scope:
- Community engagement and contributor onboarding
- Ecosystem grants and partnership coordination
- Communications, documentation, and public-facing governance transparency

---

### GP-9: Establish Infrastructure & Security Working Group

**Type:** Governance Process
**Threshold:** ≥60% approval / ≥7% quorum
**Priority:** High — required for network security continuity

**I&S Working Group Charter:** Define mandate, initial Stewards, and operating scope:
- Security monitoring of DAO-controlled infrastructure
- Vulnerability disclosure and bug bounty programme coordination (per Security Disclosure & Bug Bounty Policy once formally activated)
- Information security compliance standards
- Critical infrastructure oversight and SLA monitoring (node operations, RPC endpoints, gateway)
- Emergency response coordination with the RAC under Emergency & Safeguards Policy

This Working Group acts as the DAO's CIO/CISO function. It handles proactive security monitoring, infrastructure oversight, and compliance — the RAC handles emergency response authority.

---

## Proposal Sequence Summary

| # | Proposal | Type | Threshold | Phase | Blocking For |
|---|---|---|---|---|---|
| GP-PRE-1 | DAO Formation and Framework Adoption | Constitutional | ≥66% / ≥10% | Pre-registration | Registration |
| GP-1 | File Initial BOIR | Governance Process | ≥60% / ≥7% | Post-registration | MI compliance |
| GP-2 | Adopt Operational Policies (OA §12.4) | Governance Process | ≥60% / ≥7% | Post-registration | Full legal binding of framework |
| GP-3 | Set Treasury Limits (DAO Parameters §6.1) | Treasury | ≥60% / ≥7% | Post-registration | Treasury operations |
| GP-4 | Approve Asset Transfer Agreement + IP Schedule | Constitutional | ≥66% / ≥10% | Asset transfer | Receiving assets |
| GP-5 | Working Group Framework + G&L WG | Governance Process | ≥60% / ≥7% | Working groups | All subsequent WGs |
| GP-6 | Protocol & Engineering Working Group | Governance Process | ≥60% / ≥7% | Working groups | Network ops transition |
| GP-7 | Treasury & Finance Working Group | Governance Process | ≥60% / ≥7% | Working groups | Grant/treasury programs |
| GP-8 | Community & Ecosystem Working Group | Governance Process | ≥60% / ≥7% | Working groups | Ecosystem programs |
| GP-9 | Infrastructure & Security Working Group | Governance Process | ≥60% / ≥7% | Working groups | Security continuity |

---

## Activity-Triggered Policy Activations (As Operations Expand)

These do not require separate proposals — they activate by the trigger conditions in Transition Governance Framework §3.2. The G&L Working Group tracks and announces each activation.

| Policy | Trigger | Activates With |
|---|---|---|
| Open Source & IP Policy | Before any grant or RFP with code deliverables | GP-4 (asset transfer) |
| Source Code Stewardship Policy | Before any grant or RFP with code deliverables | GP-4 (asset transfer) |
| Asset Transfer Agreement Template + IP Schedule | Before any material asset transfer | GP-4 |
| Working Group Framework | Before first Working Group established | GP-5 |
| Election & Role Governance Policy | Before first role term expires | G&L WG drafts — required before first elections |
| Governance Continuity Framework | Before first Delegate term ends | G&L WG drafts — required before first transitions |
| Dispute Resolution & Arbitration Policy | Before first formal dispute escalated | G&L WG drafts |
| Treasury Risk & Diversification Policy | Before first diversification action | T&F WG drafts |
| Token Delegation Policy | When governance platform supports delegation | Governance Operator announces |

---

## Timeline Orientation

Each governance proposal requires a Temperature Check (minimum 7 days) before opening as a Governance Proposal (minimum 14 days). Allow at least 21 days per proposal, plus any RAC review and drafting time.

| Milestone | Earliest Possible |
|---|---|
| Phase 0 prep complete | Week 2–3 |
| GP-PRE-1 passes | Week 5–6 |
| Entity registration | Week 6–7 |
| GP-1 through GP-3 complete | Week 10–12 |
| GP-4 passes and asset transfer executed | Week 14–18 (depends on Founding Transferor readiness) |
| GP-5 through GP-9 complete | Week 22–30 |

These are minimums assuming no proposal fails its Temperature Check or requires redrafting. Build contingency into the schedule — a failed TC adds 4–6 weeks.

---

## What the RAC Does and When It Hands Off

| Phase | RAC Role | Hands Off To |
|---|---|---|
| Phase 0 | Prepares Delegate Roster, coordinates KYC, sets up multi-sig | — |
| Pre-registration | Authors GP-PRE-1, runs community engagement | — |
| Registration | Legal Signatory files | — |
| Post-registration (GP-1 to GP-3) | Coordinates filings, manages compliance | G&L WG on formation |
| Asset transfer (GP-4) | Authors transfer proposal, executes with Legal Signatory | — |
| Working groups (GP-5 to GP-9) | Supports WG charter drafting, oversees activation | Each WG progressively |
| Ongoing Phase 1 | Emergency authority, oversight, quarterly delegation reports | Full handoff at Phase 2 entry |

The RAC's interim execution authority (Transition Governance Framework §5.4) for a given workstream lapses the moment the relevant Working Group is operational. The RAC does not need to take a formal action to relinquish it — the framework extinguishes the authority automatically.
