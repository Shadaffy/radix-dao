# Frequently Asked Questions

Practical answers for anyone participating in Radix DAO governance.

For definitions of specific terms, see the [Glossary](GLOSSARY.md). For exact parameter values (quorum percentages, time limits, signing thresholds), see the [DAO Parameters Registry](Parameters/DAO-Parameters-Registry.md).

---

## For Token Holders

**How do I vote on a proposal?**
Token holders vote through the DAO's designated governance interface. You can vote YES, NO, or Abstain. Voting power is measured at the snapshot taken at the start of the voting period — so your balance at that moment determines your weight in that vote. Each XRD token represents one vote. If you hold LSU (Liquid Staking Units — XRD staked with a validator), your LSU are also counted: they are converted to their XRD equivalent at the time of the snapshot, and that equivalent amount counts as additional votes.

**Do I have to vote myself, or can someone vote on my behalf?**
You can delegate your voting power to any eligible participant (a delegate), who will then vote on all proposals using your combined power. You can also vote directly. Delegation does not take away your right to submit proposals or file veto challenges — those rights are tied to your direct holdings.

**Can I change my delegate?**
Yes, at any time. Revocations and reassignments take effect at the next governance snapshot — they do not affect a vote that is already in progress. You can also reclaim direct voting rights by delegating to yourself.

**What happens if I miss a vote?**
Nothing automatic — missing a vote just means your tokens are not counted in that proposal's outcome. This is why delegation exists: a delegate you trust can vote on your behalf when you are unavailable.

**What's the minimum token holding needed to vote?**
There is no minimum — any XRD holder or LSU holder can vote. Quorum is measured in aggregate across all eligible voting power (XRD plus LSU converted to XRD-equivalent): a proposal is only valid if enough total eligible power participates (the threshold varies by proposal type). One XRD (or its LSU equivalent) still counts as one vote.

**What if I disagree with the outcome of a vote?**
If you believe the proposal violated the Charter or a governance rule, you can file a veto challenge within 48 hours of the vote closing (see "What is the veto mechanism for?" below). If you disagree with the *policy* rather than the process, you can wait for the next proposal cycle and submit or support a counter-proposal. The DAO can always revisit any decision through a new governance vote.

---

## For Contributors & Applicants

**How do I get involved as a contributor?**
The primary route is through the five Working Groups (Strategic Coordination, Governance & Legal, Product & Protocol, Ecosystem Growth, Community & Marketing). Each Working Group engages contributors within its approved mandate and budget. Contact the relevant Working Group's Stewards or follow announcements on the governance forum and community channels.
→ See: [Governance-Processes/Execution/Working-Group-Framework.md](Governance-Processes/Execution/Working-Group-Framework.md)

**How are contributors compensated?**
Contributors are compensated through Working Group budgets approved by governance. Compensation models include fixed-term engagements, milestone-based arrangements, and specialist contracts. The Contributor Compensation Policy (Tier 2, target formal approval Month 3) sets out rates and expense reimbursement standards.
→ See: [Governance-Processes/Core/Contributor-Compensation-Policy.md](Governance-Processes/Core/Contributor-Compensation-Policy.md)

**How does the grant program work?**
The Grant Program Policy (Tier 2, target formal approval Month 3) defines four grant categories:
- **Micro grants** — small amounts, fast turnaround, approved by Working Group Stewards without a full DAO vote
- **Standard grants** — medium amounts, require a governance vote
- **Strategic grants** — large amounts, require extended review and a governance vote
- **Emergency grants** — rapid response to critical needs, approved quickly and ratified by the DAO afterward

Exact size thresholds are defined in the DAO Parameters Registry. Applications are submitted through the Ecosystem Growth Working Group.
→ See: [Governance-Processes/Core/Grant-Program-Policy.md](Governance-Processes/Core/Grant-Program-Policy.md)

**Can I hold a DAO role and also be a regular token holder / delegate?**
Yes. RAC members, Working Group Stewards, and Authorized Signers may all hold and exercise delegated voting power. However, they must disclose this in their standing conflict of interest disclosure, and must recuse from any vote where their delegated power would create a self-dealing situation.
→ See: [Token Delegation Policy §4, §7](Governance-Processes/Core/Token-Delegation-Policy.md)

