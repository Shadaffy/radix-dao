# DAO Activation Roadmap — Optimised Parallel Track

## Radix DLT DAO LLC — Accelerated Activation from RAC Election to Fully Operational DAO

> **Read alongside:** `Activation-Roadmap.md` — the sequential baseline. This document contains the same proposals and actions but reorganises them for maximum parallelism. The governance rules, thresholds, and document references are identical. Only the sequencing changes.
>
> **Assumptions:** Same as the baseline roadmap. RAC members carry forward as founding Delegates. Consultation V2 is deployed. All 10 Phase 1 governance documents are drafted. The Foundation begins preparing the IP Schedule in parallel from Day 1.
>
> **Target timeline:** 8–9 weeks to fully operational DAO with all Working Groups established and asset transfer executed (subject to Foundation readiness on the IP Schedule).

---

## Dependency Map

Before reading the parallel tracks, understand what is genuinely sequential and what is not.

**Hard sequential dependencies — these cannot be reordered:**

1. All Delegates complete KYC → BOIR can be filed
2. Consultation V2 addresses confirmed → Certificate of Formation can be filed
3. GP-PRE-1 passes → Entity registration happens
4. Entity registered → DAO's own governance proposals can open
5. Working Group Framework activated → Individual Working Groups can be established
6. Open Source & IP Policy + Source Code Stewardship Policy activated → ATA can be executed for code assets

**Everything else is flexible.** GP-1, GP-2, GP-3, GP-4, and the Working Groups bundle have no dependency on each other — only on the entity existing.

---

## Key Optimisations vs Sequential Baseline

| Optimisation | Days Saved |
|---|---|
| Bundle GP-1 + GP-2 + GP-3 into one "Entity Activation" proposal | ~42 days (2 proposal cycles) |
| Run Entity Activation, Asset Transfer, and Working Groups TCs simultaneously | ~21 days (1 proposal cycle) |
| Run all three votes simultaneously | ~14 days |
| Bundle all 5 Working Groups into one proposal | ~84 days (4 proposal cycles) |
| Use TC and vote waiting periods for parallel preparation | ~14 days |
| **Total saved** | **~9–11 weeks** |

**Trade-off:** Bundling is faster but carries more risk. If a contentious element in a bundle causes a vote to fail, the entire bundle restarts. Mitigation strategies are noted for each bundle below.

---

## Phase 0 — Parallel Preparation (Days 1–14)

All of the following run simultaneously. None depend on each other. Target: complete all by end of Day 14.

---

### Track A — KYC and Compliance (Days 1–14)

**Actor:** Each Delegate individually; coordinated by Compliance Liaison

All Delegates complete KYC Tier 1 verification through SumSub simultaneously. Do not wait for one Delegate to complete before the next begins — run all in parallel. This is the single most common cause of timeline slippage in Phase 0; start on Day 1.

- KYC Tier 2 (UBO) also applies to any Delegate holding ≥25% eligible voting power
- Compliance Liaison prepares the BOIR filing package (Section 3 records and Section 4 roster) while KYC completes, so it is ready to file immediately after registration

---

### Track B — Technical Setup (Days 1–14)

**Actor:** Governance Operator; Treasury Signers

**Day 1:** Governance Operator retrieves and records the three Consultation V2 identifiers:

| Identifier | Description |
|---|---|
| `packageAddress` | Scrypto package identifier |
| `componentAddress` | Instantiated governance component |
| `adminBadgeAddress` | Owner Badge — used to elevate Temperature Checks to Governance Proposals |

**Days 1–14:** Treasury Signers prepare and test the multi-signature treasury wallet (3-of-5 standard threshold, 4-of-5 high-risk threshold per DAO Parameters §6A). Wallet address confirmed and published before end of Phase 0.

---

### Track C — Document Preparation (Days 1–14)

**Actor:** RAC (drafting); Legal Signatory

Prepare all documents so they are ready to file or open for vote the moment Phase 1 completes:

- Insert confirmed Consultation V2 addresses into Operating Agreement §1.4 and Certificate of Formation
- Draft GP-PRE-1 (full founding proposal — see Phase 1 below)
- Draft the Entity Activation Package proposal (GP-A — covers BOIR, operational policy adoption, treasury limits)
- Draft Working Group Charters for all 5 Working Groups (see Phase 3)
- Prepare multi-sig wallet address, Delegate Roster, and KYC confirmation for publication

---

### Track D — Foundation Parallel Workstream (Days 1 onward)

**Actor:** Foundation (external); Compliance Liaison as liaison

The Foundation begins preparing the IP Schedule (Exhibit A to the Asset Transfer Agreement) from Day 1. This is entirely on the Foundation's side and is the one external dependency that cannot be internally accelerated.

