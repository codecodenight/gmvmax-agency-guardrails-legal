---
title: Disclaimer and scope
---

# Disclaimer and scope

**Publisher:** HK XINGLIAN LIMITED

**Contact:** nichao@hzglobaltrade.com

**Effective date:** 2026-10-02

## Applicability and publisher identity

The following read-only provisions apply only to these six read-only instruction packages and their included files:

- `tiktok-shop-gmv-max-report-comparison-check`
- `tiktok-shop-seller-cost-what-if`
- `tiktok-shop-gmv-max-authorization-precheck`
- `tiktok-shop-creative-evidence-checklist`
- `tiktok-shop-product-spend-status-review`
- `tiktok-ads-handoff-checklist`

It does not apply to other packages. HK XINGLIAN LIMITED is an independent third-party publisher. These skills are not TikTok or TikTok for Business products, and the publisher is not affiliated with either in relation to these skills. References to TikTok and TikTok for Business identify the third-party services or sources discussed. The referenced names and marks remain the property of their respective owners. These packages are independently published by HK XINGLIAN LIMITED and are not sponsored, endorsed or certified by TikTok or TikTok for Business.

## What the skills do and do not do

The skills organize official TikTok for Business MCP returns or user-provided records within the user's selected scope. They distinguish supplied or observed records, explicitly identified calculations, missing evidence and, where relevant, conditional rules from cited TikTok sources. User-provided records are not evidence that a live platform read occurred. Missing or unqueried records are not zero, and unconfirmed information must not be presented as established fact.

The skills do not write to or change the platform, carry out authorization changes, or execute other platform changes on the user's behalf. User approval does not change this read-only scope. The instructions and local calculation helpers are not technical enforcement controls: they cannot prevent a host or agent from misusing other tools. They do not establish complete permissions or available funds or credit.

These skills provide informational reviews and conditional calculations, not financial, legal, tax or advertising-compliance advice. Do not treat an output as professional clearance or as the sole basis for a decision. Verify material facts, current platform requirements and any advice needed from appropriately qualified advisers before acting.

## Limits of each review

- **`tiktok-shop-gmv-max-report-comparison-check`:** Compares two selected reports' scope, dates, timezones, currencies, metric definitions and page coverage. Supported same-scope, same-currency figures may be recomputed when local execution and evidence permit. This is not a diagnosis of performance changes, proof of complete attribution settings, or proof of collected revenue, profit or incremental advertising effects.
- **`tiktok-shop-seller-cost-what-if`:** Calculates a per-fulfilled-order, before-ad contribution scenario from the seller's confirmed revenue, non-ad costs and refund allowance. Seller inputs and illustrative assumptions remain separate from read-only ad-report observations. The scenario is not measured actual profit, an audit, incremental sales or a budget recommendation. It does not establish that scaling is appropriate or guarantee break-even, returns or ROI.
- **`tiktok-shop-gmv-max-authorization-precheck`:** Separates dated authorization observations, visible campaigns and conditional TikTok rules for the selected shop, accounts and proposed workflow. It neither performs nor tests a switch and does not establish its actual outcome or safe migration. Unseen campaigns, unchecked occupancy and undocumented object-transfer, recovery, deletion or restart outcomes remain unconfirmed; a cited rule is not proof that its trigger or consequence occurred in the user's account.
- **`tiktok-shop-creative-evidence-checklist`:** Organizes explicit post, identity and product links, availability and occupancy observations, request scope, source dates and missing records. It does not establish complete authorization, copyright clearance, present ability to advertise the creative or an unnamed occupant's identity. An absent record is not proof that authorization is absent or a post was deleted.
- **`tiktok-shop-product-spend-status-review`:** Places reported product-level spend and orders beside a separately timed product-status, recorded-quantity and ad-occupancy snapshot. It does not establish spending during unavailability, ongoing spend, the cause of unavailability or fulfillable stock. Recorded quantity is not a SKU-level inventory assurance.
- **`tiktok-ads-handoff-checklist`:** Organizes account context, visible shops and GMV Max campaigns within selected accounts, keeping source dates, query coverage and unchecked accounts visible. It does not establish a complete asset inventory, ownership responsibility, full permissions or a financial audit. Complete coverage of a particular request is not complete company-wide coverage.

## Sources, responsibility and warranties