**Can I hold more than one DAO role?**
Yes, subject to a maximum of 2 concurrent roles per individual (per the DAO Parameters Registry §6B), and provided no conflict of interest exists between the roles. All simultaneous role combinations must be disclosed.

---

## For Working Group Stewards

**What can a Working Group do without a separate governance vote?**
Working Groups may take any action that falls within their approved mandate and budget: engaging contributors, managing workstreams, issuing RFPs, attending to day-to-day coordination, and reporting to the DAO. If it is within the scope and budget the DAO already approved, it does not need a new vote.
→ See: [Governance-Processes/Execution/Working-Group-Framework.md](Governance-Processes/Execution/Working-Group-Framework.md)

**What spending requires a separate governance vote?**
Anything beyond the approved budget or outside the approved mandate requires a new Treasury & Budget proposal. Stewards cannot create new financial obligations above what governance has already authorised.

**How often do Working Groups report to the DAO?**
Biweekly, per the DAO Parameters Registry §7. The Transparency & Reporting Policy (Tier 2, target formal approval Month 2) specifies the format and content of reports.

**How is a new Working Group created?**
A new Working Group requires a governance proposal (at minimum a Governance Process or Treasury & Budget proposal, depending on whether new funding is needed). The five Working Groups that launched at Phase 1 were approved as part of the Phase 1 activation.

---

## About Governance Mechanics

**What is the difference between quorum and approval threshold?**
They are two separate requirements that must *both* be met for a proposal to pass:
- **Quorum** — the minimum percentage of eligible voting power (liquid XRD plus LSU converted to XRD-equivalent at snapshot) that must cast any vote (YES, NO, or Abstain) for the result to be valid. If participation is too low, the proposal fails regardless of how people voted.
- **Approval threshold** — the percentage of cast votes (excluding Abstain) that must be YES for the proposal to pass.

Example: a Governance Process proposal needs ≥7% quorum AND ≥60% YES approval. If only 6% of XRD participates, the proposal fails due to insufficient quorum even if 90% of participants voted YES.

**What are the different proposal types and when do I use each?**
| Type | Use For | Quorum | Approval |
|---|---|---|---|
| Constitutional | Amending the Charter or core governance structure | 10% | ≥66% YES |
| Governance Process | Changing policies, rules, procedures; phase transitions | 7% | ≥60% YES |
| Treasury & Budget | Funding requests, budget allocations | 5% | ≥50% YES |
| Executable | Technical or on-chain changes | 5% | ≥50% YES |
| Signaling | Non-binding community sentiment | 3% | ≥50% YES |

**How long does a proposal take from idea to decision?**
The minimum end-to-end timeline is approximately 12–17 days:
- Draft discussion: 5–7 days (community feedback before formal submission)
- Review period: 2–3 days (after formal submission, before voting opens)
- Voting period: 5–7 days

A failed proposal then has a 7-day cooldown before resubmission. Phase transitions or complex proposals may take longer due to extended community deliberation.

**What is a snapshot and why does it matter for delegation?**
The snapshot is the moment at which voting power is frozen for a specific vote. It is taken at the start of the voting period. If you change your delegation *after* the snapshot, that change only affects the *next* vote. This prevents last-minute vote buying or manipulation — no one can acquire tokens or shift delegation once a vote is underway.

**What is the veto mechanism for?**
The veto is a narrow safeguard, not a general disagreement tool. It exists *only* to halt proposals that violate the Charter or an existing governance rule. Policy disagreement — even strong disagreement — is not grounds for veto.

Any token holder can file a veto challenge within 48 hours of a vote closing. The challenge must cite the specific Charter section or governance rule being violated. The RAC reviews it within 48 hours and issues a determination. If a violation is found, the proposal is halted pending correction. The DAO can override any RAC determination via a Governance Process proposal.

**What happens if quorum is not met?**
The proposal fails. It can be resubmitted after the 7-day cooldown. If the same proposal type fails to reach quorum 3 consecutive times, the Governance Continuity Framework activates a reduced quorum threshold (50% of the standard level, minimum 1%) and an extended voting period (double the standard duration) to help the DAO make progress during periods of low participation.
→ See: [Governance-Processes/System-Integrity/Governance-Continuity.md](Governance-Processes/System-Integrity/Governance-Continuity.md), [DAO Parameters Registry §9A](Parameters/DAO-Parameters-Registry.md)