The Compliance Liaison maintains weekly contact with the Foundation to track progress and flag any asset classification questions early. The ATA terms should be negotiated and agreed in principle before entity registration — only the formal execution waits for the entity to exist.

**Foundation deliverables needed by Day 36 (registration) to achieve the optimised timeline:**
- Draft IP Schedule completed and agreed with Compliance Liaison
- ATA terms agreed in principle

---

## Phase 1 — GP-PRE-1: Founding Proposal (Days 15–35)

**Type:** Constitutional
**Threshold:** ≥66% approval / ≥10% quorum
**Process:** Temperature Check Days 15–21 → Governance Proposal Days 22–35

This runs through the **community's own Consultation V2 deployment** — operated by the community independently of the Foundation. The DAO does not yet legally exist as an entity, but the community already governs itself on-chain. This is the pre-registration founding act.

### During Temperature Check (Days 15–21): Do not wait

- Legal Signatory finalises and executes the Registered Agent engagement with MIDAO Directory Services
- Formation documents (Certificate of Formation + Operating Agreement) are signed, sealed, and ready to file — the Legal Signatory submits the moment the vote passes on Day 35
- Foundation finalises IP Schedule based on any feedback from community during TC period

### During Governance Proposal Vote (Days 22–35): Do not wait

- Foundation finalises and delivers completed IP Schedule to Compliance Liaison
- ATA is finalised and ready for signature post-registration
- Compliance Liaison prepares BOIR filing package, ready to submit the day after registration

### GP-PRE-1 covers (one vote, not four):

1. **Framework adoption** — formally adopt all 10 Phase 1 governance documents
2. **Entity formation authorization** — authorize Legal Signatory to file Certificate of Formation and Operating Agreement with MIDAO
3. **Delegate ratification** — confirm founding Delegate roster and function assignments
4. **Transition Governance Framework authorization** — confirm RAC Phase 1 transitional authority commences from registration date

**Why one proposal:** These four elements are inseparable. The community votes on the founding act as a whole.

---

## Day 36 — Registration

Vote passes Day 35. Legal Signatory files Certificate of Formation with MIDAO Directory Services on Day 36 (or next business day). Entity **Radix DLT DAO LLC** comes into legal existence.

Publish formation confirmation to governance forum within 72 hours including: entity name, formation date, Registered Agent confirmation, Delegate Roster, and multi-sig wallet address.

---

## Phase 2 — Three Simultaneous Proposal Tracks (Days 37–57)

The moment the entity is registered, three Temperature Checks open on the same day. They run concurrently through TC and vote periods.

```
Day 37  ──────────────────────────────────────────────── Day 57
  │                                                          │
  ├─ TC-A: Entity Activation Package ──────── Vote-A ───────┤
  │  (GP-1 + GP-2 + GP-3 bundled)                           │
  │                                                          │
  ├─ TC-B: Asset Transfer Authorization ───── Vote-B ───────┤
  │  (GP-4)                                                  │
  │                                                          │
  └─ TC-C: All Working Groups ─────────────── Vote-C ───────┘
     (GP-5 through GP-9 bundled)
```

---

### Track A — Entity Activation Package (GP-A)

**Type:** Governance Process
**Threshold:** ≥60% approval / ≥7% quorum
**TC:** Days 37–43 | **Vote:** Days 44–57

Bundles two administrative proposals with no dependencies on each other:

**GP-1 element — File Initial BOIR:** Authorize Compliance Liaison to file the initial BOIR with MIDAO Directory Services. All Delegates (completed KYC in Phase 0) are listed as beneficial members under §702(r). Note: the BOIR must be filed within 30 days of formation per DAO Act §712(1). If the proposal timeline would exceed this, the Compliance Liaison files under RAC transitional authority on Day 36 and this vote serves as retrospective ratification.

**GP-2 element — Adopt Operational Policies (OA §12.4):** Formally adopt all 10 Phase 1 governance documents as subordinate operational policies of Radix DLT DAO LLC. This gives the framework binding legal force under the Operating Agreement.

---

### Track B — Asset Transfer Authorization (GP-B)

**Type:** Constitutional
**Threshold:** ≥66% approval / ≥10% quorum
**TC:** Days 37–43 | **Vote:** Days 44–57

**Minimum community review period for the IP Schedule:** 14 days before the vote opens. Since the TC serves as the review window, the IP Schedule must be published on Day 37 alongside the TC. This is why the Foundation's IP Schedule preparation in Phase 0 (Track D) is critical — it must be complete by Day 36.

**GP-4 covers:**
1. Approve the Asset Transfer Agreement text as final
2. Approve the IP Schedule (Exhibit A) — full enumeration of every asset being transferred
3. Authorize Legal Signatory to execute both documents on behalf of the DAO
4. Simultaneously activate Open Source & IP Policy and Source Code Stewardship Policy (required before code assets can be received — Transition Governance Framework §3.2)

