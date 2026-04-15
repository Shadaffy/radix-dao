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

## [0.4.0] — 2026-04-13
**Type:** Minor
**Document(s):** Governance-Processes/Roles/Conflict-of-Interest-Policy.md; Legal/ (folder restructure); Supporting-Materials/governance-body-intro.md; readme.md; FAQ.md; GLOSSARY.md; CHANGELOG.md; Transition/Activation-Roadmap.md
**Summary:** Four changes in this release. (1) Conflict of Interest Policy §3.2 broadened to remove named entity references in favour of generic language covering predecessor organisations, founding sponsors, and their successors. §7 renamed to "Legacy Entity and Commercial Entity Relationships" and rewritten to shift from present-tense employment to residual-interest framing with a three-year lookback, extended to successor entities and asset transferees. (2) Repository restructured: `Legal/` and `Legal-Entity/` merged into a single `Legal/` folder with `Policy/` and `Formation/` subfolders; `RAC-Mandate.md` relocated from `Legal/` to `Governance-Processes/Roles/` where it belongs alongside other role governance documents. All cross-references in GLOSSARY.md, Activation-Roadmap.md, and Supporting-Materials/governance-body-intro.md updated. (3) Supporting materials comprehensively updated: governance-body-intro.md restructured to clearly distinguish the three distinct areas of the repository (Governance Framework, Legal Entity, Transition); document index updated with previously missing files (RAC-Mandate.md, Activation-Roadmap.md, Source-Code-Stewardship-Policy.md, Proposals/); Phase 2 table updated to include Source Code Stewardship Policy. readme.md restructured with the same three-pillar framing and Legal Entity explanation. (4) FAQ.md expanded with a new "About the Legal Entity" section covering Radix DLT DAO LLC, the Formation documents, the Activation Roadmap, and the relationship between the legal entity and governance. GLOSSARY.md expanded with entries for Activation Roadmap, Formation Documents, and Legal Entity.

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

---

## [0.2.0] — 2026-04-05
**Type:** Minor
**Document(s):** Governance-Processes/Core/Code-of-Conduct.md (new)
**Summary:** Added Code of Conduct as a new Core governance document. Defines behavioral standards for all DAO participants including token holders, contributors, role-holders, and contractors. Covers good faith participation, respectful conduct, transparency, resource protection, and confidentiality. Establishes prohibited conduct (harassment, discrimination, bribery, collusion, fraud, Sybil attacks, doxxing, retaliation), reporting procedures, enforcement process, and sanctions. Cross-referenced with Conflict of Interest Policy, Dispute Resolution & Arbitration Policy, Ethics Reporting Policy, and Working Group Charters.

---

## [0.3.1] — 2026-04-05
**Type:** Minor
**Document(s):** readme.md; Supporting-Materials/governance-body-intro.md
**Summary:** Rewrote readme and governance-body-intro to clearly communicate phased activation of the governance framework. Both documents now lead with the message that this is the full framework but complexity is introduced in deliberate waves. Added three-tier activation model (Tier 1: fully active at launch; Tier 2: guiding principles with Year 1 approval schedule; Tier 3: triggered by need) to both documents. Updated full document index in governance-body-intro with all 9 new policies annotated by tier. Removed outdated document tree. Added audience-based reading guide to readme. Removed emoji styling from both documents for consistency with the rest of the framework.

---

## [0.3.0] — 2026-04-05
**Type:** Major
**Document(s):** Charter/charter.md; Transition/Transition-Governance-Framework.md §3.1, §3.5 (new)
**Summary:** Rewrote Charter in formal but eloquent register — elevated language with weight and precision, retaining all structural sections. Added §3.6 Integrity (Code of Conduct reference), expanded §5 to reference Token Delegation Policy, §6 to reference Contributor Compensation and Grant Program policies, §7 to reference Ethics Reporting Policy, §8 to reference Conflict of Interest Policy, §9 to reference Smart Contract Audit Policy, and §13 to acknowledge the full policy library. Updated Transition Framework §3.1 to include Code of Conduct, Conflict of Interest Policy, and Token Delegation Policy as fully active from Phase 1 launch. Added §3.5 Policy Activation Schedule defining Year 1 governance approval targets for the 7 remaining new policies, with guiding principles status defined and Governance & Legal WG assigned responsibility for tracking.

---

## [0.2.8] — 2026-04-05
**Type:** Minor
**Document(s):** Governance-Processes/Core/Smart-Contract-Audit-Policy.md (new)
**Summary:** Added Smart Contract Audit Policy establishing mandatory security audit requirements before deployment of DAO-governed on-chain systems. Defines three audit tiers: Tier 1 (full independent audit for governance contracts and treasury components), Tier 2 (targeted review for minor upgrades and lower-risk contracts), Tier 3 (internal review for parameter/configuration changes). Requires audit reports to be published and included in governance proposals as a validity condition enforced by the RAC. Covers auditor independence and qualification standards, finding resolution requirements (Critical/High must be fixed or mitigated), code freeze obligations, emergency deployment exceptions with mandatory retroactive audit within 60 days, and a dedicated audit budget managed by the Product & Protocol WG.

---