**Can a proposal be resubmitted if it fails?**
Yes, after the 7-day cooldown. Minor corrections (e.g., fixing a technical error) may be resubmitted immediately without the cooldown. Substantially different proposals should be resubmitted as new proposals with fresh deliberation.

**What if two proposals conflict with each other?**
If both pass but cannot both be implemented, the proposal with the higher YES vote share (as a percentage of total votes cast) prevails. If the margin is less than 5 percentage points, both are invalidated and must be resubmitted as a single proposal with clearly defined alternatives. If one passed quorum and the other did not, the quorum-meeting proposal prevails. The RAC flags known conflicts at the start of the voting period.
→ See: [Proposal & Voting Framework §7](Governance-Processes/Core/Proposal-and-Voting-Framework.md)

---

## About Treasury & Security

**Who controls the treasury?**
No single person does. The treasury is controlled through a 5-signer multisig: any standard treasury action requires 3 of 5 Authorized Signers to approve it; high-risk actions require 4 of 5. The Authorized Signers can only execute actions that have been approved by DAO governance — they have no discretionary spending authority.

**What is a multisig and why does the DAO use one?**
A multi-signature (multisig) arrangement means that a treasury transaction can only be executed if multiple independent individuals approve it. The DAO's 5-signer pool requires at least 3 approvals for standard actions. This means no single signer — if compromised, coerced, or acting in bad faith — can unilaterally move DAO funds. It removes the single-point-of-failure risk from treasury custody.

**What stops a bad actor from draining the treasury?**
Several independent safeguards operate together:
1. **Multisig** — requires 3-of-5 (or 4-of-5) independent approvals for any transaction
2. **Execution fidelity** — Authorized Signers can only execute approved proposals, not invent new spending
3. **RAC oversight** — the RAC verifies that execution matches approved decisions
4. **Emergency powers** — the RAC can pause systems and secure assets if a threat is detected
5. **KYC and conflict requirements** — Authorized Signers are vetted and must disclose conflicts
6. **Community override** — the DAO retains power to replace any Signer via governance vote

**What counts as a "high-risk" treasury action?**
High-risk actions require 4-of-5 Authorized Signer approval rather than the standard 3-of-5. The specific definition of "high-risk" is set by the Authorized Signers Rules and may be clarified in the DAO Parameters Registry. Generally it covers large or irreversible transactions, transfers to new or unverified counterparties, and actions outside normal operational patterns.
→ See: [Governance-Processes/Roles/Authorized-Signers-Rules.md](Governance-Processes/Roles/Authorized-Signers-Rules.md)

**Can Authorized Signers refuse to execute an approved proposal?**
Only on procedural, legal, or security grounds — for example, if executing the proposal would violate applicable law, if the technical instructions are ambiguous, or if a security risk has emerged since the vote. Authorized Signers cannot refuse execution because they disagree with the policy decision. Refusing to execute on political grounds is a violation of their role.

---

## About the Legal Entity

**What is Radix DLT DAO LLC?**
Radix DLT DAO LLC is a Marshall Islands DAO LLC — the real-world legal entity that the DAO uses to hold assets, sign contracts, engage contributors, and interface with legal and financial systems. Without a legal wrapper, a DAO has no legal personhood: its assets are effectively unowned in law, contracts are unenforceable, and individual token holders may bear personal liability for DAO actions. The LLC solves this. It is structured so that governance authority remains with token holders, not with the LLC's registered managers.

**Why the Marshall Islands?**
The Marshall Islands enacted specific DAO LLC legislation that recognises on-chain governance as the primary decision-making mechanism. This means the DAO's token-holder voting is legally binding on the entity — it is not just a social convention. The legal entity is governed by its Operating Agreement, which explicitly subordinates the entity to DAO governance outcomes.

