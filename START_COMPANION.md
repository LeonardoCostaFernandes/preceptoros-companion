# Start as a Companion — with your own external agent

**Status: public guide to the existing docs-only door.** This is not permission to connect a node, grant agent capabilities or appear live in OpenWorld. The signed [CONTRACT.md](CONTRACT.md), [GROUNDTRUTH.md](GROUNDTRUTH.md), [GUIDE.md](GUIDE.md) and [CONTRIBUTING.md](CONTRIBUTING.md) take precedence.

A Companion is a **person with their own project and tools**. The house reads only what that person chooses to declare and measure, never the project's private code or signing keys. External agents may help prepare proposals, but never sign or publish on a person's behalf.

## Step 1 · Get the app or use the manual door

Open [Get the app](https://preceptoros.org/get-the-app/) and choose your device. An available download is not proof of a fully tested independent installation.

- **Linux:** an installer is offered; the APP's isolated-home source smoke was measured, but not an independent collaborator's complete install.
- **Windows:** an installer is offered; **NO_DATA(windows_installer_E2E_unverified)**.
- **Android:** the linked APK is an **OpenWorld Trusted Web Activity**, not the base AI APP; **NO_DATA(android_base_app_not_published)**.
- **Your model and tools:** you may use your own agent, local model or external provider. **Hexelion is not required**. Do not provide the house with private endpoint addresses or credentials.

If your installed APP has **Settings → Node identity → Join as a Companion**, its export prepares a local draft only. If this feature is absent, follow the same steps manually. No APP version, installer or website publication is attested by this guide.

## Step 2 · Prepare only public facts

Choose your companion folder slug (1–24 lowercase letters, digits or hyphens, beginning with a letter or digit). Prepare the project name, who it serves, what it solves, its stack and what you can demonstrate. Every reported measurement needs **a command, a date, and a machine**. An unmeasured result must be **NO_DATA(cause)**, never a fabricated PASS.

Keep secrets, private memory, access tokens, passwords, internal addresses and private Ed25519 keys out of the handoff, the agent's transcript and GitHub.

## Step 3 · Give the external agent a bounded brief

Copy this prompt into an agent you choose, substituting your own companion slug and *public* project facts:

> **Companion onboarding · proposal only.** Read the public preceptoros-companion repository's GROUNDTRUTH.md, GUIDE.md, CONTRIBUTING.md, CONTRACT.md and AGENT_CARD.md before editing. Help me prepare **only** companions/MY-SLUG/DECLARATION.md and companions/MY-SLUG/STATE.md based on the project facts that I provide. Use the existing companions/template examples. Do not invent measurements, dates, hardware, signatures or identity; say NO_DATA with a concrete cause. Do not copy secrets, request access to private repositories, authorize actions, open network connections, sign, merge, deploy, provision keys or submit a PR in my name. Show me the complete diff and evidence first. I will review and submit a docs-only PR titled HITL from my fork on branch contrib/MY-SLUG/declaration. A declared agent card is **not** authentication, permission or a working connector. Acceptance of this PR is **not** automatic OpenWorld publication.

The human may refuse or revise the draft. An external agent may suggest measurements but must not present unexecuted tests as completed.

## Step 4 · Human-reviewed declaration

1. Fork [preceptoros-companion](https://github.com/piskyRpapalo/preceptoros-companion) using your own GitHub account. The house does **not** need your account token.
2. Create a branch in your fork called **contrib/MY-SLUG/declaration**. Replace MY-SLUG with your slug.
3. Copy [companions/template/DECLARATION.md](companions/template/DECLARATION.md) and [companions/template/STATE.md](companions/template/STATE.md) into your own **companions/MY-SLUG/** directory. Keep them human-authored.
4. Review the diff, measurements, dates and machine descriptions. For hardware outside the rack, explicitly record **NO_DATA(outside_machine_no_rack_identity)** rather than invent a fleet identity.
5. Open a **docs-only pull request** into this repository, titled **HITL · Companion MY-SLUG declaration**. You can do this in GitHub's browser without sharing credentials with an AI.

If you later propose a companion agent, read [AGENT_CARD.md](AGENT_CARD.md) and [agent-card.schema.json](agent-card.schema.json). **F0 remains PROPOSED**. A card requests capabilities but **does not authenticate the agent or grant Talk, Lab or Notebook access**. No real agent can join without a separate key and the hosting node's human-approved, revocable grant.

## One-building proposal · Nexo (17 November 2026)

The scope is deliberately simple: **one Companion → one Nexo building**. The previous multi-building layout of Node 0 is not the collaborator's deployment template. A human may choose any local or external agent; only their approved **public** sources belong in the proposed knowledge file. This does not authorize retrieval of a private repository or a network port.

Copy DECLARATION.md and STATE.md, and additionally fill in knowledge.md and defense.md using the templates under companions/template/. The proposed BUILDING.json is a machine-readable declaration with count 1, never a live deployment ticket. Your agent may prepare the files in your own Companion folder, but the human reviews all public content.

After preparing your fork's docs-only PR, you may open the [architect review request](https://github.com/piskyRpapalo/preceptoros-companion/issues/new) and mention @piskyRpapalo. This is a public GitHub Issue, and it is NOT sent until you confirm Submit. GitHub account access, notification delivery, owner review, identity approval and Web deployment are separate: NO_DATA(external_submit_or_notification_not_verified) until measured.

A future Deploy one Nexo button may request a signed deployment only after the architect accepts the declaration and validates the node identity, source references and revocable permissions. No implementation or deployment is asserted by this template. The expiry of a visitor's temporary occupation must return control to NPC; it never transfers permanent ownership.

## Step 5 · Distinguish the three states

| State | Measured fact | Not implied |
| --- | --- | --- |
| **DRAFT_ONLY** | The human can inspect a local declaration draft | No PR, grant or public listing |
| **DECLARATION_IN_REVIEW** | A docs-only PR has been submitted by the person | No trusted agent, territory or listing |
| **DECLARED** | Maintainers have accepted a declaration under the proper human sign-off | No live node or automatically published OpenWorld project |

**OpenWorld has another gate:** the host's terms of use must be accepted; node identity and messages require real Ed25519 authentication; network data must follow the signed **atlas.sobre/1** packet contract (strict UTF-8, fewer than 1,024 bytes). The web remains a static renderer with zero hidden requests on load. Until independently measured, the honest state is **NO_DATA(world_publication_not_verified)**.

Acho, the visual status and the machine-readable receipt must report the **same state and cause**. An agent's self-reported completion without a verified receipt is never a completed operation.

## Acceptance still outstanding

The independent **download → install → draft with external agent → human PR → accepted declaration → verified OpenWorld project** chain remains **NO_DATA(external_companion_end_to_end_not_exercised)**. The next true acceptance run must use a collaborator's fresh HOME, no Hexelion dependency, a real docs-only PR under that person's control, and a separately authenticated public projection. A simulated PR or signed project cannot replace those observations.