A record returned by a platform or supplied by a user is not a guarantee of its accuracy, completeness or clearance for reuse. Provide only records you are entitled to use and disclose for the selected task. These skills do not grant platform access, intellectual-property rights or permission to reuse third-party content.

Platform terms, policies, tools and permissions may change. Check the terms and requirements applicable to the services you actually use before acting. These documents do not amend those terms or authorize activity they prohibit. Observations describe their recorded scope and time, not necessarily the present state. Conditional TikTok rules describe only their stated conditions and consequences; they do not establish account-specific outcomes. Local helper execution is subject to the host's capabilities and does not establish compatibility with every host.

The user remains responsible for selecting the scope, checking supplied records and current sources, and making any subsequent decisions or platform changes outside these skills. The skills are provided "as is", without warranties of accuracy, completeness, fitness for a particular purpose, platform behavior, approval, safety or business results. These exclusions apply only to the extent permitted by applicable law. Nothing in these documents excludes or restricts liability for death or personal injury caused by negligence, fraud or fraudulent misrepresentation, or any other liability, right or remedy that cannot lawfully be excluded or restricted.

For questions or factual corrections, contact nichao@hzglobaltrade.com. Do not send credentials or business records to the publisher.

## Provisions only for gmvmax-agency-guardrails

This section applies only to `gmvmax-agency-guardrails` and its included files. The publisher identity and applicable-law reservations stated in this document also apply to this package. The six packages listed above remain read-only; this section does not enable writes through them.

### Operating procedure, not technical enforcement

`gmvmax-agency-guardrails` provides operating procedure for TikTok GMV Max write actions: read-before-write checks, proposal formats, explicit human approval for each specific action, and post-write read-back verification, together with reference material on loss-heavy actions. Approval is per action, not a standing authorization. Its instructions cover the same action semantics when a generic campaign tool is used for a GMV Max object.

This package is instruction-layer content, not a technical control. It cannot prevent a misbehaving or misconfigured agent from calling a write tool and does not sit between the agent and the platform API. Keep approval authority with a human; where stronger assurance is required, implement enforcement in your own infrastructure. The package does not establish available funds or credit, guarantee safe production writes, or provide financial, legal, tax or advertising-compliance advice. Budget, bid and authorization decisions remain commercial decisions for the account operator.

### Responsibility, platform changes and loss-heavy actions

The account operator remains responsible for changes to the account, including budget and bid changes, creative additions and removals, session changes, authorization changes, campaign pauses and their consequences.

The authors of this skill accept no liability for advertising spend, lost revenue, paused or
deleted campaigns, lost authorizations, or any other direct or indirect loss arising from use
of this skill, to the maximum extent permitted by applicable law. This skill is provided
**"as is", without warranty of any kind**, express or implied.

Any exclusion is subject to the applicable-law reservations above; this section does not establish that an exclusion is enforceable against every user.

The loss-heavy-action reference material describes historical platform and MCP behavior as of 2026-08 in full-disclosure mode, not a verification of present behavior. Platform semantics, tool availability, fields and review rules may change. Verify current official TikTok documentation before relying on a specific claim; a general rule is not proof of what happened in a particular account.

The v0.1 instructions designate exclusive shop authorization transfer (`gmv_max_exclusive_authorization_create`) and Creative Boost session deletion (`campaign_gmv_max_session_delete`) as briefing-only actions: they instruct the agent never to call those two write tools under any instruction or approval. Instead, the deliverable is a risk briefing and human handoff for platform-side completion, followed, where requested, by read-only verification. This instruction is not a physical prevention guarantee or proof that a platform action is safe. The candidate protocol in the package's `references/irreversible-actions.md`, marked ROADMAP / NON-EXECUTABLE IN v0.1, is design documentation, not active behavior of this version; this section does not extend to a future version that enables it.

### Credentials and factual corrections

The package's instructions do not ask for access tokens and direct authentication through the user's agent platform or MCP host OAuth. The package is not a publisher-operated collection endpoint. This does not mean the user's host, model or connected services do not process data; see the privacy policy for the distinction.

For factual errors in the reference material, particularly historical claims that no longer match current platform behavior, contact nichao@hzglobaltrade.com. Do not send credentials or business records.

These documents do not designate a governing law or an exclusive forum for disputes. Applicable law and jurisdiction are determined under the relevant legal rules.

[Legal information](index.html) | [Privacy policy](privacy-policy.html)