**What are the Formation documents in `Legal/Formation/`?**
These are the actual corporate instruments for Radix DLT DAO LLC — not governance policies:
- **Certificate of Formation** — the foundational filing that brings the entity into legal existence with MIDAO (the Marshall Islands business registry)
- **Operating Agreement** — the internal constitution of the LLC; defines the relationship between the DAO, its Delegates, and the entity's legal structure
- **BOIR Template** — the Beneficial Owner Information Report required under Marshall Islands law; lists the entity's controlling members (Delegates)
- **Asset Transfer Agreement** — the contract governing the transfer of assets from the Radix Foundation to the DAO
- **IP Schedule** — the enumerated list of intellectual property assets (repositories, trademarks, patents) included in the transfer
- **Continuity Statement** — a legal filing confirming the ongoing continuity of the DAO entity

These documents are filed with MIDAO and are legal instruments. They are maintained in the repository for transparency and community review, but they are not amended through normal governance proposals — changes require legal process.

**What is the Activation Roadmap?**
The Activation Roadmap in `Transition/Activation-Roadmap.md` is the step-by-step operational guide for forming the legal entity and transitioning from Foundation governance to DAO governance. It covers the four phases of activation: pre-registration preparation, post-registration governance setup, asset transfer, and treasury configuration. It specifies who acts, what the action is, and (for governance steps) the required vote threshold. It is the practical companion to the Transition Governance Framework.

**Does the legal entity change how governance works?**
No. The legal entity is a wrapper, not a controller. The Operating Agreement explicitly subjects the LLC to DAO governance: token holder votes are binding on the entity through the Delegates (who hold the legal signing authority but must act on governance outcomes). The governance framework — Charter, policies, voting — remains the primary authority. The entity exists to execute what governance decides in the real world.

---

## About the Transition (Phase 1 & RAC)

**What is the Accountability Council (RAC) and what can it do?**
The RAC is the DAO's process oversight body — not a governing authority. Its core job is to ensure governance rules are followed, not to make governance decisions. Specifically, the RAC:
- Verifies that execution matches approved proposals
- Reviews veto challenges and issues determinations
- Flags conflicts between competing proposals
- Manages emergency actions (under strict conditions)
- During Phase 1 only: holds limited transitional authority for operational coordination

The RAC has 3–5 members serving 6-month terms. It cannot override DAO-approved proposals, allocate funds outside approved mandates, or define DAO strategy independently.

**Why does the RAC have expanded powers in Phase 1?**
Launching a DAO requires a bootstrapping period: assets need to be transferred, infrastructure set up, and operational gaps resolved before the full governance machinery can handle everything. During Phase 1 (the first 12 months), the RAC holds limited delegated authority strictly for this purpose — supporting operational continuity, resolving ambiguities, and facilitating transitions where waiting for a full governance cycle would cause material harm.

This is explicitly temporary. All delegated authority expires after Phase 1. The community can challenge any RAC transitional action via a Governance Process proposal filed within 14 days of disclosure.

**When does Phase 1 end and how does Phase 2 begin?**
Phase 1 lasts approximately 12 months. To enter Phase 2, the DAO must pass a Governance Process proposal (≥60% approval, ≥7% quorum) confirming that the Phase 1 completion criteria are substantially met. There is no automatic transition — the community must actively vote to move forward. The DAO could theoretically extend Phase 1 if it is not satisfied with readiness for Phase 2.

**What's the difference between Tier 1, Tier 2, and Tier 3 policies?**
Tiers describe *enforceability status*, not importance:
- **Tier 1** — fully active and enforceable from Day 1 of Phase 1. These are the foundational rules.
- **Tier 2** — published and expected to be followed in spirit from launch, but become formally enforceable (under dispute resolution and sanctions) only after a community governance vote. Each has a target approval date in Year 1.
- **Tier 3** — activate when triggered by need. Currently only the Smart Contract Audit Policy, which activates before any governance contract deployment is proposed.

Tiers are about activation status. Phases are about how much operational complexity and RAC delegation is in play. They are separate taxonomies.

**All RAC actions during Phase 1 are reported where?**
All RAC actions must be publicly reported to the DAO governance forum within 72 hours of the action being taken. Each report must include the action taken, justification, which members voted, and the outcome.
→ See: [Transition Governance Framework §8](Transition/Transition-Governance-Framework.md)

---