## [0.2.7] — 2026-04-05
**Type:** Minor
**Document(s):** Governance-Processes/System-Integrity/Ethics-Reporting-Policy.md (new)
**Summary:** Added Ethics Reporting Policy providing a structured whistleblower channel for governance integrity violations by role-holders (RAC members, Stewards, Authorized Signers). Covers abuse of role, undisclosed conflicts, misappropriation, governance manipulation, confidentiality breaches, failure to act, and false reporting. Defines three investigation tracks: standard (RAC), named RAC member (remaining RAC), and majority RAC compromise (community-nominated independent panel). Includes whistleblower identity protection, retaliation prohibition, interim protective measures, full outcomes and remedies, and an appeals process. Distinguished from Code of Conduct (behavioral violations) and Dispute Resolution Policy (operational disagreements).

---

## [0.2.6] — 2026-04-05
**Type:** Minor
**Document(s):** Governance-Processes/Execution/Contributor-Onboarding-and-Offboarding.md (new)
**Summary:** Added Contributor Onboarding and Offboarding document defining the full contributor lifecycle across all Working Groups. Onboarding covers pre-engagement checklist, orientation (DAO overview, governance basics, WG context, tools, reporting expectations, security practices), buddy assignment, access provisioning, and contributor registry entry. Offboarding covers triggers, notice periods, knowledge transfer, access revocation (within 2 business days; immediate for cause), financial close-out, exit feedback, and alumni status. Includes Steward-specific handover procedures (incoming and outgoing) and WG dissolution offboarding overseen by the RAC.

---

## [0.2.5] — 2026-04-05
**Type:** Minor
**Document(s):** Governance-Processes/Core/Security-Disclosure-and-Bug-Bounty-Policy.md (new)
**Summary:** Added Security Disclosure and Bug Bounty Policy covering proactive vulnerability discovery and responsible disclosure for DAO-governed systems. Defines in-scope systems (governance contracts, treasury multisig, voting interfaces), severity tiers (Critical/High/Medium/Low/Informational), coordinated disclosure process with severity-tiered remediation windows, safe harbour protections for compliant researchers, bounty reward tiers (amounts in DAO Parameters), and post-mortem publication requirements. Explicitly scopes out the Radix protocol layer (RDX Works' responsibility). Defines handoff to Emergency & Safeguards Policy when an active exploit is underway.

---

## [0.2.4] — 2026-04-05
**Type:** Minor
**Document(s):** Governance-Processes/Core/Transparency-and-Reporting-Policy.md (new)
**Summary:** Added Transparency and Reporting Policy consolidating all disclosure and reporting obligations across the DAO. Defines a full reporting cadence: WG monthly updates, WG quarterly reports, WG end-of-term retrospectives, monthly treasury snapshots, quarterly financial reports, annual financial summary, RAC biweekly activity log, and RAC quarterly report. Establishes public documentation repository standards and assigns maintenance to Governance & Legal WG. Defines reporting failure escalation and breach consequences. Includes confidentiality exception process with mandatory retrospective disclosure.

---

## [0.2.3] — 2026-04-05
**Type:** Minor
**Document(s):** Governance-Processes/Core/Token-Delegation-Policy.md (new)
**Summary:** Added Token Delegation Policy substantiating the delegation allowance noted in DAO Parameters Registry §8. Defines delegation mechanics (on-chain, snapshot-based, revocable), delegate eligibility and responsibilities, and delegator rights. Establishes a voluntary Public Delegate Registry maintained by the Governance & Legal WG. Includes conflict of interest provisions for role-holders holding delegated power, and a concentration monitoring mechanism for delegates approaching Constitutional quorum levels. Cross-referenced with Proposal & Voting Framework, Code of Conduct, and Conflict of Interest Policy.

---

## [0.2.2] — 2026-04-05
**Type:** Minor
**Document(s):** Governance-Processes/Core/Contributor-Compensation-Policy.md (new); Governance-Processes/Core/Grant-Program-Policy.md (new)
**Summary:** Added Contributor Compensation Policy defining how WG Stewards, contributors, and contracted specialists are engaged and paid. Covers compensation models (retainer, milestone, hourly), RFP process for procuring work, payment denominations, expense reimbursement, vesting arrangements, and full disclosure requirements. Added Grant Program Policy defining how external projects apply for ecosystem grants. Covers four grant categories (Micro, Standard, Strategic, Emergency), eligibility, application process, evaluation criteria, milestone-based disbursement, reporting obligations, suspension and clawback provisions, and reapplication restrictions.

---

## [0.2.1] — 2026-04-05
**Type:** Minor
**Document(s):** Governance-Processes/Roles/Conflict-of-Interest-Policy.md (new)
**Summary:** Added Conflict of Interest Policy as a new Roles governance document. Substantiates the disclosure and recusal obligations referenced but undefined in Elections & Role Governance Policy §15. Covers financial interests, organizational affiliations, personal relationships, and simultaneous role conflicts. Defines initial and ongoing disclosure requirements, transaction-level declarations, recusal obligations, and a Conflicts Register maintained by the RAC. Includes specific provisions for RDX Works and commercial entity relationships given the DAO's origin. Enforces via Code of Conduct and Elections policy removal procedures.
