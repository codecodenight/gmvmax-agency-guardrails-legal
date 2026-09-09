# Hosted Legal Disclaimer — gmvmax-agency-guardrails

**Effective date:** 2026-09-09

---

## What this skill is

`gmvmax-agency-guardrails` is **operating procedure**: a set of read-before-write checks,
proposal formats, approval rules, and post-write verification steps for TikTok GMV Max
write actions, together with a reference knowledge base of GMV Max actions whose
consequences are not obvious from their names.

## What this skill is not

1. **It is not a technical control and cannot enforce anything.** A skill is instruction-layer
   content. It cannot prevent a misbehaving or misconfigured agent from calling a write tool,
   and it does not sit between the agent and the platform API. Anyone relying on this skill
   as a safety mechanism must keep **approval authority with a human** and, where stronger
   assurance is required, implement enforcement in their own infrastructure.
2. **It is not financial, legal, tax, or advertising-compliance advice.** Budget, bid, and
   authorization decisions are commercial decisions belonging to the account operator.
3. **It is not a guarantee of platform behavior.** The loss-heavy-action knowledge in
   `references/irreversible-actions.md` reflects behavior observed on the TikTok advertising
   platform and its MCP tool surface **as of 2026-08 (full-disclosure mode)**. Platform
   semantics, tool availability, field meanings, and review rules change without notice.
   Verify against current official TikTok documentation before relying on any specific claim.

## Responsibility for outcomes

**The operator of the advertising account is solely responsible for every change made to
that account**, including changes proposed, described, or carried out while this skill is
active. This includes, without limitation: budget and bid changes, creative additions and
removals, session creation and modification, authorization transfers, campaign pauses, and
any resulting advertising spend, lost delivery, lost historical data, or lost authorization.

The authors of this skill accept no liability for advertising spend, lost revenue, paused or
deleted campaigns, lost authorizations, or any other direct or indirect loss arising from use
of this skill, to the maximum extent permitted by applicable law. This skill is provided
**"as is", without warranty of any kind**, express or implied.

## Loss-heavy actions

Two actions carry consequences that cannot be undone, or can be undone only after the
damage has occurred:

- exclusive shop authorization transfer (`gmv_max_exclusive_authorization_create`)
- Creative Boost session deletion (`campaign_gmv_max_session_delete`)

**This skill never calls these two write tools — under any instruction, and regardless of
any approval given.** (This matches `remote_mcp_tools_never_called` in `skill.json`; the two
declarations are kept in sync.) What the skill produces instead is a risk briefing — the
named, concrete consequences: which campaigns will pause, what is lost permanently — and a
handoff for the human to complete the action on the platform side. After completion, the
skill can offer read-only verification of what actually happened.

A candidate execution protocol for these actions exists in
`references/irreversible-actions.md`, explicitly marked **ROADMAP / NON-EXECUTABLE IN v0.1**.
It is design documentation, not behavior of this version, and this disclaimer does not
extend to any future version in which it might be enabled.

The briefing exists because the platform UI performs these actions with no equivalent
warning of their side effects. That comparison is a statement about information available to
the operator, not a warranty — see *Responsibility for outcomes* above, which applies to
these actions in full.

## Credentials and data

This skill **never asks for, stores, transmits, or logs TikTok access tokens**. Authentication
is handled entirely by the agent platform or MCP host via OAuth. This skill does not collect,
retain, or transmit advertiser data, client identities, financial records, or account
performance data to the authors or to any third party.

## Reporting a problem

If you find a factual error in the reference material — in particular, a claim about
irreversible behavior that no longer matches platform behavior — please report it to the
contact address below so it can be corrected.

---

- **Publisher:** Global Trade
- **Contact:** nichao@hzglobaltrade.com
- **Version:** 0.1.0
- **Applies to:** `gmvmax-agency-guardrails` and all files distributed with it