## About Integrity & Disputes

**What do I do if I see a Code of Conduct violation?**
During Phase 1, the primary escalation paths are via the Dispute Resolution process (if the violation is between parties in the DAO) or by raising the matter with the RAC. The Ethics Reporting Policy (Tier 2, target formal approval Month 4), when formally active, will provide a structured reporting channel with whistleblower protections.
→ See: [Governance-Processes/Core/Code-of-Conduct.md](Governance-Processes/Core/Code-of-Conduct.md), [Governance-Processes/System-Integrity/Dispute-Resolution-Arbitration-Policy.md](Governance-Processes/System-Integrity/Dispute-Resolution-Arbitration-Policy.md)

**What is a conflict of interest and what must I do about it?**
A conflict of interest exists when your personal, financial, or professional interests could improperly influence — or appear to influence — your exercise of DAO authority. If you hold a covered role (RAC member, Authorized Signer, Working Group Steward), you must:
1. Submit a standing disclosure when you take the role, listing all relevant financial interests, affiliations, and relationships
2. Update your disclosure within 14 days of any material change
3. Declare any conflict at the transaction level before participating in a specific decision
4. Recuse yourself from decisions where a material conflict exists

Ordinary token holders are not subject to mandatory disclosure, but are encouraged to act in the DAO's best interest.
→ See: [Governance-Processes/Roles/Conflict-of-Interest-Policy.md](Governance-Processes/Roles/Conflict-of-Interest-Policy.md)

**What if I believe an RAC emergency action was wrong?**
The community has a structured path to challenge it:
1. The RAC must publish full disclosure within 48 hours of the emergency action
2. A formal DAO review is scheduled within 7 days of disclosure
3. The DAO vote on ratification concludes within 14 days of the review opening
4. The community may ratify (no further consequence), reverse the action where possible, or impose consequences including RAC member removal

Additionally, any RAC transitional action under Phase 1 delegation can be challenged via a Governance Process proposal filed within 14 days of disclosure. If passed, the DAO's decision supersedes the RAC action.
→ See: [Emergency & Safeguards Policy §10](Governance-Processes/Core/Emergency-and-Safeguards-Policy.md), [Transition Governance Framework §6.2](Transition/Transition-Governance-Framework.md)

**What is the dispute resolution process?**
The DAO has a four-level escalation structure:
- **Level 1** — Direct resolution between the parties (3–5 days)
- **Level 2** — Working Group mediation (5–7 days)
- **Level 3** — RAC review and determination (5–7 days)
- **Level 4** — Full DAO arbitration via governance vote

Total maximum escalation time is 21 days. The dispute resolution path is not the same as the veto mechanism (which applies specifically to post-vote rule violations). Disputes about conduct, role behaviour, execution failures, or process disagreements use the dispute resolution path.
→ See: [Governance-Processes/System-Integrity/Dispute-Resolution-Arbitration-Policy.md](Governance-Processes/System-Integrity/Dispute-Resolution-Arbitration-Policy.md), [DAO Parameters Registry §6C](Parameters/DAO-Parameters-Registry.md)

**What if a majority of RAC members have a conflict on the same matter?**
If a conflict affects a majority of RAC members on a given matter, it must be escalated directly to a community governance vote per the Dispute Resolution & Arbitration Policy. No conflicted majority can adjudicate on matters where they have a personal interest.
→ See: [Conflict of Interest Policy §8](Governance-Processes/Roles/Conflict-of-Interest-Policy.md)

**Can the DAO remove a RAC member, Authorized Signer, or Working Group Steward?**
Yes. Any role holder can be removed via a governance vote. The removal vote threshold is ≥50% YES. Grounds for removal include misconduct, sustained inactivity (the threshold is 14 days of unexcused absence), or breach of governance obligations. The elections and role governance policy defines the full process.
→ See: [Governance-Processes/Roles/Election-and-Role-Governance-Policy.md](Governance-Processes/Roles/Election-and-Role-Governance-Policy.md), [DAO Parameters Registry §6B](Parameters/DAO-Parameters-Registry.md)

---

*For the complete document index, see [Supporting Materials / governance-body-intro.md](Supporting-Materials/governance-body-intro.md).*