**Execution after vote passes (Day 58+):**
- Legal Signatory and Foundation execute Asset Transfer Agreement
- Continuity Statement executed by Legal Signatory and Compliance Liaison
- Continuity Statement filed with Registered Agent
- Acceptance Statement published to governance forum within 72 hours
- Provenance record created per Operating Agreement §9.3
- Updated BOIR filed within 30 days if asset transfer changes reportable information

---

### Track C — All Working Groups (GP-C)

**Type:** Governance Process
**Threshold:** ≥60% approval / ≥7% quorum
**TC:** Days 37–43 | **Vote:** Days 44–57

Bundles the Working Group Framework activation and all five Working Group Charters into a single proposal. The WG Framework activation is the legal prerequisite for establishing any Working Group — by including it in the same proposal, it is satisfied simultaneously.

**GP-C covers:**
1. **Activate Working Group Framework** (Transition Governance Framework §3.2 trigger)
2. **Establish Governance & Legal Working Group** — governance maintenance, legal compliance, Phase 2/3 policy development
3. **Establish Protocol & Engineering Working Group** — protocol development, smart contract governance, repository governance, secure development lifecycle, smart contract audit coordination, network operations transition
4. **Establish Treasury & Finance Working Group** — treasury management, financial reporting, grant administration
5. **Establish Community & Ecosystem Working Group** — community engagement, ecosystem grants, communications
6. **Establish Infrastructure & Security Working Group** — infrastructure operations and SLA oversight, security monitoring, vulnerability disclosure, information security compliance, emergency coordination

**Mitigation if bundling is risky:** The most likely debate point is Steward appointments, not WG structures. Consider excluding specific Steward appointments from this proposal — establish the WG structure and mandate, then appoint Stewards via a lightweight follow-on proposal (no TC required if treated as a Governance Operations administrative action under the WG Framework). This removes the contentious element from the bundle without splitting the structural vote.

**On operational handoff:** Once each Working Group is operational, the RAC's interim execution authority for that workstream lapses automatically (Transition Governance Framework §5.4). No formal handoff action is required. The RAC notes each lapse in its quarterly delegation status report.

---

## Day 58+ — Execution Week

By Day 57, all three votes have closed. Execution actions proceed:

| Action | Actor | Dependency |
|---|---|---|
| File BOIR with Registered Agent | Compliance Liaison | Track A passed |
| Operational policies formally in force | Governance Operator records | Track A passed |
| ATA signed; IP Schedule accepted | Legal Signatory | Track B passed + Foundation ready |
| Continuity Statement executed and filed | Legal Signatory + Compliance Liaison | Track B passed |
| Acceptance Statement published | Legal Signatory | ATA executed |
| All 5 Working Groups operational | Each WG — Stewards confirmed | Track C passed |
| RAC interim execution authority lapses per workstream | Automatic | WG operational |

---

## Optimised Timeline Summary

| Days | Action |
|---|---|
| 1–14 | Phase 0: KYC, technical setup, document prep, Foundation IP Schedule — all parallel |
| 15–21 | GP-PRE-1 Temperature Check; formation documents finalised |
| 22–35 | GP-PRE-1 Vote; ATA finalised; Foundation delivers IP Schedule |
| 36 | Entity registered; formation published |
| 37–43 | Three simultaneous Temperature Checks (Entity Activation / ATA / Working Groups) |
| 44–57 | Three simultaneous Governance Proposal votes |
| 58+ | Execution: BOIR filed, policies in force, ATA signed, Working Groups operational |

**Total: ~8–9 weeks** (subject to Foundation delivering IP Schedule by Day 36)

---

## What Can Still Extend the Timeline

| Risk | Mitigation |
|---|---|
| Foundation IP Schedule not ready by Day 36 | Start Foundation workstream on Day 1; weekly check-ins from Compliance Liaison |
| GP-PRE-1 fails Temperature Check | Address community feedback during TC period; redraft before opening vote |
| A bundled post-registration proposal fails | Run failed elements as standalone proposals in the next cycle; other bundles unaffected |
| KYC delays for one or more Delegates | Begin KYC on Day 1; use SumSub expedited processing; any Delegate not KYC-complete cannot be listed on BOIR |
| MIDAO registration processing time | Engage Registered Agent before Day 36; confirm processing time upfront |

---

## What Does Not Change

The optimised track changes sequencing only. All governance rules, approval thresholds, document references, legal protections, and compliance obligations are identical to the sequential baseline in `Activation-Roadmap.md`. The community votes on the same decisions — just with less waiting between them.
