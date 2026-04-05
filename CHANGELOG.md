# Governance Document Changelog

This file records all changes to Radix DAO governance documents.

Each entry must include: version, date, document(s) affected, change type (Patch / Minor / Major), and a summary.

Change types are defined in the **Governance Maintenance & Upgrade Framework**.

---

## Format

```
## [Version] — YYYY-MM-DD
**Type:** Patch | Minor | Major
**Document(s):** <document name(s)>
**Summary:** <what changed and why>
```

---

## [0.1.0] — 2026-04-05
**Type:** Major
**Document(s):** All — initial framework
**Summary:** Initial governance framework established. Includes Charter, Proposal & Voting Framework, Execution & Treasury Actions Policy, Emergency & Safeguards Policy, Dispute Resolution & Arbitration Policy, Election & Role Governance Policy, Authorized Signers Rules, Working Group Framework, Governance Continuity Framework, Governance Maintenance & Upgrade Framework, Legal Wrapper & Representation, RAC Mandate, DAO Parameters Registry, Transition Governance Framework, and all Working Group charters.

---

## [0.1.1] — 2026-04-05
**Type:** Patch
**Document(s):** Charter §6, §7, §9, §10, §12; Legal Wrapper & Representation §10; Transition Governance Framework §2.2, §3.2, §5.1, §5.3, §6.1, §6.2, §8, §9, §11
**Summary:** Corrected stale document references in Charter (§6, §7); flagged missing frameworks in §9 and §12 and added cross-references to existing documents. Resolved signer identity conflict between Legal Wrapper §10 and Election Policy. Added cross-reference to Phase1-governance-proposal.md in Transition Governance Framework. Multiple improvements to transition framework: defined phase boundaries and entry criteria, added simplification table (§3.2), tightened material harm definition (§5.1), added RAC routine decision quorum (§5.3), conflict of interest provisions (§6.1), community challenge mechanism (§6.2), reporting specifics (§8), quarterly review cadence (§9), and extension vote type (§11).

---

## [0.1.2] — 2026-04-05
**Type:** Minor
**Document(s):** Charter §12; Parameters Registry §4, §5.1, §6.1, §6.2, §6C, §8, §9, §9A; Governance Continuity §4.3, §6; Phase1-governance-proposal.md; Transition Governance Framework §3.2
**Summary:** Removed stale note in Charter §12 (Governance Maintenance & Upgrade Framework now exists). Resolved all TBD values in Parameters Registry; added §9A Governance Continuity Parameters with defined reduced quorum thresholds, inactivity triggers, and reconstitution deadline. Aligned Phase 1 working group count across Transition Framework and Phase1 proposal. Added governance inactivity trigger and reconstitution deadline to Governance Continuity.

---

## [0.1.3] — 2026-04-05
**Type:** Minor
**Document(s):** Proposal & Voting Framework §7, §8; Emergency & Safeguards Policy §10; Parameters Registry §5.1; Authorized Signers Rules §8, §14; Working Group Framework §7.1; Governance & Legal WG Charter §11–12; Community & Marketing WG Charter §11–12; Governance Maintenance & Upgrade Framework §4; governance-body-intro.md
**Summary:** Defined proposal conflict resolution rules (§7). Expanded veto mechanism with filing eligibility, format, process, and RAC review steps (§8). Added post-emergency ratification deadlines to Emergency Policy. Added RAC routine decision quorum to Parameters Registry. Defined valid execution request format for Authorized Signers (§8.1); fixed self-dealing clause (§14). Added budget variance tolerance rules to Working Group Framework (§7.1). Completed missing Conflicts of Interest and Renewal/Sunset sections in Governance & Legal and Community & Marketing WG charters. Added explicit approval thresholds (Patch/Minor = Governance Process; Major = Constitutional) to Governance Maintenance & Upgrade Framework. Updated governance-body-intro.md directory tree to match actual file structure.

---

## [0.1.4] — 2026-04-05
**Type:** Patch
**Document(s):** All files and folders containing "-&-" in their names
**Summary:** Renamed all files and folders using "-&-" to "-and-" for filesystem compatibility. Updated all internal cross-references accordingly. Created this CHANGELOG.md to establish version control per Governance Maintenance & Upgrade Framework §6.
